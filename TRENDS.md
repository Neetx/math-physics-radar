# Trend ledger — Math-Physics Radar

Last updated: 2026-07-30

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(60+ days quiet — domain cadence; AGENTS.md § Domain cadence) ; `declining` (the field moved on). Confidence: `low | medium | high`.
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
  - 2026-07-16 (daily): fresh math.CO 2026-07-15 batch scanned for Ramsey lower bounds — none (batch held
    Sabidussi's compatibility conjecture, path-reversed-tournament inversion number, spectral extremal, etc.;
    no Ramsey-number lower bound, no referee/vetting outcome). W28 reactivation criterion still unmet → trend
    HELD dormant; W29 (due this week) archive decision unchanged.
  - 2026-07-17 (daily): fresh math.CO 2026-07-16 batch scanned for Ramsey lower bounds — none (batch held
    odd-cycle Alon–Friedland defects, three-bit flows / cycle covers, online Beck–Fiala discrepancy,
    Hamiltonian Cayley graphs of order pqrs, χ-bounds for {P₆,dart,K₄}-free graphs, etc.; no Ramsey-number
    lower bound, no referee/vetting outcome on the 2025–26 preprints). W28 reactivation criterion still unmet →
    trend HELD dormant; W29 (due this week) archive decision unchanged.
  - 2026-W29 recalibration: REACTIVATED dormant → emerging (RECONCILE-FIRST, per weekly.md §2 / AGENTS.md
    § Domain cadence). The W28 dormant-at-45-days demotion AND the standing "archive at W29" decision were both
    made under the SUPERSEDED AI-default 21/45-day windows. The domain-cadence calibration applied 2026-07-13
    (AFTER W28) sets dormancy at 60 days / archive at 120. last_evidence 2026-05-27 is 52 days old today
    (2026-07-18) — INSIDE the current 60-day active window — so under the CURRENT threshold the trend is NOT
    dormant. Per the reconcile rule ("a threshold change must retroactively fix trends mis-staged under the old
    threshold"), the stale dormancy + archive decision are VOIDED and the trend is restored to its prior stage
    (emerging). Confidence HELD at medium (still no referee/vetting outcome on the 2025–26 preprints; unrefereed-
    preprint caution). NOT promoted (no fresh post-2026-05-27 lower-bound primary this week — reconcile is a
    correction, not new velocity). NEW dormancy re-check: if no fresh Ramsey lower-bound primary or referee
    outcome appears by 2026-07-26 (the 60-day mark), it legitimately goes dormant under the current window
    (~W31); the completed-burst read from W28 remains the risk to watch.
  - 2026-07-20 (daily): first daily since 07-17 (weekend + W29 weekly). Fresh math.CO 2026-07-17→20 batch
    scanned for Ramsey lower bounds — none (batch held sign-matrix asymptotics, Baker–Huh–Kummer–Lorscheid
    Lorentzian-polynomials/matroids-over-hyperfields II, the OpenAI Cycle-Double-Cover exposition, etc.; no
    Ramsey-number lower bound, no referee/vetting outcome on the 2025–26 preprints). last_evidence 2026-05-27
    is 54 days old — INSIDE the current 60-day domain-cadence active window → trend HELD emerging; 60-day
    dormancy re-check 2026-07-26 unchanged.
  - 2026-07-21 (daily): fresh math.CO 2026-07-20 batch scanned for Ramsey lower bounds — none (batch held a
    Hypergraph Tutte Polynomial, the Oum CDC exposition, Nosal-graph supersaturation, a 2n/21 induced-subgraph
    degree-parity bound, generalised-Erdős-box upper-bound reproof, etc.; no Ramsey-number lower bound, no
    referee/vetting outcome on the 2025–26 preprints). last_evidence 2026-05-27 is 55 days old — INSIDE the
    current 60-day domain-cadence active window → trend HELD emerging; 60-day dormancy re-check 2026-07-26
    (5 days out) unchanged.
  - 2026-07-22 (daily): fresh math.CO 2026-07-21 batch scanned for Ramsey lower bounds — none (batch held
    Norine's antipodal-coloring conjecture proof, Boots-Royle/Cao-Vince solution, slice-rank of P-echelon
    tensors, e-positivity classifications, etc.; no Ramsey-number lower bound, no referee/vetting outcome on
    the 2025–26 preprints). last_evidence 2026-05-27 is 56 days old — INSIDE the current 60-day domain-cadence
    active window → trend HELD emerging; 60-day dormancy re-check 2026-07-26 (4 days out) unchanged.
  - 2026-07-23 (daily): fresh math.CO 2026-07-22 batch scanned for Ramsey lower bounds — none (batch held
    Erdős-Lovász Tihany for even-hole-free graphs, the sharp exponent for the minimal-distance problem,
    Steiner-Wiener-index inverse problem, triple arrays from ovals, etc.; no Ramsey-number lower bound, no
    referee/vetting outcome on the 2025–26 preprints). last_evidence 2026-05-27 is 57 days old — INSIDE the
    current 60-day domain-cadence active window → trend HELD emerging; 60-day dormancy re-check 2026-07-26
    (3 days out) unchanged.
  - 2026-07-23 (Pass 2): re-checked the live math.CO RSS this pass — the only Ramsey-labelled item is a
    peripheral "Ramsey number of a graph obtained by attaching a pendant to a path (length 1 mod 4)" (a
    small exact-Ramsey computation, NOT a lower-bound breakthrough) → does NOT satisfy the reactivation
    criterion (fresh Ramsey lower-bound primary OR referee/vetting outcome). last_evidence 2026-05-27 is
    57 days old — inside the 60-day window → trend HELD emerging; 60-day dormancy re-check 2026-07-26 unchanged.
  - 2026-07-24 (daily): fresh math.CO 2026-07-23 batch scanned for Ramsey lower bounds — none (batch held
    the Frankl–Tokushige product conjectures for r-cross-intersecting families, Tight Hamilton Cycles in
    linearly quasirandom 3-graphs, a Kirkman-triple-system construction, and — notably — "Improved lower
    bounds for the Shannon capacity of odd cycles" [2607.21517], a lower-bound advance but on GRAPH CAPACITY,
    NOT a Ramsey number → captured as its own queue item, does NOT satisfy the reactivation criterion). No
    Ramsey-number lower bound, no referee/vetting outcome on the 2025–26 preprints. last_evidence 2026-05-27
    is 58 days old — INSIDE the current 60-day domain-cadence active window → trend HELD emerging; 60-day
    dormancy re-check 2026-07-26 (2 days out) unchanged.
  - 2026-W30 recalibration: HELD emerging/medium. last_evidence 2026-05-27 is 59 days old today (2026-07-25) —
    still INSIDE the 60-day domain-cadence active window BY ONE DAY, so NOT demoted (the rule is 60+ days; 59<60).
    Confirmatory checks this session: (a) a fresh arXiv math.CO Ramsey scan returned only peripheral Ramsey-TYPE
    items (tree-cycle Ramsey numbers 2026-07-20, multicolor vector-space Ramsey over 𝔽₂ 2026-07-19, products of
    simplices canonically Ramsey 2026-07-16, the pendant-to-path exact-Ramsey note 2026-07-21) — NONE a Ramsey-number
    LOWER-BOUND breakthrough; (b) an arXiv-API metadata check of the four tracked preprints (2507.12926, 2605.28793,
    2604.23986, 2605.25843) shows NO fresh v-update / referee outcome (newest update 2026-07-02, all predating this
    week). So the completed-burst read (W28/W29) still holds: no fresh lower-bound primary, no vetting outcome.
    DORMANCY DECISION: the trend crosses the 60-day line 2026-07-26 (tomorrow); absent a fresh Ramsey lower-bound
    primary or a referee/vetting outcome, it goes dormant at W31 (2026-08-01, 66 days) per the standing plan.
    Confidence held medium (unrefereed-preprint caution; still no vetting outcome).
  - 2026-07-27 (daily): DEMOTED emerging → dormant. last_evidence 2026-05-27 is 61 days old today —
    over the 60-day domain-cadence line (AGENTS.md § Domain cadence; daily.md §4 applies this on any
    run, not only at the weekly's pencilled-in W31 date). Confirmatory checks this session: a fresh
    arXiv math.CO/NT/AG/DG/RT/PR batch (weekend-quiet, newest submittedDate still 2026-07-24) held no
    Ramsey-number lower-bound item, and an arXiv-API metadata check of the four tracked preprints
    (2507.12926, 2605.28793, 2604.23986, 2605.25843) shows no fresh v-update since 2026-07-02 — no
    referee/vetting outcome. Completed-burst read (W28/W29/W30) stands confirmed. Confidence held
    medium. 120-day archive line: 2026-09-24 (or sooner on the standing weekly archive review) unless
    a fresh lower-bound primary or referee outcome reactivates it first.
  - 2026-07-28 (daily): fresh math.CO 2026-07-27 batch scanned for Ramsey lower bounds — none (batch
    held "Long antipaths in oriented graphs", "Exponentially Many Circuit Double Covers" (CDC-adjacent,
    not Ramsey), "A computer-assisted proof of Kuperberg's six-cylinder conjecture", "Maximum independent
    queen set on polyominoes is NP-complete", the K(π,1)-conjecture expository notes, etc.; no Ramsey-number
    lower bound, no referee/vetting outcome). Trend HELD dormant; 120-day archive line 2026-09-24 unchanged.
  - 2026-07-29 (daily): fresh math.CO 2026-07-28 batch scanned for Ramsey lower bounds — none (batch
    held "Solution of Erdős problem #443" (Cambie), the Cautis-Logvinenko conjecture (partial case),
    "A Spectral Proof of the Hypergraph Moore Bound", etc.; no Ramsey-number lower bound, no referee/
    vetting outcome on the four tracked preprints). Trend HELD dormant; 120-day archive line 2026-09-24
    unchanged.
  - 2026-07-30 (daily): fresh math.CO 2026-07-29 batch scanned for Ramsey lower bounds — none (batch
    held the Stanley–Gasharov claw-free-Schur-positivity convergence cluster, "An Optimal Bound for
    Ramsey Goodness of Cycles" [Ramsey GOODNESS for cycles, not a Ramsey-number lower bound — own queue
    item], "Combinatorial Bounds for Codes over Metric Spaces: Ramsey-Sidorenko Thresholds", etc.; no
    Ramsey-number lower bound, no referee/vetting outcome on the four tracked preprints). Trend HELD
    dormant; 120-day archive line 2026-09-24 unchanged.

### Non-invertible (categorical) symmetries in QFT (generalized global symmetries)
- stage: seed | confidence: low | first_seen: 2026-07-27 | last_evidence: 2026-07-23
- what: A maturing research direction extending 't Hooft-anomaly / global-symmetry analysis to
  NON-INVERTIBLE ("categorical"/"generalized") symmetries in quantum field theory — fusion-category
  symmetry defects applied to lattice anomalies, 2d CFT constructions, and now a systematic (2+1)d
  gapless-phase classification via the Symmetry TFT. Three fully independent author groups now hold
  concrete artifacts on this sub-theme, clearing the ≥3-group + artifact convergence bar today.
- evidence:
  - 2026-04-03 — https://arxiv.org/abs/2604.02856 — Oishi, Ebisu, "Type-IV 't Hooft Anomalies on the
    Lattice: Emergent Higher-Categorical Symmetries and Applications to LSM Systems" (abstract
    verified via arXiv API this session).
  - 2026-07-06 — https://scipost.org/SciPostPhys.21.1.005 — Antunes, Rong, "Irrational CFTs from
    coupled anyon chains with non-invertible symmetries?" (SciPost API metadata + page opened this
    session).
  - 2026-07-23 — https://scipost.org/SciPostPhys.21.1.019 — Bhardwaj, Gai, Huang, Inamura,
    Schäfer-Nameki, Tiwari, Warman, "Gapless phases in (2+1)d with non-invertible symmetries": a
    systematic Symmetry-TFT framework for phase transitions with categorical symmetries in (2+1)d,
    building on the same group's (2+1)d gapped-phase program (SciPost API metadata + page opened this
    session).
