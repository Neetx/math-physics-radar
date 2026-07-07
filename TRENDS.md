# Trend ledger — Math-Physics Radar

Last updated: 2026-07-07

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(21+ days quiet) ; `declining` (the field moved on). Confidence: `low | medium | high`.
Trend bar: ≥3 independent sources (different orgs/author groups) + ≥1 concrete artifact.

## Active trends

### Ramsey-number lower-bound breakthroughs (extremal combinatorics)
- stage: emerging | confidence: medium | first_seen: 2026-07-03 | last_evidence: 2026-05-27
- what: A 2025–2026 wave of independent breakthroughs on Ramsey-number LOWER bounds, breaking
  decades-old barriers. Ma–Shen–Xie broke the Erdős probabilistic-method barrier for off-diagonal
  graph Ramsey numbers r(ℓ, Cℓ); Bradač then pushed the classical off-diagonal r(s,k) lower bound to
  match the 90-year-old Erdős–Szekeres upper bound up to polylog (first exponent improvement since
  Spencer 1977); parallel work sharpens these and extends to hypergraph Ramsey numbers. Preprints —
  strong but not yet fully refereed; track the vetting.
- evidence:
  - 2025-07-17 — https://arxiv.org/abs/2507.12926 — Ma, Shen, Xie, "An exponential improvement for Ramsey lower bounds": first exponential improvement over Erdős' 1947 bound for r(ℓ, Cℓ) (abstract verified this session).
  - 2026-04-27 — https://arxiv.org/abs/2604.23986 — Du, Hu, Liu, Wang, "A double-exponential lower bound for r₄(5,n)": hypergraph Ramsey, r₄(5,n) ≥ 2^{2^{cn^{1/7}}} (abstract via arXiv API this session).
  - 2026-05-25 — https://arxiv.org/abs/2605.25843 — Lin, Niu, "Sharper Ramsey lower bounds from refined Gaussian estimates": sharpens the Ma–Shen–Xie off-diagonal bound (abstract via arXiv/tvly this session).
  - 2026-05-27 — https://arxiv.org/abs/2605.28793 — Bradač, "Off-diagonal Ramsey numbers": r(s,k) ≥ Ω(k^{s-1}/(log k)^{2s-4}), matching Erdős–Szekeres up to polylog, improving Spencer 1977 (abstract via arXiv API this session).
- notes: ≥4 independent author groups on one sub-theme (Ma–Shen–Xie; Bradač; Du–Hu–Liu–Wang; Lin–Niu) + concrete artifacts → clears the trend bar. Community framing: Quanta ("Erdős method upgrade", 2026-06-26) and Gil Kalai / Sam Mattheus blogs ("a sensational Ramsey breakthrough by Bradač"). Ma–Shen–Xie also on `study_shelf`. Watch for referee outcomes and whether the diagonal r(k,k) barrier is next.
  - 2026-W27 recalibration: HELD at emerging/medium. All 4 evidence items predate the trend's
    creation (latest 2026-05-27, ~5–6 weeks old) — a backlog cluster caught at creation, not fresh
    weekly velocity, so NOT promoted; confidence held at medium under the unrefereed-preprint caution
    (no referee outcomes yet). NOT marked dormant despite the 38-day evidence gap because the trend was
    only created 2026-07-03; if no post-2026-05-27 primary or a referee/vetting outcome surfaces by W28,
    reassess for dormancy (this may be a completed burst rather than an active, accelerating trend).

## observation_queue

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).

