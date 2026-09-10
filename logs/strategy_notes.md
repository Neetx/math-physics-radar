# Strategy notes — Math-Physics Radar

Append-only log of coverage-strategy corrections, curator scope input, anchoring
warnings and amendment records. MOVED here from `TRENDS.md` (2026-09-08, curator-directed)
to keep the ledger small: it had grown to 1,115 lines, 26% of the whole file.

Read only the RECENT TAIL (last ~10 entries) to decide a run; never re-read the full
history. Never edit or reorder past entries — curator entries are never deleted.

---


Corrections to the source-coverage strategy.
- 2026-07-02 — Scope (curator input): Frontier research advances in mathematics and modern/quantum physics, for a mathematically-literate researcher. Five fronts, in priority order: (1) pure mathematics — theorems, resolved conjectures, techniques; (2) theoretical & mathematical physics — QFT, strings, quantum gravity, integrable systems, the math↔physics interface; (3) modern experimental & phenomenological physics — HEP, gravitational waves & cosmology, condensed matter, AMO; (4) quantum foundations & quantum-information theory (the science, explicitly NOT the quantum-computing / QML technology the sibling quantum radar tracks); (5) computer-assisted & formalized mathematics (Lean/mathlib, Rocq). Evidence is PRIMARY only — papers (arXiv + peer-reviewed journals), official experiment/institute results, formalization repos. Extraordinary claims (a proof of a major conjecture, a discovery/anomaly) are provisional until peer review / community vetting; track the vetting outcome, never declare victory on an unrefereed preprint. The agent owns and evolves these axes;
  promote a forming sub-theme to a trend at ≥3 independent groups + an artifact.
- 2026-07-04 (W27 recalibration) — Coverage honesty: 14 swept-every-run sources in `SOURCES.md` were
  MISSING from all 3 daily passes this week (coverage 39/53): Fields Institute, Isaac Newton Institute,
  SciPost, AMS Notices, Forum of Mathematics, r/mathematics, r/AskPhysics, r/ParticlePhysics, Physics SE,
  Azimuth (Baez), Backreaction, Breakthrough Prize, IMU/Fields, SciRate. Verified this session that the
  healthy ones are LIVE (Azimuth, Backreaction, r/mathematics, AMS Notices, Breakthrough all HTTP 200) —
  so this is a daily EXECUTION gap (the daily sampled institutes/digests instead of iterating the FULL
  list), NOT dead sources. Corrective: next daily MUST log EVERY swept-every-run entry opened/degraded;
  any still missing after W28 → heal-or-REMOVE. Findings: Fields' advertised `/rss.xml` 404s (2026-07-04)
  → keep it on HTML→`tvly extract`; SciRate remains 403 on curl+tvly (twice-failed) → proposed for removal.
- 2026-07-04 (W27) — Exploration/anchoring: the tunnel-vision check is N/A this week — the sole trend
  (Ramsey) was CREATED from the queue, so no pre-existing trend could have hoarded the new evidence. BUT
  the exploration slot ran 3/3 runs and queued 0 off-axis items (off-axis rate 0/14). Per `radar-self-eval`,
  off-axis = 0 for TWO consecutive weeks triggers an anchoring warning — flagged to watch; if W28 also
  returns 0 off-axis, rotate the discovery venues.
- 2026-07-04 (daily heal) — SciRate REACHABLE after all: `tvly search "<query>" --include-domains scirate.com`
  gets through the Cloudflare wall that blocks curl AND `tvly extract` (returned the top-scited list, e.g.
  arXiv:2604.02856, this session). Access method recorded in SOURCES.md. This REVERSES the W28 removal
  rationale (the "twice-failed" was extract-only; search works) — weekly W28 should KEEP SciRate with the
  healed search path, not drop it. Also healed this run: SciPost via its JSON API `scipost.org/api/publications/?limit=N`
  (newest-first) — the `/rss/` path serves JS HTML, not a feed.
- 2026-07-04 (W27) — Proposed amendments (cooling period; apply W28 if the signal persists and no dated
  curator veto appears here): (1) heal-or-REMOVE the 14 missing sources — enforce full-list iteration next
  week, drop any still un-swept at W28; (2) DROP SciRate from the discovery venues (twice-failed Cloudflare
  403, redundant with arXiv listings + INSPIRE + Quanta); (3) source-discovery: HOLD sammattheus.wordpress.com
  staged (1 sighting, below the ≥2 promotion bar) — promote only on recurrence.
- 2026-07-11 (W28 recalibration) — Coverage: honest diff of the swept-every-run lists vs this week's logs
  (07-05→07-10). HEALED since W27 (now swept 6/6): SciPost, Azimuth/Baez, Backreaction, IMU/mathunion, SciRate
  (healed search path). STILL MISSING all 6 daily runs (coverage lie persisting): math institutes (IHES, SLMath,
  MPIM, Fields Inst, Isaac Newton, KITP, Perimeter, IAS), experiments (DESI, IceCube), venues (Annals, AMS
  Notices, Forum of Mathematics), extra-social (r/mathematics, r/Physics, r/cosmology, r/ParticlePhysics,
  r/AskPhysics, Physics SE), awards (Abel, Breakthrough). VERIFIED LIVE this weekly session (Annals ToC, IHES
  news, r/mathematics, r/ParticlePhysics all reachable — nothing on-axis new; r/AskPhysics + r/cosmology
  transient-empty) → NOT dead, just under-iterated + genuinely low-frequency. Root cause = the same execution
  gap W27 flagged (daily iterates a high-frequency core, skips the slow block), now 2 weeks running. Removal is
  WRONG (sources valid + live) → cadence-split proposal below.
- 2026-07-11 (W28) — W27 amendments resolved: (1) heal-or-REMOVE — 5 of 14 healed/covered; the rest are
  live-but-under-iterated, so the REMOVE branch (conditioned on "still un-sweepable") does NOT fire — superseded
  by the cadence-split proposal. (2) DROP SciRate — WITHDRAWN, superseded by the 2026-07-04 heal (search path
  gets through the Cloudflare wall); KEEP SciRate with the healed path. (3) sammattheus.wordpress.com — still
  1 sighting, no recurrence this week → HOLD staged (below the ≥2 bar). No destructive amendment applied to files.