- notes: 2026-07-27 (daily, PROMOTION): 2604.02856 and the Antunes–Rong SciPost item had sat in the
  `observation_queue` since 07-05/07-07 as a 2-group "forming, below the ≥3 bar" pair (flagged again
  in the W30 report's "convergence to watch"); today's fresh SciPost sweep surfaced Bhardwaj et al.
  (Schäfer-Nameki's group, fully independent of both prior groups — verified via author lists this
  session) as a third independent artifact → promoted to a `seed` trend per the convergence-check rule
  (daily.md §4). Confidence LOW (first day as a trend; no hype-skepticism caveat needed — ordinary
  refereed/community-refereed theoretical-physics output, not an AI-assisted claim). Watch for a 4th
  group, citations of the Bhardwaj et al. framework, and any connection to the separately-tracked
  deconfined-criticality queue thread (2607.00762 / 2607.01815).

### Refutations of the Stanley-Gasharov claw-free Schur-positivity conjecture (algebraic combinatorics)
- stage: seed | confidence: medium | first_seen: 2026-07-30 | last_evidence: 2026-07-29
- what: THREE fully independent author groups, within a single week, produced concrete
  counterexamples to the ~28-year-old Stanley–Gasharov conjecture (recorded by Stanley 1998,
  credited to Gasharov) that the chromatic symmetric function of every claw-free graph is
  Schur-positive — clearing the ≥3-independent-group convergence bar. Unlike the AI-generated
  Jacobian-conjecture claim, these are elementary, computationally CHECKABLE counterexamples
  (single symmetric-function coefficients, cross-verified by independent implementations /
  exhaustive graph censuses), so the epistemic risk is lower than an unchecked large-scale claim
  — but all three remain unrefereed preprints from the same week.
- evidence:
  - 2026-07-23 — https://arxiv.org/abs/2607.21508 — Matherne, Morales, "Chromatic symmetric
    functions of claw-free graphs are not Schur positive": FIRST published counterexample (a
    12-vertex line graph with a negative Schur coefficient); also refutes Monical's 2018
    saturated-Newton-polytope conjecture. AI-ASSISTED (found using ChatGPT-5.6 Sol Pro — the
    sixth artifact in the standing AI-assisted-math wave). Abstract verified via arXiv API this
    session (v1 2026-07-23).
  - 2026-07-29 — https://arxiv.org/abs/2607.26364 — Prajapati, "A counterexample to the claw-free
    Schur-positivity conjecture": a FULLY INDEPENDENT 12-vertex counterexample (different graph,
    coefficient [s_(3,3,3,3)]X_G = −64), found via an exhaustive computer census of all 216,777
    connected claw-free graphs on ≤11 vertices (all Schur-positive) plus all 1,728,404 on 12
    vertices (exactly 2 non-Schur-positive classes) — establishing 12 vertices as the minimum
    possible order. No AI-assistance claimed. Abstract verified via arXiv API this session (v1
    2026-07-29).
  - 2026-07-29 — https://arxiv.org/abs/2607.27166 — Wang, Zhang, Zhao, "An infinite family of
    counterexamples to the Stanley–Gasharov conjecture": combines Prajapati's census with a fresh
    exhaustive search over 144,492 previously-untreated claw-free graphs (13–21 vertices),
    confirms Matherne–Morales's counterexample as the UNIQUE minimum one under a stated order, and
    constructs an INFINITE family of connected line-graph counterexamples — directly answering
    Matherne and Morales's own open question. Abstract verified via arXiv API this session (v1
    2026-07-29).
- notes: 2026-07-30 (daily, PROMOTION): Matherne–Morales sat on the queue + study_shelf since
  07-29 as a single below-bar item; today's fresh math.CO sweep surfaced Prajapati (2607.26364)
  and Wang–Zhang–Zhao (2607.27166) — both explicitly citing Matherne–Morales as independently
  prior — giving THREE fully independent groups on the same sub-theme within 07-23→07-29 →
  promoted to `seed` per the convergence-check rule (daily.md §4); this also independently clears
  the domain-cadence "landmark single result" bar (a ~30-year algebraic-combinatorics conjecture
  refuted). Confidence medium (not low, despite being day-one): the counterexamples are short,
  checkable computations reproduced across independent implementations/censuses, not a
  large-scale unchecked claim — but still unrefereed, so track for a referee outcome or a
  consolidated/definitive treatment that may supersede this cluster. Watch also for further
  independent confirmation of the companion Monical saturated-Newton-polytope refutation
  (Matherne–Morales only, so far).

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).

- 2026-07-29 — arXiv:2607.27197 — Arathoon, Ball, Kvalheim, "The Maxwell Conjecture is False" —
  https://arxiv.org/abs/2607.27197 — mathematical physics / classical electrostatics (axis 2,
  physics.class-ph/math-ph): exhibits a configuration of five point charges in Euclidean space whose
  electrostatic potential has at least 24 non-degenerate critical points, refuting Maxwell's
  ~150-year-old conjecture that the potential of $n$ point charges has at most $(n-1)^2$
  non-degenerate critical points ($(5-1)^2=16<24$). A landmark refutation of a classical named
  conjecture at the math↔physics interface. Abstract + authors verified via arXiv API this session
  (v1 2026-07-29). Also on `study_shelf`.
- 2026-07-29 — arXiv:2607.26956 — Kuang, Wang, "An Optimal Bound for Ramsey Goodness of Cycles" —
  https://arxiv.org/abs/2607.26956 — combinatorics (axis 1, math.CO): resolves the Pokrovskiy–Sudakov
  conjecture (highlighted as Conjecture 9.2 in Montgomery's 2026 ICM survey) that the optimal LINEAR
  condition $n\ge C|H|$ suffices for Ramsey goodness of cycles, proving $R(C_n,H)=(\chi(H)-1)(n-1)+
  \sigma(H)$ for every nonempty graph $H$ once $n\ge C|H|$ — the first bound linear in $|H|$, best
  possible up to a constant. Ramsey-ADJACENT (Ramsey GOODNESS for cycles, not a Ramsey-NUMBER lower
  bound) → own below-bar queue item, does NOT reactivate the dormant Ramsey-lower-bound trend. Abstract
  + authors verified via arXiv API this session (v1 2026-07-29).
- 2026-07-29 — Quanta Magazine, "Physicists Solve a Big Quantum Mystery. Now, Old Results Don't Add
  Up." — https://www.quantamagazine.org/physicists-solve-a-muon-mystery-now-old-results-dont-add-up-20260729/
  — particle physics / muon g−2 (axis 3, HEP precision): a digest tied directly to the tracked 2026
  Breakthrough Prize (muon g−2 collaborations, 2026-07-25 entry below) — explains that the BMW
  collaboration's lattice-QCD calculation (Nature 2021, since matched by independent lattice groups)
  now agrees with Fermilab's g−2 measurement to 1 part in 100 billion, resolving the old
  theory-vs-experiment tension in favor of "no new particles" — but this creates a NEW open puzzle: the
  VEPP-2000 collider's (Novosibirsk) CMD-3 detector's 2023 remeasured $e^+e^-\to$ pion-production rate
  diverges sharply from older data (BaBar, KLOE) used in the superseded "data-driven" g−2 prediction,
  and physicists do not yet know which measurement is right. Quanta page opened via `tvly extract` this
  session — a digest, NOT itself primary evidence (no single fresh 2026 arXiv/collaboration artifact
  named); routed here as context updating the standing muon g−2 / Breakthrough-Prize thread. Follow to
  the VEPP-2000/CMD-3 primary and any new BMW/lattice preprint next.
- 2026-07-29 — arXiv:2607.25928 — Cambie, "Solution of Erdős problem #443" — https://arxiv.org/abs/2607.25928
  — combinatorial number theory (axis 1, math.CO/NT): proves that the intersection
  $\{k(m-k)\}\cap\{l(n-l)\}$ (over $1\le k\le m/2$, $1\le l\le n/2$) has size $(mn)^{o(1)}$ but can be
  arbitrarily large, resolving Erdős problem #443. Abstract opened via arXiv API this session (v1
  2026-07-27). Single below-bar resolved-open-problem item.