- 2026-07-07 — arXiv:2607.05374 — "The Minkowski grid has robustly many repeated distances" (Lee, Pohoata, Zhu) — https://arxiv.org/abs/2607.05374 — Erdős-type combinatorial geometry / repeated-distances (axis 1, math.CO/NT); abstract opened via arXiv API this session. Single below-bar item.
- 2026-07-07 — SciPost — "Irrational CFTs from coupled anyon chains with non-invertible symmetries?" (published 2026-07-06) — https://scipost.org/ — axis 2/4 (CFT, non-invertible / generalized symmetries); title/date via SciPost API this session, article not opened → intake. Generalized/non-invertible-symmetry sub-theme now 2 independent items with 2604.02856 (Type-IV 't Hooft anomalies / higher-categorical symmetries) — forming, below the ≥3 bar.
- 2026-07-07 — PRL 2026-07-06 — "Scattering Amplitudes and Conservative Binary Dynamics at O(G⁵) without Self-Force Truncation" — https://feeds.aps.org/rss/recent/prl.xml — axis 2 (scattering-amplitudes / post-Minkowskian expansion of the gravitational two-body problem, 5th PM order); title/date seen via APS PRL RSS this session, article not opened → unverified intake.
- 2026-07-07 — PRL 2026-07-06 — GWTC-4 binary-black-hole population inference (two papers: "Evidence for Three Subpopulations of Merging Binary Black Holes at Different Primary Masses" + "Signatures of a Subpopulation of Hierarchical Mergers in the GWTC-4 Gravitational-Wave Dataset") — https://feeds.aps.org/rss/recent/prl.xml — axis 3 (GW population; pairs with GWTC-5.0 on study_shelf); titles/dates seen via APS PRL RSS this session, articles not opened → unverified intake (same-collaboration data, not independent groups).
- 2026-07-05 — arXiv:2604.02856 — "Type-IV 't Hooft Anomalies on the Lattice: Emergent Higher-Categorical Symmetries and Applications to LSM Systems" — https://arxiv.org/abs/2604.02856 — capture-leak catch: named only in strategy_notes prose (07-04, as a SciRate-output example) but never captured; title/date (2026-04-03) verified via arXiv API this session. Axis 2/4 (QFT anomalies / higher-categorical symmetry, lattice), single below-bar item.
- 2026-07-05 — Nature Physics News&Views "Tangled up in spin" — https://www.nature.com/articles/s41567-026-03364-7 — neutron-scattering hints of quantum entanglement in a strange-metal state (axis 3/4, entanglement as a physical observable in a correlated metal); commentary blurb opened via Nature Physics RSS this session — underlying research paper NOT identified/opened → unverified intake.
- 2026-07-04 — SciPostPhys.21.1.004 — "Towards holographic color superconductivity in QCD" — https://scipost.org/SciPostPhys.21.1.004 — an AdS/holographic model of color-superconducting QCD matter (axis 2, hep-th/holography ↔ dense-QCD interface); SciPost API metadata (published 2026-07-02) opened this session. Single below-bar item.
- 2026-07-03 — arXiv:2607.02013 — "Resolution of the Detection Threshold Conjecture for Random Geometric Graphs in the d>n Regime" — https://arxiv.org/abs/2607.02013 — a resolved conjecture (axis 1, probability/combinatorics); RSS abstract opened this session.
- 2026-07-03 — arXiv:2607.01317 — "No Evidence for Superradiant Axions in LIGO-Virgo-KAGRA GWTC-5 Binary Black Hole Spins" — https://arxiv.org/abs/2607.01317 — null result constraining axion clouds from GWTC-5 spins (axis 3, DM/GW; pairs with GWTC-5.0 on study_shelf); RSS abstract opened this session.
- 2026-07-03 — arXiv:2607.01815 — "Evidence for Deconfined Magnetic Order in the Kitaev-J₃ Model" — https://arxiv.org/abs/2607.01815 — deconfined order (axis 3/4); RSS abstract opened. Deconfined-criticality/order sub-theme now 2 independent groups (with 2607.00762) — forming, not yet at the ≥3 bar.
- 2026-07-03 — arXiv:2607.01544 — "Formalized q-series: The Rogers-Ramanujan Identities and Beyond" — https://arxiv.org/abs/2607.01544 — machine-formalized classical q-series identities (axis 5, computer-assisted math); RSS abstract opened this session.
- 2026-07-03 — 2026 Clay Research Awards announced — https://www.claymath.org/ — recognition signal (intake, ecosystem/award); named via tvly search, Clay page NOT opened this session — unverified, open next run.
- 2026-07-02 — 2026 Abel Prize presented to Gerd Faltings (ceremony) — https://www.mpim-bonn.mpg.de/ — MPIM institute page opened this session; major recognition in arithmetic/algebraic geometry (ecosystem/award, on-scope).
- 2026-07-02 — arXiv:2607.00762 — Deconfined criticality between an antiferromagnetic insulator and a nodal d-wave superconductor (quantum Monte Carlo) — https://arxiv.org/abs/2607.00762 — unverified (cond-mat.str-el listing; abstract not opened).
- 2026-07-02 — arXiv:2607.00086 — "Dissipation splits the Mott transition in one dimension" (open strongly-correlated systems) — https://arxiv.org/abs/2607.00086 — unverified (listing).
- 2026-07-02 — arXiv:2607.00134 — Phase distinction of Gibbs states without symmetry breaking: topological invariants of the 3D toric code — https://arxiv.org/abs/2607.00134 — unverified (listing; quantum-foundations/topological-order axis).
- 2026-07-02 — arXiv:2607.00318 — "A Complete Intersection Theorem for Large Permutation Groups" (extremal combinatorics) — https://arxiv.org/abs/2607.00318 — unverified (listing).
- 2026-07-02 — Formal-math toolchain releases: mathlib4 v4.32.0-rc1 (stable still v4.31.0), lean4 v4.32.0 (Pass 2: now stable, was v4.31.0), Rocq v9.2.0 — https://github.com/leanprover-community/mathlib4/releases — release tags opened via tvly (axis 5: computer-assisted/formalized math).
- 2026-07-02 — Rocq (ex-Coq) v9.2.0 released — https://github.com/rocq-prover/rocq/releases — formal-proof toolchain (axis 5); tag opened via tvly.
- 2026-07-01 — arXiv spins out of Cornell into an independent nonprofit (Simons Foundation + Schmidt Sciences funding) — community-pulse note (ecosystem/infrastructure, not a research result) — unverified.

