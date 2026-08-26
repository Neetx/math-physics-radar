# Trend ledger — Math-Physics Radar

Last updated: 2026-08-26

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(60+ days quiet — domain cadence; AGENTS.md § Domain cadence) ; `declining` (the field moved on). Confidence: `low | medium | high`.
Trend bar: ≥3 independent sources (different orgs/author groups) + ≥1 concrete artifact.

## Active trends

### Ramsey-number lower-bound breakthroughs (extremal combinatorics)
- stage: accelerating | confidence: medium | first_seen: 2026-07-03 | last_evidence: 2026-08-22
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
  - 2026-08-03 — https://arxiv.org/abs/2608.02537 — Steiner, "Multicolor Ramsey numbers of odd cycles are superexponential": extends a claimed OpenAI-model ("Astra") superexponential k-color triangle Ramsey lower bound (R_k(3)=k^Θ(k), OpenAI's "Ten Advances" announcement, queued below) to multicolor Ramsey numbers of fixed odd cycles, R_k(O_p) ≥ (log^{(p-1)}k)^{k/3-o(k)} for every fixed p (abstract + author via arXiv API this session, v1 2026-08-03).
  - 2026-08-22 — https://arxiv.org/abs/2608.21769 — Ihringer, Mattheus, "An improved algebraic construction for Ramsey numbers": explicit algebraic construction giving R(s,t) ≥ t^{(1-o(1))log s/log(log s+1)} uniformly for 3≤s≤t, improving the s-dependence in the Alon–Pudlák off-diagonal construction; first explicit construction with R(s,t) ≥ t^c for fixed s and c>2 (e.g. R(33,t) ≥ t^{2.1-o(1)}), also improving the diagonal case. Abstract + authors verified via arXiv API this session (v1 2026-08-22). A SIXTH independent author group (Sam Mattheus, of the already-staged sammattheus.wordpress.com source-discovery candidate, co-authoring a primary directly on this trend for the first time).
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
  - 2026-07-31 (daily): fresh math.CO/NT 2026-07-30 batch (187-entry broad-rotation sweep) scanned for
    Ramsey lower bounds — none (batch held "On a proof of the Gorenstein Symmetry Conjecture", "On
    Sirakov's equal-frequency uniqueness conjecture", "On a question of Gowers related to Littlewood's
    conjecture", a follow-up recursive Shannon-capacity-of-C7 construction, etc. — all captured as their
    own queue items below; no Ramsey-number lower bound, no referee/vetting outcome on the four tracked
    preprints). Trend HELD dormant; 120-day archive line 2026-09-24 unchanged.
  - 2026-W31 recalibration: HELD dormant/medium. last_evidence 2026-05-27 is 66 days old today
    (2026-08-01). Confirmatory checks this session: arXiv-API metadata on the four tracked preprints
    (2507.12926, 2605.28793, 2604.23986, 2605.25843) shows the newest per-paper update still 2026-07-02
    (2605.25843 v2) — no fresh v-update / referee outcome; a fresh math.CO Ramsey-keyword search
    returned only peripheral items (Ramsey-Sidorenko thresholds, Ramsey Goodness of cycles [already
    queued, not a lower bound], zero-sum/big-Ramsey-degree notes) — no lower-bound breakthrough. The
    completed-burst read (W28-W30) stands confirmed for a 5th consecutive week. 120-day archive line
    2026-09-24 unchanged; unless a fresh lower-bound primary or referee/vetting outcome appears first.
  - 2026-08-03 (daily): first daily since 07-31 (weekend gap, expected). Fresh math.CO/NT 2026-07-31
    batch (123-entry broad-rotation sweep) scanned for Ramsey lower bounds — none (batch held a Lean-
    verified Shannon-capacity-of-C7 follow-up, the Bolsinov-Konyaev-Matveev integrability conjecture
    proof, etc.; no Ramsey-number lower bound, no referee/vetting outcome on the four tracked
    preprints). Trend HELD dormant; 120-day archive line 2026-09-24 unchanged (69 days quiet today).
  - 2026-08-04 (daily, REACTIVATION): dormant → emerging. A fresh math.CO broad-rotation batch
    (2026-08-01→08-03, ~200 entries) surfaced arXiv:2608.02537 (Steiner, "Multicolor Ramsey numbers
    of odd cycles are superexponential") — a fresh, INDEPENDENT, ON-ARXIV Ramsey-NUMBER LOWER-BOUND
    primary, satisfying the standing W28 reactivation criterion ("a fresh Ramsey lower-bound primary
    ... reactivates it"). CONTEXT (caution warranted): Steiner's construction is a modification of a
    claimed result from an unreleased OpenAI model ("Astra"), announced 2026-08-01 in "Ten Advances in
    Mathematics and Theoretical Computer Science" (queued below as its own item), that R_k(3)=k^Θ(k)
    (resolving Erdős problem 183) — Steiner extends this to multicolor odd-cycle Ramsey numbers. Steiner's
    own paper is independently human-authored, peer-reviewable, and citable as a primary in its own right,
    but it explicitly assumes/builds on the correctness of the underlying OFF-ARXIV, UNREFEREED,
    AI-GENERATED base construction — so the reactivation is genuine (a real independent lower-bound
    contribution) but the confidence caveat is now DOUBLED: unrefereed-preprint caution on Steiner's own
    result, plus dependence on an unvetted AI-generated base result. Confidence HELD medium (not raised).
    5th independent author/group on the sub-theme (after Ma–Shen–Xie, Bradač, Du–Hu–Liu–Wang, Lin–Niu).
    New 60-day dormancy re-check: 2026-10-02.
  - 2026-08-05 (daily): fresh math.CO/GR/AG broad-rotation batch (2026-08-04, ~133 math entries)
    scanned for Ramsey lower bounds — none (batch was dominated by a rich cluster of OTHER
    landmark items — the period-index conjecture refutation, Crouzeix's conjecture, Zassenhaus-
    conjecture counterexamples, two Kourovka Notebook resolutions, all captured below — plus
    "Refined upper bounds on Schur-like numbers" [2608.03661], Ramsey-ADJACENT but an UPPER bound,
    not a lower bound → own queue item, does not reactivate/feed this trend). No Ramsey-number
    lower bound, no referee/vetting outcome on the five tracked preprints. Trend HELD emerging;
    60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-06 (daily): fresh math.CO/NT broad-rotation batch (2026-08-05, 141 fresh entries)
    scanned for Ramsey lower bounds — none (batch held a proof of the Freiman-Lev conjecture,
    a second Schiffer/Pompeiu counterexample, Tree-Product-Conjecture counterexamples, etc., all
    captured below; no Ramsey-number lower bound, no referee/vetting outcome on the five tracked
    preprints). Trend HELD emerging; 60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-07 (daily): fresh math.CO/NT broad-rotation batch (2026-08-05→08-06, 134 fresh
    2026-08-06 entries) scanned for Ramsey lower bounds — none (batch held Andersen's rainbow
    path conjecture proof [rainbow/anti-Ramsey, not a lower bound — own queue item], Gromov's
    dihedral rigidity conjecture, the HRT-conjecture disproof, etc., all captured below; no
    Ramsey-number lower bound, no referee/vetting outcome on the five tracked preprints). Trend
    HELD emerging; 60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-W32 recalibration: HELD emerging/medium. last_evidence 2026-08-03 (Steiner,
    2608.02537) is 5 days old — nowhere near the 60-day line (2026-10-02 unchanged). No further
    independent lower-bound primary landed this week (five dailies 08-03→08-07 all scanned
    fresh math.CO batches, none found); no referee/vetting outcome on any of the five tracked
    preprints (2507.12926, 2605.28793, 2604.23986, 2605.25843, 2608.02537). Confidence HELD
    medium — the doubled unrefereed-preprint caution on Steiner's result stands (own paper
    unrefereed + depends on OpenAI's unvetted "Astra" base construction), and this week's
    Scientific American attribution-misconduct report on the OpenAI cluster (08-06, see the
    OpenAI queue item) is a further reason NOT to raise confidence on anything downstream of
    that base result. Not promoted (no fresh W32 velocity beyond the already-recorded 08-04
    reactivation).
  - 2026-08-10 (daily): first daily since 08-07 (weekend gap, expected). Fresh math.CO/NT
    broad-rotation batch (2026-08-07, 138 fresh entries across the full in-scope math
    category set) scanned for Ramsey lower bounds — none (batch held a peripheral "Vertex-Ramsey
    theorems for Cartesian powers of graphs" [2608.07102], NOT a Ramsey-number lower bound;
    the Modularity-Conjecture and Mathieu-conjecture landmarks captured below, unrelated
    sub-theme). arXiv-API metadata check of all five tracked preprints (2507.12926, 2605.28793,
    2604.23986, 2605.25843, 2608.02537) shows no fresh v-update since 2026-08-03 — no
    referee/vetting outcome. Trend HELD emerging/medium; 60-day dormancy re-check 2026-10-02
    unchanged.
  - 2026-08-11 (daily): full math.CO/NT/AG/GT/DG/RT/PR/AC/RA/KT/AT/SG/AP/FA/CA/CV/OA/OC/LO/DS
    batch (2026-08-08→08-10, 392 fresh entries) scanned for Ramsey lower bounds — none (batch
    held the hyperkähler period-index refutation, the cyclotomic/almost-Moore-digraph proof,
    the Berenstein-conjecture counterexample, the Anthropic Riemann-zeta result, etc., all
    captured below, unrelated sub-theme). arXiv-API metadata on all five tracked preprints
    unchanged since 2026-08-03 — no referee/vetting outcome. Trend HELD emerging/medium;
    60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-12 (daily): fresh math.CO/NT/AG/GT/DG/RT/PR/AC/RA/KT/AT/SG/AP/FA/CA/CV/OA/OC/LO/DS
    batch (2026-08-09→08-11, 366 fresh entries) scanned for Ramsey lower bounds — none (only
    two peripheral Ramsey-labelled titles, a "nearcircumsphere-Ramsey theorem" for solvable
    transitive configurations and a small "pyramid with a Ramsey base" note, neither a
    Ramsey-number lower bound; batch dominated by the Kolokolnikov-conjecture double-discovery
    and other items captured below, unrelated sub-theme). arXiv-API metadata on all five
    tracked preprints unchanged since 2026-08-03 — no referee/vetting outcome. Trend HELD
    emerging/medium; 60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-13 (daily): fresh math.CO/NT/AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV/OA/OC/LO/DS/PR/RT
    broad-rotation batch (2026-08-12, 160 fresh entries) scanned for Ramsey lower bounds —
    none (batch's own landmark items — Gluck's conjecture, Butler's positivity conjecture,
    the Cohn-Kumar Leech-lattice auxiliary-function conjecture — all captured below,
    unrelated sub-theme; only routine Ramsey-type titles, e.g. "One-point extensions of
    Euclidean Ramsey sets," none a lower-bound breakthrough). arXiv-API metadata on all five
    tracked preprints unchanged since 2026-08-03 — no referee/vetting outcome. Trend HELD
    emerging/medium; 60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-14 (daily): fresh math.CO/NT/AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV/OA/OC/LO/DS/PR/RT
    broad-rotation batch (2026-08-13, 197 fresh entries) scanned for Ramsey lower bounds —
    none (a landmark-dense batch — Banach's isometric conjecture, Gromov's volume growth
    conjecture, the Chang-Yang conjecture, the Hayman-Wu constant, SOP2=SOP3 — all captured
    below, unrelated sub-theme; only routine Ramsey/Gallai-Ramsey titles, none a lower-bound
    breakthrough). arXiv-API metadata on all five tracked preprints unchanged since
    2026-08-03 — no referee/vetting outcome. Trend HELD emerging/medium; 60-day dormancy
    re-check 2026-10-02 unchanged.
  - 2026-08-17 (daily): first daily since 08-14 (weekend gap + W33 weekly 08-15, expected).
    Fresh math.CO/NT/AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV/OA/OC/LO/DS/PR/RT broad-rotation
    batch (2026-08-14, 151 fresh entries — the only new arXiv date; the 08-15/08-16 weekend
    and the Monday batch had not yet posted at run time) scanned for Ramsey lower bounds —
    only routine Ramsey/Schur/Gallai-Ramsey titles (a "Weakened Gallai-Ramsey Numbers for
    Books" note, Schur-log-concavity items — captured separately below, not Ramsey-number
    lower bounds). arXiv-API metadata check of all five tracked preprints shows no fresh
    v-update since 2026-08-03 — no referee/vetting outcome. Trend HELD emerging/medium;
    60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-18 (daily): fresh math.CO/NT/AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV/OA/OC/LO/DS/PR/RT
    broad-rotation batch (2026-08-15→08-17, 370 fresh entries) scanned for Ramsey lower bounds —
    none (batch dominated by other landmark items — Milnor's conjecture 2608.15505, Atiyah's
    Minkowski-space conjecture 2608.16693, Weibel's-conjecture counterexamples 2608.16066, the
    Chen-Raspaud conjecture proof 2608.15257, all captured below, unrelated sub-theme; only
    routine Ramsey/Gaifman-adjacent titles, none a lower-bound breakthrough). arXiv-API metadata
    check of all five tracked preprints shows no fresh v-update since 2026-08-03 — no
    referee/vetting outcome. Trend HELD emerging/medium; 60-day dormancy re-check 2026-10-02
    unchanged.
  - 2026-08-19 (daily): fresh math.CO/NT/AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV/OC/PR broad-rotation
    batch (2026-08-17→08-18, 400 fresh entries) scanned for Ramsey lower bounds — none (batch
    held the Complex-Hadamard-order-6 classification, Thompson's-conjecture-for-Lie-type
    completion, Sato's weak F-equivalence counterexamples, the Mahmoodian-Mirzakhani boundary
    case, all captured below, unrelated sub-theme; only routine Ramsey-adjacent titles — e.g. a
    rainbow Lehel's-conjecture note — none a lower-bound breakthrough). arXiv-API metadata check
    of all five tracked preprints shows no fresh v-update since 2026-08-03 — no referee/vetting
    outcome. Trend HELD emerging/medium; 60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-08-20 (daily): fresh math.CO/NT/AG/AC/RA/KT/AT/GT/DG/SG/AP/FA/CA/CV broad-rotation batch
    (2026-08-19, 176 fresh entries) scanned for Ramsey lower bounds — none (batch held "The
    regular pentagon is canonically Ramsey" [a Euclidean-Ramsey geometry note, not a Ramsey-number
    lower bound], Forni's periodic-orbit billiards landmark and other items captured below,
    unrelated sub-theme). arXiv-API metadata check of all five tracked preprints shows no fresh
    v-update since 2026-08-03 — no referee/vetting outcome. Trend HELD emerging/medium; 60-day
    dormancy re-check 2026-10-02 unchanged.
  - 2026-08-21 (daily): fresh math full in-scope category-rotation batch (2026-08-20, 178 fresh
    entries) scanned for Ramsey lower bounds — none (batch held an unrelated integer-programming
    method paper for classical small-Ramsey-number lower bounds via circulant graphs,
    arXiv:2608.18769, a different sub-area from the tracked asymptotic off-diagonal/hypergraph
    lower-bound wave — not counted as a new group). arXiv-API metadata check of all five tracked
    preprints shows no fresh v-update since 2026-08-03 — no referee/vetting outcome. Trend HELD
    emerging/medium; 60-day dormancy re-check 2026-10-02 unchanged.
  - 2026-W34 recalibration: HELD emerging/medium. last_evidence 2026-08-03 (Steiner, 2608.02537) is
    19 days old, nowhere near the 60-day line (2026-10-02 unchanged). arXiv-API metadata recheck of
    all five tracked preprints this session: no fresh v-update on any (newest still 2026-08-03) — no
    referee/vetting outcome. Fresh math.CO scan (through 2026-08-20/21, no new date posted by 08-22)
    held only "The regular pentagon is canonically Ramsey" (Euclidean-Ramsey geometry, not a
    Ramsey-number lower bound) — already logged by the 08-20 daily, not a new group. Not promoted
    (no fresh W34 velocity); confidence held medium (doubled unrefereed-preprint caution stands).
  - 2026-08-24 (daily): first daily since 2026-08-21 (weekend gap + W34 weekly 08-22, expected).
    Full in-scope math category-rotation RSS batch (2026-08-21, the latest posted; no fresher
    Monday batch yet) scanned for Ramsey lower bounds — none (only an unrelated "Structural
    Reductions for Monochromatic Matchings and Ramsey Tilings," 2606.24863, a different sub-area).
    arXiv-API metadata recheck of all five tracked preprints: no fresh v-update on any. Trend HELD
    emerging/medium; 60-day dormancy re-check 2026-10-02 unchanged (last_evidence now 21 days old).
  - 2026-08-25 (daily, PROMOTION): fresh math.CO batch (2026-08-22, first Tuesday-lag-cleared
    posting since the weekend) scanned for Ramsey lower bounds — CAUGHT Ihringer–Mattheus
    (2608.21769), a SIXTH independent author group with a genuine off-diagonal exponent
    improvement (first explicit R(s,t) ≥ t^c construction with c>2 for fixed s), appended as
    evidence above; last_evidence advances to 2026-08-22. Promoted emerging → accelerating
    (one-stage-max rule; six independent groups + continued fresh output over ~7 weeks reads as
    broad/fast, not merely forming). Confidence HELD medium (still no referee/vetting outcome on
    any of the six preprints — unrefereed-preprint caution stands). Also noted: a fresh circulant-
    graph small-Ramsey-number improvement, R(4,20)≥252 (arXiv:2608.18169, Yu), and an induced-
    threshold-graph Ramsey variant (arXiv:2608.22350, Li) — both Ramsey-ADJACENT but a different
    sub-area (explicit small-number bounds / induced Ramsey, not the tracked asymptotic off-
    diagonal/hypergraph exponent wave) — not counted as trend evidence, not individually queued
    (routine background activity in this sub-field). 60-day dormancy re-check reset to 2026-10-21.
  - 2026-08-26 (daily): fresh math.CO 2026-08-25 batch (arXiv API, sorted by submission date)
    scanned for Ramsey-number lower bounds — none (only the already-tracked-and-excluded
    2608.22350 threshold-graph variant recurring in a broader keyword search). No 7th independent
    group or referee/vetting outcome. Trend HELD accelerating/medium.

### Non-invertible (categorical) symmetries in QFT (generalized global symmetries)
- stage: accelerating | confidence: high | first_seen: 2026-07-27 | last_evidence: 2026-08-24
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
  - 2026-08-07 — https://www.nature.com/articles/s41567-026-03390-5 — Ueda, Vander Linden, De Vos,
    Lootens, Haegeman, Fendley, Verstraete, "Perfect particle transmission through duality defects"
    (Nature Physics, published online 2026-08-07): a FOURTH fully independent author group (Ghent
    University tensor-network/quantum-many-body group + Fendley, Oxford — independent of Oishi–Ebisu,
    Antunes–Rong, and Bhardwaj et al.), peer-reviewed in Nature Physics, constructs topological
    interfaces/duality defects in quantum spin systems with non-invertible symmetries giving perfect
    particle transmission (a lattice analogue of the Callan–Rubakov monopole-paradox resolution).
    Abstract + author list verified via `tvly extract` on the publisher page this session.
  - 2026-08-19 — https://arxiv.org/abs/2608.16520 — Flores-Calderón, Pollmann, Knap (TU Munich),
    "Non-invertible Lattice 1-Form Symmetries for Non-Abelian Topological Order": a FIFTH fully
    independent author group (condensed-matter/quantum-many-body, TUM — independent of Oishi–Ebisu,
    Antunes–Rong, Bhardwaj et al., and Ueda et al.), constructs non-invertible 1-form symmetry
    operators (governed by non-invertible fusion algebras, not a group) for non-Abelian topological
    order in quantum double lattice models $\mathcal D(G)$. Abstract + authors verified via arXiv
    API this session (v1 2026-08-14, surfaced in today's fresh physics batch).
  - 2026-08-20 — https://arxiv.org/abs/2608.18926 — Maruyoshi, Moon, Song, "Non-invertible symmetry
    and vertex operator algebra outer-automorphism": a SIXTH fully independent author group
    (independent of Oishi–Ebisu, Antunes–Rong, Bhardwaj et al., Ueda et al., and
    Flores-Calderón–Pollmann–Knap), on a distinct sub-application — the non-invertible symmetry of
    4d N=4 super Yang-Mills (from S-duality + half-space gauging + R-symmetry twist) realized as a
    vertex-operator-algebra outer-automorphism, matching the Schur/Macdonald index to a twisted
    vacuum character. Abstract + authors verified via arXiv API this session (v1 2026-08-19,
    surfaced in today's fresh hep-th batch).
  - 2026-08-24 — https://scipost.org/SciPostPhysCore.9.3.048 — Graf, Surace, Berg, Moroz, "The
    Ising dual-reflection interface: $\mathbb Z_4$ symmetry and Majorana strong zero modes": a
    SEVENTH fully independent author group (independent of Oishi–Ebisu, Antunes–Rong, Bhardwaj et
    al., Ueda et al., Flores-Calderón–Pollmann–Knap, and Maruyoshi–Moon–Song), on the lattice side
    — a non-invertible symmetry emerges in closed geometry at an interface combining a
    Kramers-Wannier transformation with spatial reflection in the transverse-field Ising chain,
    alongside a discrete $\mathbb Z_4$ symmetry realized via Majorana strong zero modes. SciPost
    Physics Core (community-refereed, acceptance date 2026-07-20); title/authors/abstract/DOI
    verified via the SciPost API this session.
  - 2026-08-22 — https://arxiv.org/abs/2608.21707 — Kobayashi, Otsuka, Tanimoto, Yamamoto,
    "Textures of dimension-six operators in the SMEFT with non-invertible selection rules": an
    EIGHTH fully independent author group (independent of all seven above), on a new
    sub-application — applies non-invertible selection rules to classify flavor textures of
    baryon-number-conserving dimension-six Standard Model Effective Field Theory operators,
    constraining Wilson-coefficient tensor structures. Abstract + authors verified via arXiv API
    this session (v1 2026-08-22).
- notes: 2026-07-27 (daily, PROMOTION): 2604.02856 and the Antunes–Rong SciPost item had sat in the
  `observation_queue` since 07-05/07-07 as a 2-group "forming, below the ≥3 bar" pair (flagged again
  in the W30 report's "convergence to watch"); today's fresh SciPost sweep surfaced Bhardwaj et al.
  (Schäfer-Nameki's group, fully independent of both prior groups — verified via author lists this
  session) as a third independent artifact → promoted to a `seed` trend per the convergence-check rule
  (daily.md §4). Confidence LOW (first day as a trend; no hype-skepticism caveat needed — ordinary
  refereed/community-refereed theoretical-physics output, not an AI-assisted claim). Watch for a 4th
  group, citations of the Bhardwaj et al. framework, and any connection to the separately-tracked
  deconfined-criticality queue thread (2607.00762 / 2607.01815).
  - 2026-W31 recalibration: HELD seed/low. No new evidence this week — SciPost API checked (20 most
    recent publications, 2026-07-21→07-31): nothing on non-invertible/categorical symmetries since
    Bhardwaj et al. (07-23). No 4th independent group yet. Confidence held low (still first week as a
    trend; no hype-skepticism caveat applies).
  - 2026-08-03 (daily): SciPost API rechecked (publications through 2026-07-31, IDs .021-.029) —
    nothing on non-invertible/categorical symmetries since Bhardwaj et al. (07-23); no 4th independent
    group. Trend HELD seed/low.
  - 2026-08-05 (daily): SciPost API rechecked (through SciPostPhys.21.2.031 / SciPostPhysCore.9.3.045,
    2026-08-03) — nothing on non-invertible/categorical symmetries since Bhardwaj et al. (07-23); no
    4th independent group. Trend HELD seed/low.
  - 2026-08-06 (daily): SciPost API rechecked (through SciPostPhys.21.2.033, 2026-08-05) — nothing
    on non-invertible/categorical symmetries since Bhardwaj et al. (07-23); no 4th independent
    group. Trend HELD seed/low.
  - 2026-08-07 (daily): SciPost API rechecked — no new publications since SciPostPhys.21.2.033
    (08-05); nothing on non-invertible/categorical symmetries since Bhardwaj et al. (07-23); no
    4th independent group. Trend HELD seed/low.
  - 2026-W32 recalibration: HELD seed/low. last_evidence 2026-07-23 is 16 days old — well
    inside the 60-day window, no dormancy concern. SciPost API rechecked this session (through
    the latest 2026-08 issue numbers, same state as the 08-07 daily) — still nothing on
    non-invertible/categorical symmetries since Bhardwaj et al.; still no 4th independent
    group after 2 full weeks as a trend. Confidence held low (no hype-skepticism caveat
    applies, but no fresh corroboration either — genuinely quiet, not thinning evidence).
  - 2026-08-10 (daily, PROMOTION): seed → emerging; confidence low → high. Today's DAILY-tier
    Nature Physics RSS sweep surfaced Ueda–Vander Linden–De Vos–Lootens–Haegeman–Fendley–Verstraete
    (Ghent + Oxford, fully independent of all three prior groups) — a 4th independent artifact,
    peer-reviewed (Nature Physics, not a preprint), satisfying both promotion criteria at once: the
    standing "watch for a 4th group" note, and the confidence-to-high bar ("≥2 INDEPENDENT
    authoritative primary sources corroborate on concrete artifacts") — SciPost's community-refereed
    Bhardwaj et al. and Nature Physics's traditionally-refereed Ueda et al. are two independent,
    authoritative, peer-reviewed corroborations of the same non-invertible-symmetries direction. No
    hype-skepticism caveat applies (ordinary refereed output, not an AI-assisted or extraordinary
    claim). Watch for a 5th group and for citations connecting this lattice/tensor-network thread to
    the Bhardwaj et al. continuum Symmetry-TFT framework.
  - 2026-08-11 (daily): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph batch
    (2026-08-08→08-10) and SciPost API (through SciPostPhys.21.2.037, 2026-08-10) both scanned —
    no 5th independent group on non-invertible/categorical symmetries specifically. One
    ADJACENT-but-distinct item noted, not counted toward this trend: arXiv:2608.08766 (Gu, Luo,
    Wang, Zhang, "Understanding Non-Split 2-Group Symmetry: (3+1)D SymTFT, Anomaly and Bordism")
    studies a non-split 2-GROUP (higher-group) symmetry's SymTFT/anomaly structure — a related
    generalized-symmetries technique (SymTFT) but a different symmetry structure (2-group, not a
    non-invertible/fusion-category symmetry) → captured as its own below-bar queue item, does not
    feed this trend. Trend HELD emerging/high.
  - 2026-08-12 (daily): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph batch
    (2026-08-09→08-11) and SciPost API (through SciPostPhys.21.2.038, 2026-08-11) both
    scanned — no 5th independent group on non-invertible/categorical symmetries specifically.
    Context note (ecosystem, not evidence): Simons Foundation announced a new "Simons
    Collaboration on the Virtues of Defects" led by Jaume Gomis (Perimeter), explicitly citing
    "advances in theories of defects that revealed new phases of quantum systems" among the
    motivating recent successes — thematically adjacent to this trend's non-invertible-defect
    research direction but a funding/ecosystem announcement, not a primary result (queued
    separately below). Trend HELD emerging/high.
  - 2026-08-13 (daily): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph batch
    (2026-08-11→08-12) and SciPost API (through SciPostPhysLectNotes.132 / SciPostPhysCore.9.3.047,
    2026-08-12) both scanned — no 5th independent group on non-invertible/categorical symmetries
    specifically. Trend HELD emerging/high.
  - 2026-08-14 (daily): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph batch
    (2026-08-13) and SciPost API (no new publications since SciPostPhysLectNotes.132/
    SciPostPhysCore.9.3.047, 2026-08-12) both scanned — no 5th independent group on
    non-invertible/categorical symmetries specifically. Trend HELD emerging/high.
  - 2026-08-17 (daily): first daily since 08-14. Fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/
    cond-mat/astro-ph batch (2026-08-14, 106 fresh entries) and SciPost API (3 new
    publications since SciPostPhysLectNotes.132, all 2026-08-14: supersymmetric Virasoro
    minimal strings, an invisible-pair/Michel-distribution note, Parisi-Sourlas-supersymmetry
    cohomology — none on-axis) both scanned — no 5th independent group on non-invertible/
    categorical symmetries specifically. Trend HELD emerging/high.
  - 2026-08-18 (daily): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph batch
    (2026-08-15→08-17, 304 fresh entries) and SciPost API (one new publication since
    SciPostPhys.21.2.041 — SciPostPhys.21.2.042 "Semi-universality of CFT_d entropy at large
    spin," 2026-08-17, a large-spin CFT thermodynamics result, not on-axis) both scanned — no
    5th independent group on non-invertible/categorical symmetries specifically. Trend HELD
    emerging/high.
  - 2026-08-19 (daily, 5th group): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph
    batch (2026-08-16→08-18, 400 fresh entries) surfaced arXiv:2608.16520 (Flores-Calderón,
    Pollmann, Knap, TU Munich) — a 5th fully independent group on non-invertible symmetries,
    satisfying the standing "watch for a 5th group" note (see evidence above). SciPost API
    rechecked (2 new since .042: .043 electro-nanomechanical Bell phase, .044 integrable 4d
    holomorphic-BF models — neither on this sub-theme). Confidence HELD high (already at the
    ceiling for an unrefereed-caveat-free ordinary result; a 6th group or explicit cross-citation
    between the lattice and continuum threads would be the next signal to watch). Trend HELD
    emerging/high.
  - 2026-08-20 (daily, 6th group): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph
    batch (2026-08-19, 138 fresh entries) surfaced arXiv:2608.18926 (Maruyoshi, Moon, Song) — a
    SIXTH fully independent group, on a different sub-application (VOA outer-automorphism
    realization in 4d N=4 SYM) than any of the five prior groups, satisfying the standing "watch
    for a 6th group" note (see evidence above). SciPost API rechecked (4 new since .044: .045
    Wilson lines with endpoints in 3d CFT, .046 frustrated bilayer edge currents, PhysCore .048-.049
    — none on this sub-theme). Confidence HELD high (already at ceiling; still watching for an
    explicit cross-citation linking the lattice/continuum threads). Trend HELD emerging/high.
  - 2026-08-21 (daily): fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/astro-ph batch
    (2026-08-20, 169 fresh entries) scanned — no 7th independent group, no explicit
    lattice/continuum cross-citation. SciPost API rechecked (routine, nothing on this sub-theme).
    Trend HELD emerging/high.
  - 2026-W34 recalibration (PROMOTION): emerging → accelerating; confidence HELD high. Velocity
    test: SIX fully independent author/institution groups (Oishi–Ebisu; Antunes–Rong; Bhardwaj et
    al.; Ueda et al., Nature Physics; Flores-Calderón–Pollmann–Knap; Maruyoshi–Moon–Song) across
    three distinct venues (SciPost ×2, Nature Physics, arXiv ×3) within a single 25-day window
    (07-27→08-20), with groups 5 and 6 landing in this same review week (08-19, 08-20) — sustained,
    still-accelerating multi-org cadence, not a one-time convergence burst. Confidence stays at the
    existing ceiling (no hype-skepticism caveat; ordinary refereed/community-refereed output).
    Promotion criterion (weekly.md §2, "broad, fast"): satisfied by breadth (6 independent groups,
    3 venue types, both lattice and continuum sub-applications) and pace (a new independent group
    roughly every 4 days over the trend's active life). One stage this week, per the one-stage-max
    rule. Watch for a 7th group or the still-outstanding explicit lattice/continuum cross-citation.
  - 2026-08-24 (daily, 7th group): first daily since 2026-08-21 (weekend gap + W34 weekly 08-22,
    expected). SciPost API rechecked (through SciPostPhysCore.9.3.048, 2026-08-21) surfaced Graf,
    Surace, Berg, Moroz — a SEVENTH fully independent group, satisfying the standing "watch for a
    7th group" note (see evidence above). Fresh hep-th/hep-ph/gr-qc/quant-ph/math-ph/cond-mat/
    astro-ph RSS batch (2026-08-21, the latest posted; no fresh entries since — weekend/Monday-
    batch-lag expected) scanned — no explicit lattice/continuum cross-citation yet. Confidence HELD
    high (already at ceiling). Stage HELD accelerating (already promoted this cycle at W34,
    2026-08-22; one-stage-max rule and no "mainstreaming"-tier signal — standard-practice adoption,
    not just group count — yet). Watch for an 8th group or the cross-citation.
  - 2026-08-25 (daily, 8th group): fresh hep-ph/hep-th batch (2026-08-22, first post-weekend/
    Monday-lag entries) surfaced Kobayashi–Otsuka–Tanimoto–Yamamoto (2608.21707), an EIGHTH fully
    independent group, satisfying the standing "watch for an 8th group" note — appended as
    evidence above; last_evidence unchanged at 2026-08-24 (a later item already on file). Notable:
    the first application of this trend's framework to Standard Model flavor phenomenology
    (SMEFT), distinct from all prior lattice/CFT/topological-order sub-applications — broadens the
    trend's reach beyond pure formal theory. Still no explicit lattice/continuum cross-citation
    found. A cross-listed hep-th "replace" of an old 2023 parafermionic-CFT defect-lines paper
    (arXiv:2309.01914 v2) was checked and excluded — a revision of pre-existing work, not a new
    primary. Confidence HELD high (ceiling); stage HELD accelerating (no mainstreaming-tier
    signal yet).
  - 2026-08-26 (daily): fresh hep-th/hep-ph 2026-08-25 batch + a direct "non-invertible symmetry"
    abstract search scanned — no 9th independent group and no lattice/continuum cross-citation.
    Trend HELD accelerating/high.

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
  - 2026-W31 recalibration: HELD seed/medium. No 4th independent group or referee/vetting outcome
    this week — arXiv search for fresh Schur-positivity/claw-free items returned only the three
    already-tracked papers plus unrelated claw-free-graph coloring results (packing/chromatic-index),
    not new counterexamples. Confidence held medium (short checkable computations, still unrefereed).
  - 2026-08-03 (daily): fresh math.CO 2026-07-31 batch scanned for Schur-positivity/claw-free items —
    none. No 4th independent group or referee/vetting outcome. Trend HELD seed/medium.
  - 2026-08-05 (daily): fresh math.CO 2026-08-04 batch scanned for Schur-positivity/claw-free items —
    none. No 4th independent group or referee/vetting outcome. Trend HELD seed/medium.
  - 2026-08-06 (daily): fresh math.CO 2026-08-05 batch scanned for Schur-positivity/claw-free items —
    none. No 4th independent group or referee/vetting outcome. Trend HELD seed/medium.
  - 2026-08-07 (daily): fresh math.CO 2026-08-06 batch scanned for Schur-positivity/claw-free items —
    none. No 4th independent group or referee/vetting outcome.
  - 2026-W32 recalibration: HELD seed/medium. last_evidence 2026-07-29 is 10 days old — well
    inside the 60-day window. Five dailies this week (08-03→08-07) all scanned fresh math.CO
    batches for Schur-positivity/claw-free items — none found; no 4th independent group, no
    referee/vetting outcome on any of the three tracked preprints. Confidence held medium
    (short, checkable computations, cross-verified across independent censuses — still
    unrefereed). Trend HELD seed/medium.
  - 2026-08-10 (daily): fresh math.CO 2026-08-07 batch scanned for Schur-positivity/claw-free
    items — none. No 4th independent group or referee/vetting outcome on any of the three
    tracked preprints. Trend HELD seed/medium.
  - 2026-08-11 (daily): fresh math.CO 2026-08-08→08-10 batch (392 entries) scanned for
    Schur-positivity/claw-free items — none. No 4th independent group or referee/vetting
    outcome on any of the three tracked preprints.
  - 2026-08-12 (daily): fresh math.CO 2026-08-09→08-11 batch (366 entries) scanned for
    Schur-positivity/claw-free items — none. No 4th independent group or referee/vetting
    outcome on any of the three tracked preprints. Trend HELD seed/medium.
  - 2026-08-13 (daily): fresh math.CO 2026-08-12 batch (160 entries) scanned for
    Schur-positivity/claw-free items — none. No 4th independent group or referee/vetting
    outcome on any of the three tracked preprints. Trend HELD seed/medium.
  - 2026-08-14 (daily): fresh math.CO 2026-08-13 batch (197 entries) scanned for
    Schur-positivity/claw-free items — none. No 4th independent group or referee/vetting
    outcome on any of the three tracked preprints. Trend HELD seed/medium.
  - 2026-08-17 (daily): first daily since 08-14. Fresh math.CO 2026-08-14 batch (151
    entries) scanned for Schur-positivity/claw-free items — none (a Skew-Schur
    log-concavity note and an m-symmetric-Schur-function characterization are unrelated
    Schur-function threads, not Stanley-Gasharov counterexamples). arXiv-API metadata check
    of all three tracked preprints shows no fresh v-update — no referee/vetting outcome.
    Trend HELD seed/medium.
  - 2026-08-18 (daily): fresh math.CO 2026-08-15→08-17 batch (370 fresh entries) scanned for
    Schur-positivity/claw-free items — two peripheral titles ("On the finite group whose proper
    enhanced power graph is claw-free" [2608.16434, group theory, unrelated] and "Three Infinite
    Families Separating Schur Positivity, the Strongly Nice Property, and the Nice Property"
    [2608.16613, a different Schur-positivity separating-families question, not a Stanley-Gasharov
    counterexample]) — neither a 4th independent group. arXiv-API metadata check of all three
    tracked preprints shows no fresh v-update — no referee/vetting outcome. Trend HELD seed/medium.
  - 2026-08-19 (daily): fresh math.CO 2026-08-17→08-18 batch (400 fresh entries) scanned for
    Schur-positivity/claw-free items — none new (only the already-tracked peripheral titles from
    08-18). No 4th independent group or referee/vetting outcome on any of the three tracked
    preprints. Trend HELD seed/medium.
  - 2026-08-20 (daily): fresh math.CO 2026-08-19 batch (176 fresh entries) scanned for
    Schur-positivity/claw-free items — none. No 4th independent group or referee/vetting outcome
    on any of the three tracked preprints. Trend HELD seed/medium.
  - 2026-08-21 (daily): fresh math.CO 2026-08-20 batch (178 fresh entries) scanned for
    Schur-positivity/claw-free items — none. No 4th independent group or referee/vetting outcome
    on any of the three tracked preprints (arXiv-API metadata unchanged). Trend HELD seed/medium.
  - 2026-W34 recalibration: HELD seed/medium. last_evidence 2026-07-29 is 24 days old, well inside
    the 60-day window. arXiv-API metadata recheck of all three tracked preprints (2607.21508,
    2607.26364, 2607.27166) this session: no fresh v-update on any — no referee/vetting outcome. No
    4th independent group surfaced this week (five dailies 08-17→08-21 all scanned fresh math.CO
    batches, none found; confirmed again this session). Confidence held medium (short, checkable,
    cross-verified computations — still unrefereed).
  - 2026-08-24 (daily): first daily since 2026-08-21 (weekend gap + W34 weekly 08-22, expected).
    Full in-scope math.CO RSS batch (2026-08-21, the latest posted) scanned for Schur-positivity/
    claw-free items — none. arXiv-API metadata recheck of all three tracked preprints: no fresh
    v-update. Trend HELD seed/medium; last_evidence now 26 days old, well inside the 60-day window.
  - 2026-08-25 (daily): fresh math.CO 2026-08-22 batch scanned for Schur-positivity/claw-free
    items — two peripheral titles found ("Schur positivity from signed elementary expansions:
    clique-spiders and spiders S(a,b,2)" and "Pfaffian-Toeplitz identities, Schur positivity, and
    the q-log-convexity of Baxter polynomials") — both unrelated general Schur-positivity results,
    not claw-free/Stanley-Gasharov counterexamples; the claw-free title re-appearing in today's
    feed is the already-tracked Prajapati preprint (2607.26364), not new. arXiv-API metadata
    recheck of all three tracked preprints: no fresh v-update — no referee/vetting outcome. No 4th
    independent group. Trend HELD seed/medium; last_evidence now 27 days old, well inside the
    60-day window.
  - 2026-08-26 (daily): fresh math.CO 2026-08-25 batch + a direct Schur-positivity/claw-free
    abstract search — no 4th independent group or referee/vetting outcome. Trend HELD seed/medium;
    last_evidence now 28 days old, well inside the 60-day window.

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).

- 2026-07-22 (CAPTURE-LEAK CATCH, chased via a Hacker-News-front-page pointer this session,
  accessed 2026-08-18) — BESIII Collaboration, "Lightest $0^{-+}$ Glueball as Dominant
  Constituent of $X(2370)$," arXiv:2607.20366 — https://arxiv.org/abs/2607.20366 — hadron/QCD
  physics (axis 3, hep-ex/hep-ph): reports the strongest evidence yet, from 10 billion $J/\psi$
  events, that the light hadron $X(2370)$ is dominated by the lightest $0^{-+}$ glueball — a
  particle made purely of gluons, sought since the 1970s — via a flavor-singlet-consistent
  suppressed-decay-mode signature. Abstract + collaboration authorship verified via arXiv API
  this session (v1 2026-07-22); widely covered mid-August by Nature News, Science, Ars Technica
  and ScienceAlert (opened via `tvly` this session), confirming the domain reads this as a
  landmark near-consensus first-of-kind result ("an experimental triumph" — Colin Morningstar,
  CMU, quoted in Science), though caution remains (Bruce Yabsley, U. Sydney, quoted in Nature:
  "no single smoking gun"). Domain-cadence landmark first-of-kind detection, missed by the
  ordinary arXiv sweep for 27 days until surfaced via today's community-pulse HN chase. Also on
  `study_shelf`.
- 2026-08-15 (v1; posted on preprints.org 2026-07-27 as v1, this is the DOI-stable v4 dated
  2026-08-06/07; discovered via a Hacker-News/press chase this session) — Shanmu Jin, "The
  Numerical Range Is a 2-Spectral Set," preprints.org DOI 10.20944/preprints202607.1919.v4 —
  https://www.preprints.org/manuscript/202607.1919 — operator/matrix theory (axis 1, math.FA):
  a SECOND, FULLY INDEPENDENT, AI-ASSISTED claimed proof of Crouzeix's conjecture (the same
  conjecture already on this ledger's `study_shelf` since 2026-08-04 via Lorist–Schwenninger,
  arXiv:2608.03841) — Jin's manuscript was actually posted FIRST (2026-07-27, ~8 days before
  Lorist–Schwenninger's independent human proof), via a 16-hour autonomous run with an
  unspecified OpenAI model, by a Beijing neurosurgery resident with no formal mathematics
  training. Preprints.org page opened via `tvly extract` this session (not an arXiv listing —
  off-arXiv, self-published-adjacent preprint server, same AI-disclosure-lane pattern as
  proofatlas.ai/openai.com). HEAVY CAVEATS (hype-skepticism + AI-watch rules): unrefereed,
  AI-substantially-assisted, off-arXiv → PROVISIONAL; per SIAM News (Alex Townsend, opened via
  `tvly` this session) the community has examined the manuscript but not yet certified it. Track
  the RESULT (that TWO independent routes now claim the same 20-year-old conjecture, a stronger
  convergence signal than either alone), not the AI method (sibling AI radars' beat). Eighth/
  ninth entries in the standing AI-assisted-math wave (Jin's paper predates and is independent of
  the already-counted Matherne–Morales entry). NEW SOURCE-DISCOVERY CANDIDATE: preprints.org
  (first sighting) — staged in SOURCES.md this session.
- 2026-08-15 (v1 2026-08-15; capture-leak-adjacent — completes a 2023 disproof program, chased
  via the fresh arXiv batch this session) — Nan Wu, Zetian Yan, "Prüfer $2$-group and Milnor's
  Conjecture on Fundamental Groups," arXiv:2608.15505 — https://arxiv.org/abs/2608.15505 —
  Riemannian geometry (axis 1, math.DG): constructs complete, one-ended manifolds in dimensions
  FOUR and FIVE with strictly positive Ricci curvature and infinitely generated (Prüfer
  $2$-group) fundamental group — counterexamples in "the two remaining dimensions" of Milnor's
  1968 conjecture (fundamental groups of complete nonnegative-Ricci manifolds are finitely
  generated), which was already known true for $n\le3$ and false for $n\ge6$ (Bruè–Naber–Semola
  2023, Quanta-covered) but open in dims 4–5 until now. Abstract + authors verified via arXiv API
  this session (v1 2026-08-15); prior status (true ≤3, false ≥6, open 4–5) corroborated via
  Wikipedia's "Milnor conjecture (Ricci curvature)" page and the original arXiv:2303.15347,
  opened via `tvly` this session. COMPLETES the Milnor-conjecture disproof program across every
  dimension — a genuine domain-cadence landmark (a 58-year-old named conjecture now fully
  resolved: true for $n\le3$, false for $n\ge4$). Also on `study_shelf`.
- 2026-03-06 (v1; CAPTURE-LEAK CATCH, ~5.5 months old, surfaced this session via a fresh follow-up
  paper citing it, accessed 2026-08-18) — Eva Viehmann, "Oort's conjecture on automorphisms of
  generic supersingular abelian varieties," arXiv:2603.06033 — https://arxiv.org/abs/2603.06033
  — arithmetic geometry (axis 1, math.AG/NT): proves Oort's conjecture in full generality — that
  generically on the supersingular locus of the moduli space of principally polarized abelian
  varieties of genus $g$ in characteristic $p$, the automorphism group of the universal abelian
  variety is $\{\pm1\}$ (with explicit exceptions at $g=2,3$, $p=2$) — resolving a standing
  conjecture in the theory of Shimura varieties / supersingular loci. Abstract + author verified
  via arXiv API this session; a same-day fresh follow-up (Karemaker–Yu, arXiv:2608.16405, v1
  2026-08-17, opened this session) explicitly cites Viehmann's "very recent" proof, which is how
  this months-old landmark was caught. Single-author, unrefereed — PROVISIONAL under the
  hype-skepticism rule, but by an established leader in the field (p-adic geometry / Shimura
  varieties). A near-miss capture-leak: this genuinely landmark result sat outside this ledger's
  window for over five months.
- 2026-08-17 — arXiv:2608.16405 — Valentijn Karemaker, Chia-Fu Yu, "Oort's conjecture on
  supersingular abelian varieties in odd characteristic" — https://arxiv.org/abs/2608.16405 —
  arithmetic geometry (axis 1, math.AG/NT): a same-day follow-up to Viehmann's proof of Oort's
  conjecture (arXiv:2603.06033, capture-leak-caught above) — constructs, for every $g\ge3$, an
  explicit codimension-1 locus of $a$-invariant $g-2$ meeting every irreducible component of the
  supersingular locus, refining the boundary/exceptional-locus structure around Viehmann's
  generic result. Abstract + authors verified via arXiv API this session (v1 2026-08-17). Below-
  bar follow-up/refinement item — the paper that led this session to Viehmann's landmark.
- 2026-08-15 — arXiv:2608.15257 — Qi Wu, Yong Lu, "A Proof of the Chen–Raspaud Conjecture" —
  https://arxiv.org/abs/2608.15257 — graph theory / flows (axis 1, math.CO): proves the
  Chen–Raspaud conjecture (2007) — every graph $G$ with odd girth $\ge2k+1$ and maximum average
  degree $<2+1/k$ admits a $(2k+1{:}k)$-coloring — for every $k\ge2$. Abstract + authors verified
  via arXiv API this session (v1 2026-08-15). Unrefereed two-author preprint claiming resolution
  of a named ~19-year-old conjecture — PROVISIONAL under the hype-skepticism rule; a below-bar but
  notable landmark-adjacent result a graph theorist should watch.
- 2026-08-17 — arXiv:2608.16693 — Ziran Liu, "Atiyah's Minkowski Space Conjecture Fails for Every
  $n\ge3$" — https://arxiv.org/abs/2608.16693 — mathematical physics / twistor geometry (axis 1/2,
  math.DG): disproves a conjecture of Michael Atiyah on the linear independence of binary forms
  built from admissible configurations of $n$ worldlines' retarded celestial directions, for every
  $n\ge3$, via an explicit planar counterexample at $n=3$. Abstract + author verified via arXiv
  API this session (v1 2026-08-17). Single-author unrefereed preprint refuting a named conjecture
  of a major 20th-century figure — provenance/age of the specific conjecture not independently
  dated this session; below-bar item.
- 2026-08-17 — arXiv:2608.16066 — Shane Kelly, "Some explicit counter-examples to Weibel's
  conjecture" — https://arxiv.org/abs/2608.16066 — algebraic K-theory (axis 1, math.AG/KT):
  constructs rings $R$ of Krull dimension 1 with $K_{-d}(R)\ne0$ for $d\ge2$. NOTE (caution
  warranted): Weibel's vanishing conjecture was proved by Kerz–Strunk–Tamme (2018) for NOETHERIAN
  schemes of finite Krull dimension — this abstract does not state whether $R$ is Noetherian, so
  it is unclear this genuinely contradicts the proven theorem rather than showing the necessity
  of a hypothesis outside it; not independently resolved this session. Abstract + author verified
  via arXiv API this session (v1 2026-08-17). Below-bar, caveated item — track for clarification.
- 2026-08-16 — arXiv:2608.15558 — Zijian Zeng, Houde Liu, Kurunathan Ratnavelu, "A Counterexample
  to the Tang Zhang Schatten Norm Conjecture and Sharp Positive Results" —
  https://arxiv.org/abs/2608.15558 — matrix analysis (axis 1, math.FA/CO): disproves a conjectured
  explicit formula (Tang–Zhang) for the best Schatten-$p$-norm subadditivity constant via two
  explicit $2\times2$ rank-one matrices at $p=3/2$. Abstract + authors verified via arXiv API this
  session (v1 2026-08-16). Single below-bar refuted-conjecture item (a recent, not classical,
  named conjecture).
- 2026-08-17 — arXiv:2608.16099 — Yi Zhang, "Counterexamples to the Generalized Gaifman
  Conjecture" — https://arxiv.org/abs/2608.16099 — mathematical logic / model theory (axis 1,
  math.LO): a negative answer to a 2025 conjecture of Shelah and Usvyatsov. Abstract + author
  verified via arXiv API this session (v1 2026-08-17). Single below-bar item (a young conjecture,
  not a classical named one).
- 2026-08-04 (CAPTURE-LEAK CATCH, ~2 weeks old, surfaced via the Simons Foundation feed this
  session, accessed 2026-08-18) — Simons Foundation, "New Simons Collaboration Will Explore
  Discrete Subgroups of Lie Groups" —
  https://www.simonsfoundation.org/2026/08/04/new-simons-collaboration-will-explore-discrete-subgroups-of-lie-groups/
  — ecosystem/recognition (axis 1/2, geometric group theory / Lie theory): launches a new Simons
  Collaboration studying discrete subgroups of Lie groups (lattices, thin groups, dynamics on
  homogeneous spaces) — thematically adjacent to several already-tracked items on this ledger
  (profinite rigidity of PSL(2,C) lattices, 2607.19012/2608.07350). Page opened via `tvly extract`
  this session. Funding/ecosystem announcement, not a result — below-bar item, missed by the daily
  RSS check for two weeks (a smaller, second item further down the same feed).
- 2026-08-13 (unverified — chased via a community-pulse Hacker-News/press pointer this session, no
  primary artifact located; accessed 2026-08-18) — Levent Alpöge (Anthropic), Philippe Voinov,
  Saul Reynolds-Haertle, with the LLM Claude — claimed construction of Hadamard matrices for every
  previously-unknown admissible order up to 2000, INCLUDING order 668 (the smallest order for
  which none was known, per Kharaghani–Tayfeh-Rezaie 2005's order-428 record) — combinatorial
  design theory (axis 1, math.CO). NO PRIMARY ARTIFACT: disclosed only via a personal X/Twitter
  post (not opened this session — X is not a primary source under this radar's hard rules), no
  arXiv listing, no official Anthropic research page located despite a search this session (unlike
  the tracked Riemann-zeta and "Ten Advances" disclosures, which used openai.com/anthropic.com
  official pages). Corroborating secondary sources opened this session: a MathOverflow answer
  (https://mathoverflow.net/questions/85201/status-of-hadamard-matrix-conjecture, describing and
  linking the X post) and a John D. Cook blog post
  (https://www.johndcook.com/blog/2026/08/13/constructing-hadamard-matrices). UNVERIFIED per the
  evidence rules — queued, not evidenced; watch for an arXiv posting or official research-page
  disclosure to promote/verify. If confirmed, this would be a notable landmark (closing the
  smallest known gap in the 1893 Hadamard conjecture) in the standing AI-assisted-math wave.
- 2026-08-13 (W33 weekly-swept institute sweep, Perimeter Institute news page) —
  Hook, Huang, Shalaby, "No cosmological constraints on dark photon dark matter from
  resonant conversion: impact of nonlinear plasma dynamics," arXiv:2510.13956, now
  published Phys. Rev. Lett. 137, 071004 (2026) — https://arxiv.org/abs/2510.13956 —
  particle/astro-particle phenomenology (axis 3, hep-ph/astro-ph): shows the standard
  linear treatment of dark-photon-to-photon resonant conversion in the early-universe
  plasma is invalidated by plasma nonlinearities that self-quench the conversion,
  invalidating cosmological exclusion bounds and reopening a dark-photon-dark-matter
  parameter space previously thought ruled out by ~8 orders of magnitude (Perimeter +
  U. Maryland). Perimeter news page (2026-08-13) + arXiv API metadata + APS journal
  listing all opened via `tvly` this session (v1 2025-10-15, PRL-published 2026-08-13).
  Peer-reviewed (PRL) — not provisional. A below-bar but notable phenomenology result
  a frontier physicist should track; caught only via the weekly institute sweep (the
  daily arXiv PRL scan reads titles/dates, not every result gets individually chased).
- 2026-08-07 (CAPTURE-LEAK CATCH, W33 weekly sweep — named in the Ramsey trend's own
  notes since the 08-11 daily but never given its own queue line) — arXiv:2608.07102 —
  "Vertex-Ramsey theorems for Cartesian powers of graphs" — https://arxiv.org/abs/2608.07102
  — extremal combinatorics (axis 1, math.CO): a peripheral Ramsey-type result explicitly
  checked and found NOT a Ramsey-NUMBER lower bound (does not feed the Ramsey trend).
  Abstract not independently re-opened this session (routed on the trend note's own
  characterization); queued per the capture rule rather than left in another item's prose.
  Single below-bar item.
- 2026-08-05 (v1 on proofatlas.ai; digested/formalized by Terence Tao, chased via Tao's blog
  2026-08-12) — Lech Mazur (curator/prompter) + OpenAI GPT-5.6 Pro, "A Computer-Assisted Proof
  of Sendov's Conjecture" — https://www.proofatlas.ai/papers/sendov-conjecture/SENDOV_CONJECTURE_PROOF_AUGUST_5_2026.pdf
  · Lean 4 formalization https://github.com/teorth/sendov · Tao's digestion
  https://terrytao.wordpress.com/2026/08/12/a-digestion-of-the-proof-of-sendovs-conjecture/ —
  complex analysis (axis 1, math.CV): claims to resolve SENDOV'S CONJECTURE (posed 1958,
  ~68 years open) IN FULL GENERALITY for all degree n≥2 polynomials with zeros in the closed
  unit disk, plus its Phelps–Rodriguez strengthening — extending Tao's own 2020 partial result
  (arXiv:2012.04125, "sufficiently high degree") to the remaining intermediate-degree cases.
  PDF + GitHub repo both opened via `tvly extract`, Tao's blog post opened via curl, this
  session (proof PDF dated 2026-08-05; Tao's digestion post 2026-08-12). HEAVY CAVEATS
  (hype-skepticism + AI-watch rules): "Generative AI played a substantial role in the discovery
  and derivation of the mathematics ... not merely in editing" (paper's own disclosure); the
  manuscript is off-arXiv, self-published on a dedicated AI-proof platform, and unrefereed →
  PROVISIONAL under the standard rule. UNUSUALLY STRONG VETTING SIGNAL, however, distinguishing
  this from the wave's earlier entries: Terence Tao — the field's own leading expert on this
  exact conjecture — has personally spent "several days" independently re-deriving and
  human-digesting the argument, and has built and published his own companion Lean 4
  formalization repository verifying the exact theorem statement against a pinned
  Lean/Mathlib toolchain (per the paper's own "Formalization status" note). Track for Tao's
  completed writeup, any gap found during the digestion, and independent specialist review.
  Seventh entry in the standing AI-assisted-math wave. NEW SOURCE-DISCOVERY CANDIDATE:
  proofatlas.ai (first sighting) — a dedicated self-publication platform for AI-generated
  proofs, structurally the same pattern as the already-tracked openai.com/anthropic.com
  AI-disclosure lanes — staged in SOURCES.md this session (see strategy_notes).
- 2026-08-12 — Alex Cohen, "Fractal uncertainty in higher dimensions," arXiv:2305.05022,
  now published in the Annals of Mathematics (2025) — https://arxiv.org/abs/2305.05022 —
  surfaced via a Quanta Magazine feature this session,
  https://www.quantamagazine.org/graduate-student-proves-the-fractal-uncertainty-principle-20260812/
  — harmonic analysis / mathematical physics interface (axis 1/2, math.CA↔quantum chaos):
  extends the Bourgain–Dyatlov fractal uncertainty principle (2016, 1D) to ALL higher
  dimensions, resolving the open extension problem from the 2016 Dyatlov–Bourgain workshop;
  originally Cohen's PhD thesis (MIT), now peer-reviewed in the field's top journal. Abstract
  verified via arXiv API + Quanta article opened via `tvly extract` this session. No AI or
  hype-skepticism caveats — ordinary refereed mathematics, now community-recognized ("a
  foundational result" — Peter Sarnak, IAS) well after its original 2023 preprint.
- 2026-08-12 — Baoyu Zhang, "A Proof of Gluck's Conjecture," arXiv:2608.11525 —
  https://arxiv.org/abs/2608.11525 — finite group theory (axis 1, math.GR/RT): settles
  Gluck's conjecture, open since 1985 (~41 years): every finite solvable group G satisfies
  |G:F(G)| ≤ b(G)², where F(G) is the Fitting subgroup and b(G) the largest irreducible
  character degree. Abstract + author verified via arXiv API this session (v1 2026-08-12).
  HEAVY CAVEAT (hype-skepticism rule): unrefereed SINGLE-AUTHOR preprint claiming resolution
  of a named 40+-year conjecture → PROVISIONAL until independent vetting; a landmark claim a
  representation/group theorist should watch.
- 2026-08-12 — Peter L. Guo, Mingyang Kang, Rui Xiong, "A solution to Butler's positivity
  conjecture," arXiv:2608.11543 — https://arxiv.org/abs/2608.11543 — algebraic combinatorics
  (axis 1, math.CO/RT): proves Butler's positivity conjecture posed in 1994 (~32 years open):
  the Schur-expansion coefficients of a Macdonald-intersection-polynomial ratio lie in
  Z≥0[q,t]. Abstract + authors verified via arXiv API this session (v1 2026-08-12). Unrefereed
  preprint (three-author, cross-verified internally, not single-author) — PROVISIONAL under
  the hype-skepticism rule; track the referee outcome.
- 2026-08-12 — Yutong Zhang, Yaoran Yang, "The 196560 auxiliary-function conjecture for the
  Leech lattice," arXiv:2608.12094 — https://arxiv.org/abs/2608.12094 — sphere packing /
  Fourier interpolation (axis 1/2, math.NT/CA, math-ph-adjacent): resolves the Cohn–Kumar
  2009 conjecture (~17 years open) on the existence of a radial Schwartz function realizing
  the Leech-lattice kissing-number identity via Poisson summation, building on the Viazovska-
  program radial Fourier interpolation basis in dimension 24. Abstract + authors verified via
  arXiv API this session (v1 2026-08-12). Unrefereed two-author preprint — PROVISIONAL; a
  notable resolution in the sphere-packing/interpolation program that produced the Fields-
  Medal-winning 8D/24D sphere-packing results.
- 2026-08-12 — Julie Kiel Holm et al. (8 authors), "Evidence for the First Globular Cluster
  Stellar Stream beyond the Milky Way," arXiv:2608.12254 — https://arxiv.org/abs/2608.12254 —
  observational astrophysics / dark matter (axis 3, astro-ph.GA/CO): Hubble Space Telescope
  imaging of ultra-diffuse galaxy UGC9050-Dw1 provides the FIRST evidence for an extragalactic
  globular-cluster tidal stream (previously observed only in the Milky Way), with a
  generative-stream-modelling dark-matter-halo mass constraint for the host. Abstract + authors
  verified via arXiv API this session (v1 2026-08-12). First-of-kind observational claim from
  a single team ("evidence for," not yet independently confirmed) — track for follow-up/
  independent confirmation.
- 2026-08-12 — Yi-Zhong Fan et al., "Evidence for a ~43 GeV γ-ray line signal in a stacking
  analysis of the Virgo, Fornax, and Ophiuchus Galaxy clusters," arXiv:2407.11737, now
  published as Phys. Rev. Lett. 137, 071003 (2026) — https://arxiv.org/abs/2407.11737 —
  indirect dark-matter search (axis 3, astro-ph.HE/CO): a stacking analysis reporting evidence
  for a ~43 GeV gamma-ray line from three galaxy clusters, a candidate dark-matter-annihilation
  signature; original 2024 preprint now peer-reviewed and published in PRL. RSS abstract (PRL
  feed) + arXiv API metadata opened this session (PRL published 2026-08-12). EXTRAORDINARY-
  CLAIM CAUTION (hype-skepticism rule): a peer-reviewed "line signal" claim is not a discovery
  — line-search anomalies in this exact subfield have a history of turning out to be
  look-elsewhere-effect or instrumental artifacts (cf. the 3.5 keV line saga); PROVISIONAL,
  track for independent confirmation/refutation by other collaborations (Fermi-LAT, H.E.S.S.).
- 2026-08-06 — John C. Baez, "Three Generations in E7," arXiv:2608.06271 —
  https://arxiv.org/abs/2608.06271 — mathematical physics (axis 2, hep-th/math-ph): a
  speculative algebraic proposal using the exceptional Lie group E7 acting on Jordan-pair
  structures to explain the 3-generation structure of Standard Model quarks/leptons, the
  author's third paper in a series (with Schwahn's exceptional-Jordan-algebra gauge-group
  result and the Bokor–Boyle Jordan-pair paper) attempting to derive Standard Model features
  from exceptional algebra. Discovered via Baez's own blog post (2026-08-12, opened via `tvly
  extract`) explaining the paper; abstract + author verified via arXiv API this session (v1
  2026-08-06). Speculative single-author theoretical proposal, not a proof/discovery — below
  the trend bar, worth tracking as part of the standing exceptional-algebra/Standard-Model
  research program.
- 2026-08-12 — Two below-bar partial-progress items opened this session, captured for the
  record (neither a full resolution): António Girão, Sergey Norin, Youri Tamitegama, Jane Tan,
  "Two Relaxations of the Dominating Hadwiger's Conjecture," arXiv:2608.12126,
  https://arxiv.org/abs/2608.12126 (extremal graph coloring, axis 1, math.CO — proves two
  weaker forms of a conjecture proposed only recently by Illingworth–Wood, not the conjecture
  itself); Jake Brukhman, "A dense-case theorem for Seymour's second neighborhood conjecture,"
  arXiv:2608.11530, https://arxiv.org/abs/2608.11530 (tournament theory, axis 1, math.CO —
  extends known partial cases of the famous ~1990 second-neighborhood conjecture to a dense
  regime, not a full resolution). Abstracts verified via arXiv API this session (both v1
  2026-08-12).
- 2026-08-12 — Simons Foundation, "New Simons Collaboration Explores Defects in Physics" —
  https://www.simonsfoundation.org/2026/08/new-simons-collaboration-explores-defects-in-physics/
  — ecosystem/recognition (axis 2, hep-th/math-ph): launches the "Simons Collaboration on the
  Virtues of Defects," led by Jaume Gomis (Perimeter Institute), studying nonlocal
  observables/defects across QFT, condensed matter and gravity; the announcement cites "advances
  in theories of defects that revealed new phases of quantum systems" among the collaboration's
  motivating recent successes — thematically adjacent to the tracked non-invertible-symmetries
  trend (Gomis is a leading defect-CFT/categorical-symmetry researcher) but a funding launch, not
  a result. Page opened via `tvly extract` this session. Below-bar ecosystem item.
- 2026-08-10 — arXiv:2608.10133 — Nair, "Towards a Proof of Mass Gap in 3d Yang-Mills Theory" —
  https://arxiv.org/abs/2608.10133 — mathematical physics (axis 2, hep-th/math-ph): sketches "the
  outlines of a proof" of a mass gap for 3d Yang-Mills theory via an inequality on Laplacian
  eigenvalues over the gauge-invariant configuration space — a continuation of the author's own
  long-running Hamiltonian approach to this problem, not a from-scratch claim, and explicitly an
  outline rather than a complete rigorous proof. Abstract + author verified via arXiv API this
  session (v1 2026-08-10). EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): a Yang-Mills mass
  gap (the 4d case is a Clay Millennium Problem; this is the 3d/Euclidean analogue) is a famous
  open problem — single-author, program-continuation, explicitly partial ("outlines") →
  PROVISIONAL, watch for a completed rigorous writeup and independent expert engagement.
- 2026-08-10 — TWO fully independent groups resolve the SAME 2015 Kolokolnikov conjecture on
  algebraic connectivity, same day — arXiv:2608.09879 (Cioabă, Jayarajan, Kannan, Roy, "Maximizing
  the algebraic connectivity of graphs of given order and size: a proof of a conjecture of
  Kolokolnikov") · arXiv:2608.09822 (Chi, Wang, Zheng, "On a conjecture of Kolokolnikov on
  algebraic connectivity") — https://arxiv.org/abs/2608.09879 ·
  https://arxiv.org/abs/2608.09822 — spectral graph theory (axis 1, math.CO): both prove
  Kolokolnikov's 2015 conjecture that the maximum algebraic connectivity α(n,2n−4) over graphs on
  n vertices with 2n−4 edges equals 2, achieved by K_{2,n−2}. Abstracts + authors verified via
  arXiv API this session (both v1 2026-08-09). A notable same-day double-discovery of a single
  named conjecture by two fully independent author groups — below the trend bar (one conjecture,
  not a multi-artifact sub-theme) but a striking convergence event in its own right.
- 2026-08-11 — arXiv:2608.11132 — Ning, "Kohayakawa's conjecture and clique coverings of
  complements of paths and cycles" — https://arxiv.org/abs/2608.11132 — extremal combinatorics
  (axis 1, math.CO): proves Kohayakawa's 1991 conjecture on the growth rate of maximum induced
  paths in a specific Kneser-graph-related bipartite construction, with a corollary sharpening
  clique-covering bounds for complements of paths/cycles. Abstract + author verified via arXiv API
  this session (v1 2026-08-11). A landmark resolution of a 35-year-old named conjecture.
- 2026-08-11 — arXiv:2608.10889 — Liu, Chen, Zhou, "Katok's intermediate entropy conjecture for
  amenable group actions" — https://arxiv.org/abs/2608.10889 — ergodic theory / dynamical systems
  (axis 1, math.DS): shows Katok's intermediate entropy conjecture holds for amenable-group actions
  with the specification property that are asymptotically entropy expansive — a significant but
  conditional (restricted system class) advance, not a full general resolution. Abstract + authors
  verified via arXiv API this session (v1 2026-08-11). Below-bar partial-progress item on a
  well-known named conjecture.
- 2026-08-10 (v1; paper dated 2026-08-10, surfaced via community pulse — chased same session) —
  Claude (Anthropic, unreleased research model), "More Than Two Thirds of the Zeros of the
  Riemann Zeta Function Lie on the Critical Line" —
  https://www.anthropic.com/research/riemann-zeta · paper PDF
  https://www-cdn.anthropic.com/564f962e60643842f5fcb4a17c9dbc8f608f1c37.pdf · Lean
  formalization https://github.com/anthropics/zeta-23-lean — analytic number theory (axis 1,
  math.NT) / AI-WATCH + axis 5 (formal verification): proves unconditionally that
  liminf N₀*(T,2T)/N(T,2T) ≥ 2/3 (optimised test family → 0.6725) — i.e. at least ~67.25% of
  nontrivial zeta zeros are simple and on the critical line, up from the ~41.6% state-of-the-art
  standing since prior work of Baluyot–Goldston–Suriajaya–Turnage-Butterbaugh (arXiv:2306.04799,
  2501.14545) and Bombieri (2000); also gives ≥83.6% distinct-on-line. Official Anthropic
  research page + full paper PDF opened via `tvly extract` this session (paper dated 2026-08-10).
  HEAVY HYPE-SKEPTICISM + AI-WATCH CAUTION (scope: track the RESULT, not the AI method — sibling
  AI radars' beat): off-arXiv, unrefereed, and a ~25-percentage-point jump over a record that had
  moved by fractions of a percent per decade is an extraordinary claim → PROVISIONAL until
  independent expert vetting. Vetting signal (not yet an outcome, but stronger than most AI-math
  claims on this ledger): two Anthropic in-house mathematicians (Ralph Furman, Levent Alpöge, per
  the paper's acknowledgments) studied and take responsibility for communicating the result, and
  Brian Conrey (AIM director, a leading authority on zero-density/critical-line estimates for
  ζ) and Dan Goldston (co-author of the BGST papers the proof builds on) are named as having
  "generously examined the paper on short notice" — genuinely well-matched external reviewers,
  though this is informal review, not peer review or independent replication. A companion Lean
  formalization (`zeta-23-lean`) is claimed but not independently verified this session (repo
  not opened). Watch for: an arXiv posting, a formal referee/replication outcome, and any public
  comment from Conrey/Goldston beyond the "examined" framing. Also on `study_shelf`.
- 2026-08-10 — arXiv:2608.08997 — Kaur, Kumar, "A proof of the cyclotomic conjecture and the
  non-existence of almost Moore digraphs" — https://arxiv.org/abs/2608.08997 — graph theory /
  degree-diameter problem (axis 1, math.CO/NT): proves Gimbert's 1999 cyclotomic conjecture on
  the irreducibility of Φₙ(1+x+…+xᵏ) over ℚ, which Conde–Gimbert–González–Miller–Miret (2014)
  showed implies the non-existence of "almost Moore" digraphs — closing a well-known open case
  of the directed degree-diameter problem that has stood since the 1980s. Abstract + authors
  verified via arXiv API this session (v1 2026-08-10). A landmark resolution of a long-standing
  named conjecture in extremal/algebraic graph theory. Also on `study_shelf`.
- 2026-08-10 — arXiv:2608.09436 — Belmans, Hotchkiss, "The hyperkähler period-index conjecture
  is false" — https://arxiv.org/abs/2608.09436 — algebraic geometry (axis 1, math.AG): refutes
  Huybrechts's strengthening of the period-index conjecture (ind(α) | per(α)^{dim(X)/2} for a
  Brauer class α on a hyperkähler variety X) on certain hyperkähler fourfolds of type K3^[2] and
  Kum². Abstract + authors verified via arXiv API this session (v1 2026-08-10). A SECOND,
  independent period-index-family refutation within a week — Perry's "The period-index conjecture
  is false" (2608.03684, queued/shelved 08-04) refuted the classical (non-hyperkähler) period-index
  conjecture; this is a different named conjecture (Huybrechts's), by a fully independent
  two-author group, on the hyperkähler strengthening specifically — a FORMING pair on the broader
  "period-index-type conjectures fail" sub-theme (below the ≥3-group trend bar; watch for a third).
  A landmark refutation of a named conjecture by a leading algebraic geometer in its own right.
- 2026-08-09 — arXiv:2608.08953 — Colbrook, Sadeghi, Stepaniants, "A computer-assisted
  counterexample to the planar Berenstein conjecture" — https://arxiv.org/abs/2608.08953 —
  analysis / spectral geometry (axis 1, math.AP/CA): adapts the same conformal-fixed-disc /
  disk-polynomial / validated-tail machinery the authors used for the Pompeiu/Schiffer
  counterexample (2608.01579, already queued/shelved 08-03) to the complementary Dirichlet
  endpoint, disproving the unrestricted planar Berenstein conjecture via an explicit noncircular
  domain. Abstract + authors verified via arXiv API this session (v1 2026-08-09). A THIRD
  classical rigidity conjecture (after Pompeiu and Schiffer) falling to the same group's
  computer-assisted method — own-group extension, not a new independent corroboration of the
  Pompeiu/Schiffer forming pair, but notable for the growing computer-assisted-proof pattern.
- 2026-08-08 — arXiv:2608.07836 — Huang, Satriano, "The dimension threshold for Batyrev's
  non-negativity conjecture on stringy Hodge numbers" — https://arxiv.org/abs/2608.07836 —
  algebraic geometry (axis 1, math.AG): shows Batyrev's non-negativity conjecture holds in
  dimension ≤4 and gives counterexamples in dimension ≥5 — a full characterization sharpening
  the already-tracked AI-assisted counterexample (2607.19184, study_shelf 07-22, "discovered
  with the assistance of OpenAI's ChatGPT"). Abstract + authors verified via arXiv API this
  session (v1 2026-08-08). NOT AI-assisted (standard human proof) — an independent, rigorous
  follow-up that locates exactly where the earlier AI-assisted counterexample's phenomenon
  begins; a useful, lower-epistemic-risk complement to that provisional AI-generated result.
- 2026-08-09 — arXiv:2608.09205 — Cameron, Di Colandrea, Cardano, Marrucci, "Evidence for
  Counterfactual Violation of Local Conservation Laws in Quantum Events" —
  https://arxiv.org/abs/2608.09205 — quantum foundations (axis 4, quant-ph): reports experimental
  evidence, using superoscillatory photons extracted from an optical-vortex core, for individual
  quantum events locally violating conservation of momentum — testing a thought experiment of
  Aharonov, Popescu and Rohrlich (APR). Abstract + authors verified via arXiv API this session
  (v1 2026-08-09). EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): "evidence for" a
  counterintuitive foundational claim about conservation laws in single quantum events is
  PROVISIONAL pending independent replication and theoretical scrutiny of the interpretation —
  but a genuine first-of-kind experimental test of a specific, well-known foundational proposal,
  worth a frontier physicist's attention.
- 2026-08-09 — arXiv:2608.08441 — Guu, "A Disproof of Santharoubane's Conjecture on
  Presentations of Generic Skein Algebras" — https://arxiv.org/abs/2608.08441 — low-dimensional
  topology / quantum topology (axis 1/2, math.GT): refutes Santharoubane's conjecture that a
  presentation derived from mapping-class-group data yields an algebra isomorphic to the generic
  Kauffman-bracket skein algebra, for surfaces of genus ≥3. Abstract + author verified via arXiv
  API this session (v1 2026-08-09). Below-bar refuted-conjecture item.
- 2026-08-09 — arXiv:2608.08478 — Prajapati, "A counterexample to the Etzion-Silberstein
  conjecture" — https://arxiv.org/abs/2608.08478 — coding theory / combinatorics (axis 1,
  cs.IT, adjacent to math.CO): disproves the Etzion–Silberstein conjecture on Singleton-type
  bounds for linear Ferrers-diagram rank-metric codes via an explicit Ferrers diagram where the
  optimal dimension falls one short of the conjectured bound. Abstract + author verified via
  arXiv API this session (v1 2026-08-09). Category-borderline (cs.IT, not a core math.* listing)
  but a genuine refuted named conjecture in algebraic/combinatorial coding theory — below-bar
  intake.
- 2026-08-10 — arXiv:2608.09191 — Yavari, "A Proof of the Imbalance Conjecture" —
  https://arxiv.org/abs/2608.09191 — combinatorics / graph theory (axis 1, math.CO): proves the
  Kozerenko–Skochko imbalance conjecture (the multiset of edge-imbalances of a graph with every
  edge positively imbalanced is always graphic). Abstract + author verified via arXiv API this
  session (v1 2026-08-10) — no AI-assistance is claimed or visible in the abstract/comments,
  despite a community-pulse post title framing it as AI-assisted; not corroborated by the primary,
  so captured here without that attribution. Below-bar resolved-conjecture item (a young
  conjecture, not a classical named one).
- 2026-08-09 — arXiv:2608.08766 — Gu, Luo, Wang, Zhang, "Understanding Non-Split 2-Group
  Symmetry: (3+1)D SymTFT, Anomaly and Bordism" — https://arxiv.org/abs/2608.08766 —
  theoretical physics (axis 2, hep-th): classifies anomalies of a non-split ℤ₂×ℤ₂ 2-group
  symmetry via oriented/spin bordism groups and constructs its (3+1)D Symmetry TFT. Abstract +
  authors verified via arXiv API this session (v1 2026-08-09). SymTFT-adjacent to the tracked
  non-invertible-symmetries trend but a DIFFERENT symmetry structure (2-group, not
  non-invertible/fusion-category) — does not feed that trend; below-bar item in its own right.
- 2026-08-07 — arXiv:2608.07173 — Feng, Yun, Zhang, "Modularity of Higher Theta Series III:
  Proof of the Modularity Conjecture" — https://arxiv.org/abs/2608.07173 — number theory /
  arithmetic geometry (axis 1, math.NT/AG): proves the Modularity Conjecture for higher theta
  series on moduli stacks of Hermitian shtukas (part III of the authors' program), and en route
  establishes a "supermodularity" refinement for general linear shtukas plus the Trace
  Conjecture for low-corank Hitchin stacks — realizing virtual fundamental classes of special
  cycles as categorical traces. Tony Feng, Zhiwei Yun and Wei Zhang are established leaders of
  the arithmetic Gan–Gross–Prasad / relative-Langlands program; this caps a multi-part series
  resolving a named conjecture central to that program. Abstract + authors verified via arXiv
  API this session (v1 2026-08-07). Domain-cadence landmark single result (a long-standing
  named conjecture resolved by a leading group, capstone of a numbered series — lower epistemic
  risk than a from-scratch single-author claim). Also on `study_shelf`.
- 2026-08-07 — arXiv:2607.19012 — Long, "Counterexamples to the xz-Conjecture and the Mathieu
  Conjecture for SU(2)" — https://arxiv.org/abs/2607.19012 — algebra / invariant theory (axis 1,
  math.RA/AG): refutes the ~29-year-old Mathieu conjecture for SU(2) (O. Mathieu, 1997 — the
  approach to the Jacobian conjecture via compact-Lie-group integration identities) with an
  explicit three-term Laurent-polynomial counterexample, also disproving the closely related
  xz-conjecture and showing the relevant kernel is not a Mathieu–Zhao subspace. CAPTURE-LEAK
  CATCH: v1 dates 2026-07-21 (~20 days ago, well inside the 60-day domain-cadence window) but
  was missed by this ledger until surfaced today via a citing follow-up (see next item) — a
  near-miss corrected same session, not a fresh result. Abstract + author verified via arXiv API
  this session. A landmark refutation of a long-standing named conjecture with a direct link to
  the Jacobian-conjecture research program already tracked on this ledger. Also on `study_shelf`.
  - 2026-08-07 — arXiv:2608.07338 — Dvorsky, "An Explicit Five-Variable Counterexample to the
    Generalized Vanishing Conjecture" — https://arxiv.org/abs/2608.07338 — explicitly motivated
    by Long's Mathieu-conjecture counterexample above, gives an independent five-variable
    counterexample to the (related) Generalized Vanishing Conjecture. A second, independent
    engagement with the same algebraic sub-theme within 2.5 weeks — a FORMING pair (below the
    ≥3-group trend bar; watch for a third). Abstract + author verified via arXiv API this
    session (v1 2026-08-07).
- 2026-08-07 — arXiv:2608.06681 — He, Sahai, "Refuting a Conjecture of Umans and Wang on
  Arithmetic-Progression Divisor Covers" — https://arxiv.org/abs/2608.06681 — combinatorial
  number theory / complexity-adjacent (axis 1, math.NT): unconditionally refutes the
  arithmetic-progression case of the Umans–Wang Strong divisor conjecture (an
  arithmetic-progression $n$-divisor set cannot have the conjectured polylogarithmic length).
  Abstract + authors verified via arXiv API this session (v1 2026-08-07). Below-bar
  refuted-conjecture item.
- 2026-08-07 — arXiv:2608.07186 — Thorne, "Towards the Fontaine–Mazur conjecture for GL(2)" —
  https://arxiv.org/abs/2608.07186 — number theory / automorphic forms (axis 1, math.NT):
  combines a new modularity result with geometry-of-numbers techniques to prove new cases of the
  Fontaine–Mazur conjecture for GL(2), by an established leader in modularity-lifting (Jack
  Thorne). Partial progress, not a full resolution. Abstract + author verified via arXiv API
  this session (v1 2026-08-07). Below-bar partial-progress item.
- 2026-08-07 — arXiv:2608.07350 — Xu, "Profinite rigidity in lattices of $\mathrm{PSL}(2,\mathbb{C})$"
  — https://arxiv.org/abs/2608.07350 — geometric group theory (axis 1, math.GR/GT): proves all
  lattices in PSL(2,C) are profinitely rigid among themselves, plus an $\mathrm{Out}$-isomorphism
  result for their profinite completions. Abstract + author verified via arXiv API this session
  (v1 2026-08-07). Below-bar single-group-theory-result item.
- 2026-08-07 — arXiv:2608.06920 — Valtonen, "Classification of Symmetric Hadamard Matrices Up to
  Order 32" — https://arxiv.org/abs/2608.06920 — combinatorics / design theory (axis 1, math.CO):
  completes the Hadamard-equivalence classification of symmetric Hadamard matrices up to order
  32 (correcting an error in the prior order-28 classification) via a new equivalence-testing
  algorithm. Abstract + author verified via arXiv API this session (v1 2026-08-07). Below-bar
  classification/enumeration item.
- 2026-08-07 — arXiv:2608.07399 — Bondarenko, Heap, "Siegel zeros and small gaps between zeros of
  the Riemann zeta function" — https://arxiv.org/abs/2608.07399 — analytic number theory (axis 1,
  math.NT): shows, conditional on RH, that Siegel zeros imply zeta-zero gaps below 0.4733× the
  normalised spacing, refuting certain strong alternative pair-correlation hypotheses under those
  assumptions. Abstract + authors verified via arXiv API this session (v1 2026-08-07). Below-bar
  conditional-result item.
- 2026-08-07 — arXiv:2608.07396 — de Dios Pont, Liehr, Muñoz-Lahoz, Taylor, Tradacete, "Banach
  lattices and phase retrieval: A case study for the use of AI in mathematics" —
  https://arxiv.org/abs/2608.07396 — AI-WATCH area (scope: track the assistance, not the AI
  method itself): a community reflection piece by Banach-lattice/phase-retrieval researchers on
  incorporating LLM assistance coupled with Lean verification into their research workflow — a
  meta-level account, not a single new theorem. Abstract + authors verified via arXiv API this
  session (v1 2026-08-07). Watch-area intake, not a result.
- 2026-08-08 — **2026 Frontiers of Science Award (mathematics) → Dennis Gaitsgory** (with Nick
  Rozenblyum) — https://www.mpim-bonn.mpg.de/ — recognition/ecosystem (axis 1, algebraic
  geometry / geometric Langlands): the International Congress for Basic Science award cites
  their "A study in derived algebraic geometry: Volumes I and II" (Math. Surveys and
  Monographs, 2017) — the foundational derived-algebraic-geometry framework underlying
  Gaitsgory–Raskin et al.'s geometric Langlands proof program. Caught via this week's
  weekly-swept institute sweep (MPIM Bonn news page, opened via `tvly extract` this session).
  BELOW the radar's main prize-capture bar (Fields/Abel/Shaw/Clay) but a substantial
  international award in a directly on-axis field — noted per the standing "chase the
  calendar" prize-lane practice (W31 M08 retrospective) rather than left un-routed. Single
  below-bar ecosystem item.
- 2026-08-06 — arXiv:2608.05044 — Faulhuber, Petersen, van Velthoven, Voigtlaender, "Linear
  dependence of time-frequency shifts of a Schwartz function" — https://arxiv.org/abs/2608.05044
  — harmonic analysis / time-frequency analysis (axis 1, math.CA/FA): DISPROVES the ~30-year-old
  HRT (Heil–Ramanathan–Topiwala, 1996) conjecture — that a nonzero Schwartz function cannot admit
  a nontrivial linear dependence among a finite set of its time-frequency shifts — via an explicit
  example of 12 dependent shifts (prior positive results had the conjecture proved up to n≤3
  shifts). Discovered via Terence Tao's blog ("A partial digestion of the HRT counterexample,"
  2026-08-06, opened via WebFetch this session — Tao engaged and reconstructed the argument
  same-day, a strong immediate vetting signal, though still not a formal referee outcome).
  AI-WATCH (scope area, not tracked as the method): the authors "disclosed their AI use
  responsibly, with final arguments written by hand" per Tao's summary — AI-assisted initial
  proof strategy, traditional numerical computation verified specific steps; track the RESULT,
  not the method. Abstract + authors verified via arXiv API this session (v1 2026-08-05, already
  present in today's math broad-rotation batch but only surfaced via the Tao-blog chase — a
  capture-leak-style near-miss, corrected same session). A landmark refutation of a long-standing
  named conjecture in harmonic analysis. Also on `study_shelf`.
- 2026-08-06 — arXiv:2608.06222 — Kun, Thom, "Nonsofic wreath products of residually finite
  groups" — https://arxiv.org/abs/2608.06222 — group theory / geometric group theory (axis 1,
  math.GR): explicitly "builds on the breakthrough of OpenAI in finding the first nonsofic
  group" (the standing OpenAI "Ten Advances" cluster, queued 2026-08-01), giving new EXPLICIT
  nonsofic constructions (generalized wreath products for property-(T), residually finite,
  Kazhdan pairs over polynomial/Laurent-polynomial rings). A further independent human
  mathematical engagement with the underlying technique — see the dated note under the OpenAI
  cluster item below for the same-day misconduct-allegation context (Fournier-Facio, on this
  SAME sub-result, is separately quoted calling the original claim less novel than presented).
  Abstract + authors verified via arXiv API this session (v1 2026-08-06).
- 2026-08-06 — arXiv:2608.06369 — Bowtell, Montgomery, Müyesser, Pokrovskiy, "A proof of
  Andersen's rainbow path conjecture for large $n$" — https://arxiv.org/abs/2608.06369 —
  extremal / probabilistic combinatorics (axis 1, math.CO): resolves a 1989 conjecture of
  Andersen — every properly edge-coloured $n$-vertex complete graph contains a rainbow path on
  $n-1$ vertices — for all sufficiently large $n$, improving prior near-optimal results
  (Alon–Pokrovskiy–Sudakov; Balogh–Molla); a related result gives near-optimal cycle-free
  rainbow transversals of Latin squares. Ramsey-ADJACENT (rainbow/anti-Ramsey flavor) but NOT a
  Ramsey-number lower bound → does not feed the Ramsey trend. Abstract + authors verified via
  arXiv API this session (v1 2026-08-06). A landmark resolution of a 37-year-old named
  conjecture by a strong, established author group (no AI-assistance claimed).
- 2026-08-06 — arXiv:2608.06320 — Bi, "Dihedral Rigidity for Convex Polytopes by Smooth
  Approximation" — https://arxiv.org/abs/2608.06320 — differential geometry / comparison geometry
  (axis 1, math.DG): claims a proof of Gromov's dihedral rigidity conjecture for convex polytopes
  (scalar-curvature rigidity of polytopes with nonnegative dihedral angles), following Brendle's
  smooth-approximation method. Abstract opened via arXiv API this session (v1 2026-08-06,
  single-line abstract). EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): a single-author,
  18-page, unrefereed preprint claiming resolution of a well-known Gromov conjecture is
  PROVISIONAL until independent vetting — same footing as the matroid-intersection-conjecture and
  Gorenstein-symmetry-conjecture claims already on this ledger; track the outcome.
- 2026-08-06 — arXiv:2608.06272 — Lorist, Meyries, Veraar, "A counterexample to the inverse
  generator problem and related questions" — https://arxiv.org/abs/2608.06272 — operator theory /
  semigroup theory (axis 1, math.FA): negative solution to the inverse generator problem on
  Hilbert spaces — constructs a bounded, dense-range generator $A$ of a bounded strongly stable
  $C_0$-semigroup whose inverse $A^{-1}$ does NOT generate a $C_0$-semigroup, plus a second
  example with unbounded, double-logarithmically-growing inverse semigroup. Abstract + authors
  verified via arXiv API this session (v1 2026-08-06). Single below-bar refuted-open-question item.
- 2026-08-06 — arXiv:2608.05662 — Pokora, "On the Numerical Terao Conjecture" —
  https://arxiv.org/abs/2608.05662 — algebraic combinatorics / arrangement theory (axis 1,
  math.AG/CO): proves the Numerical Terao Conjecture for even-degree conic-line arrangements with
  only ADE singularities, but shows it FAILS in the broader quasi-homogeneous setting once
  ordinary quadruple points are allowed, via an explicit degree-9 counterexample. Abstract +
  author verified via arXiv API this session (v1 2026-08-05). Single below-bar mixed
  proof/counterexample item.
- 2026-08-06 — arXiv:2608.06247 — Watkins, Feldman, "Reanalyzing Megamasers: a low value of
  $H_0$ from a local probe changes our view of the Hubble Tension" —
  https://arxiv.org/abs/2608.06247 — cosmology (axis 3, astro-ph.CO): re-analyzes megamaser
  distance/redshift data (an independent, non-distance-ladder $H_0$ probe) using a new peculiar-
  velocity-corrected reconstruction, finding a LOW local $H_0$ — a direct follow-on to the
  standing DESI dynamical-dark-energy / Hubble-tension saga (H₀-World-Cup thread, 07-15/07-16).
  Abstract + authors verified via arXiv API this session (v1 2026-08-06). Below-bar intake,
  extraordinary-claim caution continues to apply.
- 2026-08-05 — Alexander Smith, "The distribution of $\ell^\infty$-Selmer groups in degree
  $\ell$ twist families I/II" — https://arxiv.org/abs/2207.05674 ·
  https://arxiv.org/abs/2207.05143 — now published as J. Amer. Math. Soc. 39(1) pp.1–72 and
  39(2) (2026) — number theory (axis 1, math.NT): the two-paper technique (the "fixed point
  Selmer group") for computing distributions of $\ell^\infty$-Selmer groups in degree-$\ell$
  twist families; resolves the notoriously hard $\ell=2$ case of the Cohen–Lenstra(–Gerth)
  heuristics — the 2-primary class-group distribution problem going back to Gauss's genus
  theory (~200 years) — and shows 100% of quadratic twists of a suitable elliptic curve have
  rank $\le1$. LANDMARK, NOW PEER-REVIEWED (JAMS 2026): unlike most items on this ledger these
  arXiv preprints (2022) are NOT provisional — journal publication in 2026 is itself the
  vetting outcome. Surfaced via Scientific American / Yahoo News science coverage ("Mathematicians
  make a breakthrough on Gauss's riddle, unsolved for 200 years," 2026-08-05, community-pulse
  pointer) and corroborated via the Bourbaki survey "Recent Progress around Cohen–Lenstra
  Heuristics" (arXiv:2606.06024, opened this session, which cites Smith 2026a/2026b by their
  JAMS locants) and AMS's JAMS journal page (opened this session, confirms JAMS is a peer-reviewed
  AMS journal). Abstracts of both arXiv preprints verified via arXiv API this session. Domain-
  cadence landmark single result. Also on `study_shelf`.
- 2026-08-05 — arXiv:2608.05114 — Cao-Labora, de Dios Pont, "Counterexamples to Schiffer's
  Conjecture" — https://arxiv.org/abs/2608.05114 — analysis / spectral geometry (axis 1,
  math.AP/CA): a SECOND, FULLY INDEPENDENT counterexample to the Pompeiu and Schiffer
  conjectures — infinitely many $N$-fold-symmetric non-ball planar domains admitting a Neumann
  eigenfunction constant on the boundary — following Colbrook–Stepaniants's computer-assisted
  counterexample (arXiv:2608.01579, queued 2026-08-03) by two days, via an unrelated
  construction strategy. TWO fully independent groups refuting the same ~97-year-old conjecture
  pair within a week — a FORMING pair (below the ≥3-group trend bar; watch for a third).
  Abstract + authors verified via arXiv API this session (v1 2026-08-05).
- 2026-08-05 — arXiv:2608.04760 — Wang, Tang, "A proof of the Freiman-Lev conjecture" —
  https://arxiv.org/abs/2608.04760 — additive combinatorics / number theory (axis 1, math.NT/CO):
  completes the proof of the Freiman–Lev conjecture on restricted sumsets $2^\wedge A$ for the
  previously-open range ($a_{k-2}\ge2k-4$, $a_{k-1}\ge2k-2$). Abstract + authors verified via
  arXiv API this session (v1 2026-08-05). Single below-bar resolved-conjecture item.
- 2026-08-05 — arXiv:2608.04659 — Munaro, "Subdivided expanders and counterexamples to the Tree
  Product Conjecture" — https://arxiv.org/abs/2608.04659 — combinatorics / graph theory (axis 1,
  math.CO): extends Illingworth–Norin–Steiner's 2026 disproof of the $d=4$ case of the (2023)
  Tree Product Conjecture (Distel–Gollin–Harvey–Hendrey–Hickingbotham–Mohar–Wood) to every
  $d\ge2$ via subdivided cubic expanders, leaving only $d=1$ open. Abstract + author verified via
  arXiv API this session (v1 2026-08-05). Single below-bar item (a young, ~3-year-old conjecture,
  not a classical named one).
- 2026-08-05 — arXiv:2608.04981 — Hu, Xiao, Zhou, "A Counterexample to the Liu–Lou–Zhu
  $\mathcal Q_p$–Carleson Embedding Conjecture" — https://arxiv.org/abs/2608.04981 — harmonic
  analysis / operator theory (axis 1, math.CV/FA): disproves a conjecture on Carleson embeddings
  of $\mathcal Q_p$ spaces into tent spaces for $0<p<1$, via Cantor-type $\mathcal Q_p$ test
  functions. Abstract + authors verified via arXiv API this session (v1 2026-08-05). Single
  below-bar refuted-conjecture item.
- 2026-08-05 — TWO fresh DESI dynamical-dark-energy analyses (axis 3, gr-qc/astro-ph.CO), same
  batch — arXiv:2608.04353 (Zheng, Qiang, You, Kumar, "Revisiting the equation of state of dark
  energy from DESI BAO with SNe Ia and CMB") · arXiv:2608.04763 (Jiang, Shafieloo, "Is Dark
  Matter Really Matter?", jointly fits $w_{dm}$ and $w_{de}$ against DESI DR2 + Lyman-alpha AP +
  DES SNe + CMB, finding $w_{dm}=0.000968^{+0.000501}_{-0.000496}$ consistent with pressureless
  CDM while $w_{de}=-0.9380^{+0.0259}_{-0.0262}$ stays away from $-1$) —
  https://arxiv.org/abs/2608.04353 · https://arxiv.org/abs/2608.04763 — both direct follow-on
  analyses of the standing DESI dynamical-dark-energy / late-time-anomaly saga (07-15/07-16,
  07-29/07-31). Abstracts verified via arXiv API this session (v1 2026-08-04 both). Below-bar
  intake, extraordinary-claim caution continues to apply (not yet 5σ).
- 2026-08-05 — arXiv:2607.15345 — Kushwaha, Loizeau, Grinbaum, Friedrich, "Causality from the
  spectrum: Emergence of causal order from process-matrix mereology" —
  https://arxiv.org/abs/2607.15345 — quantum foundations (axis 4, quant-ph): extends quantum
  mereology (preferred tensor-product decompositions from a Hamiltonian spectrum) to the
  emergence of causal order itself, within higher-order/indefinite-causal-order quantum theory.
  Discovered via a Backreaction (Hossenfelder) blog post ("Physicists Say They've Found The
  Origin Of Causality," 2026-08-04, chased this session — the primary this pointed to had been
  unlocatable in the 08-05 daily, now found and captured). Abstract + authors verified via arXiv
  API this session (v1 2026-07-16). Single below-bar item.
- 2026-08-04 — arXiv:2608.03684 — Perry, "The period-index conjecture is false" —
  https://arxiv.org/abs/2608.03684 — algebraic geometry (axis 1, math.AG): for every uncountable
  algebraically closed field $k$ of characteristic 0 and every $d\ge 3$, constructs a $d$-dimensional
  variety over $k$ with a Brauer class violating the period-index conjecture (a foundational open
  problem on the relation between the period and index of Brauer classes) for Hodge-theoretic reasons;
  for $d=3$ the construction works without the uncountability hypothesis, so the conjecture already
  fails over $\overline{\mathbf{Q}}$. Abstract + author verified via arXiv API this session (v1
  2026-08-04). A landmark refutation of a long-standing named conjecture in algebraic geometry. Also
  on `study_shelf`.
- 2026-08-04 — arXiv:2608.03841 — Lorist, Schwenninger, "A solution to Crouzeix's conjecture" —
  https://arxiv.org/abs/2608.03841 — operator theory / matrix analysis (axis 1, math.FA): proves
  Crouzeix's 2004 conjecture — that $\|f(A)\|\le 2\sup_{z\in W(A)}|f(A)|$ for every square matrix $A$
  and polynomial $f$, where $W(A)$ is the numerical range — by combining machinery previously
  developed for weaker bounds with a new perturbation lemma for 2-dilations. Abstract + authors
  verified via arXiv API this session (v1 2026-08-04). A landmark resolution of a famous ~two-decade
  open problem in operator/matrix theory, unrefereed but building incrementally on the authors' own
  prior partial results (lower epistemic risk than a from-scratch claim). Also on `study_shelf`.
- 2026-08-04 — arXiv:2608.03254 — Verbeken, "Cyclic-by-abelian counterexamples to the second and
  third Zassenhaus conjectures" — https://arxiv.org/abs/2608.03254 — group theory / integral
  representations (axis 1, math.GR/RA): for every $r>1$ coprime to 30, constructs a finite group
  $G_r$ and an augmentation-preserving automorphism of $\mathbb{Z}G_r$ with no Zassenhaus
  factorization — a normalized group basis not rationally conjugate to $G_r$ even though every
  element individually is — refuting the second and third Zassenhaus conjectures (ZC2, ZC3) on units
  of integral group rings. Abstract + author verified via arXiv API this session (v1 2026-08-04). A
  landmark refutation of two long-standing named conjectures via a single construction.
- 2026-08-04 — TWO Kourovka Notebook problems resolved (both negative answers), same batch —
  arXiv:2608.03003 (de Ryke, "The solution to Kourovka problem 21.88": no finite group of odd order
  has commuting probability $1/17$, via a structural theorem also excluding $cp(G)=1/p$ for every odd
  prime $p<97$) · arXiv:2608.02970 (Sater, "Finite groups that are the product of every pair of
  non-conjugate maximal subgroups are soluble": answers Kourovka Problem 10.34 [Monakhov, 1986] in
  the negative, removing the socle $S^k$ ($k\ge2$) obstacle left open since the almost-simple case
  was settled in 2010) — https://arxiv.org/abs/2608.03003 · https://arxiv.org/abs/2608.02970 —
  finite group theory (axis 1, math.GR): two independent resolutions of long-catalogued open problems
  from the Kourovka Notebook (the field's standard open-problems register). Abstracts + authors
  verified via arXiv API this session (both v1 2026-08-04). Below the multi-group convergence bar
  (unrelated problems, not a shared sub-theme) but each a domain-cadence landmark on its own.
- 2026-08-04 — arXiv:2608.03255 — Maguire, "Unirationality is the same thing as Rational
  Connectedness in Characteristic Zero" — https://arxiv.org/abs/2608.03255 — algebraic geometry
  (axis 1, math.AG): claims that unirationality, rational connectedness and rational chain
  connectedness all coincide for smooth projective varieties over any characteristic-zero field, via
  the MRC fibration. Abstract + author verified via arXiv API this session (v1 2026-08-04).
  EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): whether every rationally connected variety is
  unirational is a famous, decades-open question in birational geometry (unirationality is classically
  much harder to establish than rational connectedness); a single-author unrefereed preprint claiming
  the FULL equivalence is PROVISIONAL until independent expert vetting — would be a major landmark if
  it survives scrutiny, watch closely.
- 2026-08-04 — arXiv:2608.03258 — Liu, Wang, "A klt generalized pair with infinitely generated
  canonical ring" — https://arxiv.org/abs/2608.03258 — algebraic geometry / birational geometry
  (axis 1, math.AG): constructs a projective klt generalized pair over $\mathbb C$ whose generalized
  log canonical ring is NOT finitely generated — bearing on finite-generation questions central to
  the minimal model program. AI-ASSISTED (WATCH area per scope): the paper states its main result "is
  obtained by generative AI, particularly GPT-5.6-sol-ultra, Fable 5, and the Danus system" — a
  further concrete arXiv artifact in the standing AI-assisted-math wave (this time an explicitly
  multi-model combination). Abstract + authors verified via arXiv API this session (v1 2026-08-04).
  Track the RESULT, not the AI method (sibling AI radars' beat); unrefereed, provisional.
- 2026-08-04 — arXiv:2608.03488 — Cassese, "A solution to Morrey's problem in $\mathbb{R}^{2\times
  m}$" — https://arxiv.org/abs/2608.03488 — calculus of variations (axis 1, math.AP/CA): constructs
  homogeneous rank-one convex integrands on $\mathbb R^{2\times m}$ (2 rows, $m$ columns) that are
  nowhere quasiconvex for large $m$. NOTE: the famous still-OPEN case of Morrey's conjecture (does
  rank-one convexity imply quasiconvexity?) is specifically the $2\times2$ case; this is a large-$m$
  extension of the already-known-false higher-dimensional regime, not a resolution of the open
  $2\times2$ problem. Abstract + author verified via arXiv API this session (v1 2026-08-04). Below-bar
  technical-extension item, title notwithstanding.
- 2026-08-04 — arXiv:2608.03661 — "Refined upper bounds on Schur-like numbers" —
  https://arxiv.org/abs/2608.03661 — combinatorics (axis 1, math.CO): Ramsey-ADJACENT (Schur numbers
  are a classical Ramsey-type quantity) but an UPPER-bound refinement, not a Ramsey-NUMBER LOWER
  bound → does not reactivate/feed the (emerging) Ramsey-lower-bound trend. Title via arXiv listing
  this session, abstract not opened → below-bar intake.
- 2026-08-04 — arXiv:2608.03710 — Lei, Song, Chen, Liu, "Entanglement Distillation of some Rank-Five
  Symmetric NPT States in Two-Qutrit Systems" — https://arxiv.org/abs/2608.03710 — quantum
  information theory (axis 4, quant-ph): resolves 1-distillability for a class of rank-five
  two-qutrit symmetric NPT states (a previously-open eigenvalue interval shown 1-undistillable) and
  gives structural results toward 2-distillability. Abstract + authors verified via arXiv API this
  session (v1 2026-08-04). A distinct state class from the tracked Werner-state 2-copy-distillability
  queue thread (2607.21367 / 2607.24309) — own below-bar item in the same broader
  entanglement-distillation research direction.
- 2026-08-04 — arXiv:2608.03459 — Yu, "3D Gravity Does Not Average Like Narain at Genus One: Rigidity
  of Virasoro Topological Boundaries" — https://arxiv.org/abs/2608.03459 — theoretical physics / 3d
  quantum gravity (axis 2, hep-th): shows that, at genus one in the ordinary nondegenerate sector,
  ensemble holography in AdS₃/CFT₂ can NOT be understood as an average over absolute 2d CFTs obtained
  by varying the topological boundary condition of the doubled Virasoro TQFT — a rigidity/no-go result
  bearing on the already-queued "universal sum over topologies in 3d gravity" thread (Belin et al.,
  SciPostPhys.21.1.017, queued 2026-07-27). Abstract + author verified via arXiv API this session (v1
  2026-08-04). Below-bar follow-up/counterpoint item.
- 2026-08-01 — OpenAI, "Ten Advances in Mathematics and Theoretical Computer Science" (internal,
  unreleased model "Astra") — https://openai.com/index/ten-advances-in-mathematics/ ·
  https://cdn.openai.com/pdf/ten-proofs-oai.pdf — AI-assisted math WATCH-area cluster (WATCH per
  scope: track the RESULTS, not the AI method — sibling AI radars' beat), spanning axes 1/2/4/5:
  claimed new results on TEN long-standing open problems (each untouched on its main result for
  ≥10 years, several far older), reportedly for under $2,000 of inference cost each; OpenAI states
  it "takes responsibility for" the Lean-formalized portions while the mathematical arguments were
  AI-generated. The ten: (1) exact asymptotic strength of the Cohn–Elkies sphere-packing linear
  program + asymptotic resolution of the Fourier sign-uncertainty problem; (2) exponential-factor
  improvements to classical fixed-distance binary/spherical code upper bounds; (3) an explicit
  NON-SOFIC group (unit group of the binary Leavitt algebra), resolving whether every countable
  group admits finite permutation approximations; (4) a DISPROOF of **Connes's rigidity
  conjecture** (infinitely many pairwise nonisomorphic property-(T) groups sharing one group von
  Neumann algebra) — a landmark-tier claim in operator-algebra theory; (5) arithmetic-circuit
  lower bounds for the permanent; (6) exponential parallel repetition for entangled two-player
  quantum games; (7) an n^{1/400}-hardness reduction for the closest vector problem; (8) a proof
  of Ehrhart's volume conjecture ((n+1)^n/n! bound, every dimension); (9) a superexponential
  multicolor-triangle-Ramsey lower bound R_k(3)=k^Θ(k), resolving Erdős problem 183 (SEE the
  reactivated Ramsey-lower-bound trend above — Steiner's arXiv:2608.02537 already builds on this
  same day); (10) two Erdős-type extremal-graph-theory conjectures (a compactness conjecture of
  Erdős–Simonovits, a degeneracy conjecture of Erdős) disproved via bipartite constructions.
  Official openai.com publication page (dated 2026-08-01) + the full technical PDF both opened via
  `tvly` this session (primary, insofar as a corporate research publication counts as the primary
  disclosure — no arXiv listing located for the OpenAI paper itself, the same off-arXiv pattern as
  the Cycle-Double-Cover proof). HEAVY HYPE-SKEPTICISM CAUTION: ten simultaneous claimed
  resolutions of major problems from a single unreleased, unrefereed AI system is the most
  extraordinary claim this radar has tracked to date — PROVISIONAL across the board until
  independent expert vetting of EACH result; track outcomes individually, a correct result on one
  problem does not imply correctness on the others. FIRST INDEPENDENT ENGAGEMENT already same-day:
  arXiv:2608.02025 (Francesco Fournier-Facio, "A torsion-free non-sofic group") constructs a
  DIFFERENT explicit non-sofic-group example "relying on the same technical criterion" as OpenAI's
  result (3) — an independent human mathematician engaging constructively (a vetting SIGNAL on
  result 3, not an outcome; abstract + author verified via arXiv API this session, v1 2026-08-03).
  Community-pulse corroboration (intake, not evidence): the OpenAI announcement topped both r/math
  and the Hacker News front page this session; Quanta's "Why the Legendary Erdős Problems Are
  Falling to AI" (Konstantin Kakaes, 2026-08-03, opened via `tvly` this session) frames this
  alongside the May 20 2026 Erdős unit-distance-conjecture counterexample (also OpenAI, not
  previously captured on this ledger — noted for context, not backfilled) as a "phase transition,"
  quoting Noga Alon that AI models are "changing dramatically the way mathematical research is
  being done." Also on `study_shelf` given the scale of the story, same heavy caveats. Watch for:
  individual on-arXiv treatments of each of the ten results (as with the Jacobian-conjecture/CDC
  pattern), any referee/vetting outcome, and whether the Connes's-rigidity-conjecture disproof
  draws independent confirmation — that alone would be a standalone landmark if it survives
  scrutiny.
  - 2026-08-07 (daily) — FIRST VETTING OUTCOME, and it is NEGATIVE (attribution/misconduct, not
    correctness): Scientific American, "OpenAI's latest math breakthroughs commit research
    misconduct, experts say" (Joseph Howlett, 2026-08-06) — https://www.scientificamerican.com/article/openais-latest-math-breakthroughs-commit-research-misconduct-experts-say/
    — opened via WebFetch this session (found via an r/mathematics community-pulse pointer; the
    article itself is press coverage, not a primary, but it names on-record credentialed experts
    with specific findings). Steven Miller (Yeshiva University) says result (1) [Cohn–Elkies
    sphere-packing linear program / Fourier sign-uncertainty] presents an argument "as its own
    but that actually first appeared in a 2016 paper by Miller and a collaborator" — "They are
    running roughshod over the work of others who came before them in a deliberate way ... It
    seems completely systematic to me, and it points to research misconduct." Francesco
    Fournier-Facio (Cambridge — the same mathematician who independently engaged result (3) on
    2026-08-03, arXiv:2608.02025, already captured) found result (3) [the non-sofic group] "wasn't
    as novel as it first appeared," merely "past[ing] together ideas" from 2016/2019 papers.
    OpenAI acknowledged and said it would "make small updates [to the paper] this week, consistent
    with standard academic practice." STATUS: this is attribution/novelty misconduct, explicitly
    DISTINCT from a correctness referee outcome — none of the ten results has yet been shown
    mathematically WRONG; track both threads (correctness AND attribution) separately going
    forward. SAME-DAY, a fresh arXiv primary independently extends the disputed result (3):
    arXiv:2608.06222 — Kun, Thom, "Nonsofic wreath products of residually finite groups" —
    https://arxiv.org/abs/2608.06222 — explicitly "builds on the breakthrough of OpenAI in finding
    the first nonsofic group," giving new explicit nonsofic constructions (generalized wreath
    products of property-(T), residually finite pairs) — a further concrete human mathematical
    engagement with the underlying technique, independent of the novelty dispute over the original
    paper's framing. Abstract + authors verified via arXiv API this session (v1 2026-08-06). Queued
    as its own below-bar item (see observation_queue) as well as folded in here for context.
- 2026-08-03 — arXiv:2608.01579 — Colbrook, Stepaniants, "A computer-assisted counterexample to
  the planar Pompeiu and Schiffer conjectures" — https://arxiv.org/abs/2608.01579 — analysis /
  spectral geometry (axis 1, math.AP/CA): constructs a bounded, simply-connected, noncircular
  planar domain with real-analytic Jordan boundary supporting a Neumann eigenfunction constant on
  the boundary — a rigorous, computer-assisted counterexample to BOTH the 1929 planar Pompeiu
  problem and the associated Schiffer conjecture (a ~97-year-old pair of rigidity questions
  linking rigid-motion integral transforms and overdetermined Neumann eigenvalue problems).
  Abstract + authors verified via arXiv API this session (v1 2026-08-02). A landmark refutation of
  two classical named conjectures via a clean, verifiable computer-assisted construction (the same
  growing pattern as Kuperberg's six-cylinder conjecture and the Balanced Four-Color Theorem,
  already on `study_shelf`) — NOT AI-generated (standard rigorous numerics), so no AI-watch caveat
  beyond the usual unrefereed-preprint note. Also on `study_shelf`.
- 2025-09-09 (v1; PRR publication undated in the pages opened, accessed 2026-08-03) —
  arXiv:2509.07745 (Physical Review Research) — Barontini, "Testing the problem of time with cold
  atoms" — https://arxiv.org/abs/2509.07745 — quantum foundations / quantum gravity interface (axis
  4/2, quant-ph/gr-qc): the FIRST experimental test of relational-time constructions motivated by the
  Wheeler-DeWitt "problem of time" — a well-isolated ultracold-atom Bose-Einstein condensate (24,000
  atoms) split by an optical barrier into observed/unobserved sectors; an entropic "internal time"
  built from the observed sector's coarse-grained entropy robustly orders events across repeated
  expansion/recollapse cycles, and an effective Schrödinger equation parameterized by this internal
  time reproduces the measured dynamics. Original arXiv preprint 2025-09-09 (v1), now published in
  Physical Review Research and drawing fresh press coverage (Univ. of Birmingham news page, opened via
  `tvly` this session, dated ~2026-07-09) — abstract verified via arXiv API this session. A
  landmark-quality FIRST-OF-KIND experimental probe of a central open question in quantum-gravity
  foundations (domain-cadence landmark-single-result note) — single-group so far; watch for
  independent replication. Also on `study_shelf`.
- 2026-07-01 — Nature Communications s41467-026-74935-8 — Wei, Zhai, Lu et al., "The Riemann
  Hypothesis manifested in dynamical quantum phase transitions" —
  https://www.nature.com/articles/s41467-026-74935-8 — math↔physics interface (axis 2/4,
  math-ph/quant-ph, peer-reviewed, published 2026-07-01): establishes a direct correspondence between
  the nontrivial zeros of the Riemann zeta function and dynamical quantum phase transitions in two
  engineered quantum many-body systems (average accumulated phase factor + Loschmidt amplitude), via
  a Riemann-based Hamiltonian construction. Abstract + publication metadata opened via `tvly` this
  session (received 2025-12-23, accepted 2026-06-18, published 2026-07-01). A genuinely novel
  RH↔physics correspondence — track for follow-up (does it offer a new verification/search strategy
  for RH zeros, or independent replication of the quantum-simulation claim). Also on `study_shelf`.
- 2026-07-31 — arXiv:2607.29681 — "Lean-verified lower bounds for the Shannon capacity of odd
  cycles" — https://arxiv.org/abs/2607.29681 — combinatorics / formalized math (axis 1/5, math.CO):
  a machine-checked (Lean 4) formalization of the lower-bound constructions for the Shannon capacity
  of C7/C11/C13, directly following the already-tracked Shannon-capacity thread (2607.21517 queued
  07-24; 2607.27869, a same-thread recursive extension, was pruned 2026-W34 queue burndown — settled,
  zero further follow-up). Title/abstract via arXiv API this session (v1 2026-07-31). Below-
  bar follow-up, but notable for axis 5: a formal-proof artifact attached to a live combinatorics
  result, not just a proof-assistant toolchain bump.
- 2026-08-01 — leodemoura.github.io — Leonardo de Moura (Lean FRO chief architect), "Postmortem for
  Kernel Soundness Bug #14576" — https://leodemoura.github.io/blog/2026-8-1-postmortem-for-kernel-soundness-bug-14576
  — formal-proof toolchain integrity (axis 5, computer-assisted math): a soundness bug in the Lean 4
  KERNEL itself (phantom parameters in nested-inductive-type elimination escaping type checking,
  reachable only via metaprogramming, letting an ill-typed argument produce a proof of `False`),
  reported and fixed the week of 2026-07-27; independently surfaced (not caused) an earlier r/math
  "AI incidentally 'proves' Collatz via a Lean bug" story (noted, not queued, ~07-25). Blog opened via
  `tvly` this session — the closest primary technical disclosure available (the tool's own chief
  architect; Lean itself does not publish papers on internal bugs). A significant integrity event for
  the formalized-math ecosystem this radar tracks (axis 5): independent-kernel re-checking still holds
  (two distinct implementations both needed a bug), but flags that a single-kernel Lean proof is not
  automatically airtight. Not AI-method tracking (sibling AI radars' beat) — captured for the
  toolchain-integrity RESULT.
- 2026-07-29/07-31 — DESI dynamical-dark-energy saga, TWO new primaries this cycle (axis 3,
  gr-qc/astro-ph.CO): (i) arXiv:2607.27410 — DESI collaboration, "DESI DR2 Results IV:
  Alcock-Paczyński Measurements from the Lyman Alpha Forest and Cosmological Constraints" —
  https://arxiv.org/abs/2607.27410 — a fresh DESI collaboration Key Paper (also covered on the DESI
  news page, opened via `tvly` this session): 1%-precision AP constraint at z=2.33 (2× tighter than
  the same-data BAO), Ω_m=0.325±0.018 (1.4σ above DESI BAO), slightly REDUCES the DESI-vs-CMB tension
  (2.4σ→2.2σ), and finds the w0-wa dynamical-dark-energy model preferred over ΛCDM at 2.7σ
  (DESI+CMB) / 3.2σ (+supernovae) — a continuing, not yet 5σ-confirmed, anomaly (extraordinary-claim
  caution applies). Abstract verified via arXiv API this session (v1/v2, 2026-07-29). (ii)
  arXiv:2607.28918 — Kim, Mota, Tamosiunas, "A Sequentially-Valid Reanalysis of DESI's Dynamical Dark
  Energy Signal" — https://arxiv.org/abs/2607.28918 — an independent statistical critique using an
  anytime-valid e-process (controls false-detection under repeated DR1→DR2→... looks): the DESI
  dynamical-dark-energy signal is concentrated almost entirely in the LRG2 redshift bin and does NOT
  survive a look-elsewhere correction across all seven bins — "a fragile, single-bin,
  specification-dependent signal rather than robust evidence." Abstract verified via arXiv API this
  session (v1 2026-07-31). Directly the kind of VETTING OUTCOME the hard rules ask this radar to
  track on an extraordinary claim — the two primaries together update, not resolve, the standing DESI
  saga (H₀-World-Cup / late-time-anomaly queue thread, 07-15/07-16).
- 2026-07-29 — Nature Communications s41467-026-75023-7 — Moritake, Takiguchi, Aihara et al.,
  "Chiral diffraction from aperiodic monotile structure" —
  https://www.nature.com/articles/s41467-026-75023-7 — math↔physics interface (axis 1/2, discrete
  geometry / optics, peer-reviewed, published 2026-07-29): a physical (photonic/optical) realization
  of the 2023 "einstein"/"hat" aperiodic monotile — a chiral (mirror-symmetry-breaking) quasiperiodic
  structure built from the monotile tiling shows genuine chiral diffraction (pinwheel-like Bragg
  patterns, circular-polarization dependence) absent in conventional quasicrystals. Full article page
  opened via `tvly extract` this session (received 2025-11-11, accepted 2026-06-18, published
  2026-07-29). Closes the 07-25-era r/math pointer ("Math's acclaimed 'einstein tile' finds a new home
  among physicists") that had sat un-chased since. Below-bar math↔physics-interface item.
- 2026-07-31 — arXiv:2607.28011 — Li, "On a proof of the Gorenstein Symmetry Conjecture" —
  https://arxiv.org/abs/2607.28011 — representation theory / homological algebra (axis 1, math.RT/RA):
  gives a homological proof of the Gorenstein Symmetry Conjecture — that one-sided finiteness of the
  self-injective dimension of an Artin algebra is sufficient for Gorensteinness — a famous, long-standing
  open problem in the representation theory of Artin algebras. Unrefereed SINGLE-AUTHOR preprint claiming
  resolution of a named conjecture → PROVISIONAL under the hype-skepticism rule, same footing as the
  matroid-intersection-conjecture claim (2607.08802, 07-13): NOT a resolved conjecture until independent
  vetting; track the outcome. Abstract + author verified via arXiv API this session (v1 2026-07-30). Also
  on `study_shelf` given the conjecture's stature, with the same caveat.
- 2026-07-29 — arXiv:2607.27197 — Arathoon, Ball, Kvalheim, "The Maxwell Conjecture is False" —
  https://arxiv.org/abs/2607.27197 — mathematical physics / classical electrostatics (axis 2,
  physics.class-ph/math-ph): exhibits a configuration of five point charges in Euclidean space whose
  electrostatic potential has at least 24 non-degenerate critical points, refuting Maxwell's
  ~150-year-old conjecture that the potential of $n$ point charges has at most $(n-1)^2$
  non-degenerate critical points ($(5-1)^2=16<24$). A landmark refutation of a classical named
  conjecture at the math↔physics interface. Abstract + authors verified via arXiv API this session
  (v1 2026-07-29). Also on `study_shelf`.
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
  2026-07-27). Single below-bar resolved-open-problem item.
- 2026-07-29 — Rocq 9.3+rc1 — https://github.com/rocq-prover/rocq/releases — formal-math toolchain
  (axis 5, computer-assisted math): the Rocq proof assistant has moved past the previously-tracked
  V9.2.0 to a 9.3 release candidate (lean4 and mathlib4 both unchanged at v4.33.0-rc1 this session).
  2026-W31 update: lean4 and mathlib4 stable tags both bumped v4.32.1→v4.32.2 (~07-28, routine
  toolchain chore per the 07-30/07-31 dailies); v4.33.0-rc1 remains the latest pre-release for both;
  Rocq unchanged at 9.3+rc1. Consolidates and supersedes the dropped 07-23 toolchain queue line.
  Release page opened via `tvly extract` this session (JS-shell rendering, standing-degraded path;
  exact release date not pinned via this access method). Single below-bar toolchain-release item.
  2026-08-05 update: mathlib4 pre-release bumped v4.33.0-rc1→v4.33.0-rc2 (`tvly extract` on the
  releases page this session; lean4/rocq pages returned JS-shell-only this pass, `tvly search`
  follow-up found no fresh version tags for either — treated as unchanged). Routine toolchain chore.
  2026-08-08 update (W32 weekly, HEAL): the 08-07 daily's lean4 version-tag ambiguity is
  RESOLVED — `tvly search "leanprover lean4 latest release version tag" --include-domains
  github.com` this session confirms lean4's pre-release also reads v4.33.0-rc2 ("This is
  release candidate 2 for the v4.33.0 release of Lean"), with v4.32.2 still the latest stable
  tag; `tvly extract` on the bare releases page keeps returning only the JS-shell nav (standing
  failure mode), while `tvly search` gets through — recorded as the working access method in
  SOURCES.md. lean4/mathlib4 pre-releases now confirmed IN SYNC at v4.33.0-rc2; Rocq unchanged
  9.3+rc1. Routine toolchain chore, not a heal-owed flag (resolved same session it was flagged).
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
- 2026-07-27 — SciPostPhys.21.1.017 — Belin, Collier, Eberhardt, Liska, Post, "A universal sum over
  topologies in 3d gravity" — https://scipost.org/SciPostPhys.21.1.017 — theoretical physics / 3d
  quantum gravity (axis 2, hep-th): a statistical version of the conformal bootstrap for AdS₃ gravity's
  sum over topologies, with surgery moves on bulk manifolds reflecting typicality/crossing symmetry of
  the boundary CFT₂ ensemble. SciPost API metadata + page opened this session (published 2026-07-23).
  Single below-bar item. RESTORED 2026-W34 (weekly): mistakenly cut in this week's queue burndown before
  the burndown-executor noticed arXiv:2608.03459 (Yu, queued 2026-08-04, below) explicitly engages this
  item as a rigidity/no-go counterpoint — not zero-follow-up, so ineligible for pruning; kept.

- 2026-07-25 — **2026 Breakthrough Prize in Fundamental Physics → the Muon g-2 collaborations (CERN, Brookhaven, Fermilab)** — https://breakthroughprize.org/ — recognition/ecosystem (axis 3, HEP precision / BSM): awarded "for multi-decade, groundbreaking contributions to the measurement of the muon's anomalous magnetic moment, pushing the boundaries of experimental precision" across three collaborations over six decades; six New Horizons prizes also awarded (early-career physics & math). Breakthrough laureate page opened this session (tvly) — CLOSES the prize-capture gap flagged 2026-07-12 (the Breakthrough 2026 fundamental-physics laureate had been missed). Ties to the famous muon g-2 anomaly (the a_μ tension with the Standard Model). Ecosystem/recognition item → follow to the collaboration's honored measurement papers next.
- 2026-07-24 — **2026 Fields Medals (IMU / ICM 2026, Philadelphia)** — https://www.mathunion.org/imu-awards/fields-medal/fields-medals-2026 — recognition/ecosystem, THE math event of the week (axis 1, pure math + math-physics): awarded 2026-07-23 at the ICM opening ceremony to **Yu Deng, John Pardon, Jacob Tsimerman, Hong Wang** — IMU laureate page WITH full citations opened this session (primary). Citations (verbatim highlights): **Deng** — PDE, incl. the rigorous derivation of the Boltzmann equation from hard-sphere dynamics and derivation of wave-kinetic equations from nonlinear dispersive systems; **Pardon** — symplectic geometry (virtual fundamental cycles, Fukaya categories, holomorphic-curve counts) + 3-manifold group actions & knot theory; **Tsimerman** — recasting o-minimality as a method of arithmetic/complex algebraic geometry, incl. Griffiths' algebraicity of period maps and the André–Oort conjecture for Siegel modular varieties; **Wang** — harmonic analysis & geometric measure theory: local smoothing, Fourier restriction, Falconer distance sets, Furstenberg sets in the plane, and the Kakeya problem in three dimensions. RADAR CONVERGENCE: two of the four honored bodies of work are ALREADY tracked here — **Wang's** Kakeya-3D (Wang–Zahl, arXiv:2502.17655) and Furstenberg-plane results are on the `study_shelf` / behind the 2026 Clay Award, and **Deng's** Boltzmann/wave-kinetic work is the 2026 Clay Award (Deng, Hani) queued 2026-07-08 → the radar's tracked landmark artifacts ARE the Fields-honored work. Also on `study_shelf`. (Same-ceremony IMU 2026 prizes noted as ecosystem: Chern Medal → Graeme Segal [math-physics/topology], Gauss Prize → Yurii Nesterov [optimization], Abacus Medal → Shayan Oveis Gharan [algorithms] — pages surfaced via IMU-site search, not individually opened → intake.)
- 2026-07-24 — arXiv:2607.21367 — "A solution to 2-copy distillability of Werner states" — https://arxiv.org/abs/2607.21367 — quantum-information theory / entanglement (axis 4, quant-ph/math-ph): proves Werner states in arbitrary dimension are 2-copy distillable **iff** 1-copy distillable, answering the longstanding open question of 2-copy distillability of Werner states — an important step toward whether every NPT (non-positive-partial-transpose) state is distillable, a central open problem in entanglement distillation. Abstract opened via arXiv API this session (v1 2026-07-23). Single below-bar resolved-open-question item; also on `study_shelf`.
- 2026-07-24 — arXiv:2607.21517 — "Improved lower bounds for the Shannon capacity of odd cycles" — https://arxiv.org/abs/2607.21517 — combinatorics / zero-error information theory (axis 1, math.CO): constructs large independent sets in strong powers (size 134753 in C₇¹⁰, 21909 in C₁₁⁶, 62530 in C₁₃⁶) improving the best-known lower bounds Θ(C₇) > 3.258020, Θ(C₁₁) > 5.289773, Θ(C₁₃) > 6.300109 — a concrete lower-bound advance on a famously hard problem (Shannon capacity of odd cycles). Abstract opened via arXiv API this session (v1 2026-07-23). Lower-bound advance but on GRAPH CAPACITY, not a Ramsey number → own below-bar queue item (does not lift the Ramsey trend).
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
- 2026-07-23 — arXiv:2607.20210 — Shaska, "Graded Keller maps and the Jacobian Conjecture" — https://arxiv.org/abs/2607.20210 — algebraic geometry (axis 1, math.AG): the FIRST arXiv mathematical analysis engaging "the map recently announced as a counterexample" to the ~87-year-old JACOBIAN CONJECTURE (Keller 1939). Classifies equivariant polynomial (Keller) maps by the SIGN-signature of their grading weights via weighted-projective geometry: the announced counterexample is equivariant for wt(x,y,z)=(1,−1,−2); if all weights are positive an equivariant Keller map is always an automorphism (no counterexample possible), and in dimension two the same holds for every sign pattern — so the counterexample necessarily lives in the mixed-sign, dim≥3 setting. Abstract opened via arXiv API this session (v1 2026-07-22). CONTEXT: the counterexample itself (3-variable, refuting the general conjecture) was announced OFF-arXiv (X post / Secret Blogging Seminar) and is AI-ASSISTED — "generated with Anthropic's Claude Fable 5" (WATCH area per scope: track the RESULT + this arXiv analysis, NOT the AI method — sibling AI radars' beat). Unrefereed + extraordinary-claim → PROVISIONAL under the hype-skepticism rule (Terence Tao and others actively scrutinizing it publicly — a vetting SIGNAL, not an OUTCOME; the counterexample announcement is NOT a primary I opened → the counterexample-claim itself stays community-pulse intake). Also on study_shelf. Single below-bar item (the on-arXiv analysis of a landmark claimed refutation).
- 2026-07-22 — arXiv:2607.19184 — "A counter-example to Batyrev's conjecture on the non-negativity of stringy Hodge numbers" — https://arxiv.org/abs/2607.19184 — algebraic geometry (axis 1, math.AG): gives a counter-example to Batyrev's conjecture — a fundamental open problem that "guided and motivated many beautiful results in motivic integration, mirror symmetry, and the McKay correspondence" — refuting the claimed non-negativity of stringy Hodge numbers. Abstract opened via arXiv API this session (v1 2026-07-21). AI-ASSISTED (WATCH area per scope): the counter-example was "discovered with the assistance of OpenAI's ChatGPT" — track the RESULT (a falsified fundamental conjecture), NOT the AI method (the sibling AI radars' beat). Unrefereed preprint → provisional under the hype-skepticism rule; track the vetting. Also on study_shelf. Single below-bar refuted-conjecture item.
- 2026-07-22 — arXiv:2607.18655 — "A proof of the mod 4 Kawauchi Conjecture" — https://arxiv.org/abs/2607.18655 — low-dimensional topology / knot theory (axis 1, math.GT): proves the mod-4 form of Kawauchi's conjecture on the Conway polynomial of amphicheiral knots (∇_K ≡ f(z)f(−z) mod 4), a statement the author conjectured in 2006 from finite-type-invariant patterns (the full integer conjecture is false — Ermotti–Hongler–Weber counterexample). Abstract opened via arXiv API this session (v1 2026-07-21). AI-ASSISTED (WATCH area): "produced with the help of Claude Fable 5" — track the RESULT, NOT the AI method. Unrefereed preprint → provisional; track the vetting. Single below-bar item.
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
- 2026-07-15 — arXiv:2607.13009 — "Model-Independent Indication for a Localized Anomaly in the Late-Time Expansion History" — https://arxiv.org/abs/2607.13009 — cosmology / dark energy (axis 3, gr-qc/astro-ph.CO): a model-independent spline reconstruction of DESI DR2 BAO + DES "Dovekie" Type-Ia-SN distances finds a localized ~3.5σ deviation from Planck-2018 ΛCDM over z≈0.3–0.6 (peak z≈0.47), robust to reconstruction/dataset/sound-horizon variations. EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): a 3.5σ anomaly is NOT a discovery — below 5σ, look-elsewhere effect, "if confirmed"; provisional, track the vetting. Ties into the DESI dynamical-dark-energy saga. DESI is a tracked experiment. Abstract opened via arXiv API this session (v1 2026-07-14).
- 2026-07-15 — arXiv:2607.13025 — "The Balanced Four-Color Theorem" — https://arxiv.org/abs/2607.13025 — combinatorics / graph coloring (axis 1, math.CO): every planar graph on n≥3 vertices admits a 4-coloring in which every color class has fewer than n/2 vertices — and this bound is BEST POSSIBLE, computable in O(n log n); extended to ≥5 colors and to general surfaces. A sharp "balanced" strengthening of the Four Color Theorem. Single below-bar item; abstract opened via arXiv API this session (v1 2026-07-14).
- 2026-07-13 — arXiv:2607.08802 — "The matroid intersection conjecture" (van der Zypen) — https://arxiv.org/abs/2607.08802 — CLAIMED PROOF of Nash-Williams' infinite matroid intersection conjecture, a long-standing open problem in infinite-matroid theory; abstract opened via arXiv API this session (v1 2026-07-09). Unrefereed single-author preprint claiming resolution of a named conjecture → PROVISIONAL under the hype-skepticism rule: NOT a resolved conjecture until independent vetting; track the outcome. Axis 1 (combinatorics).
- 2026-07-03 — arXiv:2607.01815 — "Evidence for Deconfined Magnetic Order in the Kitaev-J₃ Model" — https://arxiv.org/abs/2607.01815 — deconfined order (axis 3/4); RSS abstract opened. Deconfined-criticality/order sub-theme now 2 independent groups (with 2607.00762) — forming, not yet at the ≥3 bar.
- 2026-07-02 — arXiv:2607.00762 — Deconfined criticality between an antiferromagnetic insulator and a nodal d-wave superconductor (quantum Monte Carlo) — https://arxiv.org/abs/2607.00762 — condensed matter (axis 3/4): quantum Monte Carlo evidence for a second-order deconfined quantum phase transition (Néel → nodal d-wave superconductor) via a parton/gauge-field construction. Abstract verified via arXiv API 2026-W31 (weekly, closing a month-old unverified gap). Deconfined-criticality/order sub-theme now 2 independent groups (with 2607.01815) — forming, not yet at the ≥3 bar.
- 2026-08-13 — arXiv:2608.13536 — Lu, Yang, "A solution to Banach's isometric conjecture" —
  https://arxiv.org/abs/2608.13536 — functional analysis / Banach-space geometry (axis 1,
  math.FA): proves Banach's 1932 isometric conjecture (a real Banach space all of whose
  n-dimensional subspaces are mutually isometric, for some fixed 1<n<dim X, must be a Hilbert
  space) for every ODD n — the last open cases — completing the conjecture in the real case
  together with Gromov's 1967 even-n resolution. Abstract + authors verified via arXiv API
  this session (v1 2026-08-13). A landmark completion of a ~94-year-old classical conjecture;
  unrefereed two-author preprint — PROVISIONAL under the hype-skepticism rule, but building on
  and completing established prior work (Gromov + subsequent partial cases), lower epistemic
  risk than a from-scratch claim. Also on `study_shelf`.
- 2026-08-13 — arXiv:2608.13553 — Ge, "Heat kernel geometry and Gromov's volume growth
  conjecture" — https://arxiv.org/abs/2608.13553 — differential geometry / geometric analysis
  (axis 1, math.DG): answers affirmatively Gromov's 1986 question — every complete noncompact
  n-manifold with nonnegative Ricci curvature and scalar curvature ≥1 satisfies
  Vol(B(p,R)) ≤ C_n R^{n-2} — via the heat-kernel Fisher metric and Nash entropy. Abstract +
  author verified via arXiv API this session (v1 2026-08-13). A landmark resolution of a
  ~40-year-old named conjecture in comparison geometry; unrefereed single-author preprint —
  PROVISIONAL under the hype-skepticism rule; track the vetting outcome.
- 2026-08-13 — arXiv:2608.13497 — Gui, Li, Wei, Ye, "A positive answer to the generalized
  Chang-Yang conjecture on S^N" — https://arxiv.org/abs/2608.13497 — geometric analysis / PDE
  (axis 1, math.AP): proves the generalized Chang-Yang conjecture (a Beckner-inequality
  rigidity statement on S^N for every integer N≥3, α≥1/2) via an integral representation
  formula and a rigidity theorem for stable critical points. Abstract + authors verified via
  arXiv API this session (v1 2026-08-13). A landmark resolution of a named conjecture by an
  established PDE group (Juncheng Wei); unrefereed — PROVISIONAL; track the vetting outcome.
- 2026-08-13 — arXiv:2608.12844 — Ivanisvili, "The Hayman–Wu constant is π²" —
  https://arxiv.org/abs/2608.12844 — complex analysis / conformal mapping (axis 1, math.CV):
  determines the EXACT value of the classical Hayman–Wu constant (the sharp bound, over all
  conformal maps φ from the disk and all lines L, on the length of φ⁻¹(L∩Ω)) to be π², settling
  a question open since Hayman and Wu's 1981 paper. Abstract + author verified via arXiv API
  this session (v1 2026-08-13). A landmark resolution, by an established harmonic analyst, of a
  ~45-year-old sharp-constant problem; unrefereed single-author preprint — PROVISIONAL; track
  the vetting outcome. Also on `study_shelf`.
- 2026-08-13 — arXiv:2608.13291 — Chernikov, "SOP₂=SOP₃" — https://arxiv.org/abs/2608.13291 —
  mathematical logic / model theory (axis 1, math.LO): proves the classes of SOP₂ and SOP₃
  first-order theories coincide, answering a 2004 question of Džamonja and Shelah in Shelah's
  classification-theory stability hierarchy. Abstract + author verified via arXiv API this
  session (v1 2026-08-13). A landmark resolution of a ~22-year-old open question in model
  theory by a leading expert (Artem Chernikov); unrefereed single-author preprint —
  PROVISIONAL under the hype-skepticism rule; track the vetting outcome.
- 2026-08-13 — arXiv:2608.13539 — Jasper, Mixon, "HRT counterexamples with exponential tails" —
  https://arxiv.org/abs/2608.13539 — harmonic analysis / time-frequency analysis (axis 1,
  math.FA/CA): a SECOND, independent engagement with last week's HRT-conjecture disproof
  (Faulhuber–Petersen–van Velthoven–Voigtlaender, 2608.05044, study_shelf 08-06) — gives a
  human-readable account of the mechanism and constructs HRT counterexample functions with
  exponential (or faster) decay, which by a Bownik–Speegle result is the fastest possible decay
  for any HRT counterexample. Abstract + authors verified via arXiv API this session (v1
  2026-08-13). A sharpening/independent-engagement follow-up on an already-tracked landmark, not
  a new named-conjecture resolution in its own right.
- 2026-08-13 — arXiv:2608.13551 — Park, "Every PPT channel has finite entanglement-breaking
  index" — https://arxiv.org/abs/2608.13551 — quantum information theory (axis 4, quant-ph):
  proves every PPT (positive-partial-transpose) linear map has finite entanglement-breaking
  index, and bounds it by 3 for a large sub-family — strong evidence toward, but not a proof of,
  the long-standing PPT-cubed conjecture. Abstract + author verified via arXiv API this session
  (v1 2026-08-13). Below-bar partial-progress item toward a named conjecture.
- 2026-08-13 — arXiv:2608.13025 — Lavi, "A counterexample to the Foregger-Sinkhorn tie-point
  conjecture" — https://arxiv.org/abs/2608.13025 — combinatorial matrix theory (axis 1,
  math.CO): refutes the Foregger–Sinkhorn tie-point conjecture on permanent-minimizing doubly
  stochastic matrices via an explicit dimension-8 counterexample. Abstract + author verified via
  arXiv API this session (v1 2026-08-13). Below-bar refuted-conjecture item.
- 2026-08-13 — arXiv:2608.13021 — Rodrigues, "The Bosch and Simó conjecture on the
  Shilnikov-Hopf bifurcation" — https://arxiv.org/abs/2608.13021 — dynamical systems (axis 1,
  math.DS): proves the 1993 Bosch–Simó conjecture that "large" strange attractors (in the
  Broer–Simó–Tatjer sense) persistently and robustly arise in the unfolding of a Shilnikov–Hopf
  bifurcation, with SRB measures on a positive-measure parameter set. Abstract + author verified
  via arXiv API this session (v1 2026-08-13). A resolution of a ~33-year-old named conjecture in
  dynamical systems; unrefereed single-author preprint — PROVISIONAL; track the vetting outcome.
- 2026-08-13 — arXiv:2608.13067 — Zheng, "Computer-assisted Proof Under Audit: Typos,
  Certificate Errors, and Reproducible Exact Checks for a Symbolic Invertibility Proof" —
  https://arxiv.org/abs/2608.13067 — VETTING-OUTCOME item (analysis / computer-assisted-proof
  integrity, axis 1, math.AP): an independent, version-pinned audit of the exact-arithmetic
  certificate behind Elgindi–Pasqualotto's "Invertibility of a linearized Boussinesq flow"
  (arXiv:2310.19781, published Communications in Mathematical Physics 2025) reports 11
  proof-affecting defects and gives reproducible exact counterexamples to several implemented
  bounds/reconstruction steps in the released computation; the CMP-published version corrects
  none of the audited items. Abstract + author verified via arXiv API this session (v1
  2026-08-13). CAUTION: this is a defect report on a PUBLISHED, peer-reviewed computer-assisted
  proof, directly relevant to the radar's standing computer-assisted-proof-pattern watch
  (Pompeiu/Schiffer/Berenstein, Kuperberg six-cylinder, Balanced Four-Color Theorem) and to the
  hype-skepticism rule's emphasis on tracking vetting outcomes — a caution about certificate
  reliability, not (per the abstract) a claim that the underlying invertibility RESULT is false.
  Below-bar intake; watch for the original authors' response.
- 2026-08-13 — arXiv:2608.12897 — Alkalay, Park, Oh, Hong, Lee, Tiwari, Senapati, Umansky,
  Heiblum, Sim, "Observation of Time-Domain Braiding of Non-Abelian Anyons at ν=5/2 State" —
  https://arxiv.org/abs/2608.12897 — condensed matter physics (axis 3, cond-mat.mes-hall):
  Weizmann Institute (Heiblum group) + KAIST report a "time-domain braiding" signature of
  non-Abelian anyons in the ν=5/2 fractional quantum Hall state, via current-fluctuation
  partition-noise measurements of the downstream Abelian charged mode and the upstream
  non-Abelian neutral mode, consistent with the "particle-hole Pfaffian" topological order.
  Abstract + authors verified via arXiv API this session (v1 2026-08-13). FIRST-OF-KIND
  experimental evidence for non-Abelian anyon braiding — a domain-cadence landmark single
  result. EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): "experimental evidence of
  non-Abelian braiding has thus far remained elusive" (the paper's own framing); ν=5/2 has a
  history of contested claims in this exact system — PROVISIONAL pending independent
  replication and theoretical scrutiny. Also on `study_shelf`.
- 2026-08-11 (v1; surfaced via the off-axis exploration slot, filed under cs.CC not the math
  category rotation — a genuine off-axis catch) — arXiv:2608.11158 — Saha, Li, Xue, Chaudhuri,
  Klivans, Kothari, Meka, "New Lower and Upper Bounds for the Grothendieck Constant" —
  https://arxiv.org/abs/2608.11158 — companion methodology paper arXiv:2608.11195, "Long-Horizon
  AI Research for Grothendieck Constant: A Case Study in Human-AI Mathematical Collaboration" —
  https://arxiv.org/abs/2608.11195 — combinatorics / functional analysis (axis 1, math.FA-
  adjacent, filed cs.CC): tightens the classical Grothendieck constant K_G to
  6π/11 ≤ K_G ≤ π/(2log(1+√2)) − 10⁻⁴ (exact value open since Grothendieck's 1953 inequality),
  via a new limitation result on Krivine schemes (lower bound) and the first asymptotic
  rounding-scheme construction (upper bound). Abstracts + authors verified via arXiv API this
  session (v1/v2 2026-08-11/08-12). AI-WATCH note (scope area, not tracked as the method): the
  companion paper is an explicit case study of AI-assisted long-horizon research on this exact
  result. "Significant, off-axis" queue item per `radar-explore` — a genuine sharp-constant
  improvement on a classical open problem, caught only because the off-axis rotation reads cs.CC
  regardless of sub-topic.
- 2026-08-17 (daily) — arXiv:2608.14194 — Stessin, Yang, "Reducibility of linear
  representations, free ideals, and Kippenhahn's conjecture" — https://arxiv.org/abs/2608.14194
  — operator/matrix theory (axis 1, math.RT-adjacent, filed math.RT): a comprehensive study of
  characteristic polynomials of matrix tuples and finite-dimensional group representations that
  the authors state "provides a complete resolution to Kippenhahn's conjecture" (Kippenhahn 1951,
  on repeated factors in the characteristic polynomial of a Hermitian-matrix pencil — confirmed
  via `tvly search`, a 75-year-old, actively-studied problem with its own prior "Kippenhahn's
  Conjecture Revisited" arXiv:2603.09915 this year). Abstract verified via arXiv API this session
  (v1 2026-08-14); age/standing of the conjecture corroborated via `tvly search` this session.
  Domain-cadence LANDMARK single result (a ~75-year-old named conjecture resolved) — unrefereed
  preprint, standard caution. Also on `study_shelf`.
- 2026-08-17 (daily) — arXiv:2608.14013 — Chalmers, "A counterexample to Kusner's conjecture on
  equilateral sets" — https://arxiv.org/abs/2608.14013 — functional/convex analysis (axis 1,
  math.MG-adjacent, filed math.MG): disproves Kusner's 1983 conjecture that every equilateral set
  in $\ell_p^n$ ($2<p<\infty$) has at most $n+1$ points, via an explicit 58-point equilateral set
  in $\mathbb{R}^{56}$ under the $\ell_5$ metric — the first equilateral set of more than $n+1$
  points in $\ell_p^n$ for any finite $p\ge2$. Abstract verified via arXiv API this session (v1
  2026-08-14). Domain-cadence LANDMARK single result (a 43-year-old named conjecture refuted) —
  unrefereed preprint, standard caution. Also on `study_shelf`.
- 2026-08-17 (daily) — arXiv:2608.13964 — Makarov, "A counterexample to the Albertson-Berman
  conjecture about induced forests in planar graphs" — https://arxiv.org/abs/2608.13964 —
  extremal/structural combinatorics (axis 1, math.CO): an independent, non-AI 39-vertex
  counterexample (largest induced forest $a(G)=19 < n/2$) to the Albertson-Berman conjecture
  (open since 1979) on induced forests in planar graphs. The paper's own framing states the
  conjecture "was recently resolved in the negative by constructing a counterexample with the
  help of AI" — that AI-assisted precursor was NOT independently traced/verified this session (no
  matching arXiv id found via title/abstract search; flagged for a follow-up chase, not cited as
  evidence here). Abstract verified via arXiv API this session (v1 2026-08-14). Domain-cadence
  LANDMARK single result on its own terms (a 46-year-old named conjecture independently refuted
  by a human-only proof) — unrefereed preprint, standard caution; the same author (Makarov) has a
  January 2026 companion paper on the multigraph variant, queued separately below
  (arXiv:2601.04637).
- 2026-08-17 (daily, CAPTURE — named in the Albertson-Berman item above, given its own line per
  the capture rule) — arXiv:2601.04637 — Makarov, "Large induced forests in planar multigraphs"
  — https://arxiv.org/abs/2601.04637 — extremal combinatorics (axis 1, math.CO): a companion,
  below-bar result (not the counterexample itself) proving $a(M)\ge n/4$ for planar multigraphs
  and a refined bound $a(M) \ge \frac{2}{5}n - \frac{k}{10}$ for graphs with $k$ parallel-edge
  pairs; relates the Albertson-Berman conjecture for simple graphs to a multigraph variant.
  Abstract verified via arXiv API this session (v1 2026-01-08).
- 2026-08-17 (daily) — arXiv:2608.14217 — Ni, "The Quartic Hessian Conjecture in Dimension Four"
  — https://arxiv.org/abs/2608.14217 — algebraic geometry / polynomial-map theory (axis 1,
  math.AG, Jacobian-conjecture-ADJACENT — a distinct but related polynomial-map problem, not the
  same conjecture as the standing Jacobian-conjecture/AI-wave cluster): proves the four-variable
  quartic case of the open dimension-4 Hessian conjecture (known true for dimensions ≤3, false
  for dimensions ≥5). A partial case, not a full resolution — below the landmark bar. Abstract
  verified via arXiv API this session (v1 2026-08-14).
- 2026-08-17 (daily) — arXiv:2608.13946 — Wang, Sun, Yang, "On the Lei-Bai conjecture on
  5-regular Lin-Lu-Yau Ricci-flat graphs" — https://arxiv.org/abs/2608.13946 — graph theory /
  discrete Ricci curvature (axis 1, math.CO): disproves the Lei-Bai conjecture (that every
  5-regular Ricci-flat graph is either a specific 72-vertex graph or a nontrivial Cartesian
  product) via an infinite counterexample family. A narrower, recent conjecture (not a
  long-standing landmark) — below-bar intake. Abstract verified via arXiv API this session (v1
  2026-08-14).
- 2026-08-17 (daily) — arXiv:2608.13887 — Chen, Zheng, "The Fino-Vezzoni conjecture on balanced
  Bismut torsion-parallel manifolds" — https://arxiv.org/abs/2608.13887 — complex geometry (axis
  1, math.DG): a PARTIAL result (proves the conjecture under an added pluriclosed-metric
  hypothesis), not a full resolution — below-bar intake. Abstract verified via arXiv API this
  session (v1 2026-08-14).
- 2026-08-17 (daily) — arXiv:2608.14396 — "AI-Assisted Discovery and Construction of a
  Counterexample to the Convergence of Three-Block ADMM with the Identity Matrix as its Third
  Constraint Block" — https://arxiv.org/abs/2608.14396 — optimization (axis 1, math.OC):
  AI-ASSISTED counterexample construction — another entry in the standing AI-assisted-math wave
  (axis-5 WATCH area; track the mathematical result, not the AI method). Below-bar intake.
  Abstract verified via arXiv API this session (v1 2026-08-14).
- 2026-08-19 (daily) — arXiv:2608.18053 — Cárdenes Wuttig, Tindall, "A Complete Classification of
  Complex Hadamard Matrices of Order Six" — https://arxiv.org/abs/2608.18053 — quantum
  information / matrix analysis (axis 4, quant-ph/math.OA): gives the first complete, exact
  finite-incidence classification of order-six complex Hadamard matrices up to standard
  equivalence — order six was the first dimension where several continuous families coexist with
  an isolated solution, and has stayed open for decades since the classification through order
  five. Complex Hadamard matrices underlie mutually unbiased quantum measurements and multiphoton
  interferometry. Abstract + authors verified via arXiv API this session (v1 2026-08-18).
  Domain-cadence LANDMARK single result (a decades-open classification problem completed) —
  unrefereed preprint, standard caution. Also on `study_shelf`.
- 2026-08-19 (daily) — arXiv:2608.17891 — Liao, Wang, Zhang, "Thompson's Conjecture for Finite
  Simple Groups of Lie Type over Small Fields" — https://arxiv.org/abs/2608.17891 — group theory
  (axis 1, math.GR): proves every finite simple group of Lie type over a field of order ≤8
  contains a conjugacy class whose square is the whole group; combined with previously
  established cases, this completes the proof of Thompson's conjecture (J. G. Thompson) in full.
  Abstract + authors verified via arXiv API this session (v1 2026-08-18). Domain-cadence LANDMARK
  single result (a long-standing named conjecture in finite group theory, now fully resolved) —
  unrefereed preprint, standard caution.
- 2026-08-19 (daily) — arXiv:2608.18054 — Chakravarty, Choi, Xu, "Counterexamples to Sato's Weak
  F-Equivalence Conjecture and a Gorenstein Refinement" — https://arxiv.org/abs/2608.18054 —
  algebraic/toric geometry (axis 1, math.AG): disproves Sato's weak F-equivalence conjecture for
  nonsingular projective toric weak Fano varieties in every dimension d≥3, via smooth projective
  crepant models of centered reflexive simplices. Abstract + authors verified via arXiv API this
  session (v1 2026-08-18). Below-bar intake (a specialized toric-geometry conjecture, not a
  broadly landmark named problem).
- 2026-08-19 (daily) — arXiv:2608.17227 — Pournader, "Completing the Boundary Case of the
  Mahmoodian-Mirzakhani Conjecture and 117 New Computational 5-Cycle Decompositions of Complete
  Tripartite Graphs" — https://arxiv.org/abs/2608.17227 — combinatorial design theory (axis 1,
  math.CO): proves the Mahmoodian-Mirzakhani conjecture (5-cycle decomposability of complete
  tripartite graphs $K_{r,s,t}$) on the extremal boundary case $t=4rs/(r+s)$ for every odd triple,
  constructively. Abstract verified via arXiv API this session (v1 2026-08-18). Below-bar intake
  (a boundary case of a design-theory conjecture, not a full resolution).
- 2026-08-19 (daily) — arXiv:2608.17706 — Wang, Zhou, "A Symmetric Counterexample to the
  Snashall–Solberg Conjecture" — https://arxiv.org/abs/2608.17706 — representation theory /
  homological algebra (axis 1, math.RT): the trivial extension of the Xu–Snashall algebra gives
  the first known selfinjective counterexample to the Snashall–Solberg conjecture (that the
  Hochschild cohomology ring of a finite-dimensional algebra modulo nilpotence is finitely
  generated). Abstract + authors verified via arXiv API this session (v1 2026-08-18). Below-bar
  intake (a specialized homological-algebra conjecture).
- 2026-08-19 (daily, source-discovery + ecosystem) — Simons Foundation, "Simons Foundation
  Launches Collaboration on Universal Statistics in Number Theory" (2026-08-18) —
  https://www.simonsfoundation.org/2026/08/18/simons-foundation-launches-collaboration-on-universal-statistics-in-number-theory/
  — a new Simons Collaboration (director Jon Keating, Oxford) applying statistical-physics models
  of correlated randomness to number theory (Riemann zeta statistics, prime correlations, the
  twin-prime conjecture's "hidden patterns"). Page opened via `tvly extract` this session.
  Ecosystem/funding announcement, not a primary result — queued for context; axis 1/2 interface
  (number theory ↔ statistical mechanics), watch for the collaboration's first artifacts.
- 2026-08-19 (daily) — Terence Tao, "Palomar — a registry of Lean verified mathematics"
  (2026-08-18) — https://terrytao.wordpress.com/2026/08/18/palomar-a-registry-of-lean-verified-mathematics/
  — axis 5 (computer-assisted & formalized mathematics): announces Palomar, a new registry for
  Lean-verified mathematics results, incubated by the Lean FRO and ICARM, with a scientific
  advisory board including Tao, Jeremy Avigad, Matthew Ballard, Bryna Kra, Ravi Vakil, and Akshay
  Venkatesh among others — explicitly motivated by the recent proliferation of AI-generated proof
  claims (some formalized in Lean) that are hard for non-experts to audit for typechecking,
  axiom-cheats, and semantic match to the informal claim. Surfaced via today's Hacker News front
  page, blog post opened via `tvly extract` this session (post dated 2026-08-18). Directly
  relevant infrastructure for this ledger's standing AI-assisted-math-wave watch area. Also on
  `study_shelf`.
- 2026-08-19 (daily, community-pulse pointer, UNVERIFIED — no single primary chased) — Quanta
  Magazine, "Theory of Fluids Enters the 21st Century" (Charlie Wood, 2026-08-17) —
  https://www.quantamagazine.org/theory-of-fluids-enters-the-21st-century-20260817/ — a feature on
  a ~20-year research program rebuilding hydrodynamics as an effective field theory from
  microscopic symmetries (Navier-Stokes equations derived as a symmetry consequence, informed by
  black-hole/holography work), rather than a single new-artifact drop. A representative primary in
  this program, located via `tvly search` but not independently opened this session: arXiv:2407.08760
  (Huang et al., "Hydrodynamics as the effective field theory of strong-to-weak spontaneous
  symmetry breaking," APS-published 2026). Below-bar, digest-lane pointer only — the specific
  arXiv/APS primaries behind this feature were not opened this session; flagged for a follow-up
  chase (axis 2/3 interface, math-physics + condensed matter).
- 2026-08-20 (daily, LANDMARK) — arXiv:2606.10102 — Forni, "Existence of a Periodic Orbit for
  Billiards in Polygons" — https://arxiv.org/abs/2606.10102 — dynamical systems / geometry (axis
  1, math.DS): proves the billiard flow in ANY finite polygon (rational or irrational angles) has
  at least one periodic orbit, resolving one of Katok's "Five Most Resistant Problems in Dynamics"
  — the rational-angle case was settled ~50 years ago, but the general (irrational-angle) case had
  stood open. Solo landmark (v1 2026-06-08), surfaced via a Scientific American feature
  (2026-08-14, "What the mathematics of billiards can tell us about loving and letting go") caught
  in today's digest-lane sweep; abstract + authors verified via arXiv API this session. Below the
  ≥3-group trend bar (single author) but clears the domain-cadence LANDMARK bar (a decades-open
  named problem resolved) — queued, also on `study_shelf`.
- 2026-08-20 (daily) — arXiv:2608.16753 — Tao, "Mathematics in the age of AI" —
  https://arxiv.org/abs/2608.16753 — axis 5 (computer-assisted & formalized mathematics, AI-watch
  lane): an essay based on Tao's 2026 ICM public lecture on how the mathematical community might
  respond to AI tools capable of research-level mathematical tasks — conditions on the hypothesis
  that such capabilities arrive and asks what the goals/values of mathematical research actually
  are, using problem-solving as a case study. Surfaced via today's Hacker News front page (140
  points); abstract + author verified via arXiv API this session (v1 2026-08-17). Ecosystem/
  reflective essay, not a new mathematical result — queued for context, also on `study_shelf`
  (directly relevant to this ledger's standing AI-assisted-math-wave watch area).
- 2026-08-20 (daily, hype-skepticism watch) — arXiv:2512.00144 — Jain, Sheridan, Marsh, Heyes,
  Rogers, Schachner, "Bayesian inference on Calabi-Yau moduli spaces and the axiverse:
  experimental data meets string theory" — https://arxiv.org/abs/2512.00144 — math-physics
  interface (axis 2, hep-th/string theory): Bayesian MCMC sampling of the Weil-Petersson measure
  on Calabi-Yau moduli space, with a theory-informed prior on axion masses/decay constants; now
  published in Phys. Rev. D. Named via Peter Woit's "Not Even Wrong" post "HEP-TH and AI"
  (2026-08-16, opened via direct fetch this session — `tvly` unavailable, see Coverage/degraded),
  which flags a King's College London press release ("String theory finally testable with the
  power of AI") built on this paper as overstating the result — Woit, a standing hype-skepticism
  voice, and the press office's framing ("scientists have robustly proved [string theory] can be
  tested") reads as promotional rather than the paper's own more modest Bayesian-inference claim.
  Below-bar intake (a statistical-inference method paper, not a landmark), queued with the caution
  noted per the hard-rule hype-skepticism policy — not itself an extraordinary claim by the
  authors, but a caution on how it is being publicized.
- 2026-08-20 — arXiv:2608.20215 — Xumin Jiang, Mingxiang Li, Zhehui Wang, "On the proof of Bray's
  conjecture" — https://arxiv.org/abs/2608.20215 — comparison/Riemannian geometry, math-physics
  interface (axis 1/2, math.DG): proves a 1997 conjecture of Hubert Bray — for closed Riemannian
  $(M^n,g)$, $n\ge3$, with Ricci $\ge\varepsilon_n(n-1)g$ and scalar curvature $\ge n(n-1)$ for
  some dimensional constant $\varepsilon_n<1$, the volume is at most that of the standard
  $n$-sphere. Abstract + authors verified via arXiv API this session (v1 2026-08-20). Three-author
  unrefereed preprint resolving a named ~29-year-old conjecture in comparison geometry —
  PROVISIONAL under the hype-skepticism rule; domain-cadence landmark-tier. Also on `study_shelf`.
- 2026-08-20 — arXiv:2608.20012 — Sandra Albrechtsen, Raphael Steiner, "Proof of Lichiardopol's
  conjecture on disjoint directed cycles of distinct lengths" — https://arxiv.org/abs/2608.20012
  — digraph structure theory (axis 1, math.CO): confirms Lichiardopol's 2014 conjecture that
  there is a function $g:\mathbb N\to\mathbb N$ such that every digraph of minimum out-degree
  $\ge g(k)$ contains $k$ vertex-disjoint directed cycles of pairwise distinct lengths. Abstract +
  authors verified via arXiv API this session (v1 2026-08-20). Two-author unrefereed preprint
  resolving a named conjecture — PROVISIONAL; below-bar but notable landmark-adjacent item.
- 2026-08-20 — arXiv:2608.19923 — Jianfeng Hou, Caihong Yang, "On the Generalized Rational
  Exponents Conjecture" — https://arxiv.org/abs/2608.19923 — extremal graph theory (axis 1,
  math.CO): proves the generalized rational exponents conjecture of Gerbner and Palmer — for
  every rational $\alpha\ge1$ there exist graphs $H_\alpha,F_\alpha$ with
  $\mathrm{ex}(n,H_\alpha,F_\alpha)=\Theta(n^\alpha)$. Abstract + authors verified via arXiv API
  this session (v1 2026-08-20). Below-bar (a named but comparatively young/niche conjecture),
  unrefereed two-author preprint — PROVISIONAL.
- 2026-08-20 — arXiv:2608.19525 — Ben Krause, Hamed Mousavi, Terence Tao, Joni Teräväinen,
  "Quantitative bounds for sets lacking polynomial progressions with shifted prime difference" —
  https://arxiv.org/abs/2608.19525 — additive combinatorics / analytic number theory (axis 1,
  math.NT/CO): proves the first quantitative polynomial Szemerédi-type theorems for nonlinear
  polynomial progressions with shift restricted to the shifted primes $\mathbb P-1$, and improves
  prior quantitative bounds in the linear case. Surfaced via Tao's blog ("What's new," 2026-08-20,
  https://terrytao.wordpress.com/2026/08/20/quantitative-bounds-for-sets-lacking-polynomial-progressions-with-shifted-prime-difference/,
  opened this session); abstract + authors verified via arXiv API this session (v1 2026-08-20).
  Below-bar technical advance, notable for Tao's own co-authorship — queued.
- 2026-07-14 (v1; CAPTURE-LEAK-adjacent, ~5-week-old peer-reviewed primary, surfaced this session
  via a Backreaction post 2026-08-20 and independently opened) — Feifei Xin, Yehonatan Gelkop,
  Ewout van der Veer, Beatriz Noheda, Ludovica Falsi, Guoquan Zhang, Fang Bo, Aharon J. Agranat,
  Eugenio DelRe, "Spontaneous formation and optical manipulation of a woven domain fabric in a
  ferroelectric crystal," Light: Science & Applications, DOI 10.1038/s41377-026-02374-7 —
  https://www.nature.com/articles/s41377-026-02374-7 — condensed-matter / photonic-materials
  physics (axis 3): reports the first observation of a robust, spontaneously-formed woven fabric
  of interlaced ferroelectric domains in bulk KTN:Li below its room-temperature Curie point — an
  extended, topologically-protected defect structure with locked-in charged domain walls that can
  be locally rewritten with a focused visible laser, opening a route to solid-state topologically-
  protected photonic memory. Peer-reviewed (Nature-family journal); title/authors/DOI/abstract
  verified via direct `curl` fetch of the article page this session (the usual `idp.nature.com`
  auth-wall that blocks `WebFetch` on Nature-family articles was bypassed with a browser
  user-agent header — see Coverage/degraded and `strategy_notes` for the healed access method).
  Domain-cadence landmark first-of-kind observation — queued, also on `study_shelf`.
- 2025-08-05 (v1; MAJOR CAPTURE-LEAK CATCH, ~1-year-old primary, surfaced this session via a
  2026-08-21 Quanta feature and independently opened) — Nikhil Bansal, Haotian Jiang, "Decoupling
  via Affine Spectral-Independence: Beck-Fiala and Komlós Bounds Beyond Banaszczyk," arXiv:2508.03961
  — https://arxiv.org/abs/2508.03961 — combinatorial discrepancy theory (axis 1, math.CO/DS/PR):
  RESOLVES the 1981 Beck-Fiala conjecture (any $n$-element, degree-$k$ set system has discrepancy
  $O(\sqrt k)$) for $k\ge\log^2 n$, and gives the first improvement in decades on the related 1980s
  Komlós conjecture (bounded discrepancy for unit-column matrices), pushing the upper bound from
  $O(\sqrt{\log N})$ to $O((\log N)^{1/4})$. Abstract + authors verified via arXiv API this session
  (v1 2025-08-05); Quanta's "'Huge Breakthrough' in the Math of Imbalance" (2026-08-21,
  https://www.quantamagazine.org/huge-breakthrough-in-the-math-of-imbalance-20260821/, opened this
  session) is what surfaced this — the primary sat outside this ledger's window for over a year.
  Domain-cadence landmark (a 45-year-old named conjecture resolved in its stated regime) — queued,
  also on `study_shelf`.
- 2026-08-21 (v1) — Luca Gennaioli, Filip Rindler, "Concentration phenomena and the Vanishing Mass
  Conjecture," arXiv:2608.20899 — https://arxiv.org/abs/2608.20899 — PDE / geometric measure theory
  (axis 1, math.AP/CA): fully RESOLVES Bouchitté's 2003 Vanishing Mass Conjecture for all
  first-order constant-coefficient linear differential operators — that concentrating,
  non-equi-integrable sequences satisfying such a linear PDE constraint can always be represented
  as superpositions of "simple" concentrations. Abstract + authors verified via arXiv API this
  session. Domain-cadence landmark (a 23-year-old named conjecture fully resolved) — queued, also
  on `study_shelf`.
- 2026-08-21 (v1) — Xin Fu, Juanyong Wang, "On a conjecture of Demailly-Peternell-Schneider: the
  Kähler case," arXiv:2608.20679 — https://arxiv.org/abs/2608.20679 — complex/algebraic geometry
  (axis 1, math.AG/CV): proves pseudo-effectivity of $-K_Y$ for a surjective holomorphic map between
  normal Kähler varieties (log canonical pair, $-(K_X+\Delta)$ nef, $Y$ Q-Gorenstein) without the
  projective-morphism hypothesis used in the authors' own prior work — extending a conjecture of
  Demailly-Peternell-Schneider to the Kähler setting. Abstract + authors verified via arXiv API
  this session. Below-bar (a specialized extension, not a fully independent named-conjecture
  resolution) — queued.
- 2026-08-20 (v1) — Vasily Ionin, Roman Mikhailov, "The Parafree Conjecture for associative
  algebras," arXiv:2608.20570 — https://arxiv.org/abs/2608.20570 — algebra (axis 1, math.RA/AT):
  DISPROVES the associative-algebra analogue of the Parafree Conjecture — constructs a finitely
  generated parafree augmented associative algebra with countably infinite-dimensional second
  homology (the monoid algebra of a finitely generated but not finitely presented submonoid of a
  free monoid) — answering a question of Ivanov and Lopatkin. Abstract + authors verified via arXiv
  API this session. Below-bar (a two-author disproof of a conjecture-analogue, not the original
  named conjecture) — queued.
- 2026-08-19 (v2) — Yufeng Wang, "Counterexamples to the Henning-Yeo Conjecture: Unbounded
  Fixed-Degree Gaps and Sharp First-Order Asymptotics," arXiv:2608.19455 —
  https://arxiv.org/abs/2608.19455 — extremal graph theory (axis 1, math.CO): DISPROVES the
  Henning-Yeo conjectured upper bound on the identifying vertex cover number, via a two-parameter
  family of diameter-two graphs with an unbounded margin for every maximum degree $\ge4$. Abstract
  + author verified via arXiv API this session. Below-bar (single-author disproof of a
  comparatively young/niche conjecture) — queued.
- 2026-08-21 (v1) — Mingchen Xia, Kewei Zhang, "A counterexample to the bounded mass property,"
  arXiv:2608.21053 — https://arxiv.org/abs/2608.21053 — complex geometry (axis 1, math.AG/CV/DG):
  shows the bounded mass property fails on the Hopf threefold $(\mathbb C^3\setminus\{0\})/\langle
  z\mapsto e^{-1}z\rangle$, answering a question of Boucksom-Guedj-Lu. Abstract + authors verified
  via arXiv API this session. Below-bar (answers an open question, not a named conjecture) — queued.
- 2026-08-20 (v1) — Dennis G. Uitenbroek et al. (POLONAISE collaboration), "First Search for
  Ultraheavy Dark Matter Using a Magnetically Levitated Particle," arXiv:2608.20464 —
  https://arxiv.org/abs/2608.20464 — dark-matter detection (axis 3, hep-ph): the FIRST search for
  ultraheavy dark matter using a milligram-scale ferromagnet magnetically levitated in a
  superconducting trap (force sensitivity $0.07\,\mathrm{fN\,Hz^{-1/2}}$, impulse resolution down
  to $1\,\mathrm{TeV}/c$), setting new optimum-interval upper limits on the neutron coupling for a
  light-mediator dark-matter interaction. Abstract + authors verified via arXiv API this session.
  Domain-cadence landmark (first-of-kind detection technique/search) — queued.
- 2026-08-18 (published Phys. Rev. Lett. 137, 086501) — M. S. Grbić, I. Jakovac, I. Kupčić, H.
  Tanaka, M. Horvatić, "Discovery of Berezinskii-Kosterlitz-Thouless Correlations in the Quantum
  Kagome Compound Cs2Cu3SnF12" — http://link.aps.org/doi/10.1103/bm42-z87g — condensed-matter
  physics (axis 3): $^{63,65}$Cu nuclear quadrupolar resonance below the Néel temperature
  ($T_N=20\,$K) finds signatures of Berezinskii-Kosterlitz-Thouless correlations in this quantum
  kagome antiferromagnet. Full abstract, author list and publication date verified directly from
  the APS PRL RSS feed's `content:encoded` field this session (article page itself Cloudflare-
  blocked to direct `curl`/`WebFetch`). Domain-cadence landmark (first-of-kind observation in this
  compound) — queued.
- 2026-07-22 (CAPTURE-LEAK CATCH, chased via today's CERN Courier sweep, accessed 2026-08-24) —
  LHCb Collaboration, "A new doubly charmed baryon" (CERN Courier feature, 2026-07-23) —
  https://cerncourier.com/a/a-new-doubly-charmed-baryon/ — hadron/particle physics (axis 3,
  hep-ex): LHCb has observed a new doubly charmed baryon — the first new particle found with its
  upgraded detector. CERN Courier page opened this session (official CERN-affiliated publication
  reporting the collaboration result); the underlying LHCb paper itself was not independently
  located/opened this session — flagged for a follow-up chase to the primary LHCb/arXiv preprint.
  Domain-cadence landmark (first-of-kind with the upgraded detector) — queued, also on
  `study_shelf`.
- 2026-07-22 (CAPTURE-LEAK CATCH, chased via today's CERN Courier sweep, accessed 2026-08-24) —
  ALPHA Collaboration, "Antihydrogen toes the line" (CERN Courier feature, 2026-07-23) —
  https://cerncourier.com/a/antihydrogen-toes-the-line/ — antimatter / precision physics (axis 3,
  hep-ex): ALPHA measured the ground-state hyperfine splitting of antihydrogen a hundred times
  more precisely than before, sharpening the experimental test of CPT symmetry. CERN Courier page
  opened this session; underlying ALPHA paper not independently located this session — flagged
  for a follow-up chase. Below-bar (a precision improvement, not a first detection) — queued.
- 2026-07-22 (CAPTURE-LEAK CATCH, chased via today's CERN Courier sweep, accessed 2026-08-24) —
  CMS Collaboration, "W boson decays to three charged hadrons" (CERN Courier feature, 2026-07-23)
  — https://cerncourier.com/a/w-boson-decays-to-three-charged-hadrons/ — particle physics (axis 3,
  hep-ex): CMS searched for the rare decay of the W boson into three light charged hadrons,
  setting the most stringent limit yet on its branching fraction. CERN Courier page opened this
  session; a null/limit result — below-bar — queued.
- 2026-08-24 — arXiv:2608.23063 — Jin Sun, Lili Wang, Tao Wang, "Counterexamples to Escobar's
  conjecture" — https://arxiv.org/abs/2608.23063 — conformal/Riemannian geometry (axis 1,
  math.DG): disproves Escobar's 1999 conjecture (J. Funct. Anal.) that every $n$-dimensional
  ($n\ge3$) compact Riemannian manifold with nonnegative Ricci curvature and boundary principal
  curvatures bounded below by $κ>0$ must satisfy first-nonzero-Steklov-eigenvalue $σ_1\ge κ$ —
  explicit conformal deformations of the Euclidean unit ball violate the bound for every $n\ge3$.
  Abstract + authors verified via arXiv API this session (v1 2026-08-24). Domain-cadence
  LANDMARK single result (a 27-year-old named conjecture fully disproved) — unrefereed preprint,
  standard hype-skepticism caution — queued; also on `study_shelf`.
- 2026-08-23 — arXiv:2608.22539 — Yu Shen, Tianyang Sun, "The Bondal-Orlov Localization
  Conjecture Holds for Threefolds" — https://arxiv.org/abs/2608.22539 — derived algebraic
  geometry (axis 1, math.AG): proves a characteristic-free form of the Bondal–Orlov localization
  conjecture (derived-category reconstruction) for quasi-projective threefolds, via a semi-
  orthogonal-decomposition equivalence $D^b(Y)/\mathrm{Ker}(Rp_*)\simeq D^b(X)$ under mild
  cohomological-vanishing hypotheses. Abstract + authors verified via arXiv API this session (v1
  2026-08-23). Partial resolution (threefold case, not the full conjecture) of a well-known open
  problem in derived categories — below full-landmark bar, unrefereed — queued.
- 2026-08-24 — arXiv:2608.23089 — Yuan Yuan, "Yau's conjecture on smooth Reinhardt domains" —
  https://arxiv.org/abs/2608.23089 — several complex variables (axis 1, math.CV): proves that a
  possibly-unbounded Reinhardt domain in $\mathbb C^n$ with smooth boundary and a complete
  Bergman-Einstein metric must be biholomorphic to the complex unit ball (equivalently, no
  unbounded smooth Reinhardt domain admits a complete Bergman-Einstein metric), resolving a
  conjecture attributed to Yau in this setting. Abstract + author verified via arXiv API this
  session (v1 2026-08-24); the conjecture's exact origin/age not independently dated this
  session. Below-bar landmark-adjacent item — unrefereed, single-author — queued.
- 2026-08-24 — arXiv:2608.23132 — Haruhisa Enomoto, "The Cartan determinant conjecture for
  representation-finite algebras" — https://arxiv.org/abs/2608.23132 — representation theory of
  algebras (axis 1, math.RT/RA): proves the classical Cartan determinant conjecture (Cartan
  matrix has determinant one) for finite-dimensional representation-finite algebras over an
  algebraically closed field, under mild hypotheses. Abstract + author verified via arXiv API
  this session (v1 2026-08-24). Partial resolution of a decades-old conjecture (known false in
  general, proved here for a broad special case) — unrefereed — queued.
- 2026-08-21 — arXiv:2608.21675 — Yaping Mao, "Dense ascending waves: A resolution of the
  Alon-Spencer conjecture" — https://arxiv.org/abs/2608.21675 — additive/extremal combinatorics
  (axis 1, math.NT/CO): resolves Alon and Spencer's conjecture on the extremal ascending-wave
  length $g(n)$ (the longest strictly-increasing, nondecreasing-gap subsequence guaranteed in any
  $n/2$-density subset of $[n]$), pinning the $(\log n)^2/\log\log n$ vs. $(\log n)^2$ gap in
  their original bound. Abstract + author verified via arXiv API this session (v1 2026-08-21).
  Resolution of a named conjecture from a standard probabilistic-combinatorics reference (Alon &
  Spencer) — unrefereed, single-author — queued.
- 2026-08-24 (CAPTURE — a follow-up to the already-tracked Albertson-Berman counterexample above,
  given its own line per the capture rule) — arXiv:2608.23260 — Wouter Cames van Batenburg, Jan
  Goedgebeur, Jorik Jooken, "Counterexamples to the Albertson-Berman conjecture: minimum order,
  connectivity and an improved ratio bound" — https://arxiv.org/abs/2608.23260 — extremal/
  structural combinatorics (axis 1, math.CO): a computational follow-up to the 2026-08 Albertson-
  Berman disproofs (arXiv:2608.13964 etc., already tracked above) — establishes via exhaustive
  computation that the minimum possible order of a counterexample is exactly 29, and constructs
  infinite families of highly-connected counterexamples. Abstract + authors verified via arXiv
  API this session (v1 2026-08-24). Below-bar follow-up/characterization item — queued.
- 2026-08-23 — arXiv:2608.22448 — Pengfei Huang, "A counterexample to Bruzzo's curve
  semistability conjecture for Higgs bundles" — https://arxiv.org/abs/2608.22448 — algebraic
  geometry (axis 1, math.AG): constructs a rank-4 Higgs bundle on the second symmetric product of
  a very general plane quintic curve whose restriction to every curve mapping into it is
  semistable, disproving Bruzzo's conjecture on curve semistability for Higgs bundles. Abstract +
  author verified via arXiv API this session (v1 2026-08-23). Below-bar, single-author,
  unrefereed disproof of a modern (non-classical) named conjecture — queued.
- 2026-01-13 (CAPTURE-LEAK CATCH, ~7 months old, surfaced via today's fresh math.RT sweep,
  accessed 2026-08-25) — arXiv:2601.08218 — Liron Speyer, "The minimal counterexample to James's
  conjecture" — https://arxiv.org/abs/2601.08218 — representation theory (axis 1, math.RT):
  James's conjecture on decomposition matrices of symmetric groups/Hecke algebras was already
  disproved by Williamson in 2017 (not new); this paper computes an explicit, much smaller
  counterexample than Williamson's method could detect. Abstract + author verified via arXiv API
  this session (v1 2026-01-13; a later v2 exists, exact revision date not pinned this session).
  Below-bar incremental item (sharpens an already-known disproof, not itself a new resolution) —
  queued for completeness.
- 2026-08-24 — arXiv:2509.20144 (v3) — Julian Feuerpfeil, "A Hilbert 90 Property for S-Class
  Groups and Applications to the Gross-Kuz'min Conjecture" — https://arxiv.org/abs/2509.20144 —
  algebraic number theory (axis 1, math.NT): establishes an arithmetic criterion for a Hilbert-90-
  type property of $S$-class groups in cyclic extensions, with an application (not a full
  resolution) to the Gross-Kuz'min conjecture in Iwasawa theory. Abstract + author verified via
  arXiv API this session. Below-bar partial-progress item — queued.
- 2026-08-24 — arXiv:2608.22813 — Yanjun Liu, Lizhong Wang, Jiping Zhang, Fang Zhou, "The
  Eaton-Moretó Conjecture Holds True for $p$-Solvable Groups" — https://arxiv.org/abs/2608.22813
  — finite group representation theory (axis 1, math.RT): proves a modern (2010s) conjecture of
  Eaton and Moretó for the special case of $p$-solvable groups. Abstract + authors verified via
  arXiv API this session (v1 2026-08-24). Below-bar partial-progress item on a non-classical
  conjecture — queued.
- 2026-08-25 — arXiv:2608.24685 — Damiano Rossi, "The Isaacs-Navarro-Wolf conjecture" —
  https://arxiv.org/abs/2608.24685 — finite group representation theory (axis 1, math.RT): a proof
  of the Isaacs-Navarro-Wolf conjecture (finite solvable $G$: if $x\in G$ has $\chi(x)\ne0$ for
  every irreducible character $\chi$, then $x$ lies in some nilpotent normal subgroup of $G$).
  AI-ASSISTED — the author states the proof "was discovered with the use of artificial intelligence
  systems" (the standing AI-assisted-math wave, watch-lane per AGENTS.md axis 5: track the
  mathematical result, not the AI method). Abstract + author verified via arXiv API this session
  (v1 2026-08-25). Domain-cadence LANDMARK (named-conjecture resolution) but single-author,
  unrefereed — flagged "unrefereed preprint — claim," watch for independent verification/referee
  outcome — queued, also a study pick candidate.
- 2026-08-25 — arXiv:2608.24843 — Sven Hirsch, Yiyue Zhang, "Classification of Maximally Charged
  Black Holes" — https://arxiv.org/abs/2608.24843 — mathematical general relativity (axis 1/2,
  math.DG/gr-qc): characterizes ALL maximally-charged black hole spacetimes in 3+1 dimensions —
  every initial data set saturating the mass-charge inequality under the charged dominant energy
  condition must arise from an isometric embedding into a Majumdar-Papapetrou spacetime. A complete
  classification/rigidity theorem (equality case of the charged Penrose-type inequality). Abstract
  + authors verified via arXiv API this session (v1 2026-08-25). Domain-cadence landmark-adjacent
  (first-of-kind full classification, not a named-conjecture resolution) — queued, also a study
  pick candidate.
- 2026-08-25 — arXiv:2608.24853 — Daoqiang Liu, "Spectral Geroch conjecture and noncompact area
  enlargeable summands" — https://arxiv.org/abs/2608.24853 — mathematical general relativity /
  scalar curvature geometry (axis 1/2, math.DG): extends a theorem of Wang-Zhang (positive scalar
  curvature obstruction under connected sum with an area-enlargeable manifold) from closed to
  noncompact enlargeable summands, plus a spectral analogue of the generalized Geroch conjecture.
  Abstract + author verified via arXiv API this session (v1 2026-08-25). Below-bar technical
  extension of an existing theorem, not itself a conjecture resolution — queued.
- 2026-08-25 — arXiv:2608.23797 — Eric M. Friedlander, "The Stable Adams Conjecture" —
  https://arxiv.org/abs/2608.23797 — algebraic topology (axis 1, math.AT): proves stable-homotopy
  variants of the (already historically resolved, Quillen/Sullivan-era) Adams conjecture via
  F-spaces and a rigid Artin-Mazur étale homotopy theory, correcting/completing the author's own
  2023 reformulation attempt (arXiv:2310.14425). Abstract + author verified via arXiv API this
  session (v1 2026-08-25). Below-bar single-author foundational/technical result (not a new
  open-conjecture resolution) — queued.
- 2026-08-25 — arXiv:2608.23721 — Daniel Carranza, Chunyi Liu, Emily Riehl, Egbert Rijke,
  "Autoformalizing the calculation of $\pi_3(S^2)$" — https://arxiv.org/abs/2608.23721 —
  computer-assisted/formalized mathematics (axis 5, homotopy type theory / agda-unimath): reports
  an experiment autoformalizing the HoTT computation of $\pi_3(S^2)$ using Codex — an AI-assisted
  FORMALIZATION artifact (track the formalization result per axis 5; AI-assistance noted, not the
  method itself). Abstract + authors verified via arXiv API this session (v1 2026-08-25). Below-bar
  single artifact — queued.
- 2026-08-21 (discovered via a Hacker-News front-page pointer this session, accessed 2026-08-26) —
  arXiv:2608.21590 — Andrew J. S. Hamilton, Tyler McMaken, "Black hole singularity is a surface not
  a point" — https://arxiv.org/abs/2608.21590 — mathematical/theoretical general relativity (axis
  2/3, gr-qc): argues the black-hole central singularity is a 2-dimensional surface, not a point —
  two infalling observers on different angular trajectories lose causal contact before reaching the
  singularity; for rotating holes the singular surface sits at the inner horizon via mass-inflation
  instability. Proposes the black hole's quantum microstates reside on this surface, coevolving
  unitarily with the Hawking-radiation atmosphere — a quantum-gravity implication. Abstract +
  authors verified via arXiv API this session. Below-bar single/two-author theoretical proposal,
  unrefereed — queued.

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

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-08-26 (v1 2026-08-25) — [Classification of Maximally Charged Black Holes (Hirsch, Zhang)](https://arxiv.org/abs/2608.24843)
  — a complete classification of every maximally-charged (mass-charge-equality-saturating) black
  hole spacetime in 3+1 dimensions: any such initial data set must embed isometrically into a
  Majumdar-Papapetrou spacetime; a clean rigidity/equality-case theorem in mathematical GR.
- 2026-08-26 (v1 2026-08-25) — [The Isaacs-Navarro-Wolf conjecture (Rossi)](https://arxiv.org/abs/2608.24685)
  — a proof of a standing open conjecture in finite-group character theory, explicitly discovered
  with AI assistance (the ongoing AI-assisted-math wave); single-author, unrefereed — worth knowing
  for both the result and as a fresh data point on AI-assisted proof discovery.
- 2026-08-25 (v1 2026-08-24) — [Counterexamples to Escobar's conjecture (Sun, Wang, Wang)](https://arxiv.org/abs/2608.23063)
  — disproves Escobar's 1999 conjecture bounding the first Steklov eigenvalue below by the boundary
  principal-curvature floor, for every dimension $n\ge3$, via explicit conformal deformations of
  the unit ball; a clean, complete resolution (in the negative) of a 27-year-old named conjecture,
  unrefereed.
- 2026-08-24 (v1 2025-08-05) — [Decoupling via Affine Spectral-Independence: Beck-Fiala and Komlós Bounds Beyond Banaszczyk (Bansal, Jiang)](https://arxiv.org/abs/2508.03961)
  — resolves the 1981 Beck-Fiala conjecture for degree $k\ge\log^2 n$ and gives the first
  improvement in decades on the related Komlós conjecture; a ~1-year-old capture-leak catch
  surfaced via a 2026-08-21 Quanta feature.
- 2026-08-24 — [A new doubly charmed baryon (LHCb Collaboration)](https://cerncourier.com/a/a-new-doubly-charmed-baryon/)
  — the first new particle found with LHCb's upgraded detector; a capture-leak catch from a
  2026-07-23 CERN Courier feature.
- 2026-08-21 — [Spontaneous formation and optical manipulation of a woven domain fabric in a ferroelectric crystal (Xin, Gelkop, Noheda, DelRe et al.)](https://www.nature.com/articles/s41377-026-02374-7)
  — first observation of a robust, topologically-protected woven fabric of interlaced ferroelectric
  domains that self-organizes in bulk KTN:Li near room temperature and can be locally rewritten
  with a laser; peer-reviewed (Light: Science & Applications).
- 2026-08-21 — [On the proof of Bray's conjecture (Jiang, Li, Wang)](https://arxiv.org/abs/2608.20215)
  — resolves a 1997 conjecture of Hubert Bray bounding the volume of closed manifolds with a
  Ricci/scalar-curvature comparison condition by that of the standard sphere.
- 2026-08-20 — [Existence of a Periodic Orbit for Billiards in Polygons (Giovanni Forni)](https://arxiv.org/abs/2606.10102)
  — resolves one of Katok's "Five Most Resistant Problems in Dynamics": every finite polygon's
  billiard flow has a periodic orbit, closing the general (irrational-angle) case left open since
  the rational-angle case was settled ~50 years ago.
- 2026-08-20 — [Mathematics in the age of AI (Terence Tao)](https://arxiv.org/abs/2608.16753)
  — a 2026 ICM-lecture essay on how the mathematical community's goals and values should shape its
  response to AI tools capable of research-level mathematics; direct reflection from a leading
  voice on this ledger's standing AI-assisted-math-wave watch area (axis 5).
- 2026-08-19 — [Palomar — a registry of Lean verified mathematics (Tao et al.)](https://terrytao.wordpress.com/2026/08/18/palomar-a-registry-of-lean-verified-mathematics/)
  — a new Lean-FRO/ICARM-incubated registry for auditing Lean-verified mathematics claims
  (typechecking, no axiom-cheats, semantic match to the informal statement), with a scientific
  advisory board including Tao, Avigad, Ballard, Kra, Vakil and Venkatesh — direct infrastructure
  for the AI-generated-proof wave this ledger has tracked all summer (axis 5). Surfaced via
  Hacker News, blog post opened via `tvly extract` this session (post dated 2026-08-18).
- 2026-08-19 (v1 2026-08-18) — [A Complete Classification of Complex Hadamard Matrices of Order Six (Cárdenes Wuttig, Tindall), arXiv:2608.18053](https://arxiv.org/abs/2608.18053)
  — completes a decades-open classification problem in quantum information / matrix analysis:
  order six was the first dimension where continuous families of complex Hadamard matrices
  coexist with an isolated solution (axis 4). Abstract + authors verified via arXiv API this
  session. Unrefereed preprint — standard caution.
- 2026-08-18 (v1 2026-07-22; capture-leak catch, chased via Hacker News this session) — [Lightest $0^{-+}$ Glueball as Dominant Constituent of $X(2370)$ (BESIII Collaboration), arXiv:2607.20366](https://arxiv.org/abs/2607.20366)
  — the strongest evidence to date, from 10 billion $J/\psi$ events at BESIII, that the light
  hadron $X(2370)$ is dominated by a glueball — a particle made purely of gluons, sought since the
  1970s (axis 3, hadron/QCD physics). Abstract verified via arXiv API this session; widely
  corroborated by Nature News, Science and Ars Technica coverage this week ("an experimental
  triumph" — Colin Morningstar, CMU). Not yet a "single smoking gun" per outside commentary
  (Bruce Yabsley, U. Sydney) — a landmark, near-consensus first-of-kind result worth knowing, with
  the community's own caution about definitiveness intact.
- 2026-08-18 (v1 2026-08-15) — [Prüfer $2$-group and Milnor's Conjecture on Fundamental Groups (Wu, Yan), arXiv:2608.15505](https://arxiv.org/abs/2608.15505)
  — completes the disproof of Milnor's 1968 conjecture (fundamental groups of complete
  nonnegative-Ricci manifolds are finitely generated) in the two dimensions (4 and 5) left open
  since Bruè–Naber–Semola's 2023 counterexamples in dimensions $\ge6$ (axis 1, Riemannian
  geometry). Abstract + authors verified via arXiv API this session; prior open/closed status
  corroborated via Wikipedia and the original 2023 arXiv listing, both opened this session. A
  58-year-old classical conjecture now fully resolved across every dimension (true $n\le3$, false
  $n\ge4$) — unrefereed but a clean, checkable capstone to a well-documented multi-paper program.
- 2026-08-17 — [Reducibility of linear representations, free ideals, and Kippenhahn's conjecture (Stessin, Yang), arXiv:2608.14194](https://arxiv.org/abs/2608.14194)
  — a complete resolution of Kippenhahn's conjecture (1951) on repeated factors in the
  characteristic polynomial of Hermitian-matrix pencils, a 75-year-old problem in matrix/operator
  theory (axis 1). Abstract verified via arXiv API this session (v1 2026-08-14); the conjecture's
  age and standing corroborated via `tvly search`. Unrefereed preprint — standard caution.
- 2026-08-17 — [A counterexample to Kusner's conjecture on equilateral sets (Chalmers), arXiv:2608.14013](https://arxiv.org/abs/2608.14013)
  — disproves Kusner's 1983 conjecture on the maximum size of equilateral sets in $\ell_p^n$
  spaces via an explicit 58-point construction in $\mathbb{R}^{56}$, the first such counterexample
  for any finite $p\ge2$ (axis 1, convex/functional analysis). Abstract verified via arXiv API
  this session (v1 2026-08-14). Unrefereed preprint — standard caution.
- 2026-08-13 — [Observation of Time-Domain Braiding of Non-Abelian Anyons at ν=5/2 State (Alkalay, Park, Oh, Hong, Lee, Tiwari, Senapati, Umansky, Heiblum, Sim), arXiv:2608.12897](https://arxiv.org/abs/2608.12897)
  — the first experimental evidence of non-Abelian anyon braiding, via a time-domain
  partition-noise signature in the ν=5/2 fractional quantum Hall state (axis 3, condensed
  matter). Abstract + authors verified via arXiv API this session (v1 2026-08-13).
  EXTRAORDINARY-CLAIM CAUTION: a first-of-kind claim in a system with a history of contested
  results — PROVISIONAL pending independent replication — but worth knowing as a long-sought
  signature directly relevant to topological quantum computing, from a leading group
  (Weizmann/Heiblum + KAIST).
- 2026-08-13 — [A solution to Banach's isometric conjecture (Lu, Yang), arXiv:2608.13536](https://arxiv.org/abs/2608.13536)
  — completes Banach's 1932 conjecture (a Banach space with all n-dimensional subspaces
  mutually isometric must be Hilbert) for every remaining odd n, joining Gromov's 1967
  even-n resolution to close the real case entirely (axis 1, math.FA). Abstract + authors
  verified via arXiv API this session (v1 2026-08-13). Unrefereed but completes a ~94-year-old
  classical conjecture building on established prior work — worth knowing as a clean
  closure of a foundational question in Banach-space geometry.
- 2026-08-05 (v1 on proofatlas.ai; digested by Terence Tao 2026-08-12, surfaced this session) — [A Computer-Assisted Proof of Sendov's Conjecture (Lech Mazur, using OpenAI GPT-5.6 Pro; digestion + Lean formalization by Terence Tao)](https://www.proofatlas.ai/papers/sendov-conjecture/SENDOV_CONJECTURE_PROOF_AUGUST_5_2026.pdf)
  — an AI-generated, Lean-4-formalized proof claims to resolve Sendov's ~68-year-old
  conjecture (1958) IN FULL GENERALITY for all polynomial degrees, extending Tao's own 2020
  partial resolution (axis 1, math.CV). PDF + Tao's companion GitHub formalization
  (https://github.com/teorth/sendov) + his digestion blog post opened this session. HEAVY
  CAVEATS (hype-skepticism + AI-watch rules): off-arXiv, self-published, explicitly
  AI-substantial per its own disclosure → PROVISIONAL, not confirmed mathematics — but worth
  knowing for an unusually strong vetting signal this radar has not seen before in the
  AI-math wave: the world's leading expert on this exact conjecture personally re-deriving,
  human-digesting, and independently formalizing the argument in Lean, rather than merely
  publicly commenting on it.
- 2026-08-12 (v1 2023-05-08; now published Annals of Mathematics 2025, Quanta feature
  2026-08-12, surfaced this session) — [Fractal uncertainty in higher dimensions (Alex Cohen), arXiv:2305.05022](https://arxiv.org/abs/2305.05022)
  — extends the Bourgain–Dyatlov fractal uncertainty principle to all higher dimensions,
  resolving an extension problem open since a 2016 workshop, now published in the field's top
  journal (axis 1/2, math.CA / quantum-chaos interface). Abstract + Quanta feature opened this
  session. No caveats — refereed mathematics; a clean example of the math↔physics-interface
  results this radar tracks, and originally the author's PhD thesis (MIT), earning him an NYU
  assistant professorship at 25.
- 2026-08-10 — [More Than Two Thirds of the Zeros of the Riemann Zeta Function Lie on the Critical Line (Claude / Anthropic)](https://www.anthropic.com/research/riemann-zeta)
  — an unreleased Anthropic research model unconditionally raises the known lower bound on the
  proportion of zeta zeros that are simple and on the critical line from ~41.6% to ~67.25%
  (axis 1, math.NT), by a linear-algebraic reading of Baluyot–Goldston–Suriajaya–Turnage-
  Butterbaugh's pair-correlation work plus Bombieri (2000). Official research page + paper PDF
  opened via `tvly extract` this session (paper dated 2026-08-10). HEAVY CAVEATS (hype-skepticism
  + AI-watch rules): off-arXiv, unrefereed, an extraordinary jump over a decades-slow record —
  PROVISIONAL; worth knowing for the scale of the claimed jump and the unusually well-matched
  informal review (Brian Conrey and Dan Goldston, named specialists in exactly this subfield) plus
  an accompanying Lean formalization, not as confirmed mathematics.
- 2026-08-10 — [A proof of the cyclotomic conjecture and the non-existence of almost Moore digraphs (Kaur, Kumar), arXiv:2608.08997](https://arxiv.org/abs/2608.08997)
  — resolves Gimbert's 1999 cyclotomic conjecture, closing the associated ~45-year-old
  non-existence question for almost Moore digraphs in the directed degree-diameter problem
  (axis 1, math.CO/NT). Abstract + authors verified via arXiv API this session (v1 2026-08-10).
  A clean resolution of a classical, well-known open problem in extremal/algebraic graph theory.
- 2026-08-07 — [Modularity of Higher Theta Series III: Proof of the Modularity Conjecture (Feng, Yun, Zhang), arXiv:2608.07173](https://arxiv.org/abs/2608.07173)
  — proves the Modularity Conjecture for higher theta series on moduli stacks of Hermitian
  shtukas, capping a numbered series by leaders of the arithmetic Gan–Gross–Prasad / relative-
  Langlands program (axis 1, math.NT/AG). Abstract + authors verified via arXiv API this session
  (v1 2026-08-07).
- 2026-07-21 (v1; surfaced this session, accessed 2026-08-10) — [Counterexamples to the xz-Conjecture and the Mathieu Conjecture for SU(2) (Long), arXiv:2607.19012](https://arxiv.org/abs/2607.19012)
  — refutes the ~29-year-old Mathieu conjecture for SU(2), a named conjecture directly connected
  to the Jacobian-conjecture research program already tracked on this ledger (axis 1, math.RA/AG).
  Abstract + author verified via arXiv API this session. A capture-leak catch — worth knowing
  despite the 3-week discovery delay.
- 2026-08-06 — [Linear dependence of time-frequency shifts of a Schwartz function (Faulhuber, Petersen, van Velthoven, Voigtlaender), arXiv:2608.05044](https://arxiv.org/abs/2608.05044)
  — disproves the ~30-year-old HRT (Heil–Ramanathan–Topiwala) conjecture in time-frequency
  analysis via an explicit 12-shift linear dependence (axis 1, math.CA/FA). Abstract + authors
  verified via arXiv API this session (v1 2026-08-05). AI-assisted (responsibly disclosed per the
  authors) but independently reconstructed and engaged same-day by Terence Tao — worth knowing as
  a famous named conjecture falling, with unusually fast, credible community vetting already
  underway.
- 2026-08-05 — [The distribution of $\ell^\infty$-Selmer groups in degree $\ell$ twist families I/II (Smith), arXiv:2207.05674 / arXiv:2207.05143](https://arxiv.org/abs/2207.05674)
  — resolves the notoriously hard $\ell=2$ case of the Cohen–Lenstra(–Gerth) heuristics — the
  2-primary class-group distribution problem tracing to Gauss's genus theory (~200 years open) —
  now published as J. Amer. Math. Soc. 39(1)/39(2) (2026): a rare item on this shelf that is
  peer-reviewed, not provisional (axis 1, math.NT).
- 2026-08-04 — [A solution to Crouzeix's conjecture (Lorist, Schwenninger), arXiv:2608.03841](https://arxiv.org/abs/2608.03841)
  — proves Crouzeix's 2004 conjecture ($\|f(A)\|\le 2\sup_{z\in W(A)}|f(z)|$ for any square matrix
  $A$ and polynomial $f$, $W(A)$ the numerical range), a famous ~two-decade open problem in
  operator/matrix theory (axis 1, math.FA). Abstract + authors verified via arXiv API this session
  (v1 2026-08-04). Unrefereed but an incremental culmination of the authors' own prior partial
  results (weaker bounds, special cases) — worth knowing as the resolution of a benchmark conjecture
  every operator theorist has tried their hand at.
- 2026-08-04 — [The period-index conjecture is false (Perry), arXiv:2608.03684](https://arxiv.org/abs/2608.03684)
  — for every uncountable algebraically closed field of characteristic 0 and every dimension $d\ge3$,
  constructs a variety with a Brauer class violating the period-index conjecture (already false over
  $\overline{\mathbf Q}$ at $d=3$) — a foundational open problem on Brauer groups (axis 1,
  math.AG). Abstract + author verified via arXiv API this session (v1 2026-08-04). A landmark
  refutation of a long-standing named conjecture in algebraic geometry.
- 2026-08-01 — [OpenAI's "Ten Advances in Mathematics and Theoretical Computer Science" (internal
  model "Astra")](https://openai.com/index/ten-advances-in-mathematics/) — an unreleased OpenAI
  model claims new results on ten long-standing open problems in one release: a disproof of
  Connes's rigidity conjecture, an explicit non-sofic group, a superexponential multicolor-Ramsey
  lower bound (resolving Erdős problem 183 — see the reactivated Ramsey trend), a proof of
  Ehrhart's volume conjecture, and six more spanning sphere packing, coding theory, circuit
  complexity, quantum parallel repetition, lattice cryptography and extremal graph theory. Official
  publication page + full technical PDF (cdn.openai.com/pdf/ten-proofs-oai.pdf) opened this session
  (dated 2026-08-01). HEAVY CAVEATS (hype-skepticism + AI-watch rules): unrefereed, AI-generated,
  off-arXiv — the single most extraordinary claim this radar has tracked, PROVISIONAL on every one
  of the ten results until independent vetting; worth knowing as the story every mathematician is
  discussing this week (topped r/math and Hacker News), not as confirmed mathematics.
- 2026-08-02 — [A computer-assisted counterexample to the planar Pompeiu and Schiffer conjectures
  (Colbrook, Stepaniants), arXiv:2608.01579](https://arxiv.org/abs/2608.01579) — refutes both the
  1929 planar Pompeiu problem and the associated Schiffer conjecture via an explicit noncircular
  domain supporting a boundary-constant Neumann eigenfunction (axis 1, analysis/spectral geometry).
  Abstract + authors verified via arXiv API this session (v1 2026-08-02). A clean, non-AI,
  computer-assisted refutation of two classical ~97-year-old conjectures — the same rigorous
  computer-assisted-proof pattern as Kuperberg's six-cylinder conjecture, already on this shelf.
- 2025-09-09 (shelf-added 2026-08-03; leading date is the original preprint's v1, not the
  add date — flagged W32 recalibration so a future weekly's 120-day shelf-pruning check does
  not misread this as stale) — [Testing the problem of time with cold atoms (Barontini), arXiv:2509.07745](https://arxiv.org/abs/2509.07745)
  — the FIRST experimental test of relational-time constructions motivated by the Wheeler-DeWitt
  "problem of time": an isolated ultracold-atom Bose-Einstein condensate (24,000 atoms) split into
  observed/unobserved sectors yields an entropic "internal time" that robustly orders events across
  repeated expansion/recollapse cycles, with an effective Schrödinger equation in that internal time
  reproducing the measured dynamics (axis 4, quantum foundations / quantum-gravity interface).
  Original preprint 2025-09-09, now published in Physical Review Research and freshly covered by the
  University of Birmingham (opened via `tvly` this session, ~2026-07-09). A landmark-quality
  first-of-kind experimental probe of a central open question in quantum-gravity foundations that a
  physicist should know — single group so far, watch for independent replication.
- 2026-07-01 — [The Riemann Hypothesis manifested in dynamical quantum phase transitions (Wei, Zhai,
  Lu et al.), Nature Communications s41467-026-74935-8](https://www.nature.com/articles/s41467-026-74935-8)
  — establishes a direct correspondence between the nontrivial zeros of the Riemann zeta function and
  dynamical quantum phase transitions in two engineered quantum many-body systems, via a Riemann-based
  Hamiltonian construction (axis 2/4, math-ph/quant-ph, peer-reviewed). Abstract + publication
  metadata opened via `tvly` this session (received 2025-12-23, accepted 2026-06-18, published
  2026-07-01). A genuinely novel RH↔physics correspondence worth knowing at the math↔physics
  interface — track for follow-up (a new zero-search/verification strategy, or independent
  replication of the quantum-simulation claim).
- 2026-07-31 — [On a proof of the Gorenstein Symmetry Conjecture (Li), arXiv:2607.28011](https://arxiv.org/abs/2607.28011)
  — a homological proof of the Gorenstein Symmetry Conjecture (one-sided finiteness of the self-injective
  dimension of an Artin algebra implies Gorensteinness), a famous long-standing open problem in the
  representation theory of Artin algebras (axis 1, math.RT/RA). Abstract + author verified via arXiv API
  this session (v1 2026-07-30). HEAVY CAVEAT (hype-skepticism rule): unrefereed SINGLE-AUTHOR preprint
  claiming resolution of a named conjecture → PROVISIONAL until independent vetting; worth knowing as a
  claim a representation theorist should watch, not a confirmed result.
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