- 2026-07-29 — arXiv:2607.25982 — Craw, Yamagishi, "The Cautis-Logvinenko conjecture" —
  https://arxiv.org/abs/2607.25982 — algebraic geometry / representation theory (axis 1, math.AG/RT):
  proves the Cautis-Logvinenko conjecture (purity, under the Bridgeland-King-Reid derived equivalence,
  of the McKay-correspondence sheaves $\mathcal O_0\otimes\rho$ on the $G$-Hilbert scheme) whenever the
  McKay quiver of $G\subset SL(3,\mathbb C)$ has no loops — covering many dihedral/trihedral subgroups
  and six of the eight sporadic finite subgroups. A significant but partial (loop-free-quiver) case, not
  the full conjecture. Abstract opened via arXiv API this session (v1 2026-07-28). Single below-bar
  partial-progress item.
- 2026-07-29 — Rocq 9.3+rc1 — https://github.com/rocq-prover/rocq/releases — formal-math toolchain
  (axis 5, computer-assisted math): the Rocq proof assistant has moved past the previously-tracked
  V9.2.0 to a 9.3 release candidate (lean4 and mathlib4 both unchanged at v4.33.0-rc1 this session).
  Release page opened via `tvly extract` this session (JS-shell rendering, standing-degraded path;
  exact release date not pinned via this access method). Single below-bar toolchain-release item.
- 2026-07-29 — PRL new since the 07-23 batch — "Testing Local Lorentz Invariance with Laser Tracking of
  the LAGEOS and LAGEOS II Satellites" (axis 3, fundamental-physics test) + "Direct Measurement of the
  In-Medium η′ Mass Spectrum through the γγ Decay Channel" (axis 3, hadron physics) + "Nonunique
  Decompositions of Mixed States and Deterministic Energy Transfers" (axis 4, quantum foundations) —
  https://feeds.aps.org/rss/recent/prl.xml — titles/dates (2026-07-27) via APS PRL RSS this session,
  articles not opened → unverified intake.
- 2026-07-28 — arXiv:2607.24691 — Matić, Radoičić, "A computer-assisted proof of Kuperberg's
  six-cylinder conjecture" — https://arxiv.org/abs/2607.24691 — discrete/convex geometry (axis 1,
  math.CO/MG): proves that at most six pairwise non-overlapping infinite unit cylinders can
  simultaneously touch a unit ball (six is achievable) — resolving Kuperberg's question exactly, via
  a computer-assisted case analysis (≈2.95M cases, each an elementary polynomial-inequality check on
  a box, full case list provided). Abstract opened via arXiv API this session (v1 2026-07-27). A
  resolved named conjecture by a clean, checkable computer-assisted method (the same growing pattern
  as the Balanced Four-Color Theorem and the OpenAI CDC proof). Also on `study_shelf`.
- 2026-07-28 — arXiv:2607.22844 — VandeBogert, "Carlsson's Conjecture and the Generalized Total Rank
  Conjecture in Characteristic Two" — https://arxiv.org/abs/2607.22844 — commutative algebra /
  algebraic topology (axis 1, math.AC/AT): proves the generalized total rank conjecture over regular
  rings of characteristic 2 (rank_R(P) ≥ 2^codim for a differential module P with a finite projective
  flag and nonzero homology), and as a corollary proves **Carlsson's conjecture for elementary abelian
  2-groups in every rank** — a long-standing (1980s) open problem on free group actions/rank bounds in
  homological algebra — plus sharp homology bounds for continuous actions of such groups and the sphere
  rank conjecture. Abstract opened via arXiv API this session (v1 2026-07-24). A landmark-quality
  resolution of an important special case of a named conjecture. Also on `study_shelf`.
- 2026-07-28 — arXiv:2607.24309 — Fraser, Huber, Pozsgay, Vona, "On the two-copy distillability of
  Werner states and a new partial trace inequality" — https://arxiv.org/abs/2607.24309 — quantum
  information theory (axis 4, math.RA/quant-ph): answers Problem 5 of "Five Open Problems in Quantum
  Information Theory" [PRX Quantum 3, 010101 (2022)] in the negative — the two-ququart Werner state
  ϱ(4,−1/2) is NOT two-copy distillable — via a new partial-trace norm inequality, and shows the
  one-copy and two-copy distillability regions of ϱ(d,α) coincide for every d (threshold α≥−1/2).
  Abstract opened via arXiv API this session (v1 2026-07-27). SECOND FULLY INDEPENDENT group (after
  Fu–Gao–Park, arXiv:2607.21367, queued/study_shelf 2026-07-24) resolving Werner-state 2-copy
  distillability within 4 days — a FORMING pair on this sub-theme (below the ≥3-group trend bar; watch
  for a third). AI-WATCH note (scope area, not tracked as the method): the paper states its results
  "have been found and written up with AI tools" — folded into the standing AI-assisted-math wave note
  below, not tracked separately.
- 2026-07-28 — arXiv:2607.24005 — Shi, "Fuglede's conjecture holds for three intervals" —
  https://arxiv.org/abs/2607.24005 — harmonic analysis (axis 1, math.CA): proves every bounded
  measurable subset of ℝ that is spectral AND a union of three intervals tiles ℝ by translation,
  completing Fuglede's (spectral-set) conjecture for this class, via a new cofactor-rigidity method on
  the secular determinant of an associated self-adjoint derivative. Abstract opened via arXiv API this
  session (v1 2026-07-27). Single below-bar case-restricted-progress item (Fuglede's conjecture is
  known false in general; this is 1D case-by-case progress).
- 2026-07-28 — SciPostPhys.21.1.021 — "Fay identities for polylogarithms on higher-genus Riemann
  surfaces" — https://scipost.org/SciPostPhys.21.1.021 — mathematical physics (axis 2, hep-th/math-ph):
  functional (Fay-type) identities for polylogarithms on higher-genus Riemann surfaces, relevant to
  string-amplitude/modular-graph-function computations. SciPost API metadata opened this session
  (published 2026-07-27). Single below-bar item.
- 2026-07-28 — arXiv:2607.24659 — Paolini, "The K(π,1) conjecture for Artin groups of spherical type"
  — https://arxiv.org/abs/2607.24659 — geometric group theory (axis 1, math.GT/GR): expository notes
  presenting a proof of the 50-year-old K(π,1) conjecture in the spherical case via combinatorial
  topology — NOT a new resolution (the spherical case was proved by Paolini–Salvetti in 2021; this
  author is the same Paolini, now writing up an expository account). Abstract opened via arXiv API
  this session (v1 2026-07-27). Minor below-bar intake (exposition of prior work, not a new result).
- 2026-07-27 — SciPostPhys.21.1.020 — de Boer, Hollander, Rolph, "A reverse black hole information
  problem" — https://scipost.org/SciPostPhys.21.1.020 — theoretical physics / holography (axis 2,
  hep-th): studies black-hole formation, detection and coarse-graining in AdS/CFT — the tension
  between boundary unitarity and mixed-state Hawking radiation in the bulk, via CFT states dual to
  trans-Planckian particle collisions and boundary probes distinguishing small AdS black holes from
  other microcanonical states. SciPost API metadata + page opened this session (published 2026-07-24).
  Single below-bar item, black-hole-information-problem adjacent.
- 2026-07-27 — SciPostPhys.21.1.017 — Belin, Collier, Eberhardt, Liska, Post, "A universal sum over
  topologies in 3d gravity" — https://scipost.org/SciPostPhys.21.1.017 — theoretical physics / 3d
  quantum gravity (axis 2, hep-th): a statistical version of the conformal bootstrap for AdS₃ gravity's
  sum over topologies, with surgery moves on bulk manifolds reflecting typicality/crossing symmetry of
  the boundary CFT₂ ensemble. SciPost API metadata + page opened this session (published 2026-07-23).
  Single below-bar item.