## source_rotation

Append-only coverage log MOVED to `logs/source_rotation.md`. Each run APPENDS one dated line
THERE and reads only the recent tail (~7 days) — do not write scans into TRENDS.md.

## strategy_notes

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

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-07-07 — [The Burau representation of the braid group is faithful for n = 4 (Bharathram, Birman, Brendle), arXiv:2607.05283](https://arxiv.org/abs/2607.05283) — resolves a decades-old open problem in low-dimensional topology: the Burau representation of B₄ is faithful (it is classically faithful for n≤3 and known NON-faithful for n≥5 — Moody, Long–Paton, Bigelow — leaving n=4 as the last open case). Corollary: the Jones representation of B₄ is also faithful. Abstract + authors verified via arXiv API this session (v1 6 Jul 2026). Unrefereed preprint — but by leading braid-group topologists (Birman, Brendle) building on established methods; track the referee/vetting outcome.
- 2026-07-02 — [An exponential improvement for Ramsey lower bounds (Ma, Shen, Xie), arXiv:2507.12926](https://arxiv.org/abs/2507.12926) — first exponential improvement over Erdős' classical 1947 probabilistic lower bound for the Ramsey number r(ℓ, Cℓ); abstract + authors/dates verified this session (v1 17 Jul 2025, v2 26 Apr 2026). This is the "Erdős method upgrade" Quanta covered 2026-06-26 (Pass 1 mis-attributed it to Sudakov, who was only quoted — corrected).
- 2026-07-02 — [GWTC-5.0 — updated LIGO–Virgo–KAGRA gravitational-wave catalog](https://www.ligo.org/news.php) — new release of the GW transient catalog setting precision records; the current census of compact-binary mergers (LIGO collaboration news page opened this session).
- 2026-05-01 — [Erdős Problem #1196: primitive sets and von Mangoldt chains (Alexeev, Barreto, Li, Lichtman, Price, et al.)](https://arxiv.org/abs/2605.00301) — resolves an Erdős problem on primitive sets via a von-Mangoldt-chain method; metadata verified via the arXiv API this session.

## calibration

Append-only self-evaluation log MOVED to `logs/calibration.md` (see `radar-self-eval`).
Weekly runs APPEND there, never here.
