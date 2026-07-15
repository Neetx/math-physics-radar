# Trend ledger — Math-Physics Radar

Last updated: 2026-07-15

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(21+ days quiet) ; `declining` (the field moved on). Confidence: `low | medium | high`.
Trend bar: ≥3 independent sources (different orgs/author groups) + ≥1 concrete artifact.

## Active trends

### Ramsey-number lower-bound breakthroughs (extremal combinatorics)
- stage: dormant | confidence: medium | first_seen: 2026-07-03 | last_evidence: 2026-05-27
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
  - 2026-W28 recalibration: DEMOTED emerging → dormant. last_evidence 2026-05-27 is now 45 days old
    (21+ days quiet = dormant; W27 had set W28 as the reassessment point). No post-2026-05-27 lower-bound
    breakthrough and no referee/vetting outcome surfaced this week; a fresh arXiv math.CO Ramsey scan this
    session returned only peripheral items (small/anti-Ramsey, Ramsey-type path–cycle) — the breakthrough
    wave (Jul 2025–May 2026) reads as a COMPLETED BURST caught as a backlog at creation. NOT archived
    despite hitting the 45-day archive line: the trend has been TRACKED only 8 days (created 2026-07-03),
    too short a window to archive a bar-clearing, field-shaping cluster, and referee outcomes on these major
    preprints could still reactivate it. DECISION POINT: archive at W29 unless a fresh Ramsey lower-bound
    primary or a referee/vetting outcome appears.
  - 2026-07-14 (daily): Lin–Niu (a trend author group) posted a fresh primary, arXiv:2607.10111
    "Hypergraph Erdős–Rogers functions with consecutive clique sizes" — Ramsey-ADJACENT (an Erdős–Rogers
    extremal function) but NOT a Ramsey-number lower bound → queued as its own item, does NOT satisfy the
    W28 reactivation criterion (fresh Ramsey lower-bound primary OR referee outcome). Trend HELD dormant;
    W29 archive decision unchanged.
  - 2026-07-15 (daily): fresh math.CO 2026-07-14 batch scanned for Ramsey lower bounds — none (batch was
    Balanced Four-Color Theorem, 3-stable Kneser chromatic number, orthogonal quantum Latin squares, etc.;
    no Ramsey-number lower bound, no referee/vetting outcome on the 2025–26 preprints). W28 reactivation
    criterion still unmet → trend HELD dormant; W29 (this week's weekly) archive decision unchanged.

## observation_queue

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).

