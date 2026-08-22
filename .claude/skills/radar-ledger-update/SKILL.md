---
name: radar-ledger-update
description: |
  Safely update TRENDS.md (the AI Radar ledger): append evidence, move stages, manage observation_queue, source_rotation and strategy_notes without breaking the file contract. Use every time TRENDS.md is edited, before committing radar updates, and when promoting or archiving trends.
---

# Update the ledger safely

`TRENDS.md` is the single source of truth and later sessions parse it. The
structure is a contract.

## File contract (do not change)

HEALED 2026-W34: this section previously described a sibling radar's file
contract (an `# AI Radar` header, `### [id: slug-NNN]` trend blocks with an
`alias` field, a standalone `## observation_queue` H2) that never matched this
repo's actual `TRENDS.md`. Flagged 2026-08-17 (daily), healed this weekly per
the skill-maintenance policy. The contract below now matches the real,
established structure (2000+ lines, many prior sessions).

- Header: `# Trend ledger — Math-Physics Radar`, then `Last updated: YYYY-MM-DD`,
  then the stage legend.
- Sections, in this order: `## Active trends` (trend blocks, followed directly —
  no sub-header — by the unheaded `observation_queue` block, introduced by the
  line "Signals not yet promoted to a trend..."), `## source_rotation`,
  `## strategy_notes`, `## study_shelf`, `## calibration`. There is NO standalone
  `## observation_queue` H2 — the queue lives inside `## Active trends`; link to
  it as `TRENDS.md#observation_queue` by convention only (README practice), not
  a real anchor.
- `## source_rotation` and `## calibration` are POINTER stubs only: their real
  append-only content lives in `logs/source_rotation.md` and `logs/calibration.md`
  respectively. Keep the two stub headers (the section order is the contract) but
  NEVER inline log lines back into TRENDS.md — appends go to the `logs/` files.
- Trend block: `### Title` (no id/slug, no `alias` field) with fields `stage`,
  `confidence`, `first_seen`, `last_evidence` on one `- stage: ... | confidence:
  ... | first_seen: ... | last_evidence: ...` line, then `- what:`, `- evidence:`
  (list), `- notes:` (a running dated log of every session's recalibration of
  this trend, append-only within the trend).
- Evidence line: `  - YYYY-MM-DD — URL — one line of context` (nested two-space
  indent under `- evidence:`).
- Queue item: `- YYYY-MM-DD — description/URL — context` at the top level of the
  unheaded queue block (not indented).

## Rules

- Match findings to existing trends by title/topic before creating a new trend
  (there is no id/alias field to match on). New trends start at `seed` or
  `emerging`.
- ROUTE a captured primary, don't default to "queue it": (a) if it lands on an
  EXISTING trend's axis, append it as EVIDENCE there — a single primary suffices
  for an existing trend; the ≥3-source bar is only for CREATING a trend; (b) if
  the queue now holds ≥3 independent groups on one untracked sub-theme, promote
  that cluster to a `seed` trend; (c) else it stays a queue item. Leaving an
  on-axis primary in the queue (hoarding evidence) or a named primary in report
  prose only is a routing failure.
- Max 10 evidence items per trend — drop the oldest. Keep `last_evidence` equal
  to the newest evidence date.
- Stage moves: at most ONE stage up per trend per day, only on new independent
  evidence, justified in `notes`. Demotions are always allowed. DORMANCY/ARCHIVE
  windows follow the curator-set DOMAIN CADENCE (AGENTS.md § Domain cadence — this
  is a SLOW field, months not days): **60+ days** without evidence → `dormant`; at
  **120+ days** the weekly pass moves the entry to `ARCHIVE.md` as a one-line
  post-mortem. (NOT the AI-default 21/45 — a months-old `last_evidence` is normal
  for a live topic here; do NOT demote/archive merely for a quiet stretch. A
  threshold change retroactively fixes trends mis-staged under an old window —
  reconcile every already-dormant/archived entry against the CURRENT window first.)
- Pinned trends (`pinned: true`): NEVER auto-archived, no matter how long
  without evidence — they are the curator's standing-watch axes. They still
  follow the normal stage rules, INCLUDING going `dormant` when quiet (the
  ledger stays truthful about activity); they simply never leave the board.
  Only the curator adds/removes a pin (or the agent proposes it via amendment).
- `observation_queue` items are dated and marked "unverified" unless opened. It
  is a WORKING SET (signals pending verification), not a knowledge store, but the
  DOMAIN CADENCE (AGENTS.md § Domain cadence) governs its size: SOFT cap **~40**
  live items (NOT the AI-default ~25), and intake here is LOW, so below-bar items
  should PERSIST — a math result stays relevant for MONTHS. Do NOT run a per-session
  cap-driven burndown and do NOT prune a slow, low-volume queue just to hit a number.
  Staleness is at **~60 days** (not 14): the weekly pass verifies items older than
  ~60 days and either promotes, drops (one-line reason), or re-dates. Resolve the
  oldest ONLY when GENUINELY over the soft cap, and even then target the lowest tier
  (never-opened title-only intake), never verified results. Items leave ONLY by
  resolution: promoted to a trend (the signal is captured there) or dropped with a
  one-line reason in the day's/week's report (write-once, permanent). NEVER silently
  delete — every removal is a promotion or a recorded drop, so shrinking the queue
  loses no knowledge. Re-date an item only if it is genuinely still worth watching.
- Append one dated line per session to `logs/source_rotation.md` (the coverage
  log; not the TRENDS.md stub). Append dated corrections to the `strategy_notes`
  section of TRENDS.md; never delete curator entries.
- `study_shelf`: newest first, format `date — [name](url) — one line of why`;
  single-artifact items allowed (the trend bar does not apply), opened primary
  sources only.
- `calibration` (now `logs/calibration.md`) is append-only and written by weekly
  runs only (see the `radar-self-eval` skill); daily runs never touch it.
- Update the `Last updated` line. Keep everything in English.

## Validate before commit

```bash
grep -n '^## ' TRENDS.md
# expected, in order: Active trends, source_rotation, strategy_notes, study_shelf, calibration
# (no standalone observation_queue heading — it lives inside Active trends)
grep -c '^### ' TRENDS.md                # trend count matches expectations
grep -nE '^  - [0-9]{4}-[0-9]{2}-[0-9]{2} — ' TRENDS.md | head -3   # evidence format
grep -n '^Last updated:' TRENDS.md       # date is today
# the two externalized logs must exist and only grow (append-only):
test -f logs/source_rotation.md && tail -1 logs/source_rotation.md | head -c 80
test -f logs/calibration.md && tail -1 logs/calibration.md | head -c 80
# TRENDS.md must NOT have regrown a log body (the stubs stay one-line pointers):
awk '/^## source_rotation/{n=0} /^## strategy_notes/{print "rotation stub lines:", n} {n++}' TRENDS.md
```

If a check fails, fix the file before committing. Commit and push per the
conventions in AGENTS.md.