- 2026-07-25 — **2026 Breakthrough Prize in Fundamental Physics → the Muon g-2 collaborations (CERN, Brookhaven, Fermilab)** — https://breakthroughprize.org/ — recognition/ecosystem (axis 3, HEP precision / BSM): awarded "for multi-decade, groundbreaking contributions to the measurement of the muon's anomalous magnetic moment, pushing the boundaries of experimental precision" across three collaborations over six decades; six New Horizons prizes also awarded (early-career physics & math). Breakthrough laureate page opened this session (tvly) — CLOSES the prize-capture gap flagged 2026-07-12 (the Breakthrough 2026 fundamental-physics laureate had been missed). Ties to the famous muon g-2 anomaly (the a_μ tension with the Standard Model). Ecosystem/recognition item → follow to the collaboration's honored measurement papers next.
- 2026-07-24 — **2026 Fields Medals (IMU / ICM 2026, Philadelphia)** — https://www.mathunion.org/imu-awards/fields-medal/fields-medals-2026 — recognition/ecosystem, THE math event of the week (axis 1, pure math + math-physics): awarded 2026-07-23 at the ICM opening ceremony to **Yu Deng, John Pardon, Jacob Tsimerman, Hong Wang** — IMU laureate page WITH full citations opened this session (primary). Citations (verbatim highlights): **Deng** — PDE, incl. the rigorous derivation of the Boltzmann equation from hard-sphere dynamics and derivation of wave-kinetic equations from nonlinear dispersive systems; **Pardon** — symplectic geometry (virtual fundamental cycles, Fukaya categories, holomorphic-curve counts) + 3-manifold group actions & knot theory; **Tsimerman** — recasting o-minimality as a method of arithmetic/complex algebraic geometry, incl. Griffiths' algebraicity of period maps and the André–Oort conjecture for Siegel modular varieties; **Wang** — harmonic analysis & geometric measure theory: local smoothing, Fourier restriction, Falconer distance sets, Furstenberg sets in the plane, and the Kakeya problem in three dimensions. RADAR CONVERGENCE: two of the four honored bodies of work are ALREADY tracked here — **Wang's** Kakeya-3D (Wang–Zahl, arXiv:2502.17655) and Furstenberg-plane results are on the `study_shelf` / behind the 2026 Clay Award, and **Deng's** Boltzmann/wave-kinetic work is the 2026 Clay Award (Deng, Hani) queued 2026-07-08 → the radar's tracked landmark artifacts ARE the Fields-honored work. Also on `study_shelf`. (Same-ceremony IMU 2026 prizes noted as ecosystem: Chern Medal → Graeme Segal [math-physics/topology], Gauss Prize → Yurii Nesterov [optimization], Abacus Medal → Shayan Oveis Gharan [algorithms] — pages surfaced via IMU-site search, not individually opened → intake.)
- 2026-07-24 — arXiv:2607.21367 — "A solution to 2-copy distillability of Werner states" — https://arxiv.org/abs/2607.21367 — quantum-information theory / entanglement (axis 4, quant-ph/math-ph): proves Werner states in arbitrary dimension are 2-copy distillable **iff** 1-copy distillable, answering the longstanding open question of 2-copy distillability of Werner states — an important step toward whether every NPT (non-positive-partial-transpose) state is distillable, a central open problem in entanglement distillation. Abstract opened via arXiv API this session (v1 2026-07-23). Single below-bar resolved-open-question item; also on `study_shelf`.
- 2026-07-24 — arXiv:2607.21517 — "Improved lower bounds for the Shannon capacity of odd cycles" — https://arxiv.org/abs/2607.21517 — combinatorics / zero-error information theory (axis 1, math.CO): constructs large independent sets in strong powers (size 134753 in C₇¹⁰, 21909 in C₁₁⁶, 62530 in C₁₃⁶) improving the best-known lower bounds Θ(C₇) > 3.258020, Θ(C₁₁) > 5.289773, Θ(C₁₃) > 6.300109 — a concrete lower-bound advance on a famously hard problem (Shannon capacity of odd cycles). Abstract opened via arXiv API this session (v1 2026-07-23). Lower-bound advance but on GRAPH CAPACITY, not a Ramsey number → own below-bar queue item (does not lift the Ramsey trend).
- 2026-07-24 — arXiv:2607.21336 — "Lu's conjecture for minimal surfaces in codimension two" — https://arxiv.org/abs/2607.21336 — differential geometry (axis 1, math.DG): proves Lu's second-gap conjecture for closed minimal surfaces M²→S⁴ (if S+λ₂ is constant and > 2 then ≥ 3), completing the codimension picture — with Peng–Terng (hypersurfaces) and the Li–Zhao counterexamples (m≥3), the gap conjecture holds precisely for codim m=1,2 and fails for every m≥3. Abstract opened via arXiv API this session (v1 2026-07-23). Single below-bar resolved-conjecture (codimension-two case) item.
- 2026-07-24 — arXiv:2607.20849 — "Protected corners and a trichotomy for Han's conjecture" — https://arxiv.org/abs/2607.20849 — representation theory / homological algebra (axis 1, math.RT): progress on Han's conjecture (a finite-dimensional algebra with eventually-vanishing Hochschild homology has finite global dimension); proves a "protected corner" theorem settling the Liu–Morin extension conjecture beyond the monomial and special-biserial cases, and establishes a trichotomy for Gap-A failures on three strongly-connected vertices (all-infinite impossible). Abstract opened via arXiv API this session (v1 2026-07-23). Single below-bar partial-progress item.
- 2026-07-24 — Jacobian-conjecture / Keller-map arXiv CLUSTER (fresh) — arXiv:2607.21572 + arXiv:2607.20968 — https://arxiv.org/abs/2607.21572 · https://arxiv.org/abs/2607.20968 — algebraic geometry / commutative algebra (axis 1, math.AG/AC): the AI-announced (Claude Fable 5) counterexample to the ~87-year-old Jacobian Conjecture is now spawning a wave of on-arXiv mathematical analyses (joining Shaska 2607.20210, queued 2026-07-23 + on study_shelf → THREE items in ~3 days). (i) **2607.21572** "Generic degrees of real polynomial Keller maps with non-dense image" — determines the possible generic degrees of real Keller maps with non-dense image (even, ≠2, hence ≥4; every even ≥4 occurs), realized in dim 3 by "an explicit member of the deformation family of the July 2026 counterexample to the Jacobian conjecture". (ii) **2607.20968** "An Explicit Characteristic-2 Counterexample to the Separable Jacobian Conjecture" — an explicit F: 𝔸³→𝔸³ over char-2 with Jacobian ≡ 1, field-extension degree 3, non-injective → counterexample to the separable (Adjamagbo) formulation in char 2, stabilizing to all n≥3. Both abstracts opened via arXiv API this session (v1 2026-07-23). CAVEATS (hype-skepticism + AI-watch): all downstream of an UNREFEREED, AI-generated counterexample announced OFF-arXiv (still community-pulse intake) → the refutation remains PROVISIONAL until independent vetting (Tao et al. publicly scrutinizing — a signal, not an outcome); tracked for the mathematical RESULTS, NOT the AI method (sibling AI radars' beat). A FORMING cluster to watch: if the counterexample survives vetting this is a landmark seed; NOT promoted while the underlying claim is unvetted.
  - 2026-07-27 (daily) — VETTING SIGNAL STRENGTHENS (community-pulse, still not a primary/formal outcome):
    Terence Tao's own blog post "A digestion of the Jacobian conjecture counterexample"
    (https://terrytao.wordpress.com/2026/07/21/a-digestion-of-the-jacobian-conjecture-counterexample/,
    dated 2026-07-21, opened via WebFetch this session — a capture-leak catch, not previously routed)
    goes well beyond "scrutinizing": Tao states the conjecture "was recently shown (using the Fable
    AI) that the conjecture is false in three dimensions", states it as "Theorem 2 (Counterexample to
    conjecture)" with no hedging, and gives his OWN independent geometric re-derivation of the
    counterexample "with relatively little use of algebraic geometry... that minimizes the amount of
    'miracles' required" — i.e. a leading mathematician has independently RECONSTRUCTED the
    mathematical content, not merely discussed it, and states he "used an AI chatbot ... to confirm
    several of the calculations". STILL not a formal peer-reviewed outcome and STILL not a primary
    under the hard rules (a mathematician's blog, not a journal/arXiv artifact) → stays community-pulse
    intake, caveat unchanged in kind, but this is the strongest vetting signal yet on the counterexample
    itself (as opposed to the on-arXiv analyses of it) — watch for Tao's reconstruction to itself land
    on arXiv, which would convert this into citable evidence.
- 2026-07-24 — PRL new since the 07-22 batch — "Programmable Open Quantum Systems" + "Pseudogauge-Invariant Nonequilibrium Density Operator" (axis 2, heavy-ion/relativistic-hydro QFT) + "Observation of Radiation-Loss-Based Non-Hermitian Point Gap in Photonic Crystals" (axis 3, non-Hermitian topological photonics) + "Space-Charge-Limited van der Waals Spin Transistor" (axis 3, cond-mat) — https://feeds.aps.org/rss/recent/prl.xml — titles via APS PRL RSS this session, articles not opened → unverified intake. (PRX top unchanged: Statistical Physics of Deep Learning [ML-theory off-core], molecular clock transitions / Floquet Ising machines already queued.)
- 2026-07-23 — arXiv:2607.20210 — Shaska, "Graded Keller maps and the Jacobian Conjecture" — https://arxiv.org/abs/2607.20210 — algebraic geometry (axis 1, math.AG): the FIRST arXiv mathematical analysis engaging "the map recently announced as a counterexample" to the ~87-year-old JACOBIAN CONJECTURE (Keller 1939). Classifies equivariant polynomial (Keller) maps by the SIGN-signature of their grading weights via weighted-projective geometry: the announced counterexample is equivariant for wt(x,y,z)=(1,−1,−2); if all weights are positive an equivariant Keller map is always an automorphism (no counterexample possible), and in dimension two the same holds for every sign pattern — so the counterexample necessarily lives in the mixed-sign, dim≥3 setting. Abstract opened via arXiv API this session (v1 2026-07-22). CONTEXT: the counterexample itself (3-variable, refuting the general conjecture) was announced OFF-arXiv (X post / Secret Blogging Seminar) and is AI-ASSISTED — "generated with Anthropic's Claude Fable 5" (WATCH area per scope: track the RESULT + this arXiv analysis, NOT the AI method — sibling AI radars' beat). Unrefereed + extraordinary-claim → PROVISIONAL under the hype-skepticism rule (Terence Tao and others actively scrutinizing it publicly — a vetting SIGNAL, not an OUTCOME; the counterexample announcement is NOT a primary I opened → the counterexample-claim itself stays community-pulse intake). Also on study_shelf. Single below-bar item (the on-arXiv analysis of a landmark claimed refutation).
- 2026-07-23 — arXiv:2607.20376 — Song, "The Erdős-Lovász Tihany Conjecture holds for all even-hole-free graphs" — https://arxiv.org/abs/2607.20376 — combinatorics / graph coloring (axis 1, math.CO): proves the 1968 Erdős-Lovász Tihany Conjecture — every graph with ω(G)<χ(G)=s+t−1 is (s,t)-splittable (V partitions so the two parts have chromatic numbers ≥s and ≥t) — for the class of even-hole-free graphs (using that they are C₄-free and every induced subgraph has a bisimplicial vertex). A new class-restricted case of a long-standing coloring conjecture. Abstract opened via arXiv API this session (v1 2026-07-22). Single below-bar item.
- 2026-07-23 — PRL/PRX new since the 07-21 batch — "Observation of Genuine Tripartite Non-Gaussian Entanglement from a Superconducting Three-Photon SPDC Source" (PRL, axis 4, multipartite non-Gaussian entanglement) + "Measurement of the Dispersion-Galaxy Cross-Power Spectrum with the Second CHIME/FRB Catalog" (PRL, axis 3, FRB cosmology) + "New Approach to Pulsar Timing Array Data Combination" (PRL, axis 3, PTA/GW) — https://feeds.aps.org/rss/recent/prl.xml — titles/dates via APS PRL RSS this session, articles not opened → unverified intake. (PRX top unchanged since 07-21: molecular clock transitions / MoTe₂ fractional-TI / classical-quantum path integrals already queued.)
- 2026-07-22 — arXiv:2607.19184 — "A counter-example to Batyrev's conjecture on the non-negativity of stringy Hodge numbers" — https://arxiv.org/abs/2607.19184 — algebraic geometry (axis 1, math.AG): gives a counter-example to Batyrev's conjecture — a fundamental open problem that "guided and motivated many beautiful results in motivic integration, mirror symmetry, and the McKay correspondence" — refuting the claimed non-negativity of stringy Hodge numbers. Abstract opened via arXiv API this session (v1 2026-07-21). AI-ASSISTED (WATCH area per scope): the counter-example was "discovered with the assistance of OpenAI's ChatGPT" — track the RESULT (a falsified fundamental conjecture), NOT the AI method (the sibling AI radars' beat). Unrefereed preprint → provisional under the hype-skepticism rule; track the vetting. Also on study_shelf. Single below-bar refuted-conjecture item.
- 2026-07-22 — arXiv:2607.18655 — "A proof of the mod 4 Kawauchi Conjecture" — https://arxiv.org/abs/2607.18655 — low-dimensional topology / knot theory (axis 1, math.GT): proves the mod-4 form of Kawauchi's conjecture on the Conway polynomial of amphicheiral knots (∇_K ≡ f(z)f(−z) mod 4), a statement the author conjectured in 2006 from finite-type-invariant patterns (the full integer conjecture is false — Ermotti–Hongler–Weber counterexample). Abstract opened via arXiv API this session (v1 2026-07-21). AI-ASSISTED (WATCH area): "produced with the help of Claude Fable 5" — track the RESULT, NOT the AI method. Unrefereed preprint → provisional; track the vetting. Single below-bar item.
- 2026-07-22 — arXiv:2607.19293 — "GWTC-5.0: Tests of General Relativity" (LIGO–Virgo–KAGRA) — https://arxiv.org/abs/2607.19293 — gravitational-wave physics / tests of GR (axis 3, gr-qc): the LVK collaboration's GR-tests companion paper to the GWTC-5.0 transient catalog; a citable collaboration artifact (pairs with GWTC-5.0 on study_shelf; a same-collaboration AdvancedVirgo+ O4 calibration paper 2607.xxxxx appeared in the same batch). Title/date via arXiv API this session (v1 2026-07-21), full article not opened → intake. Single below-bar item.
- 2026-07-21 — arXiv:2607.16695 — Nguyen-Dang, "Counterexamples of Friedlander–Iwaniec dual sums conjecture" — https://arxiv.org/abs/2607.16695 — analytic number theory (axis 1, math.NT): gives explicit counterexamples to Friedlander & Iwaniec's 2005 Conjecture 1 on sharply-truncated nonlinear dual sums 𝓑_{ℓ,D}(x,N), using A(s)=B(s)=ζ(s)^m with m≥4 — refuting the conjectured (DNx)^ε bound. Abstract opened via arXiv API this session (v1 2026-07-18). Single below-bar refuted-conjecture item.
- 2026-07-21 — PRX/Nature Physics new since the 07-20 batch — "Engineered Molecular Clock Transitions for Precision Measurements" (PRX 07-20, axis 3, AMO precision metrology / clock-transition engineering) + "Attosecond response of molecules to impulsive ionization" (Nature Physics 07-20, axis 3, AMO ultrafast — attosecond X-ray absorption tracking ionization dynamics in para-aminophenol; Nature Physics title HEALED via tvly extract this session past the recurring CDATA-empty RSS parse) — https://feeds.aps.org/rss/recent/prx.xml · https://www.nature.com/nphys.rss — titles/dates via APS PRX RSS + tvly this session, articles not opened → unverified intake.
- 2026-07-20 (updated 2026-07-21) — arXiv:2607.15399 + arXiv:2607.16356 — the OpenAI "Cycle Double Cover" proof, NOW WITH TWO independent expositions by leading structural-graph-theorists — https://arxiv.org/abs/2607.15399 (Geelen) · https://arxiv.org/abs/2607.16356 (Oum) — combinatorics / graph theory + machine-assisted math (axis 1/5, math.CO): clarifying expositions of an OpenAI-produced proof of the CYCLE DOUBLE COVER CONJECTURE (Szekeres 1973 / Seymour 1979 — a ~50-year-old open problem: every bridgeless graph has a family of cycles covering every edge exactly twice). (i) 2607.15399 Geelen (matroid theorist), abstract opened via arXiv API 07-20 (v1 2026-07-16); (ii) 2607.16356 Sang-il Oum (structural graph theory / rank-width), "A proof of the cycle double cover conjecture by OpenAI: An exposition" — "presents the proof with slight modifications intended to make it more accessible", abstract opened via arXiv API this session (v1 2026-07-17). TWO independent expositions within a day = the community is actively engaging with the artifact (a vetting SIGNAL, not yet a vetting OUTCOME). TRIPLE CAUTION: (i) AI-assisted math is a WATCH area per scope — track the RESULT + any formalization, NOT the AI method (the AI radars' beat); (ii) unrefereed + AI-generated → extraordinary-claim / hype-skepticism rule, PROVISIONAL until independent expert vetting (both notes are EXPOSITIONS, not independent confirmations of correctness); (iii) the original OpenAI paper was not locatable on arXiv this session. If the proof survives vetting this is a landmark. Geelen exposition also on study_shelf with the same caveats. Below-bar (WATCH-area result), two exposition artifacts.
  - 2026-07-28 (daily) — NEW INDEPENDENT MATHEMATICAL ENGAGEMENT (still a vetting signal, not an outcome):
    arXiv:2607.24724 — Hušek, Šámal, "Exponentially Many Circuit Double Covers" —
    https://arxiv.org/abs/2607.24724 — proves a counting version (≥2^{n/2−1} circuit double covers for
    2-edge-connected 3-edge-colorable cubic graphs, matching their own prior conjectured lower bound; a
    weaker exponential bound for girth-≥16 3-edge-connected cubic graphs) using "the same system of linear
    equations used by OpenAI in their proof," with additional combinatorial interpretation. Abstract opened
    via arXiv API this session (v1 2026-07-27). Independent authors BUILDING ON the OpenAI CDC machinery
    with new results — a further (stronger) community-engagement data point than a pure exposition, though
    still not a correctness referee outcome; the underlying OpenAI proof itself remains unrefereed. Folded
    into this cluster, not a separate queue item.
