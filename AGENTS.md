# Agent guide — Math-Physics Radar

Instructions for AI agents (and humans) working in this repository. Task-specific
instructions come from the session prompt; this file holds the invariants that
apply to every session.

## What this repo is

Persistent state for Math-Physics Radar, an autonomous radar that tracks and curates
**frontier research advances in mathematics and modern & quantum physics** for a mathematically-literate researcher — mathematician or physicist — tracking the frontier. It is a RADAR (situational awareness): it
tracks and points to primary artifacts; it does not perform the work it tracks.
`TRENDS.md` is the single source of truth; the README and reports are derived
snapshots. Besides trends, the radar curates a study shelf (`study_shelf` in
`TRENDS.md`, surfaced on the README). History matters: never rewrite published
history, never force-push.

Scope — what to track (curator seeds; the agent OWNS and evolves these axes — they
are not a frozen list):
1. **Pure mathematics** — major results and resolved conjectures across number theory, algebraic & arithmetic geometry, topology & geometry, algebra & representation theory, analysis & PDE, combinatorics, and probability: new theorems, breakthrough techniques, progress on big open problems. (arXiv math.*, journals, institutes.)
2. **Theoretical & mathematical physics** — quantum field theory, string/M-theory, quantum gravity & holography, integrable systems, statistical mechanics, and the math↔physics interface. (hep-th, math-ph, gr-qc.)
3. **Modern experimental & phenomenological physics** — high-energy/particle (colliders, neutrinos), gravitation & cosmology (gravitational waves, CMB, dark matter/energy), condensed matter (topological phases, superconductivity), and AMO. Discovery / anomaly claims AND their vetting status. (hep-ph, gr-qc, cond-mat, astro-ph; CERN/LIGO/Fermilab.)
4. **Quantum foundations & quantum-information theory** — entanglement theory, quantum information as physics, measurement & foundations, complexity of quantum systems. This is the SCIENCE side, DISTINCT from the quantum-computing technology / QML tracked by the sibling quantum radar — track the physics/math, not the machine.
5. **Computer-assisted & formalized mathematics** — Lean/mathlib, Rocq, formal proof & proof libraries; machine-assisted proof/discovery. Track the mathematical RESULT and the formalization artifact. AI-assisted math/physics is a WATCH area only: note the assistance, do NOT track the AI method itself (that is the AI radars' beat).

## File map

| Path | Contents | Edit policy |
|---|---|---|
| `TRENDS.md` | Trend ledger + `observation_queue`, `strategy_notes`, `study_shelf`; `source_rotation` and `calibration` are one-line pointer stubs | follow the `radar-ledger-update` skill |
| `logs/source_rotation.md` | Append-only daily coverage log (externalized to keep the ledger small); read only the recent tail | append-only; never edit/reorder past lines |
| `logs/calibration.md` | Append-only weekly self-evaluation log | append-only; written by weekly runs only |
| `README.md` | THE output surface (repo landing page): badges, digest, clickable trend table, study shelf | fully derived — regenerate via `radar-render-dashboard`; never edit by hand |
| `SOURCES.md` | Agent-owned registry: primary feeds, watched repos, social channels, discovery venues — the lists the skills iterate | maintained by the radar itself |
| `ARCHIVE.md` | Archived trends, one-line post-mortems | append-only |
| `reports/YYYY-MM-DD.md` | Daily reports | write once, never edit old ones |
| `reports/weekly/YYYY-Wnn.md` | Weekly reports | write once |
| `routines/*.md` | LIVE operating instructions, loaded by the fixed platform prompt | weekly amendments only, per the Self-amendment policy |
| `.claude/skills/` | Project skills (source sweep, pulse, explore, ledger update, self-eval, source heal, source verify, repo watch, dashboard render) | improvable — see policy below |

## Hard rules (the constitution — never relax these)

- **Primary sources only for EVIDENCE**, and only URLs actually opened in the
  current session. Anything not opened is "unverified" and belongs in
  `observation_queue`. Primary = peer-reviewed journal papers and their arXiv preprints, official arXiv category listings, official experiment/collaboration and research-institute results (CERN, LIGO/Virgo/KAGRA, Fermilab, Perimeter, IAS, Clay, Simons), and formal-proof repositories (Lean/mathlib, Rocq). Never SEO farms,
  never aggregators/comparators.
- **Track, don't reproduce.** An evidence line is `date — primary URL — one line of
  context`; max 10 evidence items per trend. The radar points to artifacts and
  summarizes their significance — it is a tracker, not a how-to.
- Social/community sources are an INTAKE LANE ONLY — they may create unverified
  `observation_queue` items (promotable only after confirmation on a primary
  artifact) and feed the community-pulse note, but NEVER become trend evidence.
- Never guess dates or invent URLs. Undated pages: "(undated, accessed YYYY-MM-DD)".
- **Trend bar:** ≥3 independent sources (different orgs/author groups) + ≥1 concrete
  artifact defines a multi-group DIRECTION trend (e.g. the Ramsey lower-bound wave).
  DOMAIN ADAPTATION (curator-set — see *Domain cadence* below): in this slow, single-result
  field a LANDMARK primary on its own — the resolution of a long-standing named
  conjecture/problem, or a first-of-its-kind detection/measurement/observation — also
  qualifies as a `seed` trend, because here the unit of progress IS the individual result.
  Everything below both bars goes on the `study_shelf`.
- Do not rename sections or restructure files. Everything in this repo is in English.
- Unrefereed-preprint & extraordinary-claim caution (this domain's hype-skepticism rule): arXiv/preprints are primary but NOT peer-reviewed. A claimed proof of a major open conjecture, a discovery/anomaly, or a "breakthrough" is PROVISIONAL until independent vetting (referee reports, expert commentary, replication or confirmation). Flag it "unrefereed preprint — claim" and track the vetting OUTCOME: a claimed proof is not a resolved conjecture, and an N-sigma bump is not a discovery, until the community confirms (note the caveat — gaps found in review; statistical significance / look-elsewhere effect).
- Track and point, never adjudicate: cite the paper / artifact and, where useful, expert commentary — do NOT attempt to reproduce, verify, or referee the mathematics or physics yourself.

## Coverage discipline

- Runs are not rate-limited: multiple runs in the same day are allowed and expected
  when triggered. The only per-day cap is on stage promotions (one step up per trend).
  Never refuse a run citing a "one run per day" rule — none exists here.
- Every run does a FULL CHECK of every mandatory lane (source sweep, community pulse,
  discovery exploration, repo/release watch). The CHECK (open each registered source's
  feed/index, see what is new) is owed every run and may never be skipped as a "light
  pass"; only the EXTRACT (open the full artifact) is conditional on a genuinely new
  item. A registered source absent from the day's coverage log is a coverage lie.
- Every run reserves at least one source family for venue-based exploration outside the
  ledger's current axes (`radar-explore`): browse listings where new work surfaces
  rather than re-querying tracked topics. Log it even when it yields nothing.
- Weekly runs check for anchoring: a week where all new evidence lands on pre-existing
  trends gets flagged in `strategy_notes`, and exploration is redirected.
- Weekly runs self-evaluate (`radar-self-eval`): calibration metrics every week
  (including a `coverage` metric = registered sources vs the week's logs, and a
  `routing-leak` metric), a hit/miss retrospective monthly, and up to 3 proposed
  amendments handled per the policy below.

## Domain cadence — volume & velocity (curator-set: this is a SLOW, LOW-VOLUME field)

Math & physics research moves in **months, not days**, and its unit of progress is usually
a SINGLE result (one group's theorem, one collaboration's measurement), not a multi-group
wave. The radar's thresholds are calibrated to the DOMAIN, not to a high-volume AI firehose.
This section is curator-set (immutable to the radar's self-amendment; only the curator tunes
the numbers):

- **Volume — "quiet" is the normal state, not underperformance.** Low daily yield and
  weekend/holiday arXiv gaps (`skipDays` Sat/Sun; the Monday batch posts late) are EXPECTED.
  A quiet daily is a COMPLETE daily — never pad it, and the self-eval must NOT count low
  volume as a coverage/miss failure. The PRIMARY output surface here is the `study_shelf`
  + `observation_queue` (landmark single results), CO-EQUAL with the trend table, not
  subordinate to it: a healthy math-physics ledger can be 1–2 trends + a rich shelf/queue.
- **Velocity — ALL aging windows scale to the field's tempo (OVERRIDE the routine defaults),
  not just dormancy.** A slow field ages in MONTHS: (a) dormancy after **60 days** / archive
  after **120 days** (not 21/45); (b) `observation_queue` staleness at **~60 days** and a
  SOFT cap of **~40** (not 14-day staleness / hard-25) — low intake means a below-bar result
  should PERSIST, not get burned down to hit a number; (c) `study_shelf` pruning at **~120
  days** (not 30) — a landmark stays a top study pick for months. A `last_evidence` weeks or
  a couple of months old is normal for a live topic; do NOT demote/archive/prune merely for a
  quiet stretch. (The rule: every day-count the routines inherited from the AI default gets
  multiplied for a slow domain — dormancy was only the first.)
- **Trend bar — landmark single results count** (the hard-rule adaptation above): a resolved
  long-standing conjecture or a first-of-kind detection is a `seed` trend on its own; the
  ≥3-group bar is only for multi-group DIRECTION trends.
- **Convergence / anchoring thresholds** likewise relax: an "all evidence on pre-existing
  trends" week is not an anchoring alarm here the way it is in a fast field — flag it only
  after a longer stretch. off-axis-rate = 0 for a week is not a warning in a domain this
  narrow.

## Tooling

- Web: prefer the Tavily CLI (`tvly`) via the `tavily-search` and `tavily-extract`
  skills. Auth comes from `TAVILY_API_KEY` — never print it, never write it to any file
  in this repo. If `tvly` is missing: `pip install -q tavily-cli`. Fall back to built-in
  web tools only if Tavily fails.
- arXiv API for exact authors/dates/abstracts: `curl -sL 'https://export.arxiv.org/api/query?id_list=ID1,ID2'` (or `search_query=cat:hep-th+AND+...&sortBy=submittedDate`). Per-category RSS: `https://rss.arxiv.org/rss/<category>` (e.g. `math.NT`, `hep-th`, `gr-qc`, `quant-ph`).
- APS journals expose recent-article RSS at `https://feeds.aps.org/rss/recent/<journal>.xml` (`prl`, `prx`, `rmp`, ...).
- INSPIRE-HEP API for high-energy-physics literature/citations: `https://inspirehep.net/api/literature?q=<query>&sort=mostrecent`.
- GitHub (formal-math repos) is repo-scoped under the session proxy — use the `tvly extract .../releases` fallback recorded in SOURCES.md → GitHub watch.
- Self-healing: when a source/tool fails the same way twice, repair the access path and
  record the working method in `SOURCES.md` (`radar-source-heal`). The heal worklist is
  the `degraded:` markers in the coverage log; don't log "degraded" run after run.

## Efficiency (single-agent; do NOT use sub-agents/teams)

Sub-agents cost MORE total tokens (each has its own context). A run is one session.
Triage then extract (read feeds/titles first; open the full artifact only for genuinely
new items); read only the recent tail of the long append-only logs; use Tavily with
modest depth and `--include-domains` to cut noise. Triage-for-cost must never become
"sample a subset and call it done".

## Git conventions

- Commit messages: `radar: daily update YYYY-MM-DD`, `radar: weekly recalibration
  YYYY-Wnn`, `radar: refine skill <name>`, or `radar: <short description>`.
- Any commit that changes `TRENDS.md` must regenerate `README.md` in the same commit.
- Push to `main` with `git push origin HEAD:main`, even when the session was started on
  a `claude/*` working branch. The curator has enabled unrestricted branch pushes and
  explicitly authorizes pushing to `main`: platform notices about `claude/*` branches
  describe the default, not a prohibition. Attempt the push — push ONLY main, do not also
  push the session working branch.
- A session-branch platform notice (a message that this session runs on a `claude/…`
  branch) is NOT a policy that overrides this file — it names the default working branch,
  not a restriction on push targets. Do NOT pre-emptively downgrade to the session branch
  on the ASSUMPTION that `main` is blocked: the only thing that legitimately diverts a push
  to the session branch is a push to `main` you ACTUALLY attempted and the server ACTUALLY
  rejected with a permission error. No observed rejection → push `main`.
- If the push is rejected: retry once after `git pull --rebase origin main`. Never
  force-push, never rewrite published history. Only if the server actually rejects it
  (permission error): push to the session branch, open the report with a prominent
  BRANCH WARNING that `main` must be fast-forwarded before the next run, and paste the
  verbatim rejection error, AND send the curator a push notification — stranded state on a
  branch is attention-worthy (main does not fast-forward itself, and the next scheduled run
  will build on the stale main and orphan this session's work), and a report note alone is
  not seen until the curator looks.
- Operator notifications: stay SILENT on healthy/routine runs (a notification every run is
  noise). Send a push notification only for something the curator must see BEFORE the next
  run — a failed `main` push / stranded state, a broken hard rule, or a degradation you have
  self-flagged "heal owed" for ≥3 consecutive runs.

## Self-amendment (autonomy contract)

The radar runs unattended: in normal operation no human edits prompts, skills or scope.
The fixed platform prompt of each scheduled session is a fixed loader and must never
change:

> You are the daily [weekly] operator of this repository. Read AGENTS.md, then read
> routines/daily.md [routines/weekly.md] and execute it exactly. If either file is
> missing or unreadable, write a report describing the problem, commit only the report,
> and stop.

Because `routines/*.md` are the live operating instructions, they are amendable:

- Only weekly runs amend `routines/*.md`, skills, or scope axes. Daily runs execute.
- Every amendment must cite the calibration metric or retrospective that motivates it.
- Cooling period: PROPOSED in one weekly report, APPLIED on the next weekly run only if
  the motivating signal persists. Silence is consent; the curator may veto with a dated
  entry in `strategy_notes`.
- One dedicated commit per applied amendment: `radar: amend <target> — <reason>`.
- Auto-rollback: if calibration metrics worsen for two consecutive weeks after an
  amendment, `git revert` it and log the rollback in `calibration`.
- Scope axes evolve the same way: a "radar-adopted" dated entry in `strategy_notes` may
  supersede an older axis. Curator entries are never deleted or edited.

Immutable (curator-only): the Hard rules, Coverage discipline and this Self-amendment
section; the existence of the self-evaluation step; append-only history.

## Skill maintenance policy

Skills in `.claude/skills/` may be improved when a procedure proves wrong, clunky or
incomplete. Never relax the hard rules above (skills make them more precise, not weaker).
Keep SKILL.md frontmatter valid (`name`, `description`). One dedicated commit per skill
change. Create a new skill only after the same procedure has been improvised twice.