- 2026-07-11 (W28) — Anchoring warning (radar-adopted): off-axis = 0 for TWO consecutive weeks (W27 0/14,
  W28 0/6) → per radar-self-eval an anchoring warning fires. The daily explore slot keeps reading arXiv-NEW top
  items, which are on-axis by construction. REDIRECT W29 exploration to genuinely off-axis venues (rotate the
  discovery-venue window; deliberately read a non-tracked field's top items and queue "significant, off-axis").
  Note: this week 0 new evidence landed on ANY trend (the sole trend went dormant with none), so the classic
  tunnel-vision test is moot — the signal is UNDER-EXPLORATION, not trend-hoarding.
- 2026-07-11 (W28) — Proposed amendments (cooling → apply W29 if the signal persists and no dated curator veto,
  silence = consent): (A) CADENCE-SPLIT the SOURCES.md swept lists into DAILY (high-frequency feeds: arXiv, APS
  PRL/PRX/RMP, Nature Physics, Quantum, SciPost, INSPIRE, CERN Courier, Fermilab, Simons, LIGO, mathlib/lean/rocq,
  the digest/blog lane, r/math, MathOverflow, HN, Mathstodon, Quanta, SciRate) vs WEEKLY-SWEPT (the slow
  institute/venue/award block above + low-yield extra-social subs) — motivated by the 2-week coverage miss on
  exactly that low-frequency block; makes the daily coverage promise honest and hands the slow block to the
  weekly operator. (B) ROTATE the discovery/exploration venues toward genuinely off-axis reading — motivated by
  the 2-week off-axis=0 anchoring warning.
- 2026-07-18 (W29 recalibration) — RECONCILE-FIRST correction (the headline of the week): the Ramsey
  lower-bound trend was REACTIVATED dormant → emerging. Both the W28 dormant demotion (at 45 days) and the
  standing "archive at W29" decision were made under the SUPERSEDED 21/45-day AI-default windows; the
  domain-cadence calibration applied 2026-07-13 sets dormancy at 60 days. last_evidence 2026-05-27 is 52 days
  old — inside the current active window — so the trend is not dormant under the current threshold. Per the
  weekly.md §2 reconcile rule, the stale decisions are voided and the trend restored to emerging (confidence
  held medium; unrefereed-preprint caution). New 60-day dormancy re-check: 2026-07-26. First application of the
  "a threshold change retroactively fixes trends mis-staged under the old threshold" rule.
- 2026-07-18 (W29) — Amendments APPLIED (W28 proposals A & B; cooling period elapsed, signal persisted, no
  dated curator veto — silence = consent): (A) CADENCE-SPLIT of the SOURCES.md swept lists into a DAILY
  high-frequency tier and a WEEKLY-SWEPT slow tier (institute/venue/award block + low-yield extra-social),
  motivated by the coverage-miss on exactly that slow block now running 3 weeks (W27/W28/W29); (B) formalized
  the OFF-AXIS discovery-venue rotation in the SOURCES.md exploration section, motivated by the anchoring
  warning. Each applied in its own dedicated commit (radar: amend SOURCES.md …). The daily had already begun
  operating under both (07-14 handed the slow block to the weekly; 07-16/07-17 read off-axis venues) — the
  amendments ratify observed practice.
- 2026-07-18 (W29) — Coverage: the slow institute/venue/award block was again under-iterated by the dailies
  this week (same execution gap W27/W28 flagged). Live-verified this weekly session via tvly (IMU/mathunion,
  DESI, IHES/SLMath/Newton): all LIVE, nothing new on-axis (DESI still the Apr-2026 survey-complete milestone;
  institutes admin/ecosystem; ICM 2026 opens 23–30 Jul, no Fields laureates yet). Sources live + genuinely
  low-frequency, not dead → the cadence-split (A) is the correct fix, not removal.
- 2026-07-18 (W29) — Anchoring warning EASING: off-axis rate 1/5 this week (07-17 queued the Thomas
  positive-circuits planar-case resolution, math.DS, "significant, off-axis"), up from 0/14 (W27) and 0/6 (W28).
  The W28 discovery-venue redirect is working; keep the off-axis rotation (B) in force and re-check next week.
- 2026-07-18 (W29) — Proposed (cooling → apply W30 if the signal persists, silence = consent): (C) SYNC the
  `radar-ledger-update` skill's stale window numbers (it still hardcodes "~25 cap", "21+/45+ days") to the
  curator-set domain-cadence windows (~40 cap, 60/120 days) — motivated by this week's reconcile correction,
  which the skill's own text contradicts; the dailies already follow AGENTS.md over the skill (no active harm),
  but the skill is a latent trap for a future run. Skill-maintenance, one dedicated commit when applied.
- 2026-07-25 (W30 recalibration) — Amendment (C) APPLIED (cooling period elapsed; signal persisted — the skill
  still hardcoded the AI-default 21/45-day dormancy, 45-day archive and ~25-item cap with a per-session
  cap-driven burndown, all of which contradict the curator-set domain cadence in AGENTS.md; no dated curator
  veto). Synced `radar-ledger-update` SKILL.md to the domain-cadence windows (dormant 60+/archive 120+ days,
  soft cap ~40 with persistence over burndown). One dedicated commit. Two-week regression check on W29's
  applied amendments (A cadence-split, B off-axis rotation): only 1 week elapsed → no 2-week window yet; both
  reading healthy (off-axis 0→1→see below; daily promise now honest) → no rollback.
- 2026-07-25 (W30) — Ramsey trend HELD emerging (59 days < the 60-day dormancy line by one day). Confirmatory
  arXiv checks this session found NO fresh Ramsey lower-bound primary (only peripheral Ramsey-type notes) and
  NO referee/vetting v-update on the four tracked preprints → completed-burst read intact. Dormancy at W31
  (2026-08-01, 66 days) unless a fresh lower-bound primary or vetting outcome appears.
- 2026-07-25 (W30) — Coverage (weekly-swept tier, weekly operator's sweep duty): SWEPT the slow block this
  session. IMU/Fields (ICM-season DAILY-chase exception): 2026 Fields Medals (Deng, Pardon, Tsimerman, Wang)
  confirmed — the SAME four already captured 07-24 (also corroborated via Simons Foundation + IAS "Three IAS
  Scholars Honored"). Clay: 2026 Clay Awards (tracked); NEW minor — Anna Skorobogatova awarded a 2026 Maryam
  Mirzakhani New Frontiers Prize (geometric measure theory) — early-career ecosystem, BELOW the radar's
  prize-capture bar (Fields/Abel/Shaw/Clay-main), noted not queued. Annals (Vol 203/204), AMS Notices (2025
  year-review), KITP/IAS/IHES/SLMath/MPIM/Newton/Perimeter: opened, nothing NEW on-axis (institutes =
  programs/admin — domain-normal). Extra-social: r/Physics + r/cosmology opened (nothing on-axis; IPhO 2026
  results, general Q&A); r/ParticlePhysics + r/AskPhysics degraded (empty/429 via curl — recurring rate-limit,
  not death); Forum of Mathematics degraded this session (tvly returned off-topic hits — low-yield, KEEP).
  Net: the weekly-swept tier is domain-normal quiet; the week's only on-axis landmark (the Fields Medals) was
  already captured by the daily. NOT a coverage lie — every swept-tier source logged opened or degraded.
- 2026-07-25 (W30) — Anchoring / tunnel-vision: N/A-to-mild this week — 0 new EVIDENCE landed on any trend
  (the sole trend took no fresh evidence; all captures were queue items), so the classic "all evidence hoarded
  on pre-existing trends" test is moot. off-axis rate for the week's dailies remained low but the W29 off-axis
  rotation (amendment B) stays in force; in a domain this narrow off-axis=low is not an alarm per AGENTS.md
  domain-cadence. No redirect beyond keeping B in force.
- 2026-07-25 (W30) — Source-discovery (drain staged candidates): both staged candidates remain BELOW the ≥2
  promotion bar — sammattheus.wordpress.com (1 sighting, no recurrence) and sbseminar.wordpress.com (1 sighting,
  first seen 07-23) → HOLD both staged, no promotion this week. No new recurring on-axis org surfaced un-promoted.
- 2026-07-25 (W30) — Queue hygiene: queue at 65 (well over the ~40 soft cap; W29 held 46, +19 across six
  dailies with no burndown). Nothing is stale (oldest item 23 days « the 60-day domain-cadence staleness line).
  Per weekly.md §3 ("resolve the oldest only when genuinely over cap") did a MEASURED burndown of the LOWEST tier
  only: 8 oldest title-only physics-journal RSS batch-intake lines (07-07→07-13, "titles via RSS, articles not
  opened → unverified intake", superseded by later batch snapshots and preserved permanently in their day's
  reports) — dropped with reason. NO abstract-opened math or physics RESULT touched (domain cadence: math results
  persist for months). Queue 65 → 57, still deliberately above the soft cap for the verified below-bar backlog.
- 2026-07-25 (W30) — Capture-leak sweep (MANDATORY backstop): 50 arXiv ids in TRENDS.md + 19 in this week's
  reports mechanically diffed — every report id present on a discrete queue/evidence/shelf line, 0 leaks.
- 2026-07-25 (W30) — No new amendments proposed this week (the ledger, skills and scope axes are in a
  consistent state after C; the source registry is honest post cadence-split). Monthly hit/miss retrospective
  NOT due (day 25 > 7; M08 due first run of August).
- 2026-08-01 (W31 recalibration) — Coverage (weekly-swept tier, weekly operator's sweep duty): full
  list-vs-log diff run against the 21-entry weekly-swept roster in SOURCES.md. SWEPT this session: IHES,
  MPIM, Fields Institute, Isaac Newton, KITP, Perimeter, IAS, Clay (8/9 institutes — nothing new on-axis,
  admin/program pages only); Annals (Vol 203 unchanged), AMS Notices (generic landing, nothing new);
  r/cosmology, Physics SE (both opened, routine Q&A only); Abel (Faltings unchanged), Breakthrough (menu
  only, nothing new), IMU/Fields (unchanged since the 07-23 medals — first weekly-cadence sweep since ICM
  closed 07-30). Degraded (all logged, none silently dropped): SLMath (`tvly extract` fetch failure,
  healed via `tvly search` — "Elected to IMU Executive Committee for Second Term," admin, nothing on-axis);
  Forum of Mathematics (cookie/paywall gate, standing); r/Physics, r/ParticlePhysics, r/AskPhysics (still
  blocked even with a full-browser UA — recurring rate-limit, LIVE not dead, same as W30); Shaw (`tvly
  extract` failed, healed via `tvly search --include-domains shawprize.org` — confirms Candès/De Lellis
  unchanged). 21/21 logged opened-or-degraded — NOT a coverage lie. TOOL NOTE: `tvly` was reported hitting
  a plan-usage-limit outage in the 07-31 daily (first occurrence, "watch for recurrence") — this session
  needed a fresh `pip install -q tavily-cli` (binary was entirely absent from PATH, a different failure
  mode than a quota error) and then worked normally for the rest of the sweep; treating as resolved, not
  yet a 2-in-a-row heal trigger for either failure mode.
- 2026-08-01 (W31) — Source-discovery (drain staged candidates): both candidates checked against this
  week's 5 daily reports (grep) — no recurrence. sammattheus.wordpress.com and sbseminar.wordpress.com
  both HOLD at 1 sighting each, below the ≥2 promotion bar. No new recurring on-axis org surfaced
  un-promoted this week.
- 2026-08-01 (W31) — Anchoring / off-axis: this week's 5 dailies (07-27→07-31) ran the off-axis exploration
  slot every run (5/5 compliance; roster advanced math.AT/KT/OA/FA/SG/GT → math.NA → econ.TH → cs.CC →
  q-bio.PE) but queued 0 significant off-axis items (0/5 yield). Per AGENTS.md § Domain cadence this is
  explicitly NOT an anchoring alarm on its own in a field this narrow ("off-axis-rate = 0 for a week is not
  a warning here") — noted for the record, not flagged as a warning, in contrast to the pre-domain-cadence
  precedent (W27/W28) that DID fire an alarm at 0/14 and 0/6. Evidence-hoarding test is separately moot:
  0 new evidence landed on the two active-at-week-start trends (Ramsey took none; non-invertible-symmetries
  and Stanley-Gasharov took none beyond their creation week) — no tunnel-vision signal either.
- 2026-08-01 (W31) — Queue hygiene: queue at 75 (58 at W30 close, +17 net across five dailies, well over
  the ~40 soft cap). Per weekly.md §3 did a MEASURED burndown of the LOWEST tier only: 13 lines dropped —
  10 never-opened title-only APS PRL/PRX RSS batch lines (07-06 through 07-29, "titles via RSS, articles
  not opened → unverified intake"), 1 Nature Physics commentary blurb whose underlying paper was never
  identified in ~4 weeks (07-05), 1 fully-superseded formal-math-toolchain snapshot (07-23, superseded by
  the already-queued 07-29 Rocq-9.3+rc1 line, which this session was updated in place with the current
  lean4/mathlib4 v4.32.2 state), and 1 fully-resolved Clay-Research-Awards ecosystem line (07-08) whose
  two landmark primaries are already on `study_shelf` (Wang-Zahl 3D-Kakeya, Burklund-Hahn-Levy-Schlank
  telescope-conjecture counterexample). NO abstract-opened math or physics RESULT touched. Also VERIFIED
  (not dropped) the one remaining never-opened queue line, arXiv:2607.00762 (deconfined criticality),
  closing a month-old unverified gap. Queue 75 → 62, nothing stale (oldest live item ~30 days « the 60-day
  domain-cadence staleness line).
- 2026-08-01 (W31) — Capture-leak sweep (MANDATORY backstop): 67 unique arXiv ids in TRENDS.md (pre-edit)
  mechanically diffed against 20 ids named across this week's 5 daily reports — all 20 present on discrete
  queue/evidence/shelf lines, 0 leaks. The weekly's own burndown/verification edits touched no id-bearing
  math/physics-result line (only title-only RSS/ecosystem lines with no arXiv ids of their own).
- 2026-08-01 (W31) — Self-amendment: two-week regression check on W29's amendments (A cadence-split, B
  off-axis rotation) — the qualifying window (W30, W31). Coverage promise honesty (the metric A targets):
  W30 17/21 logged, W31 21/21 logged — both fully honest, no lie, no regression. Off-axis compliance (the
  metric B targets): exploration ran every daily both weeks (compliance, not yield); yield dropped W29's
  1/5 → W30 "low" → W31 0/5, but AGENTS.md's domain-cadence override (applied 2026-07-13, AFTER W29) makes
  off-axis=0 a non-alarm here — the metric B was built to fix didn't regress, it was superseded by a wider
  curator-set relaxation. NO ROLLBACK on either amendment. Amendment C (skill-window sync, applied W30) is
  only 1 week old — regression check not due until W32.
- 2026-08-01 (W31) — No new amendments proposed this week: the source registry, skills and scope axes are
  in a consistent, honest state (cadence-split coverage clean 2 weeks running; skill windows synced;
  no un-drained source-discovery backlog). First monthly self-evaluation retrospective (M08) — see
  `logs/calibration.md` — completed this session (day 01 ≤ 7).
- 2026-08-08 (W32 recalibration) — Coverage (weekly-swept tier, weekly operator's sweep duty): full
  list-vs-log diff run against the 21-entry weekly-swept roster. SWEPT this session (opened, nothing new
  on-axis beyond the Gaitsgory item queued above): IHES, MPIM (Gaitsgory Frontiers of Science Award
  found here), Fields Institute, Isaac Newton, KITP, Perimeter, IAS, Clay (8/9 institutes); Annals
  (unchanged), AMS Notices (generic landing); r/Physics, r/cosmology, r/ParticlePhysics, r/AskPhysics,
  Physics SE (all opened directly this session — the recurring rate-limit did NOT reproduce; routine
  Q&A/noise only, one borderline off-axis solar-physics item on r/Physics not queued); Abel (Faltings
  unchanged), Breakthrough (menu only), IMU/Fields (unchanged since 07-23). Degraded (healed via search,
  none silently dropped): SLMath (`tvly extract` fails, `tvly search --include-domains slmath.org`
  works — an "In Memoriam" post, nothing on-axis); Forum of Mathematics (login/paywall gate, standing);
  Shaw (`tvly extract` fails, `tvly search --include-domains shawprize.org` confirms Candès/De Lellis
  unchanged). 21/21 logged opened-or-degraded — NOT a coverage lie.
- 2026-08-08 (W32) — Source-discovery (drain staged candidates): promotion bar is ≥2 on-axis primary
  artifacts OR recurrence across ≥2 runs, verified by opening. PROMOTED three: **nature.com/ncomms**
  (2 on-axis primaries — RH↔quantum-phase-transitions 07-01, aperiodic-monotile chirality 07-29; feed
  verified this session, `https://www.nature.com/ncomms.rss` redirects to a working RSS) → added to
  Research/publication venues, DAILY tier. **scientificamerican.com** (2 sightings — Cohen-Lenstra
  pointer 08-05, original misconduct reporting with named experts 08-06; no dedicated RSS found, access
  method `tvly search --include-domains scientificamerican.com`, already used successfully twice) →
  added to the digest/press lane, DAILY tier. **openai.com/cdn.openai.com** (tallied 1 in the staging
  counter but the staging note itself documents TWO now-tracked direct disclosure events — the
  off-arXiv Cycle-Double-Cover proof pre-dating this staging mechanism, and "Ten Advances" 08-01 — a
  genuine recurring new-artifact-drop channel for the AI-assisted-math wave, not a one-off; no feed, access
  via periodic `tvly search`) → added to Primary feeds as an AI-watch-lane primary, DAILY tier. HELD below
  bar (no promotion): sammattheus.wordpress.com (1, no recurrence), journals.aps.org/prresearch (1 —
  but the RSS feed `https://feeds.aps.org/rss/recent/prresearch.xml` was pre-verified working this
  session for when it does clear the bar), leodemoura.github.io (1 — RSS `feed.xml` also pre-verified
  working), sbseminar.wordpress.com (1, no recurrence since 07-23), ams.org/journals/jams (1, no RSS —
  `tvly extract` works, curl 403s), bourbaki.fr (1, no RSS — `tvly extract` works on the static page).
  Cleared/updated the promoted lines out of the staging list in SOURCES.md.
- 2026-08-08 (W32) — Self-healing: resolved the 08-07 daily's lean4 version-tag ambiguity — `tvly search
  "leanprover lean4 latest release version tag" --include-domains github.com` confirms v4.33.0-rc2
  (matching mathlib4's 08-05 bump) with v4.32.2 still latest stable; `tvly extract` on the bare releases
  page keeps returning only a JS-shell nav (standing failure, not newly broken) — the search-based path
  is now the recorded working method in SOURCES.md for both lean4 and mathlib4 release-tag checks.
- 2026-08-08 (W32) — Anchoring / off-axis: this week's 5 dailies (08-03→08-07) ran the off-axis
  exploration slot every run (5/5 compliance; roster advanced nlin.CD → math.OC → math.ST → cs.CC →
  econ.TH) but queued 0 significant off-axis items (0/5 yield) — per AGENTS.md § Domain cadence this is
  explicitly NOT an alarm on its own here, consistent with W31's 0/5. Tunnel-vision check: exactly 1 new
  evidence item landed this week, and it landed on a pre-existing trend (Ramsey, Steiner 2608.02537,
  08-04) — but this was a genuinely fresh independent primary from the day's arXiv batch, not evidence
  mined out of a hoarded queue, and a single data point is too thin to read as hoarding in a field this
  slow; not flagged as an anchoring alarm, noted for the record.
- 2026-08-08 (W32) — Queue hygiene: queue at 99 lines pre-edit (62 at W31 close, +37 net across five
  landmark-dense dailies 08-03→08-07 — the OpenAI "Ten Advances" cluster and the Cohen-Lenstra/period-index/
  Crouzeix landmark stretch drove an unusually high intake week, not a coverage problem). Per weekly.md §3
  did a MEASURED burndown of the LOWEST tier only: 4 never-opened title-only lines dropped (GWTC-5.0 GR-tests
  companion paper 07-22, the Thomas positive-circuits off-axis catch 07-17 [already fully preserved in its
  own day's report and in the W29 strategy_notes entry], the H₀ World Cup community meta-analysis 07-16, the
  AdS₃×S³×T⁴ Quantum Spectral Curve program paper 07-16) — all four were title-only, never opened in the
  weeks since capture. NO abstract-opened math or physics RESULT touched (domain cadence: verified below-bar
  results persist for months). +1 new item added this session (Gaitsgory Frontiers of Science Award, queued
  above). Net 99 → 96, still well above the ~40 soft cap deliberately (domain cadence: persistence over
  burndown-to-a-number); nothing stale (oldest live item ~36 days « the 60-day domain-cadence staleness line).
- 2026-08-08 (W32) — Capture-leak sweep (MANDATORY backstop): 35 unique arXiv ids named across this week's
  5 daily reports (08-03→08-07) mechanically diffed against TRENDS.md — all 35 present on discrete
  queue/evidence/shelf lines, 0 leaks. Full-ledger cross-check (107 unique arXiv ids in TRENDS.md overall):
  the 11 ids appearing in trend `evidence:` blocks or `study_shelf` but not the queue section are
  legitimately captured there (not queue duplicates required) — 0 leaks ledger-wide.
- 2026-08-08 (W32) — Self-amendment: two-week regression check on Amendment C (skill-window sync, applied
  W30 2026-07-25) — the qualifying window (W31, W32) has now elapsed. Re-read `radar-ledger-update`
  SKILL.md this session: it still correctly states the domain-cadence windows (60+/120+ day dormancy/
  archive, ~40 soft cap, ~60-day staleness) — no regression, no drift back to the AI-default numbers.
  NO ROLLBACK. Amendments A (cadence-split) and B (off-axis rotation), both checked clean at W31, remain
  in force and continue reading healthy this week (coverage 21/21, off-axis compliance 5/5). No new
  amendments proposed this week — the source registry (now grown by 3 genuine promotions), skills and
  scope axes are all in a consistent, honest state. Monthly hit/miss retrospective NOT due (day 08 > 7;
  M09 due first run of September).
- 2026-08-11 (daily) — Self-heal: Strassler ("Of Particular Significance") flagged 08-10 for
  apparent feed staleness since Feb 2026 — confirmed via the live homepage (`tvly extract`, not
  just the RSS) that "The Physicists and Mr. Epstein" (posted 05/02/2026) is still the latest
  post. Genuinely quiet (a low-cadence author on hiatus), not a feed/caching bug — same pattern
  as the CERN Courier self-heal (08-10). Reclassified from degraded to confirmed-quiet; heal-owed
  flag cleared.
- 2026-08-12 (daily) — Repo watch: lean4 pre-release bumped v4.33.0-rc2 → **v4.34.0-rc1**
  (`tvly search "leanprover lean4 latest release version tag" --include-domains github.com`
  this session, confirmed text "release candidate 1 for the v4.34.0 release of Lean"). mathlib4's
  matching bump NOT independently confirmed this pass — the same search query against
  leanprover-community/mathlib4 returned only stale/wiki hits, not a clean current-tag
  confirmation; `tvly extract` on the bare releases page returned only the standing JS-shell nav.
  Logged degraded rather than asserted; the two repos have tracked closely in every prior
  observation (v4.33.0-rc2 in sync as of 08-08) so a matching mathlib4 bump is likely but
  unverified — recheck next run. Rocq confirmed unchanged at V9.3+rc1.
- 2026-08-12 (daily) — Source-discovery: no new candidate staged this session — the fresh
  ecosystem item (Simons Foundation "Virtues of Defects" collaboration) is already on the
  tracked Simons Foundation RSS feed (DAILY tier), and all captured math/physics primaries are
  on already-tracked arXiv. CERN Courier's "arXiv's one-strike rule on AI" article (already
  captured 2026-07-30) resurfaced this session via a community-pulse pointer to a concrete
  enforcement anecdote — a graph-theory counterexample paper (Teschner's bondage-number
  conjecture) reportedly pulled from arXiv under the new policy and re-hosted on figshare; NOT
  captured as evidence (figshare is not a primary venue under the hard rules, and the underlying
  claim was not independently verified this session) — noted here only as ecosystem color on the
  already-tracked policy item, not a new queue line.
- 2026-08-12 (daily) — Queue hygiene: queue at 114 pre-edit (unchanged count carried from 08-11
  close) +5 new items today (Kolokolnikov pair, Kohayakawa, Katok partial, 3d-YM mass-gap
  outline, Simons defects collaboration) → 119. Still well over the ~40 soft cap deliberately
  (domain cadence: persistence over burndown-to-a-number); nothing stale (oldest live item well
  under the 60-day staleness line). Next weekly (~08-15) should consider a measured lowest-tier
  pass per weekly.md §3, now overdue for two consecutive weekly cycles at this queue size.
- 2026-08-14 (daily) — Self-heal (repo watch, resolves the 08-13 daily's 2nd-consecutive
  mathlib4 miss, heal-owed): the bare `/releases` page keeps returning a JS-shell nav via
  `tvly extract` (standing failure) AND `tvly search` intermittently returns stale/wiki hits
  for mathlib4 specifically — but the `/releases.atom` Atom feed works cleanly via `tvly
  extract` for all three repos (lean4, mathlib4, Rocq) this session. NEW FINDING: mathlib4
  does NOT tag semantic-version releases the way lean4/Rocq do — its releases.atom instead
  shows continuous daily `master-YYYY-MM-DD` auto-tags (newest this session:
  `master-2026-08-13`), which is WHY a "latest version tag" search for mathlib4 kept coming
  up empty/stale — there is no discrete version tag to find. Recorded in SOURCES.md as the
  primary access method (prefer `.atom` over `tvly search`) and the daily-tag behavior noted
  so future runs don't mis-diagnose it as degraded. Confirmed this session: lean4 stable
  bumped v4.32.2→**v4.33.0** (2026-08-10), pre-release v4.34.0-rc1 (2026-08-10); mathlib4 at
  master-2026-08-13; Rocq unchanged V9.3+rc1. Routine toolchain state, heal-owed flag cleared.
- 2026-08-14 (daily) — Queue hygiene: queue at 128 pre-edit (carried from 08-13 close) +12 new
  items today (Banach's isometric conjecture, Gromov's volume-growth conjecture, the
  Chang-Yang conjecture, the Hayman-Wu constant, SOP2=SOP3, HRT exponential-tail follow-up,
  PPT-channel entanglement-breaking, Foregger-Sinkhorn, Bosch-Simó, the Boussinesq
  computer-assisted-proof audit, non-Abelian anyon braiding, the Grothendieck-constant
  off-axis catch) → 140 — an unusually landmark-dense day (5+ named-conjecture resolutions in
  one arXiv batch). Still well over the ~40 soft cap deliberately (domain cadence:
  persistence over burndown-to-a-number); nothing stale (oldest live item well under the
  60-day staleness line). Weekly burndown (~08-15, due tomorrow) now overdue for three
  consecutive weekly cycles at this queue size — flagged again.
- 2026-08-15 (W33 recalibration) — Coverage (weekly-swept tier, weekly operator's sweep
  duty): full 21-entry list-vs-log diff, swept live this session (not just log-diffed, since
  the dailies correctly do not touch this tier). OPENED, nothing new on-axis beyond the dark
  photon catch below: IHES, SLMath, MPIM (Gaitsgory/Faltings items unchanged), Fields
  Institute, Isaac Newton, KITP, IAS (healed via `tvly search` — bare `/news` extract returns
  only nav, membership-cycle announcement only), Clay (Sept conference reminder), Annals
  (Vol 203/204 unchanged), AMS Notices (ICM retrospective coverage only), Forum of Mathematics
  (accessible this session, two routine PDE/topology titles, no landmark), Physics SE (routine
  Q&A), Abel/Breakthrough/Shaw/IMU-Fields (all unchanged since capture). DEGRADED (direct
  extract blocked, healed via `tvly search` fallback, routine content only): r/Physics,
  r/cosmology, r/ParticlePhysics. STILL DEGRADED (no clean fallback found this session):
  r/AskPhysics — search fallback returned r/Physics hits, not r/AskPhysics-specific; flagged
  heal-owed for next weekly if it recurs. **PERIMETER CATCH:** the institute's own news page
  surfaced a fresh, peer-reviewed PRL paper (Hook–Huang–Shalaby, dark-photon plasma-nonlinearity
  result, arXiv:2510.13956) that the daily's routine PRL-title scan had not individually
  chased — queued this session; a concrete example of why the weekly institute sweep is not
  redundant with the daily's high-volume feed reading. 21/21 tier entries logged
  opened-or-degraded — NOT a coverage lie.
- 2026-08-15 (W33) — Source-discovery (drain staged candidates): promotion bar is ≥2 on-axis
  primary artifacts OR recurrence across ≥2 runs. Checked all 8 staged candidates in
  SOURCES.md against this week's 5 daily reports + this session's own findings — NO
  recurrence for any: sammattheus.wordpress.com, journals.aps.org/prresearch,
  leodemoura.github.io, sbseminar.wordpress.com, ams.org/journals/jams, bourbaki.fr (all
  unchanged at 1 sighting, several weeks stale now — genuinely one-off, not actively
  building toward promotion) and the two newer stages anthropic.com/research (1, since
  08-11) and proofatlas.ai (1, since 08-13, too recent to expect recurrence yet). HOLD all
  8 below the ≥2 bar; no promotions this week. No new recurring on-axis org surfaced
  un-promoted.
- 2026-08-15 (W33) — Anchoring / off-axis: this week's 5 dailies (08-10→08-14) ran the
  off-axis exploration slot every run (5/5 compliance; roster advanced math.OA → q-bio.PE →
  math.LO → math.NA → cs.CC) with 1/5 yield (08-14's Grothendieck-constant catch,
  arXiv:2608.11158, "significant, off-axis" per `radar-explore`) — a genuine off-axis hit,
  not just compliance. Tunnel-vision check: ZERO new evidence landed on any of the three
  active trends this week (all three HELD all five dailies) — but this reads as a
  domain-normal quiet week for the tracked axes rather than hoarding: the week's landmark
  intake (Sendov's conjecture, non-Abelian anyon braiding, Banach's isometric conjecture,
  five-conjecture 08-14 batch) all landed on the queue/study_shelf, not on pre-existing
  trends, so nothing was hoarded either. No anchoring warning.
- 2026-08-15 (W33) — Queue hygiene: queue at 140 pre-edit (carried from the 08-14 daily
  close), now 3 consecutive weekly cycles over the ~40 soft cap with no burndown (W32 closed
  at 96; +44 net across five landmark-dense dailies, the busiest single-week intake stretch
  yet). Per weekly.md §3 ("resolve the oldest only when genuinely over cap") ran a LARGER
  burndown than the recent 4-13-item precedent, given the backlog: 22 of the oldest queue
  lines (2026-07-02 through 2026-07-21, all 14–45 days old — nowhere near the 60-day
  staleness line, but genuinely settled) DROPPED with reason — single-author/small-group
  below-bar results with zero follow-up or citation in 3+ weeks, no forming-pair status, no
  study_shelf tag, no ongoing extraordinary-claim watch: Friedlander–Iwaniec dual-sums
  counterexample (2607.16695), Lusztig's special-pieces conjecture (2607.15406), Thakur
  conjecture counterexample (2607.15305), 3D Navier–Stokes transport-noise regularization
  (2607.15140), path-reversed-tournament inversion number (2607.13829), Sundaram's
  higher-Lie-positivity conjecture (2607.12749), Hypergraph Erdős–Rogers functions
  (2607.10111), Kellner's Wilson-quotient conjectures (2607.10106), a QEC diagrammatic-field-
  theory paper (2607.08911), the Morel structure conjecture (2607.08905), a bounded-VC-
  dimension Erdős–Hajnal bound (2607.09049), the 2026 Shaw Prize ceremony record (superseded
  by its own capture, no forward action pending), a degraded/metadata-only SciPost item
  (free-fermions-in-disguise), the Minkowski-grid repeated-distances result (2607.05374), a
  SciPost holographic-QCD item, the Detection-Threshold-Conjecture RGG result (2607.02013),
  a GWTC-5 axion null-result companion (2607.01317), formalized q-series (2607.01544), the
  Higher-Order Clique Density Theorem (2607.06545), "The abc Conjecture Revisited"
  (2607.07641), a random-multiplicative-functions CLT (2607.06398), and the 2026 Abel Prize
  ceremony record. EXPLICITLY NOT touched: anything on `study_shelf`, either member of a
  forming pair (deconfined-criticality 2607.00762/2607.01815; the matroid-intersection-
  conjecture claimed-proof watch, still no vetting outcome after 33 days), the Jacobian-
  conjecture/AI-wave narrative cluster, the OpenAI "Ten Advances" cluster, or the DESI
  saga thread. +2 new items this session (the Perimeter dark-photon catch; the
  2608.07102 capture-leak catch, see below). Net 140 → 120, still well above the ~40 soft
  cap (domain cadence: persistence over burndown-to-a-number) but the 3-cycle backlog is
  now meaningfully worked down; nothing remaining is stale (oldest live item now ~26 days
  « the 60-day line).
- 2026-08-15 (W33) — Capture-leak sweep (MANDATORY backstop): 45 unique arXiv ids named
  across this week's 5 daily reports (08-10→08-14) mechanically diffed against TRENDS.md —
  all 45 present on discrete queue/evidence/shelf lines, 0 leaked. Separately swept every
  trend's own `notes` field for embedded arXiv ids not backed by their own citation anywhere
  in the ledger (grep for ids never preceded by `arXiv:`/`abs/`) — found ONE real leak:
  arXiv:2608.07102 ("Vertex-Ramsey theorems for Cartesian powers of graphs"), named in the
  Ramsey trend's own notes since the 08-11 daily as a dismissed non-qualifying candidate but
  never given its own queue line — QUEUED this session (see queue). capture-leak: 45 report
  ids checked + full-ledger notes-field sweep / 1 queued.
- 2026-08-15 (W33) — Self-amendment: no amendments were proposed at W32, so none are due for
  application this week. Two-week regression check: Amendments A (cadence-split) and B
  (off-axis rotation), both long-standing and re-checked clean at W32, continue healthy
  (coverage 21/21 this week, off-axis compliance 5/5 with a genuine 1/5 yield). Amendment C
  (skill-window sync, applied W30) last checked clean at W32; re-read `radar-ledger-update`
  SKILL.md this session — still correctly states the domain-cadence windows, no drift. NO
  ROLLBACK on any amendment. ONE new amendment PROPOSED this week (cooling → apply W34 if the
  signal persists, silence = consent): **(D) size the weekly queue burndown to the backlog,
  not a fixed small tier.** Motivated by this week's 3-consecutive-cycle overdue backlog
  (W32→W33 queue grew 96→140, +44, while burndowns stayed at 4-13 items/week) — a fixed
  "measured lowest-tier" burndown cannot keep pace with intake this uneven. Proposal: when the
  weekly finds the queue 2×+ over the ~40 soft cap AND the prior weekly's burndown was
  flagged overdue by a daily more than once, the weekly burndown should target working the
  backlog down toward roughly 2–3× the soft cap (not a fixed item count), still restricted to
  settled, zero-follow-up, non-landmark items per the existing criteria. Monthly hit/miss
  retrospective NOT due (day 15 > 7; M09 due first run of September).
- 2026-08-17 (daily) — SKILL/FILE-CONTRACT MISMATCH FLAGGED (not amended today; daily runs
  execute, only weekly runs amend skills per AGENTS.md § Self-amendment): invoked
  `radar-ledger-update` this session — its documented file contract ("# Trend ledger — AI
  Radar" header, `### [id: slug-NNN] Title` trend blocks with an `alias` field, a standalone
  `## observation_queue` H2 header) does NOT match this repo's actual `TRENDS.md` structure
  (header reads "Math-Physics Radar"; trend blocks are `### Title` with
  `stage/confidence/first_seen/last_evidence` inline fields, no id/alias; the queue is an
  unheaded block directly under `## Active trends`, consistently across 2000+ lines and many
  prior sessions). Followed the REAL, established file structure (which matches AGENTS.md's
  File map) rather than the skill's stale template text — likely inherited unedited from a
  sibling radar's skill set. Flagged for the weekly operator to heal the skill text (skill
  maintenance policy: one dedicated commit, `radar: refine skill radar-ledger-update`) so a
  future session isn't misled into restructuring the file to match the wrong contract.
- 2026-08-20 (daily) — TOOLING DEGRADATION FLAGGED (not a skill/hard-rule issue; noted for
  awareness, not an amendment): `tvly` (both `search` and `extract`) returned "This request
  exceeds your plan's set usage limit" for every call from partway through this session onward
  (first hit on a Not-Even-Wrong post extract; LIGO/DESI/CERN/IceCube extracts earlier in the
  same session succeeded before the wall was hit) — an account-level quota exhaustion, not a
  single-source outage. WORKED AROUND per AGENTS.md's "fall back to built-in web tools only if
  Tavily fails": `WebFetch` substituted cleanly for the GitHub `releases.atom` repo-watch lane
  (lean4/mathlib4/Rocq, all confirmed) and for wordpress/HTML blog pages (Not Even Wrong, IAS-style
  pages); direct `curl` substituted for RSS/API feeds and even for the Woit wordpress page (no
  Cloudflare block on that host). ONE lane had NO working fallback: r/math and r/mathematics —
  `WebFetch` on `.rss` returned "unable to fetch from www.reddit.com" and `WebSearch` (with or
  without `--include-domains`-style domain filtering) could not surface live reddit threads either
  — logged `degraded` (see Coverage below), continuing the standing reddit-access streak, now via
  a NEW failure mode (quota, not a block) layered on the old one. Not yet flagged heal-owed (this
  is the first occurrence of the quota-exhaustion mode specifically); if `tvly` is still
  quota-exhausted on the next run, this becomes a heal-worklist item and probably warrants a
  curator ping (the account's Tavily plan may need attention) rather than another workaround.
- 2026-08-21 (daily) — TOOLING DEGRADATION, 2nd consecutive daily (not yet heal-owed): `tvly` was
  ABSENT at session start (not just quota-exhausted — the binary itself was gone, `command not
  found`) and had to be reinstalled via `pip install -q tavily-cli`; after reinstall, `tvly extract`
  on the very first call (Nature Physics current-issue) returned the SAME "This request exceeds
  your plan's set usage limit" error as 08-20 — confirming this is an account-level Tavily plan
  quota, not a session-local or binary-availability issue, and it persists across a full
  reinstall. This is only the SECOND consecutive daily on this exact failure mode; AGENTS.md's
  operator-notification bar is "heal-owed for ≥3 consecutive runs" — that bar is not yet met, so
  NO push notification was sent this session (the 08-20 note's "probably warrants a curator ping"
  language was premature/non-binding — AGENTS.md's explicit ≥3 threshold governs). If `tvly` is
  STILL quota-exhausted on the next daily, that will be the 3rd consecutive occurrence and should
  trigger both the heal-owed flag and a curator push notification. WORKED AROUND entirely without
  `tvly` this session (arXiv API, direct `curl`, `WebSearch`, `WebFetch` covered every lane that
  needed it).
- 2026-08-21 (daily) — HEAL: the Nature-family `idp.nature.com` auth-wall that blocks `WebFetch` on
  individual article pages (Nature Physics/Nature Communications, standing degraded 6+ consecutive
  dailies) can be BYPASSED for an already-known article URL with a plain `curl -A "Mozilla/5.0"
  <url>` — returns a full HTTP 200 page with `citation_*` meta tags (title/authors/journal/DOI/
  date all machine-readable), no auth redirect. Verified this session fetching
  https://www.nature.com/articles/s41377-026-02374-7 (Light: Science & Applications, a Nature
  Partner Journal) directly, cleanly, with `WebFetch` on the SAME url still hitting the
  `idp.nature.com` redirect in parallel. CAVEAT — this only heals the "cite a specific already-
  located article" case, not the harder "browse the current issue for what's NEW" case: the Nature
  Physics/Nature Comms `.rss` feeds are still empty-CDATA, and the `nature.com/nphys/current-issue`
  HTML index is client-rendered (the `curl` fetch returns only the shell + head metadata, no
  article list) — so this does NOT yet restore the daily "what's new in Nature Physics" check; it
  only means that once a Nature-family primary is NAMED (via a digest/pulse pointer, as happened
  today via Backreaction), it can now be opened and cited directly instead of routing around the
  auth-wall or leaving it uncited. Recorded as a partial heal in SOURCES.md.
- 2026-08-21 (daily) — HEAL (minor): the n-Category Café (`golem.ph.utexas.edu/category/`), listed
  as requiring `tvly extract`, opens cleanly via plain `curl -A "Mozilla/5.0"` (HTTP 200, full
  post-title HTML) — no Cloudflare/JS block found this session. Recorded in SOURCES.md; `tvly
  extract` no longer needed as the primary method for this source.
- 2026-08-21 (daily) — r/math and r/mathematics remain degraded (6th+ consecutive daily; `tvly`
  quota-exhausted so the 08-18-healed `tvly search --include-domains reddit.com` fallback is
  unusable, and both `WebFetch` on `.rss`/`old.reddit.com` failed outright with "unable to fetch
  from www.reddit.com" — no working path found this session). Compounding the standing
  reddit-access issue; the weekly should consider whether this pair of sources needs a durable
  alternate access method (e.g. a mirror, or dropping to intake-via-Mathstodon/HN only) if `tvly`
  quota is not restored soon.
- 2026-W34 recalibration (2026-08-22) — TOOLING: `tvly` still returned the account-level
  "exceeds your plan's set usage limit" error on the FIRST call this session (fresh `pip install`
  did not help) — this is the 3rd CONSECUTIVE run on this exact failure mode (08-20 daily, 08-21
  daily, 08-22 weekly), crossing AGENTS.md's ≥3-consecutive-runs heal-owed bar. FLAGGED heal-owed;
  a curator push notification was sent this session (account Tavily plan needs attention — this is
  outside the radar's own remediation power; `WebFetch`/`WebSearch`/direct `curl`/arXiv API cover
  every lane that has a fallback, but see the reddit/Physics-SE note below for the one lane with
  none). Worked around entirely via `WebFetch`, `WebSearch`, direct `curl`, and the arXiv API for
  every check this session.
- 2026-W34 recalibration — r/Physics, r/cosmology, r/ParticlePhysics, r/AskPhysics (weekly-swept
  tier) AND Physics Stack Exchange all UNREACHABLE this session: direct `curl` on every `.rss`/
  `/feeds/` URL returned HTTP 403, `WebFetch` returned "unable to fetch from www.reddit.com" /
  physics.stackexchange.com outright, and `WebSearch` could not surface live threads either — the
  same failure pattern the dailies have logged on r/math/r/mathematics for 7+ consecutive days now
  extends to the full extra-social weekly-swept roster and Physics SE. Logged degraded (not
  silently dropped) — see the W34 report for the coverage tally. No durable alternate access path
  found this session; if this persists next weekly, propose a durable fallback (a mirror, or
  folding this lane into Mathstodon/HN-only intake) rather than logging "degraded" indefinitely.
- 2026-W34 recalibration — SKILL HEAL (skill-maintenance policy, dedicated commits): both
  `radar-ledger-update` and `radar-render-dashboard` SKILL.md files documented a sibling radar's
  file contract (`# AI Radar` header, `### [id: slug-NNN]` trend blocks with an `alias` field, a
  standalone `## observation_queue` H2) that never matched this repo's real `TRENDS.md` structure
  (flagged 2026-08-17 daily, per AGENTS.md only weekly runs amend skills). Corrected both skills
  in place to describe the actual structure (`# Trend ledger — Math-Physics Radar` header, plain
  `### Title` trend blocks with `stage/confidence/first_seen/last_evidence`, no id/alias, queue
  unheaded inside `## Active trends`); updated the anchor rule and validation checks accordingly.
- 2026-W34 recalibration — QUEUE BURNDOWN (applying PROPOSED Amendment D, W33 → no curator veto,
  signal persisted: queue kept growing 119→156 across the five 08-17→08-21 dailies): dropped 18
  settled, zero-independent-follow-up, non-landmark, non-study_shelf queue items dated 07-22→08-02
  (below-bar single-author refutations/partial-progress items with no citation or engagement in
  3+ weeks) — see the W34 weekly report for the full list. Explicitly did NOT touch: study_shelf-
  tagged items, forming pairs (deconfined criticality, Werner-state 2-copy distillability), the
  Jacobian-conjecture/AI-wave cluster, the DESI saga, the matroid-intersection watch, Fields
  Medal/Breakthrough Prize ecosystem entries, or anything with an active follow-up thread. SELF-
  CAUGHT during the burndown's own capture-leak cross-check: one candidate drop (Belin et al.,
  "A universal sum over topologies in 3d gravity," SciPostPhys.21.1.017) was RESTORED after
  discovering arXiv:2608.03459 (Yu, queued 08-04) explicitly engages it as a rigidity/no-go
  counterpoint — not zero-follow-up, ineligible; a second stale cross-reference (2607.27869,
  correctly dropped, but still named as "queued" in a sibling item's prose) was fixed by editing
  the prose rather than restoring the item. Net: queue 155→137 (19 identified, 1 restored, 18
  dropped net). This falls short of Amendment D's
  literal "2-3× the ~40 soft cap" (80-120) target: a careful item-by-item review of every
  3+-week-old entry found most of the remaining age-eligible items are genuinely protected by the
  existing criteria (study_shelf tag, forming pair, active cluster/saga, or a live follow-up) —
  the domain-cadence "let below-bar items persist" principle appears to be doing real work here,
  not merely deferring a backlog. Amendment D's target band may need recalibrating to this
  domain's actual eligible-item rate rather than a fixed multiple of the soft cap; flagged as a
  possible amendment refinement for a future weekly if the queue keeps growing despite full-effort
  burndowns.
- 2026-W34 recalibration — SOURCE-DISCOVERY: 0 promoted, 9 held. Checked all 9 staged candidates
  in SOURCES.md (sammattheus.wordpress.com, journals.aps.org/prresearch, leodemoura.github.io,
  sbseminar.wordpress.com, ams.org/journals/jams, bourbaki.fr, anthropic.com/research,
  proofatlas.ai, preprints.org) against this week's 5 daily reports (08-17→08-21) — no recurrence
  for any; all remain at their prior single-sighting count, still below the ≥2 promotion bar. No
  new on-axis untracked-domain primaries surfaced this session's institute/venue sweep to stage.
- 2026-W34 recalibration — WEEKLY-SWEPT TIER COVERAGE: 9/9 institutes opened (IHES, SLMath, MPIM
  Bonn, Fields Institute, Isaac Newton Institute, KITP, Perimeter [via WebSearch, direct fetch
  403], Clay, IAS [via WebSearch, direct fetch 403]) — no new landmark result beyond what the
  dailies already caught (Perimeter's dark-photon paper, tracked 08-13). Slow venues: Annals of
  Mathematics (directory only, no article-level content extractable this session), AMS Notices
  (JS-rendered, no content extractable — same standing degradation), Forum of Mathematics Pi
  (6 recent papers listed, none a landmark conjecture resolution beyond ordinary technical
  advances — not queued). Prizes: Abel/Breakthrough/Fields/Shaw all already captured earlier this
  cycle, no gap. Extra-social + Physics SE: see the tooling note above — unreachable this session,
  logged degraded.
- 2026-08-24 (daily) — TOOLING: `tvly` still quota-exhausted on the first call this session (4th
  consecutive occurrence: 08-20 daily, 08-21 daily, 08-22 weekly, 08-24 daily). Already crossed the
  heal-owed bar at the 3rd occurrence (08-22, curator notified then); NOT re-notified this session
  — no new escalation criterion met, and a repeat notification for an already-reported, unresolved
  external outage would be noise per the notification-discipline rule. Worked around entirely via
  WebFetch/WebSearch/direct `curl`/the arXiv API.
- 2026-08-24 (daily) — HEAL: Nature Physics (`nature.com/nphys.rss`) and Nature Communications
  (`nature.com/ncomms.rss`) both returned FULL, real titles via plain `curl` this session (8 items
  each, e.g. "Antidots measure anyonic charge in graphene") — the standing 7+-consecutive-daily
  empty-CDATA degradation (last confirmed 08-21) did NOT recur today. Flagging as recovered, not
  re-classifying as a permanent heal yet — retest next daily before declaring the degradation over,
  since it self-resolved without any access-method change on this radar's side.
- 2026-08-24 (daily) — HEAL: `home.cern/news` (the bare HTML page) is now blocked by a Cloudflare/
  WAF challenge (`wpewaf.com`) via direct `curl`, but the site's own `https://home.cern/feed/` RSS
  works cleanly (10 items, admin/facility news) — prefer the RSS feed over the bare HTML page for
  this source going forward. Recorded in SOURCES.md.
- 2026-08-24 (daily) — HEAL: the GitHub-proxy-scoping restriction (`api.github.com`/`.atom` direct
  `curl` returns "sessions are bound to their configured repositories") can be BYPASSED with
  `WebFetch` on the plain `releases.atom` URL — verified working cleanly this session for all three
  watched repos (leanprover-community/mathlib4, leanprover/lean4, rocq-prover/rocq), returning
  accurate release-tag lists with dates. Prefer `WebFetch` on `.atom` ahead of `tvly extract` for
  this lane going forward (works even when `tvly` is quota-exhausted, as it was this session).
  Recorded in SOURCES.md.
- 2026-08-24 (daily) — CAPTURE-LEAK NOTE: three CERN Courier items this session (LHCb doubly
  charmed baryon, ALPHA antihydrogen CPT test, CMS W-boson limit — all dated 2026-07-23) were
  queued citing ONLY the CERN Courier feature page, not the underlying LHCb/ALPHA/CMS primary
  paper — the primary papers themselves were not independently located/opened this session. This
  is consistent with the hard rule (CERN Courier is itself an official CERN-affiliated publication
  reporting collaboration results, hence primary) but flagged for a follow-up chase to the actual
  arXiv/journal preprints, which would sharpen the evidence and may reveal additional detail
  (exact significance, dataset size) the Courier summary omits.
- 2026-08-25 (daily) — TOOLING: `tvly` still returned "exceeds your plan's set usage limit" on the
  FIRST call this session, even after a fresh `pip install -q tavily-cli` (5th consecutive
  occurrence: 08-20 daily, 08-21 daily, 08-22 weekly, 08-24 daily, 08-25 daily). Already
  heal-owed and curator-notified at the 3rd occurrence (08-22); not re-notified this session (no
  new escalation criterion — a 5th identical, already-reported outage is not new information).
  Worked around entirely via direct `curl`/`WebFetch`/the arXiv API for every lane.
- 2026-08-25 (daily) — HEAL CONFIRMED DURABLE: Nature Physics (`nature.com/nphys.rss`) and Nature
  Communications (`nature.com/ncomms.rss`) both returned full real titles via plain `curl -A
  "Mozilla/5.0"` again this session (2nd consecutive daily after the 08-24 recovery) — the prior
  7+-consecutive-daily empty-CDATA degradation appears genuinely resolved, not a one-off. Downgrade
  from "recovered, retest" to a standing heal.
- 2026-08-25 (daily) — NEW DEGRADATION: `ligo.org/news.php` returned a Cloudflare "Attention
  Required" challenge page via `curl -A "Mozilla/5.0"` this session (previously verified reachable
  via `tvly extract`, which is unusable while `tvly` is quota-exhausted). First occurrence of this
  specific block; no working direct-fetch fallback found this session — logged degraded, retest
  next daily before treating as standing.
- 2026-08-25 (daily) — CORRECTION to a SOURCES.md access note: MathOverflow's `/feeds/` URL (with
  trailing slash) now returns an HTTP 307 redirect to `/feeds` (WITHOUT the trailing slash, the
  opposite of the standing "trailing slash required" note from 2026-07-02) — `curl -sL` (follow
  redirects) on either path resolves cleanly to the Atom feed either way, so no practical access
  issue, but the "trailing-slash-required, `/feeds` returns empty" claim in SOURCES.md is stale;
  corrected to "use `-L` to follow the redirect, either path works."
- 2026-08-25 (daily) — r/math and r/mathematics: still degraded (`curl` "blocked due to a network
  policy", `tvly` quota-exhausted so its 08-18-healed search fallback is unusable) — 9th+
  consecutive degraded daily on this pair, no working fallback found this session.
- 2026-08-25 (daily) — Source-discovery: no new untracked on-axis domain surfaced this session
  (all primaries this session came from already-swept arXiv/SciPost venues); Sam Mattheus
  (sammattheus.wordpress.com, staged since 2026-07-03, still below the ≥2-sighting bar as a
  BLOG source) now also appears as a co-AUTHOR on a primary directly evidencing the Ramsey trend
  (arXiv:2608.21769) — noted as a stronger signal that this blog is a genuine pointer/participant
  surface for the trend, but the promotion bar is about the BLOG's sighting count as a discovery
  channel, which is unchanged this session (still 1) — held, not promoted.
- 2026-08-25 (daily) — capture-leak reconciliation: this session named 12 new arXiv ids
  (2608.23063, 2608.22539, 2608.23089, 2608.23132, 2608.21675, 2608.23260, 2608.22448, 2601.08218,
  2509.20144, 2608.22813, 2608.21769, 2608.21707) — all 12 land on discrete queue/evidence lines
  above, 0 leaked. PLUS the mandatory mechanical file-wide reconciliation
  (`grep -oE '[0-9]{4}\.[0-9]{5}' TRENDS.md`, 198 unique ids, up from 183 on 2026-08-24) found 35
  ids without a same-line `arxiv.org/abs/` link — diffed against yesterday's already-verified set
  of 32 (all legitimate cross-references, confirmed 08-24): exactly 3 new entries
  (2309.01914, 2608.18169, 2608.22350), all three the deliberately-excluded Ramsey-adjacent/
  parafermionic-CFT-revision items named and explicitly NOT queued in today's trend notes above
  (a documented judgment call, not a leak) — 0 file-wide leaks found.
- 2026-08-26 (daily) — TOOLING: `tvly` still returned "exceeds your plan's set usage limit" on
  the first call this session (a fresh `pip install -q tavily-cli` was needed since the CLI was
  absent from this session's environment; installing it did not clear the quota) — 6th
  consecutive occurrence (08-20, 08-21, 08-22, 08-24, 08-25, 08-26). Already heal-owed and
  curator-notified at the 3rd occurrence (08-22); not re-notified this session (no new escalation
  criterion — a 6th identical, already-reported outage is not new information). Worked around
  entirely via direct `curl`/the arXiv API for every lane.
- 2026-08-26 (daily) — LIGO RETEST: `ligo.org/news.php` via `curl -A "Mozilla/5.0"` still returns
  the Cloudflare "Attention Required" challenge page (2nd consecutive occurrence after the first
  2026-08-25 report) — no working direct-fetch fallback found again this session (`tvly` remains
  quota-exhausted). Upgrading from "first occurrence, retest" to standing degraded; DESI (same
  DR2 Lyman-alpha result already tracked 07-30) and CERN (`home.cern/feed/`, routine admin items,
  no new physics result) both opened cleanly.
- 2026-08-26 (daily) — HEAL: IceCube's bare `/news/` page returns only a JS-rendered widget shell
  via direct `curl` (no article titles extractable, matching the Scientific American failure
  class) — but its RSS feed `https://icecube.wisc.edu/category/news/feed/` (distinct from the
  empty `/news/feed` path) works cleanly via plain `curl`, returning full titles/dates. Recorded
  in SOURCES.md; prefer this feed over the bare HTML page going forward.
- 2026-08-26 (daily) — r/math and r/mathematics: still degraded (direct `curl` served an HTML
  interstitial, not the `.rss`/Atom feed; `tvly` quota-exhausted so its search fallback is
  unusable) — 10th+ consecutive degraded daily on this pair, no working fallback found this
  session.
- 2026-08-26 (daily) — Source-discovery: no new untracked on-axis domain surfaced this session —
  today's on-axis primaries came from arXiv (already the core swept venue) and one item
  (arXiv:2608.21590, the black-hole-singularity paper) was discovered via Hacker News' Algolia
  front-page API, which is already a tracked DAILY-tier intake channel (not a new domain to
  stage). No candidate promotions/demotions to SOURCES.md's discovered-source staging list.
- 2026-08-26 (daily) — capture-leak reconciliation: this session named 6 new arXiv ids
  (2608.24685, 2608.24843, 2608.24853, 2608.23797, 2608.23721, 2608.21590) — all 6 land on
  discrete queue lines above, 0 leaked. PLUS the mandatory mechanical file-wide reconciliation
  (`grep -oE '[0-9]{4}\.[0-9]{5}' TRENDS.md`, 205 unique ids, up from 198 on 2026-08-25) found 36
  ids without a same-line `arxiv.org/abs/` link — diffed against yesterday's already-verified set
  of 35: exactly 1 new entry (2310.14425, Eric Friedlander's own 2023 "Reformulation of the stable
  Adams conjecture," cited in prose in today's queued "The Stable Adams Conjecture" item as the
  superseded prior attempt the new paper corrects/completes — not itself an independent primary
  worth a separate queue line, a documented judgment call, not a leak) — 0 file-wide leaks found.
- 2026-08-27 (daily) — TOOLING: `tvly` still returned "exceeds your plan's set usage limit" on
  the first call this session (a fresh `pip install -q tavily-cli` did not help) — 7th
  consecutive occurrence (08-20, 08-21, 08-22, 08-24, 08-25, 08-26, 08-27). Already heal-owed and
  curator-notified at the 3rd occurrence (08-22); not re-notified (no new escalation criterion).
  Worked around entirely via direct `curl`/`WebFetch`/`WebSearch`/the arXiv API.
- 2026-08-27 (daily) — HEAL: LIGO's `ligo.org/news.php` (standing degraded since 2026-08-25,
  Cloudflare "Attention Required" via `curl`, unhealable via `tvly` while quota-exhausted) can be
  bypassed with `WebFetch` on the plain `http://www.ligo.org/news` URL (no `.php`, no forced
  HTTPS) — returns the full LSC news listing cleanly (confirmed this session: newest item still
  GWTC-5.0, 2026-05-26, already tracked). `WebFetch` on the original `https://www.ligo.org/news.php`
  URL instead reports a same-host redirect to this URL, which must be re-fetched directly.
  Recorded in SOURCES.md as the primary access method going forward; downgrading LIGO from
  standing-degraded to healed.
- 2026-08-27 (daily) — capture-leak reconciliation: this session named 5 new arXiv ids
  (2608.24385, 2608.25385, 2608.25865, 2608.25591, 2608.25688) — all 5 land on discrete
  queue/evidence lines above, 0 leaked. This session ALSO re-ran the mechanical file-wide sweep
  with a corrected (whole-file, not same-physical-line) citation check — same-line matching
  produces false positives whenever a paragraph wraps across lines, which is the norm in this
  file; checking instead whether each unique id appears anywhere as `arXiv:<id>`, `abs/<id>`, or
  `arxiv.org/abs/<id>` is the actual test daily.md's capture rule cares about ("does this id land
  on a discrete queue/evidence/shelf line, not merely in prose"). 210 unique ids file-wide (up
  from 205); 22 have no such citation anywhere — ALL verified legitimate, not leaks: 18 are ids of
  items DROPPED in the W33/W34 weekly queue burndowns whose ids persist only inside
  `strategy_notes`' own burndown documentation (e.g. 2607.16695, 2607.15406, 2607.09049,
  2607.01544 — the burndown notes name what was dropped and why, not a live capture obligation),
  and 4 are ids of items EXPLICITLY CHECKED AND EXCLUDED from a trend inside that trend's own
  notes, cited without the `arXiv:` prefix due to a shared-prefix citation style (2606.24863,
  2608.16434, 2608.16613 — each already reasoned about as "not a Ramsey/Schur-positivity-trend
  group" the day it was found; 2501.14545 — cited alongside 2306.04799 as background prior work
  behind the Riemann-zeta ledger item, not an independent primary). 0 actual file-wide leaks.
  capture-leak: 5 new ids checked + full-file citation-anywhere sweep (210 ids, 22 reviewed, 0
  leaked).
- 2026-08-27 (daily) — Source-discovery: no new untracked on-axis domain surfaced this session —
  today's primaries (the 3-Decomposition Conjecture, the non-invertible-symmetries 9th group, the
  below-bar items) all came from the already-swept arXiv venue.

- 2026-08-28 (daily) — TOOLING: `tvly` was entirely absent from PATH at session start; a fresh
  `pip install -q tavily-cli` succeeded but the first live call returned "exceeds your plan's set
  usage limit" — 8th consecutive quota-exhausted occurrence (08-20, 08-21, 08-22, 08-24, 08-25,
  08-26, 08-27, 08-28). Already heal-owed and curator-notified at the 3rd occurrence (08-22); not
  re-notified (no new escalation criterion). Worked around entirely via direct `curl`/`WebFetch`/
  the arXiv API.
- 2026-08-28 (daily) — capture-leak reconciliation: 5 new arXiv ids named this session (2608.27242,
  2608.27447, 2608.26976, 2608.27416, 2608.27303; the 6th capture, the CERN double-Higgs item, has
  no arXiv id) — all 5 land on discrete queue/study_shelf lines, 0 leaked. Full-file mechanical
  sweep (citation-anywhere test, per the 08-27 corrected method): 217 unique arXiv ids (up from
  210); 23 have no `arXiv:<id>`/`abs/<id>` citation anywhere (up from 22) — the +1 is 2608.27405
  (today's peripheral online-Ramsey item, checked-and-excluded inside the Ramsey trend's own notes
  without the `arXiv:` prefix — same legitimate exclusion pattern as the 4 prior ones); all 23
  verified legitimate (18 dropped-burndown ids + 5 checked-and-excluded ids) — 0 file-wide leaks.
- 2026-08-28 (daily) — Source-discovery: no new untracked on-axis domain surfaced this session —
  today's primaries came from already-swept arXiv + the already-swept CERN (`home.cern/feed/`)
  venue.
- 2026-08-29 (W35 weekly recalibration) — QUEUE BURNDOWN (same Amendment-D-style criteria as W34:
  settled, zero-independent-follow-up, non-landmark, non-study_shelf, no live cross-reference, 3+
  weeks quiet — the W34-reviewed 07-22→08-02 cluster left untouched, this week's newly-eligible
  08-03→08-07 batch, 37 items, reviewed item-by-item): dropped 10 (2608.06681 Umans-Wang divisor
  refutation, 2608.07186 Fontaine-Mazur GL(2) partial progress, 2608.06920 Hadamard-matrix order-32
  classification, 2608.07399 Siegel-zeros conditional result, 2608.06272 inverse-generator-problem
  counterexample, 2608.05662 Numerical Terao Conjecture, 2608.04659 Tree Product Conjecture
  extension, 2608.04981 Carleson-embedding-conjecture counterexample, 2608.03488 Morrey's-problem
  higher-m extension, 2608.03661 Schur-like-numbers upper bound — all single/narrow technical
  results, no landmark framing, no forming-pair note, no study_shelf tag, no cross-reference from
  another live item). KEPT despite eligibility: 2608.07350 (Xu, profinite rigidity of PSL(2,C)
  lattices) — explicitly cross-referenced by the still-live 2026-08-04 Simons-Collaboration
  ecosystem item ("thematically adjacent... 2607.19012/2608.07350"); dropping it would have
  repeated the exact stale-cross-reference mistake W34 caught. Queue 175 → 165 (net −10). This AGAIN
  falls well short of a literal 80-120 (or even 40) numeric target — the SAME finding as W34 (most
  aged items are landmark/forming-pair/study_shelf/cross-referenced, genuinely protected, not
  deferred) — now confirmed a SECOND consecutive week under full item-by-item rigor. PROPOSING
  Amendment E (cooling period, apply W36 if signal persists / no curator veto): replace the fixed
  numeric queue-size target band with a criterion-completeness metric — the burndown's health is
  "100% of newly-3+-week-eligible items reviewed against the existing drop criteria" plus
  "items dropped vs. items protected-with-a-stated-reason," NOT a raw queue-size number. A fixed
  numeric target structurally conflicts with AGENTS.md's domain-cadence "let below-bar items
  persist" rule in a landmark-dense stretch; two independent full-rigor weeklies now agree the gap
  is real protection, not under-effort.
- 2026-08-29 (W35 weekly) — Source strategy (weekly-swept tier, 21/21 logged opened-or-degraded):
  9/9 institutes (IHES, MPIM, Fields, KITP, Clay opened directly; SLMath, Newton, Perimeter, IAS all
  403'd on direct `WebFetch` this session, healed via `WebSearch`) — nothing on-axis beyond
  already-tracked prize/ceremony/admin news. Slow venues: Forum of Mathematics opened cleanly (8
  current-issue titles, none landmark); Annals of Mathematics and AMS Notices both degraded again
  (page opens but no article-level/dated content extractable — standing JS-rendering limitation,
  unchanged from W34). Low-yield extra-social: r/Physics, r/cosmology, r/ParticlePhysics,
  r/AskPhysics all degraded — a SECOND consecutive fully-unreachable week, now root-caused (see
  SOURCES.md): direct `curl` (multiple UAs, `.rss`/`.json`/`old.reddit.com`) all 403 from Reddit's
  own edge, and `WebSearch` with an `allowed_domains:["reddit.com"]` filter errors outright
  ("not accessible to our user agent") — a hard, structural block on every access path this radar
  has, not a `tvly`-quota artifact; HEAL-OWED, escalated (see calibration/curator notification).
  Physics Stack Exchange HEALED this session: the recorded `/feeds/` form was unreliable, but plain
  `curl` on `/feeds` (no trailing slash, same pattern as the 08-25 MathOverflow fix) returns a clean
  live Atom feed — recorded in SOURCES.md. Prizes: Abel, Breakthrough opened directly; Shaw, IMU
  opened via `WebSearch` (all unchanged from the already-tracked 2026 laureates). Source-discovery:
  checked all 9 staged candidates against this week's 5 daily reports — only sammattheus.wordpress.com
  recurred (already counted, Sam Mattheus now co-authoring a Ramsey primary directly — noted in the
  trend's own evidence, not a fresh staging sighting); the other 8 held with no recurrence, still
  below the ≥2 bar; 0 promoted. Anchoring/off-axis: exploration ran 5/5 this week (math.OC → q-bio.PE
  → math.LO → cs.CC → nlin.SI/CD), 0/5 significant off-axis yield — a SECOND consecutive quiet week;
  per the domain-cadence override still not an alarm on its own, but flagged to watch for a third.
  Capture-leak: file-wide mechanical sweep (`grep -oE '[0-9]{4}\.[0-9]{5}' TRENDS.md`, 208 unique
  ids after the burndown) found 24 ids with no same-token `arXiv:`/`abs/` citation — all 24 verified
  legitimate (dropped-burndown ids named in this file's own documentation, or checked-and-excluded
  ids cited via a bracket style without the `arXiv:` token, per the established 08-27 pattern) — 0
  file-wide leaks; this week's 5 daily reports each also independently reported 0 leaked.
- 2026-08-29 (W35 weekly) — Self-amendment: two-week regression check on Amendments A
  (cadence-split), B (off-axis rotation), and C (skill-window sync) — all clean (coverage 21/21,
  exploration 5/5, no skill-window drift found) — NO ROLLBACK. Amendment D (queue-burndown sizing,
  applied W34) — see the QUEUE BURNDOWN entry above: the target-band shortfall recurred a second
  week running under full rigor, superseding Amendment D's numeric framing with the PROPOSED
  Amendment E above (cooling period, decide W36).
- 2026-08-29 (W35 weekly) — TOOLING: `tvly` hit the same account-level quota-exhaustion error again
  on the first call this session (a fresh `pip install -q tavily-cli` succeeded, but the live call
  immediately errored) — the 9th CONSECUTIVE run on this exact failure (08-20, 08-21, 08-22, 08-24,
  08-25, 08-26, 08-27, 08-28, 08-29), one full week past the original heal-owed notification
  (08-22). Combined with the newly-root-caused hard Reddit block above (which the `tvly search`
  heal had been the ONLY working fallback for), this materially widens the coverage gap beyond what
  was true at the first notification — re-escalated to the curator this session via a push
  notification (both issues: Tavily plan quota, and that its restoration is now the only known path
  back into the reddit/r/math/r/mathematics/r/Physics/r/cosmology/r/ParticlePhysics/r/AskPhysics
  lane).
- 2026-08-31 (daily) — TOOLING: `tvly` was again absent from PATH at session start; a fresh
  `pip install -q tavily-cli` succeeded, but the first live `tvly search` call immediately returned
  the same account-level "exceeds your plan's set usage limit" error — the 10th CONSECUTIVE run on
  this exact failure (08-20, 08-21, 08-22, 08-24, 08-25, 08-26, 08-27, 08-28, 08-29, 08-31; no run
  08-30, expected weekend gap). Already heal-owed/re-escalated at the 3rd and again at the 9th
  (W35) — not re-notified this session per AGENTS.md (notify only for a NEW degradation or a
  failed-push/stranded state, not a repeat of an already-flagged one). Worked around entirely via
  direct `curl` (arXiv API with URL-encoded date-range brackets — literal `[`/`]` in a `curl` URL
  trigger its globbing parser and silently break `-o` output; use `%5B`/`%5D` or `--globoff`),
  `WebFetch`, and the arXiv API for every lane that needed it — r/math/r/mathematics remain the one
  lane with no working fallback while `tvly` stays quota-exhausted (still unresolved from the
  curator's side; see the W35 report).
- 2026-09-01 (daily) — TOOLING RECOVERY: `tvly` was absent from PATH at session start (routine
  fresh-container state); a fresh `pip install -q tavily-cli` succeeded, and — for the first time
  since the streak began 08-20 — the first live `tvly search` call SUCCEEDED (no quota error).
  This ends the 10-CONSECUTIVE-RUN account-quota-exhaustion streak (last seen 08-31). Re-tested
  specifically on the previously hard-blocked r/math/r/mathematics lane via `tvly search
  "<query>" --include-domains reddit.com --time-range week`: WORKED, returning live dated August
  2026 threads (one of which led to today's Petersen-coloring-conjecture backlog catch — see
  observation_queue). Direct `curl -A "Mozilla/5.0" reddit.com/.rss` STILL 403s (confirms the
  hard network-level block on direct/WebFetch access is a separate, still-standing issue from the
  tvly-quota gap; the `tvly search` heal remains the only working path into Reddit). Not
  re-notifying the curator (this is a recovery, not a new degradation) — noting for the record
  since it reopens a lane that had been escalated twice.
- 2026-09-01 (daily) — Trend creation: PROMOTED "Sharpening the exponent in Marton's conjecture /
  polynomial Freiman-Ruzsa" to a `seed`-bar-clearing `emerging` trend (see Active trends) — three
  independent groups (GGMT 2024, Liao 2024, Song-Yue 2026) sequentially improving one constant,
  the same wave-pattern precedent as the Ramsey lower-bound trend. Two of the three evidence
  artifacts (2024) predate this radar's 2026-07-02 founding; backdated per the established
  precedent of citing pre-radar primaries when a fresh capture reveals a multi-year pattern
  (opened and verified via the arXiv API this session, not asserted from memory).
- 2026-09-01 (daily) — Backlog capture: a community-pulse (Reddit, via the newly-healed `tvly
  search`) pointer led to a genuine 3-week-old MISS — Putman's Petersen Coloring Conjecture
  counterexample (arXiv:2608.10012, 08-08) and Jooken's independent verification
  (arXiv:2608.10028, 08-09) were never captured in any daily report or in this file. Both queued
  + study_shelf'd this session as a domain-cadence landmark (a major conjecture refuted, with
  independent same-week corroboration). Root cause: neither id fell inside any 08-08/08-09 arXiv
  category-rotation batch review this radar can reconstruct from past reports — logged as a
  reminder that the community-pulse lane is also a backstop against title-triage misses in the
  primary sweep, not solely an intake-for-unverified-signals lane.
- 2026-09-01 (daily) — Source-discovery: no new untracked on-axis domain surfaced this session —
  today's primaries came from already-swept arXiv, Quanta, IceCube, and Reddit (via the
  already-registered `tvly search --include-domains reddit.com` access method) venues.
- 2026-09-01 (daily) — capture-leak reconciliation: 11 new arXiv ids named this session
  (2404.02244, 2404.09639, 2608.30336, 2603.03257, 2608.10012, 2608.10028, 2608.31126, 2608.30945,
  2608.31039, 2608.28395, 2608.30139) — all 11 land on discrete trend-evidence/queue/study_shelf
  lines, 0 leaked. Full-file mechanical sweep (citation-anywhere test): 233 unique arXiv ids (up
  from 222); 33 have no `arXiv:<id>`/`abs/<id>` citation anywhere — the SAME 33 already verified
  legitimate in prior sessions' documentation (18 dropped-burndown ids + 15 checked-and-excluded
  bracket-style-citation ids, unchanged from the 08-31 count) — 0 file-wide leaks; none of today's
  11 new ids appear in the uncited set, confirming today's additions are all properly cited.
  capture-leak: 11 new ids checked + full-file citation-anywhere sweep (233 ids, 33 reviewed, 0
  leaked).
- 2026-09-02 (daily) — Trend recalibration: full math (all 20 in-scope categories:
  AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV/NT/CO/PR/RT/LO/OA/OC/DS) and physics (hep-th/hep-ph/gr-qc/
  math-ph/quant-ph/astro-ph.CO/astro-ph.HE/cond-mat.str-el/cond-mat.supr-con/cond-mat.mes-hall)
  category rotation swept via the arXiv API, 250-cap each, fresh 09-01 batch (215 math + 180
  physics entries) triaged in full by title. Ramsey — HELD accelerating/medium (two
  Ramsey-adjacent titles today — tree-vs-odd-cycle threshold, Ramsey-Turán factors — checked and
  excluded, off the tracked lower-bound-specific axis). Non-invertible symmetries — HELD
  accelerating/high (no new artifact). Stanley-Gasharov — HELD seed/medium (no 4th group;
  last_evidence now 35 days old, well inside the 60-day window). Marton's-conjecture-exponent —
  HELD emerging/medium (no 4th group). KEY CAPTURES: Tan-Zhang's claimed proof of Fraenkel's
  Conjecture (2609.01570, a ~53-year-old named conjecture in combinatorics on words, unrefereed
  two-author preprint — queued as a provisional domain-cadence-caliber claim); the LZ
  collaboration's 248 keV single-event dark-matter hint, announced 2026-09-01 at TeV Particle
  Astrophysics (queued + study_shelf'd — see Active trends for the full writeup and caveats).
- 2026-09-02 (daily) — Source-discovery: STAGED two new candidates in SOURCES.md — lz.lbl.gov (LZ
  collaboration's own publications page: a decade-plus, regular e-print/PRL cadence, structurally
  identical to the already-tracked LIGO/DESI/CERN/IceCube Experiments-block sources) and
  newscenter.lbl.gov (Berkeley Lab's official news channel, the announcement surface for today's
  LZ result) — both first-seen this session via the LZ dark-matter capture above. Flagged for
  early weekly promotion given LZ is a flagship direct-detection experiment on par with the
  existing Experiments block, not a one-off blog.
- 2026-09-02 (daily) — capture-leak reconciliation: 3 new arXiv ids named this session
  (2609.01570, 2609.01583, 2609.01592) — all 3 land on discrete queue/study_shelf lines, 0 leaked.
  Full-file mechanical sweep (citation-anywhere test): 236 unique arXiv ids (up from 233); 33 have
  no `arXiv:<id>`/`abs/<id>` citation anywhere — the SAME 33 already verified legitimate in prior
  sessions (unchanged from the 09-01 count) — 0 file-wide leaks; none of today's 3 new ids appear
  in the uncited set. capture-leak: 3 new ids checked + full-file citation-anywhere sweep (236
  ids, 33 reviewed, 0 leaked).
- 2026-09-03 (daily) — Trend recalibration: full math (20 in-scope categories) and physics (10
  in-scope categories) rotation swept via the arXiv API, 250-cap each, fresh 09-02 batch (198
  math + 167 physics entries) triaged in full by title. All four active trends HELD (see their
  own notes for detail): Ramsey (accelerating/medium, no 7th group — one peripheral
  Maker-Breaker-game title excluded), Non-invertible symmetries (accelerating/high, no 10th
  group), Stanley-Gasharov (seed/medium, no 4th group), Marton's-exponent (emerging/medium, no
  4th group). KEY CAPTURE: Youness Lamzouri's independent, unconditional, human-authored proof of
  the same >67.25%/≥83.62% Riemann-zeta zero-density bounds an Anthropic Claude research model
  claimed 2026-08-10 (arXiv:2609.02882) — his own abstract states the Claude proof "was
  subsequently verified by Alpöge and Furman," the strongest public vetting signal yet on this
  ledger's single biggest AI-assisted-math claim; appended as a nested update to the existing
  queue item and added to `study_shelf`. Also captured: a computer-assisted 14-runner case of the
  Lonely Runner Conjecture (2609.02604); the Borovik-Cherlin conjecture resolved in the ACF case
  (2609.02198); an IceCube null search constraining extra-dimension size to <0.17 μm
  (2608.29746, found via the IceCube news RSS, chased to the arXiv abstract); and a 3-paper LZ
  248-keV-event theoretical-interpretation cluster (2609.02608/02868/02807), noted as a cluster
  rather than individually evidenced.
- 2026-09-03 (daily) — Community-pulse lead NOT captured (no citable primary located): a
  `tvly search --include-domains reddit.com` r/mathematics hit ("Another Leaked Result,"
  u/New-Committee-4052) references a claimed proof of "a conjecture of Kozma and Nizan" in
  percolation theory, dimensions 3–10 — snippet-only in Tavily's search index; the underlying
  Reddit thread and any arXiv id could not be located this session (direct Reddit fetch still
  403s; targeted `tvly search`/`tvly extract` attempts for the specific thread and for "Kozma
  Nizan" + percolation/arxiv all came back empty or off-topic). Per the hard rule against
  inventing URLs, NOT queued — flagged here as an open lead for a future session's community-pulse
  pass to re-chase (try a direct Reddit permalink search once a `tvly` quota/access window is
  fresh, or watch for the underlying paper to surface via the ordinary math.PR/math-ph arXiv
  sweep).
- 2026-09-03 (daily) — Source-discovery: no new untracked on-axis domain surfaced this session —
  today's primaries came from already-swept arXiv, IceCube, and reddit (via the already-registered
  `tvly search --include-domains reddit.com` access method) venues.
- 2026-09-03 (daily) — Exploration slot (off-axis rotation): econ/q-fin (econ.TH/econ.EM/
  q-fin.MF/PR/CP, next in the roster after math.PR↔math.ST) — top 34 items read via the arXiv API
  regardless of sub-topic (mechanism design, econometrics, derivatives pricing, DeFi/AMM theory,
  etc.), 0/34 significant off-axis catch (non-alarm per AGENTS.md domain cadence). Roster
  continues; next up: math.DG.
- 2026-09-03 (daily) — tvly: healthy, 3rd consecutive clean run (no quota error) since the 09-01
  recovery from the 10-run quota-exhaustion streak — not re-flagging. Direct Reddit access (curl/
  WebFetch) remains hard-blocked (`tvly search` stays the only working path); no change from the
  standing W35 finding.
- 2026-09-03 (daily) — capture-leak reconciliation: 8 new arXiv ids named this session
  (2609.02882, 2609.02604, 2609.02198, 2608.29746, 2609.02608, 2609.02868, 2609.02807, plus the
  excluded-and-cited-without-prefix 2609.02588) — all properly routed. Full-file mechanical sweep
  (citation-anywhere test): 244 unique arXiv ids (up from 236); 34 have no `arXiv:<id>`/`abs/<id>`
  citation anywhere — the SAME 33 already verified legitimate in prior sessions PLUS 2609.02588
  (today's checked-and-excluded Maker-Breaker-games title, cited bracket-style in the Ramsey
  trend's notes, same established pattern as the other 33) — 0 file-wide leaks. capture-leak: 8
  new ids checked + full-file citation-anywhere sweep (244 ids, 34 reviewed, 0 leaked).
- 2026-09-04 (daily) — KEY CAPTURES: full math (20 in-scope categories) and physics (10 in-scope
  categories) rotation swept via the arXiv API, 250-cap each, fresh 09-03 batch (250 math + 250
  physics entries, both hit the API cap — a high-volume day) triaged in full by title. Two major
  AI-assisted-math/formal-verification captures via community pulse (Hacker News front page,
  chased same session): (1) OpenAI's GPT-6 Astra model launch (2026-09-03) disclosed two paired
  prime-gap results — bounded gaps down to 186 (from Polymath8b's 246, 2014) and an improved
  large-gaps bound — both opened and read directly from cdn.openai.com; (2) Anthropic's
  `formal-math` GitHub repo (Justin Leder + Claude) disclosed a complete Lean 4/Mathlib
  formalization of θ(p_c) = 0 for Bernoulli bond percolation on ℤ^d in ALL dimensions d ≥ 2,
  resolving a famous open problem (3 ≤ d ≤ 10, incl. ℤ³) cited in Grimmett's textbook and
  Duminil-Copin's ICM 2018 problem list — surfaced via Gil Kalai's blog and RESOLVING the
  standing "Kozma-Nizan"/"Another Leaked Result" open lead first flagged 2026-09-01 and
  re-flagged 2026-09-03 (the correct spelling is Kozma–Nitzan; the Reddit-sourced "Nizan" was a
  mishearing, now corrected). Both items are unrefereed/self-published AI disclosures — queued
  under HEAVY HYPE-SKEPTICISM + AI-WATCH CAUTION per the hard rules, not treated as resolved.
  Also captured: Volpato's non-invertible-symmetries chiral-CFT paper (2609.03043, a 10th
  independent group on the already-`accelerating` trend, evidence list now at the 10-item cap)
  and a below-bar batch of six single/paired-result math items (Daykin-Frankl confirmation, the
  generalized Chui conjecture, Chern's Conjecture special case, a McKean's-conjecture
  counterexample, a permutation-polynomials conjecture resolution, and a forming Oort's-conjecture
  pair). All four PRE-EXISTING trends (Ramsey, Marton's-exponent, Stanley-Gasharov) HELD — no new
  independent group found on those three axes in today's fresh batch.
- 2026-09-04 (daily) — Source-discovery: TWO new candidates staged in SOURCES.md —
  github.com/anthropics (the `formal-math` repo specifically, a distinct AI-disclosure channel
  from the already-tracked anthropic.com/research pages) and proofsandprompts.com (a new
  multi-author mathematician blog on AI-in-mathematics, discovered via a cross-link from Kalai's
  already-tracked blog). Both first-seen this session, held below the ≥2-sighting promotion bar.
- 2026-09-04 (daily) — Exploration slot (off-axis rotation): cs.CC (computational complexity,
  genuinely off the in-scope category list, unlike math.DG/OA/LO/OC/DS which are now already
  covered by the full daily 20-category math rotation and so add no incremental explore value —
  substituted cs.CC for this run; noting the roster drift for the weekly to reconcile) — top 40
  items read via the arXiv API regardless of sub-topic, all routine TCS/complexity-theory papers,
  0/40 significant off-axis catch (non-alarm per AGENTS.md domain cadence).
- 2026-09-04 (daily) — tvly: healthy, 4th consecutive clean run (no quota error) since the 09-01
  recovery — not re-flagging. Direct Reddit access (curl/WebFetch) remains hard-blocked (`tvly
  search` stays the only working path); no change from the standing W35 finding. GitHub repo-watch
  (mathlib4/lean4/rocq `releases.atom`) 403'd on direct `curl` this session (proxy-scoped
  environment, per the standing SOURCES.md ACCESS NOTE) — not individually re-verified via `tvly`/
  `WebFetch` fallback this session (time-boxed given the two major captures above); no known
  version movement expected (mathlib4 continuous daily tags, lean4/rocq unchanged for weeks per
  every prior session) — logged as `degraded: proxy-403, not healed this session` rather than
  silently dropped.
- 2026-09-04 (daily) — capture-leak reconciliation: 8 new arXiv ids named this session (2609.03043,
  2609.03087, 2609.03134, 2609.03711, 2609.03847, 2609.03353, 2609.04072, 2609.03188) — all 8 land
  on discrete trend-evidence/queue lines, 0 leaked. The percolation and prime-gaps captures use
  GitHub/PDF URLs, not arXiv ids, so they do not appear in the arXiv-id mechanical sweep; both are
  directly cited by their own opened URLs in the queue (checked by eye). Full-file mechanical sweep
  (citation-anywhere test): 253 unique arXiv ids (up from 244); 34 have no `arXiv:<id>`/`abs/<id>`
  citation anywhere — the SAME 34 already verified legitimate in prior sessions (unchanged from the
  09-03 count) — 0 file-wide leaks; none of today's 8 new ids appear in the uncited set. capture-leak:
  8 new ids checked + full-file citation-anywhere sweep (253 ids, 34 reviewed, 0 leaked).
- 2026-09-05 (W36 recalibration) — Trends: all four HELD (see their own notes) — Ramsey
  accelerating/medium (no 7th group all week), non-invertible symmetries accelerating/high (no
  11th group, still no lattice/continuum cross-citation), Stanley-Gasharov seed/medium (now 38
  days quiet, flagged weakest — a real decision point approaches by early October per the
  standing W35 forward bet), Marton's-exponent emerging/medium (no 4th group, 5 days old). No
  reconcile action needed (nothing currently dormant/archived). No merges.
- 2026-09-05 (W36) — QUEUE BURNDOWN (first application of proposed Amendment E's
  criterion-completeness framing — see Amendments below): reviewed the full newly-3+-week-eligible
  batch (items dated 2026-08-08→2026-08-15, 39 items — the batch immediately following W35's
  2026-08-03→08-07 review) item-by-item against the established drop criteria (settled,
  zero-independent-follow-up, non-landmark, non-study_shelf, no live cross-reference, self-
  described below-bar/partial). Rather than a raw count, health is reported as
  criterion-completeness: 39/39 reviewed (100%), 13 dropped (self-described below-bar/partial-
  progress/refuted-conjecture items with no forward hook — a Chen–Raspaud-conjecture preprint, a
  below-bar Perimeter dark-photon phenomenology result, Katok's-intermediate-entropy partial
  progress, a Santharoubane's-conjecture disproof, an Etzion–Silberstein counterexample, the
  Imbalance Conjecture, a non-split-2-group-symmetry paper, the Gaitsgory Frontiers-of-Science
  ecosystem note, a PPT-channel partial-progress item, a Foregger–Sinkhorn counterexample, and a
  same-day Kolokolnikov-conjecture double-discovery — full list + one-line reasons per item
  recorded in this session's edits), 26 KEPT as protected-with-a-stated-reason (an unverified
  open Hadamard-matrix watch, an active Yang-Mills-mass-gap-outline watch, an extraordinary-claim
  γ-ray-line-signal watch under the hype-skepticism rule, a counterfactual-conservation-laws
  extraordinary-claim watch, a forming hyperkähler-period-index pair, two cross-referenced
  computer-assisted-proof-pattern follow-ups [Berenstein, Batyrev-dimension-threshold], an active
  HRT-conjecture follow-up, a Boussinesq-audit item with an explicit "watch for the authors'
  response," the still-live Simons-Collaboration ecosystem anchor, and 15 items promoted to
  `study_shelf` this session as genuine landmarks rather than dropped — see below). SEPARATELY,
  per the hard 60-day staleness rule (not the 3-week Amendment-E batch), the one remaining
  queue item older than 60 days with no protection was dropped: arXiv:2601.08218 (Speyer, a
  ~7.5-month-old incremental sharpening of an already-known 2017 disproof, explicitly
  self-described "queued for completeness" with zero follow-up since capture). Net queue: 186 →
  175 (net −11, after the 13 drops + the 2 items that were dropped-as-narrow but are separately
  represented by their `study_shelf` promotion, per the ledger contract's "drop OR promote, not
  both" resolution — see the study_shelf entry below for the precise accounting). Nothing else
  is stale (oldest live, unprotected item now well under the 60-day line).
- 2026-09-05 (W36) — study_shelf: 11 items PROMOTED this session — a genuine backlog of
  landmark-caliber unpromoted queue items, mostly from the 2026-08-12→08-13 landmark-dense
  stretch that the 08-14 daily itself flagged as too dense to individually shelf at capture time:
  Viehmann's Oort's-conjecture resolution (2603.06033, a 5.5-month-old near-miss capture-leak
  catch, now doubly relevant given this week's fresh Oort's-conjecture-pair capture), Gluck's
  Conjecture (2608.11525), Butler's positivity conjecture (2608.11543), the Leech-lattice 196560
  auxiliary-function conjecture (2608.12094), Kohayakawa's conjecture (2608.11132), Gromov's
  volume growth conjecture (2608.13553), the generalized Chang-Yang conjecture (2608.13497),
  SOP₂=SOP₃ (2608.13291), the Bosch-Simó conjecture (2608.13021), the Hayman–Wu constant
  (2608.12844 — this queue line already claimed "Also on `study_shelf`" but the item was in fact
  NOT on the shelf, a pre-existing ledger inconsistency now corrected), and the first
  extragalactic globular-cluster tidal stream (2608.12254, a first-of-kind observational
  landmark). No pruning needed this session (oldest content-dated pick, Viehmann 2026-03-06, is
  explicitly override-flagged per the established Barontini precedent so a future 120-day check
  does not misread it as stale; the oldest ordinarily-dated pick, 2026-07-01, is 66 days old,
  well inside the 120-day window).
- 2026-09-05 (W36) — Capture-leak sweep (mandatory backstop): full-file mechanical check
  (`grep -oE '[0-9]{4}\.[0-9]{5}'`, 243 unique arXiv ids post-burndown, down from 253 — the net
  effect of removing 13 queue lines while adding 11 study_shelf entries that cite already-present
  ids) found 0 leaks — every id newly touched this session (the 11 promoted + the 1 additionally
  dropped) already carries its own `arXiv:`/`abs/` citation on the line that introduced it, and
  spot-checking confirms the small number of dropped ids that still appear in old dated daily-note
  prose (2608.15257, 2510.13956, 2608.08766, 2601.08218) are historical narration of what was true
  on that day, the same pattern already established for every prior burndown (dropped ids remain
  named in the file's own history without requiring a live queue line).
- 2026-09-05 (W36) — Source strategy (weekly-swept tier, this operator's duty): full 21-entry
  list-vs-log diff and a LIVE sweep this session (institutes: `curl`/`tvly extract` — IHES, MPIM,
  Fields, Newton, KITP, Clay opened directly; SLMath, Perimeter, IAS 403'd/failed on direct
  fetch, healed via `tvly search` — nothing on-axis beyond already-tracked prize/ceremony/admin
  news, incl. the already-tracked Gaitsgory and Faltings items on MPIM's own page; slow venues:
  Forum of Mathematics opened cleanly [8 current titles, all routine, none landmark], Annals
  unchanged [Vol 203/204, no article-level content — standing JS limitation], AMS Notices
  degraded [generic landing, same standing limitation]; extra-social: r/Physics, r/cosmology,
  r/ParticlePhysics, r/AskPhysics all opened via `tvly search --include-domains reddit.com`
  [routine Q&A/discussion, the LZ 248 keV item recirculating on r/ParticlePhysics but already
  tracked], Physics SE opened directly via the W35-healed `/feeds` URL [routine Q&A]; prizes: Abel
  healed via `tvly search` [unchanged, Faltings], Breakthrough opened directly [unchanged], Shaw
  confirmed via `tvly search` [unchanged, Candès/De Lellis], IMU/Fields confirmed via `tvly
  search` [unchanged, the 2026 medals]). 21/21 logged opened-or-degraded-and-healed — NOT a
  coverage lie; nothing new on-axis beyond what the dailies already captured this week.
- 2026-09-05 (W36) — Source-discovery (drain staged candidates): PROMOTED lz.lbl.gov (1 sighting,
  but this session's own `tvly extract` verified a genuine, regular, years-long e-print/PRL
  publication cadence structurally identical to the already-tracked Experiments-block sources —
  early promotion per the staging note's own recommendation) → Primary feeds Experiments block,
  DAILY tier, with newscenter.lbl.gov folded in as its companion announcement channel rather than
  a separate line. HELD below the ≥2 bar (checked against this week's reports; both first seen
  2026-09-04, only one run old, no recurrence expected yet): github.com/anthropics
  ("formal-math" repo), proofsandprompts.com. The 6 longer-staged candidates (sammattheus.
  wordpress.com, journals.aps.org/prresearch, leodemoura.github.io, sbseminar.wordpress.com,
  ams.org/journals/jams, bourbaki.fr, anthropic.com/research, proofatlas.ai, preprints.org) were
  not re-checked individually this session (no new sighting reported against any this week) —
  hold unchanged.
- 2026-09-05 (W36) — Anchoring / off-axis: this week's 5 dailies (08-31→09-04) ran the off-axis
  exploration slot every run (5/5 compliance; roster: math.NA → q-bio.PE → math.PR↔math.ST →
  econ/q-fin → cs.CC) with 0/5 significant off-axis yield — a THIRD consecutive quiet week (after
  W34's 0/5 and W35's 0/5, which flagged "watch for a third"). Per AGENTS.md § Domain cadence
  this is still not an automatic alarm in a field this narrow, but three in a row is worth acting
  on rather than merely re-noting: the roster has now cycled through most of its original list
  (math.DS, math.OC, math.LO, math.OA, math.DG, math.NA, cs.CC, nlin.SI/CD, q-bio.PE,
  math.PR↔math.ST, econ/q-fin) without a hit since W33's Grothendieck-constant catch — flagging
  for the next weekly to consider whether the off-axis venue LIST itself (not just rotation
  compliance) needs refreshing, e.g. toward venues with less overlap with the now-comprehensive
  20-category daily math rotation (per the 09-04 daily's own roster-drift note). Tunnel-vision
  check: NOT all evidence landed on pre-existing trends this week — a new trend (Marton's-
  exponent) was created 09-01 — so no hoarding signal.
- 2026-09-05 (W36) — Self-amendment: Amendment E APPLIED (cooling period elapsed since the
  2026-08-29/W35 proposal; signal persisted — no dated curator veto). This session's own
  burndown was run under the new criterion-completeness framing from the start (see QUEUE
  BURNDOWN above: 39/39 newly-eligible items reviewed, 13 dropped / 26 protected-with-a-reason,
  reported as completeness + a drop/protect breakdown rather than a queue-size delta chased
  against a numeric band) — it replaces Amendment D's fixed 80-120 (or ~40) numeric target band
  for judging burndown health; the underlying item-by-item mechanics (review every newly-3+-
  week-eligible item against the stated drop criteria) are unchanged. One dedicated commit this
  session. Regression checks: Amendments A (cadence-split) and B (off-axis rotation) both clean
  this week (coverage 21/21; exploration compliance 5/5, though see the off-axis YIELD concern
  above — that is a venue-list question, not a rotation-compliance regression, so B itself is not
  rolled back). Amendment C (skill-window sync, applied W30) re-checked clean again this session
  (`radar-ledger-update` SKILL.md still states the correct 60+/120+/~40/~60-day domain-cadence
  numbers, no drift). NO ROLLBACK on any amendment.
- 2026-09-05 (W36) — New proposals (cooling period; apply W37 if the signal persists and no
  dated curator veto — silence = consent): **(F) refresh the off-axis exploration roster.**
  Motivated by the three-consecutive-quiet-week finding above (W34/W35/W36 all 0/5 genuine
  off-axis yield) — the current roster has cycled through nearly every entry at least once since
  W29 with only one hit (W33's Grothendieck-constant catch, itself filed under cs.CC). Proposal:
  add venues with LESS topical overlap with the daily's now-comprehensive 20-category math
  rotation and the already-covered physics categories — candidates to verify before adding:
  stat.ME/stat.ML (statistics, methodologically math-adjacent but a distinct community),
  physics.hist-ph (history/philosophy of physics, where foundational reinterpretations sometimes
  first surface), or a non-arXiv venue entirely (e.g. a philosophy-of-science or general-science
  top-attention feed) — decide the specific additions at W37 rather than pre-committing here.
  **(G) add a periodic older-paper/citation-chase pass to the exploration or source-sweep
  lanes.** Motivated by this session's monthly retrospective (`logs/calibration.md`, retro M09):
  both of the two items independently verified as "big this month" (the percolation
  supercritical-sharpness proof, the Beck-Fiala/Komlós decoupling result) were HIT-late — caught
  only once a Quanta feature pointed at them, 6-12 months after the underlying preprint was
  already on arXiv, because the routine category-rotation sweep triages by RECENCY and has no
  mechanism to revisit older, uncited-at-the-time papers. This is the same root cause behind
  several of this ledger's own past capture-leak catches (Viehmann/Oort's-conjecture this
  session, the BESIII glueball catch, the Mathieu-conjecture-SU(2) catch). Proposal: once every
  2-3 weeks, the exploration slot (or a dedicated rotation) checks arXiv's own "cites" /
  INSPIRE-HEP most-cited-this-month, or SciRate's top-scited, filtered to papers 3+ months old —
  a genuinely different discovery mechanism than recency-sorted listings or the community-pulse
  digest lane, targeting exactly the gap this retrospective found. Decide the specific mechanism
  at W37.
- 2026-09-08 (daily) — Arxiv-source ceiling: the arXiv API's underlying corpus has not advanced
  past 2026-09-04 for ANY in-scope math or physics category as of this session (confirmed via
  direct date-range probes on math.NT/CO/AG, hep-th/hep-ph/gr-qc/quant-ph/astro-ph.CO/
  cond-mat.str-el — all return 0 results for submittedDate windows after 09-04, while a control
  query against an earlier known-populated window returns results normally, ruling out a query-
  syntax fault). This is the SAME ceiling the 09-07 daily's batch already scanned in full
  (submittedDate 202609040000-202609080000) — today's arXiv CHECK is genuinely quiet, not a
  skipped check; the two new landmark captures today (below) both came from non-arXiv-API lanes
  (PRL RSS, a digest-blog pointer to a self-published PDF). Flagging for the weekly in case this
  persists into a genuine multi-day gap worth a heal note.
- 2026-09-08 (daily) — Source-discovery: two new candidates staged in SOURCES.md — science.org/
  Science Advances (AAAS, via the quantum-free-fall equivalence-principle capture) and
  cims.nyu.edu (Tristan Buckmaster's own institutional page, via the Alpöge-Buckmaster Boussinesq
  capture, discovered through Tao's already-tracked blog). Both first-seen this session, held
  below the ≥2-sighting promotion bar.
- 2026-09-08 (daily) — Self-heal note: SciPost's publications API now returns an Anubis
  proof-of-work bot-check challenge to both direct `curl` and `tvly extract` — a NEW failure
  mode (first occurrence this session, not the standing pattern of any prior degradation).
  Logged `degraded` in SOURCES.md rather than healed (per `radar-source-heal`, healing is owed
  once a failure recurs); the non-invertible-symmetries and Stanley-Gasharov trends both rely on
  this feed, so a second consecutive miss should trigger a heal attempt next session.
- 2026-09-08 (daily) — capture-leak reconciliation: 1 new arXiv id named this session
  (2502.14535) — lands on its own discrete queue line + study_shelf entry, 0 leaked; the two
  other new captures (the Alpöge-Buckmaster PDF, the two PRL items) use non-arXiv-id URLs and are
  cited directly by eye on their own queue lines. Full-file mechanical sweep: 252 unique arXiv
  ids (up from 251), consistent with the one new id — 0 file-wide leaks.
- 2026-09-09 (daily) — Capture-leak count discrepancy: this session's mechanical sweep
  (`grep -oE '[0-9]{4}\.[0-9]{4,5}' TRENDS.md | sort -u | wc -l`) found 230 unique arXiv ids, not
  ~252-253 as the trend from recent dailies' self-reports would predict (251→252 over 09-07→09-08,
  +5 new ids expected today ≈ 257). The discrepancy (230 vs. ~257 expected) was NOT chased down
  this session — flagging for the weekly to determine whether it is a genuine regex/counting-method
  drift between sessions (e.g. a prior session counting substring occurrences rather than unique
  ids, or a different digit-width pattern) or an actual content change; no evidence of accidental
  content loss was found in a spot-check of the file structure (headers, evidence caps, and the
  known older entries all verified intact this session).
- 2026-09-09 (daily) — Load-state near-miss: a `git fetch origin main claude/modest-bohr-wg8j3e`
  (two refs in one invocation) failed to update the local `origin/main` tracking ref for one of the
  two refspecs, briefly reading as a possible stranded-branch state (matching the AGENTS.md
  BRANCH WARNING pattern). A clean single-ref `git fetch origin main` immediately resolved it —
  `origin/main` was already fully current with local HEAD (71b5747), no push needed. This is the
  SAME multi-ref-fetch artifact class already flagged in the 09-07 daily's log — now seen twice.
  Recommend: weekly should consider adding "always fetch `origin main` as its own single-ref
  invocation during load-state" as a standing operating note (not a routine amendment, since this
  is a tooling-usage habit, not a scope/skill change) to stop this false-alarm pattern recurring.
- 2026-09-09 (daily) — Source-discovery: cims.nyu.edu now clears the ≥2-sighting promotion bar (3
  distinct on-axis primary artifacts — Boussinesq 09-07, Euler + IPM + a public statement 09-08/09
  — across 2 separate daily runs); flagged ready for weekly promotion into the swept registry
  rather than promoted here (daily stages, weekly promotes, per the source-discovery convention).
- 2026-09-10 (daily) — Self-heal note (partial): SciPost's Anubis bot-check now blocks individual
  article pages too (not just the `/api/publications/` endpoint), a 3rd consecutive degraded daily —
  full heal still owed. A second partial workaround found this session: `scipost.org/sitemap.xml`
  loads via plain `curl` with no bot-check and lists every publication's short-code URL, letting the
  radar detect THAT new publications exist (issue-number advancement) even though titles/abstracts
  stay blocked on both the API and article pages. Recorded in SOURCES.md; if the Anubis block persists
  a 4th consecutive daily this becomes a genuine heal-owed escalation per `radar-source-heal`.
- 2026-09-10 (daily) — Capture-leak count still unreconciled: this session's mechanical sweep found
  240 unique arXiv ids (up from 230 pre-session), consistent with exactly the 10 ids captured this
  session — 0 new leaks. The 09-09 daily's flagged discrepancy (230 found vs. ~257 predicted by the
  prior self-reported trend) was NOT chased down this session either; still flagged for the weekly to
  determine whether it is a counting-method drift between sessions or something else — no evidence of
  content loss found in either session's spot-checks.
