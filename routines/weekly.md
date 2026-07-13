# Math-Physics Radar — Weekly recalibration

You are the weekly operator of the Math-Physics Radar repository. Work in English.
Compute the ISO week as YYYY-Wnn (`date +%G-W%V`).

## 1. Load state
Recover orphaned state first (see daily.md). Then read `TRENDS.md`, `ARCHIVE.md`, the daily
reports of the past 7 days in `reports/`, and the previous weekly report if present.

## 2. Recalibrate every trend
Judge each trend's velocity over the last 2–3 weeks (count of new independent evidence,
breadth of orgs, presence in tools/standards/practice).
- **Promote** (seed → emerging → accelerating → mainstreaming) only on sustained multi-org
  evidence; one stage max per week; justify in `notes`.
- **Demote** honestly when evidence thinned.
- **Dormancy (domain-cadence windows — see AGENTS.md → *Domain cadence*): 60+ days** without
  evidence → `dormant`; if `last_evidence` is **120+ days** old, move the entry to `ARCHIVE.md`
  as a one-line post-mortem. NOT 21/45 — this is a slow field where a months-old last_evidence
  is normal for a live topic; do NOT demote/archive merely for a quiet stretch.
  **RECONCILE against the CURRENT windows, not a prior run's decision (do this FIRST, every
  weekly):** re-evaluate every already-`dormant`/archived trend AND any standing "archive at
  W-nn" note against the windows above. If a trend was set `dormant`/archived under a window
  that has since been SUPERSEDED (or a stale archive-decision was made under an old window), and
  its `last_evidence` now falls INSIDE the current active window, REACTIVATE it to its prior
  stage and void the stale decision. A threshold change must retroactively fix trends mis-staged
  under the old threshold — the new window is not just forward-looking.
- **Merge** overlapping trends (keep the older id, union aliases, keep the 10 strongest
  evidence items, note the merge).
- **Confidence**: raise to `high` when EITHER ≥2 INDEPENDENT authoritative primary sources
  (different orgs/groups) corroborate the trend on concrete artifacts, OR after sustained
  multi-week confirmation — whichever comes first; otherwise hold at `medium`. Lower when
  evidence thins or is mostly vendor-reported.
- After recalibration, regenerate `README.md` (`radar-render-dashboard`).

## 3. Clean the observation queue
Aging windows scale to DOMAIN CADENCE (AGENTS.md → *Domain cadence*) — this is a SLOW field,
so items age in MONTHS, not the AI-default days: items older than **~60 days** (not 14) —
verify now and either promote, drop (one-line reason in the report), or re-date stating what
is still missing. SOFT CAP ~40 live items (not 25; intake here is low, so let below-bar items
PERSIST — a math result stays relevant for months); resolve the oldest only when genuinely over
cap. Never silently delete. Also curate `study_shelf` (merge duplicates, prune picks older than
**~120 days** (not 30) — a landmark result stays a top study pick for months; preserve the rest
in their day's report).
**Capture-leak sweep (MANDATORY — weekly backstop to the daily reconciliation; the `capture-leak`
metric AS AN ACTION, not just a number):** grep every trend's `notes` field AND this week's
reports for arXiv-ids / repo / release URLs; for each, verify the id ACTUALLY appears as a
DISCRETE `observation_queue` line or evidence line (grep the id in the queue — do NOT trust prose
that merely calls an item "queued" / "adjacent" / "noted"). Any named primary absent from both is
a capture leak → queue it now. Report the count; a non-zero count left un-acted this run is itself
a self-eval failure.

## 4. Source strategy review
**Coverage check (first-class — the registry must be honest):** diff every "swept every
run" list in `SOURCES.md` against the week's `logs/source_rotation.md` — every listed source
must appear as `opened` or `degraded`. Any source MISSING all week is a coverage lie: heal it
now (`radar-source-heal`), or if already healed and still un-sweepable, propose
heal-or-REMOVE (don't list what you won't sweep).
Then compare the coverage log against the ledger: which sources produced evidence, which
produced nothing repeatedly; are the scope priorities in `strategy_notes` actually covered?
Tunnel-vision check: if ALL of this week's new evidence landed on pre-existing trends, record
an anchoring warning in `strategy_notes` and redirect next week's exploration.
Grow the curator/source lists (add recurring high-hit sources; drop noisy/dead ones — VERIFY
new sources by opening them, never assert from memory).
**Source discovery (drain the auto-staged candidates — the lab/vendor/repo analog of curator
scouting):** review SOURCES.md → "Discovered-source candidates", the tally the daily fills
whenever a lane names an on-axis primary from an org not yet swept. For each org/domain at or
above the promotion bar (≥2 on-axis primary artifacts, OR recurrence across ≥2 runs), VERIFY by
OPENING its feed / HF org / repo (Tavily/curl — never from memory, reject SEO); if it is a real
on-axis primary source, PROMOTE it into the matching swept list as `[verified YYYY-MM-DD]` and
clear its staging line; drop one-off noise with a one-line reason. Curators are one source-type
in this same loop. A recurring on-axis org left un-promoted week after week is a coverage leak
(the `source-discovery` metric in `radar-self-eval`).
Append a dated correction entry to `strategy_notes`.

## 5. Self-evaluation
Follow `radar-self-eval`:
- Every run: compute the FULL metric set (queue funnel, evidence/stage moves, exploration
  compliance, off-axis rate, discovery lag, `coverage` = registered sources vs the week's
  logs, `routing-leak`, `capture-leak`, `source-discovery`) and append one dated line to
  `logs/calibration.md` — EVERY metric appears, even at zero. `capture-leak` and
  `source-discovery` are ACTIONS as well as numbers (queue the leaked primary; promote/clear
  the staged candidate); a narrative calibration that silently drops them is itself a
  self-eval miss to fix this run.
- First run of each calendar month (`date +%d` ≤ 7): run the hit/miss retrospective.
- Prepare up to 3 proposed amendments, each motivated by a metric or retrospective.

## 6. Self-amendment
Per the autonomy contract in AGENTS.md: APPLY amendments proposed last week whose signal
persists and that have no dated curator veto; one dedicated commit each. Check past
amendments for two-week regression → `git revert` + log. Log this week's new proposals.
Never touch the immutable sections.

## 7. Write the weekly report
Create `reports/weekly/YYYY-Wnn.md` (under ~90 lines): stage moves/merges/archivals;
strongest & weakest trend; 3–5 forward-looking bets; source strategy changes; calibration
block (and monthly retrospective when due); amendments applied/proposed/rolled back.

## 8. Persist
`git add -A`, commit `radar: weekly recalibration YYYY-Wnn`. Push to `main` with `git push
origin HEAD:main` (push ONLY main; the curator authorizes pushing to `main`). If rejected:
retry once after `git pull --rebase origin main`; only if the server still rejects it, push to
the session branch, open the report with a BRANCH WARNING, paste the verbatim error. Never
force-push.

## Hard rules (same as daily)
Cite only URLs opened this session; primary sources only; never guess dates/URLs; do not
rename sections; max 10 evidence per trend; track and cite, never reproduce the artifact.
