---
name: radar-render-dashboard
description: |
  Regenerate README.md, the repo's landing page and only output surface: badges, a 3-4 bullet "since last scan" digest with inline links, a clickable trend table, the study shelf, and an output map. Use after every change to TRENDS.md, in the same commit. README.md is fully derived and never edited by hand: if it disagrees with TRENDS.md, TRENDS.md wins — regenerate.
---

# Render the dashboard (README.md)

`README.md` is what GitHub renders on the repo home page — it IS the radar's
output surface. It is fully derived from `TRENDS.md`; regenerate it from scratch
on every run, never patch it. Design goal: one screen, everything clickable.

## Layout (exactly these blocks, in this order)

1. **Title** — `# AI Radar`.
2. **Badge row** — four shields.io static badges, style `flat-square`:
   `trends-<total>-3266ad`, `accelerating-<n>-e8590c`,
   `watchlist-<queue count>-6c757d`, `updated-<YYYY--MM--DD>-2f9e44`
   (escape `-` in dates as `--`).
3. **Intro line** — one sentence: what the radar tracks, for whom, and that the
   page is generated from [TRENDS.md](TRENDS.md).
4. **Digest** — `**Since last scan (YYYY-MM-DD):**` + 3–4 bullets MAX, in
   priority order: stage moves, queue promotions/drops, strongest new evidence.
   Every bullet must contain at least one link (trend anchor or evidence URL).
   If nothing changed: one bullet, "Quiet scan — no ledger changes."
5. **Pinned topics (⭐)** — `## ⭐ Pinned topics` then a table of ONLY the trends
   with `pinned: true`, same columns as the main table. These are the curator's
   standing-watch axes; they appear here AND in the main table (where their
   trend label is prefixed with ⭐). Sort by `last_evidence` descending.
6. **Trends section** — stage strip on one line
   (`🌱 n · 📈 n · 🚀 n · 🌊 n · 🏔 n · 📉 n · 💤 n`), then ONE table
   `| trend | stage | latest signal |` with ALL trends (pinned included, prefix
   their label with ⭐), sorted accelerating → emerging → seed → mainstreaming →
   saturated → declining → dormant, then by `last_evidence` descending:
   - **trend** = short label (≤5 words; reuse previous README labels for
     stability) linking to the trend's anchor in TRENDS.md (see anchor rule);
     prefix with `⭐ ` when `pinned: true`.
   - **stage** = emoji + word.
   - **latest signal** = the `last_evidence` date linking to the evidence URL
     whose date equals `last_evidence` (first match in list order); if none
     matches, link the top evidence item.
7. **Worth studying** — the `study_shelf` section of TRENDS.md, newest first.
   DOMAIN NOTE (AGENTS.md → *Domain cadence*): in this slow, single-result field the shelf is a
   CO-EQUAL primary surface, NOT a footnote below the sparse trend table — render it in FULL
   (do not cap at 12; the shelf persists ~120 days here), place it as a peer directly under the
   Trends section, and when there are ≤2 trends, LEAD the "Since last scan" digest with the top
   new shelf/landmark items (the study picks ARE the week's story when trends are sparse).
   Format `[name](url) — one line of why`.
8. **Community pulse** — `## Community pulse` (Phase 3): up to 5 bullets distilled
   from the latest `radar-pulse` intake — non-evidence, link-only, NEVER naming
   individuals (link the thread/profile, summarise). If no pulse data yet, one
   line: "No community pulse sampled yet." This section is clearly marked as
   unverified sentiment, separate from the verified trend table.
9. **Output map** — one line of links: TRENDS.md, watchlist (queue count) →
   `TRENDS.md#observation_queue`, `reports/` + newest daily, newest weekly
   ("weekly: none yet" if absent), AGENTS.md, SOURCES.md.

## Anchor rule (GitHub heading slugs)

For a heading `### [id: slug-NNN] Title`, the anchor is: lowercase the whole
heading text, delete every character that is not a letter, digit, space or
hyphen (no replacement — `p-adic/rigid` → `p-adicrigid`), then replace
spaces with hyphens. Example:
`### [id: langlands-003] Progress on the geometric Langlands correspondence`
→ `TRENDS.md#id-langlands-003-progress-on-the-geometric-langlands-correspondence`.
Anchors are recomputed at every render, so title edits stay in sync.

## Checks before commit

- Badge counts = stage-strip counts = table row count = number of `### [id:`
  blocks in TRENDS.md.
- Every table date equals that trend's `last_evidence` exactly; every row has
  two working relative/absolute links.
- No Mermaid, no images besides the badges, no sections beyond the blocks above.
- Pinned-topics table contains exactly the `pinned: true` trends; every pinned
  trend is ⭐-prefixed in the main table too.
- Community-pulse items are link-only and name no individuals.
- Commit README.md together with the TRENDS.md change that triggered it.