- 2026-07-15 — arXiv:2607.13009 — "Model-Independent Indication for a Localized Anomaly in the Late-Time Expansion History" — https://arxiv.org/abs/2607.13009 — cosmology / dark energy (axis 3, gr-qc/astro-ph.CO): a model-independent spline reconstruction of DESI DR2 BAO + DES "Dovekie" Type-Ia-SN distances finds a localized ~3.5σ deviation from Planck-2018 ΛCDM over z≈0.3–0.6 (peak z≈0.47), robust to reconstruction/dataset/sound-horizon variations. EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): a 3.5σ anomaly is NOT a discovery — below 5σ, look-elsewhere effect, "if confirmed"; provisional, track the vetting. Ties into the DESI dynamical-dark-energy saga. DESI is a tracked experiment. Abstract opened via arXiv API this session (v1 2026-07-14).
- 2026-07-15 — arXiv:2607.13025 — "The Balanced Four-Color Theorem" — https://arxiv.org/abs/2607.13025 — combinatorics / graph coloring (axis 1, math.CO): every planar graph on n≥3 vertices admits a 4-coloring in which every color class has fewer than n/2 vertices — and this bound is BEST POSSIBLE, computable in O(n log n); extended to ≥5 colors and to general surfaces. A sharp "balanced" strengthening of the Four Color Theorem. Single below-bar item; abstract opened via arXiv API this session (v1 2026-07-14).
- 2026-07-15 — arXiv:2607.12749 — "A Proof of Sundaram's Bounded-Interval Higher Lie Positivity Conjecture" — https://arxiv.org/abs/2607.12749 — representation theory / algebraic combinatorics (axis 1, math.RT): resolves a positivity conjecture of Sheila Sundaram on higher Lie characters over bounded intervals. Single below-bar resolved-conjecture item; title/abstract opened via arXiv API this session (v1 2026-07-14).
- 2026-07-14 — arXiv:2607.10111 — "Hypergraph Erdős–Rogers functions with consecutive clique sizes" (Lin, Niu) — https://arxiv.org/abs/2607.10111 — extremal combinatorics (axis 1, math.CO): bounds for the hypergraph Erdős–Rogers function, a Ramsey-type extremal function; by Lin–Niu, one of the author groups in the (dormant) Ramsey-lower-bound trend. Ramsey-ADJACENT but NOT a Ramsey-number lower bound → its own below-bar queue item, does not lift the trend's dormancy. Title/date (v1 2026-07-13) via arXiv RSS this session.
- 2026-07-14 — arXiv:2607.10106 — "A resolution of Kellner's conjectures on Wilson quotients" (Matsuno) — https://arxiv.org/abs/2607.10106 — number theory (axis 1, math.NT): resolves Kellner's conjectures on Wilson quotients. Single below-bar resolved-conjecture item; abstract opened via arXiv API this session (v1 2026-07-11).
- 2026-07-14 — arXiv:2607.08911 — "A diagrammatic field theory of quantum error correction" (SciRate-attention catch) — https://arxiv.org/abs/2607.08911 — a field-theoretic framework for QEC built on fusion-space codes in unitary fusion categories, with algebro-geometric directions (tube/Hopf algebras, Yangian structures, Higgs bundles, spectral curves, abelian varieties); cross-listed hep-th/math-ph/math.AG/math.RT (axis 2, the math↔physics interface). Surfaced via SciRate top-scited (tracked discovery venue) this session; abstract opened via arXiv API (v1 2026-07-09). AXIS-BOUNDARY caveat: the QEC subject overlaps the sibling quantum radar's quantum-computing beat — captured here for its mathematical-physics/category-theory content, not the QEC machinery. Single below-bar intake.
- 2026-07-14 — PRL 2026-07-13 (new since the 07-10 batch): "Volume-Law Protection of Metrological Advantage" (axis 4, entanglement-enhanced quantum metrology) + "Edge of Safety: Charge-Charge Correlation in the Back-to-Back Limit" (axis 3, jet/energy-correlator QCD) — https://feeds.aps.org/rss/recent/prl.xml — titles/dates via APS PRL RSS this session, articles not opened → unverified intake.
- 2026-07-13 — arXiv:2607.08802 — "The matroid intersection conjecture" (van der Zypen) — https://arxiv.org/abs/2607.08802 — CLAIMED PROOF of Nash-Williams' infinite matroid intersection conjecture, a long-standing open problem in infinite-matroid theory; abstract opened via arXiv API this session (v1 2026-07-09). Unrefereed single-author preprint claiming resolution of a named conjecture → PROVISIONAL under the hype-skepticism rule: NOT a resolved conjecture until independent vetting; track the outcome. Axis 1 (combinatorics).
- 2026-07-13 — arXiv:2607.08905 — "On The Morel Structure Conjecture" (Bertizzolo) — https://arxiv.org/abs/2607.08905 — completes the proof of Morel's structure conjecture: Witt K-theory is effective over any perfect field of characteristic 2, finishing the program initiated by Bachmann (axis 1, motivic/A¹-homotopy theory); abstract opened via arXiv API this session (v1 2026-07-09). Single below-bar resolved-conjecture item.
- 2026-07-13 — arXiv:2607.09049 — "A Single-Exponential Erdős–Hajnal Bound for Graphs of Bounded VC-Dimension" (Sun, Wang, Zeng) — https://arxiv.org/abs/2607.09049 — improves the Nguyen–Scott–Seymour Erdős–Hajnal bound to single-exponential for bounded-VC-dimension graphs (axis 1, extremal combinatorics; adjacent to but distinct from the Ramsey trend); abstract opened via arXiv API this session (v1 2026-07-10). Single below-bar item.
- 2026-07-13 — 2026 Shaw Prize in Mathematical Sciences — Emmanuel Candès & Camillo De Lellis (equal shares) — https://www.shawprize.org/ — recognition/ecosystem (axis 1); Shaw page + IAS news ("Camillo De Lellis Wins 2026 Shaw Prize") BOTH opened this session (corroborated). Closes the 2026-07-12 prize-capture gap (Shaw 2026 had been missed). Follow to the honored work next (Candès: compressed sensing / high-dimensional statistics; De Lellis: geometric measure theory, regularity & the Plateau problem).
- 2026-07-13 — PRL 2026-07-10 (pair) — "Extended Haloscope Search and Exclusion of a Candidate Signal near 1.036 GHz" + "Cavendish Tests of Millicharged Particles" — https://feeds.aps.org/rss/recent/prl.xml — axis 3 (dark-matter direct searches: an axion-haloscope candidate-signal exclusion + a tabletop millicharged-particle constraint); titles/dates via APS PRL RSS this session, articles not opened → unverified intake.
- 2026-07-13 — PRL 2026-07-08 — "Comprehensive Analysis of the B⁰→K*⁰μ⁺μ⁻ Decay" — https://feeds.aps.org/rss/recent/prl.xml — axis 3 (flavor physics / b→sℓℓ, the long-running LHCb angular-observable anomaly); title/date via APS PRL RSS this session, article not opened → unverified intake.
- 2026-07-13 — SciPost Phys. 21, 011 (2026) — "A free fermions in disguise model with claws" (Pozsgay), published 2026-07-08 — https://scipost.org/ — axis 2/4 (integrable systems / free-fermion-in-disguise construction); metadata via tvly search (SciPost JSON API returned empty this session — degraded) → intake. Single below-bar item.
- 2026-07-10 — PRL 2026-07-09 (pair) — "Gravitational-Wave Tomography of the Moon: Constraining Lunar Structure with Calibrated Gravitational Waves" + "Thick Lunar Crust Amplifies Deci-Hertz Gravitational-Wave Signals" — https://feeds.aps.org/rss/recent/prl.xml — axis 3 (GW ↔ lunar seismology; a novel proposal to use the Moon as a deci-Hertz GW antenna / probe lunar interior structure with calibrated GWs); titles/dates via APS PRL RSS this session, articles not opened → unverified intake. Novel cross-domain concept, single below-bar theme.
- 2026-07-10 — Nature Physics 2026-07-09 — "Emergence of Fermi's golden rule in a quantum many-body system" — https://www.nature.com/nphys.rss — axis 3/4 (AMO / quantum many-body foundations: experimental emergence of the golden-rule decay law from a genuinely interacting many-body system); title/date via Nature Physics RSS this session, article not opened → unverified intake. Single below-bar item.
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
- 2026-07-08 — arXiv:2607.06545 — "A Higher-Order Clique Density Theorem" — https://arxiv.org/abs/2607.06545 — extremal graph theory (axis 1, math.CO): sharp lower bound for K_r-density at prescribed K_s-density (3≤s<r), a genuinely-nonlinear generalization of Reiher's clique density theorem; abstract opened via arXiv API this session. Single below-bar item, extremal-combinatorics (adjacent to but distinct from the Ramsey trend).
- 2026-07-09 — arXiv:2607.07641 — "The abc Conjecture Revisited" (Letendre) — https://arxiv.org/abs/2607.07641 — proposes a NEW abc-type conjecture and derives an application to sums of ω(n) (distinct-prime-factor counts) over short intervals (axis 1, math.NT); abstract opened via arXiv API this session. NOT a proof of abc — a proposed conjecture + consequence. Single below-bar item.
- 2026-07-09 — PRL 2026-07-08 — "Observation of the Doubly Charmed Baryon Ξcc+ with the LHCb Run 3 Detector" — https://feeds.aps.org/rss/recent/prl.xml — axis 3 (HEP, LHCb Run 3 re-observation of the doubly-charmed baryon, first seen by LHCb 2017); title/date via APS PRL RSS this session, article not opened → unverified intake. Single below-bar.
- 2026-07-08 — arXiv:2607.06398 — "Random Multiplicative Functions and Making Squares from Polynomial Values" — https://arxiv.org/abs/2607.06398 — analytic number theory / probability (axis 1, math.NT/PR): CLTs for sums of random multiplicative functions over polynomial values via a paucity phenomenon for P(n₁)…P(n₄)=□; abstract opened via arXiv API this session. Single below-bar item.
- 2026-07-08 — Nature Physics 2026-07-07 — "Visualization of the Zhang–Rice singlet, electronic molecules and Cooper pair formation in a cuprate superconductor" — https://www.nature.com/nphys.rss — axis 3 (high-Tc superconductivity / correlated cond-mat); title/date via Nature Physics RSS this session, article not opened → unverified intake.
- 2026-07-08 — PRL 2026-07-07 — "Aligned Hierarchical Black Hole Mergers in Active-Galactic-Nuclei Disks Revealed by GWTC-4" — https://feeds.aps.org/rss/recent/prl.xml — axis 3 (GW population; hierarchical-merger channel in AGN disks); title/date via APS PRL RSS this session, article not opened → unverified intake. Adds to the GWTC-4 population sub-theme (with the two 07-07 GWTC-4 items) — but all GWTC-4-derived, same-collaboration data, NOT independent groups.
- 2026-07-08 — PRL 2026-07-07 — "Worldsheet for Generalized Veneziano Amplitudes" — https://feeds.aps.org/rss/recent/prl.xml — axis 2 (string/hep-th scattering amplitudes, worldsheet construction for generalized Veneziano amplitudes); title/date via APS PRL RSS this session, article not opened → unverified intake.
- 2026-07-08 — 2026 Clay Research Awards (page dated 2026-04-14) — https://www.claymath.org/2026-clay-research-awards/ — RESOLVED (was unverified since 07-03): recipients now confirmed via Clay page opened (tvly extract) this session — (i) Orponen, Shmerkin, Wang, Zahl for the Furstenberg set conjecture (plane) + Kakeya conjecture in 3D; (ii) Burklund, Hahn, Levy, Schlank for counterexamples to Ravenel's Telescope Conjecture; (iii) Deng, Hani. Recognition/ecosystem signal (axis 1 pure math). The underlying landmark artifacts (3D-Kakeya proof, Telescope-conjecture counterexample) are NOT opened this session → track and follow to those primaries next run.
- 2026-07-02 — 2026 Abel Prize presented to Gerd Faltings (ceremony) — https://www.mpim-bonn.mpg.de/ — MPIM institute page opened this session; major recognition in arithmetic/algebraic geometry (ecosystem/award, on-scope).
- 2026-07-02 — arXiv:2607.00762 — Deconfined criticality between an antiferromagnetic insulator and a nodal d-wave superconductor (quantum Monte Carlo) — https://arxiv.org/abs/2607.00762 — unverified (cond-mat.str-el listing; abstract not opened).
- 2026-07-14 — Formal-math toolchain releases: **lean4 v4.32.0 now the latest tag (final)** — moved past v4.32.0-rc1; mathlib4 still v4.32.0-rc1 (stable v4.31.0), Rocq v9.2.0 unchanged — https://github.com/leanprover/lean4/releases — release pages opened via tvly this session (axis 5: computer-assisted/formalized math). Exact release date not pinned (tvly search still showed rc1 "3 weeks ago"); mathlib stable expected to follow lean4 v4.32.0. Prior line (2026-07-02): mathlib4/lean4/Rocq all at v4.32.0-rc1 / v9.2.0.

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

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-07-13 — [K-theoretic counterexamples to Ravenel's telescope conjecture (Burklund, Hahn, Levy, Schlank), arXiv:2310.17459](https://arxiv.org/abs/2310.17459) — the landmark DISPROOF of Ravenel's telescope conjecture: at each prime p and height n+1 ≥ 2, the telescopic (T(n+1)) and chromatic (K(n+1)) localizations of spectra differ — shown via the T(n+1)-localized algebraic K-theory of BP⟨n⟩^{hℤ} being non-K(n+1)-local (chromatic homotopy theory / algebraic K-theory). One of the two landmarks behind the 2026 Clay Research Award (Burklund–Hahn–Levy–Schlank); followed to primary from the Clay award resolved on the queue 2026-07-08, per the 07-10 report's Next. Abstract + authors verified via arXiv API this session (v1 26 Oct 2023).
- 2026-07-10 — [Volume estimates for unions of convex sets, and the Kakeya set conjecture in three dimensions (Wang, Zahl), arXiv:2502.17655](https://arxiv.org/abs/2502.17655) — the landmark RESOLUTION of the Kakeya set conjecture in ℝ³: every Kakeya set in ℝ³ has Minkowski and Hausdorff dimension 3, via a new volume estimate for unions of δ-tubes not concentrated in a common convex set (axis 1, geometric measure theory / harmonic analysis). Followed to primary from the 2026 Clay Research Award (Orponen–Shmerkin–Wang–Zahl, Furstenberg + 3D Kakeya) resolved on the queue 2026-07-08; abstract + authors verified via arXiv API this session (v1 24 Feb 2025). A 2025 artifact surfaced here on its Clay-2026 recognition — a genuinely field-shaping resolved conjecture worth knowing.
- 2026-07-09 — [The Algebraic Montgomery–Yang Problem (Jo, Park, Park), arXiv:2607.06686](https://arxiv.org/abs/2607.06686) — completely RESOLVES the algebraic Montgomery–Yang problem, a conjecture of Kollár: every rational homology projective plane with quotient singularities and a simply-connected smooth locus has at most three singular points. Proof combines a new lattice-theoretic constraint from Donaldson's diagonalization theorem + the distinguished spin^c structure on the smooth locus with the orbifold Bogomolov–Miyaoka–Yau inequality to rule out all remaining cases (axis 1, algebraic geometry ↔ 4-manifold topology). Abstract + authors verified via arXiv API this session (v1 7 Jul 2026). Unrefereed preprint — a claimed resolution of a named conjecture; track the referee/vetting outcome.
- 2026-07-07 — [The Burau representation of the braid group is faithful for n = 4 (Bharathram, Birman, Brendle), arXiv:2607.05283](https://arxiv.org/abs/2607.05283) — resolves a decades-old open problem in low-dimensional topology: the Burau representation of B₄ is faithful (it is classically faithful for n≤3 and known NON-faithful for n≥5 — Moody, Long–Paton, Bigelow — leaving n=4 as the last open case). Corollary: the Jones representation of B₄ is also faithful. Abstract + authors verified via arXiv API this session (v1 6 Jul 2026). Unrefereed preprint — but by leading braid-group topologists (Birman, Brendle) building on established methods; track the referee/vetting outcome.
- 2026-07-02 — [An exponential improvement for Ramsey lower bounds (Ma, Shen, Xie), arXiv:2507.12926](https://arxiv.org/abs/2507.12926) — first exponential improvement over Erdős' classical 1947 probabilistic lower bound for the Ramsey number r(ℓ, Cℓ); abstract + authors/dates verified this session (v1 17 Jul 2025, v2 26 Apr 2026). This is the "Erdős method upgrade" Quanta covered 2026-06-26 (Pass 1 mis-attributed it to Sudakov, who was only quoted — corrected).
- 2026-07-02 — [GWTC-5.0 — updated LIGO–Virgo–KAGRA gravitational-wave catalog](https://www.ligo.org/news.php) — new release of the GW transient catalog setting precision records; the current census of compact-binary mergers (LIGO collaboration news page opened this session).

## calibration

Append-only self-evaluation log MOVED to `logs/calibration.md` (see `radar-self-eval`).
Weekly runs APPEND there, never here.