- 2026-07-20 — arXiv:2607.15406 — Juteau, Levy, Sommers, Yu, "Lusztig's special pieces conjecture" — https://arxiv.org/abs/2607.15406 — geometric representation theory (axis 1, math.AG/RT): proves every special piece P(O) of a special nilpotent orbit is the quotient of a smooth G-variety by a finite group, resolving Lusztig's conjecture for the exceptional Lie algebras (the classical case was Kraft–Procesi); two independent proofs given. Abstract opened via arXiv API this session (v1 2026-07-16). Single below-bar resolved-conjecture item.
- 2026-07-20 — arXiv:2607.15305 — Niedbala Giraudin, "A counterexample to a conjecture of Thakur on Carlitz-Wieferich primes" — https://arxiv.org/abs/2607.15305 — function-field arithmetic (axis 1, math.NT): refutes Thakur's 2015 conjecture that in odd characteristic every c-Wieferich prime has degree divisible by p, via an explicit degree-5 c-Wieferich prime over F_{19^3} (degree 5 is minimal). Abstract opened via arXiv API this session (v1 2026-07-14). Single below-bar refuted-conjecture item.
- 2026-07-20 — PRL/PRX new since the 07-17 batch — "Timescale for Macroscopic Equilibration in Isolated Quantum Systems: A Rigorous Derivation for Free Fermions" (PRL 07-19, axis 4, quantum-foundations / many-body equilibration) + "Periodic Gravitational Lensing with Oscillating Boson Stars" (PRL 07-17, axis 3) + "Progenitor of the Recoiling Supermassive Black Hole RBH-1 Identified Using HST and JWST" (PRL 07-17, axis 3, astro) + "Floquet-Based Ising Machines Escape Local Minima in QUBO Problems" (PRX 07-20, off-core QC) — https://feeds.aps.org/rss/recent/prl.xml — titles/dates via APS RSS this session, articles not opened → unverified intake.
- 2026-07-17 — arXiv:2607.15140 — "Absence of blow-up in the 3D Navier-Stokes equations with transport noise" (Agresti) — https://arxiv.org/abs/2607.15140 — analysis/PDE + probability (axis 1/2, math.PR/AP): proves the 3D Navier–Stokes equations driven by a suitably chosen TRANSPORT noise admit global-in-time smooth solutions with high probability, uniformly for initial data in arbitrarily large balls of subcritical spaces. A regularization-BY-NOISE result — explicitly NOT a resolution of the deterministic global-regularity open problem (no claim on the noise-free NSE). Abstract opened via arXiv API this session (v1 2026-07-16). Single below-bar item.
- 2026-07-17 — arXiv:2607.14143 — "The Planar Case of Thomas' Positive Circuits Conjecture" — https://arxiv.org/abs/2607.14143 — dynamical systems / monotone-network theory (OFF-AXIS explore find, math.DS): resolves the planar case of Thomas' conjecture that a positive feedback circuit is necessary for multistationarity. Significant-off-axis exploration catch (W28 anchoring redirect — deliberately read a non-tracked venue's top items); title/link via arXiv math.DS RSS this session, article not opened → unverified intake.
- 2026-07-17 — PRX new since the 07-16 batch — "Covariant Path Integrals for Quantum Fields Backreacting on Classical Space-Time" (axis 2, classical–quantum / post-quantum semiclassical gravity: a covariant path-integral for QFT backreacting on a classical spacetime) + "Candidate for a Fractional Topological Insulator in Twisted MoTe₂" (axis 3, topological cond-mat / fractional-TI candidate) — https://feeds.aps.org/rss/recent/prx.xml — titles/dates (2026-07-15/16) via APS PRX RSS this session, articles not opened → unverified intake.
- 2026-07-17 — PRL new since the 07-15 batch — "Observation of CP Violation in B⁰→J/ψρ(770)⁰ Decays" (axis 3, HEP flavor / CP violation in a new b-hadron channel) + "Any Unitary Gate Can Be Certified Device-Independently in a Quantum Network" (axis 4, quantum foundations / device-independent certification) + "Even Denominator Fractional Quantum Hall States in the Zeroth Landau Level of ABA Trilayer Graphene" (axis 3, topological cond-mat) — https://feeds.aps.org/rss/recent/prl.xml — titles/dates (2026-07-15/16) via APS PRL RSS this session, articles not opened → unverified intake.
- 2026-07-17 → 07-23 (Pass 2) — community-pulse (intake, UNVERIFIED — never evidence) — a multi-model AI-assisted-mathematics WAVE now landing CONCRETE arXiv artifacts, not just chatter: (07-17, r/math) GPT-5.6 reported to solve all six IMO 2026 problems + a claimed Lean-verified closing of a ~30-year gap in convex optimization; (07-20→23, HN front page + r/math) the JACOBIAN-CONJECTURE counterexample now the center of gravity — "Terence Tao is left scratching his head about the Jacobian Conjecture counterexample" (r/math top) + "Terence Tao's ChatGPT conversation about the Jacobian Conjecture counterexample" (HN front page), David Speyer's "The new counterexample to the Jacobian conjecture" (Secret Blogging Seminar) working through it; the counterexample (3-variable, refuting the general conjecture) attributed to Anthropic's Claude Fable 5 (Levant Alpöge's X announcement, >20M views per Fortune); an AMS Notices interview with Fields-frontrunner Jacob Tsimerman on AI in math; (07-22) an unverified RUMOR that the 2026 Fields Medal winner list leaked ahead of the ICM opening ceremony — https://www.reddit.com/r/math/ · https://news.ycombinator.com/ — WATCH area per scope: AI-assisted math is the sibling AI radars' beat. STATUS OF PRIMARIES (re-checked this session): the wave now has FIVE distinct AI-assisted results (four with concrete arXiv artifacts, one off-arXiv): OpenAI Cycle-Double-Cover proof (Geelen 2607.15399 + Oum 2607.16356 expositions), Batyrev-conjecture counter-example via ChatGPT (2607.19184), mod-4 Kawauchi proof via Claude Fable 5 (2607.18655), the Jacobian-conjecture counterexample via Claude Fable 5 — whose FIRST on-arXiv mathematical analysis appeared 07-22 (Shaska, 2607.20210, captured; the counterexample MAP itself is still announced only OFF-arXiv → the map stays intake, the analysis paper is the primary) — and NEW THIS PASS (07-23), a claimed disproof of the ~30-year-old DINITZ–GARG–GOEMANS conjecture on single-source unsplittable flows (Kleinberg/Dinitz–Garg–Goemans 1999: any fractional single-source flow can be rounded to an unsplittable one raising each edge by < d_max), attributed to Dmitry Rybin using GPT-5.6 Pro — announced OFF-arXiv (X post + Digg, surfaced via r/math + r/mathematics this pass); NO arXiv primary locatable this session (searched arXiv for Rybin/unsplittable-flow, only pre-existing DGG-related works) → stays UNVERIFIED community-pulse intake exactly like the Jacobian map, WATCH area (track the RESULT if/when a primary lands, not the method), extraordinary-claim caution (a 30-yr conjecture "disproof" is provisional until vetting). Community engaging = a vetting SIGNAL, not an OUTCOME (all unrefereed; Tao publicly scrutinizing). STILL NO IMU primary for the Fields Medal "leak": the mathunion.org Fields-Medal page (RE-OPENED this Pass 2, ~13:48 UTC) is STILL the static statute page — no 2026 laureates listed; a broad news search returned zero Fields-Medal hits (only sports/politics noise) → the announcement has NOT propagated as of this pass (ICM opening ceremony 23–30 Jul in Philadelphia; Fields Medals announced at the ceremony — still pending). CONFIRMED this pass that the 20th IMU General Assembly IS in session (NYC 20–21 Jul): r/math surfaced the GA vote selecting GLASGOW as ICM 2030 host (ecosystem, intake). Chase the official Fields announcement first thing next run. IMO-2026 results still have no arXiv artifact.
  - 2026-07-28 (daily) — wave continues, two more data points (still community-pulse/ecosystem, not
    primaries): (i) Peter Woit's blog (Not Even Wrong, "Requiem for a Field?", 2026-07-26, opened via
    RSS this session) reports 2026 Fields medalist **Jacob Tsimerman announced he is joining OpenAI**,
    hours after his medal was announced — quoting Kevin Hartnett's framing of his own Fields-week profile
    of Tsimerman as reading "like a requiem for a field," i.e. a leading pure mathematician moving into an
    AI lab; ties directly to the AMS Notices Tsimerman/AI-in-math interview already noted 07-23. (ii) the
    SECOND independent Werner-state 2-copy-distillability paper captured today (arXiv:2607.24309, queue)
    self-describes as "found and written up with AI tools" — a second concrete arXiv artifact (after the
    mod-4 Kawauchi and Batyrev items) explicitly AI-assisted outside the Jacobian-cluster/CDC storylines,
    reinforcing the wave is broadening across sub-fields (quantum information, not just pure geometry/
    combinatorics). Still WATCH-area, track results not methods.
  - 2026-07-29 (daily) — ICM 2026 (Philadelphia, closes tomorrow 07-30) puts AI-in-math on the PLENARY
    PROGRAM itself, not just community chatter: Terence Tao's ICM public lecture "Mathematics in the age
    of AI" (delivered 2026-07-24; slides at https://teorth.github.io, opened via `tvly search` this
    session) argues formalization + AI verification could resolve math's "crisis of trust" in an
    AI-accelerated era; the newly-published ICM 2026 Proceedings Vol. 2 (Plenary Lectures, SIAM,
    epubs.siam.org, `tvly search` this session) includes Alex Kontorovich's plenary on "how computational
    tools currently interact with mathematical practice" and Peter Bartlett's ML-theory plenary — i.e.
    TWO of this cycle's plenary lecture slots are explicitly about AI/math, alongside Tao's own public
    lecture (he chaired the ICM Structure Committee through Aug 2025). Gil Kalai's blog ("The Ramanujan
    Challenge for AI", opened via RSS this session) is a further community data point in the same vein.
    SEPARATELY, a SIXTH concrete AI-assisted arXiv artifact landed this session: arXiv:2607.21508
    (Matherne–Morales, refuting Stanley's claw-free Schur-positivity conjecture via ChatGPT-5.6 Sol Pro —
    captured as its own queue item above). All WATCH-area (sibling AI radars' beat) — but the wave has now
    visibly moved from "arXiv artifacts + blog chatter" to "the field's own flagship congress dedicating
    plenary slots to it," worth noting as the ecosystem's own signal of significance.
  - 2026-07-30 (daily) — INSTITUTIONAL RESPONSE (ecosystem/policy, not a tracked result): CERN Courier
    reports arXiv has formalized a "one-strike" content policy — a year-long submission suspension for
    "incontrovertible evidence of hallucinatory AI generation" (e.g. hallucinated references, citations
    to non-existent papers, stray model meta-commentary left in the text), per arXiv scientific director
    Steinn Sigurðsson, driven by a rising volume of AI-generated submissions straining moderation.
    https://cerncourier.com/a/arxivs-one-strike-rule-on-ai/ opened via `tvly extract` this session. The
    radar's own primary venue is now visibly reacting to the same wave tracked here since 07-17 — a
    direct institutional-response data point, still WATCH-area (policy/ecosystem, not a math/physics
    result; sibling AI radars' beat for the AI-method side).
- 2026-07-16 — arXiv:2607.13829 — "The inversion number of a path-reversed tournament: Resolving a conjecture of Belkhechine, Bouaziz, Boudabbous, and Pouzet" — https://arxiv.org/abs/2607.13829 — combinatorics / tournaments (axis 1, math.CO): computes the inversion number inv(Q_n) of the tournament obtained from the transitive tournament by reversing consecutive pairs, resolving a conjecture of Belkhechine et al. Single below-bar resolved-conjecture item; abstract opened via arXiv API this session (v1 2026-07-15).
- 2026-07-16 — arXiv:2607.13282 + 2607.13283 — "The H₀ World Cup I. Summary of the baseline group stage results" + "II. A comprehensive competition between proposed Hubble tension solutions" — https://arxiv.org/abs/2607.13282 — cosmology (axis 3, astro-ph.CO): a systematic head-to-head "tournament" ranking of proposed solutions to the Hubble tension against baseline datasets. Community meta-analysis (intake), ties into the tracked DESI dark-energy / late-time-anomaly saga; titles/links via arXiv RSS this session, articles not opened → unverified intake.
- 2026-07-16 — arXiv:2607.13673 — "Deriving the AdS₃×S³×T⁴ Quantum Spectral Curve I: Y-system and discontinuity relations" — https://arxiv.org/abs/2607.13673 — integrable systems / AdS/CFT (axis 2, nlin.SI/hep-th): first paper of a program deriving the Quantum Spectral Curve for the AdS₃×S³×T⁴ string background (Y-system, discontinuity relations). Single below-bar item; title/link via arXiv nlin.SI RSS this session (v1 2026-07-15).
- 2026-07-16 — PRL new since 07-15 batch — "Atomic Clock Frequency Ratios with Fractional Uncertainty ≤3.2×10⁻¹⁸" (axis 3, AMO precision-metrology record) + "Hidden Sector Custodial Naturalness" (axis 3, BSM) + "Demonstration of Deuterium's Enhanced Sensitivity to Symmetry Violations Governed by the Standard-Model Extension" (axis 3, Lorentz/CPT test) + "Connecting Magic Dynamics in Thermofield Double States to Spectral Form Factors" (axis 2/4, holography/quantum-info) — https://feeds.aps.org/rss/recent/prl.xml — titles/dates via APS PRL RSS this session, articles not opened → unverified intake.
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
- 2026-07-13 — SciPost Phys. 21, 011 (2026) — "A free fermions in disguise model with claws" (Pozsgay), published 2026-07-08 — https://scipost.org/ — axis 2/4 (integrable systems / free-fermion-in-disguise construction); metadata via tvly search (SciPost JSON API returned empty this session — degraded) → intake. Single below-bar item.
- 2026-07-07 — arXiv:2607.05374 — "The Minkowski grid has robustly many repeated distances" (Lee, Pohoata, Zhu) — https://arxiv.org/abs/2607.05374 — Erdős-type combinatorial geometry / repeated-distances (axis 1, math.CO/NT); abstract opened via arXiv API this session. Single below-bar item.
- 2026-07-07 — PRL 2026-07-06 — "Scattering Amplitudes and Conservative Binary Dynamics at O(G⁵) without Self-Force Truncation" — https://feeds.aps.org/rss/recent/prl.xml — axis 2 (scattering-amplitudes / post-Minkowskian expansion of the gravitational two-body problem, 5th PM order); title/date seen via APS PRL RSS this session, article not opened → unverified intake.
- 2026-07-05 — Nature Physics News&Views "Tangled up in spin" — https://www.nature.com/articles/s41567-026-03364-7 — neutron-scattering hints of quantum entanglement in a strange-metal state (axis 3/4, entanglement as a physical observable in a correlated metal); commentary blurb opened via Nature Physics RSS this session — underlying research paper NOT identified/opened → unverified intake.
- 2026-07-04 — SciPostPhys.21.1.004 — "Towards holographic color superconductivity in QCD" — https://scipost.org/SciPostPhys.21.1.004 — an AdS/holographic model of color-superconducting QCD matter (axis 2, hep-th/holography ↔ dense-QCD interface); SciPost API metadata (published 2026-07-02) opened this session. Single below-bar item.
- 2026-07-03 — arXiv:2607.02013 — "Resolution of the Detection Threshold Conjecture for Random Geometric Graphs in the d>n Regime" — https://arxiv.org/abs/2607.02013 — a resolved conjecture (axis 1, probability/combinatorics); RSS abstract opened this session.
- 2026-07-03 — arXiv:2607.01317 — "No Evidence for Superradiant Axions in LIGO-Virgo-KAGRA GWTC-5 Binary Black Hole Spins" — https://arxiv.org/abs/2607.01317 — null result constraining axion clouds from GWTC-5 spins (axis 3, DM/GW; pairs with GWTC-5.0 on study_shelf); RSS abstract opened this session.
- 2026-07-03 — arXiv:2607.01815 — "Evidence for Deconfined Magnetic Order in the Kitaev-J₃ Model" — https://arxiv.org/abs/2607.01815 — deconfined order (axis 3/4); RSS abstract opened. Deconfined-criticality/order sub-theme now 2 independent groups (with 2607.00762) — forming, not yet at the ≥3 bar.
- 2026-07-03 — arXiv:2607.01544 — "Formalized q-series: The Rogers-Ramanujan Identities and Beyond" — https://arxiv.org/abs/2607.01544 — machine-formalized classical q-series identities (axis 5, computer-assisted math); RSS abstract opened this session.
- 2026-07-08 — arXiv:2607.06545 — "A Higher-Order Clique Density Theorem" — https://arxiv.org/abs/2607.06545 — extremal graph theory (axis 1, math.CO): sharp lower bound for K_r-density at prescribed K_s-density (3≤s<r), a genuinely-nonlinear generalization of Reiher's clique density theorem; abstract opened via arXiv API this session. Single below-bar item, extremal-combinatorics (adjacent to but distinct from the Ramsey trend).
- 2026-07-09 — arXiv:2607.07641 — "The abc Conjecture Revisited" (Letendre) — https://arxiv.org/abs/2607.07641 — proposes a NEW abc-type conjecture and derives an application to sums of ω(n) (distinct-prime-factor counts) over short intervals (axis 1, math.NT); abstract opened via arXiv API this session. NOT a proof of abc — a proposed conjecture + consequence. Single below-bar item.
- 2026-07-08 — arXiv:2607.06398 — "Random Multiplicative Functions and Making Squares from Polynomial Values" — https://arxiv.org/abs/2607.06398 — analytic number theory / probability (axis 1, math.NT/PR): CLTs for sums of random multiplicative functions over polynomial values via a paucity phenomenon for P(n₁)…P(n₄)=□; abstract opened via arXiv API this session. Single below-bar item.
- 2026-07-08 — 2026 Clay Research Awards (page dated 2026-04-14) — https://www.claymath.org/2026-clay-research-awards/ — RESOLVED (was unverified since 07-03): recipients now confirmed via Clay page opened (tvly extract) this session — (i) Orponen, Shmerkin, Wang, Zahl for the Furstenberg set conjecture (plane) + Kakeya conjecture in 3D; (ii) Burklund, Hahn, Levy, Schlank for counterexamples to Ravenel's Telescope Conjecture; (iii) Deng, Hani. Recognition/ecosystem signal (axis 1 pure math). The underlying landmark artifacts (3D-Kakeya proof, Telescope-conjecture counterexample) are NOT opened this session → track and follow to those primaries next run.
- 2026-07-02 — 2026 Abel Prize presented to Gerd Faltings (ceremony) — https://www.mpim-bonn.mpg.de/ — MPIM institute page opened this session; major recognition in arithmetic/algebraic geometry (ecosystem/award, on-scope).
- 2026-07-02 — arXiv:2607.00762 — Deconfined criticality between an antiferromagnetic insulator and a nodal d-wave superconductor (quantum Monte Carlo) — https://arxiv.org/abs/2607.00762 — unverified (cond-mat.str-el listing; abstract not opened).
- 2026-07-23 — Formal-math toolchain releases: **mathlib4 now also at v4.33.0-rc1** (followed lean4 v4.33.0-rc1, both now at the same rc); lean4 unchanged at v4.33.0-rc1; Rocq V9.2.0 unchanged — https://github.com/leanprover/lean4/releases · https://github.com/leanprover-community/mathlib4/releases — release pages opened via tvly extract this session (axis 5: computer-assisted/formalized math). Exact release dates not pinned via tvly. Prior line (2026-07-16): lean4 v4.33.0-rc1, mathlib4 v4.32.0 (final), Rocq V9.2.0.

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

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-07-30 — [The Maxwell Conjecture is False (Arathoon, Ball, Kvalheim), arXiv:2607.27197](https://arxiv.org/abs/2607.27197)
  — refutes Maxwell's ~150-year-old conjecture that the electrostatic potential of $n$ point charges
  has at most $(n-1)^2$ non-degenerate critical points, via an explicit 5-point-charge configuration
  with 24 (axis 2, mathematical physics / classical electrostatics). Abstract + authors verified via
  arXiv API this session (v1 2026-07-29). A clean, classical, checkable refutation of a genuinely old
  named conjecture at the math↔physics interface — no AI-assistance or unrefereed-extraordinary-claim
  caveats apply (an explicit, verifiable counterexample).
- 2026-07-29 — [Chromatic symmetric functions of claw-free graphs are not Schur positive (Matherne,
  Morales), arXiv:2607.21508](https://arxiv.org/abs/2607.21508) — refutes Stanley's 1995 claw-free
  Schur-positivity conjecture (attributed also to Gasharov) via explicit line-graph counterexamples,
  and separately refutes Monical's 2018 saturated-Newton-polytope conjecture (axis 1, algebraic
  combinatorics). Abstract + authors verified via arXiv API this session (v1 2026-07-23). HEAVY CAVEATS
  (hype-skepticism + AI-watch rules): unrefereed preprint → PROVISIONAL until independent vetting; both
  counterexamples were "found using ChatGPT-5.6 Sol Pro" → tracked for the mathematical RESULT (a
  ~30-year conjecture refuted) a frontier combinatorialist should know, NOT the AI method (sibling AI
  radars' beat). Sixth concrete arXiv artifact in the standing AI-assisted-math wave.
- 2026-07-28 — [Carlsson's Conjecture and the Generalized Total Rank Conjecture in Characteristic Two (VandeBogert), arXiv:2607.22844](https://arxiv.org/abs/2607.22844) — proves the generalized total rank conjecture over characteristic-2 regular rings and, as a corollary, **Carlsson's conjecture for elementary abelian 2-groups in every rank** — a long-standing open problem in homological/commutative algebra on rank bounds for free group actions (axis 1, math.AC/AT). Abstract + author verified via arXiv API this session (v1 2026-07-24). A landmark-quality resolution of an important case of a named conjecture, worth knowing even though the full (odd-prime) conjecture remains open.
- 2026-07-28 — [A computer-assisted proof of Kuperberg's six-cylinder conjecture (Matić, Radoičić), arXiv:2607.24691](https://arxiv.org/abs/2607.24691) — settles Kuperberg's question exactly: at most six pairwise non-overlapping infinite unit cylinders can touch a unit ball (axis 1, discrete/convex geometry), via a checkable computer-assisted case analysis (~2.95M cases, full list published). Abstract + authors verified via arXiv API this session (v1 2026-07-27). A clean example of the growing computer-assisted-proof pattern in extremal/discrete geometry (alongside the Balanced Four-Color Theorem on this shelf).
- 2026-07-27 — [Gapless phases in (2+1)d with non-invertible symmetries (Bhardwaj, Gai, Huang, Inamura, Schäfer-Nameki, Tiwari, Warman), SciPostPhys.21.1.019](https://scipost.org/SciPostPhys.21.1.019) — a systematic Symmetry-TFT framework for phase transitions between gapless theories with categorical (non-invertible) symmetries in (2+1)d, extending the group's earlier gapped-phase program (axis 2, math↔physics interface / QFT). SciPost API metadata + page opened this session (published 2026-07-23). The artifact that completed today's `seed`-trend promotion (non-invertible/generalized symmetries, now ≥3 independent groups) — the clearest single entry point into a QFT sub-field a mathematical physicist should now be tracking.
- 2026-07-24 — [2026 Fields Medals — Deng, Pardon, Tsimerman, Wang (IMU / ICM 2026)](https://www.mathunion.org/imu-awards/fields-medal/fields-medals-2026) — the four 2026 Fields Medals, awarded 2026-07-23 at the ICM opening ceremony in Philadelphia, with the official IMU citations (axis 1, pure mathematics): **Yu Deng** (PDE — rigorous Boltzmann derivation from hard-sphere dynamics, wave-kinetic equations from dispersive systems), **John Pardon** (symplectic geometry — virtual fundamental cycles, Fukaya categories; 3-manifold group actions & knot theory), **Jacob Tsimerman** (o-minimality as a method in arithmetic/algebraic geometry — Griffiths' period-map algebraicity, André–Oort for Siegel modular varieties), **Hong Wang** (harmonic analysis & GMT — local smoothing, Fourier restriction, Falconer distance sets, Furstenberg-plane and the Kakeya problem in ℝ³). IMU laureate page with citations opened this session (primary). The single most important thing a frontier mathematician should absorb this week — and a radar convergence: Wang's Kakeya-3D (Wang–Zahl, on this shelf) and Deng's Boltzmann/wave-kinetic work (2026 Clay Award) are already-tracked landmark artifacts, now Fields-honored.
- 2026-07-24 — [A solution to 2-copy distillability of Werner states, arXiv:2607.21367](https://arxiv.org/abs/2607.21367) — proves Werner states (arbitrary dimension) are 2-copy distillable iff 1-copy distillable, resolving a longstanding open question in entanglement distillation and an important step toward the central open problem of whether every NPT state is distillable (axis 4, quantum-information theory). Abstract verified via arXiv API this session (v1 2026-07-23). A clean resolved-open-question a quantum-information researcher should know.
- 2026-07-23 — [Graded Keller maps and the Jacobian Conjecture (Shaska), arXiv:2607.20210](https://arxiv.org/abs/2607.20210) — the FIRST on-arXiv mathematical analysis of the announced counterexample to the ~87-year-old JACOBIAN CONJECTURE (Keller 1939): classifies equivariant Keller maps by the sign-signature of their grading weights (weighted-projective geometry), showing the announced counterexample must live in the mixed-sign, dimension-≥3 regime (all-positive weights, or any sign pattern in dim 2, force an automorphism) (axis 1, algebraic geometry). Abstract/author/date verified via arXiv API this session (v1 2026-07-22). HEAVY CAVEATS (hype-skepticism + AI-watch rules): the underlying counterexample (3-variable, refuting the general conjecture) was announced OFF-arXiv and is AI-GENERATED (Anthropic's Claude Fable 5) → PROVISIONAL until independent vetting (Terence Tao and others publicly scrutinizing it — a signal, not an outcome); tracked for the RESULT + this arXiv analysis a frontier researcher should know, NOT the AI method (sibling AI radars' beat). The biggest math story of the week (paired with the Batyrev and mod-4 Kawauchi results in the AI-assisted-math wave); watch for a confirmed refutation / a machine-checked formalization / a gap.
- 2026-07-22 — [A counter-example to Batyrev's conjecture on the non-negativity of stringy Hodge numbers, arXiv:2607.19184](https://arxiv.org/abs/2607.19184) — refutes Batyrev's conjecture, "a fundamental open problem" that guided decades of results in motivic integration, mirror symmetry, and the McKay correspondence (the assertion that stringy Hodge numbers of Gorenstein varieties are non-negative) (axis 1, algebraic geometry). Abstract + date verified via arXiv API this session (v1 2026-07-21). HEAVY CAVEATS (hype-skepticism + AI-watch rules): unrefereed preprint → PROVISIONAL until independent vetting; the counter-example was "discovered with the assistance of OpenAI's ChatGPT" → tracked for the mathematical RESULT (a falsified fundamental conjecture a researcher should know), NOT the AI method (the sibling AI radars' beat). Part of the 07-22 cluster of AI-assisted arXiv artifacts (with the mod-4 Kawauchi proof via Claude Fable 5 and the OpenAI CDC proof); watch for expert scrutiny.
- 2026-07-20 — [OpenAI's proof of the Cycle Double Cover Theorem (Geelen, exposition), arXiv:2607.15399](https://arxiv.org/abs/2607.15399) — a clarifying write-up by matroid theorist Jim Geelen of an OpenAI-produced proof of the CYCLE DOUBLE COVER CONJECTURE, one of graph theory's most famous ~50-year-old open problems (Szekeres 1973 / Seymour 1979: every bridgeless graph carries a family of cycles covering each edge exactly twice) (axis 1 combinatorics + axis 5 machine-assisted math). Abstract/author/date verified via arXiv API this session (v1 2026-07-16). HEAVY CAVEATS (hype-skepticism + AI-watch rules): the proof is AI-GENERATED and UNREFEREED → PROVISIONAL, not a confirmed resolution until independent expert vetting; Geelen's note is exposition (self-described "no new insights"), NOT community confirmation; the original OpenAI paper was not locatable on arXiv this session. Tracked for the RESULT + the exposition artifact a frontier researcher should know — NOT the AI method (the sibling AI radars' beat). Watch for expert scrutiny / a machine-checked formalization.
- 2026-07-16 — [A Proof of Sabidussi's Compatibility Conjecture (Ulyanov), arXiv:2607.13225](https://arxiv.org/abs/2607.13225) — resolves Sabidussi's compatibility conjecture: for a finite connected multigraph with all even degrees and min-degree ≥ 4 and an Eulerian closed trail T, the edges can be partitioned into circuits (indeed 4-coloured with an even-degree monochromatic-subgraph property) so no circuit uses two edges consecutive in T (axis 1, combinatorics/graph theory). Notable for axis 5: the proof is accompanied by a **Lean 4 formalization** in the author's GitHub — a machine-checked resolution of a named conjecture. Abstract + author + Lean-4 claim verified via arXiv API this session (v1 2026-07-14). Unrefereed single-author preprint — a claimed resolution → provisional under the hype-skepticism rule, but the accompanying formalization materially raises confidence; track the vetting.
- 2026-07-13 — [K-theoretic counterexamples to Ravenel's telescope conjecture (Burklund, Hahn, Levy, Schlank), arXiv:2310.17459](https://arxiv.org/abs/2310.17459) — the landmark DISPROOF of Ravenel's telescope conjecture: at each prime p and height n+1 ≥ 2, the telescopic (T(n+1)) and chromatic (K(n+1)) localizations of spectra differ — shown via the T(n+1)-localized algebraic K-theory of BP⟨n⟩^{hℤ} being non-K(n+1)-local (chromatic homotopy theory / algebraic K-theory). One of the two landmarks behind the 2026 Clay Research Award (Burklund–Hahn–Levy–Schlank); followed to primary from the Clay award resolved on the queue 2026-07-08, per the 07-10 report's Next. Abstract + authors verified via arXiv API this session (v1 26 Oct 2023).
- 2026-07-10 — [Volume estimates for unions of convex sets, and the Kakeya set conjecture in three dimensions (Wang, Zahl), arXiv:2502.17655](https://arxiv.org/abs/2502.17655) — the landmark RESOLUTION of the Kakeya set conjecture in ℝ³: every Kakeya set in ℝ³ has Minkowski and Hausdorff dimension 3, via a new volume estimate for unions of δ-tubes not concentrated in a common convex set (axis 1, geometric measure theory / harmonic analysis). Followed to primary from the 2026 Clay Research Award (Orponen–Shmerkin–Wang–Zahl, Furstenberg + 3D Kakeya) resolved on the queue 2026-07-08; abstract + authors verified via arXiv API this session (v1 24 Feb 2025). A 2025 artifact surfaced here on its Clay-2026 recognition — a genuinely field-shaping resolved conjecture worth knowing.
- 2026-07-09 — [The Algebraic Montgomery–Yang Problem (Jo, Park, Park), arXiv:2607.06686](https://arxiv.org/abs/2607.06686) — completely RESOLVES the algebraic Montgomery–Yang problem, a conjecture of Kollár: every rational homology projective plane with quotient singularities and a simply-connected smooth locus has at most three singular points. Proof combines a new lattice-theoretic constraint from Donaldson's diagonalization theorem + the distinguished spin^c structure on the smooth locus with the orbifold Bogomolov–Miyaoka–Yau inequality to rule out all remaining cases (axis 1, algebraic geometry ↔ 4-manifold topology). Abstract + authors verified via arXiv API this session (v1 7 Jul 2026). Unrefereed preprint — a claimed resolution of a named conjecture; track the referee/vetting outcome.
- 2026-07-07 — [The Burau representation of the braid group is faithful for n = 4 (Bharathram, Birman, Brendle), arXiv:2607.05283](https://arxiv.org/abs/2607.05283) — resolves a decades-old open problem in low-dimensional topology: the Burau representation of B₄ is faithful (it is classically faithful for n≤3 and known NON-faithful for n≥5 — Moody, Long–Paton, Bigelow — leaving n=4 as the last open case). Corollary: the Jones representation of B₄ is also faithful. Abstract + authors verified via arXiv API this session (v1 6 Jul 2026). Unrefereed preprint — but by leading braid-group topologists (Birman, Brendle) building on established methods; track the referee/vetting outcome.
- 2026-07-02 — [An exponential improvement for Ramsey lower bounds (Ma, Shen, Xie), arXiv:2507.12926](https://arxiv.org/abs/2507.12926) — first exponential improvement over Erdős' classical 1947 probabilistic lower bound for the Ramsey number r(ℓ, Cℓ); abstract + authors/dates verified this session (v1 17 Jul 2025, v2 26 Apr 2026). This is the "Erdős method upgrade" Quanta covered 2026-06-26 (Pass 1 mis-attributed it to Sudakov, who was only quoted — corrected).
- 2026-07-02 — [GWTC-5.0 — updated LIGO–Virgo–KAGRA gravitational-wave catalog](https://www.ligo.org/news.php) — new release of the GW transient catalog setting precision records; the current census of compact-binary mergers (LIGO collaboration news page opened this session).

## calibration

Append-only self-evaluation log MOVED to `logs/calibration.md` (see `radar-self-eval`).
Weekly runs APPEND there, never here.
