# Trend ledger — Math-Physics Radar

Last updated: 2026-11-27

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(60+ days quiet — domain cadence; AGENTS.md § Domain cadence) ; `declining` (the field moved on). Confidence: `low | medium | high`.
Trend bar: ≥3 independent sources (different orgs/author groups) + ≥1 concrete artifact.

## Active trends

### Ramsey-number lower-bound breakthroughs (extremal combinatorics)
- stage: accelerating | confidence: medium | first_seen: 2026-07-03 | last_evidence: 2026-10-05
- what: A 2025–2026 wave of independent breakthroughs on Ramsey-number LOWER bounds, breaking
  decades-old barriers. Ma–Shen–Xie broke the Erdős probabilistic-method barrier for off-diagonal
  graph Ramsey numbers r(ℓ, Cℓ); Bradač then pushed the classical off-diagonal r(s,k) lower bound to
  match the 90-year-old Erdős–Szekeres upper bound up to polylog (first exponent improvement since
  Spencer 1977); parallel work sharpens these and extends to hypergraph Ramsey numbers. Preprints —
  strong but not yet fully refereed; track the vetting.
- evidence:
  - 2025-07-17 — https://arxiv.org/abs/2507.12926 — Ma, Shen, Xie, "An exponential improvement for Ramsey lower bounds": first exponential improvement over Erdős' 1947 bound for r(ℓ, Cℓ) (abstract verified this session).
  - 2026-04-27 — https://arxiv.org/abs/2604.23986 — Du, Hu, Liu, Wang, "A double-exponential lower bound for r₄(5,n)": hypergraph Ramsey, r₄(5,n) ≥ 2^{2^{cn^{1/7}}} (abstract via arXiv API this session).
  - 2026-05-25 — https://arxiv.org/abs/2605.25843 — Lin, Niu, "Sharper Ramsey lower bounds from refined Gaussian estimates": sharpens the Ma–Shen–Xie off-diagonal bound (abstract via arXiv/tvly this session; v1 2026-05-25, W44 version-history spot-check: silently revised to v2, updated 2026-07-02 — no new group/claim, same author/result, folded in for the record).
  - 2026-05-27 — https://arxiv.org/abs/2605.28793 — Bradač, "Off-diagonal Ramsey numbers": r(s,k) ≥ Ω(k^{s-1}/(log k)^{2s-4}), matching Erdős–Szekeres up to polylog, improving Spencer 1977 (abstract via arXiv API this session).
  - 2026-08-03 — https://arxiv.org/abs/2608.02537 — Steiner, "Multicolor Ramsey numbers of odd cycles are superexponential": extends a claimed OpenAI-model ("Astra") superexponential k-color triangle Ramsey lower bound (R_k(3)=k^Θ(k), OpenAI's "Ten Advances" announcement, queued below) to multicolor Ramsey numbers of fixed odd cycles, R_k(O_p) ≥ (log^{(p-1)}k)^{k/3-o(k)} for every fixed p (abstract + author via arXiv API this session, v1 2026-08-03; W41 version-history spot-check: silently revised to v2, updated 2026-09-07 — no new group/claim, same author/result, folded in for the record).
  - 2026-08-22 — https://arxiv.org/abs/2608.21769 — Ihringer, Mattheus, "An improved algebraic construction for Ramsey numbers": explicit algebraic construction giving R(s,t) ≥ t^{(1-o(1))log s/log(log s+1)} uniformly for 3≤s≤t, improving the s-dependence in the Alon–Pudlák off-diagonal construction; first explicit construction with R(s,t) ≥ t^c for fixed s and c>2 (e.g. R(33,t) ≥ t^{2.1-o(1)}), also improving the diagonal case. Abstract + authors verified via arXiv API this session (v1 2026-08-22). A SIXTH independent author group (Sam Mattheus, of the already-staged sammattheus.wordpress.com source-discovery candidate, co-authoring a primary directly on this trend for the first time).
  - 2026-09-22 — https://arxiv.org/abs/2609.26563 — Du, Hu, Liu, Wang, "The Erdős–Hajnal hypergraph Ramsey problem for r₄(6,n)": the SAME group as the trend's r₄(5,n) evidence line (2604.23986) extends their own method to prove r₄(6,n) ≥ 2^{2^{cn}} — as a consequence, CONFIRMS THE FULL Erdős–Hajnal hypergraph-Ramsey conjecture for k=4 (previously only the s≥k+3 cases were known, via Mubayi–Suk and Conlon–Fox–Sudakov). Own-group escalation, not a new independent group, but a substantially stronger result (a full named-conjecture resolution, not just a lower-bound improvement) on the same tracked sub-theme. Found via a Semantic Scholar citation chase on the trend's own Ma–Shen–Xie anchor (this week's Amendment G pass) — missed 4 days by the daily sweep (title has no obvious Ramsey-lower-bound keyword match). Abstract + authors verified via direct arXiv page this session (v1 2026-09-22).
  - 2026-10-05 — https://arxiv.org/abs/2610.06081 — Verbeken, "Polynomial families of incident flags and explicit off-diagonal Ramsey graphs": explicit off-diagonal Ramsey graph construction from polynomial families of incident point–hyperplane flags, directly extending Bradač's construction (cites Bradač 2605.28793 by name). A NINTH independent author/group on this sub-theme. Found via this week's Amendment G Semantic Scholar citation chase on the Bradač anchor; abstract + author verified via direct arXiv page this session (v1 2026-10-05).
  - 2026-10-03 — https://arxiv.org/abs/2610.06969 — Kandasamy, Zhou, Segal, "Improved Explicit and Algorithmic Lower Bounds for r(5,t)": explicitly modifies Bradač's construction (cites Bradač 2605.28793 by name) to give r(5,t)=Ω(t^{7/4}) and, via a Coulter–Matthews-polynomial pruning, a deterministic polynomial-time r(5,t)=Ω(t^{20/11-ε}) construction. A TENTH independent author/group on this sub-theme. Found via this week's Amendment G Semantic Scholar citation chase on the Bradač anchor; abstract + authors verified via direct arXiv page this session (v1 2026-10-03).
- notes: ≥4 independent author groups on one sub-theme (Ma–Shen–Xie; Bradač; Du–Hu–Liu–Wang; Lin–Niu) + concrete artifacts → clears the trend bar. Community framing: Quanta ("Erdős method upgrade", 2026-06-26) and Gil Kalai / Sam Mattheus blogs ("a sensational Ramsey breakthrough by Bradač"). Ma–Shen–Xie also on `study_shelf`. Watch for referee outcomes and whether the diagonal r(k,k) barrier is next.
  - 2026-W39 recalibration (Amendment G citation-chase catch): HELD accelerating/medium; last_evidence
    advances 2026-08-22 → 2026-09-22 (Du–Hu–Liu–Wang's own r₄(6,n) full-conjecture resolution, above).
    Semantic Scholar "cited by" chase on the Ma–Shen–Xie anchor (2507.12926, 22 citing papers reviewed)
    also surfaced Fan, Li, Lin, Ning, "An improved double-exponential lower bound for r₄(5,n)"
    (arXiv:2605.04105, 2026-05-04) — an independent-author-list improvement on the SAME r₄(5,n) bound,
    but co-authored by Lin Qizhong, who is already one of this trend's tracked authors via the
    off-diagonal Lin–Niu evidence line (2605.25843) — judged an extension of an already-counted
    author's portfolio, not a clean 7th independent group, so queued in its own right rather than
    counted toward group-count promotion (honesty over the independent-group tally). No referee/
    vetting outcome on any of the six tracked preprints (arXiv version-history check this session:
    only the three Stanley-Gasharov-adjacent papers and the Marton exponent paper show v2s, all
    predating this week — see that trend's own note). Not promoted to a 7th-group confidence bump;
    confidence held medium (unrefereed-preprint caution unchanged). Watch continues for a genuine 7th
    independent group or a referee outcome.
  - 2026-09-22 — https://arxiv.org/abs/2512.17718 — Hunter, Milojević, Sudakov, "Gaussian random graphs
    and Ramsey numbers": an independent SIMPLER/alternate proof of the Ma–Shen–Xie exponential
    improvement, via Gaussian random graphs — a SEVENTH independent author group, predating this
    trend's own creation (2025-12-19) but never previously captured. Found via this week's Amendment G
    citation-chase on the Ma–Shen–Xie anchor (22 citing papers reviewed via Semantic Scholar).
  - 2026-01-21 — https://arxiv.org/abs/2601.15183 — Campos, Pohoata, "An update on multicolor Ramsey
    lower bounds": building on Conlon–Ferber–Wigderson and Sawin, an EIGHTH independent author group
    improving multicolor Ramsey lower bounds via independent-set density bounds in K_t-free graphs —
    same citation-chase catch, also predating this trend's creation, never previously captured.
  - 2026-W27 through W37 recalibration history (daily "no new lower-bound item found" entries
    plus the W27-W35 dormancy/reactivation/promotion cycle and the 2026-09-03 daily through W37
    recalibrations) RELOCATED to `logs/trend_history.md` (W27-W35 moved 2026-10-24 at W43;
    2026-09-03 through W37 moved 2026-11-07 at W45, Amendment L applied) — moved verbatim,
    unaltered; see that file for the full day-by-day record.
  - 2026-W38 recalibration: HELD accelerating/medium. last_evidence 2026-08-22 is 28 days old, well
    inside the 60-day window (dormancy line 2026-10-21 unchanged). No 7th independent group or
    referee/vetting outcome surfaced across the week's dailies (09-14→09-18, each keyword-sweeping
    fresh math batches — a landmark-dense week on OTHER sub-themes, incl. FLT's Lean formalization,
    Erdős-Sós, Sylvester, Kusner, Chvátal, Pach-Tardos, but nothing on Ramsey-number lower bounds
    specifically). Confidence held medium (doubled unrefereed-preprint caution on Steiner's result
    stands). Not promoted (no fresh W38 velocity).
  - 2026-W40 recalibration: HELD accelerating/medium. last_evidence 2026-09-22 is 11 days old, well
    inside the 60-day window (dormancy line 2026-11-21). No 7th independent group or referee/vetting
    outcome surfaced across the week's dailies (09-28→10-02, each scanning fresh math batches — a
    landmark-dense week on OTHER sub-themes, incl. Kahn-Saks, Cassels-Swinnerton-Dyer, Ehlers-Kundt,
    inhomogeneous Duffin-Schaeffer, Graham's rearrangement, the Hopf problem, Lehmer's permutation
    conjecture, but nothing on Ramsey-number lower bounds specifically). This week's Amendment G
    citation-chase pass was spent on the Komlós/Beck-Fiala trend instead (see that trend's note) —
    rotate the chase back to this trend's own anchors next time. Confidence held medium (doubled
    unrefereed-preprint caution on Steiner's result stands). Not promoted.
  - 2026-W41 recalibration: Amendment I version-history spot-check — 2608.02537 (Steiner) found
    silently revised to v2 (updated 2026-09-07, ~1 month unnoticed), same author/result, no new
    group, folded into its evidence line; the other 6 tracked preprints (2507.12926, 2604.23986,
    2605.25843, 2605.28793, 2608.21769, 2609.26563) show no v-update beyond what prior checks
    already found. Amendment G citation-chase (rotated back to this trend per the W40 note) on the
    Ma–Shen–Xie anchor (22 citing papers) surfaced TWO genuine capture-gap catches — Hunter–
    Milojević–Sudakov's independent alternate proof (2512.17718, Dec 2025) and Campos–Pohoata's
    multicolor-lower-bound update (2601.15183, Jan 2026) — a SEVENTH and EIGHTH independent group,
    both predating this trend's own creation and missed until now (titles carry no obvious
    "Ramsey lower bound" keyword match — the same title-blind-miss pattern as the capture-gap
    pattern flagged in recent weeklies). Evidence cap still has room (9/10), no rotation needed.
    Several more citing papers on Ramsey-adjacent sub-themes (Erdős–Rogers function variants,
    Ramsey goodness, zero-sum/coprime Ramsey numbers) were below-bar for this trend and routed to
    `observation_queue` instead (see queue). last_evidence 2026-09-22 unchanged (no later actual
    date surfaced). Group count now 8; still not promoted to `mainstreaming` (no standard-practice-
    adoption signal, only group count/pace).
  - 2026-W42 recalibration (Amendment I version-history spot-check, re-run): THREE further silent
    revisions found that the W41 pass's own "no v-update" conclusion had missed — 2507.12926
    (Ma–Shen–Xie) to v2, updated 2026-04-26 (same title/authors; this was already correctly noted
    on this ledger's own `study_shelf` entry for this paper, just never propagated back to this
    trend's evidence/notes — now synced); 2605.28793 (Bradač) to v3, updated 2026-06-16 (same
    title/author); 2512.17718 (Hunter–Milojević–Sudakov) to v2, updated 2026-05-18 (same title/
    authors). All three predate this trend's own last_evidence (2026-09-22) and are same-
    author/same-result revisions — no new groups, no last_evidence change. Also CORRECTED a date
    error (not a revision): the W41 citation-chase note recorded Campos–Pohoata's 2601.15183 as
    "2026-01-08," but the paper's actual (single-version) date is 2026-01-21 — fixed in the
    evidence line above. Group count unchanged at 8; not promoted.
  - 2026-W44 recalibration (Amendment I version-history spot-check, re-run): a FOURTH silent
    revision found that both the W41 and W42 passes missed — 2605.25843 (Lin–Niu) to v2, updated
    2026-07-02, same title/authors, predating this trend's last_evidence (2026-09-22). No new
    group, no last_evidence change; folded into the evidence line for the record. The other seven
    tracked preprints show no v-update beyond what prior checks already found. Group count
    unchanged at 8; not promoted.
  - 2026-W44 recalibration (Amendment G citation-chase, rotated to this trend's Bradač anchor,
    2605.28793, per the W42/W43 rotation precedent): a fresh Semantic Scholar "cited by" pass (14
    citing papers reviewed) surfaced a NINTH and TENTH independent group — Verbeken (2610.06081)
    and Kandasamy–Zhou–Segal (2610.06969), both explicitly extending Bradač's construction by name
    — appended as evidence above (cap now 9/10, no rotation needed); last_evidence advances
    2026-09-22 → 2026-10-05. Five further citing papers correctly NOT counted as new groups —
    same-author-portfolio escalations by already-tracked authors: Lin Qizhong again (2610.17891,
    with Zhang), Bradač again (2609.37987, with Janzer–Sarkar), Ihringer again (2609.32461, with
    Han–Van Maldeghem), Hunter–Milojević–Sudakov again (2610.03358, with Gvozdic), and Lin again
    (2607.00732, with Dai) — logged for engagement, not independently re-queued (same-author
    caution, consistent with the Fan–Li–Lin–Ning precedent). One (2610.15293, Kai-Zhe Chen, "a
    note on" 2610.17891) and one off-theme upper-bound paper (2609.28075, Balko–Grinerová, already
    tracked on the Harary–Hill trend) excluded as below-bar/off-theme. Group count now 10; not
    promoted to `mainstreaming` (group-count/pace signal only, no standard-practice adoption).

### Non-invertible (categorical) symmetries in QFT (generalized global symmetries)
- stage: accelerating | confidence: high | first_seen: 2026-07-27 | last_evidence: 2026-11-18
- what: A maturing research direction extending 't Hooft-anomaly / global-symmetry analysis to
  NON-INVERTIBLE ("categorical"/"generalized") symmetries in quantum field theory — fusion-category
  symmetry defects applied to lattice anomalies, 2d CFT constructions, and now a systematic (2+1)d
  gapless-phase classification via the Symmetry TFT. Three fully independent author groups now hold
  concrete artifacts on this sub-theme, clearing the ≥3-group + artifact convergence bar today.
- evidence:
  - 2026-10-20 — https://scipost.org/SciPostPhysCore.9.4.069 — Bhattacharyya, Ghosh, Pal, Santara,
    "On the resolution of categorical symmetries in (non-) unitary rational CFTs": a further fully
    independent author group (independent of all ~18 already tracked), deriving a general categorical
    symmetry-resolved entanglement entropy formula for 2d RCFT (diagonal and non-diagonal, unitary and
    non-unitary) without invoking the SymTFT construction. Title/authors/abstract/date verified via
    the SciPost publications API this session. Oldest evidence line (2026-08-20, Maruyoshi-Moon-Song)
    dropped to hold the 10-item cap.
  - 2026-09-28 — https://scipost.org/SciPostPhysCore.9.3.063 (arXiv:2511.18969, Maity,
    Tripathi, Nevidomskyy, Rice Univ.) + https://scipost.org/SciPostPhys.21.3.078 (arXiv:2601.08615,
    Inamura, Ohyama): a TWELFTH fully independent author group (Maity–Tripathi–Nevidomskyy,
    extending non-invertible duality constructions to (2+1)d lattice models with subsystem
    symmetries) now on file via SciPost's community-refereed publication of both papers this week;
    Inamura–Ohyama's companion paper (generalized cluster-state SPT models with non-invertible
    symmetries) is NOT counted as a new group — Inamura already tracked via the Bhardwaj et al.
    group (2026-07-27 evidence, now rotated off the 10-line cap) — same author-portfolio caution as
    the Ramsey trend's Lin Qizhong case. Both papers pre-date this week (arXiv v1 2025-11/2026-01)
    but were caught only now via their SciPost publication dates — title/authors verified via the
    arXiv API this session (2511.18969 W44 version-history spot-check: silently revised to v2,
    updated 2026-10-26 — same authors/result, last_evidence advanced accordingly, see note below).
    DROPPED the 2026-08-19 Flores-Calderón evidence line to hold the 10-item
    cap (still tracked in notes/group-count history above).
  - 2026-08-24 — https://scipost.org/SciPostPhysCore.9.3.048 — Graf, Surace, Berg, Moroz, "The
    Ising dual-reflection interface: $\mathbb Z_4$ symmetry and Majorana strong zero modes": a
    SEVENTH fully independent author group (independent of Oishi–Ebisu, Antunes–Rong, Bhardwaj et
    al., Ueda et al., Flores-Calderón–Pollmann–Knap, and Maruyoshi–Moon–Song), on the lattice side
    — a non-invertible symmetry emerges in closed geometry at an interface combining a
    Kramers-Wannier transformation with spatial reflection in the transverse-field Ising chain,
    alongside a discrete $\mathbb Z_4$ symmetry realized via Majorana strong zero modes. SciPost
    Physics Core (community-refereed, acceptance date 2026-07-20); title/authors/abstract/DOI
    verified via the SciPost API this session.
  - 2026-11-09 — http://link.aps.org/doi/10.1103/hl1d-99hv — Fidkowski, Xu, Zhang,
    "Noninvertible Bosonic Chiral Symmetry on the Lattice" (Phys. Rev. X 16, 041036): a further
    fully independent author group, constructing a continuous chiral symmetry in a 3D quantum
    rotor model and showing that gauging the charge symmetry yields noninvertible, duality-like
    lattice operations. Title/authors/DOI verified via the PRX RSS feed this session. Oldest
    evidence line (2026-08-22, Kobayashi et al.) dropped to hold the 10-item cap (still tracked
    in notes/group-count history above).
  - 2026-08-25 — https://arxiv.org/abs/2608.24385 — Ahn, Bajnok, Elek, "New RG flows between
    non-Unitary CFTs from exact massless scattering theories": a NINTH fully independent author
    group (independent of all eight above), on a new sub-application — constructs an infinite
    family of integrable RG flows (via massless S-matrix bootstrap / thermodynamic-Bethe-ansatz
    solutions) from higher-fusion-level minimal models to non-unitary Virasoro minimal models
    (including a flow to the Yang-Lee CFT), and shows a family of non-invertible Verlinde defect
    lines is preserved along the flows — the first engagement on this trend from the
    integrable-QFT/TBA sub-community. Abstract + authors verified via arXiv API this session
    (v1 2026-08-25; W41 version-history spot-check: silently revised to v2, updated 2026-09-29 —
    same author group/result, no new group; last_evidence advanced to this date for the record;
    W47 version-history spot-check: a further silent revision to v3, updated 2026-11-18 — same
    author group/result, no new group, last_evidence advanced accordingly).
  - 2026-09-04 — https://arxiv.org/abs/2609.03043 — Volpato, "Monstrous parafermionic defects and
    other non-invertible symmetries in chiral CFTs": a TENTH fully independent author (independent
    of all nine above), constructing non-invertible topological defects (parafermionic and
    beyond) in chiral CFTs connected to Monstrous Moonshine, extending the non-invertible-defect
    toolkit to chiral/holomorphic CFTs. Abstract + author verified via arXiv API this session
    (v1 2026-09-02, surfaced in today's fresh hep-th/physics batch; W41 version-history
    spot-check: silently revised to v2, updated 2026-09-11 — same author/result, no new group).
  - 2026-09-06 — https://arxiv.org/abs/2609.06751 — Ravindran, Eck, Chen (Caltech), "Ginzburg-Landau
    Theory for Non-Invertible Symmetry-Breaking Transitions": an ELEVENTH fully independent author
    group (independent of all ten above), develops a Symmetry-TFT-based field-theoretic
    (Ginzburg-Landau) description of critical points for symmetry-breaking transitions of
    non-invertible symmetries in (1+1)d, identifying the algebra of local order parameters from the
    Lagrangian algebra. Abstract + authors verified via arXiv API this session (v1 2026-09-06,
    surfaced in today's fresh cond-mat.str-el batch); oldest evidence line (2604.02856,
    Oishi–Ebisu) dropped to hold the 10-item cap, per `radar-ledger-update`.
  - 2026-09-09 — https://arxiv.org/abs/2609.09550 — Chen, Jia, "On general background of quantum
    non-invertible symmetry in 2D": a TWELFTH fully independent author group (independent of all
    eleven above), develops a general framework for computing partition functions of the dual
    Rep(G) theory obtained by gauging a non-abelian symmetry G, in arbitrary non-invertible-symmetry
    (topological-defect-network) backgrounds, with worked examples for finite groups and a formal
    extension to compact Lie groups (Rep(SU(2))). Abstract + authors verified via arXiv API this
    session (v1 2026-09-09, surfaced in today's fresh hep-th batch); oldest evidence line
    (2026-07-06, Antunes–Rong) dropped to hold the 10-item cap.
  - 2026-09-09 — https://scipost.org/SciPostPhys.21.3.058 — Kaidi, Shi, Shimamori, Sun, "The SymTFT
    for N-ality defects: Part I" (SciPost Physics, published 2026-09-09): a THIRTEENTH fully
    independent author group (independent of all twelve above), constructs the Symmetry TFT for
    theories with an N-ality extension of a discrete Abelian symmetry group, determining boundary
    F-symbols from the choice of bulk Z_N symmetry (Tambara-Yamagami-like structures for prime N).
    Title/authors/abstract/dates verified via the SciPost publications API this session (API healed
    this session — see coverage log; individual article pages remain Anubis-blocked). Oldest
    evidence line (2026-07-23, Bhardwaj et al.) dropped to hold the 10-item cap.
  - 2026-09-10 — https://arxiv.org/abs/2609.11895 — Ohki, Uemura, "Non-invertible Selection Rules
    from Generalized Discrete Gauging of Finite Non-Abelian Symmetries": a FOURTEENTH fully
    independent author group (independent of all thirteen above), develops a general framework for
    non-invertible selection rules from discrete H-gauging of non-Abelian discrete global symmetries,
    with non-Abelian multidimensional-irrep effects central to the construction. Abstract + authors
    verified via arXiv API this session (v1 2026-09-10, surfaced in today's fresh hep-th/hep-ph
    batch; W41 version-history spot-check: silently revised to v2, updated 2026-09-25 — same
    author group/result, no new group). Oldest evidence line (2026-08-07, Ueda et al., Nature
    Physics) dropped to hold the 10-item cap.
- 2026-W31 through W37 recalibration history (the out-of-order 09-09/09-10/09-11/W37 notes plus
  the creation note's nested W31-through-09-08 chronological sub-list) RELOCATED to
  `logs/trend_history.md` 2026-11-07 (W45, Amendment L applied) — moved verbatim, unaltered; see
  that file for the full day-by-day record.
- notes: 2026-07-27 (daily, PROMOTION): 2604.02856 and the Antunes–Rong SciPost item had sat in the
  `observation_queue` since 07-05/07-07 as a 2-group "forming, below the ≥3 bar" pair (flagged again
  in the W30 report's "convergence to watch"); today's fresh SciPost sweep surfaced Bhardwaj et al.
  (Schäfer-Nameki's group, fully independent of both prior groups — verified via author lists this
  session) as a third independent artifact → promoted to a `seed` trend per the convergence-check rule
  (daily.md §4). Confidence LOW (first day as a trend; no hype-skepticism caveat needed — ordinary
  refereed/community-refereed theoretical-physics output, not an AI-assisted claim). Watch for a 4th
  group, citations of the Bhardwaj et al. framework, and any connection to the separately-tracked
  deconfined-criticality queue thread (2607.00762 / 2607.01815).
  - 2026-W38 recalibration: HELD accelerating/high. last_evidence 2026-09-10 is 9 days old, nowhere
    near the 60-day line. No 15th independent group or the still-outstanding explicit
    lattice/continuum cross-citation surfaced across the week's dailies (09-14→09-18, each
    keyword-sweeping fresh hep-th/hep-ph/gr-qc/math-ph/quant-ph/cond-mat batches and the SciPost
    API — one adjacent fusion-category construction paper, 2609.15986, checked and correctly
    excluded 09-16, now queued in its own right per this week's capture-leak fix above). Confidence
    held at the ceiling — still the strongest of the four active trends by group count (fourteen)
    and venue breadth. Not promoted to `mainstreaming`. Watch for a 15th group or the cross-citation.
  - 2026-W40 recalibration: HELD accelerating/high. last_evidence 2026-09-10 is 23 days old, well
    inside the 60-day window. No 15th independent group or the still-outstanding explicit
    lattice/continuum cross-citation surfaced across the week's dailies (09-28→10-02; SciPost API
    and fresh hep-th/hep-ph/gr-qc/math-ph/quant-ph/cond-mat batches both routine, nothing on this
    sub-theme per the daily coverage log). Confidence held at the ceiling. Not promoted.
  - 2026-W41 recalibration (Amendment I version-history spot-check): of the 7 tracked preprints,
    THREE were found silently revised with no evidence-line annotation — 2608.24385 (Ahn-Bajnok-
    Elek) to v2 updated 2026-09-29 (the latest actual date on file for this trend, postdating the
    recorded last_evidence — last_evidence advanced 2026-09-28 → 2026-09-29 accordingly), 2609.03043
    (Volpato) to v2 updated 2026-09-11, and 2609.11895 (Ohki-Uemura) to v2 updated 2026-09-25 (both
    older than last_evidence, no date impact). All three are same-author/same-result revisions, not
    new groups — no stage/confidence impact. No 15th independent group found. Not promoted.
  - 2026-W42 recalibration (Amendment G citation-chase, rotated to this trend per the W41 note):
    an INSPIRE-HEP citation chase on the trend's two foundational anchors (Bhardwaj–Gai–Huang–
    Inamura–Schäfer-Nameki–Tiwari–Warman, arXiv:2503.12699, the paper that triggered this trend's
    own 2026-07-27 creation; and Oishi–Ebisu, arXiv:2604.02856, the earliest-dated tracked group,
    now rotated off the 10-item evidence cap) — 37 citing papers reviewed — surfaced THREE further
    independent author groups, all pre-dating this trend's own creation by over a year and never
    previously captured (the same backlog-miss pattern as the Ramsey trend's W41 catches):
    Aksoy–Wen (MIT; arXiv:2503.21764, 2025-03-27, "Phases with non-invertible symmetries in
    1+1D... as duality automorphisms" — a symTO/Lagrangian-condensable-algebra classification of
    1+1D gapped phases under non-invertible symmetries); Lu–Xu–You (UC San Diego; arXiv:2505.00673,
    2025-05-01, strange correlators/string order parameters diagnosing non-invertible-SPT phases);
    Cordova–García-Sepúlveda–Ohmori (arXiv:2504.03614, 2025-04-04, non-invertible one-form
    symmetries at Higgsing-transition fixed points of Chern–Simons matter theories). All three
    confirmed independent of every already-tracked group (no shared authors, checked by name
    against this trend's full roster) and of each other. Group count now AT LEAST 18 (evidence-cap
    rotation means the exact tracked list undercounts the true group count — this is itself a
    standing side-effect of the 10-item cap, not a correction). No stage change (already at the
    `accelerating`/`high` ceiling; no standard-practice-adoption signal for `mainstreaming`).
    last_evidence unchanged (all three predate 2026-09-29). ~34 further citing papers reviewed and
    excluded — same-lineage follow-ups (Schäfer-Nameki/Tiwari/Warman/Gai co-authorships), already-
    tracked SciPost publications of already-counted preprints, or 2-group-symmetry papers (a
    distinct formalism, standing exclusion). No referee/vetting outcome on any of the 10 tracked
    preprints. Amendment I version-history spot-check (same session): 2601.08615 (Inamura–Ohyama,
    named in prose above with only a loose "2025-11/2026-01" date) silently revised to v3, updated
    2026-08-26 — same title/authors, not independently counted as a group either way, logged for
    the record.
  - 2026-10-26 (daily): today's SciPost API sweep surfaced a further independent author group
    (Bhattacharyya-Ghosh-Pal-Santara, SciPostPhysCore.9.4.069) — appended as evidence above; oldest
    evidence line dropped to hold the cap. Group count now 19+ (the evidence-cap rotation undercounts
    the true total, a standing side-effect already noted at W42). Stage HELD accelerating/high
    (already at the confidence ceiling, no mainstreaming-tier standard-practice-adoption signal
    found). last_evidence advances 2026-09-29 → 2026-10-20.
  - 2026-W44 recalibration (Amendment I version-history spot-check): TWO silent revisions found —
    2511.18969 (Maity–Tripathi–Nevidomskyy) to v2, updated 2026-10-26, which POSTDATES the
    recorded last_evidence (2026-10-20) — last_evidence advances 2026-10-20 → 2026-10-26
    accordingly, same title/authors, no new group; and 2503.21764 (Aksoy–Wen) to v2, updated
    2025-03-28 (one day after v1, predates last_evidence, no date impact). No new groups found on
    either; group count unchanged at 19+. Not promoted (no mainstreaming-tier signal).
  - 2026-11-12 (daily, evidence append): a 20th+ independent group (Fidkowski–Xu–Zhang, PRX)
    caught via today's PRX RSS sweep — continuous chiral symmetry in a 3D quantum rotor model,
    gauging charge symmetry yields noninvertible lattice operations. last_evidence 2026-10-26 →
    2026-11-09 (oldest evidence line, 2026-08-22 Kobayashi et al., dropped to hold the 10-item
    cap). Still `accelerating`/`high`, well short of a `mainstreaming` signal.
  - 2026-W47 recalibration (Amendment I version-history spot-check, full batch of every tracked
    id across the ledger): 2608.24385 (Ahn-Bajnok-Elek) found silently revised a second time, to
    v3 updated 2026-11-18 — same author group/result, no new group; last_evidence advances
    2026-11-09 → 2026-11-18 (the latest dated activity now on file for this trend). No 21st
    independent group found this session.

### Refutations of the Stanley-Gasharov claw-free Schur-positivity conjecture (algebraic combinatorics)
- stage: dormant | confidence: medium | first_seen: 2026-07-30 | last_evidence: 2026-07-29
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
  - 2026-W31 through the 2026-09-03 daily recalibration history (repeated "no 4th independent
    group found" checks during this trend's seed-stage watch) RELOCATED to `logs/trend_history.md`
    2026-10-24 (W43, Amendment L applied) — moved verbatim, unaltered; see that file for the
    full day-by-day record.
  - 2026-W36 recalibration: HELD seed/medium. last_evidence 2026-07-29 is 38 days old — well
    inside the 60-day window (dormancy line 2026-09-27), but now over five weeks quiet with no
    4th independent group and no referee/vetting outcome on any of the three tracked preprints.
    Confidence held medium (unrefereed, cross-verified computations; no fresh corroboration
    either way). Weakest of the four active trends — per the W35 forward bet, if nothing moves
    by early October this needs a real decision (accept a 3-group seed indefinitely, or let the
    60-day dormancy line take it).
  - 2026-09-07 (daily): first daily since 09-04. Fresh math.CO full in-scope category-rotation
    batch (2026-09-04→09-07, 168 fresh entries) scanned for Schur-positivity/claw-free items —
    none. arXiv-API metadata recheck of all three tracked preprints (2607.21508, 2607.26364,
    2607.27166): no fresh v-update — no referee/vetting outcome. No 4th independent group. Trend
    HELD seed/medium; last_evidence 2026-07-29 now 40 days old, still inside the 60-day window
    (dormancy line 2026-09-27, 20 days out).
  - 2026-09-08 (daily): no fresh arXiv batch past the 09-04 ceiling; the math.OC exploration-slot
    read (below) and the day's other captures (Alpöge-Buckmaster blowup, quantum-free-fall
    equivalence-principle test) are both off this trend's axis. No 4th independent group or
    referee/vetting outcome on the three tracked preprints. Trend HELD seed/medium; last_evidence
    2026-07-29 now 41 days old, still inside the 60-day window (dormancy line 2026-09-27, 19 days
    out) — still the weakest of the four active trends per the standing W35/W36 forward bet.
  - 2026-W37 recalibration: HELD seed/medium. last_evidence 2026-07-29 is 45 days old, inside the
    60-day window but only 15 days from the 2026-09-27 dormancy line. No 4th independent group or
    referee/vetting outcome on any of the three tracked preprints surfaced across the week's
    dailies (09-07→09-11); arXiv-API metadata recheck this session: no fresh v-update on any of
    the three. Confidence held medium (short, checkable, cross-verified computations — still
    unrefereed, now six-plus weeks quiet). Still the weakest of the four active trends. DECISION
    POINT UNCHANGED from W35/W36: if no 4th group or vetting outcome lands by the 2026-09-27
    dormancy line (next weekly, W38), the trend goes `dormant` under the domain-cadence rule rather
    than being held open indefinitely — this is the expected, routine outcome of the rule, not a
    failure to chase harder.
  - 2026-W38 recalibration: HELD seed/medium. last_evidence 2026-07-29 is 52 days old today
    (2026-09-19) — inside the 60-day window, 8 days from the 2026-09-27 dormancy line (CORRECTION
    to the W37 report's forward bet, which loosely flagged "dormant at W38": the line is a fixed
    calendar date, 2026-09-27, which falls AFTER this run, not on it — the daily reports of
    09-15/09-16 already caught and correctly deferred this). No 4th independent group or
    referee/vetting outcome on any of the three tracked preprints (2607.21508, 2607.26364,
    2607.27166) surfaced across the week's dailies (09-14→09-18, each keyword-sweeping fresh
    math.CO batches) or this session's arXiv-API metadata recheck (no fresh v-update on any).
    Confidence held medium (short, checkable, cross-verified computations — still unrefereed, now
    seven-plus weeks quiet). Still the weakest of the four active trends. DECISION POINT: if no 4th
    group or vetting outcome lands by 2026-09-27 (the first daily on/after that date, or W39 if
    sooner), the trend goes `dormant` under the domain-cadence rule — the routine, expected outcome
    of a quiet single-week convergence burst, not a failure to chase harder.
  - 2026-W39 recalibration (DEMOTION, seed → dormant, per the standing W35–W38 decision point): today
    (2026-09-26) is W39, one day BEFORE the fixed 2026-09-27/60-day dormancy line, but the standing
    plan explicitly named "W39 if sooner" as the trigger — so this run resolves it rather than waiting
    the one remaining day. A Semantic Scholar "cited by" check on all three tracked preprints
    (2607.21508, 2607.26364, 2607.27166; this week's Amendment G pass) found only already-excluded
    peripheral Schur-positivity papers plus two genuinely new but non-qualifying items: Suvrit Sra,
    "GPT, the Counterexample Machine" (arXiv:2608.29595, a compiled report of 15+ GPT-found
    counterexamples across many fields, citing Matherne-Morales as one instance — a survey of the AI
    method itself, not a 4th independent Stanley-Gasharov proof, and out of scope per the AI-watch
    rule) and Li, St. Dizier, "Schubitopes are not Ehrhart positive" (arXiv:2608.00377, an unrelated
    AI-assisted conjecture refutation, queued separately below). No 4th independent group, no referee/
    vetting outcome on any of the three tracked preprints (arXiv version-history recheck this
    session: no v-update since each paper's already-recorded v2, both from July). last_evidence
    2026-07-29 is now 59 days quiet, one day short of the formal 60-day line but the trend has had no
    new signal for two full months and the standing decision point is reached — DEMOTED to `dormant`.
    Confidence held medium (unchanged; dormancy is a velocity call, not a correctness downgrade — the
    three counterexamples remain valid, checkable, unrefereed). Reactivation trigger unchanged: a 4th
    independent group or a referee/vetting outcome on any of the three preprints.
  - 2026-W40 recalibration: HELD dormant/medium. last_evidence 2026-07-29 is 66 days quiet. No 4th
    independent group or referee/vetting outcome on any of the three tracked preprints surfaced
    across the week's dailies (09-28→10-02); a direct Schur-positivity/claw-free re-check this
    session (arXiv API metadata on all three) found no fresh v-update. Archive line (120 days from
    last_evidence) is 2026-11-26 — still 7+ weeks out, not yet due. No change.
  - 2026-11-27 (daily): the 120-day archive line (2026-11-26) has now PASSED — last_evidence
    2026-07-29 is 121 days quiet today. No 4th independent group or referee/vetting outcome found
    this session (no fresh arXiv activity on this sub-theme in today's full-category sweep). Per
    `routines/daily.md`, archiving is a WEEKLY action, not this daily's to take — flagging again,
    now overdue, for W48 (due ~2026-11-28, tomorrow) to archive without further delay.
  No stage/confidence change (`dormant`/`medium`) pending that weekly action.

### Sharpening the exponent in Marton's conjecture / polynomial Freiman-Ruzsa (additive combinatorics)
- stage: dormant | confidence: medium | first_seen: 2026-09-01 | last_evidence: 2026-09-15
- what: THREE independent author groups have now successively shaved the constant in the
  polynomial-Freiman-Ruzsa bound established by Gowers-Green-Manners-Tao's 2024 resolution of
  Marton's conjecture — a sequential-improvement DIRECTION trend (the same wave pattern as the
  Ramsey lower-bound trend above), not a fresh open-conjecture race: the conjecture itself is
  already settled, and the sub-theme is who can tighten the exponent next.
- evidence:
  - 2024-04-02 — https://arxiv.org/abs/2404.02244 — Gowers, Green, Manners, Tao, "Marton's
    Conjecture in abelian groups with bounded torsion": proves the polynomial Freiman-Ruzsa
    conjecture in full generality; for $G=\mathbb{F}_2^n$ specializes to a cover by at most
    $2K^{C}$ cosets with $C=12$. Abstract verified via arXiv API this session.
  - 2024-04-15 — https://arxiv.org/abs/2404.09639 — Liao, "Improved Exponent for Marton's
    Conjecture in $\mathbb{F}_2^n$": simple modifications to the GGMT argument improve $C=12$ to
    $C=9$. Abstract verified via arXiv API this session.
  - 2026-08-31 (v2 2026-09-15) — https://arxiv.org/abs/2608.30336 — Song, Yue, "An Improvement to
    the Upper Bound for Marton's Covering Conjecture": further improves the exponent from $9$ (Liao);
    v1 (08-31) gave $8.873$, v2 (09-15, this week's catch — see note) tightens it further to $5.287$.
    Surfaced in today's fresh math.CO batch; abstract verified via arXiv API this session.
- notes: 2026-09-01 (daily, PROMOTION): today's math.CO sweep surfaced the Song-Yue exponent
  improvement, which cites Liao's 2024 improvement of the original GGMT 2024 resolution as its
  immediate predecessor — three fully independent groups (GGMT; Liao; Song-Yue), each with its
  own concrete artifact, sequentially tightening one constant → clears the ≥3-independent-group
  convergence bar for a DIRECTION trend (daily.md §4), backdated evidence opened and verified this
  session even though the first two artifacts predate this radar. Stage set to `emerging` rather
  than `seed` given the sequence is already 2+ years and three iterations deep. Confidence medium
  (each step is a short, checkable refinement of a landmark already fully proved, not an
  extraordinary claim) — watch for a 4th group or the exponent approaching a plausible final
  constant.
  - 2026-09-03 (daily): fresh math.CO 2026-09-02 batch scanned for PFR/Marton-exponent items —
    none. No 4th independent group. Trend HELD emerging/medium; last_evidence 2026-08-31 now 3
    days old, well inside the 60-day window.
  - 2026-W36 recalibration: HELD emerging/medium. last_evidence 2026-08-31 is 5 days old. No 4th
    independent group surfaced across the week's dailies (09-01→09-04). Confidence held medium
    (each step a short, checkable refinement of an already-proved landmark). Not promoted (no
    fresh W36 velocity beyond the trend's founding week).
  - 2026-09-07 (daily): first daily since 09-04. Fresh math.CO full in-scope category-rotation
    batch (2026-09-04→09-07, 168 fresh entries) scanned for PFR/Marton-exponent items — none. No
    4th independent group. Trend HELD emerging/medium; last_evidence 2026-08-31 now 7 days old,
    well inside the 60-day window.
  - 2026-09-08 (daily): no fresh arXiv batch past the 09-04 ceiling (confirmed via direct API
    probes on math.CO/NT and the full in-scope category set this session — the underlying arXiv
    source has not advanced past 2026-09-04 despite two elapsed calendar days). No 4th independent
    group. Trend HELD emerging/medium; last_evidence 2026-08-31 now 8 days old, well inside the
    60-day window.
  - 2026-W37 recalibration: HELD emerging/medium. last_evidence 2026-08-31 is 12 days old, well
    inside the 60-day window (dormancy line 2026-10-30). No 4th independent group surfaced across
    the week's dailies (09-07→09-11, each rechecking fresh math.CO batches). Confidence held medium
    (each step a short, checkable refinement of an already-proved landmark). Not promoted (no fresh
    W37 velocity).
  - 2026-W38 recalibration: HELD emerging/medium. last_evidence 2026-08-31 is 19 days old, well
    inside the 60-day window (dormancy line 2026-10-30 unchanged). No 4th independent exponent-
    tightening group surfaced across the week's dailies (09-14→09-18); the 09-18 daily's
    Arunachalam-Dutt-Grewal-Gupte polynomial-time algorithm (arXiv:2609.20771) is a genuine
    Marton's-conjecture-adjacent artifact but an ALGORITHMIC contribution, not a tighter exponent
    constant, so per the trend's own same-sub-theme-only rule it does NOT count as a 4th group —
    correctly queued below-bar in its own right rather than as trend evidence (re-confirmed this
    session). Confidence held medium (each step a short, checkable refinement of an already-proved
    landmark). Not promoted (no fresh W38 velocity).
  - 2026-W39 recalibration (CORRECTION — an 11-day-old miss): Song-Yue's own preprint (2608.30336)
    posted a v2 on 2026-09-15, tightening their exponent from 8.873 to 5.287 — missed by every daily
    between 09-15 and 09-25 (a same-author revision, not a new arXiv id, so invisible to a
    title-keyword scan; caught this session via a routine arXiv-API version-history check on the
    trend's own tracked preprints). last_evidence advances 2026-08-31 → 2026-09-15. A same-author
    revision, not a 4th independent group — HELD emerging/medium (no promotion; the revision
    tightens existing evidence, it does not add a new corroborating group). Process gap: no dated
    v-history spot-check on active trends' own tracked preprints existed as a standing weekly step —
    proposed as this week's amendment (see report).
  - 2026-W40 recalibration: HELD emerging/medium. last_evidence 2026-09-15 is 18 days old, well
    inside the 60-day window. Version-history recheck this session (arXiv page for 2608.30336):
    still v2, no v3 — no further tightening. No 4th independent exponent-tightening group surfaced
    across the week's dailies (09-28→10-02). Not promoted.
  - 2026-W42 recalibration (Amendment I version-history spot-check): the ORIGINAL GGMT anchor
    (2404.02244) found silently revised to v2, updated 2024-05-20 — over two years old, low
    materiality, but a genuine previously-unnoticed revision (same title/authors; no change to the
    result this trend tracks). 2404.09639 (Liao) and 2608.30336 (Song–Yue) show no further
    v-update beyond what's already on file. No 4th independent group this week. Not promoted.
  - 2026-W46 recalibration (DORMANCY PROBE, 60 days quiet, first crossing of the 60-day
    threshold): Amendment I check (this session, full batch) confirms none of the three tracked
    preprints (2404.02244, 2404.09639, 2608.30336) show any v-update beyond what's already on
    file. Probed this trend's own evidence channel (arXiv): a fresh `search_query` scan for
    math.CO abstracts mentioning "Freiman-Ruzsa" over the full silent window — only the
    already-excluded, already-queued Arunachalam-Dutt-Grewal-Gupte algorithmic paper (09-17)
    falls inside the window; no new exponent-tightening group. Independent check:
    `tvly search "Marton conjecture polynomial Freiman-Ruzsa new exponent bound" --topic news
    --start-date 2026-09-15` returned no on-topic hits. Empty probe → moved to `dormant` per the
    60-day domain-cadence window. Not archived (nowhere near 120 days). Reactivation trigger: a
    4th independent exponent-tightening group or a referee/vetting outcome on any of the three
    preprints.

### Resolution of the Komlós / Beck-Fiala discrepancy conjectures (AI-discovered, human-confirmed)
- stage: emerging | confidence: high | first_seen: 2026-09-24 | last_evidence: 2026-11-03
- what: an AI research agent ("Odin Automatic AI Research Agent") is credited with discovering a
  proof of the ~50-year-old Komlós conjecture (vector-signing/discrepancy problem) AND, as a
  corollary, the square-root dependence predicted by the Beck-Fiala conjecture, in one paper
  (2026-09-10); TWO independent human author groups have already built on it within two weeks —
  an elementary re-proof and an exposition with a further tightened constant — a fast, multi-group
  human-confirmation pattern on a single AI-discovered result (axis 1, combinatorics/discrepancy
  theory; axis 5 AI-assisted-math watch). HEAVY CAVEATS (hype-skepticism + AI-watch rules):
  unrefereed preprints throughout; the ORIGINAL proof is AI-discovered → PROVISIONAL until
  independent vetting. Track the mathematical RESULT (two named conjectures), NOT the AI method
  (the sibling AI radars' beat) — noted here only because the human re-derivations are themselves
  primary mathematical contributions.
- evidence:
  - 2026-09-10 — https://arxiv.org/abs/2609.11189 — Guo, Fang, Lu, "Vector Balancing via
    Directional Total Variation": proves a $3\sqrt{2\pi}$ bound for the Komlós signing problem
    (dimension/family-size independent) and the square-root Beck-Fiala dependence via a
    Banaszczyk-transform + directional-total-variation argument; abstract states "the proof was
    discovered by the Odin Automatic AI Research Agent." Abstract + authors + AI-discovery
    statement verified via direct arXiv page this session (arXiv API itself 406-erroring this
    session, worked around via `arxiv.org/abs/<id>` + RSS).
  - 2026-09-17 (v2 2026-09-22) — https://arxiv.org/abs/2609.20979 — Karingula, Lovett, "An
    elementary proof of the Komlós conjecture": simplifies the Guo-Fang-Lu proof to an elementary
    combinatorial/probabilistic argument, $\|\cdot\|_\infty\le 36$. Abstract + authors verified via
    direct arXiv page this session.
  - 2026-09-23 (v2 2026-09-29) — https://arxiv.org/abs/2609.27172 — Akbas, Sra, "Tighter bounds on
    Komlós discrepancy: existence and algorithmic results" (RETITLED at v2 — v1 was "An exposition
    of the proof of the Komlós conjecture"; see W40 note): improves the existence bound for
    unit-norm vectors and gives a deterministic algorithm to compute such a coloring efficiently.
    Title/authors/v1→v2 change verified via direct arXiv page this session.
  - 2026-09-17 — https://arxiv.org/abs/2609.19714 — Altschuler, "Improved Algorithms for Beck-Fiala
    with Bounded Sets": a FOURTH independent author (new to this trend), gives an efficient
    algorithm with improved discrepancy bounds for Beck-Fiala when matrix columns have bounded
    sparsity, via a bootstrapping technique built on the Bansal-Jiang algorithm (the same Bansal-
    Jiang prior-art already cross-referenced in this trend's W39 note). Title/author/date verified
    via direct arXiv page this session — found via a Semantic Scholar "cited by" chase on the
    Guo-Fang-Lu founding artifact (this week's Amendment G pass).
  - 2026-09-24 — https://arxiv.org/abs/2609.30044 — Xiaoyu Li, "Fast Spectral Signing for Vector
    Balancing": a FIFTH independent author, gives a faster deterministic algorithm for the Komlós
    sign-assignment problem via a spectral approach, improving prior algorithms' running time and
    discrepancy bound. Title/author/date verified via direct arXiv page this session — found via
    the same citation chase.
  - 2026-09-27 — https://arxiv.org/abs/2609.33215 — Bansal, "On the Guo-Fang-Lu Algorithm for Komlos
    Discrepancy": a simplified exposition of Guo-Fang-Lu's polynomial-time algorithm, emphasizing
    the spectral-potential technique. Nikhil Bansal is the SAME author cross-referenced in this
    trend's W39 prior-art note (Bansal-Jiang, arXiv:2508.03961) — an escalation of an already-known
    adjacent author directly onto this trend's founding result, not counted toward the independent-
    group tally, but a further community-engagement data point. Title/author/date verified via
    direct arXiv page this session — found via the same citation chase.
  - 2026-11-03 — https://arxiv.org/abs/2611.03427 — Lawrence Hollom, "Proving the Komlós conjecture
    slowly": a motivated pedagogical exposition of the Karingula-Lovett elementary proof. ALSO
    names a previously-uncaptured result: "a counterexample to the strong Komlós conjecture due to
    Kintali" — NOT independently verified this session (only this exposition's mention opened; the
    Kintali primary itself not yet located) — flagged for next session to chase. Abstract + author
    verified via arXiv API this session.
- notes: 2026-09-24 (daily, SEED): today's math.CO/FA fresh-batch triage surfaced the two follow-up
  papers (elementary proof + exposition), both explicitly crediting an underlying "recent proof of
  Guo, Fang, and Lu" without giving its arXiv id; `arxiv.org/search` + WebSearch located and opened
  the original (2609.11189, 2026-09-10, previously uncaptured — a 2-week-old miss, likely because
  its title ("Vector Balancing via Directional Total Variation") doesn't surface on a
  Komlós/discrepancy keyword title-scan). Three independent author groups + three concrete arXiv
  artifacts on one sub-theme within two weeks clears the domain's convergence bar; set to `seed`
  rather than `emerging` given the founding artifact is AI-discovered and wholly unrefereed —
  watch for a fourth group, a referee outcome, or a gap found in the underlying proof.
  - 2026-W39 recalibration (cross-reference correction, no promotion): the `observation_queue`
    already held an older, PARTIAL prior result on exactly these two conjectures —
    Bansal, Jiang, "Decoupling via Affine Spectral-Independence: Beck-Fiala and Komlós Bounds Beyond
    Banaszczyk" (arXiv:2508.03961, 2025-08-05, capture-leak-caught 2026-08-21) — which already
    resolved the Beck-Fiala conjecture for $k\ge\log^2 n$ and improved (not resolved) the Komlós
    bound to $O((\log N)^{1/4})$. Guo-Fang-Lu's dimension/family-size-INDEPENDENT constant bound
    (this trend's founding artifact) is the genuine full generalization Bansal-Jiang's regime-
    restricted result did not reach — the two are complementary, not duplicative, and Guo-Fang-Lu's
    abstract does not cite Bansal-Jiang (checked this session) — flagged here so a future referee
    pass on the AI-discovered proof has this prior-art context on file. No evidence/stage change;
    HELD seed/medium. Held for a fourth group, a referee outcome, or a gap report.
  - 2026-W40 recalibration (PROMOTION, seed → emerging; confidence medium → high; this week's
    Amendment G citation-chase pass): a Semantic Scholar "cited by" search on the Guo-Fang-Lu
    founding artifact (2609.11189) surfaced NINE citing papers in the three weeks since posting —
    far more community engagement than the two follow-ups on file at creation. Verified by opening
    each candidate directly (arXiv abstract pages this session): two are NEW independent groups
    building algorithmic improvements directly on Komlós/Beck-Fiala — Altschuler (2609.19714) and
    Xiaoyu Li (2609.30044), now appended as evidence, bringing the independent-group count to FIVE
    (Guo-Fang-Lu; Karingula-Lovett; Akbas-Sra; Altschuler; Li) — satisfying the standing "watch for
    a fourth group" note twice over. A SIXTH citing paper (Bansal, 2609.33215) is the SAME author as
    the already-cross-referenced Bansal-Jiang prior art, an escalation not a new group (appended as
    evidence for the engagement signal, not counted toward the tally). CORRECTION found in the same
    pass: the Akbas-Sra evidence line (2609.27172) had gone stale — the paper was RETITLED and
    rescoped at v2 (2026-09-29, from "An exposition of the proof..." to "Tighter bounds on Komlós
    discrepancy: existence and algorithmic results"), the same silent-retitling pattern flagged
    elsewhere this week (see the Hopf-problem/S²×S³ capture-gap notes in `logs/strategy_notes.md`)
    — fixed in the evidence line above. TWO further citing papers (Niles-Weed–Sadovsky–Shkrob,
    2610.02127; Jiang–Lim–Parvatikar, 2609.31389) engage a related but DISTINCT variant problem
    (vector balancing with permutations; "unbalancing" unit vectors — the reverse direction) and do
    NOT count as trend evidence, per the same adjacent-sub-area handling as the Ramsey trend's
    Ramsey-adjacent items — queued in their own right below. PROMOTION rationale: five independent
    groups within three weeks of an AI-discovered, wholly-unrefereed base result is exactly the
    "fast, multi-group human-confirmation pattern" this trend's own `what` field anticipated;
    Karingula-Lovett's and Akbas-Sra's papers are themselves independent RE-DERIVATIONS of the core
    Komlós bound by different methods, which is the kind of "replication" the hard rules' hype-
    skepticism caution treats as a genuine (if not yet peer-reviewed) vetting signal — meeting the
    confidence-to-high bar ("≥2 independent authoritative primary sources corroborate... on concrete
    artifacts"). Confidence raised to high despite the unrefereed-preprint caution remaining in
    force (still no formal peer review; the base proof is still AI-discovered) — the caution is
    about PEER REVIEW, which this does not have, not about independent corroboration, which it now
    has in abundance; held open for a referee outcome or a found gap, which would require a
    demotion regardless of corroboration count. last_evidence advances 2026-09-23 → 2026-09-29
    (Akbas-Sra's v2 retitling/rescoping — the newest dated activity among this trend's own
    evidence lines; the two queued variant-problem papers are not trend evidence and do not set
    this date).
  - 2026-W43 recalibration (Amendment G citation-chase rotation, this trend's turn per the W42
    rotation note): a fresh Semantic Scholar "cited by" pass on the Guo-Fang-Lu anchor (2609.11189)
    surfaced two further citing papers. Shengtao Guo, Ethan X. Fang, Junwei Lu, "Vector Balancing
    in Polynomial Time" (2609.23540, 2026-09-20) is the SAME original author trio's own follow-up
    (verified via arXiv API — identical author names), not a new independent group — logged for
    engagement, not appended as evidence. Emile Anand, Peter Chen, "The Komlós Problem in
    Matrix-Multiplication Time" (2610.20995, 2026-10-14) IS a genuinely new, previously-uncaptured
    independent pair — a SEVENTH independent group/artifact on this trend (after Guo-Fang-Lu,
    Karingula-Lovett, Akbas-Sra, Altschuler, Li; Bansal's escalation not counted). Confidence
    already at `high`, no further promotion triggered (already past the 2-group bar); appended
    below as evidence for the record.
  - 2026-10-14 — https://arxiv.org/abs/2610.20995 — Anand, Chen, "The Komlós Problem in
    Matrix-Multiplication Time": a seventh independent author pair, giving an algorithm running in
    matrix-multiplication time for the Komlós sign-assignment problem. Abstract/authors verified
    via arXiv API this session (found via the W43 Amendment G citation chase).
  - 2026-11-04 (daily): Hollom's pedagogical exposition (see evidence) is a further community-
    engagement data point (already past the 2-group confidence bar, no promotion). Surfaced a
    previously-uncaptured NAMED claim worth chasing: a "counterexample to the strong Komlós
    conjecture due to Kintali" — not yet independently verified (only this exposition's mention
    opened); next session should locate Kintali's own primary. No stage/confidence change.
    last_evidence advances 2026-10-14 → 2026-11-03.

### Resolution of Sarnak's positive trace gap conjecture (hyperbolic lattices)
- stage: dormant | confidence: medium | first_seen: 2026-09-25 | last_evidence: 2026-09-25
- what: a single-author resolution of the ~18-year-old positive trace gap conjecture, attributed to
  Sarnak by Geninska and Leuzinger (2008), for lattices in PSL_2(R)/PSL_2(C) — a named, long-standing
  open problem in the geometry of discrete groups (domain-cadence landmark single result, axis 1,
  hyperbolic geometry/number theory). Author is an established specialist in this exact sub-field
  (arithmetic/quasi-arithmetic hyperbolic lattices, PhD HSE under Ernest Vinberg, now UofT Scarborough
  faculty) — credible, not a hype/crank pattern, but still an unrefereed preprint.
- evidence:
  - 2026-09-24 (CORRECTED 2026-10-17, W42 Amendment I check — a 1-day date-entry error, not a
    revision; this line had recorded 2026-09-25) — https://arxiv.org/abs/2609.29033 — Bogachev,
    "Proof of the positive trace gap conjecture": proves a lattice in PSL_2(R) or PSL_2(C) has
    positive trace gap iff it is derived
    from an admissible quaternion algebra, resolving the conjecture for cocompact Fuchsian groups;
    extends to a similar characterization for lattices in SL_d(R), d≥3. Abstract + author verified
    via direct arXiv page this session (v1 2026-09-25, cross-listed math.DS/GR/GT/NT).
- notes: 2026-09-25 (daily, SEED): caught in today's full in-scope math category-rotation sweep
  (cross-listed in four categories, which flagged it for a closer look). Single credible-author
  landmark resolution of a named 2008 conjecture — clears the domain-cadence adaptation bar on its
  own. Confidence held medium (unrefereed-preprint caution; no independent confirmation yet) — watch
  for a referee outcome or a second group engaging with the quaternion-algebra characterization. Also
  on `study_shelf`.
- notes: 2026-11-24 (daily): DORMANCY PROBE (owed, now run) — `last_evidence` hits the 60-day
  domain-cadence dormancy line exactly today. Probed the trend's own channel (the paper's arXiv
  page: still v1, no new version since creation) plus an independent web search for commentary —
  found none (no referee outcome, no second group, no citing/engaging paper). Empty probe → move
  to `dormant`. Re-check at the 120-day archive line (~2027-01-23) or sooner if independent
  engagement appears.

### Irrationality of ζ(5) (Fauzan; independently Lean-verified by Firsching)
- stage: seed | confidence: medium | first_seen: 2026-09-26 | last_evidence: 2026-11-12
- what: a claimed proof that ζ(5) is irrational (Aabir Fauzan, off-arXiv, Zenodo, 2026-09-17) — the
  first individual-odd-zeta-value irrationality result since Apéry's 1978 proof for ζ(3) — held on
  this ledger's `observation_queue` since 2026-09-25 with EXTREME hype-skepticism caveats (no author
  publication history, AI-model-only "vouching," two competing INCOMPLETE Lean formalizations).
  PROMOTED this week: a THIRD, INDEPENDENT Lean formalization (Moritz Firsching — Google DeepMind,
  an established Lean/Mathlib contributor who leads the `formal-conjectures` project — not affiliated
  with Fauzan) is now COMPLETE and `sorry`-free, closing the domain-cadence "landmark + independent
  confirmation" bar this ledger applied to the Komlós/Beck-Fiala precedent. Still short of formal
  peer review — this is the strongest vetting signal available for an off-arXiv claim, not a
  publication-grade outcome.
- evidence:
  - 2026-09-17 — https://zenodo.org/records/22826418 — Aabir Fauzan, "ζ(5) is irrational": via integer
    polynomials $Q_n$ of degree $37n$ with $0<Q_n(\zeta(5))<\exp(-139n^2/5)$ (Hankel determinants +
    moment representations + log-energy estimates), giving $|\zeta(5)-a/b|>b^{-260}$ for large $b$.
    Off-arXiv (Zenodo, no endorsement gate); author has no prior publication history. Zenodo record
    opened directly (title/author/date/abstract verified, this session and 2026-09-25).
  - 2026-09-23 — https://github.com/mo271/zeta5 — Moritz Firsching, complete Lean 4 formalization:
    `irrational_five` proved with no `sorry`, axioms limited to `propext`, `Classical.choice`,
    `Quot.sound` (the Lean/Mathlib standard set) — confirmed via the repo's own
    `#print axioms Apery.irrational_five`. TECHNICAL CAVEAT (verified this session): the Lean proof
    deviates from Fauzan's own construction at one step — "direct class-wise partial fractions
    instead of the Tate-algebra functional" and different normalizer bounds — but reproduces the
    same numerical threshold (constant ≈1.345, required <1.36) with matching intermediate values
    against the original paper's appendix. So this is an INDEPENDENT re-derivation confirming the
    same result via a formally verified but not identical route, not a literal proof-check of
    Fauzan's exact argument. Repo, commit history and README opened directly this session; public
    reaction from Alex Kontorovich (Rutgers, analytic number theory) opened via WebSearch ("WOW!!
    Zeta(5) is irrational!... Amazing what we'll learn (with AI help)") — enthusiasm from a credible
    specialist, not a formal correctness statement.
  - 2026-10-05 — https://arxiv.org/abs/2610.06838 — Li Lai, "The linear independence of $1$,
    $\zeta(3)$, and $\zeta(4)$": combines "Fauzan's determinant method" explicitly with classical
    simultaneous-approximation methods (Zudilin; Dauguet–Zudilin) to prove 1, ζ(3), ζ(4) are
    linearly independent over ℚ — a different author extending the anchor technique, strengthening
    this trend's axis (not a re-confirmation of ζ(5) itself). Single-author, unrefereed — same
    hype-skepticism caution as the anchor claim. Abstract + author verified via arXiv API this
    session (v1 2026-10-05). CAPTURE-LEAK FIX (W41 weekly): this item was named and its
    last_evidence-advancing effect claimed in the 2026-10-06 daily note below, but never given its
    own evidence-list line until now.
- notes: 2026-W39 recalibration (PROMOTION, queue → seed): the queue item's own standing instruction
  ("chase this daily until it resolves... a completed Lean formalization, a human referee report, or
  a found gap") is satisfied by Firsching's complete, sorry-free, independently-authored
  formalization — a materially stronger signal than the AI-model-only "vouching" that held this back
  on 2026-09-25, and the same class of event (independent human/tooling confirmation) that promoted
  the Komlós/Beck-Fiala trend. Confidence held medium, not high: the Lean proof takes a technically
  different route at one step rather than literally re-checking Fauzan's exact argument, so this is
  strong corroboration of the NUMERICAL RESULT, not a line-by-line audit of the original manuscript;
  no traditional peer review yet; the two other, still-incomplete formalization efforts
  (danromik/zeta5-irrationality — two axiomatized classical lemmas, one unproved inequality;
  long-mathematics/zeta5-irrationality — 3/49 targets proved) remain open and are themselves worth
  watching for whether they close on Fauzan's literal construction. Watch for: either incomplete
  formalization reaching completion (which would audit Fauzan's exact argument rather than
  Firsching's variant), a named-mathematician on-record statement beyond Kontorovich's social-media
  reaction, or a found gap in any of the three efforts.
  - 2026-09-28 (daily): first NAMED-MATHEMATICIAN on-record engagement beyond Kontorovich's social
    reaction — "Persiflage" (a pseudonymous blog by a University of Chicago mathematics professor,
    galoisrepresentations.org), 2026-09-24, expresses skepticism about Fauzan's own paper ("gives me
    the impression of being almost entirely AI generated (if so, it then comes with a very dishonest
    disclosure)") but confirms the result "has now been verified in Lean" and traces the technique to
    prior literature (Prévost, Uvarov, Krattenthaler, Zudilin) — i.e. engaging with the mathematical
    substance/provenance rather than a bare reaction. Neither confirms nor refutes correctness; a
    genuine vetting SIGNAL (authorship-honesty concern + provenance work), not an OUTCOME. Confidence
    held medium; stage held seed. Post opened directly this session.
  - 2026-09-29 (daily): further research-level engagement — a MathOverflow question ("On the recent
    irrationality proof for ζ(5)," asked 2026-09-25, https://mathoverflow.net/questions/515519)
    treats Fauzan's Hankel-determinant construction as a serious object, asking whether it embeds in
    Francis Brown's motivic/moduli-space framework for irrationality proofs — implicit substantive
    engagement (not dismissal), still no referee outcome. Confidence held medium; stage held seed.
    Question opened directly this session.
  - 2026-10-06 (daily): a direct methodological follow-on — Li Lai, "The linear independence of
    $1$, $\zeta(3)$, and $\zeta(4)$" (https://arxiv.org/abs/2610.06838, v1 2026-10-05) — combines
    "Fauzan's determinant method" explicitly (the same technique underlying this trend's anchor
    result) with classical simultaneous-approximation methods (Zudilin; Dauguet–Zudilin) to prove
    1, ζ(3), ζ(4) are linearly independent over ℚ. Single-author, unrefereed — same hype-skepticism
    caution as the anchor claim, but a genuine extension of the method by a different author,
    strengthening (not just re-confirming) this trend's axis. last_evidence advances 2026-09-23 →
    2026-10-05. Abstract + author + date verified via arXiv API this session.
  - 2026-W42 recalibration (Amendment I version-history spot-check): Li Lai's 2610.06838 found
    silently revised to v2, updated 2026-10-15 — only 2 days old, missed by both the 10-06 daily's
    own creation check and every subsequent daily/weekly on this trend. last_evidence advances
    2026-10-05 → 2026-10-15. Same author/title; the specific nature of the v2 change was not
    re-verified this session (abstract-level check only) — worth a closer look if it recurs as a
    live watch item. No change to Fauzan's own Zenodo record or Firsching's Lean repo. Stage held
    `seed`/medium (still no traditional peer review on the anchor claim).
  - 2026-11-13 (daily): a fourth author group extends the anchor technique — Fischler, Lai,
    Sprang, Zudilin, "Many more odd zeta values are irrational"
    (https://arxiv.org/abs/2611.16156, v1 2026-11-12) — improves the known asymptotic count of
    irrational odd zeta values, explicitly citing "the Hankel determinant method that appeared in
    the proof that ζ(5) is irrational posted by Fauzan" as one of its combined techniques. Wadim
    Zudilin is a leading transcendence-number-theory specialist — a credible author independently
    building on the anchor method (not merely commenting on it), the strongest methodological
    endorsement this trend has received yet. Caught via today's math.NT title-triage sweep.
    last_evidence advances 2026-10-15 → 2026-11-12. Confidence held `medium` (the anchor claim
    itself remains unrefereed). Abstract/authors verified via arXiv API this session.

### Advances in poset linear-extension theory (Kahn-Saks conjecture resolved; first 1/3-2/3 conjecture progress in 30 years)
- stage: seed | confidence: medium | first_seen: 2026-09-28 | last_evidence: 2026-10-28
- what: two companion results posted the same day resolve/advance two of order theory's most famous
  conjectures on linear extensions of posets. Max Aires proves the Kahn-Saks conjecture (1984)
  outright: sufficiently large poset width forces the balancing coefficient δ(P) arbitrarily close to
  1/2. A companion paper by Aires with Swee Hong Chan, Igor Pak, and Greta Panova gives the first
  general improvement to the classical 1/3–2/3 conjecture's balance constant in over 30 years,
  beating the Brightwell–Felsner–Trotter (1995) bound by a small ε. Domain-cadence landmark (a
  decades-old named conjecture resolved outright) with directly related progress on an even more
  famous, still-open conjecture in the same subfield, by credible authors (Pak, Panova are
  established combinatorialists).
- evidence:
  - 2026-09-25 — https://arxiv.org/abs/2609.30895 — Max Aires, "Proof of the Kahn Saks Conjecture":
    resolves the 1984 Kahn-Saks conjecture that large poset width forces the balancing coefficient
    toward 1/2 (abstract verified via direct arXiv page this session, v1 2026-09-25).
  - 2026-09-25 — https://arxiv.org/abs/2609.30888 — Aires, Chan, Pak, Panova, "Breaking the Infinite
    Barrier in the 1/3–2/3 Conjecture": first general improvement to the balance constant since
    Brightwell-Felsner-Trotter 1995 — "the first general result towards the 1/3-2/3 conjecture in
    over 30 years" (abstract verified via direct arXiv page this session, v1 2026-09-25; W44
    version-history spot-check: silently revised to v2, updated 2026-10-28 — no new group/claim,
    same author/result, folded in for the record).
- notes: 2026-09-28 (daily, seed creation): both posted the same day by an overlapping author team
  (Aires common to both); captured via the full math category-rotation sweep (math.CO), part of the
  Monday weekend-backlog batch. Not yet an independent-multi-group DIRECTION trend (one author
  cluster) but qualifies under the domain's landmark-single-result bar (Kahn-Saks resolved outright),
  with the 1/3-2/3 progress bundled as directly related context. Unrefereed preprints — watch for
  referee outcomes and whether a second group engages with the 1/3-2/3 improvement.
  - 2026-W44 recalibration (Amendment I version-history spot-check): 2609.30888 (Aires–Chan–Pak–
    Panova) found silently revised to v2, updated 2026-10-28 — POSTDATES the recorded last_evidence
    (2026-09-25); last_evidence advances 2026-09-25 → 2026-10-28 accordingly. 2609.30895 (Aires)
    shows no v-update. Same author/result, no new group. Not promoted.

### Proof of the Cassels–Swinnerton-Dyer conjecture for smooth cubic surfaces
- stage: dormant | confidence: medium | first_seen: 2026-09-28 | last_evidence: 2026-09-25
- what: Valery Alexeev and Stefan Schreieder give two independent proofs completing the
  Cassels–Swinnerton-Dyer conjecture (a cubic hypersurface has a rational point iff it has a
  zero-cycle of degree 1) for smooth cubic surfaces over arbitrary fields, closing the missing
  degree-4-point case that a ~50-year reduction chain (Coray 1976, extended by Voisin earlier in
  2026) had left open; they also separately settle the singular-cubic-surface case. Landmark single
  result in arithmetic/algebraic geometry — a classical named conjecture fully resolved in its
  cubic-surface case.
- evidence:
  - 2026-09-14 (v1), last revised 2026-09-25 (v3) — https://arxiv.org/abs/2609.15930 — Alexeev,
    Schreieder, "Two proofs of the Cassels-Swinnerton-Dyer conjecture for cubic surfaces": completes
    Coray (1976)/Voisin (2026)'s reduction to the degree-4-point case with two independent arguments,
    plus a separate treatment of singular cubic surfaces (abstract verified via direct arXiv page
    this session).
- notes: 2026-09-28 (daily, seed creation): captured via the full math category-rotation sweep
  (math.AG, cross-listed math.NT); the v3 revision (09-25) is what surfaced it in today's fresh-batch
  window even though v1 predates by ~2 weeks. Single-group landmark; unrefereed preprint — watch for
  referee/community reaction, and check whether Voisin's own cited 2026 reduction paper (not
  independently opened this session) belongs on this ledger too.
- notes: 2026-11-24 (daily): DORMANCY PROBE (owed, now run) — `last_evidence` hits the 60-day
  domain-cadence line exactly today. Probed the paper's own arXiv page (still v3, no newer
  revision) plus an independent web search for commentary — found none (no referee outcome, no
  citing/engaging paper beyond a generic unreviewed-claims aggregator). Empty probe → move to
  `dormant`. Re-check at the 120-day archive line (~2027-01-23) or sooner if engagement appears.
  Voisin's own cited reduction paper still not independently opened (standing chase item).

### Resolution of Graham's rearrangement conjecture (additive combinatorics)
- stage: seed | confidence: high | first_seen: 2026-09-29 | last_evidence: 2026-02-17
- what: Ronald Graham's 1971 conjecture — that any sequence of distinct nonzero residues mod a
  prime p can be reordered so that all partial sums are distinct — is fully resolved via a
  four-paper chain spanning four independent author groups (2022-2026), each extending the
  randomized method further, closing with a February 2026 paper giving the general case. Meets
  the multi-group DIRECTION bar directly (≥3 independent groups + concrete artifacts), not only
  the domain's landmark-single-result adaptation.
- evidence:
  - 2022-04-20 — https://arxiv.org/abs/2204.09666 — Müyesser, Pokrovskiy, "A random Hall-Paige
    conjecture": the randomized method later adapted to Graham's conjecture (abstract + authors
    verified via arXiv API this session).
  - 2024-09-11 — https://arxiv.org/abs/2409.07403 — Bedert, Kravitz, "Graham's rearrangement
    conjecture beyond the rectification barrier" (abstract + authors verified via arXiv API this
    session).
  - 2025-08-25 — https://arxiv.org/abs/2508.18254 — Bedert, Bucić, Kravitz, Montgomery, Müyesser,
    "On Graham's rearrangement conjecture over $\mathbb{F}_2^n$" (abstract + authors verified via
    arXiv API this session).
  - 2026-02-17 — https://arxiv.org/abs/2602.15797 — Pham, Sauermann, "On Graham's rearrangement
    conjecture": the general case, officially closing the 55-year-old problem (abstract + authors
    verified via arXiv API this session).
- notes: 2026-09-29 (daily, seed creation): caught via a Quanta Magazine piece ("Mathematicians
  Harness Randomness To Crack a 55-Year-Old Conjecture," 2026-09-28, Shalma Wegsman) found in the
  community-pulse digest sweep; all four arXiv ids opened and verified this session (a ~7-month-old
  capture-leak catch on the final paper, which posted quietly in February). Four distinct author
  groups across four years is itself a DIRECTION-bar case, seeded at `high` confidence given the
  closing paper plus named-expert corroboration (Noga Alon, quoted in the Quanta piece, on the
  proof's significance). Watch for follow-on generalizations (the conjecture's higher-order/
  non-prime-modulus variants).
  - 2026-W40 recalibration (dormancy-clock clarification, no action): `last_evidence` (2026-02-17)
    is nominally 228 days old today, which would read as past even the 120-day archive line — but
    this trend was only first_seen 2026-09-29 (4 days ago) and the conjecture is a RESOLVED landmark
    (the "evidence" is the closing paper's actual publication date, not a signal of continuing
    activity). Per the precedent set for the Ramsey trend at its own creation (W27/W28: "NOT marked
    dormant despite the evidence gap because the trend was only created N days ago"), a freshly
    created trend's dormancy clock should run from when THIS LEDGER started tracking it, not from
    an old backlog artifact's own date — so this is NOT a dormancy case. No fresh follow-on
    generalization surfaced this week. Watch continues; this note exists so a future session does
    not mechanically read the raw day-count and misfire an archive action.
  - 2026-W42 recalibration (Amendment I version-history spot-check): two of the four prior-art
    evidence lines found silently revised, both over a year old and low-materiality but genuine
    previously-unnoticed revisions — 2204.09666 (Müyesser–Pokrovskiy) to v3, updated 2025-02-25;
    2409.07403 (Bedert–Kravitz) to v2, updated 2025-01-07. Both same title/authors, predating this
    trend's own creation by well over a year; no change to the trend's own last_evidence (set by
    the 2602.15797 closing paper, unaffected). No fresh follow-on generalization this week.

### The Hopf problem — a complex structure on S⁶ (Alpöge/Claude, 1947 problem)
- stage: seed | confidence: medium | first_seen: 2026-10-01 | last_evidence: 2026-09-27
- what: Heinz Hopf's 1947 problem — does the six-dimensional sphere S⁶ admit an integrable complex
  structure? — one of the most famous open problems in differential geometry (Borel–Serre: only S²
  and S⁶ even admit *almost*-complex structures). Levent Alpöge (Anthropic), using an internal
  Claude model, self-published a claimed construction on 2026-08-23/24: a family of complex
  threefolds diffeomorphic to S⁶, built from a (3,4,∞)-triangle-group modular family of 2-tori
  completed at three special fibres. DOMAIN-CADENCE LANDMARK (resolution of a 79-year-old named
  problem) — EXTREME unrefereed-preprint caution: off-arXiv, self-published, and this exact problem
  has a troubled history (Gábor Etesi's 2015 *J. Math. Phys.* claim is now widely regarded as flawed
  per the MathOverflow thread below). AI-WATCH: note the Claude assistance, track the mathematical
  result.
- evidence:
  - 2026-08-23/24 — https://alpo.ge/s6.pdf — Alpöge (communicating a Claude-generated construction),
    "The (3,4,∞) modular family of 2-tori, completed at its three special points, is a complex
    structure on S⁶": the original manuscript. Opened directly this session (PDF fetched and read).
  - 2026-08-27 — https://philip-engel.github.io/S6.pdf — Philip Engel (U. Illinois Chicago),
    "Complex structures on S6": an independent expository write-up reconstructing and explaining the
    geometric ideas of the construction (period maps, Kodaira fillings at the three special fibres).
    Opened directly this session.
  - 2026-09-27 — https://arxiv.org/abs/2609.33785 — Jeff Viaclovsky (UC Irvine), "A two-parameter
    family of complex structures on S⁶": an INDEPENDENT arXiv paper constructing a second, different
    two-parameter family of complex structures on S⁶ (from a rational elliptic surface with singular
    fibers III*,I₁,I₁,I₁), explicitly built atop and contrasted with "the original Alpöge–Claude
    examples" — the strongest peer-track-record corroboration signal found this session (an
    established differential geometer treating the base construction as solid enough to extend).
    Abstract + author verified via arXiv API this session.
- notes: 2026-10-01 (daily, seed creation, COVERAGE-GAP): caught via a Scientific American piece
  ("AI solves 79-year-old math mystery of six-dimensional spheres") found in today's community-pulse
  digest sweep — a 5+ week-late capture (original claim 2026-08-23/24), flagged in today's report as
  a genuine coverage miss, not a fresh find (none of alpo.ge/philip-engel.github.io/2609.33785 were
  in `TRENDS.md` before today). Vetting status: Boris Alexeev (OpenAI) reportedly posted a Lean
  formalization of the construction to GitHub on 2026-08-27 (per a MathOverflow answer — NOT
  independently opened this session, so not logged as its own evidence line); MathOverflow's thread
  on "Is there a complex structure on the 6-sphere?" shows a MIXED reaction — at least one answer
  states "I do not think that proof is correct" — alongside Robert Bryant's (Duke) more cautiously
  positive "there seems to be an emerging consensus that the construction is plausible" (quoted in
  the Scientific American piece). Confidence held medium (not high): a real independent-mathematician
  extension (Viaclovsky) plus a reported Lean formalization are meaningful technical signals, but
  there is no completed peer review and open mathematician-level disagreement on correctness. Watch
  for: a peer-reviewed outcome, direct confirmation/refutation from a named specialist, or the
  Alexeev Lean repo opened and verified directly.

### Resolution of Lehmer's 1965 permutation conjecture (neighbor-swap Hamiltonicity)
- stage: seed | confidence: medium | first_seen: 2026-10-02 | last_evidence: 2026-10-02
- what: D.H. Lehmer conjectured in 1965 that the permutations of every multiset admit an
  "imperfect Hamiltonian traversal" by adjacent (neighbor) swaps — posed as an unsolved research
  problem in Knuth's *The Art of Computer Programming*. Tom Verhoeff (TU Eindhoven), who in 2017
  reformulated the conjecture as the Hamiltonicity of a derived graph N(S) on non-stutter words
  (with two known exceptional families), now proves that reformulation — and with it Lehmer's
  original conjecture — via a hypercube-partition argument gluing Hamiltonian cycles along a
  spanning tree, reducing the single-odd-multiplicity case to a 1992 theorem of Stachowiak.
  DOMAIN-CADENCE LANDMARK: a 61-year-old named conjecture, posed in a canonical reference (Knuth),
  now resolved. Confidence raised above the usual single-author-preprint floor because the proof
  is accompanied by a complete Lean 4 / Mathlib formalization, machine-checked against brute-force
  graphs for the finite base cases — axis 5 (computer-assisted/formalized math) overlap, similar
  in kind to the already-tracked ζ(5)/FLT Lean-verification precedents. Still an unrefereed preprint
  (hype-skepticism caution applies to the human-written proof narrative even though the Lean
  artifact is machine-checked).
- evidence:
  - 2026-10-01 — https://arxiv.org/abs/2610.01240 — Tom Verhoeff, "A proof of Lehmer's permutation
    conjecture for neighbor-swap graphs": the resolution, with an accompanying Lean 4 formalization
    checked against brute-force graphs. Abstract + author + date verified via arXiv API this
    session (v1, submitted 2026-10-01); full abstract opened and read.
- notes: 2026-10-02 (daily, seed creation): caught in today's full math.CO RSS sweep (same-day
  v1). Domain-cadence landmark bar met (61-year-old conjecture, canonical-reference provenance,
  Lean-formalized) — promoted straight to seed rather than queued, per the ζ(5)/FLT precedent of
  weighting a machine-checked formalization above the usual unrefereed-single-author floor. Watch
  for: the Lean repository itself opened and verified directly (not yet done this session — only
  the arXiv abstract was read), and any community/referee reaction.

### Proof of the Linear Hadwiger Conjecture (Norin–Steiner, GPT-6 Astra-assisted)
- stage: seed | confidence: medium | first_seen: 2026-10-06 | last_evidence: 2026-10-04
- what: claims a full proof of the LINEAR Hadwiger conjecture — there exists a constant C such that
  every K_t-minor-free graph is Ct-colorable — the asymptotic/linear form of Hadwiger's 1943
  conjecture that has been a central target of structural graph theory for decades (the strongest
  prior published bound, O(t log log t)-colorability, is due to Delcourt–Postle and Norin–Song,
  2023/2024; the original EXACT (t-1)-colorability form of Hadwiger's conjecture remains open and is
  NOT addressed by this paper). Authors: Sergey Norin (McGill) — one of the field's leading
  researchers on exactly this problem, co-author of the prior best bound — and Raphael Steiner, who
  is independently already active on this ledger's Hadwiger cluster (co-author of the 2026-09-29
  "Disproof of the dominating Hadwiger conjecture," arXiv:2609.35361, already queued). The paper's
  own abstract states plainly: "The proof was found by GPT-6 Astra, following the directions by the
  authors." DOMAIN-CADENCE LANDMARK (resolution of a major, heavily-studied named conjecture) —
  EXTREME unrefereed-preprint + AI-disclosure-lane caution: two days old, zero independent human
  engagement yet, and an extraordinary claim (a full resolution would be one of the most significant
  graph-theory results of the year). AI-WATCH: note the GPT-6 Astra assistance; track the
  mathematical result, not the model.
- evidence:
  - 2026-10-04 (v1) — https://arxiv.org/abs/2610.05291 — Sergey Norin, Raphael Steiner, "A Proof of
    the Linear Hadwiger Conjecture": states $K_t$-minor-free graphs are $Ct$-colorable for some
    absolute constant $C$; proof credited to GPT-6 Astra under the authors' direction. Abstract +
    authors + date verified via arXiv API this session.
- notes: 2026-10-06 (daily, seed creation): caught in today's full math.CO RSS sweep (same-day v1,
  2 days old). Promoted straight to seed per the Hopf-problem/S⁶ (Alpöge–Claude) and ζ(5)/Lehmer
  precedents — a named, credentialed mathematician (here, the field's own leading expert on this
  exact problem) presenting an AI-assisted result under their own name clears the domain-cadence
  landmark bar even pre-referee; confidence held at medium (not high) given zero independent
  engagement so far and the sheer size of the claim. Watch for: referee/community reaction (expect
  fast, high-profile scrutiny given Norin's standing in this exact subfield), any gap found, and
  whether this interacts with the already-tracked "dominating Hadwiger" disproof (same Steiner,
  different sub-conjecture — the two are logically independent, not a contradiction).

### Refutation of the 3SUM and APSP hypotheses (Alman–Vassilevska Williams, Claude-discovered)
- stage: seed | confidence: medium | first_seen: 2026-10-09 | last_evidence: 2026-10-11
- what: axis-1/axis-5 DOMAIN-CADENCE LANDMARK (AI-discovered, human-confirmed, Lean-formalized): the
  first polynomial-factor improvements over the textbook running times for 3SUM and All-Pairs
  Shortest Paths (APSP) — two of fine-grained complexity theory's oldest, most-studied barriers
  (the 3SUM hypothesis dates to the 1990s; the APSP hypothesis anchors a large body of conditional
  lower bounds). Josh Alman (Columbia) and Virginia Vassilevska Williams (MIT, a co-originator of
  the fine-grained-complexity framework these hypotheses sit in) give a deterministic $O(n^{1.9992})$
  3SUM algorithm and an $O(n^{2.9995})$ APSP algorithm, REFUTING both hypotheses outright, plus (via
  known reductions) the Exact Triangle hypothesis, the Zero-Weight $k$-Clique hypotheses, and three
  rectangular Online Matrix-Vector conjectures — all via one new algorithm for "thin" matrix
  products built from a Coppersmith/Schönhage rectangular-multiplication variant. Per the paper's own
  abstract (opened directly via the arXiv HTML full-text this session): "Claude, an AI model
  developed by Anthropic, discovered the algorithm that refutes" the hypotheses; the two named
  human authors then "worked to understand, simplify, strengthen, and extend" it, and "Claude also
  verified this paper's main results using the Lean 4 proof assistant" with Mathlib — matching this
  ledger's standing AI-discovered/human-confirmed pattern (the Komlós/Beck-Fiala trend) PLUS an
  independent Lean-formalization verification signal (the Hopf-problem/S⁶, FLT precedents), a
  stronger combination than either alone. Unrefereed-preprint caution still applies (5 days old,
  no independent human engagement yet beyond the named co-authors) but the established-researcher
  co-authorship + Lean-checked main results clears the domain-cadence landmark bar pre-referee, per
  the Hadwiger/Hopf-S⁶ precedent.
- evidence:
  - 2026-10-05 (v1) — https://arxiv.org/abs/2610.06783 — Josh Alman, Virginia Vassilevska Williams,
    "Truly Subquadratic 3SUM and Truly Subcubic APSP via Triangles in Sparse Lopsided Graphs":
    $O(n^{1.9992})$ 3SUM, $O(n^{2.9995})$ APSP, refuting both hypotheses + Exact Triangle +
    Zero-Weight $k$-Clique + three rectangular OMv conjectures (van den Brand–Nanongkai–Saranurak).
    Abstract/authors/date verified via arXiv API; the AI-discovery/Lean-verification statements
    verified via the arXiv HTML full-text (`arxiv.org/html/2610.06783v1`) this session — present in
    the paper's own abstract/intro, not only secondary coverage.
  - 2026-10-08 (commit date; found 2026-10-09) — https://github.com/anthropics/formal-math —
    `3sum-apsp/` subdirectory: Anthropic's Lean 4/Mathlib formalization of the paper's headline
    theorems, Palomar-registry comparator-checked. Repo README table (opened directly via
    `raw.githubusercontent.com` this session) confirms the project and its toolchain pin.
  - 2026-10-11 (v1) — https://arxiv.org/abs/2610.15663 — Karingula, Lovett, "A simplified proof of
    polynomial improvements for 3SUM and APSP": an independent HUMAN simplification of the
    Alman–Vassilevska Williams result (weaker exponents, built on Schönhage's inner/outer-product
    identity via "selected-entry matrix multiplication"), a positive independent-engagement/
    vetting signal distinct from the named co-authors or the Lean formalization. Abstract/authors
    verified via arXiv API this session; found via today's exploration-slot pass over cs.CC.
  - 2026-11-12 — https://hexagonmath.org/2611.00388v1 — "Which Fine-Grained Lower Bounds Survive
    the Refutation of 3SUM and APSP?": a follow-on analysis determining which conditional lower
    bounds derived from the now-refuted hypotheses still survive, and extending Majdoddin's
    triangle-counting method to a wider exponent range ($\varepsilon<0.17843$ when prescribed
    edges are known in advance), confirming Majdoddin's own numerical estimate. Opened and read
    via the hexagonmath `/rss/all` feed this session.
- notes: 2026-10-09 (daily, seed creation): caught via the GitHub repo-watch lane — the
  `anthropics/formal-math` README's project table gained a SECOND row (`3sum-apsp/`, alongside the
  already-tracked `zeta23/` zeta-zeros formalization); the underlying arXiv paper itself (2610.06783,
  2026-10-05) was NOT separately caught by this session's math/physics category sweep (it crosses
  cs.DS/cs.CC, outside the swept math/physics category set) — a title-blind, category-blind miss
  the GitHub watch lane happened to catch instead; worth the weekly considering whether cs.DS/cs.CC
  need a standing (not just off-axis-rotation) presence given this is the second complexity-theory
  landmark this ledger has caught off-category (after the 2608-era Linear-Hadwiger-adjacent misses).
  Promoted straight to seed per the Komlós/Beck-Fiala (AI-discovered) and Hopf-S⁶/FLT
  (Lean-formalized) precedents combined. Also added to `study_shelf`. Watch for: independent human
  engagement/citations, a referee outcome, or a found gap in either the algorithm or the Lean
  formalization.
  - 2026-10-15 (daily): FIRST independent human engagement — Karingula–Lovett's simplified proof
    (see evidence) confirms the headline result holds up to independent scrutiny (weaker exponents,
    different technique), answering part of the "watch for" above. last_evidence advances
    2026-10-05 → 2026-10-11.

### Proof of the hyperkähler SYZ conjecture (Engel–Mauri)
- stage: seed | confidence: medium | first_seen: 2026-10-09 | last_evidence: 2026-10-08
- what: axis-1 DOMAIN-CADENCE LANDMARK (resolution of a long-standing named conjecture): claims a
  full proof of the hyperkähler SYZ conjecture — that sections of a power of any non-trivial nef
  isotropic line bundle on a hyperkähler manifold define a Lagrangian fibration — the hyperkähler
  analogue of the Strominger–Yau–Zaslow mirror-symmetry conjecture, open and actively studied for
  ~15+ years (prior partial results, e.g. Bakker–Svaldi 2021, required extra hypotheses). NOT a
  fringe claim: a 2025 Engel–Filipazzi–Mauri–Svaldi paper on boundedness of hyperkähler varieties
  (arXiv:2507.00973, cited 17 times per this session's search) is explicitly CONDITIONAL on this
  exact conjecture, and both authors are core members of the ERC "HyperK" research program and the
  Simons Collaboration on Moduli of Varieties — i.e. this is a central open problem in an active,
  well-resourced research cluster the authors themselves belong to, not an isolated claim.
  Unrefereed-preprint caution applies (days old, no outside engagement yet) but established-
  researcher authorship in exactly this subfield clears the domain-cadence landmark bar pre-referee,
  per the LeBrun–Salamon/Linear-Hadwiger precedent.
- evidence:
  - 2026-10-08 (v1) — https://arxiv.org/abs/2610.12277 — Philip Engel, Mirko Mauri, "Hyperkähler SYZ
    conjecture": one-paragraph abstract states the full result. Abstract + authors + date verified
    via arXiv API this session.
- notes: 2026-10-09 (daily, seed creation): caught in today's math.AG fresh-batch triage (title
  alone named the conjecture). Corroborating context (Engel's 2025 conditional-boundedness paper,
  the ERC HyperK project, the Simons moduli-of-varieties collaboration) found via `tvly search` this
  session, not opened as evidence (secondary confirmation of significance only). Watch for: referee/
  community reaction, any gap found, and whether the 2025 Engel–Filipazzi–Mauri–Svaldi boundedness
  result becomes unconditional as a consequence.

### 2026 Nobel Prize in Physics — Francis Halzen / IceCube astrophysical neutrinos
- stage: seed | confidence: high | first_seen: 2026-10-07 | last_evidence: 2026-10-06
- what: the Royal Swedish Academy of Sciences awarded the 2026 Nobel Prize in Physics to Francis
  Halzen (University of Wisconsin–Madison) "for decisive contributions to the IceCube Neutrino
  Observatory and the discovery of high-energy neutrinos of astrophysical origin" — a DOMAIN-CADENCE
  LANDMARK (the field's own highest recognition, crowning a foundational axis-3 discovery this radar
  already tracks via the IceCube source). Single laureate, official announcement, not an AI-assisted
  or unrefereed claim — confidence `high` from the outset (an official Nobel Committee decision is
  about as authoritative as a primary source gets in this domain).
- evidence:
  - 2026-10-06 — https://www.nobelprize.org/prizes/physics/2026/press-release/ — official Royal
    Swedish Academy of Sciences press release, opened directly this session: confirms laureate,
    institution, and citation wording verbatim.
  - 2026-10-06 — https://icecube.wisc.edu/category/news/feed/ — IceCube's own news feed (DAILY-tier
    primary source) corroborates: "Francis Halzen, IceCube principal investigator, wins 2026 Physics
    Nobel Prize," opened this session via the standing RSS heal.
- notes: 2026-10-07 (daily, seed creation): caught in today's routine IceCube news-feed check (the
  announcement happened 2026-10-06, one day before this session); cross-verified directly against
  the official nobelprize.org press release. SOURCES.md's "Prizes & recognition" list only tracked
  Abel/Breakthrough/Shaw/Fields — the Nobel Prize in Physics was a listed-but-missing coverage gap,
  now added (see SOURCES.md) with a chase-daily exception for the first week of October (Nobel
  announcement week), mirroring the existing ICM/Fields exception. Watch for: the Nobel Committee's
  "Popular information"/"Scientific background" documents (not yet opened this session) if more
  physics detail is needed later; no vetting-status tracking needed here (a Nobel award is not a
  provisional claim).

### AI-assisted Lean formalization of the Hamilton–Perelman proof of the Poincaré Conjecture (two independent efforts)
- stage: seed | confidence: medium | first_seen: 2026-10-07 | last_evidence: 2026-10-09
- what: PROMOTED from the observation_queue (was held there since 2026-09-29, arXiv:2609.33842) now
  that a SECOND, apparently independent team has published its own AI-assisted Lean 4 formalization
  of the same landmark result (axis 5, computer-assisted/formalized math) within 8 days of the first.
  Qin/Liao/Khaitan/Chow (2609.33842, 09-29) formalized the Hamilton–Perelman Ricci-flow-with-surgery
  proof of the smooth 3D Poincaré conjecture plus the Moise smoothing theorem (topological form).
  Zhang/Delaval/L.Chen/J.Chen/Xu/Liao/Jiang/C.Liu/Dong (2610.08329, 10-06) present a SEPARATE
  AI-assisted Lean 4 formalization effort, focused on the organizational/methodology side (proof
  blueprints, milestone statements enabling parallel agent work, human-intervention analysis) —
  DIFFERENT lead author and 9-person team vs. the first paper's 4; one shared surname ("Liao") but
  different given names (Yuan Liao vs. Yuxuan Liao) in the two author lists — treated as DISTINCT
  individuals absent contrary evidence, making this a genuinely independent second formalization,
  not a duplicate. Two independent formalization efforts of the same Millennium-Prize-adjacent
  theorem, each AI-assisted, within little over a week — this clears the "≥2 independent
  authoritative sources corroborate on concrete artifacts" confidence bar in addition to the
  single-landmark domain-cadence bar already met by the first paper alone (same precedent as
  Hadwiger/Hopf-S⁶/ζ(5)/FLT-in-Lean). Confidence held at `medium` (not `high`) because neither Lean
  artifact itself has been independently RUN/checked by a third party yet (per the FLT-in-Lean/
  Buzzard precedent) — two groups attempting the SAME formalization is a strong but not yet
  equivalent signal to independent verification of one.
- evidence:
  - 2026-09-27 (v1; CORRECTED 2026-10-17, W42 Amendment I check — a date-entry error, not a
    revision: this line had recorded 2026-09-29) — https://arxiv.org/abs/2609.33842 — Qin, Liao,
    Khaitan, Chow, "A Lean Formalization of the Hamilton–Perelman Proof of the Three-Dimensional
    Poincaré Conjecture": formalizes the smooth + topological 3D Poincaré conjecture. Abstract +
    authors verified via arXiv API (prior session).
  - 2026-10-06 (v1) — https://arxiv.org/abs/2610.08329 — Zhang, Delaval, Chen, Chen, Xu, Liao,
    Jiang, Liu, Dong, "An AI-Assisted Formalization of the Poincaré Conjecture": a second,
    differently-staffed AI-assisted Lean 4 formalization project of the same theorem, with an
    accompanying analysis of the human-in-the-loop workflow. Abstract + authors verified directly
    via arXiv API this session.
  - 2026-10-09 (v1) — https://arxiv.org/abs/2610.13897 — Liao, Qin, Chung, Khaitan, Zhang, Lin,
    Zhang, Zhu, Lu, Chow, "A Lean Formalization of the Hamilton–Perelman Proof of Thurston's
    Geometrization Conjecture": the SAME core team as the trend's first effort (2609.33842 —
    Liao, Qin, Khaitan, Chow all co-author both) escalates from the 3D Poincaré conjecture (a
    special case) to the FULL geometrization conjecture (every closed orientable 3-manifold
    decomposes into geometric pieces) — a substantially broader formalization target, not a
    duplicate. Abstract verified via arXiv API this session; no explicit AI-assistance statement
    in this paper's own abstract, inferred from the overlapping author team and methodology.
- notes: 2026-10-07 (daily, promotion from queue to seed): the second independent effort is the
  triggering event — caught in today's full math.GT/AT RSS category sweep. Watch for: whether the
  two teams' Lean repositories are cross-checked against each other (a natural next vetting step
  given they target the identical theorem), any referee/expert commentary (e.g. from Buzzard, who
  verified the FLT-in-Lean proof), and whether the "Liao"/"Liao" name coincidence is in fact the
  same individual working across both teams (would weaken, not strengthen, the independence case —
  flag for correction if confirmed either way).
  - 2026-10-12 (daily): the first team (Liao/Qin/Khaitan/Chow) escalates its own formalization from
    Poincaré to the full geometrization conjecture — caught via the daily math.DG sweep, not a new
    independent group but a major scope expansion on the same tracked effort. last_evidence
    advances 2026-10-06 → 2026-10-09.

### OpenAI's mass mathematical-results disclosure (github.com/openai/math, Oct 2026 — 722 manuscripts/372 result families)
- stage: seed | confidence: medium | first_seen: 2026-10-07 | last_evidence: 2026-11-23
- what: axis-5 AI-WATCH-LANE event (track the RESULTS, not the AI method): on 2026-10-06, OpenAI
  published "Sharing AI progress in mathematics" (openai.com) alongside a public GitHub repository,
  `github.com/openai/math` (Apache-2.0), containing 722 manuscripts organized into 372 "result
  families" across 17 mathematical disciplines, all produced by an unreleased internal frontier
  model. This is a DOMAIN-CADENCE LANDMARK by sheer scale alone — roughly 37× the size of the
  already-tracked "Ten Advances" disclosure (2026-08-01, queued) — and explicitly implements the
  agmai.org (IAS Advisory Group on Mathematics and AI) "Responsible Release" recommendations this
  ledger has been watching for since 2026-09-29. Many of the 372 families name long-standing,
  famous open problems; a non-exhaustive sample from the repo's own CONTENTS.md (titles + one-
  paragraph descriptions, opened directly this session): #002 a case of the full Birch–
  Swinnerton-Dyer formula (density-one quadratic twists, Selmer corank ≤1) — a Clay Millennium
  Prize Problem; #001 Milne's rationality conjecture for abelian varieties; #003 "the quasi-Riemann
  hypothesis" (a zero-free-region result for Dirichlet L-functions, per secondary press coverage);
  #004 Hilbert's tenth problem over ℚ; #005 irrationality of Catalan's constant; #018 the
  Margulis–Platonov conjecture; #087 the Mahler conjectures; #102 the Unique Games Conjecture;
  #107 matrix multiplication with exponent ≤9/4; #143 Hilbert's sixteenth problem (uniform limit-
  cycle bounds); #179 the circulant Hadamard conjecture; #266 exactly three mutually unbiased bases
  in dimension six; #304 the Hilbert–Smith conjecture. HEAVIEST possible hype-skepticism caution —
  this exceeds even the already-extreme "Ten Advances" and OpenAI Navier-Stokes precedents in
  scale: wholly AI-generated, UNREFEREED, from an unreleased model, with (per secondary press —
  CellCog, BigGo Finance, Unite.AI, opened via `tvly search` this session, NOT independently
  verified per-count by this radar) Lean formalizations for only ~162 of the 722 manuscripts'
  main results; average compute reported as ~3 hours of ChatGPT-Pro-equivalent thinking per result.
  PROVISIONAL across the board — track outcomes per-result as they individually surface (same
  protocol as the Ten Advances cluster, which already produced one independent-engagement signal
  and one misconduct finding against a single result). Held at `seed` (not merely queued) given the
  unprecedented scale is itself the landmark event, matching this ledger's domain-cadence precedent
  of seeding a landmark EVENT even pre-referee (Hadwiger/Hopf-S⁶ precedent) — but this is an explicit
  departure from the "Ten Advances" precedent (held at queue), flagged below for the next weekly to
  reconcile.
- evidence:
  - 2026-10-06 — https://openai.com/index/sharing-ai-progress-in-mathematics/ — OpenAI's own
    publication page, opened directly via `curl`/`tvly extract` this session: confirms date, scale,
    Apache-2.0 GitHub release, Lean formalizations, and explicit reliance on agmai.org's
    recommendations.
  - 2026-10-07 — https://github.com/openai/math/blob/main/history.md — OpenAI's own changelog,
    opened directly via `raw.githubusercontent.com` this session: WITHDREW three manuscripts
    ("Algebraicity of Weil classes on split abelian eightfolds," "Algebraicity of Kuga–Satake
    Correspondences for K3 Surfaces," "The rational Hodge conjecture for products of K3 surfaces" —
    the last a case of the Hodge conjecture, a Clay Millennium Prize Problem) after a sign error
    invalidated a shared stabilization-trace-cancellation argument; separately REVISED 14 other
    manuscripts (proof repairs across a Lipschitz-heights/Ashkin–Teller cluster, a Kähler
    minimal-model/abundance cluster, a taming/hypersymplectic-deformation pair, one incompressible-
    transport paper, and a citation fix on the BSD-case manuscript) and added 6 more Lean
    formalizations (now 300/719 ≈ 42% formalized; total manuscript count 722→719 post-withdrawal).
  - 2026-11-23 (found this session via the daily math.CA title-triage sweep) — Xiangyu Wang,
    "OpenAI's proof of the local smoothing conjecture: A harmonic analytic perspective" —
    https://arxiv.org/abs/2611.30274 — a SECOND independent expert exposition of result-family #079
    (the local-smoothing-conjecture claim), written "for harmonic analysts who may be new to
    quaternionic Monge-Ampère equations," distinct from Temur's engagement already evidenced below —
    two independent authors now digesting the same result-family. Abstract + author verified via
    direct arXiv API fetch this session.
  - 2026-10-21 (v1; found this session via a fresh math.AG arXiv sweep) — Jenia Tevelev (UMass
    Amherst), "On OpenAI's proof of the Nagata conjecture" — https://arxiv.org/abs/2610.30050 — an
    expert's own expanded exposition (from a seminar talk) of this disclosure's claimed proof of the
    1959 NAGATA CONJECTURE (interpolation of fat points on P², a famous open problem since 1959,
    related to Seshadri constants) — confirmed via a direct search of `openai/math`'s own catalogue
    (sites.pitt.edu mirror) that this is part of the Oct-6 result-family set, not a separate claim.
    Tevelev calls the proof "remarkably simple" and raises no correctness caveat anywhere in the
    note — a notably clean positive vetting signal for this specific result-family, though still
    only one expert's reading, not a referee report. Abstract + full text opened via `WebFetch` this
    session (v1 only, submitted 2026-10-21).
  - 2026-10-21 (v1; found 2026-10-23 via that session's math category-rotation batch) — Zhentao Li,
    "A note on the proof of Barnette's conjecture" — https://arxiv.org/abs/2610.30490 — a "digested
    exposition of OpenAI's generated proof of Barnette's conjecture" (1969: every cubic 3-connected
    bipartite planar graph is Hamiltonian) — a long-standing named graph-theory conjecture, same
    individually-engaged-result-family pattern as Tevelev's Nagata exposition above; confirms this
    result-family is part of the Oct-6 disclosure (cites `\cite{openai-barnette}`). Abstract +
    author verified via arXiv API this session.
  - 2026-10-21 (community pulse, Gil Kalai's blog, opened directly this session) —
    https://gilkalai.wordpress.com/2026/10/21/progress-on-borsuks-problem-and-answer-to-tyi-60/ —
    reports that one of the Oct-6 disclosure's ~700 manuscripts claims $f(9) > 10$ for BORSUK'S
    PROBLEM (the minimum number of smaller-diameter pieces needed to cover any diameter-1 set in
    $\mathbb{R}^9$), exceeding the standard $d+1$ bound, via a topological argument related to the
    Borsuk–Ulam theorem; the main theorem is reported as Lean-formalized. Kalai notes the
    construction's correctness "still needs careful checking," and a commenter (Gábor Damásdi)
    argues the specific finite example used does not settle the separate, still-open FINITE
    question $g(d)$ vs $f(d)$ (every finite subset is 8-colorable) — a genuine, specific correctness
    caveat on record, not mere hedging. No direct arXiv/GitHub primary link opened this session
    (Kalai's post does not give one); treated as a secondary pointer to a named result-family within
    the already-evidenced disclosure, not an independent primary.
  - 2026-11-01 (v1), revised 2026-11-18 (v2) — https://arxiv.org/abs/2611.01745 — Nikita
    Markarian, "A remark on the AI proof of the Deligne–Drinfeld conjecture": an independent
    geometric interpretation of the projection/reconstruction underlying result-family #008 (the
    Deligne–Drinfeld conjecture proof, confirmed against `openai/math`'s own `CONTENTS.md` this
    session) — makes the OpenAI proof's implicit reconstruction explicit via an independent
    method. A positive, substantive vetting-engagement signal on one specific result-family, same
    pattern as the Tevelev/Nagata and Zhentao-Li/Barnette expositions above. Abstract + author
    verified via direct arXiv page fetch this session.
  - 2026-09-28 (v1, revised 2026-09-29 v2, 2026-11-18 v3; found via a MathHelm forum sweep this
    session, a new source — see SOURCES.md staging) — https://arxiv.org/abs/2609.35406 — Zhen
    Lei, Xiao Ren, "Finite-Time Blowup for
    Navier-Stokes with Smooth Forcing, Part I: Construction of Self-Similar Solutions with
    Admissible Stress and Flat Remainder": an independent "readable and accessible version of the
    profile-construction part of OpenAI's manuscript," explicitly stating "We regard OpenAI's work
    as a major advance on the Navier-Stokes Millennium Prize Problem." The first NAMED-EXPERT
    engagement constructively reconstructing (not merely critiquing) part of OpenAI's claimed
    Navier-Stokes finite-time-blowup proof (queued separately below, still unrefereed) — Zhen Lei
    is an established Navier-Stokes researcher (Fudan University). A companion "Part II" is
    referenced but its arXiv id was not located this session (chase next session). Abstract +
    authors verified via direct arXiv page fetch this session.
  - 2026-11-19 — https://arxiv.org/abs/2611.26524 — Shiyu Zhang, "Remark on Kobayashi's conjecture:
    a volume Schwarz lemma": an explicit "expository reconstruction of OpenAI's proof of
    Kobayashi's ampleness conjecture for compact Kähler manifolds, together with new results" —
    confirmed against `openai/math`'s own `CONTENTS.md` this session as result-family #051,
    "Kobayashi's canonical-ampleness conjecture" (every compact connected Kähler manifold of
    positive dimension with no nonconstant entire curve has ample canonical bundle). Same
    independent-reconstruction-plus-extension pattern as the Tevelev/Nagata, Zhentao-Li/Barnette,
    and Markarian/Deligne-Drinfeld items above. Abstract + author verified via direct arXiv page
    fetch this session.
  - 2026-11-04 (found this session via a MathHelm thread pointer) — https://arxiv.org/abs/2611.07085
    — Faruk Temur, "The square function estimates for cones in arbitrary dimensions and elliptic
    quadrics": derives sharp square-function estimates for the light cone (and, via affine
    sections, spheres/ellipsoids/paraboloids/hyperboloids) directly "from local-smoothing and
    auxiliary-energy statements in the October 25, 2026 OpenAI manuscript" — the FIRST located
    independent-expert engagement with result-family #079 ("Local smoothing for the Euclidean wave
    equation," the Sogge/Bochner-Riesz/Kakeya/Nikodym cascade claim), which this trend has been
    watching for since 2026-10-27 as its single largest-magnitude unvetted claim bundle after the
    BSD case. Abstract + author verified via direct arXiv page fetch this session.
- notes: 2026-11-20 (daily): two further independent-expert engagement items added (Zhang/
  Kobayashi-ampleness; Temur/local-smoothing-cascade, the latter the first engagement found with
  result-family #079 specifically — see the companion `observation_queue` entry on Mark Lewko's
  related, still-unpublished Kakeya-all-dimensions claim, which explicitly builds on the SAME
  Oct-25 OpenAI manuscript). Evidence cap reached again (10/10); the two most purely-general
  governance/reception posts (Tao's "Math 2.0," Huiberts' "This is normal bad work") were dropped
  to make room for these two specific-result engagements — no information lost (both remain
  summarized in this trend's own `what`/prior `notes`), only de-duplicated toward the
  per-result-family engagement signal this trend is tracking. last_evidence 2026-11-01 →
  2026-11-19.
- notes: 2026-11-24 (daily): a THIRD independent-expert engagement with result-family #079 added
  (Wang's local-smoothing exposition, found via today's math.CA title-triage) — now two separate
  authors (Temur, Wang) have each written their own digested account of this one claim, the
  strongest per-result-family engagement signal this trend has for any single family. Evidence
  cap reached again (10/10); dropped Hales' guest-post primer on Lean reliability (2026-10-09) —
  the most purely-general, least result-specific entry remaining, same de-duplication rationale as
  2026-11-20 — no information lost (summarized in this trend's own `what`). last_evidence
  2026-11-19 → 2026-11-23.
- notes: 2026-11-19 (daily): two independent-expert engagement items added above (Deligne-Drinfeld
  geometric reinterpretation; Navier-Stokes Part I reconstruction) — both found via MathHelm, a
  newly-discovered research-mathematician forum (staged in SOURCES.md this session). Evidence cap
  reached again (10/10); the live repo-listing and the generic AGMAI "declines to judge" entry were
  dropped to make room (both redundant with this trend's own `what` summary and with AGMAI's
  separate standing presence in SOURCES.md) — no information lost, only de-duplicated.
- notes: 2026-10-07 (daily, seed creation): caught via the Hacker News front page (683-point story)
  and corroborated independently via Gil Kalai's blog ("amazing") and r/OpenAI community-pulse
  threads naming several of the same results (Unique Games Conjecture, circulant Hadamard
  conjecture, no-4-MUBs-in-dimension-6) — all intake, not evidence; the GitHub repo and OpenAI's own
  page are the evidence. NOT independently verifying any individual one of the 372 claims this
  session (triage-for-cost; opening 722 manuscript PDFs is out of scope for a single daily run) —
  this entry tracks the DISCLOSURE EVENT, not the correctness of any specific result. FLAG FOR NEXT
  WEEKLY: (a) reconcile the queue-vs-seed inconsistency with the "Ten Advances" precedent (this
  session judged scale-as-landmark sufficient for seed; the weekly should decide if that reasoning
  holds or if this should demote to queue pending at least one independently-engaged result, as Ten
  Advances had); (b) consider whether axis-5 needs a standing "AI mass-disclosure" tracking
  structure distinct from a single evidence-capped trend block, since individual results within
  this release (e.g. the BSD case, if it draws expert engagement) may need their OWN trend/queue
  entries later, the way Ten-Advances result (3) and (9) each spawned independent follow-up items.
  Watch for: ANY expert engagement on the BSD-case claim specifically (a Millennium Prize Problem
  claim from this release would be the single biggest story this radar could register, bigger even
  than the already-tracked OpenAI Navier-Stokes claim) — chase this daily until a vetting signal
  appears.
  - 2026-10-13 (daily): community-reaction wave CONTINUES on Tao's blog beyond the Huiberts post
    above — "Additional recent pieces on math and AI" (2026-10-12) rounds up seven further
    opinion pieces (Kevin Buzzard, Alexander Gamburd, Harald Helfgott, Gil Kalai, Asaf Karaglia,
    Matilde Marcolli, Fenner Stanley Tanswell — named only in aggregate per the social-channel
    no-individual-naming-beyond-a-bare-URL norm, not individually opened this session); a guest
    post by Kate Stange and Edmund Harriss, "Illustration beyond Proof" (2026-10-11), takes the
    debate into mathematical-illustration practice rather than proof per se; Woit's "Slopocalypse"
    (2026-10-06, Not Even Wrong) is the same critique in the physics-commentary lane. None names a
    new on-axis primary result (all discourse ABOUT the disclosure event, already evidenced above)
    — logged as continued vetting-status/community-governance signal, not new evidence lines, to
    avoid note bloat. SEPARATELY: result-family #003 (the quasi-Riemann-hypothesis claim, named
    only in this trend's `what` text since creation) is PROMOTED today to its own seed trend —
    see "OpenAI's claimed proof of the quasi-Riemann Hypothesis" above — closing a self-inflicted
    capture-leak (a primary named only in prose, never given a discrete evidence/queue line) now
    that independent human engagement (a MathOverflow collaborative-verification proposal)
    specifically on that result-family has appeared, fulfilling note (b)'s standing flag that
    individual results inside this bundle may need their own trend entries.
  - 2026-10-08 (daily): vetting-status / community-reaction catch. (a) The Association for Human
    Mathematics (AHM), a newly-identified mathematician advocacy organization, published a
    statement (its own site, opened directly this session: https://www.ahmath.org — also reposted
    by Terence Tao, https://terrytao.wordpress.com/2026/10/07/ahm-statement-on-openais-october-6-release-of-mathematical-documents/)
    condemning the October 6 release as "a demonstration of power" rather than scholarship and
    urging mathematicians to "discontinue their work with OpenAI" — the first organized
    organizational (not just individual-blogger) pushback this ledger has tracked against an
    AI math disclosure. AHM staged as a discovered-source candidate in SOURCES.md. (b) Quanta
    Magazine, "As AI Closed In on 'Unique Games' Proof, Researchers Raced to Beat the Machines"
    (opened directly this session: https://www.quantamagazine.org/as-ai-closed-in-on-unique-games-proof-researchers-raced-to-beat-the-machines-20261007/)
    clarifies that OpenAI's release's unique-games-conjecture-adjacent claim is specifically a
    Lean-verified proof of Khot's "2-to-1 games conjecture," in an AI-generated manuscript with NO
    human editing or independent expert review — a concrete vetting-status data point (Lean-checked
    ≠ independently reviewed, same caveat as the Bastounis–Circelli–Hansen Navier-Stokes critique
    already tracked). The same article reports an independent HUMAN result rushed to preprint
    (mid-September 2026) by Dor Minzer (MIT) with graduate students Yumou Fei and Shuo Wang,
    proving a weaker "4-to-1 games conjecture" variant with the same key consequences, explicitly to
    predate the rumored OpenAI announcement — praised on record by Ryan O'Donnell (CMU) and Mark
    Braverman (Princeton). The underlying arXiv preprint was NOT located via the arXiv API this
    session (author-name search returned no September 2026 match) — queued below with the Quanta
    article as its only source pending primary-ID location (not evidence per the hard rules; chase
    next session).
  - 2026-10-09 (daily): AGMAI itself — the IAS advisory group whose "Responsible Release"
    recommendations this disclosure explicitly follows — published its own vetting-status statement
    on the release, "On OpenAI's Release of Mathematical Results" (agmai.org, dated 2026-10-06;
    opened directly via `WebFetch`/`tvly extract` this session — a primary already in the swept
    list, not previously captured as its own evidence/note, only alluded to generically on 10-07).
    Stance: explicitly declines to judge the results' correctness or endorse OpenAI's release
    process ("not a judgment... or an endorsement"), and places verification entirely in the
    mathematical community's hands ("only the mathematical community can undertake the assessment
    that is needed") — the disclosure is "a first step," understanding still to come. A concrete,
    named-institution confirmation of this trend's PROVISIONAL/unreviewed status, distinct from
    AHM's adversarial framing (10-08) and Quanta's Lean-checked-≠-reviewed clarification (10-07).
  - 2026-10-09 (daily): FIRST CONCRETE VETTING OUTCOME — caught via a Hacker News front-page story
    ("OpenAI withdraws three mathematical results," 276 points) pointing directly to OpenAI's own
    `history.md` changelog (opened directly this session, see evidence). On 2026-10-07 OpenAI
    withdrew 3 of the 722 manuscripts, including a claimed case of the HODGE CONJECTURE (a Clay
    Millennium Prize Problem) for products of K3 surfaces, after a sign error was found in a shared
    argument; separately revised 14 others with proof repairs. This is exactly the "gaps found in
    review" outcome the hard rules' hype-skepticism caution anticipates — a genuine, OpenAI-
    self-reported correction, not yet an outside referee, but the first concrete per-result
    vetting signal on this specific disclosure (distinct from the AHM/Quanta/AGMAI community-
    reaction notes above, which are about process/governance, not a specific result's correctness).
    Feeds directly into the next weekly's standing flag to reconcile this trend's scale-as-landmark
    seeding against the "Ten Advances" precedent — note that unlike Ten Advances' misconduct
    finding (plagiarism/prior-art, found by outsiders), this correction was self-reported by OpenAI
    itself as part of its own ongoing-revision process, a different and arguably healthier vetting
    pattern worth the weekly distinguishing.
  - 2026-10-12 (daily): COMMUNITY-GOVERNANCE continuation, two more named-mathematician voices on
    the standing AI-in-math vetting/values question this disclosure crystallized. (a) Terence Tao,
    "Math 2.0" (https://terrytao.wordpress.com/2026/10/10/math-2-0/, also a Caltech 2026 talk,
    front-paged on Hacker News 2026-10-11 at 366+364 points) — argues traditional ("Math 1.0")
    mathematical progress is valued not just for the proof itself but for the followup activity
    (talks, workshops, new collaborations, textbook digestion) a breakthrough generates, and that
    "Math 2.0" needs to value this more holistically if AI-generated proofs are not to short-
    circuit that process. (b) Thomas Hales, guest post on Tao's blog, "What mathematicians should
    know about the Lean Theorem Prover: questions of reliability and AI"
    (https://terrytao.wordpress.com/2026/10/09/what-mathematicians-should-know-about-the-lean-theorem-proverquestions-of-reliability-and-ai/)
    — a formal-verification expert's primer on what Lean-checked actually guarantees (and does
    not), aimed squarely at mathematicians evaluating AI-era Lean-formalization claims (directly
    relevant to this radar's own "Lean-verified ≠ independently reviewed" vetting caveat). Both
    opened directly this session. Intake-lane sources (Tao's blog); captured as evidence of
    continuing expert/community vetting discourse per the hard rules' "cite... expert commentary"
    allowance, not as new primary math results. last_evidence advances 2026-10-07 → 2026-10-10.
  - 2026-10-15 (daily): TWO closures. (a) The 4-to-1 Games Conjecture primary flagged
    "not located" since the 2026-10-08 report (Quanta's profile of Dor Minzer's human race against
    this disclosure's Unique-Games-adjacent claim) is now LOCATED: Fei, Minzer, Wang, "On the
    Hardness of 4-to-1 Games with Perfect Completeness" (https://arxiv.org/abs/2610.12378, v1
    2026-10-14), confirming Khot's 4-to-1 Games Conjecture (CCC 2002) with PERFECT completeness —
    stronger than the prior best (Dinur–Khot–Kindler–Minzer–Safra's almost-perfect-completeness
    result). Found via today's exploration-slot pass over cs.CC (the paper crosses cs.CC, outside
    this ledger's swept math/physics category set, so this was also a category-blind-miss catch,
    closed). Own queue line added (below) alongside this note per capture discipline. (b) Result-
    family #260 ("Spacetime Penrose inequalities…", OpenAI's own CONTENTS.md, dated 2026-10-05) is
    identified as this disclosure's claimed treatment of the general spacetime Penrose conjecture —
    see the new "spacetime Penrose conjecture" seed trend above, created this session after an
    independent human paper (Bray–Dolmen–Khuri–Schmidt) explicitly engaged with this exact claim.
    last_evidence advances 2026-10-10 → 2026-10-14 (the Penrose-family primary's own dated artifact).
  - 2026-W42 recalibration (RECONCILIATION, resolving the standing flag from this trend's own
    2026-10-07 creation note): HOLD at `seed` — the scale-as-landmark reasoning stands, now
    reinforced rather than merely asserted. Since creation, this disclosure has produced exactly
    the kind of independent-engagement and vetting-outcome signal the "Ten Advances" precedent
    (held at queue pending those) was waiting for: (a) a genuine, if self-reported, vetting
    OUTCOME — OpenAI's own 2026-10-07 withdrawal of 3 manuscripts including a claimed Hodge-
    conjecture case; (b) an individual result-family (#003, the quasi-RH claim) drawing
    independent human engagement specific enough to spin off its own seed trend (2026-10-13); (c)
    a second result-family (#260, spacetime Penrose) likewise spinning off after an independent
    human paper engaged with the identical claim (2026-10-15); (d) organized community-governance
    reaction naming this disclosure specifically (AHM's statement, AGMAI's statement, Tao's "Math
    2.0," Huiberts' "This is normal bad work"). This is a stronger evidentiary position than Ten
    Advances had when it was held at queue. Not promoted beyond `seed` (no referee outcome on the
    bulk of the 719 remaining manuscripts; this is still a disclosure-event trend, not a verified-
    results trend) and not demoted to queue. Standing watch (the BSD-case claim specifically)
    unchanged.
  - 2026-10-22 (daily): TWO more individually-engaged result-families, same pattern as #003
    (quasi-RH) and #260 (spacetime Penrose) above — a credentialed mathematician's own exposition
    of the NAGATA CONJECTURE claim (Tevelev, 2610.30050) and a community-flagged correctness caveat
    on the BORSUK'S-PROBLEM claim (Damásdi, via Kalai's blog) — see evidence above. Neither rises to
    its own seed trend (unlike #003/#260, no NEW independent primary artifact exists yet for either
    — Tevelev's note is exposition of the existing claim, and Damásdi's caveat is a blog comment,
    not a paper); both folded in here instead. last_evidence advances 2026-10-14 → 2026-10-21. Watch
    continues for the BSD-case claim and for whether either of today's two items draws a fuller
    independent write-up.
  - 2026-10-23 (daily): THREE more individually-engaged items, found via today's full-abstract pass
    over math.SG (post-mortem) and the math category-rotation batch (exposition + a self-admitted
    partial result). (a) — THE FIRST CONCRETE TECHNICAL POST-MORTEM on the 2026-10-07 Hodge-
    conjecture withdrawal: an unsigned/unidentified-author note, "Rigidity, flexibility, and a sign
    error" (https://arxiv.org/abs/2610.30976, math.SG, 2026-10-22) states plainly "[t]he documents
    [OAI26a, OAI26b, OAI26c] claimed to prove cases of the Hodge conjecture via homological mirror
    symmetry, before being withdrawn by OpenAI. We discuss the source of the error (but do not
    analyse the rest of the argument)" — the first technical (not merely process/governance)
    engagement with WHY the withdrawn manuscripts failed, beyond OpenAI's own self-reported
    changelog. Author identity not independently confirmed this session (not named in the abstract
    itself). Abstract opened via arXiv API this session; not added as a separate evidence line
    (cap already at 10 after today's Barnette addition) — cited here, URL is the citable primary.
    (b) Zhentao Li's Barnette's-conjecture exposition (above) — see evidence. (c) BELOW-BAR, not
    added as evidence: el Houcein el Abdalaoui, "OpenAI partially disproves Littlewood's 1961
    $L^\alpha$-flat theorem" (https://arxiv.org/abs/2610.30797, 2026-10-22) — the author's own
    abstract calls OpenAI's counterexample "only a limited refutation, as such sequences fail to
    satisfy an implicit assumption of Littlewood's theorem" — a self-admitted partial/qualified
    result, routed to `observation_queue` instead (cross-referenced to this trend) rather than
    consuming an evidence slot. last_evidence unchanged at 2026-10-21 (Barnette's exposition is
    dated the same day; the sign-error post-mortem (2610.30976) is dated 2026-10-22 but was not
    given its own evidence line — see above).
  - 2026-10-26 (daily): COMMUNITY-GOVERNANCE continuation. (a) AGMAI published a new statement,
    "Disadvantages of Designating Mathematicians for AI Output Releases" (agmai.org, dated
    2026-10-25; also a guest post on Terence Tao's blog,
    https://terrytao.wordpress.com/2026/10/25/disadvantages-of-designating-mathematicians-for-ai-output-releases/,
    opened directly via WebFetch this session) — argues AI labs should stop designating specific
    mathematicians to receive and develop AI-generated math output ahead of the wider community
    ("on balance the disadvantages outweigh the advantages": delayed/unequal access, denied agency,
    biased selection, borrowed reputation, and being unnecessary given recent organic community
    engagement), recommending instead its own September 29 pathway 2A/2B recommendations (improved
    citations, independent repositories, process disclosure, Lean formalization, community-
    understanding funding). Confirmed live on agmai.org's own page (opened directly this session)
    alongside its Oct 6 and Sep 29 statements. (b) A new COMMUNITY INFRASTRUCTURE project launched:
    "oai-math-revised" (https://github.com/mathcommunity/oai-math-revised, browsable at
    https://mathcommunity.github.io/oai-math-revised/), a guest post on Terence Tao's blog by
    Abhinav Nellore, Johannes Schmitt, Soledad Villar, and Rachel Ward (2026-10-24, opened directly
    via WebFetch this session) — a volunteer-run hub inviting students/postdocs/professors to
    review and improve OpenAI's math write-ups ("can be difficult to understand and can have
    incomplete citations"), distinct from AGMAI (advisory/coordination, not line-editing). Tao's
    own comment gives a concrete example already in progress: his pull request on the
    Landau-Siegel-zeros write-up now cites the independent follow-ups already tracked on this
    ledger's quasi-Riemann-Hypothesis trend (Banks, Kerr, Green) plus his own blog post.
    Comment-section reception is mixed/critical (unpaid-labor-for-a-for-profit-company concerns; a
    pointer to mathhelm.org as an alternative non-profit venue, not independently verified this
    session). Both mathcommunity.github.io/oai-math-revised and mathhelm.org staged in SOURCES.md
    as discovered-source candidates (1 sighting each). last_evidence advances 2026-10-21 →
    2026-10-25.
  - 2026-10-27 (daily): THREE more manuscript-set additions, per OpenAI's own `history.md`
    changelog (Oct 26 entry, opened directly via `raw.githubusercontent.com` this session) and a
    new OpenAI publication page, "Working with academic communities to build scientific
    understanding" (https://openai.com/index/building-scientific-understanding-with-academic-communities/,
    opened via `tvly extract` this session — direct `curl`/`WebFetch` 403; found via a 706-point
    Hacker News front-page story). (a) Result-family #378, "Disproof of the Exponential Time
    Hypothesis" (`CONTENTS.md`, confirmed via `history.md`'s Oct 26 entry) — SPLIT into its own new
    seed trend below (independent same-day Anthropic claim on the identical hypothesis). (b)
    Result-family #079, "Local smoothing for the Euclidean wave equation" — claims Sogge's local
    smoothing conjecture for the wave equation in EVERY spatial dimension at least two, which the
    paper says implies the Bochner-Riesz conjecture, the Kakeya and Nikodym maximal conjectures
    (every Euclidean Kakeya set has full Hausdorff dimension), sharp Stein square-function bounds,
    and Fourier restriction estimates for the sphere/paraboloid/cone — a CASCADE of some of harmonic
    analysis's most famous open problems, Lean-formalized (lean/docs/079.md); supersedes an earlier,
    narrower manuscript in the same disclosure restricted to 3 dimensions ("Critical local smoothing
    for the three-dimensional wave equation," Sept 24 2026). EXTREME hype-skepticism caution —
    wholly AI-generated, unrefereed, and this is now the single largest-magnitude claim bundle in
    this disclosure after the BSD case; watch for ANY expert engagement (Kakeya/restriction
    specialists) as a top daily-chase priority alongside the BSD case. (c) A Lean formalization was
    added for the rational Hodge conjecture for CM abelian varieties (a Millennium Prize Problem
    case, same class as the already-tracked BSD/Hodge families). last_evidence advances 2026-10-25
    to 2026-10-26. See also the new "OpenAI's claimed proof of Yang-Mills existence..." seed trend
    below (same Oct 26 publication page, a THIRD, physics-side announcement) and AGMAI's same-day
    "Recommendation for Immediate Release of Yang-Mills AI Output" statement (agmai.org, opened
    directly this session) — cross-referenced there rather than duplicated here.
  - 2026-10-28 (daily): mainstream-press corroboration of the #079 (local-smoothing/Kakeya/
    Bochner–Riesz/Nikodym cascade) and Yang–Mills items from a NEW named-source: Scientific
    American's Joseph Howlett, "OpenAI just scooped mathematicians' work on another
    million-dollar problem" and "Dueling proofs from OpenAI and Anthropic astound scientists"
    (both 2026-10-27; the first 404'd on a direct `WebFetch` re-check this session, the second
    opened cleanly — cited in full on the Yang–Mills and ETH-refutation trends respectively) —
    the press frames #079's Hausdorff-dimension consequence plainly as "the Kakeya conjecture in
    every dimension," and separately reports that AGMAI (OpenAI's own organized advisory panel)
    says OpenAI's own approach on the Yang–Mills and ETH releases CONFLICTS with AGMAI's own
    guidance on two of the three Oct 26 results — a sharper governance criticism than AGMAI's own
    on-site statement conveyed directly. Not given its own evidence line (cap reached); logged
    here per capture discipline since it names and press-frames result-family #079 specifically.
    last_evidence advances 2026-10-26 → 2026-10-27.
  - 2026-W44 recalibration (capture-leak catch via the WEEKLY-SWEPT institute sweep, not the daily
    governance-commentary lanes): the Isaac Newton Institute (Cambridge) — a tracked WEEKLY-SWEPT
    source — posted its OWN director's statement, "Statement from INI Director on 722 OpenAI
    results" (https://www.newton.ac.uk/news/ini-news/statement-from-ini-director-on-722-openai-results/,
    dated 2026-10-07, opened via `curl` this session after `WebFetch`/`tvly` both failed — see
    `logs/source_rotation.md`), a FOURTH institutional voice (after AGMAI, the mathcommunity hub,
    and Scientific American's reporting) reaffirming institutional engagement with the disclosure
    without taking a position on specific claims. 24 days old when found — a backfill catch, this
    time from a source that WAS on the swept list all along (unlike the Vaught's-conjecture/CFSG-
    class misses, which came from entirely unswept channels); the gap here is that INI's own news
    page had not been opened since this trend's creation. Not given its own evidence line (cap
    full); logged per capture discipline. No last_evidence change (predates 2026-10-27). Also
    found on the same page: INI's 2026-09-09 commentary on the OpenAI Navier–Stokes claim,
    cross-referenced to the standing Navier-Stokes/Buckmaster-Alpöge authorship-dispute thread
    (below-bar, not re-opened this session).
  - 2026-11-02 (daily): THREE further governance/community-response developments found via Terence
    Tao's blog (already-tracked source), all opened directly this session, none a new math result
    (logged per capture discipline, cap full, no new evidence line): (a) "Mathematics has changed.
    Let's act like it" (guest post by Frank Calegari, a prominent number theorist,
    https://terrytao.wordpress.com/2026/11/01/mathematics-has-changed-lets-act-like-it/,
    2026-11-01) — a named-expert reaction to the Oct-6 disclosure's significance ("a watershed in
    the history of mathematics"). (b) "The mathematical sciences in an AI-enabled world"
    (https://terrytao.wordpress.com/2026/10/31/the-mathematical-sciences-in-an-ai-enabled-world/,
    2026-10-31) — the UK's Academy for the Mathematical Sciences released a report under this
    title; ONLY Tao's summary of it was opened this session, NOT the Academy's own report PDF
    (located via `tvly search` at
    https://www.acadmathsci.org.uk/wp-content/uploads/2026/10/Mathematical_Sciences_AI_AcadMathsSci_Oct2026_preprint_final.docx.pdf
    but NOT independently opened/read this session) — the report's content itself is unverified,
    flagged for next session to open directly; acadmathsci.org.uk staged as a discovered-source
    candidate in SOURCES.md. (c) "Report of the Summit on Math Research in the Age of AI"
    (https://terrytao.wordpress.com/2026/10/30/__trashed/, 2026-10-30) — a guest post by the
    summit's organizers (Dan Freed, Larry Guth, Bryna Kra, Emily Riehl, Mohammed Abouzaid), a
    fourth institutional/governance voice alongside AGMAI, the mathcommunity hub and Scientific
    American's reporting. last_evidence advances 2026-10-27 → 2026-11-01 (Calegari post date).

### First operating thorium-229 nuclear clocks (Vienna + Beijing, independent teams)
- stage: seed | confidence: medium | first_seen: 2026-10-08 | last_evidence: 2026-10-07
- what: axis-3 DOMAIN-CADENCE LANDMARK (first-of-kind measurement/detection): the first SUSTAINED,
  operating nuclear clocks based on the thorium-229 nuclear isomer transition (long sought for
  ~20 years as a nuclear alternative to electronic atomic clocks, with potential sensitivity to
  fundamental-constant variation). Secondary press (Reuters, South China Morning Post,
  sciencemediacentre.es — opened via `tvly search` this session, NOT independently verified
  per-claim by this radar) reports TWO independent teams — a Tsinghua University (Beijing)-led
  group and a TU Wien (Vienna)-led group — each demonstrating sustained nuclear-clock operation,
  in simultaneous Nature publications; the press frames Beijing's clock as showing better
  stability. This session located and directly verified ONE underlying preprint, a USTC
  (Jian-Wei Pan group, Hefei) collaboration with TU Wien co-authors (Schumm, Beeks), demonstrating
  30-hour continuous feedback-locked operation. The distinct Tsinghua-only and/or TU-Wien-only
  Nature paper(s) referenced by the press were NOT located on arXiv this session — flagged for
  follow-up. Landmark by scale (first-of-kind sustained operation, two-team independent
  confirmation per secondary press) even before full verification of the second paper.
- evidence:
  - 2026-10-07 (v1) — https://arxiv.org/abs/2610.10056 — Wang, Yin, Wang, et al. (USTC/Hefei, with
    TU Wien co-authors Beeks and Schumm), "A solid-state nuclear clock based on VUV absorption
    spectroscopy of $^{229}$Th": demonstrates sustained operation of a solid-state Th-229:CaF2
    nuclear clock, feedback updated every ~10s over a 30-hour record, fractional frequency
    instability ~1.24x10^-13 at 10^4s. Abstract + full author list verified via arXiv API this
    session.
- notes: 2026-10-08 (daily, seed creation): caught via Hacker-News-adjacent press chase (NYT
  headline on the front page of community pulse) and the physics.atom-ph arXiv sweep
  independently surfacing the same preprint — convergent discovery. NOT yet located: the specific
  Tsinghua-led and/or TU-Wien-solo Nature paper(s) the press describes as the "second independent
  team" — chase next session (search Nature.com directly, or author names from the press pieces).
  Also added to `study_shelf`.

### Finiteness of planar central configurations for five bodies (Smale's sixth problem)
- stage: seed | confidence: medium | first_seen: 2026-10-12 | last_evidence: 2026-11-12
- what: axis-1 DOMAIN-CADENCE LANDMARK (resolution of a named open problem): settles, for the
  5-body case, Smale's sixth problem (from Stephen Smale's 1998 list of mathematical problems for
  the 21st century) — whether the planar n-body problem has only finitely many central
  configurations (relative-equilibrium shapes) up to similarity, for every choice of positive
  masses. Albouy–Kaloshin (2012) proved this for n=5 outside a codimension-two algebraic exceptional
  set of mass values; this paper extends their valuation/algebraic-curve method to cover ALL
  positive masses, closing the gap for n=5. A single-author result on a problem from a canonical
  list (Smale's problems sit alongside Hilbert's/Clay's as named benchmarks this radar tracks).
  Unrefereed preprint — standard caution.
- evidence:
  - 2026-10-09 (v1) — https://arxiv.org/abs/2610.13100 — Tejasvi Singh Tomar, "Finiteness of planar
    central configurations of five bodies for all positive masses": proves finiteness of central
    configurations for every choice of 5 positive masses in the plane, completing the n=5 case of
    Smale's sixth problem (Albouy–Kaloshin 2012 had covered all but a codimension-two exceptional
    mass set). Abstract + author verified via arXiv API this session (W44 version-history
    spot-check: silently revised to v2, updated 2026-10-15 — no new claim, same author/result).
  - 2026-10-16 (v1) — https://arxiv.org/abs/2610.23329 — Zhe Chen, Zhicheng Tong, "Finiteness of
    planar central configurations of six bodies for all positive masses: Part I, exceptional-mass
    first limits": a DIFFERENT author pair begins extending the n=5 method to n=6 — this first
    installment confines the generic-mass finiteness problem's exceptional-mass loci (40 of 117
    Chang–Chen diagram "first-limit" obligations) rather than closing n=6 outright. Exactly the
    generalization this trend's creation note flagged as a watch item. Abstract + authors verified
    via arXiv API this session.
  - 2026-10-25 (v1) — https://hexagonmath.org/2610.00550 — Tejasvi Singh Tomar, "Smale's sixth
    problem for five bodies in the plane, with a proof formalized in Lean": the SAME author/result
    as the already-evidenced arXiv:2610.13100 above, now with a Lean 4 proof plus exact
    computer-algebra certificates publicly posted (hexagonmath mirrors/companions the arXiv
    posting) — a genuine vetting-positive signal (formal verification) for an otherwise unrefereed
    single-author preprint. Opened directly via `WebFetch` this session.
  - 2026-11-12 — https://hexagonmath.org/2611.00377v1 — "Smale's sixth problem for six bodies in
    the plane: finiteness of central configurations for generic masses, with a proof formalized
    in Lean": a THIRD author effort on the n=6 program (after Chen–Tong's Part I above) — proves
    finiteness for six bodies for all positive masses OUTSIDE a proper algebraic exceptional
    subset (which the paper only partially characterizes); full n=6 finiteness for EVERY mass
    choice remains explicitly open. A genuine advance, not a closure — same partial-progress
    character as the Albouy–Kaloshin n=5 precedent this trend's own `what` cites. Lean-formalized
    (kernel-checked computations). Opened and read via the hexagonmath `/rss/all` feed this
    session.
- notes: 2026-10-12 (daily, seed creation): caught in the full math.DS category sweep
  (2026-10-09 submission batch). Watch for expert/community engagement (celestial-mechanics
  specialists, Smale-problems trackers) and whether the method generalizes to n=6+.
  - 2026-10-19 (daily): the n=6 generalization watch condition fires — Chen–Tong's Part I (above),
    a SEPARATE author pair from Tomar's n=5 proof, opens an n=6 program but only for exceptional-mass
    loci (Part I of a presumably multi-part effort); last_evidence advances 2026-10-09 → 2026-10-16.
    Not a stage promotion (still a single-problem program, not yet a multi-group DIRECTION trend);
    watch for Part II/n=6 closure and for referee/community engagement on either paper.
  - 2026-10-27 (daily): Tomar's own Lean formalization surfaces (above), found via hexagonmath's
    `/rss/math` feed (a mirror/companion posting of the same n=5 result, not a new independent
    group). last_evidence advances 2026-10-16 → 2026-10-25. Confidence held at `medium` pending
    community/referee engagement — a self-formalization is a positive signal but not independent
    corroboration.
  - 2026-11-13 (daily): a third n=6 effort (above, hexagonmath 2611.00377), Lean-formalized but
    still only a partial-mass-set result — n=6 finiteness for every positive mass remains open.
    last_evidence advances 2026-10-25 → 2026-11-12. Confidence held `medium`. Caught via today's
    hexagonmath `/rss/all` sweep.

### GW231123 — the most massive binary black-hole merger yet detected (LIGO–Virgo–KAGRA)
- stage: seed | confidence: medium | first_seen: 2026-10-12 | last_evidence: 2026-10-08
- what: axis-3 DOMAIN-CADENCE LANDMARK (first-of-kind detection), BACKFILLED — a coverage gap, not a
  new discovery: on 2023-11-23 LIGO detected GW231123, a binary black-hole merger with component
  masses ~137 and ~101 solar masses (both inside/above the pair-instability mass gap) and
  exceptionally high component spins (~0.9 and ~0.8) — the most massive, highest-spin BBH merger
  LVK has reported, announced/published 2025-07-10. This event was never captured on this ledger;
  the gap surfaced only via today's below-bar follow-up analysis (already queued 2026-10-08) citing
  it. Backfilled per the same policy used for the Abel Prize gap (W41 weekly): the landmark result
  itself qualifies for `seed` regardless of when this radar catches up to it.
- evidence:
  - 2025-07-10 (v1) — https://arxiv.org/abs/2507.08219 — LIGO Scientific Collaboration, Virgo
    Collaboration, KAGRA Collaboration, "GW231123: a Binary Black Hole Merger with Total Mass
    190-265 $M_\odot$": the original detection/parameter-estimation paper. Abstract verified via
    arXiv API this session.
  - 2026-10-08 (v1) — https://arxiv.org/abs/2610.12205 — Wang et al., "Evidence for orbital
    eccentricity supports a hierarchical origin for GW231123": argues the event's properties are
    better explained by an eccentric, dynamically-assembled (hierarchical-merger) origin than a
    quasi-circular one — the follow-up analysis that surfaced this ledger's gap. Abstract + authors
    verified via arXiv API (2026-10-08 session).
- notes: 2026-10-12 (daily, seed creation from backfilled gap + today's queue item): the
  2026-10-08 queue entry flagging "GW231123 itself... not yet on this ledger" is RESOLVED by
  promoting both the original detection and the follow-up into this new trend (removed from the
  queue, not duplicated). Several 2025 interpretation papers exist (primordial-black-hole,
  hierarchical-merger, even "cosmic string" explanations) — not individually chased this session;
  watch for a definitive formation-channel consensus.
  - 2026-W43 recalibration (Amendment I version-history spot-check): 2507.08219 found silently
    revised to v2, updated 2025-11-10 (predates this trend's own creation by ~11 months — the
    published/final LVK paper, same title/result). Low materiality, no change to `last_evidence`.

### OpenAI's claimed proof of the quasi-Riemann Hypothesis (zero-free region ℜs>7/8)
- stage: seed | confidence: medium | first_seen: 2026-10-13 | last_evidence: 2026-11-12
- what: axis-1 DOMAIN-CADENCE LANDMARK, PROMOTED out of prose: one specific result-family (#003)
  inside the already-tracked OpenAI mass-disclosure release (2026-10-06, 722 manuscripts) had sat
  named only in that trend's `what` text since 2026-10-07 — a capture-leak by this ledger's own
  discipline (a primary named only in another trend's prose, never given its own evidence/queue
  line). Promoted today because INDEPENDENT HUMAN ENGAGEMENT specifically on this result-family has
  now appeared (the watch condition this ledger has carried since 10-07), distinct from the generic
  disclosure-event community reaction already tracked on the parent trend. The claim: every
  Dirichlet L-function (incl. ζ(s)) and every finite-order Hecke L-function over ℚ(√-3) is zero-free
  in the half-plane ℜs>7/8, with a companion proof pushing to ℜs>11/12 (ruling out Landau–Siegel
  zeros) — the first fixed-width zero-free region in this generality in decades; falls short of the
  critical line ℜs=1/2 but many RH-consequences only need a tighter critical strip, not the full
  hypothesis. HEAVIEST unrefereed-preprint caution — wholly AI-generated (same unreleased OpenAI
  model as the parent disclosure), zero completed independent verification as of this session: a
  MathOverflow thread proposes a Polymath-style collaborative project specifically BECAUSE the
  proof is "quite opaque" and unreviewed; a community-run leaderboard site exists but could not be
  read this session (JS-rendered shell, no content extractable via direct `curl`/`tvly extract`) so
  its claims are UNVERIFIED, not evidence.
- evidence:
  - 2026-09-30 — https://github.com/openai/math/blob/main/preprints/The-Quasi-Riemann-Hypothesis-September-30-2026/paper.pdf
    — the original ℜs>7/8 manuscript (OpenAI internal model), per `CONTENTS.md` item #003. Verified
    live via `raw.githubusercontent.com` this session (direct `github.com` blob view 403s under this
    session's GitHub proxy-scoping; content fetched through the raw-content host instead).
  - 2026-10-05 — https://github.com/openai/math/blob/main/preprints/The-Quasi-Riemann-Hypothesis-October-5-2026/paper2.pdf
    — companion manuscript, alternate proof of the stronger ℜs>11/12 half-plane, explicitly ruling
    out Landau–Siegel zeros. Verified live via `raw.githubusercontent.com` this session.
  - 2026-10-01 (found this session via Terence Tao's blog, not the standing arXiv/GitHub sweep) —
    https://github.com/openai/math/blob/main/preprints/Uniform-exclusion-of-Landau-Siegel-zeros-October-1-2026/paper.pdf
    — "Uniform exclusion of Landau-Siegel zeros": a DISTINCT, previously-uncaptured standalone
    OpenAI manuscript (9pp, algebraic number theory + geometry of numbers) on the same Landau-Siegel
    half-plane as the Oct-5 companion above — the specific version Terence Tao sketches his own
    proof of (see notes). Verified live via `raw.githubusercontent.com` this session.
  - 2026-10-15 — https://arxiv.org/abs/2610.21099 — Bryce Kerr, "A simpler proof that there are no
    Landau–Siegel zeros" — explicitly states it simplifies the OpenAI proof above. The first
    INDEPENDENT HUMAN ENGAGEMENT that reproduces/simplifies (not merely discusses) one of this
    result-family's two half-planes — exactly the watch condition this trend has carried since
    10-13. Still not a full independent re-derivation from scratch nor a referee report; confidence
    held at `medium` pending a fuller read of whether Kerr's simplification is self-contained or
    leans on OpenAI's own lemmas.
  - 2026-10-30 (daily, found via hexagonmath.org's `/rss/all` feed, opened directly) — A FIFTH
    independent effort on this sub-theme: Baiying Liu, "An improved zero-free half-plane for Hecke
    L-functions over number fields and Quasi-Riemann Hypothesis" —
    https://hexagonmath.org/2610.00655v1 (v1, 2026-10-29) — proves $\Re s>B^*$ (an explicit algebraic
    constant, $B^*\approx0.87447$) is zero-free for EVERY finite-order Hecke L-function over ANY
    number field, generalizing Cureton–Thorner's Dedekind-zeta-only result above to the full Hecke
    L-function class, at a cost of a slightly weaker constant than either OpenAI's 7/8 or
    Cureton–Thorner's 31/32. Page states the text mixes human-written and AI-generated material
    (OpenAI Codex + Anthropic Claude credited for drafting/reference-checking/auditing) — per this
    ledger's axis-5 AI-watch policy, the mathematical RESULT is tracked, not the AI-assistance
    itself. Unrefereed preprint — claim; not independently assessed for correctness this session.
  - 2026-11-02 (daily, found via hexagonmath.org's `/rss/all` feed, a large ~50-item batch
    appeared since 10-30, opened directly) — A SIXTH item on this sub-theme: "We reconstruct the
    argument recorded in a frozen Lean development establishing nonvanishing of the unit-compatible
    angular Hecke L-functions over ℚ(√-3) in the strict half-plane ℜs>7/8... This strengthens the
    earlier 15/16 result for the same angular family." —
    https://hexagonmath.org/2610.00716 — same field (ℚ(√-3)) and same 7/8 bound as OpenAI's original
    claim, phrased as a RECONSTRUCTION of an existing Lean development rather than a new independent
    derivation — unclear from the page whether this is a genuine Lean-kernel verification of
    OpenAI's own claim (the watched condition) or another AI-generated exposition; no byline/author
    metadata found this session. Flag for next session to clarify. Unrefereed preprint — claim; not
    independently assessed for correctness this session.
  - 2026-11-12 — https://arxiv.org/abs/2611.16665 — Xin Hang Ji, "Proof of the Quasi Riemann
    Hypothesis using $\mathbb Q[i]$": a SEVENTH sub-theme effort — a human author explicitly
    adapts OpenAI's original cubic-Gauss-sum method to quartic Gauss sums over $\mathbb Q(i)$,
    obtaining a zero-free half-plane $\Re s>599/600$ for $\zeta_{\mathbb Q(i)}(s)$ (and hence for
    $\zeta(s)$ itself) — a weaker bound than OpenAI's 7/8 but via an independently-worked route
    over a different number field, the kind of direct human re-derivation this trend's watch
    condition has sought since creation. Caught via today's math.NT title-triage sweep.
    last_evidence advances 2026-10-30 → 2026-11-12. Abstract/author verified via arXiv API this
    session; not independently assessed for correctness (unrefereed preprint — claim).
  - 2026-W47 recalibration (bookkeeping correction): the header `last_evidence` field had drifted
    to 2026-11-02, two advances behind the trend's own notes (which already recorded the 10-21 and
    10-30 advances, and the 11-12 evidence line above) — corrected to 2026-11-12, the latest dated
    activity actually on file. No new group or vetting outcome found this session.
- notes: 2026-10-13 (daily, seed creation/promotion): caught via today's MathOverflow sweep — two
  fresh threads (2026-10-12), Benjamin Durkan proposing a Polymath-type verification project ("the
  proof proffered by OpenAI is quite opaque... it would be beneficial for humans to break down the
  proof into manageable steps") and Pace Nielsen's "Consequences of quasi-RH" treating the ℜs>7/8
  bound as provisionally accepted pending the community tracker, both intake-only (not evidence; no
  individual named/quoted per the social-channel rule). Scientific American's "The most exciting
  claims from OpenAI's heap of new proofs" (2026-10-08, already a tracked DAILY-tier digest source)
  quotes Hector Pasten (a number theorist) on the result's significance — a named, on-record expert
  commentary with no other primary source, citable per the hard-rule allowance, but note-only (not
  an evidence line): "Plenty of applications of the Riemann hypothesis did not need the full Riemann
  hypothesis." This is commentary on significance, NOT a verification of correctness — track the
  vetting outcome, not the mathematics, per the hard rule. Watch for: a completed independent
  verification (human or Lean) of either half-plane, referee commentary, or the proposed Polymath
  project actually launching.
  - 2026-10-16 (daily): Bryce Kerr's "A simpler proof that there are no Landau–Siegel zeros"
    (arXiv:2610.21099, caught via today's math-category arXiv sweep, title-visible) explicitly
    states it simplifies the OpenAI proof above — the first INDEPENDENT HUMAN ENGAGEMENT that
    reproduces/simplifies (not merely discusses) one of this result-family's two half-planes, the
    watch condition carried since seed creation. Still short of a full independent re-derivation or
    a referee report (confidence held at `medium`); not yet clear whether Kerr's simplification is
    self-contained or leans on OpenAI's own lemmas. Watch for: whether this is itself treated by the
    community as confirming correctness of the ℜs>7/8 bound, and a similar simplification of the
    stronger ℜs>11/12 proof.
  - 2026-10-11 (v1; found this session, pointer via Terence Tao's blog) —
    https://arxiv.org/abs/2610.15483 — William D. Banks, "On the OpenAI proof that Landau-Siegel
    zeros do not exist": a SECOND independent human digestion (after Kerr's) of this result-family's
    stronger half-plane, giving a detailed, self-contained, explicit-constants account — an
    interpolation-determinant argument yielding $q_0=10^{10}$, $δ_0=3.0\times10^{-3}$, combined with
    a Lu-Zaman-Zhao computation for a bound at every conductor $q\ge3$. Abstract/author verified via
    arXiv API this session. Older than the existing Oct-15 evidence date — a backfill catch, no
    `last_evidence` change.
  - 2026-10-20 (daily) — STRONGEST COLLECTIVE VETTING SIGNAL YET, still short of a formal outcome:
    found via Terence Tao's blog, "A sketch of the proof of non-existence of Siegel zeroes"
    (https://terrytao.wordpress.com/2026/10/19/a-sketch-of-the-proof-of-non-existence-of-siegel-zeroes/,
    2026-10-19, opened this session — commentary, not itself a primary): Tao gives his OWN worked
    sketch of the key bound for a DISTINCT standalone OpenAI preprint on the same Landau-Siegel-zero
    claim (https://github.com/openai/math/blob/main/preprints/Uniform-exclusion-of-Landau-Siegel-zeros-October-1-2026/paper.pdf,
    "Uniform exclusion of Landau-Siegel zeros," 2026-10-01, 9pp, via algebraic number theory +
    geometry of numbers — now folded into evidence above as a further primary on this half-plane,
    predating the Oct-15/Oct-11 digestions), attributing the "particularly elegant" formulation he
    follows to Ben Green (hexagonmath.org/2610.00311v2, not an arXiv link, not independently opened
    this session). Separately, Quanta's "AI Proved the Quasi-Riemann Hypothesis. What Happens Now?"
    (https://www.quantamagazine.org/ai-proved-the-quasi-riemann-hypothesis-what-happens-now-20261019/,
    2026-10-19, opened this session) surveys the vetting status of BOTH half-planes: the community
    has set the ℜs>7/8 (Lean-verified, 199pp) paper aside to focus on the unformalized ℜs>11/12
    (49pp) one; several 7-13-page human expositions are circulating privately; named specialists
    (Jared Duker Lichtman, Alexander Dunn, Michael Rubinstein, Will Sawin, Thomas Bloom) "largely
    agree" the result is correct, but Peter Sarnak states he will not treat it as established until
    humans check every detail line-by-line, and Maksym Radziwiłł criticizes the EXPOSITION (not the
    correctness) of both OpenAI papers as "well below the field's standards of clarity." Net: this is
    now the broadest named-expert engagement on file for any single item this ledger tracks, but
    still short of a completed line-by-line verification or formal referee outcome — confidence held
    at `medium` per the hard rule (a claimed proof is not a resolved result until the community
    confirms). Watch for: a completed independent write-up posted openly (not privately circulating),
    or Sarnak/another named skeptic's verdict after a full check.
  - 2026-10-21 (daily) — THE WATCHED-FOR POLYMATH-STYLE PROJECT LAUNCHED: Terence Tao, "An
    experimental AI-math challenge: using tenth discriminant bounds to explore arguments ruling out
    Siegel zeroes" (2026-10-20,
    https://terrytao.wordpress.com/2026/10/20/an-experimental-ai-math-challenge-using-tenth-discriminant-bounds-to-explore-arguments-ruling-out-siegel-zeroes/,
    opened directly this session) — a collaborative, disclosed-AI-use, Polymath-style challenge to
    derive an effective bound on a hypothetical "tenth discriminant" using the newer Landau-Siegel-
    zero-exclusion machinery (incl. this trend's own claims) rather than classical Heilbronn-Linfoot/
    Goldfeld-Oesterlé methods — fulfilling the specific watch condition carried on this trend since
    its 2026-10-13 creation (the MathOverflow-proposed Polymath project "actually launching").
    Fast-moving, self-correcting thread (not itself evidence of the quasi-RH/Siegel-zero claims'
    correctness): a historical-attribution fix (Kulikov), a revised numeric bound after an error was
    found (Silberman, ~10^15 → ~10^45), a self-reported "twinheterodox" sequence reaching q<2000
    (self-reported, says it passed independent cross-checks, not verified by this radar), and several
    explicitly CONDITIONAL entries (LemmaLab's d≤653, Henric Larsson's |D|<50,000) that depend on the
    very zero-free-region claims this trend tracks rather than independently confirming them. Net:
    a genuine, ongoing community-vetting mechanism now exists and is actively exercising this
    trend's underlying claims, but no entry in the thread so far constitutes an independent
    confirmation or refutation of the ℜs>7/8 or ℜs>11/12 results themselves — confidence held at
    `medium`. last_evidence advances 2026-10-15 → 2026-10-20. Watch for: whether any challenge entry
    turns into a genuine independent audit of the OpenAI zero-free-region arguments, and the
    class-number-one/tenth-discriminant bound outcome itself (axis-1 significance in its own right
    if a sub-threshold effective bound is found, independent of the Siegel-zero claim's fate).
  - 2026-10-22 (daily, found via John Baez's blog, opened directly this session) — A THIRD
    independent AI system now engages this exact claim: Dean Cureton, Jesse Thorner (research
    direction) with proofs/Lean formalization by "AxiomProver" (AxiomMath), "A quasi-Riemann
    hypothesis for Dedekind zeta functions" — https://hexagonmath.org/2610.00200 (v2, 2026-10-14) —
    proves $\zeta_K(s)\ne0$ for $\Re s>31/32$ for EVERY number field $K$ (a stronger half-plane than
    OpenAI's $7/8$/$11/12$), citing OpenAI's quasi-RH papers in its bibliography; opened directly via
    `WebFetch` this session. Backfill — predates last_evidence, no date change. Building on it,
    Christopher Frei, Efthymios Sofos, Martin Widmer, "Some applications of the quasi-Riemann
    hypothesis to class groups and small generators of number fields" —
    https://arxiv.org/abs/2610.18491 (v1 2026-10-13, human authors) — makes UNCONDITIONAL the
    Ellenberg–Venkatesh $\ell$-torsion bounds on class groups, explicitly conditional on "recent
    breakthroughs of OpenAI and Cureton–Thorner" — the first human paper found deriving a concrete
    unconditional NUMBER-THEORY CONSEQUENCE from this trend's claims (distinct from exposition/
    simplification of the proof itself). Abstract/authors verified via arXiv API this session
    (W44 version-history spot-check: silently revised to v2, updated 2026-10-14 — predates
    last_evidence, no new claim, same authors).
    Backfill (2026-10-13), no last_evidence change. hexagonmath.org now has 2 independent-session
    sightings (the First-Proof Third-Batch report 2026-10-19, this Cureton–Thorner paper today) —
    staged for weekly promotion-bar review in SOURCES.md. Confidence held `medium` (neither item is
    an independent verification of OpenAI's own proof; both build on/extend an unrefereed claim).
  - 2026-10-23 (daily, found via today's math category-rotation batch) — A FOURTH independent
    attempt at a no-Landau-Siegel-zeros result: Victor Zhenyu Guo, "An explicit elementary proof of
    no Landau-Siegel zeros" — https://arxiv.org/abs/2610.30476 (v1, 2026-10-21) — claims a fully
    elementary (no separate small-conductor zero computations), explicit-constant ($c=1/100$) proof
    that every real zero $\beta\in(0,1)$ of $L(s,\chi)$ for a primitive quadratic character of
    conductor $q\ge3$ satisfies $(1-\beta)\log q>c$ — distinct in method from Kerr's, Banks's, and
    Cureton-Thorner's already-tracked approaches above (all build on or digest the OpenAI/Tao
    machinery; this one claims to be self-contained and elementary). Human author, not AI-attributed
    in the abstract — if the elementary claim holds, this would be independent of the OpenAI result
    entirely rather than a verification of it. Abstract + author verified via arXiv API this
    session; not independently assessed for correctness (unrefereed, flag "unrefereed preprint —
    claim"). Separately — found via today's math.SG full-abstract pass, opened directly via WebFetch
    — Terence Tao's blog hosts a guest post by Caroline Turnage-Butterbaugh (co-author of the BGST-B
    paper underlying the Claude/Anthropic zeta-zeros-simplicity result, a SEPARATE standing queue
    item on this ledger), "Simple and critical zeros of the Riemann zeta-function"
    (https://terrytao.wordpress.com/2026/10/22/simple-and-critical-zeros-of-the-riemann-zeta-function/,
    2026-10-22): an expository survey, not a new primary for THIS trend, but cites "An OpenAI
    quasi-RH preprint" as separate related evidence without independently assessing it — logged
    here for cross-reference, not added as its own evidence line (survey/commentary, no new primary
    for the quasi-RH claim specifically); the substantive zeta-zeros-simplicity content is routed to
    that other standing queue item instead (see below). last_evidence advances 2026-10-20 →
    2026-10-21.
  - 2026-11-02 (daily): a SIXTH sub-theme effort added above (hexagonmath 2610.00716, a possible
    Lean reconstruction of OpenAI's own ℚ(√-3)/7/8 claim — see evidence; not independently
    assessed). VETTING-STATUS SIGNAL found via Terence Tao's blog (already-tracked source),
    "Collaborative retreat: New developments in the theory of zeta functions"
    (https://terrytao.wordpress.com/2026/10/30/collaborative-retreat-new-developments-in-the-theory-of-zeta-functions/,
    2026-10-30, opened directly this session): Edgar Assing, Valentin Blomer and Farrell Brumley
    are organizing a Jan 11-15 2027 retreat at the Hausdorff Center (Bonn) whose own announcement
    text refers to "the recently established proof of the quasi Riemann Hypothesis over the
    rational numbers as well as over general number fields" as a premise for a workshop on its
    consequences (Artin's primitive root conjecture, torsion in class groups, equidistribution of
    periodic torus orbits) — the strongest community-acceptance language this trend has seen yet
    ("established," not "claimed"), from a legitimate analytic-number-theory research retreat,
    though this is a workshop-announcement blurb, not itself a referee report or independent
    re-derivation; confidence held at `medium` pending the retreat actually occurring/producing
    assessable output. last_evidence advances 2026-10-21 → 2026-10-30 (retreat announcement date).

### A candidate nonperturbative lattice definition of the Standard Model (Craig, chiral fermions)
- stage: emerging | confidence: medium | first_seen: 2026-10-13 | last_evidence: 2026-11-03
- what: axis-2 DOMAIN-CADENCE LANDMARK, a TITLE-BLIND capture-gap catch (Amendment J failure class —
  no conjecture/theorem/proof keyword in the title). Nathaniel Craig (particle theorist, UC Santa
  Barbara/KITP, on a one-year visiting position at OpenAI since this summer) nonperturbatively
  constructs a gauge-invariant measure for overlap fermions on 4D Euclidean lattices for a class of
  nonabelian chiral gauge theories that includes the Standard Model: comparing chiral projectors at
  successive lattice spacings yields an exponentially local current, establishing the global
  properties needed for Lüscher's reconstruction of a smooth, gauge-invariant fermion measure. This
  targets the long-standing chiral-fermion/fermion-doubling obstruction to defining chiral gauge
  theories (the Standard Model's own gauge structure) nonperturbatively on the lattice — a
  candidate resolution, not yet a consensus one. Single-author, AI-assisted (author states OpenAI
  involvement) — standard unrefereed-preprint caution; this is a hard technical claim in a mature,
  heavily-scrutinized subfield (lattice gauge theory), so expect slow, careful community vetting
  rather than a quick confirm/refute.
- evidence:
  - 2026-10-06 — https://arxiv.org/abs/2610.09093 — Nathaniel Craig, "A gauge-invariant measure for
    lattice chiral fermions": abstract + author + date verified via arXiv API this session.
  - 2026-11-03 — https://arxiv.org/abs/2611.05051 — Edward Witten, "A Note On Lattice Definition of
    Gauge Theories With Chiral Fermions": independent engagement by a top theorist with the exact
    construction above — describes a variant of Craig's algorithm (interpolating the lattice gauge
    field over the continuum), notes "the same variant was also proposed recently by Hsu" (citation
    not located this session — chase next), and flags a concrete practical obstruction: the
    approach "can be implemented on a computer in principle, but not in practice by Monte Carlo
    methods because the chiral fermion path integral is not positive." Witten credits Claude Opus
    5.5 for technical help (AI-watch, axis-5 note, not the result itself). TITLE-BLIND capture
    (Amendment J failure class again — no conjecture/theorem/proof keyword), caught via Peter
    Woit's "Not Even Wrong" blog (`tvly extract` on the feed) this session, not the arXiv
    hep-lat/hep-th/hep-ph title-triage sweep. Abstract + authors + categories verified via arXiv
    API this session.
- notes: 2026-10-13 (daily, seed creation, COVERAGE-GAP): a DOUBLE miss — not just title-blind, but
  a CATEGORY gap: the paper's primary category is `hep-lat` (lattice gauge theory), which is NOT in
  this radar's swept physics-category rotation at all (SOURCES.md lists hep-th/hep-ph/gr-qc/quant-ph/
  math-ph/cond-mat.*/astro-ph.*/nucl-th/nucl-ex/nlin — no `hep-lat`), so no title-triage pass could
  have caught it regardless of keyword; caught today only via Peter Woit's "Not Even
  Wrong" blog ("AI and Chiral Fermions", 2026-10-08, already a tracked digest source) explicitly
  calling it out as "of more interest to fundamental physics" than the same-week math slopocalypse.
  Community reaction so far (Reddit r/Physics thread, per `tvly search` snippet, intake-only, not
  independently opened) frames it as "a candidate nonperturbative lattice definition of the Standard
  Model" — echoing the author's own abstract, not yet an independent technical assessment. Watch
  for: a lattice-QCD specialist's technical response, and whether this is the same author/effort as
  Craig's companion "FERMIACC: Agents for Particle Theory" AI-tooling paper (arXiv:2603.22538,
  axis-5 WATCH only — the tool, not a math/physics result); CORRECTION (2026-10-17, W42 weekly
  capture-leak sweep): this note had called 2603.22538 "already-tracked," but it carried no
  discrete line of its own anywhere on the ledger — a capture leak, now closed via a queue line
  below.
- 2026-11-05 (daily): STAGE BUMP seed → emerging — a third independent author (Edward Witten,
  arXiv:2611.05051, see evidence) has now engaged with this exact construction, alongside Craig
  and a cited-but-unlocated Hsu, crossing from a single-author claim into multiple groups actively
  working the same problem (the "multi-source, forming" bar for `emerging`). Confidence held at
  `medium`, not raised to `high`: Witten's note is not a corroboration of correctness — it flags a
  genuine remaining obstruction (the chiral-fermion path integral's non-positivity blocks Monte
  Carlo in practice), so the vetting-status caution stands. Caught via community pulse (Woit's
  blog), not the arXiv title-triage sweep — same title-blind failure class as the trend's own
  creation. Chase next session: Hsu's uncited paper, and any lattice-QCD specialist reaction to
  Witten's note specifically.

### Proof of the Erdős–Simonovits rational exponents conjecture (Epoch AI model, human-verified)
- stage: seed | confidence: medium | first_seen: 2026-10-14 | last_evidence: 2026-10-13
- what: axis-1 DOMAIN-CADENCE LANDMARK. The rational exponents conjecture of Erdős and Simonovits
  (a decades-old question in extremal/Turán graph theory: for every rational $r\in[1,2]$ there is a
  graph $H$ with $\mathrm{ex}(n,H)=\Theta(n^r)$) is resolved in a proof CLAIMED BY EPOCH AI — a
  third AI organization (after OpenAI, Anthropic) now disclosing a claimed major math result — and
  written up/explained by eight prominent extremal combinatorialists (Conlon, Janzer, Jiang, Kim,
  Lee, Liu, Longbrake, Yepremyan): "We present a proof of this conjecture claimed by Epoch AI,
  explaining how it builds upon ideas and methods developed by many researchers." Per Epoch AI's own
  "FrontierMath Erdős" page (found via `tvly search`, not yet independently opened this session — see
  SOURCES.md staging), their pipeline requires a submission to pass Lean proof-checking
  (`Comparator`, maintained by the Lean FRO) before being accepted as resolving a conjecture — a
  stronger formal-verification gate than OpenAI's unrefereed-PDF disclosure pattern, though the
  human write-up itself is still a fresh, non-peer-reviewed arXiv preprint. HYPE-SKEPTICISM CAUTION
  still applies (AI-claimed result, same tier as the other AI-assisted claims on this ledger) but is
  PARTIALLY OFFSET by (a) the Lean-verification gate and (b) eight named, credentialed human authors
  willing to put their names on an explanatory write-up — closer in kind to the Linear Hadwiger
  Conjecture (GPT-6 Astra-assisted, Norin–Steiner) precedent than to OpenAI's bare unrefereed drops.
- evidence:
  - 2026-10-13 — https://arxiv.org/abs/2610.18713 — Conlon, Janzer, Jiang, Kim, Lee, Liu, Longbrake,
    Yepremyan, "A proof of the rational exponents conjecture": human-authored explanatory write-up of
    a proof claimed by Epoch AI; abstract + authors verified via arXiv API and the arXiv abstract page
    this session.
- notes: 2026-10-14 (daily, seed creation): caught via the day's math.CO/NT broad-rotation batch
  (title carries no AI-attribution keyword, so this was a content-triage catch, not a coverage gap).
  `tvly search` chase on "Epoch AI" surfaced the FrontierMath Erdős program page (epoch.ai) —
  source-discovery candidate staged in SOURCES.md (1 sighting). Watch for: Epoch AI's own primary
  disclosure page (not yet opened directly this session, 404 on a guessed path), independent referee
  commentary, and whether this becomes a recurring disclosure channel alongside openai.com/
  anthropic.com (promotion bar: 2 sightings).

### Disproof of the Erdős unit-distance conjecture (OpenAI model, human-verified by Alon et al.)
- stage: seed | confidence: medium | first_seen: 2026-10-14 | last_evidence: 2026-05-20
- what: axis-1 DOMAIN-CADENCE LANDMARK, BACKFILLED CAPTURE-LEAK CLOSURE. The planar unit distance
  problem (Erdős, 1946 — "one of the best-known questions in combinatorial geometry," with a
  monetary prize historically offered for its resolution) is disproved: an internal OpenAI model
  constructs point configurations with at least $n^{1+\delta}$ unit-distance pairs for infinitely
  many $n$ (some fixed $\delta>0$), beating the "square grid" bound long believed near-optimal. This
  result was explicitly named in this ledger's OpenAI mass-disclosure trend notes since 2026-08-03
  ("the May 20 2026 Erdős unit-distance-conjecture counterexample... noted for context, not
  backfilled") but never given its own evidence/queue line — a genuine capture leak, closed this
  session. STRONG VETTING SIGNAL (the best-vetted of the AI-claimed results tracked on this ledger):
  a human-verified, independently-written digest — "Remarks on the disproof of the unit distance
  conjecture" — was co-authored by NINE prominent mathematicians (Noga Alon, Thomas F. Bloom, W. T.
  Gowers [Fields Medalist], Daniel Litt, Will Sawin, Arul Shankar, Jacob Tsimerman, Victor Wang,
  Melanie Matchett Wood), who confirm the construction and its number-theoretic machinery
  (Ellenberg–Venkatesh / Golod–Shafarevich / Hajir–Maire–Ramakrishna ideas). HYPE-SKEPTICISM CAUTION
  still formally applies (AI-generated, OpenAI unrefereed) but this is the closest this ledger has to
  a genuine positive human-vetting outcome on an AI math claim.
- evidence:
  - 2026-05-20 — https://arxiv.org/abs/2605.20695 — Alon, Bloom, Gowers, Litt, Sawin, Shankar,
    Tsimerman, Wang, Wood, "Remarks on the disproof of the unit distance conjecture": human-verified
    digest of the OpenAI-generated counterexample; abstract + authors + date verified via arXiv API
    this session.
  - 2026-05-20 — https://cdn.openai.com/unit-distance-proof.pdf — OpenAI, "Planar Point Sets with Many
    Unit Distances": the original AI-generated construction; title/abstract verified via `tvly
    search` this session (original announcement: "An OpenAI model has disproved a central conjecture
    in discrete geometry," openai.com).
- notes: 2026-10-14 (daily, seed creation, CAPTURE-LEAK CLOSURE): both primaries pre-date this
  session by ~5 months; backfilled now per the capture-leak reconciliation rule (a primary named in
  another trend's notes-prose without its own evidence/queue line). Directly upstream of the next new
  seed trend below (the sum-product conjecture disproof, which reuses ideas from this construction).
  - 2026-W42 recalibration (dormancy-clock clarification, no action — same precedent as Graham's
    rearrangement conjecture's own W40 note): `last_evidence` (2026-05-20) is nominally 150 days
    old today, which would read as past even the 120-day archive line — but this trend was only
    first_seen 2026-10-14 (3 days ago) and is a BACKFILLED landmark (the "evidence" is the result's
    own publication date, not a signal of continuing activity). Per the precedent set for the
    Ramsey trend at its own creation and reaffirmed for Graham's rearrangement conjecture, a freshly
    created/backfilled trend's dormancy clock runs from when THIS LEDGER started tracking it, not
    from the backlog artifact's own date — NOT a dormancy case. This note exists so a future session
    does not mechanically read the raw day-count and misfire an archive action.

### Disproof of the Erdős–Szemerédi sum-product conjecture (Bloom–Sawin–Schildkraut–Zhelezov)
- stage: seed | confidence: medium | first_seen: 2026-10-14 | last_evidence: 2026-05-27
- what: axis-1 DOMAIN-CADENCE LANDMARK, BACKFILLED CAPTURE-LEAK CLOSURE, HUMAN-AUTHORED (no AI
  involvement, no hype-skepticism caveat needed). The sum-product conjecture (Erdős–Szemerédi) —
  that for any finite $A\subset\mathbb{R}$, $\max(|A+A|,|AA|)$ must be close to $|A|^2$ — is
  disproved: Bloom, Sawin, Schildkraut, Zhelezov construct arbitrarily large $A\subset\mathbb{R}$
  with $\max(|A+A|,|AA|)\le|A|^{2-c}$ for an absolute constant $c>0$, also disproving the "many sums
  and products" generalization. Per OpenAI's own "Ten Advances" footnote (found via `tvly search`
  this session) and Quanta's "Why the Legendary Erdős Problems Are Falling to AI" (Konstantin Kakaes),
  this human result directly built on techniques from the AI-generated unit-distance disproof above —
  a notable case of an AI result accelerating ordinary human mathematical research, not replacing it.
- evidence:
  - 2026-05-27 — https://arxiv.org/abs/2605.28781 — Bloom, Sawin, Schildkraut, Zhelezov, "The
    sum-product conjecture is false for real numbers": abstract + authors + date verified via arXiv
    API this session.
- notes: 2026-10-14 (daily, seed creation, CAPTURE-LEAK CLOSURE): surfaced via a `tvly search` chase
  on OpenAI's "Ten Advances" footnote while researching the Epoch AI rational-exponents catch above;
  pre-dates this session by ~5 months, never previously captured on this ledger. Same footnote also
  names Pohoata's "Split primes and the Elekes–Rónyai problem" and Saha–Xu–Ye's "Furthest Pair
  Requires Quadratic Time..." as further human follow-on work — both routed to `observation_queue`
  below (narrower/more technical, not independently verified as landmark-tier this session).
  - 2026-W42 recalibration (dormancy-clock clarification, no action — same precedent as Graham's
    rearrangement conjecture's own W40 note, and the unit-distance trend immediately above): the
    dormancy clock for this BACKFILLED landmark runs from first_seen (2026-10-14, 3 days ago), not
    from the raw `last_evidence` (2026-05-27, nominally 143 days old) — NOT a dormancy case. Logged
    so a future session does not mechanically misfire an archive action on the raw day-count.

### First detection of the rotational kinematic Sunyaev–Zel'dovich effect (Goldstein–Hill)
- stage: seed | confidence: medium | first_seen: 2026-10-14 | last_evidence: 2026-10-13
- what: axis-3 DOMAIN-CADENCE LANDMARK — a clean, ordinary peer-reviewed first-of-kind detection, NO
  AI involvement and no hype-skepticism caveat. Goldstein & Hill report the first robust evidence for
  the rotational kinematic Sunyaev–Zel'dovich (rkSZ) effect: a dipolar CMB anisotropy from Thomson
  scattering off rotating intracluster gas in galaxy clusters, a predicted-but-previously-unconfirmed
  secondary CMB signature distinct from the thermal/kinematic SZ effects already used for cluster
  cosmology.
- evidence:
  - 2026-10-13 — https://link.aps.org/doi/10.1103/lz37-crg1 — Goldstein, Hill, "Evidence of Galaxy
    Cluster Rotation and Intrahalo Gas Motions in the Cosmic Microwave Background," Phys. Rev. Lett.
    137, 161001 (2026): first robust rkSZ detection; title/authors/journal/date verified via the APS
    PRL RSS feed this session. Preprint: https://arxiv.org/abs/2512.10951 (2025-12-11).
- notes: 2026-10-14 (daily, seed creation): caught via the routine daily PRL RSS sweep (on-axis,
  title-visible, no coverage gap). Watch for follow-up measurements on additional cluster samples
  (statistical significance / sample-size growth) and any connection to existing intracluster-gas-
  dynamics or cluster-cosmology trends.

### The spacetime Penrose conjecture (mathematical general relativity)
- stage: seed | confidence: medium | first_seen: 2026-10-15 | last_evidence: 2026-10-14
- what: axis-2 DOMAIN-CADENCE LANDMARK with a vetting-status dimension: the GENERAL (non-time-
  symmetric) spacetime Penrose inequality — a ~50-year-old conjecture of Roger Penrose's, open
  since the Riemannian (time-symmetric) case was settled by Huisken–Ilmanen (2001) and Bray (2001)
  — now has TWO independent claimed treatments within a week of each other. (1) OpenAI's Oct 6
  mass-disclosure (already tracked above, earlier in this ledger) includes result-family #260, "Spacetime Penrose
  inequalities: enclosing area, charge, rotation, and anti-de Sitter extensions" (several
  constituent manuscripts, all dated October 5, 2026), an AI-generated, UNREFEREED claim of the
  fully general case (arbitrary second fundamental form) in all dimensions n≥3 — same heavy
  hype-skepticism caution as the rest of that disclosure. (2) A new HUMAN preprint by Hubert Bray
  (co-prover of the original 2001 Riemannian case), Tuan Dolmen, Marcus Khuri, and David Schmidt
  proves the inequality unconditionally for the restricted but still broad "maximally
  parameterized" class of initial data (same local degrees of freedom as an arbitrary symmetric
  2-tensor), in all dimensions n≥3, via a new 1-parameter family of generalized Schoen–Yau
  identities — and its own abstract EXPLICITLY states "we believe this is what the OpenAI paper
  posted last week on October 6, 2026 claims to have done," i.e. an established-expert team
  independently engaging with and partially corroborating an AI org's claim on the same named
  conjecture within days — exactly the kind of vetting-status datapoint this ledger exists to
  track. Held at `seed` on the strength of the human paper (established, field-founding authors;
  domain-cadence landmark on a named 50-year conjecture) with the OpenAI claim tracked alongside
  as the broader (more general, still unrefereed) companion claim.
- evidence:
  - 2026-10-14 (v1) — https://arxiv.org/abs/2610.20559 — Bray, Dolmen, Khuri, Schmidt, "Proof of
    the Penrose Conjecture for Maximally Parameterized Initial Data Sets": unconditional proof of
    the spacetime Penrose inequality for maximally parameterized asymptotically flat data, all
    dimensions n≥3, under the dominant energy condition. Abstract/authors verified via arXiv API
    this session.
  - 2026-10-05 (per OpenAI's own repo; found 2026-10-15) — https://github.com/openai/math —
    `CONTENTS.md` result-family #260, "Spacetime Penrose inequalities: enclosing area, charge,
    rotation, and anti-de Sitter extensions" (constituent preprints incl. "The spacetime Penrose
    inequality with charge and original-data rigidity," "A Charged Reduction of the Spacetime
    Penrose Inequality in Spatial Dimensions at Least Four," "The Kerr–Newman Penrose Inequality
    for Axisymmetric Electrovacuum Exteriors"): OpenAI's own repo CONTENTS.md opened directly
    (`raw.githubusercontent.com`) this session — claims the general-case inequality beyond the
    maximally-parameterized restriction. AI-generated, unrefereed; part of the already-tracked
    722-manuscript disclosure, not independently verified by this radar.
- notes: 2026-10-15 (daily, seed creation): caught via the routine math-category arXiv sweep
  (title-visible, "Penrose Conjecture" keyword match) — the Bray–Dolmen–Khuri–Schmidt paper's own
  abstract named the OpenAI connection, which this session then confirmed directly against
  OpenAI's own CONTENTS.md (result-family #260, previously outside this ledger's non-exhaustive
  sample of that disclosure's named conjectures — see the OpenAI mass-disclosure trend's notes,
  cross-referenced there too). Also on `study_shelf`. Watch for: independent referee engagement on
  the Bray et al. paper; whether OpenAI's general-case claim (#260) draws its own independent
  human engagement (the same promotion-to-own-seed pattern already used for the quasi-Riemann-
  Hypothesis result-family); whether the two treatments' overlap region (maximally parameterized
  data) is found to agree.

### A starlike counterexample to the hot spots conjecture (Atar–Burdzy)
- stage: seed | confidence: medium | first_seen: 2026-10-15 | last_evidence: 2026-10-14
- what: axis-1 DOMAIN-CADENCE LANDMARK (spectral geometry / PDE): a significant strengthening of
  the known refutation of Rauch's "hot spots" conjecture (that the hottest/coldest point of a
  generic insulated body, at late times, lies on the boundary). The conjecture's original
  counterexamples (Burdzy–Werner 1999) required non-simply-connected 2D domains; this new result,
  by Rami Atar and Krzysztof Burdzy (Burdzy himself the author of the 1999 counterexample),
  constructs a bounded, simply-connected (starlike about the origin) Lipschitz domain in ℝ³ whose
  first Neumann eigenfunction has its unique global maximum in the domain's INTERIOR (at the
  origin) rather than on the boundary — extending the refutation to a far more restrictive, closer
  to a previously-expected-true, class of domains.
- evidence:
  - 2026-10-14 (v1) — https://arxiv.org/abs/2610.19908 — Atar, Burdzy, "A starlike 3-dimensional
    counterexample to the hot spots conjecture." Abstract/authors verified via arXiv API this
    session.
- notes: 2026-10-15 (daily, seed creation): caught via the routine math-category arXiv sweep
  (title-visible, "counterexample to the hot spots conjecture" keyword match). Unrefereed preprint;
  standard caution, same tier as the Drézet–Ballico-Ellia entry above (explicit construction, not
  AI-assisted). Also on `study_shelf`. Watch for independent confirmation/citation.

### M23 realized as a Galois group over Q, completing the inverse Galois problem for sporadic groups (Huang–Jackson–Lee–Poonen–Pries–Zhang)
- stage: seed | confidence: high | first_seen: 2026-10-16 | last_evidence: 2026-08-09
- what: axis-1 DOMAIN-CADENCE LANDMARK, BACKFILLED CAPTURE-LEAK CLOSURE (same class as the GW231123
  and Abel Prize backfills) — completes a ~40-year program: 25 of the 26 sporadic finite simple
  groups were realized as Galois groups over ℚ by the late 1980s via rigidity methods (Thompson,
  Matzat, Malle et al.); the Mathieu group M23 was the last holdout. This paper produces an explicit
  degree-23 polynomial with rational coefficients whose splitting field has Galois group M23 over ℚ,
  closing the inverse Galois problem for all 26 sporadic groups. High-confidence authorship (Bjorn
  Poonen, MIT, a leading number theorist, among 6 co-authors) and an explicit, checkable
  construction — held at `high` confidence despite being a preprint, same treatment this ledger
  gives other explicit-construction results from established authors. AI assistance is disclosed
  (accelerated computation) but the result/proof is human-authored and explicit, not an AI-claimed
  proof — axis-5 WATCH only, not the axis-1 hype-skepticism caution tier.
- evidence:
  - 2026-08-09 — https://arxiv.org/abs/2608.08538 — Huang, Jackson, Lee, Poonen, Pries, Zhang, "The
    Mathieu group M23 is a Galois group over ℚ." Abstract/authors/date verified via arXiv API this
    session.
  - 2026-08-11 — https://icarm.io/news/icarm-s-blake-jackson-involved-in-solving-the-inverse-galois-problem-for-the-las/
    — ICARM's own announcement (co-author Blake Jackson is an ICARM Innovation Engineer), confirming
    the 40-year program and background. Opened directly via `tvly extract` this session.
- notes: 2026-10-16 (daily, seed creation, CAPTURE-LEAK BACKFILL): surfaced via this session's
  deeper AI-watch-lane chase on icarm.io (previously staged in SOURCES.md on 2026-10-15 from only a
  single webinar-announcement page) — its own `/news` index had never been swept past that one page,
  missing this and the item below for over two months. A genuinely significant pure-math landmark
  that carries essentially zero AI-hype-skepticism risk (explicit, checkable, human-led). Watch for:
  - 2026-W43 recalibration (Amendment I version-history spot-check): 2608.08538 found silently
    revised to v2, updated 2026-10-07 — same title/abstract/result, no new claim; low materiality.
    No change to the trend's own `last_evidence` (backfill precedent: set by the paper's own
    content date, not a cosmetic revision timestamp).
  independent verification/citation of the M23 construction.
  - 2026-W42 recalibration (dormancy-clock clarification, no action — same precedent as Graham's
    rearrangement conjecture's own W40 note): `last_evidence` (2026-08-09) is nominally 69 days old
    today, well inside the 60-day window by itself, but this note exists for the record anyway
    since this is also a BACKFILLED landmark (first_seen 2026-10-16, 1 day ago) — the dormancy
    clock runs from first_seen, not from the backlog artifact's own date, consistent with how this
    ledger treats every backfilled-landmark trend.

### First evidence that X(2370) is dominantly a glueball (BESIII Collaboration)
- stage: dormant | confidence: medium | first_seen: 2026-10-17 | last_evidence: 2026-09-01
- what: axis-3 DOMAIN-CADENCE LANDMARK, PROMOTED from the observation_queue/study_shelf (held there
  since a 2026-07-22 capture-leak catch, never previously promoted to its own trend despite meeting
  the landmark-single-result bar). From 10 billion J/ψ events, the BESIII Collaboration reports the
  strongest evidence yet that the light hadron X(2370) is dominantly the lightest 0⁻⁺ glueball — a
  particle made purely of gluons, sought since the 1970s — via a flavor-singlet-consistent
  suppressed-decay-mode signature. An experimental-collaboration result (not an unrefereed AI/solo
  claim), with named-expert corroboration already on file, though not yet a unanimous consensus.
- evidence:
  - 2026-07-22 — https://arxiv.org/abs/2607.20366 — BESIII Collaboration, "Lightest $0^{-+}$ Glueball
    as Dominant Constituent of $X(2370)$": abstract + collaboration authorship verified via arXiv
    API this session (v1 2026-07-22).
  - 2026-05-26 (v1; backfill, found this session via a CERN Courier chase) —
    https://arxiv.org/abs/2605.26495 — BESIII Collaboration, "Observation of the $X(2370)$ in
    $J/ψ\rightarrowγK^{0}_{S}K^{0}_{S}π^{0}$ and $J/ψ\rightarrowγπ^{0}π^{0}η$": two further decay
    channels (>14σ and >20σ respectively) combined with the already-tracked $K^0_SK^0_Sη'$ channel
    to pin mass 2359(+13/-14) MeV, width 170(+44/-29) MeV. Same collaboration, same experiment —
    corroborating detail, not a second independent group. Abstract/authors verified via arXiv API
    this session.
  - 2026-09-01 (v1) — https://arxiv.org/abs/2609.01342 — Ben, Yang, Zou, "On the Nature of
    $X(2370)$": a COMPETING-INTERPRETATION paper, exactly the vetting-status watch item this
    trend's creation note flagged — argues the BESIII glueball arguments are "flawed" and the
    claimed conclusion "unjustified," proposing instead that every observed property of X(2370) is
    naturally explained by a $\bar Σ Σ$ (baryon-antibaryon) molecular state. Abstract/authors
    verified via arXiv API this session (v1 2026-09-01, v2 2026-09-06). Found via a CERN Courier
    17 September review article ("A case for pure glue") opened this session, which also names a
    supporting lattice-QCD prediction (Chen, Gui, Li, Sun, arXiv:2605.01757, pseudoscalar glueball
    at 2395±14 MeV) — below-bar context, not added as its own evidence line.
- notes: 2026-10-17 (weekly, W42, PROMOTION): this result sat on the queue + study_shelf since a
  2026-07-22 capture-leak catch (chased via a Hacker-News pointer, missed by the ordinary arXiv
  sweep for 27 days), widely covered mid-August by Nature News, Science, Ars Technica and
  ScienceAlert — "an experimental triumph" (Colin Morningstar, CMU, quoted in Science), though
  caution remains ("no single smoking gun" — Bruce Yabsley, U. Sydney, quoted in Nature). Promoted
  to its own seed trend this week (this week's queue-tiering review, per AGENTS.md's domain-cadence
  landmark-single-result bar) rather than left as a queue/shelf-only item indefinitely. Confidence
  medium (named-expert corroboration exists but is not unanimous; no formal collaboration-internal
  peer review cited yet). Watch for: a definitive/consolidated collaboration treatment, or a
  competing-interpretation paper.
  - 2026-10-20 (daily): the watched-for competing-interpretation paper ARRIVED (Ben-Yang-Zou,
    ΣΣ̄-molecule reading, see evidence above) — found via a CERN Courier retrospective, not the
    standing arXiv sweep (hep-ex/hep-ph category batches had already rolled past its Sept 1 v1 by
    the time this ledger started tracking the trend). Confidence held at medium — the glueball
    reading now has a genuine, named rival interpretation in the literature, not just outside
    caution quotes. Watch for: a BESIII or third-party response to the molecular-interpretation
    challenge.
  - 2026-W43 recalibration: `last_evidence` field reconciled against the evidence list (per last
    week's flag) — CORRECT, not stale: 2026-09-01 is the Ben-Yang-Zou paper's own posting date
    (the newest evidence item by content date), not a discovery-lag artifact; this trend's
    discovery of that paper happened 2026-10-20, but the convention this ledger uses throughout is
    the evidence's own date, not the session that found it. No change. Now 54 days old — inside the
    60-day dormancy window but worth a fresh hep-ex/hep-ph-specific chase next session if no
    collaboration response surfaces.
  - 2026-11-05 (daily, DORMANCY PROBE, 65 days quiet, first crossing of the 60-day threshold):
    probed this trend's own evidence channels — CERN Courier (checked earlier this session,
    stale since Oct 1, no new HEP content at all) plus a `WebSearch "X(2370) glueball BESIII
    2026"` covering the Sept 1 → Nov 5 window — found only already-tracked material (the same
    Aug-2026 BESIII announcement, the already-evidenced competing-interpretation paper, and older
    background). No new on-scope hit inside the window. Empty probe → moved to `dormant` per the
    60-day domain-cadence window. Not archived (well short of 120 days); re-check for a BESIII or
    third-party response to the molecular-interpretation challenge whenever next revisited.

### Proof of the Erdős–Szemerédi sunflower conjecture (Bucić–He–Lee)
- stage: seed | confidence: medium | first_seen: 2026-10-20 | last_evidence: 2026-10-19
- what: axis-1 DOMAIN-CADENCE LANDMARK, found via today's math category-rotation batch. Erdős and
  Szemerédi conjectured in the 1970s that any collection of subsets of $[n]$ avoiding a $k$-sunflower
  has size at most $c_k^n$ for some $c_k<2$; the $k=3$ case followed from Croot-Lev-Pach and
  Ellenberg-Gijswijt's cap-set-problem breakthrough (via a reduction of Alon-Shpilka-Umans) — the
  same celebrated polynomial-method machinery behind the Naslund-Sawin sunflower-lemma improvement.
  This paper proves the FULL conjecture for every $k\ge3$. Matija Bucić (Princeton) is a leading
  extremal/probabilistic combinatorialist; a clean, complete resolution of a famous 50-year-old
  Erdős problem, not an incremental bound.
- evidence:
  - 2026-10-19 (v1) — https://arxiv.org/abs/2610.26686 — Bucić, He, Lee, "Proof of the
    Erdős-Szemerédi sunflower conjecture": abstract + authors verified via arXiv API this session.
- notes: 2026-10-20 (daily, seed creation): unrefereed preprint, standard caution — but a
  multi-author, well-credentialed resolution of a classical named conjecture directly building on
  an already-celebrated technique (cap-set/polynomial method); no AI-assistance disclosed. Watch
  for: referee outcome, community reaction (this is squarely the kind of result Quanta covers).

### First observation of weak magnetism in neutron decay (Camarasa-Domene–González-Alonso–Novoa-Brunet)
- stage: seed | confidence: medium | first_seen: 2026-10-20 | last_evidence: 2026-10-19
- what: axis-3 DOMAIN-CADENCE LANDMARK (first-of-kind), found via today's physics category-rotation
  batch. Weak magnetism — a hallmark prediction of Gell-Mann's conserved-vector-current (CVC)
  hypothesis — had never been directly observed in the decay of the free neutron because the usual
  observable (the β asymmetry) cannot separate the weak-magnetism form factor $g_M$ from the
  axial-to-vector ratio λ. Combining β-asymmetry measurements with the neutron lifetime and the
  $\mathcal{F}t$ value of superallowed $0^+\to0^+$ decays lifts the degeneracy: $g_M=4.47(87)$,
  matching the CVC prediction of 4.71 and excluding the absence of weak magnetism at 5.1σ (5.0σ-6.1σ
  across dataset variations) — "the first observation of weak magnetism in the decay of the free
  neutron nearly seven decades after Gell-Mann's prediction." A phenomenological reanalysis of
  existing data (not a new experiment), by established CVC/β-decay theorists.
- evidence:
  - 2026-10-19 (v1) — https://arxiv.org/abs/2610.26792 — Camarasa-Domene, González-Alonso,
    Novoa-Brunet, "First observation of weak magnetism in neutron decay": abstract + authors
    verified via arXiv API this session.
- notes: 2026-10-20 (daily, seed creation): unrefereed preprint, standard caution, but a
  phenomenological/statistical result building transparently on public neutron-decay data (no
  AI-assistance, no extraordinary-claim-scale jump) — lower epistemic risk than a from-scratch
  single-result claim. Watch for: referee outcome, and whether the significance holds up as new
  neutron-lifetime/asymmetry measurements arrive.

### AI-claimed resolution of the percolation-criticality conjecture (Benjamini–Schramm; Claude and OpenAI, independently)
- stage: seed | confidence: medium | first_seen: 2026-09-04 (promoted from `observation_queue` 2026-10-22) | last_evidence: 2026-10-21
- what: axis-1 DOMAIN-CADENCE LANDMARK + AI-WATCH LANE: TWO fully independent AI organizations have
  now separately claimed proofs that critical Bernoulli percolation has no infinite cluster — the
  Benjamini–Schramm criticality conjecture, which (via Kozma–Nitzan's 2024 reduction) implies
  θ(p_c)=0 for nearest-neighbour bond percolation on ℤᵏ for every k≥2, closing the famous
  intermediate-dimension gap (3≤k≤10, crucially ℤ³) left open between Harris/Kesten (k=2) and the
  lace-expansion regime (k≥11) — Conjecture 1 of Duminil-Copin's ICM 2018 problem list. Anthropic/
  Claude's claim (2026-09-04) proves it via Kozma–Nitzan's own Conjecture 3 ("near-one gluing");
  OpenAI's claim (preprints dated 2026-09-24, disclosed 2026-10-06 as part of its 722-manuscript
  release) proves a more general form directly for every quasi-transitive graph, via a different
  route, and separately proves the companion Benjamini–Schramm NONUNIQUENESS conjecture (p_c<p_u on
  nonamenable quasi-transitive graphs). Promoted out of `observation_queue` today: the item has now
  drawn mainstream-press coverage with named-expert reaction (Scientific American) and a human
  mathematician's own exposition note explicitly treating "the proof" as established enough to
  write up (Gouéré) — sustained multi-source engagement on a landmark single result, per AGENTS.md
  § Domain cadence, even though BOTH underlying claims remain wholly AI-generated and unrefereed.
  HEAVIEST unrefereed-preprint caution, doubled: two independent AI labs claiming the same landmark
  within three weeks of each other is a striking convergence signal, but neither has a completed
  independent human verification; Lean-checked (Claude's route) is not independently audited, and
  OpenAI's route has no formalization confirmed opened this session.
- evidence:
  - 2026-09-04 — https://github.com/anthropics/formal-math/blob/795efb86f191735c5481675763537cfb4ff37e55/percolation/README.md
    — Claude (Anthropic) with human author Justin Leder, complete Lean 4/Mathlib formalization of
    θ(p_c)=0 for all d≥2, via a new "additive gluing inequality"; repo README states the proof is
    "not yet... refereed by anyone independent of the author." (Full detail/history retained in the
    `observation_queue` entry this promotes, below.)
  - 2026-09-24 (preprints dated; disclosed 2026-10-06) — https://github.com/openai/math (CONTENTS.md
    items #213–#214) — OpenAI, "Critical percolation on every quasi-transitive graph" /
    "The Benjamini–Schramm nonuniqueness conjecture": resolves the bond form of the criticality
    conjecture for every infinite, connected, locally finite, quasi-transitive graph with p_c<1
    (specializing to no infinite cluster at criticality for bond AND site percolation on ℤ³), and
    separately proves p_c<p_u on every nonamenable quasi-transitive such graph. Opened directly via
    `raw.githubusercontent.com` (CONTENTS.md) this session — an INDEPENDENT route (not via
    Kozma–Nitzan) to essentially the same landmark Claude claimed three weeks earlier.
  - 2026-09-30 — https://www.scientificamerican.com/article/ai-solves-a-holy-grail-problem-from-probability-theory/
    — Scientific American, "AI solves a 'holy grail' problem from probability theory": reports the
    Claude/Anthropic claim, notes Hugo Duminil-Copin's 2026-08-30 prediction (four days before the
    claim surfaced) that AI would likely resolve "the most famous conjecture in our field," and
    quotes Benedikt Jahnel (TU Braunschweig) on the mixed community reaction ("ambivalent feelings...
    joy... mixed with disappointment that an AI supplied the crucial step"). No independent
    verification reported. Opened directly via `WebFetch` this session.
  - 2026-10-21 (v1) — https://arxiv.org/abs/2610.30063 — Jean-Baptiste Gouéré, "On the proof of the
    Kozma-Nitzan conjecture": exposition of a proof of Conjecture 1 of Kozma–Nitzan. ATTRIBUTION
    RESOLVED this week (full PDF opened): Gouéré's own reference [9] for the proof he expounds is a
    THIRD, previously-uncaptured OpenAI manuscript, "Critical bond and site percolation on the
    cubic lattice" (dated 2026-09-24, same disclosure batch as #213/#214) — distinct from both
    already-tracked OpenAI items (#213 "every quasi-transitive graph," #214 the nonuniqueness
    conjecture). Gouéré's reference [10] IS OpenAI's quasi-transitive-graph paper (matching #213),
    which he explicitly states he does "not consider... in these notes." So OpenAI independently
    proved the conjecture via the SAME Kozma–Nitzan route Claude used, in addition to its own
    differently-routed quasi-transitive-graph proof — not a misattribution, a genuine third
    manuscript. Also newly found via Gouéré's own reference [1] (not independently opened before
    this session): Arthur Blanc-Renaudie, "Notes on Kozma and Nitzan's proof of θ(p_c)=0"
    (arXiv:2610.10502, 2026-10-07) — a human-intelligible exposition SPECIFICALLY of the
    Claude/Leder Lean proof ("The proof was recently found by AI, but was very poorly written. Our
    version is much shorter..."), the counterpart on Claude's route to what Gouéré did for OpenAI's.
    Both verified via full-text `WebFetch` this session.
  - 2026-09-24 (v1; newly captured, third OpenAI manuscript, same disclosure batch as #213/#214) —
    https://github.com/openai/math/blob/main/preprints/Critical-bond-and-site-percolation-on-the-cubic-lattice-September-24-2026/paper.pdf
    — OpenAI, "Critical bond and site percolation on the cubic lattice": proves Kozma–Nitzan's
    Conjecture 1 directly (the SAME conjecture Claude's route proves), independently of the
    quasi-transitive-graph route in #213/#214. Verified via Gouéré's reference [9] this session.
  - 2026-10-07 (v1) — https://arxiv.org/abs/2610.10502 — Arthur Blanc-Renaudie, "Notes on Kozma and
    Nitzan's proof of θ(p_c)=0": human-intelligible, shortened exposition of the Claude/Leder Lean
    proof specifically (not OpenAI's) — the first independent human engagement with THAT route.
    Full text verified via `WebFetch` this session.
- notes: 2026-10-22 (daily, promotion): see `observation_queue`'s original 2026-09-04 entry (now
  superseded by this trend) for the full original capture detail, Kalai's blog post, and the
  Fields-medal prediction context. Watch for: an independent Lean audit of Claude's proof, any
  human/traditional verification of OpenAI's #213/#214 route, a statement from Kozma, Nitzan, or
  Duminil-Copin.
  - 2026-W43 recalibration: Gouéré attribution flag RESOLVED (see evidence above) — not a
    misattribution; OpenAI's 2026-09-24 disclosure batch in fact contains (at least) THREE distinct
    manuscripts on this landmark, not two, one of which uses Claude's own Kozma–Nitzan route. Two
    independent human expository notes now exist, one per AI lab's route (Blanc-Renaudie on
    Claude's; Gouéré on OpenAI's) — neither is a referee report or a from-scratch independent
    re-derivation, so confidence held at `medium`; this is the closest this trend has come to
    genuine human engagement with the actual proof mechanics on both sides. `last_evidence`
    unchanged (both newly-captured items predate 2026-10-21).

### Disproof of Hochster's small Cohen-Macaulay conjecture / negative resolution of the Eisenbud-Schreyer-Weyman Ulrich-bundle question
- stage: seed | confidence: medium | first_seen: 2026-10-22 | last_evidence: 2026-10-21
- what: axis-1 DOMAIN-CADENCE LANDMARK, a multi-group convergence caught via a survey paper found in
  today's math.AG sweep. For a smooth complex projective surface Y with an ample, globally
  generated divisor H such that H²<σ(Y) (the signature), a September 2026 cluster of independent
  results showed: (a) no ULRICH BUNDLES exist when H is very ample, answering NEGATIVELY the
  Eisenbud–Schreyer–Weyman (2003) question for sheaves supported on the whole variety; (b) no
  ARITHMETICALLY COHEN-MACAULAY bundles exist either, disproving HOCHSTER's 1973 SMALL
  COHEN-MACAULAY CONJECTURE for this class of surfaces. Per the survey, "four preprints and an
  AI-generated manuscript" produced this obstruction across September 2026, with at least two named
  independent human groups (Anghel; Lopez, extending to arbitrary dimension) — clears the
  domain-adaptation landmark bar (two 20th-century named conjectures disproved) and approaches the
  multi-group convergence bar. Unrefereed preprints; one contributing manuscript is AI-generated
  (not independently identified this session) — standard caution.
- evidence:
  - 2026-10-21 (v1; found via today's math.AG arXiv sweep) — https://arxiv.org/abs/2610.30027 —
    Cristian Anghel, "The recent counterexamples to the Eisenbud-Schreyer-Weyman Ulrich problem
    (2003) and to Hochster's small Cohen-Macaulay conjecture (1973): a survey, with a generalization
    to arbitrary dimension": the survey/generalization itself, naming and citing the September 2026
    cluster below. Abstract opened via arXiv API this session.
  - 2026-09-02 (v1; independently opened via arXiv API this session, W43 weekly) —
    https://arxiv.org/abs/2609.02718 — Cristian Anghel, "Smooth Counterexamples to the
    Eisenbud–Schreyer–Weyman Ulrich Existence Problem": confirmed via abstract — a rank-independent
    Bogomolov–Hodge obstruction gives a smooth counterexample on the exponent-3 Hesse surface.
  - 2026-09-06 (v1; independently opened via arXiv API this session, W43 weekly) —
    https://arxiv.org/abs/2609.06678 — Angelo Felice Lopez, "On the existence of smooth varieties of
    any dimension carrying no Ulrich bundles for some very ample line bundle": confirmed via
    abstract — using Anghel's dimension-2 examples, extends the obstruction to every $n\ge3$ plus
    further dimension-2 examples.
- notes: 2026-10-22 (daily, seed creation): the underlying September results were never previously
  captured by this ledger (not found in any prior report/TRENDS.md grep) — a genuine, if delayed,
  capture via the survey's own citations rather than at original publication. Watch for: independent
  confirmation, and whether the AI-generated contribution the survey mentions (not individually
  identified) draws its own vetting-status commentary.
  - 2026-W43 recalibration: Anghel (2609.02718) and Lopez (2609.06678) independently opened and
    verified via arXiv API this session (per last week's flag) — both titles/abstracts confirm the
    survey's characterization exactly; no discrepancy found. The survey's "four preprints and an
    AI-generated manuscript" claim remains only partially enumerated (these two plus the survey
    itself are the only three individually identified so far) — still a standing watch item, not
    chased further this session (time-budget).
  - 2026-W44 recalibration (Amendment I version-history spot-check): Lopez's preprint (2609.06678)
    found silently revised to v3, updated 2026-09-10 — predates this trend's last_evidence
    (2026-10-21), same author/result, no new group, no last_evidence change. Anghel's two tracked
    preprints (2610.30027, 2609.02718) show no v-update. Not promoted.

### Resolution of the Gauss–Fourier conjecture (critical points of rational functions)
- stage: seed | confidence: low | first_seen: 2026-10-23 | last_evidence: 2026-10-22
- what: axis-1 DOMAIN-CADENCE LANDMARK (provisional), found in today's math category-rotation batch.
  A conjecture attributed to Gauss and Fourier, open for "over two centuries" per the authors' own
  framing, states every real critical point of $p'(s)/p(s)$ (for a real polynomial $p$) is
  associated with a pair of non-real zeros of $p$. Lande Ma and Zhaokun Ma claim a complete
  resolution across two companion papers, handling what they term the "first kind" and "second
  kind" of zeros of $(p'(s)/p(s))'$ via a root-locus method. HEAVY HYPE-SKEPTICISM CAUTION: two
  unrefereed preprints from authors with no track record visible to this session on a claimed
  200+-year-old named conjecture — flag "unrefereed preprint — claim," track vetting; held at
  `low` confidence pending any independent engagement (unlike the Simon's-$L^2$ item above, no
  named-authority context was found this session to assess credibility).
- evidence:
  - 2026-10-21 (v1) — https://arxiv.org/abs/2610.29790 — Lande Ma, Zhaokun Ma, "Principle of
    generating critical points of rational functions and Gauss-Fourier conjecture for second-kind
    zeros." Abstract + authors verified via arXiv API this session.
  - 2026-10-22 (v1) — https://arxiv.org/abs/2610.30620 — Lande Ma, Zhaokun Ma, "Comprehensive
    Resolution of the Gauss-Fourier Conjecture for the First Kind of Zeros." Abstract + authors
    verified via arXiv API this session.
- notes: 2026-10-23 (daily, seed creation): seeded under the domain-adaptation landmark-single-
  result bar (a long-standing named conjecture, claimed fully resolved); confidence held at `low`
  rather than `medium` given no corroborating context on the authors/venue was found this session —
  next session or the weekly should attempt a `tvly search` for any response to these two papers.
  Watch for: any expert commentary, citation, or correction.

### Resolution of the Propeller Conjecture (Khot–Naor 2008): OpenAI claim + independent human simplification (Heilman)
- stage: seed | confidence: medium | first_seen: 2026-10-26 | last_evidence: 2026-10-23
- what: axis-1/5 DOMAIN-CADENCE LANDMARK, split from the already-tracked OpenAI mass-disclosure trend
  (same precedent as the quasi-Riemann-Hypothesis #003 and spacetime-Penrose #260 splits). The
  Propeller Conjecture of Khot and Naor (2008) — the sum of squared lengths of Gaussian first moments
  of any finite measurable partition of Euclidean space is at most $9/(8\pi)$ — underlies an NP-
  hardness result (via a separate Unique Games theorem) for improving a clustering approximation
  ratio. OpenAI's October 6 mass disclosure includes this as result-family #096 ("The Gaussian
  propeller conjecture in every dimension"), never individually evidenced on this ledger until today.
  An independent human specialist, Steven Heilman, now simplifies, sharpens (pinning the equality
  case precisely), and partially DE-COMPUTERIZES OpenAI's proof — a genuine vetting-positive signal,
  the same class as Kerr's/Banks's simplifications on the quasi-RH trend.
- evidence:
  - 2026-10-05 (per OpenAI's own repo; found 2026-10-26) — https://github.com/openai/math —
    `CONTENTS.md` result-family #096, "The Gaussian propeller conjecture in every dimension"
    (constituent preprint: `preprints/The-Gaussian-Propeller-Bound-in-Every-Dimension-September-24-2026/main.pdf`):
    proves the bound in every dimension plus the equality case and, combined with a separate Unique
    Games theorem, the resulting clustering NP-hardness consequence. OpenAI's own CONTENTS.md opened
    directly via `raw.githubusercontent.com` this session.
  - 2026-10-23 — https://arxiv.org/abs/2610.32158 — Steven Heilman, "On the Propeller Conjecture":
    simplifies and improves OpenAI's proof, shows equality occurs only for three 120-degree planar
    sectors (up to symmetries/measure-zero changes/orthogonal cross products), and removes computer
    assistance from the three-dimensional case (which previously used an epsilon-net traversal).
    Abstract + author verified via arXiv API this session.
- notes: 2026-10-26 (daily, seed creation/split): caught via the Amendment J full-abstract pass
  (today's category math.CV) finding nothing, which prompted a broader cross-listed-category check of
  the same day's batch — Heilman's paper's primary category is `cs.CC`, outside this ledger's swept
  math/physics category rotation (same category-blind-miss class as the 3SUM/APSP and 4-to-1-games
  misses). Confidence `medium` (not `high`): OpenAI's own manuscript remains wholly AI-generated and
  unrefereed; Heilman's paper is itself a fresh, not-yet-cited preprint, though the de-computerization
  of the 3D case is a genuine, checkable vetting-positive signal distinct from mere exposition. Watch
  for: citations of Heilman's paper, further independent engagement, and any commentary on OpenAI's
  own manuscript specifically.

### Resolution of the Harary–Hill conjecture (crossing number of $K_n$): OpenAI claim + independent human exposition (Balko)
- stage: seed | confidence: medium | first_seen: 2026-10-27 | last_evidence: 2026-11-05
- what: axis-1/5 DOMAIN-CADENCE LANDMARK, split from the OpenAI mass-disclosure trend (same
  precedent as the quasi-RH/spacetime-Penrose/Propeller splits). The Harary–Hill conjecture (1963)
  states the crossing number of the complete graph $K_n$ is exactly
  $\frac14\lfloor n/2\rfloor\lfloor(n-1)/2\rfloor\lfloor(n-2)/2\rfloor\lfloor(n-3)/2\rfloor$ — one of
  graph theory's most famous 60+-year-old open problems. OpenAI's October 6 disclosure includes a
  claimed proof; Martin Balko (Charles University, Prague — an established crossing-number/graph-
  drawing researcher, independent of OpenAI) now posts a streamlined, more accessible exposition
  that simplifies several steps and extends the result to determine crossing numbers of several
  other graph families — the same independent-human-engagement pattern as Heilman's Propeller-
  Conjecture paper and Balko/Tevelev-style expositions already tracked on this ledger.
- evidence:
  - 2026-10-06 (per OpenAI's disclosure; not independently opened this session) — https://github.com/openai/math
    — the Harary–Hill proof is among the Oct 6 result families (per Balko's abstract, "recently
    announced by OpenAI (2026)"); not independently cross-checked against `CONTENTS.md` this
    session (time-budget) — flagged for next session to locate the exact result-family number.
  - 2026-10-25 (v1) — https://arxiv.org/abs/2610.34444 — Martin Balko, "Proof of the Harary–Hill
    conjecture: an exposition": a streamlined, simplified rewrite of OpenAI's proof, explicitly
    calling the original "quite difficult to follow." Abstract + author verified via arXiv API
    this session.
  - 2026-11-03 (v1) — https://arxiv.org/abs/2611.03515 — Gelasio Salazar, "The proof of the
    Harary–Hill conjecture: a detailed exposition and an extension to rotation systems": a SECOND
    independent specialist's exposition of OpenAI's proof (also calling it "very hard to follow"),
    extending the argument to rotation systems. A second independent-human-engagement data point
    on the same OpenAI proof, same pattern as Balko's. Abstract + author verified via arXiv API
    this session.
- notes: 2026-10-27 (daily, seed creation/split): caught in today's math category-rotation batch
  (keyword triage on "conjecture"/"proof of"). Confidence `medium`: a credible independent
  specialist's exposition is a vetting-positive signal, but OpenAI's own manuscript remains
  wholly AI-generated and unrefereed, and this session did not independently verify the
  result-family's exact number/scope in `CONTENTS.md`. Watch for: that verification, further
  citations of Balko's exposition, and any correctness caveats.
  - 2026-11-04 (daily): a SECOND independent exposition (Salazar, see evidence) — two independent
    specialists have now separately found OpenAI's original proof hard to follow and rewritten it;
    both expositions agree the underlying argument holds, a strengthening vetting-positive signal.
    No stage/confidence change (still unrefereed at the source). last_evidence advances
    2026-10-25 → 2026-11-03.
  - 2026-W45 recalibration (Amendment I version-history spot-check, first check): Balko's
    2610.34444 found silently revised to v2, updated 2026-11-05 — POSTDATES the recorded
    last_evidence (2026-11-03); last_evidence advances accordingly. Same title/author, no new
    claim. Salazar's 2611.03515 shows no v-update. Not promoted.

### Independent same-day AI claims refuting the Exponential Time Hypothesis (OpenAI + Anthropic)
- stage: seed | confidence: low | first_seen: 2026-10-27 | last_evidence: 2026-10-27
- what: axis-5 AI-WATCH-LANE DOMAIN-CADENCE LANDMARK, EXTRAORDINARY-CLAIM caution at the highest
  tier this ledger tracks. The Exponential Time Hypothesis (ETH, Impagliazzo–Paturi 1999-2001)
  postulates 3-SAT requires $2^{\Omega(n)}$ worst-case time; it underlies most of fine-grained
  complexity theory's conditional lower bounds (the same family as the already-tracked 3SUM/APSP
  trend). On essentially the SAME day (2026-10-25/26), TWO different AI organizations each
  published a Lean-formalized claim refuting it: Anthropic (an internal research Claude model) via
  both hexagonmath.org and its own `anthropics/formal-math` GitHub repo, and OpenAI (its own
  internal model) via its `openai/math` repo. The two claims are related but not verified identical
  (Anthropic: a deterministic $2^{o(n)}$-time 3-SAT decision/counting algorithm; OpenAI: a
  deterministic algorithm exactly counting $k$-CNF satisfying assignments in
  $(n+m)^{O_k(1)}2^{n/(\log n)^{1/2+o(1)}}$ time, also yielding new $\mathsf E^{\mathsf{NP}}$ circuit
  lower bounds). OpenAI states "an independent group led by Impagliazzo, Paturi, and Williams will
  examine the proof" — i.e. the hypothesis's OWN original authors are reviewing it, a strong
  (though not yet completed) credibility signal. HEAVIEST hype-skepticism caution: wholly
  AI-generated, unrefereed by anyone outside each lab as of this session, and ETH-refutation claims
  of this kind have a history of hidden gaps; track the vetting OUTCOME, not the claim.
- evidence:
  - 2026-10-25 (v1, dated by hexagonmath feed) — https://hexagonmath.org/2610.00577 — "A
    $2^{o(n)}$ Time Algorithm for 3-SAT," attributed to Anthropic (an internal research Claude
    model), Lean 4-formalized. Abstract opened directly via `WebFetch` this session.
  - 2026-10-26 (per feed `updated` timestamp; undated commit otherwise) — https://github.com/anthropics/formal-math/blob/main/eth
    — Anthropic's own Lean-formalization repo, `eth/` project: states the same deterministic
    counting algorithm and explicitly "refutes the Exponential Time Hypothesis," citing a
    `paper.pdf`. README opened directly via `WebFetch` this session (no independent verification of
    the Lean build/comparator-check status).
  - 2026-10-26 — https://github.com/openai/math (`CONTENTS.md` #378, `history.md`'s same-day entry)
    — "Disproof of the Exponential Time Hypothesis" / "The Exponential Time Hypothesis is False":
    OpenAI's own repository, opened directly via `raw.githubusercontent.com` this session; states
    the Impagliazzo–Paturi–Williams independent-review plan.
  - 2026-10-27 — https://www.scientificamerican.com/article/dueling-proofs-from-openai-and-anthropic-astound-scientists/
    — Joseph Howlett, "Dueling proofs from OpenAI and Anthropic astound scientists": names
    Russell Impagliazzo and Ramamohan Paturi (UC San Diego) and Ryan Williams (MIT) as actively
    working WITH OpenAI on the independent investigation (Williams states OpenAI will sponsor a
    dedicated CS conference on the proof); frames the OpenAI/Anthropic claims as a direct,
    unresolved conflict ("the article describes the result as controversial"); flags a
    transparency gap (proprietary model, no released prompts/compute/chain-of-thought); notes
    that refuting ETH would not automatically resolve P vs NP. Opened directly via `WebFetch`
    this session.
- notes: 2026-10-27 (daily, seed creation): caught via two independent lanes the same session —
  the hexagonmath.org `/rss/all` daily sweep (Anthropic's posting) and the openai/math
  `history.md` changelog check (prompted by a 706-point Hacker News front-page story linking
  OpenAI's own Oct 26 publication page, which also announced the Yang–Mills claim below — see that
  trend). Held at `seed`/`low` (not merely queued) per the domain-cadence precedent of seeding a
  landmark EVENT pre-referee (same as the OpenAI mass-disclosure and Hadwiger/Hopf-S⁶ precedents) —
  but `low`, not `medium`, given NO outside-the-originating-lab verification exists yet for either
  claim. Watch for (top daily-chase priority): the Impagliazzo/Paturi/Williams review outcome;
  whether the two labs' algorithms are mathematically the same construction; any complexity-theory
  community reaction (Woit/Baez/Aaronson-type commentary, Hacker News/community-pulse threads).
  - 2026-10-28 (daily): mainstream-press corroboration (Scientific American, see evidence) —
    the Impagliazzo/Paturi/Williams review is confirmed ACTIVE (not merely announced), with a
    dedicated conference now planned; the conflict between OpenAI's and Anthropic's claims is
    explicitly unresolved as of this article. Two further hexagonmath.org postings this session —
    "Some exposition of 'The Exponential Time Hypothesis Is False'" (2610.00572) and "On counting
    satisfying assignments via polynomial separation" (2610.00574, a "preliminary exposition" of a
    weaker $O_\varepsilon(2^{\varepsilon n})$-time qualitative form) — are third-party expository/
    reproduction attempts at OpenAI's specific construction, not independent NEW claims; opened
    directly via `curl` this session, logged here (not given separate evidence lines, to respect
    the 10-item cap) as early community engagement with the mathematics itself, distinct from the
    press/governance reaction above. last_evidence advances 2026-10-26 → 2026-10-27.

### OpenAI's claimed proof of Yang–Mills existence and a QCD/Standard-Model completion
- stage: seed | confidence: medium | first_seen: 2026-10-27 | last_evidence: 2026-11-25
- what: axis-2/3 EXTRAORDINARY-CLAIM, the single highest-magnitude item this ledger has ever logged
  if confirmed: Yang–Mills existence and mass gap is one of the seven Clay Millennium Prize Problems
  (claymath.org). OpenAI's Oct 26 publication, "Working with academic communities to build
  scientific understanding," states its internal model produced a natural-language proof of
  Yang–Mills existence (2026-09-09) and then of QCD (2026-09-18), with the Yang–Mills Lean
  formalization completed 2026-10-16; OpenAI describes the physics result as "a mathematically
  rigorous existence proof of certain interacting quantum field theories containing gauge fields and
  fermions in four dimensions, including Quantum Chromodynamics (QCD) and a unified completion of
  the Standard Model." CRITICAL CAVEAT, from Peter Woit's same-day commentary (opened directly this
  session): OpenAI's press release does NOT state whether the "existence" claim includes the MASS
  GAP (the actual Millennium condition) — Woit suspects it may be a weaker "existence for small
  volume" result and calls the omission "intentionally deceptive" if so; he also reports that,
  beyond the press release, NO manuscript, Lean proof, or further detail has been made public —
  OpenAI has instead appointed a review panel (David Gross leading Arthur Jaffe, Michael Douglas,
  Igor Klebanov, Nikita Nekrasov — senior, credible QFT theorists) with private access, pending some
  future "transition." This is PROVISIONAL in the most extreme sense this ledger tracks: an
  announcement of a result, not yet an inspectable claim. AGMAI (the IAS advisory group, already
  tracked on the OpenAI mass-disclosure trend) published a statement the SAME day, "Recommendation
  for Immediate Release of Yang–Mills AI Output," arguing the finished Lean formalization leaves "no
  scientific reason" to withhold the material — i.e. the release AGMAI called for is the press
  release itself, not the underlying proof.
- evidence:
  - 2026-10-26 — https://openai.com/index/building-scientific-understanding-with-academic-communities/
    — OpenAI's own publication page (direct `curl`/`WebFetch` 403; opened via `tvly extract` this
    session, corroborated by a `tvly search` snippet quoting the Sept 9/Sept 18/Oct 16 dates
    verbatim). Confirms the claim, the dates, and the Gross-led review panel.
  - 2026-10-26/27 — https://www.math.columbia.edu/~woit/wordpress (post "Secret Unified Physics
    Slop," found via its RSS feed, `?p=15948`) — Peter Woit's critical same-day commentary: raises
    the mass-gap-scope ambiguity and the no-public-manuscript point above, and separately notes an
    UNRELATED, publicly-posted independent effort by Levent Alpöge (already on this ledger via the
    Hopf-problem/S⁶ trend) and Ethan Sussman toward rigorous Yang–Mills (a ~1000-page 3D manuscript,
    plus a claimed-but-unchecked 4D existence argument "tens of thousands of pages" long) — not
    independently opened this session (no URL given in the extracted text); flagged for next
    session to locate and assess. Woit's post opened directly via `tvly extract` (feed URL) this
    session, not via WebFetch (the direct `curl`/`WebFetch` on this domain intermittently returns
    HTTP 000 — see `logs/strategy_notes.md`).
  - 2026-10-27 — https://www.scientificamerican.com/article/dueling-proofs-from-openai-and-anthropic-astound-scientists/
    and https://www.scientificamerican.com/article/openai-just-scooped-human-researchers-on-a-million-dollar-quantum-math-problem
    — Joseph Howlett, two Scientific American pieces (both opened directly via `WebFetch` this
    session): Roland Bauerschmidt (NYU) on Tadeusz Balaban's decades-old Yang–Mills papers —
    "there's no one who understands these papers and can tell whether they're correct or not";
    confirms (via Ethan Sussman) the Alpöge–Sussman independent from-scratch effort is real,
    ongoing, and that OpenAI's announcement "appears to have beaten them to it"; Michael R. Douglas
    (Harvard, review-panel member) calls the claim "a major advance" and "just the start"; Tristan
    Buckmaster (already tracked elsewhere on this ledger) disputes OpenAI's claimed month-long
    verification timeline, saying Lean verification "takes, at most, a couple of days."
  - 2026-11-09/10 (document; opened 2026-11-16) — https://github.com/yang-mills-group/YM/blob/main/docs/assessment-1.pdf
    — the shepherding committee's own "Validation of the OpenAI Yang–Mills construction"
    (companion to their Nov 10 release), downloaded via `raw.githubusercontent.com` and read
    directly via `pdftotext` this session — THE PRIMARY RELEASE this trend has been chasing since
    its creation. States their judgment that the Oct 28 Lean submission "proves that a relativistic
    quantum field theory satisfying the Wightman axioms can be constructed as a scaling limit of
    four-dimensional Wilson lattice gauge theory for any simple compact gauge group" via
    subsequential-limit COMPACTNESS (weak existence) — explicitly: "It does not prove that the
    infinite-volume limit is unique or that there is a mass gap." This is existence in a WEAKER
    sense than Jaffe–Witten's own Millennium Problem statement requires (see the Woit evidence line
    below, which quotes Jaffe–Witten excluding weak/compactness existence as a solution) — a
    precise primary-sourced scope correction, not just a skeptic's reading.
  - 2026-11-11 — https://www.math.columbia.edu/~woit/wordpress (post "The Yang-Mills Publicity
    Stunt," opened via `WebFetch` on the feed this session) — Peter Woit argues OpenAI's Oct 26
    press release claims more than the Nov 9–10 committee materials support: quotes Jaffe–Witten's
    own problem statement verbatim, "We specifically exclude weak-existence (compactness) as the
    solution to the existence part of the Millennium problem" (https://www.claymath.org/wp-content/uploads/2022/06/yangmills.pdf),
    directly matching what the assessment PDF above admits; questions the claimed "Standard Model
    completion" (may be only a Higgs-less minimal SU(5) GUT, which disagrees with experiment); calls
    the Millennium-Problem framing misleading; calls for the group to correct the record, release
    all documents, and disband. Cites two independent human-authored write-ups of the Lean proof:
    Martin Hairer (Fields Medalist) at https://github.com/hairer/humanise-yang-mills and Scott
    Armstrong at https://github.com/scottnarmstrong/yang-mills-informalization — neither
    independently opened this session (flagged for next session's chase) — plus a new statement
    site, https://hep-open-release.org/, from "a large group of prominent theorists" criticizing
    non-release practices (staged below in SOURCES.md).
  - 2026-11-11/12 — https://www.scientificamerican.com/article/openais-shepherds-affirm-blockbuster-physics-result/
    — Joseph Howlett (opened via `WebFetch` this session): the committee's Nov 9 statement says the
    submission "proves the existence of pure Yang–Mills theory" under standard problem statements,
    with the Lean code released Nov 10; the committee says it does "not claim to fully understand
    the proof yet." Michael R. Douglas: four-dimensional Yang–Mills had "never been properly
    understood mathematically" despite 50+ years of work. Scott Armstrong (independent write-up
    author above): welcomes the Lean release but argues AI-lab results should be reviewed in the
    open rather than via closed shepherding committees. Confirms mass gap and a rigorous Standard
    Model reduction remain unestablished — corroborates the assessment PDF's own scope, independent
    secondary confirmation of the primary document.
  - 2026-11-15 (v1) — https://hexagonmath.org/2611.00492v1 — Zeng Chunping, "From Four-Dimensional
    Wilson Lattice Gauge Theory to Quantum Yang–Mills Theory: Construction with Proofs from
    Certified Assumptions, and the Record of Its Independent Validation": a third-party compilation
    explicitly built on the Oct 28 OpenAI Lean submission and the shepherding committee's
    validation; states a positive mass gap, uniqueness of the infinite-volume limit, uniqueness of
    the mixed-theory vacuum, and order-by-order OPE agreement with perturbation theory are "not
    proved" — consistent with the assessment PDF. EXTREME caution (hexagonmath page: "mix of
    human-written and AI-generated text," "Human understanding: some parts," no DOI, beta venue).
    Opened directly via `WebFetch` this session.
  - 2026-10-27 (document itself; found/opened 2026-11-04) — https://www.kitp.ucsb.edu/sites/default/files/YM_working_group.pdf
    — the shepherding committee's OWN statement (Douglas, Gross [chair], Jaffe, Klebanov, Nekrasov),
    hosted at KITP (an already-tracked institute); downloaded and read directly via `pdftotext` this
    session (WebFetch could not parse the PDF's text layer). RESOLVES the standing open question
    on mass-gap scope: the committee states explicitly "confinement and the mass gap remain very
    important important open challenges" — confirming Woit's suspicion that only EXISTENCE
    (including fermion coupling/QCD) is claimed, not the mass gap. New concrete detail: on Oct 16
    Gross was asked by OpenAI to "assume custody" of the proof and chose the rest of the committee;
    the committee states "We have no responsibility to OpenAI"; they are still validating the Lean
    formalization against the informal statement and have NOT yet released it; once satisfied they
    will release the Lean proof, then their assessment together with "the full 1147-page LLM
    proofs" (first concrete page count on file). Cites a related primary for next-session chase:
    Douglas, "The Yang–Mills Millennium problem," Nat. Rev. Phys 8, 86–97 (2026). Found via a
    MathOverflow community-pulse pointer ("Lean 4 verification of a no-go bridge...", intake only,
    not itself evidence) → `tvly search` → this primary PDF.
  - 2026-10-06 (repository; found/opened 2026-11-04) — https://github.com/ethanwsussman/Yang--Mills-LLM-experiment
    — RESOLVES the standing "Alpöge–Sussman repository URL" open item carried across the 2026-10-27,
    10-28, 11-02 and 11-03 reports. Opened directly via `WebFetch`. The repo (Ethan Sussman, with
    Levent Alpöge — already tracked via the Hopf-problem/S⁶ trend) is an independent, from-scratch,
    PUBLICLY-posted attempt (using Claude, credited explicitly for the mathematical ideas under
    Alpöge's guidance — AI-watch-lane: track the result, not the method) to complete Balaban's
    4D Yang–Mills existence program. Status per its own README (none of it verified): QED3 (242pp,
    "if correct" has the full construction incl. Osterwalder–Schrader axioms, believed essentially
    correct but unchecked); YM3 (857+1201pp, OS axioms for tr[F²] "if correct," one author less
    confident); YM4 (unfinished, "appears to" have an existence argument, called "very long and
    largely not understandable" by Alpöge, "more likely than not mostly correct" per Sussman, who
    urges caution). An update note in the README acknowledges OpenAI's own YM4 construction and
    says the authors will continue regardless. EXTREME caution tier (self-described as largely
    unverified LLM output, "slop" in the authors' own term) — tracked because it is the one named,
    independent, from-scratch competing effort this ledger has been chasing for 3+ sessions.
  - 2026-11-17 (v1) — https://hexagonmath.org/2611.00543v1 — Zeng Chunping, "From Four-Dimensional
    Wilson Lattice Gauge Theory to Quantum Yang–Mills Theory, with a Conditional Mass-Gap Theorem":
    Part I of a planned series by the same submitter as the 2611.00492 compilation above; recompiles
    the Lean-verified construction and gives full proofs of every step derivable from the
    definitions, including — UNDER an explicit, individually registered package of
    renormalization-group and analytic assumptions — a CONDITIONAL mass-gap theorem. Consistent
    with, not a reversal of, the committee's own "mass gap not proved" scope: the gap is proved
    only conditionally on stated assumptions, not unconditionally. EXTREME caution (hexagonmath,
    same submitter/venue class as 2611.00492). Opened directly via `WebFetch`/hexagonmath RSS this
    session.
  - 2026-11-25 — https://www.kitp.ucsb.edu/sites/default/files/4th-Statement-About-Quantum-YangMills-Theory_Nov-25.pdf
    — the shepherding committee's 4th statement (Douglas, Gross [chair], Jaffe, Klebanov,
    Nekrasov): discloses that the FIRST (pure-YM) submission's own formal theorem was "initially a
    bit too weak to establish that the theory constructed is Yang–Mills theory," requiring the
    committee to formulate stronger tests of their own (which the Oct 28 submission then passed),
    and that "the earlier work on which the construction rests is not properly credited" — the
    first committee-disclosed correctness/attribution defect on this claim. Releases ALL remaining
    OpenAI material (the QCD and SU(5) chiral-gauge-theory/"Standard Model completion" submissions)
    as explicitly UNASSESSED ("this release is not an endorsement"), citing unresolved community
    disagreement over the committee's embargo-before-release policy. Companion assessment/material
    PDFs at github.com/yang-mills-group/{YM,QCD,chiral}. Downloaded and read directly via
    `pdftotext` this session.
- notes: DROPPED 2026-11-16 (evidence-cap rotation, oldest/least-central): the committee's
  2026-11-03 governance document (RULES AND PROCEDURES PDF) — process/conflict-of-interest detail,
  superseded now the substantive Nov 9-10 release it anticipated has landed (see evidence above).
  2026-10-27 (daily, seed creation): caught via the same Hacker News front-page story and
  openai.com publication page as the ETH-refutation trend above (one Oct 26 post announces all
  three results). Held at `seed`/`low` (domain-cadence pre-referee-landmark-EVENT precedent, same
  reasoning as the ETH trend and the original mass-disclosure seed) — but this is the MOST cautious
  entry on this ledger: there is not yet even an unrefereed preprint to point to, only a press
  release plus one skeptic's reading of it. TOP daily-chase priority going forward, ahead of even
  the BSD case: watch for (a) the actual manuscript/Lean proof becoming public, (b) clarification of
  whether the mass-gap is claimed, (c) the Gross/Jaffe/Douglas/Klebanov/Nekrasov panel's findings,
  (d) the Alpöge–Sussman effort's own status, (e) any Clay Mathematics Institute statement (this is
  their prize problem).
  - 2026-10-28 (daily): mainstream-press corroboration (Scientific American, see evidence) —
    confirms the existence-only/mass-gap-still-open scope reading already on record, adds
    Bauerschmidt's named-expert statement on the general unverifiability of Balaban's source
    papers, and CONFIRMS the Alpöge–Sussman effort is a real, ongoing, independent project (not
    merely something Woit mentioned in passing) — still no repository URL located despite a
    targeted `WebSearch` this session; remains the top standing chase item. last_evidence advances
    2026-10-26 → 2026-10-27.
  - 2026-11-03 (daily): RESOLVED a standing open item from 2026-10-28 (that session's guessed
    Scientific American URL for the companion "quantum math problem" piece 404'd) — located and
    opened the correct URL this session (see evidence above): Douglas's "major advance" assessment
    and Buckmaster's dispute of OpenAI's verification-timeline framing are new named-expert
    reactions, not previously on file. No stage/confidence change (still the most cautious entry
    on this ledger — no public manuscript or Lean proof located). Still no Alpöge–Sussman
    repository URL found this session either.
  - 2026-11-04 (daily): TWO of the five standing chase items from this trend's own creation note
    RESOLVED this session (see evidence above) — (b) the mass-gap-scope question: the shepherding
    committee's own KITP-hosted statement confirms existence-only (incl. fermion coupling), mass
    gap/confinement explicitly still open; (c) partial progress on the panel's findings: the
    committee states it is still validating the Lean formalization internally and has NOT yet
    released anything, with a plan to eventually release the Lean proof then a full assessment plus
    the 1147-page manuscript; (d) the Alpöge–Sussman repository located
    (`github.com/ethanwsussman/Yang--Mills-LLM-experiment`) — an independent, still-unverified,
    Claude-assisted from-scratch effort at QED3/YM3/YM4, continuing despite OpenAI's announcement.
    No stage/confidence change (still `seed`/`low` — no public OpenAI manuscript, Lean proof, or
    committee assessment released yet; the new primaries clarify SCOPE and STATUS of the claim, not
    its correctness). Remaining open: (a) the actual OpenAI manuscript/Lean proof becoming public,
    (e) any Clay Mathematics Institute statement. last_evidence unchanged at 2026-10-27 (no newer-
    dated primary found this session; the KITP statement and the GitHub repo's own content both
    predate or coincide with that date).
  - 2026-11-05 (daily): the committee's governance document (RULES AND PROCEDURES, see evidence)
    adds the conflict-of-interest/no-academic-credit terms the group operates under — process
    detail, not a correctness or scope update. Located but could NOT open a second, more
    substantive committee statement (dated 2026-11-03, per Woit's blog) that reportedly commits to
    releasing the Lean proof "next week" — every filename guess 404'd; chase again next session
    (try the KITP activity page's own file listing or a `tvly search` for the exact filename).
    last_evidence advances 2026-10-27 → 2026-11-03 (the governance doc's own date). No stage/
    confidence change — still no public manuscript, Lean proof, or committee assessment.
  - 2026-11-16 (daily): THE STANDING TOP-PRIORITY CHASE ITEM RESOLVED — the Lean proof and the
    committee's own assessment were released Nov 9-10 (see the `assessment-1.pdf` evidence line,
    read directly via `pdftotext` this session) and corroborated by Woit's critical Nov 11 post and
    Scientific American's Nov 11/12 piece (both opened this session). Precise scope now
    primary-sourced rather than inferred: EXISTENCE is established only in the WEAK
    (subsequential-limit/compactness) sense, which the Jaffe–Witten problem statement itself
    explicitly excludes as a solution to the Millennium Problem's existence part (quoted verbatim
    in the Woit evidence line) — so this is a genuine, committee-endorsed advance, but is NOT a
    resolution of the Millennium Problem as traditionally framed, and the mass gap/uniqueness
    remain explicitly unproved by the committee's own words. A hexagonmath third-party compilation
    of the same Oct 28 submission (2611.00492, EXTREME caution, opened this session) independently
    states the same "not proved" list. CONFIDENCE RAISED low→medium: ≥2 independent authoritative
    sources (the committee's own primary assessment document + Scientific American's named-quote
    corroboration + Woit's informed critical reading, all converging on the identical scope) now
    corroborate on a concrete, inspectable artifact (the Lean repo + assessment PDF), satisfying the
    daily routine's confidence-bump bar — still `seed` (not escalated to `emerging`/`accelerating`:
    this remains one claim's unfolding vetting story, not a multi-group direction). Evidence-cap
    rotation: dropped the now-superseded 2026-11-03 governance/procedures PDF line (see notes
    above) to make room within the 10-item cap. Remaining open: Hairer's and Armstrong's
    independent human write-ups (github.com/hairer/humanise-yang-mills,
    github.com/scottnarmstrong/yang-mills-informalization) not yet independently opened; any Clay
    Mathematics Institute statement; the Alpöge–Sussman effort's reaction to this release.
  - 2026-11-17 (daily): a Part I "conditional mass-gap theorem" compilation surfaced on hexagonmath
    (see evidence above) — explicitly conditional on a registered assumption package, so this
    REFINES rather than reverses last session's scope finding (mass gap still not proved
    unconditionally). No stage/confidence change (`seed`/`medium`). last_evidence advances
    2026-11-15 → 2026-11-17.
  - 2026-11-27 (daily): MAJOR VETTING-PROCESS UPDATE — the shepherding committee's 4th statement
    (Nov 25, see evidence) discloses a concrete defect found and fixed in the FIRST (pure-YM)
    submission's formal theorem (too weak to establish the theorem proved was Yang–Mills theory,
    until the committee demanded stronger tests) and a crediting problem with the construction's
    prior-art attribution — the first committee-disclosed correctness issue on this claim. The
    committee also released the QCD and SU(5) chiral-gauge-theory ("Standard Model completion")
    submissions as explicitly UNASSESSED, citing unresolved controversy over their embargo-before-
    release policy. Peter Woit's same-day post ("The Shepherds Release the Flock," opened directly
    this session) calls the Standard-Model-completion claim "simply fraudulent" — the SU(5)
    construction has no Higgs field and nothing on electroweak/GUT symmetry breaking, so "it
    definitely has nothing to do with the Standard Model"; he finds the QCD material shows none of
    the physics (confinement, baryon/pion spectrum) one would expect either. His companion post
    ("Getting Access," Nov 18, also opened directly this session — closing a 2-session-old flagged
    item) reports a secretive "Alignment Institute for Fundamental Science" has formed among US
    QG/QFT theorists with privileged frontier-lab access, now with its own name/website per a
    same-post update. last_evidence advances 2026-11-17 → 2026-11-25. No stage/confidence change
    (`seed`/`medium`) — this sharpens the hype-skepticism caveat on the SM-completion and QCD
    sub-claims specifically (now expert-disputed, not merely unassessed), while the pure-YM
    weak-existence result itself stands, now committee-stress-tested. Chase next session: any
    community reaction once the newly-released QCD/chiral assessment PDFs are read in full (only
    Woit's summary was read this session).

### Resolution of the Erdős–Nicolas–Sárközy conjecture (admissible-set counting)
- stage: seed | confidence: medium | first_seen: 2026-10-27 | last_evidence: 2026-11-19
- what: axis-1 DOMAIN-CADENCE LANDMARK: Erdős, Nicolas, and Sárközy (1991) conjectured that
  $\log a(N)\asymp\sqrt N$, where $a(N)$ counts "admissible" subsets of $\{1,\dots,N\}$ (any two
  subsets with equal sum have equal cardinality) — a 35-year-old named Erdős problem in additive
  combinatorics. Wang and Yang prove matching absolute-constant upper and lower bounds, resolving
  it. Ordinary (non-AI) human mathematics.
- evidence:
  - 2026-10-25 (v1) — https://arxiv.org/abs/2610.34372 — Guoqing Wang, Wenkai Yang, "Counting
    Admissible Sets of Integers: A Proof of the Erdős–Nicolas–Sárközy Conjecture." Abstract +
    authors verified via arXiv API this session (W46 version-history spot-check: silently revised
    to v2, updated 2026-11-08 — same title/authors, no new group; last_evidence advances
    accordingly; W47 version-history spot-check: a further silent revision to v3, updated
    2026-11-19 — same title/authors, no new group; last_evidence advances accordingly).
- notes: 2026-10-27 (daily, seed creation): caught in today's math category-rotation batch
  (keyword triage). Confidence `medium` (unrefereed preprint, standard caution). Watch for
  referee/community engagement.
  - 2026-W46 recalibration (Amendment I version-history spot-check): silent v2 found (above);
    last_evidence 2026-10-25 → 2026-11-08. No new group, no referee/vetting outcome. Confidence
    held medium.
  - 2026-W47 recalibration (Amendment I version-history spot-check): a further silent revision to
    v3, updated 2026-11-19 (above); last_evidence 2026-11-08 → 2026-11-19. No new group, no
    referee/vetting outcome. Confidence held medium.

### Complete Lean formalization of the Classification of Finite Simple Groups (CFSG, "the Enormous Theorem") — AxiomMath
- stage: seed | confidence: low | first_seen: 2026-10-28 | last_evidence: 2026-11-16
- what: axis-5 DOMAIN-CADENCE LANDMARK at the largest magnitude this ledger has tracked for
  formalized mathematics. AxiomMath — a new, previously untracked AI-mathematics organization
  (PI Letong Hong; core contributors Dean Cureton, Vasily Ilin, Bhavik Mehta, Niels Voss) —
  states it has produced the first complete machine-checked Lean 4 proof of the Classification
  of Finite Simple Groups: every finite simple group is cyclic of prime order, alternating
  ($n\ge5$), one of 16 infinite families of Lie type, or one of the 26 (27 counting the Tits
  group) sporadic groups. The original ("first-generation") proof, assembled across roughly
  500 papers/books by ~100 mathematicians over decades under Gorenstein's organizing project,
  had never been independently machine-checked end-to-end; the field has lived with persistent
  doubts about its sheer length and dispersal (the historical 600-page unpublished quasithin
  manuscript gap is the most famous close call). AxiomMath's agent-swarm effort (24 days,
  ~43.1M lines of Lean, reportedly the largest open-source Lean project by volume) reports 34
  "noteworthy deviations" from the published record — mostly typos/table errors — the most
  substantial being a genuine gap in John Walter's 1986 proof of the Unbalanced Group Theorem
  (the agents found counterexamples to a closure assertion the published proof relied on);
  AxiomMath replaced the broken step with a new argument built on Solomon's 1976 work, in
  consultation with CFSG's own leading living authorities, Richard Lyons and Ronald Solomon
  (co-authors of the standard ongoing CFSG-revision project). EXTREME hype-skepticism caution —
  a wholly new, self-published organization with no independent outside verification, of
  either the 43.1M-line Lean build or the mathematics, as of this session; the Hacker News
  discussion (192 points) raises the standard "how do we know the formalization itself has no
  errors" question with no resolution offered. Track the vetting OUTCOME — whether Lyons/
  Solomon or any independent group confirms the build and the UGT replacement — not the claim
  itself.
- evidence:
  - 2026-10-27 (HN submission date; the site itself shows no explicit publication date) —
    https://cfsg.axiommath.ai/ — AxiomMath's interactive CFSG proof-map page: states the full
    first-generation classification, ~43.1M lines of Lean, "every logical step checked by
    Lean's kernel," code at `github.com/AxiomMath/CFSG`. Opened directly via `WebFetch` this
    session.
  - 2026-10-26 — https://axiommath.ai/research/the-enormous-theorem-formalized/ — AxiomMath's
    own announcement post: the 24-day/43.1M-line effort, the 34 deviations, the Unbalanced
    Group Theorem gap and its Solomon-1976-based replacement (new Theorem 2.3, later shortened
    via Remark 9.5), and consultation with Richard Lyons and Ronald Solomon. Opened directly
    via `WebFetch` this session.
  - 2026-10-27 (hexagonmath feed timestamp) — https://hexagonmath.org/2610.00575 — "The
    Unbalanced Group Theorem," the accompanying paper presenting the replacement argument.
    Opened directly via `curl` this session (title confirmed live).
  - 2026-11-16 — https://axiommath.ai/research/beyond-the-classification-what-the-cfsg-corpus-unlocks/
    — AxiomMath, "Beyond the Classification: What the CFSG Corpus Unlocks": reports 30 further
    published results formalized in Lean using the CFSG corpus (but not depending on the
    classification itself), including the Hall–Paige conjecture (all 26 sporadic groups), a
    remark of Serre on orders of Lie-type groups, a claim from Galois's 1832 letter, Nagao's 1966
    theorem, Baddeley's 1993 result, and a spectral characterization of the Tutte 12-cage; cites
    external papers (mostly DOI, one arXiv id: 1811.12671, Bray et al. 2020) and notes the
    Hall–Paige formalization still takes some corpus results as explicit inputs. No independent
    third-party verification reported. Opened directly via `WebFetch` this session.
- notes: 2026-11-19 (daily): first evidence of the CFSG corpus being used for DOWNSTREAM
  formalization (a vetting-relevant signal — a usable, extensible corpus is harder to fake
  convincingly than an isolated claim — though still self-reported, no outside confirmation).
  Confidence held `low` (unchanged).
- notes: 2026-10-28 (daily, seed creation): caught via the Hacker News front page (192 points,
  52 comments, "Classification of Finite Simple Groups Formalized in Lean") — the standout
  catch of the day. `axiommath.ai` staged as a new discovered-source candidate in SOURCES.md
  (first sighting, 2026-10-28). `github.com/AxiomMath/CFSG` 403'd under this session's GitHub
  proxy-scoping — not independently opened; re-attempt via `tvly extract` next session. Watch
  for (top daily-chase priority): any statement FROM Richard Lyons or Ronald Solomon themselves
  (as opposed to AxiomMath's own account of consulting them); any independent rebuild/
  verification attempt of the Lean codebase; commentary from the formal-math/group-theory
  community (Kevin Buzzard, Thomas Hales, the Lean Zulip, group-theory blogs) once the story
  reaches the usual digest lane — none of Tao/Woit/Kalai/Gowers/Baez had posted on this as of
  this session (the story is hours old at run time).

### Kaplansky's group-ring conjectures fail in positive characteristic (torsion-free hyperbolic groups)
- stage: seed | confidence: low | first_seen: 2026-11-04 | last_evidence: 2026-11-04
- what: axis-1 DOMAIN-CADENCE LANDMARK, caught in today's math full-category arXiv sweep
  (math.GR/RA). Kaplansky's four group-ring conjectures (zero-divisor, idempotent, unit,
  and the related soficity/surjunctivity questions) are textbook-famous open problems since
  the 1940s/1950s on whether group algebras of torsion-free groups can be "pathological." This
  paper shows ALL FOUR fail in positive characteristic for torsion-free word-hyperbolic groups:
  for every prime $p$ there is a finitely presented, torsion-free, word-hyperbolic group $G$
  (finite 2-dim classifying space) with $a,b\in\mathbb F_p[G]$, $ab=1\ne ba$ — a non-trivial
  idempotent, zero divisor and unit over every field of characteristic $p$, and $G$ is neither
  sofic nor surjunctive.
- evidence:
  - 2026-11-03 (v1) — https://arxiv.org/abs/2611.04599 — Nidhal Mghirbi, Seth Douglas,
    "Kaplansky's conjectures fail for torsion-free hyperbolic groups in positive characteristic":
    for $p=2$ the group $G$ and elements $a,b$ come "from OpenAI's random construction" (an
    AI-watch-lane connection — the counterexample seed itself is AI-generated; tracked for the
    mathematical RESULT, not the AI method). Abstract + authors verified via arXiv API this
    session.
- notes: 2026-11-04 (daily, seed creation): unrefereed arXiv preprint — PROVISIONAL under the
  hype-skepticism rule pending independent engagement, though Kaplansky's conjectures are
  famous enough that expert reaction should surface quickly if there is a gap. Watch for
  independent verification and any commentary from group-ring-theory specialists.

### Every classifiable simple C*-algebra has a C*-diagonal (completing the Elliott classification programme's diagonal question)
- stage: seed | confidence: low | first_seen: 2026-11-04 | last_evidence: 2026-11-04
- what: axis-1 DOMAIN-CADENCE LANDMARK (math.OA), caught in today's math full-category sweep.
  Combined with Xin Li's prior construction in the stably-finite setting, this paper constructs
  C*-diagonals in all UCT Kirchberg algebras, completing the proof that EVERY classifiable
  simple C*-algebra (in the sense of the Elliott classification programme) admits a C*-diagonal
  — every UCT Kirchberg algebra in fact admits an untwisted principal étale groupoid model with
  a finite-dimensional unit space.
- evidence:
  - 2026-11-03 (v1) — https://arxiv.org/abs/2611.04648 — Samuel Evington, Philipp Sibbel, "Every
    classifiable simple C*-algebra has a C*-diagonal." Abstract + authors verified via arXiv API
    this session.
  - 2026-11-11 (v1) — https://arxiv.org/abs/2611.16079 — Nikolay A. Ivanov, Ali I. Raad, "Every
    classifiable stably finite $C^*$-algebra has an untwisted étale groupoid model": shows every
    classifiable STABLY FINITE C*-algebra is isomorphic to the C*-algebra of a second-countable,
    locally compact Hausdorff, principal étale groupoid (equivalently has a C*-diagonal with
    trivial Weyl twist). Combined with Evington–Sibbel's UCT-Kirchberg result above, this
    completes untwisted principal groupoid models for EVERY classifiable C*-algebra (purely
    infinite and stably finite cases together). Abstract + authors verified via arXiv abstract
    page this session.
- notes: 2026-11-04 (daily, seed creation): unrefereed arXiv preprint, PROVISIONAL pending
  referee/community engagement; a program-completing result within a well-established
  classification research program (Elliott programme), so the claim is well-specified against
  known prior work (Xin Li's stably-finite construction) rather than an isolated surprise. Watch
  for operator-algebra community reaction.
  - 2026-11-17 (daily): caught via today's math.OA listing scan — the stably-finite companion to
    this trend's UCT-Kirchberg result (see evidence above), together closing the full classification
    programme's groupoid/diagonal question. No stage change; confidence held `low` (still no
    outside community reaction found). last_evidence advances 2026-11-04 → 2026-11-11.

### Progress toward the abc conjecture: a weak form proved via adelic intersection theory (Soulé)
- stage: seed | confidence: low | first_seen: 2026-11-04 | last_evidence: 2026-11-04
- what: axis-1 EXTRAORDINARY-CLAIM caution (same tier as the quasi-RH/Yang-Mills entries): the
  abc conjecture is one of the most famous open problems in number theory (Masser-Oesterlé
  1985), with a long, unresolved, and highly controversial prior claimed-proof saga
  (Mochizuki's IUT). A single, highly credible author (Christophe Soulé, IHES) now proves a
  WEAK FORM of the abc conjecture, plus a conjecture of Vojta for curves of genus two, via
  adelic intersection theory, following a method "envisioned by Parshin and Moret-Bailly." This
  is explicitly PARTIAL progress, NOT a full resolution of the abc conjecture itself — seeded
  here (rather than queued) given the conjecture's outsized significance to the field; any
  movement on it merits standing-watch treatment.
- evidence:
  - 2026-11-03 (v1) — https://arxiv.org/abs/2611.05217 — Christophe Soulé, "On the abc
    conjecture." Abstract + author verified via arXiv API this session.
  - 2026-11-12 — https://hexagonmath.org/2611.00330v1 — Zeng Chunping, "Explicit Weak abc
    Inequalities and the Discrete Obstruction to Full abc in the DIC Framework": an independent
    technical audit of Soulé's preprint, opened and read via the hexagonmath `/rss/all` feed
    this session. Finds that full abc is unattainable inside Soulé's audited construction for
    nine independent reasons, NONE depending on the truth of Soulé's Theorem A itself — i.e. the
    construction is structurally capped at a polynomial-type weak bound and cannot be
    bootstrapped to the full conjecture, regardless of whether Theorem A holds.
- notes: 2026-11-04 (daily, seed creation): EXTREME caution — single-author, unrefereed arXiv
  preprint on one of number theory's most famous and most hype-sensitive open problems; Soulé's
  standing (IHES, a highly credible algebraic/arithmetic geometer) lends weight, but "weak form"
  means this is explicitly NOT a full resolution. Flag "unrefereed preprint — partial claim."
  Watch for: expert commentary (this will likely surface quickly given the conjecture's profile),
  and clarification of exactly how "weak" the proved form is relative to the full conjecture.
  2026-11-12 (daily, vetting-status update): an independent hexagonmath audit (Zeng Chunping)
  confirms the "weak form only" framing from the inside — it finds Soulé's method structurally
  cannot reach the full conjecture (not a flaw found in Theorem A, but a limits-of-the-method
  result). Stage/confidence unchanged (still `seed`/`low`): this clarifies rather than
  strengthens or weakens the existing claim. EXTREME caution applies equally to this audit
  itself (also unrefereed, single-author).

### An elementary proof of the Binary Goldbach Conjecture (unrefereed preprint — claim)
- stage: seed | confidence: low | first_seen: 2026-11-09 | last_evidence: 2026-11-06
- what: axis-1 EXTRAORDINARY-CLAIM. The binary Goldbach conjecture (every even integer greater
  than 4 is the sum of two odd primes) is one of the oldest and most famous open problems in
  number theory. Qazaqzeh and Rawashdeh claim a proof by showing the count of ordered Goldbach
  pairs summing to $2n$ is $\Omega(n/\ln^2 n)$ (hence always $\ge1$), and apply the same method to
  re-derive the ternary Goldbach conjecture (already proved by Helfgott et al.). Two-author,
  ordinary (non-AI) human mathematics, brand-new (zero days old this session), no referee or
  community engagement yet. Per the hard-rule hype-skepticism clause this is flagged "unrefereed
  preprint — claim," PROVISIONAL until independent vetting — a claim of this magnitude on a
  problem this old warrants extreme caution; track the vetting outcome, do not adjudicate the
  mathematics.
- evidence:
  - 2026-11-06 (v1) — https://arxiv.org/abs/2611.09007 — Qazaqzeh, Rawashdeh, "An Elementary Proof
    of the Binary Goldbach Conjecture." Abstract + authors verified via arXiv API this session.
- notes: 2026-11-09 (daily, seed creation): caught via today's math-category arXiv API sweep
  (math.NT). Confidence `low` (single brand-new preprint, extraordinary claim on a 280-year-old
  conjecture, zero corroboration). Watch for number-theory community response/rebuttal — a claim
  this size on a problem this famous typically draws fast expert commentary either way.

### A proof of the Aaronson-Ambainis conjecture (quantum query complexity)
- stage: seed | confidence: medium | first_seen: 2026-11-09 | last_evidence: 2026-11-06
- what: axis-4 DOMAIN-CADENCE LANDMARK (quantum foundations/complexity of quantum systems — the
  SCIENCE side, not a QC-technology result). Aaronson and Ambainis (2008) conjectured every
  bounded low-degree polynomial on the discrete cube has an influential variable, which would
  imply every $T$-query quantum algorithm's acceptance probability is approximable on most inputs
  by a classical $\mathrm{poly}(T)$-query algorithm. David Turturean proves the conjecture
  (elementary proof, degree-$d$ bound $c\,\mathrm{Var}(f)^{5/2}/d^6$), confirming that
  superpolynomial quantum query speedups require input structure (a promise). Single author,
  ordinary human mathematics; standard unrefereed-preprint caution.
- evidence:
  - 2026-11-06 (v1) — https://arxiv.org/abs/2611.09773 — David Turturean, "A proof of the
    Aaronson-Ambainis conjecture." Abstract + author verified via arXiv API this session.
- notes: 2026-11-09 (daily, seed creation): caught via today's physics-category arXiv API sweep
  (cs.CC, cross-listed quant-ph-adjacent). Confidence `medium` (single author, brand-new, no
  corroboration yet — but a well-known, long-standing (2008) named conjecture in quantum
  complexity theory, a frequently-cited open problem in the field).

### Complete Lean formalization of Faltings' Theorem (Mordell Conjecture) — AxiomMath
- stage: seed | confidence: low | first_seen: 2026-11-13 | last_evidence: 2026-11-12
- what: axis-5 WATCH + axis-1 formalization landmark, EXTREME caution tier (same as the
  already-tracked CFSG-in-Lean and Weil-conjectures-in-Lean claims from the same organization —
  no outside verification of AxiomMath's claims exists yet). Faltings' Theorem (the 1983 proof of
  the Mordell Conjecture: a curve of genus ≥2 over ℚ has only finitely many rational points) is
  one of the deepest results in arithmetic geometry. AxiomMath claims a complete Lean
  formalization, reusing components from its own prior Stacks Project formalization.
- evidence:
  - 2026-11-12 — https://axiommath.ai/research/faltings-theorem-formalized — AxiomMath blog
    announcement; names the companion repository `github.com/AxiomMath/Mordell`. Opened and read
    directly via `curl` this session.
- notes: 2026-11-13 (daily, seed creation): caught via today's axiommath.ai/research/ sweep.
  Confidence `low` (not `medium`): unlike the CFSG/Weil claims, this session could not reach
  `github.com/AxiomMath/Mordell` directly (GitHub proxy-scoping) to confirm a `sorry`-free/
  kernel-checked status — the blog post itself does not state one (no "sorry"/"kernel"/"Mathlib"
  mention found in the page text this session). Watch for: direct repo verification (via `tvly
  extract` next session), any outside review, and whether this is held to the same CFSG-style
  "peer-review before being merged into mathlib" standard.

### Complete Lean formalization of the Weil Conjectures (AxiomMath)
- stage: seed | confidence: low | first_seen: 2026-11-09 | last_evidence: 2026-11-06
- what: axis-5 LANDMARK formalization (EXTREME caution tier — same brand-new org as the
  already-tracked CFSG-in-Lean claim, no outside verification yet). AxiomMath (lead Tony Yue Yu;
  contributors incl. Kenny Lau, Jannis Limperg, Ken Ono) reports a complete, sorry-free Lean
  formalization of the four classical Weil conjectures (Deligne's 1974 theorem, building on
  Dwork/Grothendieck/Artin-Verdier machinery): rationality of the zeta function, the functional
  equation, the topological (Betti-number) comparison, and the Riemann-hypothesis-analogue bound
  on Frobenius eigenvalues — proved via Laumon's Fourier-transform route rather than reproducing
  Deligne's original argument, reusing AxiomMath's own prior Stacks Project Lean formalization
  (already on `study_shelf`), with no axioms beyond Lean's standard logical foundations per the
  org's own description. A formal proof of the Ramanujan tau bound is explicitly NOT included.
  No arXiv manuscript; the only artifact is the GitHub repository itself.
- evidence:
  - 2026-11-06 — https://github.com/AxiomMath/Weil/tree/27cdb2049be62ee2911429b47f54774078450e32
    — AxiomMath/Weil repository, pinned revision. Blog announcement
    https://axiommath.ai/research/the-weil-conjectures-formalized-in-lean/ (dated 2026-11-06,
    "repository scope and review status checked November 5, 2026") opened directly via `WebFetch`
    this session.
- notes: 2026-11-09 (daily, seed creation): caught via today's axiommath.ai/research/ sweep.
  Confidence `low` (same EXTREME-caution tier as the org's CFSG-in-Lean claim: brand-new org, no
  independent Lean/mathlib-community review of the repository yet, no arXiv write-up). Watch for:
  Lean/mathlib-community commentary on the repository (Kenny Lau's involvement as a contributor is
  a point in favor of technical credibility but not itself independent verification); whether the
  repo's claimed sorry-free status holds up under outside inspection.

### Disproof of Guralnick's conjecture (unbounded cohomology of finite simple groups)
- stage: seed | confidence: medium | first_seen: 2026-11-10 | last_evidence: 2026-11-17
- what: axis-1 DOMAIN-CADENCE LANDMARK (representation theory / finite group cohomology). Bowman,
  de la Fuente, Libedinsky and Plaza show that, in every fixed positive degree, the cohomology of
  finite simple groups, algebraic groups and quantum groups (coefficients in simple modules) can
  have arbitrarily large dimension — disproving Guralnick's conjecture, which predicted a uniform
  bound. Four-author, ordinary human mathematics; standard unrefereed-preprint caution.
- evidence:
  - 2026-11-08 (v1, revised 2026-11-17 v2) — https://arxiv.org/abs/2611.11677 — Bowman, de la
    Fuente, Libedinsky, Plaza, "The cohomology of finite simple groups is unbounded." Abstract +
    authors verified via direct arXiv `/abs/` fetch this session (W47 version-history spot-check:
    silently revised to v2, updated 2026-11-17 — same authors/result, no new group; last_evidence
    advances accordingly).
- notes: 2026-11-10 (daily, seed creation): caught via today's math-category arXiv batch
  (math.GR, title-triage). Confidence `medium` (brand-new, no corroboration yet).
  - 2026-W47 recalibration (Amendment I version-history spot-check): silent v2 found (above);
    last_evidence 2026-11-08 → 2026-11-17. No referee/vetting outcome, no independent group yet.
    Confidence held medium.

### Proof of Gromov's conjecture on nilpotent groups (integrable measure equivalence)
- stage: seed | confidence: medium | first_seen: 2026-11-10 | last_evidence: 2026-11-09
- what: axis-1 DOMAIN-CADENCE LANDMARK (geometric group theory). Kajal Das proves Gromov's
  well-known conjecture that quasi-isometric infinite finitely-generated torsion-free nilpotent
  groups have isomorphic Mal'cev completions (as Lie groups), via the stronger statement for
  integrable measure equivalence, combined with Shalom's theorem to give a three-way equivalence
  (quasi-isometry ⟺ integrable measure equivalence ⟺ isomorphic Mal'cev completions). Single
  author, ordinary human mathematics; standard unrefereed-preprint caution.
- evidence:
  - 2026-11-09 (v1) — https://arxiv.org/abs/2611.12009 — Das, "Integrable Measure Equivalence and
    Gromov's conjecture on nilpotent groups." Abstract + author verified via direct arXiv `/abs/`
    fetch this session.
- notes: 2026-11-10 (daily, seed creation): caught via today's math-category arXiv batch
  (math.GR, title-triage — "Gromov's conjecture" keyword). Confidence `medium` (single author,
  brand-new, no corroboration yet).

### Resolution of the Δ-primitive-squares conjecture (Erdős–Rosenfeld factor-difference sets)
- stage: seed | confidence: medium | first_seen: 2026-11-10 | last_evidence: 2026-11-08
- what: axis-1 DOMAIN-CADENCE LANDMARK (combinatorial number theory). Golfieri and Schvöllner prove
  that the set of natural numbers with the "$\Delta$ property" (related to the Erdős–Rosenfeld
  factor-difference set being non-sum-free) contains infinitely many $\Delta$-primitive perfect
  squares, as conjectured — and show these squares can avoid any prescribed finite set of primes
  other than 3. Two-author, ordinary human mathematics; standard unrefereed-preprint caution.
- evidence:
  - 2026-11-08 (v1) — https://arxiv.org/abs/2611.11574 — Golfieri, Schvöllner, "On the
    $\Delta$-primitive squares conjecture." Abstract + authors verified via direct arXiv `/abs/`
    fetch this session.
- notes: 2026-11-10 (daily, seed creation): caught via today's math-category arXiv batch
  (math.NT, title-triage — named-conjecture keyword). Confidence `medium` (brand-new, no
  corroboration yet).

### Resolution of the Falconer distance conjecture in all dimensions (OpenAI internal model; independent human exposition)
- stage: seed | confidence: low | first_seen: 2026-11-11 | last_evidence: 2026-11-10
- what: axis-1 DOMAIN-CADENCE LANDMARK + axis-5 AI-WATCH-LANE (track the result, not the method).
  Falconer's distance conjecture (Kenneth Falconer, 1985) — that a compact set $E\subset\mathbb R^d$
  with Hausdorff dimension greater than $d/2$ determines a set of Euclidean distances of positive
  Lebesgue measure — is a central, long-open problem in geometric measure theory (it is part of the
  body of work cited for Hong Wang's 2026 Fields Medal, already on this ledger). Result #073 of
  OpenAI's already-tracked mass mathematical-results disclosure (github.com/openai/math, internally
  dated 2026-09-23, publicly released 2026-10-06) claims a full proof in every integer dimension
  $d\ge2$. Today's new primary is an INDEPENDENT human exposition: five mathematicians (Kotaro
  Inami, Jianbin Li, Yudong Liang, Bochen Liu, Francisco Romero Acosta) post an arXiv preprint
  presenting the proof "in our own words... designed for graduate-level readers" — the same
  human-engagement pattern as the already-tracked Erdős unit-distance disproof (Alon et al.'s
  "Remarks on..."), though with fewer/less senior authors and no explicit correctness-verification
  claim (they say they "catch the main idea," not that every step was checked). HEAVIEST
  hype-skepticism caution: the original proof is wholly AI-generated and UNREFEREED; the repo's own
  Lean artifact (`lean/ComparatorChallenges/FalconerAllDimensions.lean`) is a target STATEMENT
  only, with a `sorry` in place of the proof — opened and confirmed directly this session, not
  merely claimed.
- evidence:
  - 2026-10-07 (repo commit date; internally dated 2026-09-23) — https://github.com/openai/math/blob/main/preprints/The-Falconer-distance-conjecture-in-all-dimensions-September-23-2026/paper.pdf
    — OpenAI's own manuscript, result #073 of the mass-disclosure corpus; `CONTENTS.md` entry and
    the Lean comparator stub (`sorry`-containing) opened directly via `raw.githubusercontent.com`
    this session.
  - 2026-11-10 (v1) — https://arxiv.org/abs/2611.13789 — Inami, Li, Liang, Liu, Romero Acosta, "On
    the proof of Falconer distance conjecture": independent human exposition of the OpenAI proof;
    abstract + authors verified via the arXiv API this session.
- notes: 2026-11-11 (daily, seed creation): caught via today's math.CA arXiv title-triage ("proof
  of... conjecture" keyword); chased to the OpenAI mass-disclosure corpus via `tvly search`
  (confirmed the Sept 23 2026 manuscript, result #073) and verified the GitHub artifacts directly.
  Cross-references the already-seeded "OpenAI's mass mathematical-results disclosure" trend (same
  corpus) — this is item #073 of that corpus, now given its own dedicated trend given the problem's
  standalone fame and a fresh independent-exposition primary, mirroring how the quasi-Riemann-
  Hypothesis and Yang–Mills items from the same corpus each got dedicated trends. Confidence held
  at `low` (not `medium`): the human exposition does not claim to have verified correctness, and
  the Lean artifact is an unproved target statement. Watch for: a completed (`sorry`-free) Lean
  formalization; independent commentary from geometric-measure-theory specialists (Iosevich, Guth,
  Wang, Keleti).

### Resolution of Smale's mean value conjecture (1981) — $\sup_d K(d)=4$ (hexagonmath, AI-assisted, unrefereed preprint — claim)
- stage: seed | confidence: low | first_seen: 2026-11-11 | last_evidence: 2026-11-11
- what: axis-1 DOMAIN-CADENCE LANDMARK + axis-5 AI-WATCH. Smale's mean value conjecture (Steve
  Smale, 1981) asked whether his proven bound $K(d)\le4$ (relating a polynomial's value at a point
  to its value at a critical point) could be sharpened to $K=1$; Jatar–Ng already disproved "K=1
  suffices" earlier in 2026 ($K^*>1$). A new hexagonmath.org preprint by a single contributor
  (Dave Goel) now claims to settle the REMAINING open question — the exact value of Smale's mean
  value constant $\sup_d K(d)$ — proving it equals 4 (the trivial upper bound itself, not attained
  for any finite $d$), combining "a reduction due to Jatar and Ng" with an explicit construction,
  and states the result "has also been formalized in the Lean 4 proof assistant" (not independently
  located/opened this session). HEAVIEST hype-skepticism caution: hexagonmath's own provenance tag
  for this submission reads "a mix of human-written and AI-generated text... Human understanding:
  some parts" — a self-admission of PARTIAL human understanding of its own submission, the most
  explicit uncertainty flag this ledger has logged on a claimed full resolution; single
  contributor, no independent review.
- evidence:
  - 2026-11-11 (v1) — https://hexagonmath.org/2611.00282v1 — Dave Goel, "Smale's mean value
    constant (1981) equals 4": abstract + provenance tag ("mix of human-written and AI-generated
    text... Human understanding: some parts") opened directly via `curl`/page fetch this session.
  - 2026-11-11 (v1, superseded by the above, same day) — https://hexagonmath.org/2611.00306v1 —
    same author, "Smale's mean value constant (1981) exceeds 1.1559...": the immediately-preceding
    partial bound, kept as a record of the claim's same-day progression.
- notes: 2026-11-11 (daily, seed creation): caught via today's hexagonmath.org `/rss/all` feed
  sweep (title-triage — named constant/conjecture). Confidence `low` given the self-disclosed
  partial human understanding, single contributor, unrefereed, no-peer-review venue. Watch for: the
  Lean formalization artifact itself (not located this session — check the submission's own source
  files next run); any response from complex-analysis specialists.

### Disproof of the Erdős–Mahler conjecture (1939) on irrationality-exponent continued fractions (Marques)
- stage: seed | confidence: medium | first_seen: 2026-11-11 | last_evidence: 2026-11-10
- what: axis-1 DOMAIN-CADENCE LANDMARK, human-authored (no AI involvement disclosed). A 1939
  conjecture of Erdős and Mahler is disproved: for every real $τ\ge4$, Diego Marques constructs a
  Cantor set of numbers of irrationality exponent $τ$, each having infinitely many regular
  continued-fraction convergents of the restricted form $2^a/3^b$ — a case the 87-year-old
  conjecture predicted should not occur. Single-author, standard (not AI-related) unrefereed-
  preprint caution.
- evidence:
  - 2026-11-10 (v1) — https://arxiv.org/abs/2611.13604 — Diego Marques, "A counterexample to the
    Erdős–Mahler conjecture": abstract + author + date verified via the arXiv API this session.
- notes: 2026-11-11 (daily, seed creation): caught via today's math.NT arXiv title-triage
  ("counterexample to... conjecture"). Confidence `medium` (ordinary human mathematics, single
  preprint, no corroboration yet).

### Proof of the quantum Kazhdan–Lusztig conjecture for quantum loop algebras
- stage: seed | confidence: medium | first_seen: 2026-11-12 | last_evidence: 2026-11-12
- what: axis-1/2 DOMAIN-CADENCE LANDMARK, human-authored. The Kazhdan–Lusztig conjecture
  (1979) and its quantum-group analogues are a central theme in representation theory; the
  quantum-loop-algebra case (studied e.g. by Varagnolo–Vasserot) has remained open. Qiyue Tang
  proves it for finite-dimensional type-1 representations of untwisted quantum loop algebras
  at every non-root-of-unity complex parameter. Standard unrefereed-preprint caution.
- evidence:
  - 2026-11-12 — https://hexagonmath.org/2611.00322v1 — Qiyue Tang, "The Quantum
    Kazhdan–Lusztig Conjecture for Quantum Loop Algebras": full description opened and read via
    the hexagonmath `/rss/all` feed this session.
- notes: 2026-11-12 (daily, seed creation): caught in today's hexagonmath.org sweep. Confidence
  `medium`.

### Proof of Euler's 1747 conjecture on sums of integers with restricted prime factors
- stage: seed | confidence: medium | first_seen: 2026-11-13 | last_evidence: 2026-11-12
- what: axis-1 DOMAIN-CADENCE LANDMARK, a genuine 279-year-old conjecture. In a 1747 letter to
  Goldbach, Euler proposed that every positive integer congruent to 2 mod 4 is a sum of two
  positive integers whose prime factors are all congruent to 1 mod 4 (with 1 admissible as a
  summand). This paper proves it in full: a four-squares representation-counting argument bounds
  the exceptional cases containing a common prime divisor ≡3 mod 4, reducing to an explicit
  finite threshold ($64^4$) checked by a finite arithmetic certificate covering the remaining
  4,194,304 integers. Hexagonmath-hosted; standard unrefereed-preprint caution (no named author
  found on the page this session — flag to re-check attribution next session).
- evidence:
  - 2026-11-12 — https://hexagonmath.org/2611.00370v1 — "Euler's 1747 conjecture on sums of
    integers with restricted prime factors": full proof via quaternionic Hecke bounds + a finite
    arithmetic certificate. Opened and read directly via the hexagonmath `/rss/all` feed this
    session (full description/abstract text retrieved).
- notes: 2026-11-13 (daily, seed creation): caught via today's hexagonmath `/rss/all` sweep
  (50-item batch). Watch for: author attribution (not found this session), independent
  verification of the finite certificate, any named-number-theorist commentary.

### Undecidability and a counterexample to any-dimensional Hilbert's 17th problem (Debus–Schabert)
- stage: seed | confidence: medium | first_seen: 2026-11-13 | last_evidence: 2026-11-12
- what: axis-1 DOMAIN-CADENCE LANDMARK, human-authored arXiv primary, with an axis-4 crossover
  consequence. Two results: (1) it is UNDECIDABLE whether a symmetric function with rational
  coefficients is nonnegative in every dimension, answering a question of Acevedo–Blekherman–
  Debus–Riener — as a direct consequence, deciding dimension-free moment criteria for
  entanglement in quantum information is also undecidable; (2) a degree-8 homogeneous symmetric
  function is exhibited that is positive-definite in every dimension but admits NO sum-of-squares
  multiplier uniform in the dimension — a genuine counterexample showing Artin's solution of
  Hilbert's 17th problem and the Krivine–Stengle Positivstellensatz have no any-dimensional
  analog, refuting the any-dimensional Positivstellensätze sought by Levin and Chandrasekaran.
  Standard unrefereed-preprint caution.
- evidence:
  - 2026-11-12 (v1) — https://arxiv.org/abs/2611.16690 — Sebastian Debus, Robin Schabert,
    "Hilbert's 17th problem for symmetric functions: undecidability and a counterexample".
    Abstract/authors verified via arXiv API this session.
- notes: 2026-11-13 (daily, seed creation): caught via today's math.AG/math.OC/quant-ph
  cross-listed title-triage sweep (title keyword "counterexample"). Watch for: independent
  commentary from real-algebraic-geometry or quantum-information specialists on the
  entanglement-criterion consequence.

### Resolution of Erdős Problem 521 on real roots of random polynomials
- stage: seed | confidence: medium | first_seen: 2026-11-13 | last_evidence: 2026-11-15
- what: axis-1 DOMAIN-CADENCE LANDMARK, human-authored arXiv primary — resolves Erdős Problem 521
  (from the curated Erdős-problems collection, the same class of named-problem resolution this
  ledger already tracks for Lehmer's 1965 conjecture and the Komlós/Beck-Fiala conjectures).
  Proves that for Rademacher random polynomials, the normalized real-root count $N_n/\log n$
  almost surely has NO limit; more generally, for Kac polynomials with i.i.d. mean-zero,
  variance-one real coefficients and a finite exponential moment, the $\liminf$ is exactly
  $1/\pi$, the $\limsup$ is $1/\pi+C_*$ for an explicit constant $C_*$, and the set of
  subsequential limits is exactly the interval between them. Standard unrefereed-preprint
  caution.
- evidence:
  - 2026-11-12 (v1, revised 2026-11-15 v2) — https://arxiv.org/abs/2611.16157 — Zengjing Chen,
    Xiaodong Liu, Jie Peng, Hanchao Wang, Mingjian Zhang, "The limit point set of real roots of
    random polynomials: a resolution of Erdős Problem 521". Abstract/authors verified via arXiv
    API this session (W47 version-history spot-check: silently revised to v2, updated 2026-11-15
    — same authors/result, no new group; last_evidence advances accordingly).
- notes: 2026-11-13 (daily, seed creation): caught via today's math.PR title-triage sweep (title
  states the resolution explicitly). Watch for: independent verification/citation, and whether
  conjectures.io or another Erdős-problems tracker records this resolution.
  - 2026-W47 recalibration (Amendment I version-history spot-check): silent v2 found (above);
    last_evidence 2026-11-12 → 2026-11-15. No referee/vetting outcome, no independent group yet.
    Confidence held medium.

### Convergence toward evidence for evolving (dynamical) dark energy (DESI + DES + independent reanalyses)
- stage: emerging | confidence: medium | first_seen: 2026-11-17 | last_evidence: 2026-11-17
- what: axis-3 MULTI-GROUP DIRECTION trend (promoted via today's mandatory convergence check):
  ≥3 independent orgs/author groups now hold concrete artifacts converging on the same sub-theme
  — late-time cosmological evidence (currently ~3σ, NOT yet a 5σ discovery) that dark energy's
  equation of state evolves rather than staying constant (w0-wa beyond ΛCDM). Independent lines:
  (1) the DESI collaboration's own DR2 Key Papers; (2) the DES collaboration's independent
  final-dataset analysis (a DIFFERENT flagship survey, not a DESI reanalysis); (3)-(5) at least
  three independent academic reanalyses (Jiang–Shafieloo; Zheng–Qiang–You–Kumar; the
  model-independent spline reconstruction) plus a critical reanalysis (Kim–Mota–Tamosiunas)
  arguing the DESI-only signal is fragile/single-bin — the vetting-status split itself is part of
  what makes this a genuine, unresolved multi-group direction rather than a settled single claim.
  EXTRAORDINARY-CLAIM CAUTION (hype-skepticism rule): consistently ~3σ across analyses, below the
  5σ discovery threshold, look-elsewhere effects apply; track the vetting, do not call it resolved.
- evidence:
  - 2026-11-16 (Quanta/Fermilab pointer, opened directly this session) — https://arxiv.org/abs/2605.27221
    — DES collaboration final-dataset results (combined with DESI + CMB): a ~3σ preference for an
    evolving-dark-energy fit over ΛCDM; the mismatch between CMB, matter-clumping, and supernova
    datasets cannot be traced to any single dataset. Independent collaboration/survey from DESI —
    the key new convergence signal this session. Opened via `WebFetch` (Quanta Magazine article
    naming the arXiv id) this session.
  - 2026-07-29/07-31 — https://arxiv.org/abs/2607.27410 — DESI collaboration, "DESI DR2 Results IV:
    Alcock-Paczyński Measurements from the Lyman Alpha Forest and Cosmological Constraints": finds
    the w0-wa dynamical-dark-energy model preferred over ΛCDM at 2.7σ (DESI+CMB) / 3.2σ
    (+supernovae).
  - 2026-07-31 — https://arxiv.org/abs/2607.28918 — Kim, Mota, Tamosiunas, "A Sequentially-Valid
    Reanalysis of DESI's Dynamical Dark Energy Signal": an anytime-valid e-process critique finding
    the DESI signal concentrated almost entirely in one redshift bin, not surviving a
    look-elsewhere correction — the standing vetting-skeptic voice in this direction.
  - 2026-08-04 — https://arxiv.org/abs/2608.04763 — Jiang, Shafieloo, "Is Dark Matter Really
    Matter?": jointly fits $w_{dm}$/$w_{de}$ against DESI DR2 + Lyman-alpha AP + DES SNe + CMB,
    finding $w_{de}=-0.9380^{+0.0259}_{-0.0262}$ stays away from $-1$.
  - 2026-07-14 — https://arxiv.org/abs/2607.13009 — "Model-Independent Indication for a Localized
    Anomaly in the Late-Time Expansion History": a model-independent spline reconstruction of DESI
    DR2 BAO + DES SN distances finds a localized ~3.5σ deviation from Planck-2018 ΛCDM at z≈0.3–0.6.
- notes: 2026-11-17 (daily, promoted from observation_queue via the mandatory convergence check):
  this sub-theme has recurred across the queue since 07-15 (H₀-World-Cup/late-time-anomaly thread)
  without being promoted; today's DES final-dataset primary (an independent SURVEY/collaboration,
  not a DESI reanalysis) tips it over the ≥3-independent-groups bar alongside the DESI collaboration
  itself and ≥3 independent academic groups. Stage `emerging` (not `accelerating`: still one
  evolving story, ~3σ, actively contested — see the Kim-Mota-Tamosiunas critique). Several older
  below-bar queue lines on this same saga (07-15, 07-29/07-31, 08-04/08-05) remain in
  `observation_queue` for now rather than being retroactively pruned (no silent deletion); treat
  this trend as the forward-looking home for new evidence on this theme going forward.

### A proof of the Erdős–Herzog–Piranian lemniscate conjecture (univalent polynomials)
- stage: seed | confidence: low | first_seen: 2026-11-17 | last_evidence: 2026-11-09
- what: axis-1 LANDMARK (full resolution, source/fame-blind per the W46-ratified bar — see
  `routines/daily.md` §3): resolves a 1958 conjecture of Erdős, Herzog, and Piranian that for a
  monic degree-$n$ polynomial $p$, the lemniscate $\{z:|p(z)|=1\}$ has maximal length when
  $p(z)=z^n-1$; proved in every degree, with equality characterized exactly.
- evidence:
  - 2026-11-09 (v1) — https://arxiv.org/abs/2611.12830 — Teng Zhang, "A proof of the
    Erdős-Herzog-Piranian lemniscate conjecture." Abstract + author verified via direct arXiv
    `/abs/` fetch this session.
- notes: 2026-11-17 (daily, seed creation): caught via today's math.CV listing scan (a bounded-
  cycle-rotation category not yet due this cycle). Ordinary single-author academic preprint —
  standard unrefereed-preprint caution (hard rule); confidence `low` pending outside reaction.

### Independent proof of the Kiessling–Altshuler–Yuzbashyan (KAY) conjecture (Eliashberg $T_c$ bound)
- stage: seed | confidence: low | first_seen: 2026-11-17 | last_evidence: 2026-11-16
- what: axis-2/3 LANDMARK (math-ph / condensed-matter interface): proves the Kiessling–Altshuler–
  Yuzbashyan conjecture bounding the Eliashberg-theory superconducting critical temperature,
  $T_c<C(\lambda\langle\omega^2\rangle)^{1/2}$ with $C\approx0.1827$ sharp (a bound Leavens stated
  in 1977 on partly numerical grounds), plus all-coupling uniqueness of $T_c$, for every phonon
  spectrum with finite second moment — via an independent comparison-principle argument.
- evidence:
  - 2026-11-16 (v1) — https://arxiv.org/abs/2611.20496 — Davis Rens, "Sharp bounds on the Eliashberg
    critical temperature: a comparison principle, convexity in the spectrum, and the
    Kiessling-Altshuler-Yuzbashyan conjectures." Abstract + author verified via direct arXiv `/abs/`
    fetch this session.
- notes: 2026-11-17 (daily, seed creation): caught via today's math-ph listing scan. The abstract
  itself notes an earlier, not-yet-peer-reviewed Kondratev preprint already claimed this same
  bound — this is a SECOND, independent proof; watch for convergence/corroboration. Standard
  unrefereed-preprint caution; confidence `low`.

### Disproof of the El-Zahar–Erdős conjecture (bounded-clique chromatic bipartition)
- stage: seed | confidence: medium | first_seen: 2026-11-19 | last_evidence: 2026-11-18
- what: axis-1 LANDMARK (full resolution, source/fame-blind per the W46-ratified bar): El-Zahar
  and Erdős asked whether every graph of bounded clique number and sufficiently large chromatic
  number contains two vertex-disjoint induced subgraphs, each of large chromatic number, joined
  by no edge. Disproved even for triangle-free graphs: for every $g\ge4$, there exist graphs of
  girth $\ge g$ and arbitrarily large chromatic number in which any two disjoint induced
  subgraphs each requiring $\ge7$ colors are joined by an edge.
- evidence:
  - 2026-11-18 (v1) — https://arxiv.org/abs/2611.24735 — Chenghua Liu, Boning Meng, "A disproof
    of the El-Zahar–Erdős conjecture." Abstract + authors verified via direct arXiv page fetch
    this session (title-triage catch, math.CO category-rotation sweep).
- notes: 2026-11-19 (daily, seed creation): caught via today's full 35-category arXiv RSS sweep.

### A Counterexample to Voiculescu's Normal Dilation and Stable Classification Conjectures
- stage: seed | confidence: medium | first_seen: 2026-11-19 | last_evidence: 2026-11-18
- what: axis-1 LANDMARK (operator theory / operator algebras): constructs a compact operator $T$
  with trace-class self-commutator and vanishing Helton-Howe measure such that $T\oplus S-M\notin
  \mathcal S_2$ for every bounded $S$ and bounded normal $M$ — a counterexample to Voiculescu's
  normal dilation conjecture AND his stable classification conjecture. Uses magnetic shifts on
  finite square tori.
- evidence:
  - 2026-11-16 (v1), revised 2026-11-18 (v2) — https://arxiv.org/abs/2611.21495 — Xiang Tang, "A
    Counterexample to Voiculescu's Normal Dilation Conjecture." Abstract + author verified via
    direct arXiv page fetch this session (math.FA/OA category-rotation sweep).
- notes: 2026-11-19 (daily, seed creation): caught via today's full 35-category arXiv RSS sweep.

### The sharp constant in the Erdős maximum-term problem (hexagonmath, AI-assisted)
- stage: seed | confidence: low | first_seen: 2026-11-19 | last_evidence: 2026-11-18
- what: axis-1 LANDMARK, EXTREME caution (hexagonmath, unrefereed): for a transcendental entire
  function $f$, determines EXACTLY the supremum of $\liminf_{r\to\infty}\mu(r,f)/M(r,f)$ (maximum
  term vs. maximum modulus) as the reciprocal of the minimum circle norm in the He–Tang theta
  family, with the extremal function fully characterized — a full, sharp resolution of this named
  Erdős problem (stronger than the already-queued Erdős Problem 593 structural-description item,
  which stays below bar).
- evidence:
  - 2026-11-18 (hexagonmath pubDate) — https://hexagonmath.org/2611.00583v1 — Will Howe, Grant
    Huffman, Jensen Kohlmeyer, Liam Kruer, "The sharp constant in the Erdős maximum-term problem."
    Page opened directly via `WebFetch` this session; provenance statement: "AI tools assisted
    with developing and checking arguments and with drafting this manuscript," labeled "Primarily
    AI-generated text," "Human understanding: no parts."
- notes: 2026-11-19 (daily, seed creation): caught via today's hexagonmath `/rss/all` full-batch
  read. Same author group (Howe/Huffman/Kohlmeyer/Kruer) also behind the conjectures.io Erdős
  Problem 108 staged candidate (SOURCES.md) — watch for a pattern across this group's output.

### Proof of Stanley's Conjecture on the Leading Ehrhart Coefficients of the Birkhoff Polytope
- stage: seed | confidence: medium | first_seen: 2026-11-20 | last_evidence: 2026-11-19
- what: axis-1 LANDMARK (enumerative/algebraic combinatorics): full proof of a conjecture of
  Richard Stanley on the Ehrhart polynomial of the $n\times n$ Birkhoff polytope — writing $c(n,k)$
  for the coefficient of $r^{(n-1)^2-k}$, the paper proves $c(n,k)/c(n,0)\sim n^{3k}/(2^k k!)$ as
  $n\to\infty$ for every fixed nonnegative integer $k$, confirming Stanley's conjectured asymptotic.
- evidence:
  - 2026-11-19 — https://arxiv.org/abs/2611.25973 — Jiahang Liu, Jinlong Tang, "Proof of Stanley's
    Conjecture on the Leading Ehrhart Coefficients of the Birkhoff Polytope." Abstract + authors
    verified via direct arXiv page fetch this session (math.CO title-triage keyword hit).
- notes: 2026-11-20 (daily, seed creation): caught via the 35-category arXiv RSS sweep; a
  well-known conjecture of Stanley's on a classical object (the Birkhoff polytope), no outside
  engagement found yet.

### Alpöge's claimed Lean-formalized proof of the Riemann Hypothesis and GRH for Dirichlet L-functions (Claude-assisted)
- stage: seed | confidence: medium | first_seen: 2026-11-23 | last_evidence: 2026-11-25
- what: axis-1 LANDMARK CLAIM, the single largest-magnitude claim this ledger has ever tracked.
  Levent Alpöge (Harvard Society of Fellows; also affiliated with Anthropic) states he has,
  "working with Claude," discovered a Lean-4-formalized proof that $L(s,\chi)\neq0$ for
  $\mathrm{Re}(s)>1/2$ and every Dirichlet character $\chi$ — i.e. the classical Riemann
  Hypothesis (the $\chi=1$ case; a Clay Millennium Prize Problem) AND the Generalized Riemann
  Hypothesis for Dirichlet L-functions, posed by Riemann in 1859 (167 years). He states the method
  "easily extends" further and expects, with more time, the Extended RH too (not yet done). THE
  CENTRAL UNRESOLVED QUESTION: independent checks so far verify only that the Lean kernel(s) accept
  the formal proof of the STATED Lean theorems (internal logical consistency) — NOT that those
  formalized statements are a faithful rendering of the informal mathematical claim, nor that any
  human mathematician has read and understood the ~17-million-line argument. No referee, no
  published human exposition yet exists; this is day 1-3 of an unfolding, extremely fast-moving
  story. AI-WATCH-LANE: the method is AI-assisted, but the RESULT (RH/GRH) is this radar's beat.
- evidence:
  - 2026-11-20 — https://alpo.ge/remark.pdf — Alpöge's own 4-page announcement note ("Note on a
    proof of the Riemann hypothesis"), opened and read directly this session (PDF). In his own
    words: "I believe I have, working with Claude, discovered a proof of the Riemann Hypothesis. In
    fact, the method easily extends much further, resolving the so-called Generalized Riemann
    Hypothesis... Claude and I have also formalized the arguments without assumptions." States the
    argument is "incredibly long at the moment" and that he has "just taken a step" toward
    understanding it, not completed that understanding; names a long list of mathematicians he
    consulted/wants to credit (incl. Manjul Bhargava, Peter Sarnak, Maksym Radziwiłł). Links the Lean
    archive at https://alpo.ge/lean.tar.gz.part01 through part14.
  - 2026-11-22, UPDATED 2026-11-24 (page "last updated 2026-11-24 03:30 UTC") —
    https://math.mit.edu/~drew/grh/ — Andrew Sutherland (MIT), an independent, named, credible
    computational number theorist, runs a public verification-status page (checks run with Claude
    Code) for the Lean archive: opened directly this session. Confirms a full build of 175,187 Lean
    modules compiles with ZERO errors (Lean v4.33.1 / Mathlib v4.33.1), the five headline theorems
    depend ONLY on the three standard axioms (`propext`, `Classical.choice`, `Quot.sound`), and an
    independent SANDBOXED rebuild on a separate machine (no network, read-only source) reproduces
    the 61.57 GB export byte-for-byte. Since the 11-22 snapshot, every remaining check has now
    completed and PASSED: Comparator v4.33.0 end-to-end ("Your solution is okay!"), nanoda, con-leche,
    con-ron, lean4lean, Lean's default kernel AND its paranoid kernel all accept the full export; the
    one still-running check (`lake comparator` v4.36.0) has cleared its paranoid-kernel and nanoda
    stages and is mid-way through its final (default-kernel) stage. Explicit, important caveat
    UNCHANGED and still quoted directly: "GRH here means Dirichlet L-functions" (Dedekind zeta, Hecke,
    and general automorphic L-functions are NOT among the statements checked), and a passing check
    "relies on those kernels and on Mathlib's definitions being what they are intended to be" — i.e.
    this page alone still does not independently argue that Mathlib's definition faithfully represents
    the classical hypothesis (see the Lean FRO/Mathlib Initiative statement below, which explicitly
    addresses that point).
  - 2026-11-21 — https://leanprover-community.github.io/blog/posts/riemann-hypothesis/ — a joint
    statement from the Lean FRO and the Mathlib Initiative (opened directly this session; the blog's
    own index, also checked, posts only a handful of times a year, confirming this is a deliberate,
    non-routine statement, not a form post): states they have "full confidence" the proof is correct
    and CERTIFY both the statement and the proof, citing four criteria (statement correctness, the
    library compiles, the code proves that statement, the proof is valid). States the Lean statement
    "has been carefully vetted by experts in Lean and number theory" — the first authoritative,
    INSTITUTIONAL (not just one individual's) source to explicitly address the
    STATEMENT-faithfulness question Sutherland's page above says it does not itself settle. Does not
    claim the underlying mathematical IDEAS have been human-digested — only that the formal
    statement and its derivation are correct.
  - 2026-11-20 — https://terrytao.wordpress.com/2026/11/20/unforced-euler-singularity-unforced-navier-stokes-singularity-and-the-generalized-riemann-hypothesis/
    — Terence Tao's own blog post (opened directly this session) reports the claim same-day,
    describing it as "the least digested" of three results in the post (see the companion Euler/
    Navier-Stokes seed trend below) and says his preliminary read is that the proof "appears to use
    recent Langlands program and arithmetic geometry developments"; does not state a correctness
    view. In comments (2026-11-20/22, read this session) Tao cross-references an entirely
    INDEPENDENT, human, trace-formula-based GRH attempt by Alessandro Masullo (posted the same week
    via Ravi Vakil's blog) as methodologically distinct ("one being correct would not make the other
    redundant"), and later notes Alpöge's proof "appears to be holding up" under continued scrutiny
    (as of the comments read this session) while Masullo's own manuscript — per
    https://johncarlosbaez.wordpress.com/2026/11/22/masullo-on-the-riemann-hypothesis/ (opened
    directly this session) — has already drawn specific, unresolved correctness objections (a
    prime-2 limit discrepancy; a Markushevich/Schauder-basis terminology error; Chapter 13, where
    GRH is to be deduced, reported as still only placeholders) and Masullo himself says it is "not
    ready for submission," planning roughly another year of revision with Brian Conrad.
  - 2026-11-21/23 — https://mathhelm.org (listing opened directly this session) — active discussion
    threads, incl. "Maybe we have overestimated the difficulty of Riemann Hypothesis" (started by
    Xinyi Yuan, MathHelm's chair, a leading number theorist, 2026-11-20/21) and "Some effort to
    rebuilding the natural language proof of GRH" (Ruida Di, a 6-volume from-Lean reconstruction
    effort, first volumes posted 2026-11-23) — genuine, real-name research-mathematician engagement,
    distinct from the AI-generated hexagonmath commentary below.
  - 2026-11-20/21 — hexagonmath.org reader's-guide cluster (all labelled "Primarily AI-generated
    text"; opened directly this session): Manvir Jaswal's guide (https://hexagonmath.org/2611.00799,
    v1 2026-11-20) gives the primary-source links above and reports "A. Sutherland has compiled the
    archive and reports that Lean's kernel and two independent kernels accept it" plus a GitHub
    mirror and a Lean Zulip discussion thread; Sinisa Slijepcevic's outline
    (https://hexagonmath.org/2611.00812, v1 2026-11-21) restates the main theorem (L(s,χ)≠0 for
    Re s>1/2, every Dirichlet χ) and confirms the Lean-4 formal development is the primary source;
    Robin Zhang's provenance note (https://hexagonmath.org/2611.00809, v1 2026-11-21) traces
    mathematical antecedents, explicitly states a GPT model was used to infer a human-readable
    account from the Lean code, and reports no independent correctness check of its own.
  - 2026-11-20 — https://github.com/Deicyde/riemann-hypothesis — community-run "Independent
    Comparator" mirror/verification repo (opened directly this session): `main` is active
    community-maintenance work, `original` preserves the first public release retrieved from
    alpo.ge; `src/Main.lean` proves five statements incl. Mathlib's `riemannHypothesis`,
    `src/Challenge.lean` states the same five with `sorry`, and a `comparator/` setup checks that
    `Main` proves exactly the challenge statements using only the three standard axioms. 14 open
    issues, 133 pull requests at fetch time — substantial, fast community scrutiny already underway;
    the repo itself reports no verification RESULTS (points to a `verification/NOTES.md` not present
    in what was fetched).
  - (undated, accessed 2026-11-26) — https://github.com/lsernau/grh-lean — "a much shorter version"
    of the Lean GRH/RH formalization, README states explicitly "based on Levent Alpöge's, with
    Claude," produced "in collaboration with my colleagues at Anthropic, and Claude"; two editions
    (`grh/` ~300k lines, `grh-compact/` ~76k lines) covering the same five theorems, same three
    standard axioms, Apache-2.0/Anthropic-PBC-copyrighted. Opened directly this session (caught via
    Hacker News front page, 371 points). README states "passed machine checks only," no
    mathematician review yet — a re-formalization artifact, NOT an independent second method.
- notes: 2026-11-23 (daily, seed creation): MAXIMUM hype-skepticism caution, by far the largest
  claim this radar tracks — but also an unusually STRONG verification signal for an unrefereed
  claim this fresh (an independent, named, credible expert's own multi-kernel Lean check, within
  72 hours, rather than the more typical "AI lab self-disclosure, no outside check yet" pattern).
  Track the vetting outcome above all else: (1) whether any human mathematician publishes an
  understood, checked account of the argument itself (not merely a Lean-compiles report); (2)
  whether the formalized Lean statement is confirmed to actually mean RH/GRH (the one check
  explicitly NOT yet done); (3) the GitHub comparator repo's open issues/PRs for a reported error;
  (4) the rival Masullo attempt's own fate, as a methodologically-independent sanity check on how
  hard this problem remains even for a 12-year human effort. This is also, distinctly, an
  Anthropic/Claude event: unlike the official `anthropic.com/research` "riemann-zeta" disclosure
  (a weaker, already-tracked zero-density-bound result; checked this session — anthropic.com/
  research shows NO post on this claim as of 2026-11-23, confirming this is Alpöge's own personal/
  unofficial announcement, not a company disclosure). Chase daily until a human-digested account or
  a definitive bug report appears.
- notes: 2026-11-24 (daily): watch item (2) is now SUBSTANTIALLY ADDRESSED — the Lean FRO/Mathlib
  Initiative's own joint statement (evidence above) explicitly certifies statement-faithfulness, not
  just kernel acceptance, and Sutherland's page has since completed every remaining independent
  check with a PASS (Comparator, both Lean kernels, nanoda, con-leche/con-ron, a byte-identical
  sandboxed rebuild). Confidence raised seed/low → seed/medium on this two-source independent
  corroboration (an MIT expert's own multi-kernel audit PLUS an institutional Lean-ecosystem
  certification); NOT raised to `high` — watch item (1), a human-DIGESTED account of why the proof
  works, still does not exist, and that is this ledger's remaining bar for full confidence. Watch
  item (4) RESOLVED, negatively for the rival: Alessandro Masullo's own competing 940-page
  trace-formula attempt ("The Music of the Primes," posted via Ravi Vakil's blog 2026-11-20) is
  an admittedly unfinished draft (Chapter 13, where GRH itself would be deduced, is only
  placeholders); Masullo's own statement (reported via
  https://johncarlosbaez.wordpress.com/2026/11/22/masullo-on-the-riemann-hypothesis/, opened
  directly this session) says it is "in no way in a state that is fit for submission or
  dissemination," citing specific found errors (a holomorphy/limit discrepancy at the prime 2,
  flagged by Eric Naslund; a false claim about Markushevich bases) and plans ~1 year of revision
  with Brian Conrad. John Baez reports Alpöge's claim "seems to be holding up" by comparison.
  Not promoted to its own trend (a failed/withdrawn-in-current-form rival attempt, not an
  independent corroboration of GRH) — tracked here only as the methodological sanity-check this
  ledger flagged it for. Watch item (3): the comparator mirror (github.com/Deicyde/riemann-hypothesis)
  has grown to 905 stars / 25 open issues / 441 open PRs (huge, fast community engagement; no
  specific correctness bug reported in what was fetched this session — re-check the issue tracker
  directly next session, not just the repo summary). SOURCE-DISCOVERY (new domains staged in
  SOURCES.md this session, Amendment M index check done for the first): leanprover-community.github.io
  (the Lean FRO/Mathlib Initiative's own blog — Amendment M index checked, confirms this is a rare,
  deliberate statement, not routine content); Masullo's own site, github.com/mccorvie/riemann-masullo
  (crowdsourced formalization of Masullo's incomplete proof), github.com/enaslund/rh-verification
  (Naslund's independent review repo), github.com/jimjamzola/RH-Alpoge-Reconstruction — these four
  named only via the Baez post this session, Amendment M index check still owed next session.
- notes: 2026-11-25 (daily): a new, strong vetting-process signal — Terence Tao's blog posted
  "G.R.H. Polymath" (https://terrytao.wordpress.com/2026/11/24/g-r-h-polymath/, 2026-11-24, a guest post by Anurag Sahai, Will Sawin,
  and Lior Silberman, opened directly this session), proposing a Polymath-style collaboration
  explicitly to (1) coordinate worldwide verification effort, (2) produce a human-readable account
  of the proof (this ledger's still-outstanding watch item (1)), (3) clarify the related literature,
  and (4) explore the mathematics behind the Lean certificate, pointing to a public Zulip forum for
  the discussion. This is the first organized human-expert verification EFFORT (not yet an outcome)
  — logged as a note rather than a new evidence line (the trend's evidence cap already holds its
  strongest primaries); watch for the Polymath project's own findings next. last_evidence unchanged
  (2026-11-24, no new primary result).
- notes: 2026-11-26 (daily): a second Lean-formalization artifact surfaced — see new evidence item
  below (github.com/lsernau/grh-lean, caught via today's Hacker News front page, 371 points). It is
  explicitly NOT an independent re-derivation: the README states the Lean argument "is based on
  Levent Alpöge's, with Claude," produced "in collaboration with my colleagues at Anthropic, and
  Claude" — a shorter (76k–300k line, vs. the original's much larger export) re-formalization of the
  SAME proof, not a second method. README itself states it has "passed machine checks only" and no
  mathematician has reviewed it — does not advance watch item (1) (a human-digested account).
  last_evidence advances 2026-11-24 → 2026-11-25 (repo's own evident activity date).

### Unforced finite-time blowup claimed for 3D incompressible Euler and Navier–Stokes (Alpöge–Buckmaster–Coiculescu; a direct Clay Millennium Problem claim)
- stage: seed | confidence: low | first_seen: 2026-11-23 | last_evidence: 2026-11-23
- what: axis-1 LANDMARK CLAIM: Levent Alpöge, Tristan Buckmaster (NYU Courant; 2019 Clay Research
  Award for Navier-Stokes non-uniqueness work with Vlad Vicol — an established, highly credible
  researcher in exactly this area), and Matei P. Coiculescu claim, with heavy AI (Claude)
  assistance, finite-time blowup for the UNFORCED 3D incompressible Euler equations (smooth,
  periodic, divergence-free initial data; bounded velocity, unbounded vorticity at the origin) AND,
  in a companion paper, the UNFORCED 3D incompressible Navier-Stokes equations. The unforced case is
  the one that matters for the Clay Millennium Prize Problem (global existence/smoothness) — a
  materially stronger and more consequential claim than this ledger's already-tracked FORCED-case
  work (Alpöge-Buckmaster's own Sept-2026 Euler/Boussinesq-with-smooth-forcing papers on
  `study_shelf`, and OpenAI's own Sept-2026 forced-Navier-Stokes claim, tracked as evidence on the
  "OpenAI's mass mathematical-results disclosure" trend above). Each paper has an accompanying Lean
  formalization.
- evidence:
  - 2026-11-20 (v1) — https://cims.nyu.edu/~tristanb/cc.pdf — Alpöge, Buckmaster, Coiculescu,
    "Finite-Time Singularity Formation for the Three-Dimensional Euler Equations": opened and read
    directly this session (54pp PDF). Theorem 1.1 constructs an odd divergence-free smooth $u_0$ on
    $\mathbb T^3$ whose maximal classical solution is smooth on $[0,T_*)$, has
    $\int_0^{T_*}\|\nabla u\|_{L^\infty}=\int_0^{T_*}\|\mathrm{curl}\,u\|_{L^\infty}=\infty$, stays
    bounded in velocity, with vorticity magnitude blowing up at the origin while the solution extends
    smoothly away from the origin. Uses Craik-Criminale waves as multi-scale building blocks,
    explicitly contrasted in the paper's own introduction against prior FORCED constructions
    (Córdoba-Martínez-Zoroa et al.) — this paper's construction is unforced by design. Reads as
    genuine, technically serious mathematics with real citations to the standing literature
    (Elgindi; Elgindi-Ghoul-Masmoudi; Chen-Hou; Buckmaster-Vicol). Companion Lean formalization:
    github.com/mcoiculescu/EulerBlowupPublic — opened directly this session (18 stars, 2 forks):
    the repo's own claim is that the main theorem's Lean proof corresponds one-to-one with the
    paper and depends only on the three standard axioms, with ONE explicit, self-reported gap —
    Corollary 8.3 relies on a periodic Beale-Kato-Majda criterion that is NOT itself formalized
    (an acknowledged, bounded hole in the correspondence, not a reported error).
  - 2026-11-20 — https://github.com/tristanbuckmaster/navier-stokes/ — Alpöge, Buckmaster, "Finite-
    time blow-up for the Navier-Stokes equations" (79pp companion paper + Lean-4 formalization,
    ~2,270 files/600,000 lines): repo opened directly this session. States five formal statements
    including Theorem 1.1, Theorem 7.1, Corollary 7.2, and Appendix B via `sorry`-stated
    `Challenge.lean` statements proved in `Solution.lean`; notes the paper's own certificate/hash and
    an interval-arithmetic (128-bit, Arb/FLINT) check are NOT included in the repo and "will be
    released." A patch dated 2026-11-20 changing cell-layer statements had NOT been rebuilt in the
    assembled repo at fetch time — an open, acknowledged loose end.
  - 2026-11-20 — https://terrytao.wordpress.com/2026/11/20/unforced-euler-singularity-unforced-navier-stokes-singularity-and-the-generalized-riemann-hypothesis/
    — Tao's own post (opened directly this session, shared with the GRH trend above) ranks this the
    MOST digested of the three results it reports: the Euler paper read as "technically
    human-readable" with a "broadly clear" strategy following "an expected route: numerically build
    an approximate discretely self-similar solution, then use rigorous perturbation theory to get an
    exact one," though Tao says a professionally-written version "still needs more work." Comments
    raise the Clay Millennium Prize directly; the post itself does not take a position on the prize
    or on correctness.
  - 2026-11-23 — https://terrytao.wordpress.com/2026/11/23/finite-time-singularity-formation-for-the-three-dimensional-euler-equations/
    — a GUEST POST on Tao's blog by co-author Matei P. Coiculescu himself (opened directly this
    session; Tao's own editorial note: "initially written in a different file format and converted
    using AI"), giving a full self-contained exposition of the Euler paper's setup and main
    construction. Visibility/amplification by Tao, NOT independent third-party verification (same
    author, not a new reader) — distinct from Tao's own Nov 20 commentary post above.
- notes: 2026-11-23 (daily, seed creation): HEAVY caution (unrefereed, AI-heavy, days old) but
  materially more credible on its face than a typical self-disclosure, given Buckmaster's own
  track record (2019 Clay Research Award, exactly this subfield) and Tao's "technically
  human-readable" assessment of the Euler paper specifically. Distinguish carefully from this
  ledger's existing OpenAI forced-Navier-Stokes thread: this is a DIFFERENT team, a DIFFERENT
  (unforced) equation, and — if it holds — a direct resolution of the actual Clay Millennium
  Problem, not an adjacent forced variant. Track for: a human-authored exposition (as happened for
  the earlier forced-case work via Zhen Lei's reconstruction, already tracked), any reported Lean
  gap (the acknowledged un-rebuilt 11-20 patch above), and the certificate/hash release promised by
  the Navier-Stokes repo's own README.
- notes: 2026-11-24 (daily): opened the Euler companion repo (github.com/mcoiculescu/EulerBlowupPublic)
  directly this session (see evidence, updated) — one explicit, bounded formalization gap found
  (Corollary 8.3's reliance on an unformalized periodic Beale-Kato-Majda criterion), not a
  correctness bug. No human-authored exposition or referee commentary located yet for either paper
  this session (checked Kalai/Woit/Tao/Baez — none has a new post on this specifically beyond the
  11-20 Tao post already evidenced). Navier-Stokes repo's un-rebuilt patch/certificate status
  unchanged (not re-checked this session; chase next).
  - 2026-11-27 (daily): Tao's blog hosted a guest-post exposition of the Euler paper by co-author
    Coiculescu himself (see evidence, 2026-11-23) — amplifies visibility but is not independent
    verification (same author). last_evidence advances 2026-11-20 → 2026-11-23. No human-authored
    THIRD-PARTY exposition or referee commentary located yet (checked Kalai/Woit/Baez/Hossenfelder
    this session — none has a new post on this specifically). Navier-Stokes repo's un-rebuilt
    patch/certificate status still unchanged (not re-checked this session; chase next). No stage/
    confidence change (`seed`/`low`).

### Solution to the Banach-Ulam conjecture (1935) on invariant finitely-additive measures on compact metric spaces
- stage: seed | confidence: medium | first_seen: 2026-11-23 | last_evidence: 2026-06-08
- what: axis-1 DOMAIN-CADENCE LANDMARK: a full resolution of a 1935 conjecture of Stefan Banach and
  Stanisław Ulam (91 years old) — that every compact metric space admits a finitely additive
  probability measure invariant under its congruences — proved via a new geometrization of compact
  metric spaces building on ideas of Banach and Jan Mycielski; the same techniques also resolve a
  related problem of Michel Talagrand. CAPTURE-LEAK/backfill catch: the paper is 5+ months old,
  surfaced only via today's arXiv cross-list sweep.
- evidence:
  - 2026-06-08 — https://arxiv.org/abs/2606.09783 — Grzegorz Tomkowicz, "On some geometrization of
    compact metric spaces: A solution to the Banach-Ulam conjecture." Abstract + author verified via
    direct arXiv page fetch this session (caught via today's 35-category cross-list sweep, math.FA).
    Tomkowicz is co-author (with Stan Wagon) of the standard monograph "The Banach-Tarski Paradox" —
    a recognized specialist in precisely this circle of invariant-measure/paradoxical-decomposition
    problems, raising confidence this is a serious, informed attempt rather than an outsider claim.
- notes: 2026-11-23 (daily, seed creation): long-standing (91y) conjecture bearing two celebrated
  names directly tied to the widely-known Banach-Tarski paradox literature; single-author, unrefereed
  preprint — no outside engagement found yet. Watch for referee/expert commentary.

### Bloch's conjecture completed for (anti-)symplectic automorphisms of surfaces with trivial canonical bundle
- stage: seed | confidence: low | first_seen: 2026-11-23 | last_evidence: 2026-10-29
- what: axis-1 LANDMARK (algebraic geometry): proves Bloch's conjecture (1970s; action of
  correspondences/automorphisms on Chow/cycle groups, one of algebraic geometry's central standing
  conjectures) for (anti-)symplectic automorphisms of smooth projective complex K3 surfaces of
  Picard number two — which, combined with the already-known abelian-surface case and the other K3
  cases, SETTLES the full sub-program of Bloch's conjecture for (anti-)symplectic automorphisms of
  smooth projective complex surfaces with trivial canonical bundle. A defined, complete sub-case of a
  famous conjecture, not the fully general conjecture. CAPTURE-LEAK/backfill catch (paper nearly a
  month old, surfaced via today's cross-list sweep).
- evidence:
  - 2026-10-29 — https://arxiv.org/abs/2610.39368 — Zaiyuan Chen, Zhiyuan Li, "Bloch's conjecture
    for (anti-)symplectic automorphisms of K3 surfaces." Abstract + authors verified via direct
    arXiv page fetch this session (caught via today's 35-category cross-list sweep, math.AG).
- notes: 2026-11-23 (daily, seed creation): completes a well-defined sub-program of a famous,
  long-standing conjecture; unrefereed preprint, no outside engagement found yet.

### Proof of Chvátal's 1972 conjecture on intersecting families in ideals (Chang–Liu–Liu, extended by Keevash, re-proved by Ellis–Filmus–Friedgut)
- stage: seed | confidence: high | first_seen: 2026-11-24 | last_evidence: 2026-09-23
- what: axis-1 LANDMARK (combinatorics, extremal set theory): resolves Vašek Chvátal's 1972
  conjecture — for any ideal (down-closed family of sets) and any intersecting subfamily of it,
  some element $a$ exists such that the subfamily is no larger than the number of ideal-sets
  containing $a$. 54 years old, long-standing by this ledger's own bar. CAPTURE-LEAK/backfill:
  the original proof is over 2 MONTHS old, only surfaced via today's reading of a Gil Kalai blog
  post flagged "fetched, not yet read" in yesterday's report — a genuine coverage miss (digest
  blogs are swept daily, but the post itself sat unread for 4 days, and the underlying arXiv
  papers for over 2 months before that).
- evidence:
  - 2026-09-16 — https://arxiv.org/abs/2609.19123 — Fan Chang, Hong Liu, Miao Liu, "A proof of
    Chvátal's conjecture via a sharp correlation inequality": the original resolution, building on
    a 2018 correlation-inequality framework of Friedgut–Kahn–Kalai–Keller. Abstract + authors
    verified via direct arXiv API fetch this session.
  - 2026-09-20 — https://arxiv.org/abs/2609.23595 — Peter Keevash, "On Kahn's flow conjecture":
    independently extends the Chang–Liu–Liu proof to the full generality of Kahn's original
    (broader) conjecture, of which Chvátal's is a special case. Abstract + author verified via
    direct arXiv API fetch this session.
  - 2026-09-23 — https://arxiv.org/abs/2609.28404 — David Ellis, Yuval Filmus, Ehud Friedgut,
    "Chvátal's conjecture: a proof from The Book": an independent, simplified re-proof — genuine
    independent-expert engagement confirming the result, not merely restating it. Per Gil Kalai's
    blog (intake, not evidence — followed to the primaries above), this simplification "relied
    primarily on AI," an axis-5 WATCH note (the mathematical RESULT is this ledger's beat, not the
    AI assistance). Abstract + authors verified via direct arXiv API fetch this session.
- notes: 2026-11-24 (daily, seed creation): clears the landmark bar on both independent-engagement
  prongs at once — Keevash's own extension AND Ellis-Filmus-Friedgut's own independent re-proof,
  not merely commentary. Gil Kalai (a leading combinatorialist, uninvolved in either paper) calls
  it a "remarkable breakthrough" (intake, not evidence). Chvátal's own standing $10 prize for a
  solution was paid out (per Kalai's post) — a concrete, if whimsical, confirmation signal.
  Confidence set to `high` at creation (not the usual `medium` default) given the depth of
  independent engagement already on record (an extension plus an independent re-proof, not just
  one). First_seen 2026-11-24 is this ledger's capture date; last_evidence 2026-09-23 is the
  newest primary's own date (backfill precedent, as for this session's other capture-leak catches).

### Claimed proof that VP ≠ VNP over every field (Anthropic-internal Claude research model; hexagonmath, unrefereed)
- stage: seed | confidence: low | first_seen: 2026-11-24 | last_evidence: 2026-11-24
- what: axis-1/5 LANDMARK CLAIM (algebraic complexity theory): claims a resolution of Valiant's
  1979 VP-vs-VNP conjecture — the algebraic analogue of P≠NP — over EVERY field, via a
  superpolynomial ($m^{c(\log m)^{1/3}}$-gate) arithmetic-circuit lower bound for the permanent
  (reals and every field of characteristic ≠2) and, via the Hamiltonian-cycle polynomial, every
  field including characteristic 2. Explicitly does NOT resolve P≠NP itself (algebraic circuits
  are not Boolean circuits). 47 years old, and VP-vs-VNP is celebrated FAR beyond its own
  subfield as the flagship open problem of algebraic complexity theory (taught alongside P-vs-NP
  in every complexity course) — clears the landmark bar on long-standing AND celebrated. MAXIMUM
  hype-skepticism caution: wholly AI-generated (an internal Anthropic research Claude model),
  deposited directly by Anthropic (not an individual researcher) to hexagonmath (explicit
  no-peer-review venue), with a claimed Lean formalization but NO repository link given on the
  page itself to check it. AI-WATCH-LANE: method is AI-discovered, but the RESULT is this radar's
  beat. NOW A TWO-LAB CONVERGENCE: OpenAI's own internal model independently landed on the SAME
  conclusion ~24h later via a completely different witness/method (below) — still two unrefereed
  AI claims, not independent human confirmation, but a materially stronger signal than a single
  lab's claim.
- evidence:
  - 2026-11-23 — https://hexagonmath.org/2611.00954v1 — "VP $\neq$ VNP over every field," `dc:creator`
    Anthropic, 70pp, cs.CC/math.MG/math.RA/cs.LO, CC BY 4.0: opened directly this session via
    hexagonmath's own `/rss/all` feed. States the result "was discovered by an internal research
    Claude model" and "has been formalized in Lean" but gives no formalization repository link;
    page states the writeup mixes human- and AI-written text, "some parts" marked human-understood.
    Cites recent related lower-bound work (Guo arXiv:2609.29568; Kumar-Volk arXiv:2609.34462;
    Sheshadri arXiv:2606.13628/2610.40484; Raz arXiv:2604.22006) as context, none claiming the full
    conjecture.
  - 2026-11-24 — https://github.com/openai/math/blob/main/preprints/Paths-trees-and-grids-separate-Valiants-hierarchy-November-24-2026/paper.pdf
    — OpenAI, "Paths, trees and grids separate Valiant's hierarchy": an INDEPENDENT second proof
    of VP≠VNP over every field, via a different witness (the state-sum polynomial on an n×n grid,
    in VNP, requiring arithmetic circuits of size $n^{\Omega((\log n)^{1/12})}$ — a weaker exponent
    than Anthropic's claim but a self-contained construction that also separates circuits from
    algebraic branching programs (trees) and branching programs from formulas (paths) in the same
    paper. PDF opened directly via `raw.githubusercontent.com` and read (`pdftotext`) this session;
    not yet indexed in `openai/math`'s own `CONTENTS.md` at the time of this check.
- notes: 2026-11-24 (daily, seed creation): caught via hexagonmath's `/rss/all` feed, the same
  surface as yesterday's GRH/Euler-NS story; corroborated as independently significant via Hacker
  News front page same day (301 points, "VP ≠ VNP over Every Field" — intake only). Distinct from
  the Alpöge GRH/Euler-NS cluster (different team: Anthropic's own internal model, not Alpöge's
  personal project) and from the openai/math mass-disclosure trend (different company, different
  disclosure channel: hexagonmath, not github.com/openai). No Lean repository located this session
  despite the claim of formalization — chase directly next session (search hexagonmath's own
  listing and Anthropic's GitHub org for a companion repo) before any confidence change. No
  independent expert engagement found yet beyond the HN front-page attention signal.
- notes: 2026-11-25 (daily): OpenAI's own internal model independently proved the same conjecture
  (above), reported same-day by Gil Kalai ("Claude, and a few hours later ChatGPT, proved that
  VP ≠ VNP" — gilkalai.wordpress.com, 2026-11-24, opened directly this session) — the two-lab,
  two-method convergence this session treats as a corroboration SIGNAL, not a vetting OUTCOME
  (both remain unrefereed AI claims; confidence held `low`). last_evidence advances 2026-11-23 →
  2026-11-24. Watch for: whether either lab's Lean formalization becomes independently checkable,
  and any human-expert reconciliation of the two different lower-bound constructions.

### OpenAI's claimed resolution of the matrix multiplication exponent (ω = 9/4 exactly, unrefereed)
- stage: seed | confidence: low | first_seen: 2026-11-25 | last_evidence: 2026-11-24
- what: axis-1/5 LANDMARK CLAIM (algebraic complexity theory): claims the EXACT value of the
  matrix-multiplication exponent $\omega$ — one of the most famous open problems in theoretical
  computer science, open since Strassen's 1969 $O(n^{2.807})$ algorithm and the subsequent
  decades-long race toward the widely-hoped $\omega=2$. An OpenAI model first established the
  upper bound $\omega\le9/4$ over $\mathbb{C}$ (2026-10-02), independently extended to every field
  by Amanov–van den Berg–Zuiddam (arXiv:2610.30054, a CAPTURE-LEAK catch this session — sitting
  unqueued since 2026-10-21 despite being a genuine independent-expert exposition of an already-
  tracked OpenAI result). A second OpenAI preprint (2026-11-24) now claims the MATCHING LOWER
  BOUND — every formal arithmetic circuit for $n\times n$ matrix multiplication needs at least
  $n^{9/4}/2$ multiplication/division gates — which, combined with the upper bound, would pin
  $\omega=9/4$ EXACTLY and definitively REFUTE the long-hoped $\omega=2$ conjecture. 45+ years old
  and celebrated far beyond theoretical computer science (taught in every algorithms course,
  covered in general-audience science press) — clears the landmark bar on long-standing AND
  celebrated, independently of any AI-watch caution. MAXIMUM hype-skepticism caution: the
  lower-bound claim is HOURS old, wholly AI-generated, unrefereed, from OpenAI's internal model,
  with zero independent engagement yet on the lower bound specifically (only the earlier upper
  bound has independent-expert exposition). AI-WATCH-LANE: method is AI-discovered, the RESULT is
  this radar's beat.
- evidence:
  - 2026-10-02 — https://github.com/openai/math/blob/main/preprints/Matrix-Multiplication-Nine-Fourths-October-2-2026/paper.pdf
    — OpenAI's own upper-bound preprint, $\omega_{\mathbb C}\le9/4$; part of the already-tracked
    Oct-6 mass-disclosure (result-family #107 per `CONTENTS.md`, opened directly this session via
    `raw.githubusercontent.com`).
  - 2026-10-21 (v1; CAPTURE-LEAK, found this session's mechanical check) — https://arxiv.org/abs/2610.30054
    — Alimzhan Amanov, Maxim van den Berg, Jeroen Zuiddam, "Multiplying matrices via polynomials:
    exposition and barriers": an independent exposition of OpenAI's upper-bound proof extending it
    to $\omega_{\mathbb F}\le9/4$ over EVERY field (not just $\mathbb C$), plus new rectangular-
    multiplication bounds and an operational barrier result. Jeroen Zuiddam is an established
    algebraic-complexity/tensor-theory researcher — genuine independent expert engagement. Abstract
    + authors verified via direct arXiv API fetch this session.
  - 2026-11-24 — https://github.com/openai/math/blob/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf
    — OpenAI, "The matrix multiplication exponent is nine fourths": the new lower-bound claim
    ($n^{9/4}/2$ gates, formal arithmetic circuits, every field), via a reduction from a
    tensor-network-compression argument to a lower bound for testing list-distinctness. PDF opened
    directly via `raw.githubusercontent.com` and read (`pdftotext`) this session; not yet indexed in
    `openai/math`'s own `CONTENTS.md` at the time of this check.
- notes: 2026-11-25 (daily, seed creation): caught via the Hacker News front page (379 points, 191
  comments, "Matrix Multiplication is Θ(n^2.25)" — intake only; thread itself corrected its own
  title from the submitted "O(n^2.25)" to the accurate "Θ" within the first few comments, and
  clarified the upper bound was already known — the NEW content is the lower bound). No
  independent human engagement with the lower-bound claim specifically found this session (hours
  old at run time) — chase directly next session (MathOverflow, the complexity-theory blogs, any
  Zuiddam/tensor-theory-community reaction). Distinct from the VP≠VNP trend above (different
  problem, same AI-watch skepticism tier) and from the OpenAI mass-disclosure collection trend
  (this result-family's significance, once the lower bound is added, clears the landmark bar on
  its own merits — promoted out per the BATCH PRODUCERS rule, AGENTS.md).

### Resolution of Seymour's Second Neighborhood Conjecture (OpenAI claim + independent human re-proof)
- stage: seed | confidence: medium | first_seen: 2026-11-25 | last_evidence: 2026-11-24
- what: axis-1 LANDMARK (graph theory): Seymour's Second Neighborhood Conjecture (1990, 36 years
  old) — every nonempty finite oriented graph has a vertex whose second out-neighborhood is at
  least as large as its first — is a flagship, widely-known open problem in graph theory (dozens
  of partial-progress papers over three decades, e.g. Fisher's tournament case 1996, Chen-Shen-Yuster
  2003). An OpenAI model proved it in full (part of the already-tracked Oct-6 mass disclosure,
  result-family #173, Lean-formalized per the repo); a short INDEPENDENT human proof, by a team
  including leading combinatorialist Stéphan Thomassé, landed 2026-11-24 — the same
  OpenAI-claim-plus-independent-human-exposition pattern that already promoted the Propeller and
  Harary–Hill conjectures to their own trends. Clears the landmark bar: long-standing AND now
  independently engaged (re-proved, not merely expounded) by experts.
- evidence:
  - 2026-09-23 — https://github.com/openai/math/blob/main/preprints/A-proof-of-Seymours-second-neighborhood-conjecture-September-23-2026/paper.pdf
    — OpenAI's own proof (result-family #173 per `CONTENTS.md`, opened directly this session via
    `raw.githubusercontent.com`): "every nonempty finite oriented graph has a vertex with at least
    as many vertices at directed distance exactly two as at directed distance one," Lean-formalized
    (`lean/docs/173.md`).
  - 2026-11-24 — https://arxiv.org/abs/2611.32872 — Romain Bourneuf, Pierre Charbit, Samuel Coulomb,
    Stéphan Thomassé, "A short proof of Seymour's Second Neighborhood Conjecture": an independent
    alternative proof, explicitly building on OpenAI's reduction but supplying a different core
    argument. Abstract + authors verified via direct arXiv API fetch this session (math.CO
    title-triage, "conjecture" keyword hit).
- notes: 2026-11-25 (daily, seed creation): caught via today's math.CO title-triage sweep; cross-
  checked against `openai/math`'s own `CONTENTS.md` to confirm the OpenAI priority claim before
  seeding. No outside commentary (Tao/Kalai/Gowers/Baez) found yet — chase next session.

### Resolution of the Spielman-Teng conjecture on random sign matrices (He–Cheng, exact form)
- stage: seed | confidence: medium | first_seen: 2026-11-25 | last_evidence: 2026-11-24
- what: axis-1 LANDMARK (random matrix theory / theoretical computer science): the Spielman-Teng
  conjecture (2002, smoothed analysis of condition numbers) predicts
  $\mathbb P(\sigma_{\min}(A)\le\varepsilon n^{-1/2})\le\varepsilon+e^{-cn}$ for an $n\times n$
  random sign matrix $A$. Sah–Sahasrabudhe–Sawhney (arXiv:2405.20308, GAFA 2025, verified via
  direct arXiv API fetch this session) resolved it only up to a $(1+o(1))$ factor for general
  subgaussian entries. This new, purely human-authored paper proves the EXACT inequality (no
  $(1+o(1))$ fudge) specifically for random sign matrices — closing the gap and fully resolving the
  conjecture as originally stated. 24 years old; Spielman (Rolf Nevanlinna Prize 2010, for
  smoothed analysis) and this conjecture are celebrated well beyond random matrix theory, cited
  across numerical linear algebra and theoretical computer science. NOT an AI-watch item — ordinary
  human mathematics, standard unrefereed-preprint caution only.
- evidence:
  - 2024-05-30 — https://arxiv.org/abs/2405.20308 — Ashwin Sah, Julian Sahasrabudhe, Mehtaab
    Sawhney, "On the Spielman-Teng Conjecture": resolves the conjecture up to a $(1+o(1))$ factor
    for iid subgaussian entries. Abstract + authors + date verified via direct arXiv API fetch
    this session (context/background, not itself the new result).
  - 2026-11-24 — https://arxiv.org/abs/2611.32090 — Hengzhi He, Guang Cheng, "The smallest singular
    value of a random sign matrix: the Spielman-Teng conjecture": proves the exact bound for all
    $\varepsilon\ge0$, plus a first-order improvement in an intermediate regime. Abstract + authors
    verified via direct arXiv API fetch this session (math.PR title-triage, conjecture-name keyword
    hit).
- notes: 2026-11-25 (daily, seed creation): caught via today's math.PR title-triage sweep; the
  2024-2025 partial-resolution context (Sah-Sahasrabudhe-Sawhney) was found via a follow-up
  `WebSearch` this session to confirm the new paper genuinely closes an open gap rather than
  duplicating prior work — standard unrefereed-preprint caution (days old, no outside engagement
  yet). Chase next session for any community reaction.

### Alpöge–Smith's AI-assisted disproof of the Loewner and Carathéodory conjectures (capture-leak backfill)
- stage: seed | confidence: medium | first_seen: 2026-11-26 | last_evidence: 2026-11-25
- what: axis-1 LANDMARK, CAPTURE-LEAK BACKFILL (differential geometry): the Carathéodory conjecture
  (every closed, convex, sufficiently smooth surface in $\mathbb R^3$ has at least two umbilic
  points) was attributed to Carathéodory by Hamburger at a 1924 Berlin Mathematical Society
  session — 102 years old — and, with the Willmore (proved 2013, Brendle) and Lawson (proved 2014,
  Marques–Neves) conjectures, is one of the "three obdurate conjectures of differential geometry"
  (Osserman's 1980s naming, confirmed via Guilfoyle's own survey arXiv:2502.11716, opened this
  session) — the last of the three still open. Levent Alpöge (Anthropic/Harvard) announced an
  explicit smooth ($C^\infty$, non-real-analytic) counterexample via an online post on 2026-08-19,
  crediting John-Paul Smith and noting AI use — this disproves BOTH the Loewner conjecture (umbilic
  index $\le1$) and, via the index-sum-equals-2 argument on a closed convex surface, Carathéodory's
  conjecture, in that regularity class. Naoya Ando and Masaaki Umehara (established differential
  geometers) independently gave a simpler, self-contained reconstruction confirming the index-2
  umbilic construction exists. IMPORTANT CAVEAT, tracked not adjudicated: Guilfoyle–Klingenberg
  have a long-standing (since 2008) claimed PROOF that the conjecture is TRUE for
  $C^{3+\alpha}$-smooth convex surfaces (arXiv:1207.5994, still being revised as of this session's
  fetch) — the apparent conflict may resolve via the differing regularity classes ($C^\infty$-but-
  not-real-analytic vs. $C^{3+\alpha}$) rather than a direct contradiction; this ledger's own
  capture-leak (missed for ~99 days since the original announcement) found via today's Amendment J
  full-abstract pass on math.DG.
- evidence:
  - 2026-10-25 (v2 2026-11-25) — https://arxiv.org/abs/2610.34036 — Naoya Ando, Masaaki Umehara, "A
    simple construction of smooth counterexamples to the Loewner and Carathéodory conjectures" —
    PDF opened directly (`raw`/`pdftotext`) this session. States in its own introduction: "Alpöge
    recently announced smooth counterexamples to the Loewner and Carathéodory conjectures in an
    online post. In the announcement, he credits John-Paul Smith and notes the use of AI." Gives an
    independent, simpler trigonometric-function construction realizing the same index-2 isolated
    umbilic on a strictly convex closed regular surface, self-contained with regard to existence.
  - 2012-07-25 (latest version fetched 2026-11-26) — https://arxiv.org/abs/1207.5994 — Brendan
    Guilfoyle, Wilhelm Klingenberg, "An index bound for smooth umbilic points": claims the local
    index of an isolated umbilic point on a $C^{3+\alpha}$-smooth convex surface is less than two
    (i.e. the conjecture is TRUE in that regularity class) via a Riemann–Hilbert boundary-value
    co-kernel argument ("totally real blow-up"). Abstract + authors verified via direct arXiv API
    fetch this session — cited here as the standing counter-claim/vetting-status context, not as
    corroborating evidence for the disproof.
- notes: 2026-11-26 (daily, seed creation): caught via today's Amendment J full-abstract pass on
  math.DG (title-blind: "A simple construction of smooth counterexamples..." carries no
  conjecture-resolution keyword hit under the standing title-triage regex). A genuine ~99-day
  capture-leak — the original 2026-08-19 announcement was never staged or queued. The original
  announcement itself is social media (not evidence per the hard rules); cited here only via what
  the primary arXiv paper's own introduction states about it. FLAG "unrefereed preprint — claim"
  for the Alpöge/Smith side; the Guilfoyle–Klingenberg side is itself a 14-years-unpublished claim.
  Chase next session: any mathematician's public reconciliation of the two regularity classes;
  whether Guilfoyle–Klingenberg respond to the new counterexample.

### Yunhao Sun's claimed resolution of the Tate conjecture for finite fields (positive characteristic, unrefereed)
- stage: seed | confidence: low | first_seen: 2026-11-26 | last_evidence: 2026-11-26
- what: axis-1 LANDMARK CLAIM (arithmetic/algebraic geometry): claims a full proof of the Tate
  conjecture for finite fields (Tate, 1963 — 63 years old; part of the same circle of ideas as the
  Hodge/Mordell-Weil/BSD family, a core conjecture of arithmetic geometry, unquestionably celebrated
  far beyond its own subfield). The one-page note reduces the claim to two known equivalences due
  to Bruno Kahn (the Tate conjecture for a finite field $\Leftrightarrow$ a map of motivic
  complexes is an isomorphism $\Leftrightarrow$ a right-adjoint realisation functor lands in
  $DM^{\mathrm{eff}}_{\mathrm{\acute et}}$) and claims to establish the latter via the
  Dwyer–Greenlees equivalence between $\ell$-completed and $\ell$-torsion objects. MAXIMUM
  hype-skepticism caution: solo author, extremely terse (note-style) writeup, v1 submitted
  2026-11-20 and v2 posted HOURS before this session; the author's five other arXiv papers (checked
  this session) span information theory, PDE/MHD stability, single-particle-trajectory statistics,
  and photoacoustic tomography — no prior algebraic/arithmetic-geometry track record, a notable
  provenance anomaly for a claim of this depth. Zero independent engagement found this session.
- evidence:
  - 2026-11-20 (v1; v2 2026-11-26) — https://arxiv.org/abs/2611.28178 — Yunhao Sun, "The Tate
    Conjecture in Positive Characteristic" — abstract, author, and version dates verified via
    direct arXiv API fetch this session (math.NT/math.AG title-triage keyword hit, "Conjecture").
- notes: 2026-11-26 (daily, seed creation): caught via today's full arXiv title-triage sweep. This
  ledger already tracks several genuine PARTIAL Tate-conjecture results (abelian fourfolds,
  ordinary Calabi-Yau threefolds, integral Hodge/Tate via weak approximation — see
  `observation_queue`) — this claim is categorically larger (the FULL conjecture for finite fields,
  not a restricted case). FLAG "unrefereed preprint — claim," maximum caution given the
  cross-field authorship anomaly. Chase next session: any outside reaction (Tao/Kalai/
  MathOverflow/arithmetic-geometry specialists); whether a v3 retraction or correction appears.

### Tangli Ge's claimed resolution of the Zilber–Pink conjecture for algebraic tori (hexagonmath, unrefereed)
- stage: seed | confidence: low | first_seen: 2026-11-26 | last_evidence: 2026-11-26
- what: axis-1 LANDMARK CLAIM (Diophantine / unlikely-intersections geometry): claims the FULL
  Zilber–Pink conjecture for arbitrary irreducible subvarieties of algebraic tori
  $\mathbb G_m^n$ over $\mathbb C$ — every irreducible subvariety has only finitely many maximal
  atypical (optimal) components. Independently proposed by Zilber and Pink around 2005 (21 years
  old), a leading, actively-studied conjecture generalizing Manin–Mumford and Mordell–Lang,
  extensively surveyed in arithmetic/Diophantine geometry. Confirmed via `WebSearch` this session
  that the GENERAL torus case (beyond curves) remains open in the recent literature: Habegger–Pila's
  unconditional result and Maurin's theorem cover only CURVES in tori/abelian varieties, not
  arbitrary subvarieties — so this claim, if correct, closes a known-open case rather than
  reproving settled ground. MAXIMUM hype-skepticism caution: unrefereed hexagonmath submission
  (explicit no-peer-review disclaimer, same caution tier as arXiv), solo author, hours old at
  discovery, zero independent engagement found this session.
- evidence:
  - 2026-11-26 — https://hexagonmath.org/2611.01093v1 — Tangli Ge, "The Zilber–Pink conjecture for
    algebraic tori" — opened directly via hexagonmath's `/rss/all` feed this session; `dc:creator`
    Tangli Ge, posted 2026-11-26 01:15 UTC.
- notes: 2026-11-26 (daily, seed creation): caught via today's hexagonmath `/rss/all` sweep,
  followed by a `WebSearch` to confirm the torus case's open status before seeding (per the hard
  rule against guessing significance). FLAG "unrefereed preprint — claim." Chase next session for
  any outside reaction from the Diophantine-geometry community (Habegger, Pila, Masser, Zannier,
  Scanlon are the field's natural reviewers).

### OpenAI's claimed disproof of the polynomial Hirsch conjecture
- stage: seed | confidence: low | first_seen: 2026-11-26 | last_evidence: 2026-11-24
- what: axis-1 LANDMARK CLAIM (combinatorial optimization / polytope theory): Hirsch (1957, 69 years
  old) conjectured a $d$-dimensional polyhedron with $n$ facets has graph diameter at most $n-d$;
  Santos (2010/2012, published in the Annals of Mathematics) disproved that exact bound, but left
  open whether SOME polynomial in $n$ still bounds the diameter — the "polynomial Hirsch
  conjecture," independently confirmed this session (via a July-2026 arXiv survey, Black–Xue,
  "Any Proof of Polynomial Hirsch Must be Completely Incoherent") to remain "among the most
  notorious and well studied problems in polyhedral theory," closely tied to simplex-method
  complexity. This new OpenAI preprint constructs bounded simple rational polytopes with $n$ facets
  whose graph diameter grows faster than every fixed power of $n$ (dimension growing only
  $n^{o(1)}$) — a full disproof. Part of the already-tracked OpenAI mass-disclosure collection;
  PROMOTED OUT to its own seed per the BATCH PRODUCERS rule (same pattern as the already-promoted
  matrix-multiplication-exponent and Seymour's-SNC trends), since this result clears the landmark
  bar (long-standing AND celebrated) on its own merits. MAXIMUM hype-skepticism caution: 2 days old,
  wholly AI-generated, unrefereed, zero independent engagement found this session beyond the HN
  front-page attention signal.
- evidence:
  - 2026-11-24 — https://github.com/openai/math/blob/main/preprints/Superpolynomial-graph-diameter-of-simple-polytopes-November-24-2026/paper.pdf
    — OpenAI, "Superpolynomial graph diameter of simple polytopes": Theorem 1.1, for every
    $s(n)=n^{o(1)}$ a family of bounded simple rational polytopes with $n$ facets, dimension
    $n^{o(1)}$, and $s$-move diameter $n^{\omega(1)}$; taking $s(n)=1$ disproves the polynomial
    Hirsch conjecture. PDF opened directly via `raw.githubusercontent.com` and read (`pdftotext`)
    this session.
- notes: 2026-11-26 (daily, seed creation): caught via Hacker News front page ("The polynomial
  Hirsch conjecture is false," 144 points). Same openai/math disclosure channel and Nov-24 release
  cluster as the already-tracked matrix-multiplication-exponent and VP≠VNP trends. Gil Kalai (a
  leading voice on Hirsch-conjecture-adjacent convexity/combinatorics) has posted nothing on this
  per his feed checked today — chase his blog specifically next session, along with any
  polytope-theory specialist reaction.

### Google Cogentic's unconditional classical algorithms for integer factorization and discrete logarithm
- stage: seed | confidence: low | first_seen: 2026-11-26 | last_evidence: 2026-11-25
- what: axis-1/5 LANDMARK CLAIM (algorithmic/computational number theory): a FOURTH AI-lab
  math-disclosure channel (after OpenAI, Anthropic, Epoch AI) — Google Research/DeepMind's
  "Cogentic" multi-agent theorem-proving orchestrator (arXiv:2609.40324, 2026-09-30) — released a
  same-day (2026-11-25) six-paper batch including two companion unconditional classical algorithms:
  (a) integer factorization in time $L_N[1/3,O(1)]$, closing the 34-year-old (1992) gap between
  Lenstra–Pomerance's rigorous $L_N[1/2,1]$ bound and the heuristic General Number Field Sieve's
  conjectural $1/3$ exponent — now proved WITHOUT unproven number-theoretic hypotheses (every prime
  factor certified via AKS primality testing); (b) discrete logarithms in finite fields of fixed
  characteristic in sub-quasi-polynomial time, improving unconditionally on Kleinjung–Wesolowski
  (2022)/Lido (2026)'s quasi-polynomial algorithms. Integer factorization is among the most famous
  problems in computational number theory (the basis of RSA); both results, if correct, close
  long-standing, celebrated gaps between heuristic and unconditional bounds. MAXIMUM
  hype-skepticism caution: brand-new disclosure channel (first sighting this ledger), wholly
  AI-generated (a multi-agent system, not a named human author), unrefereed, zero independent
  engagement found this session. SOURCE-DISCOVERY: staging
  `github.com/google-research/google-research` (the `cogentic_research_papers` directory) as a new
  AI-watch-lane candidate — see `SOURCES.md`.
- evidence:
  - 2026-11-25 — https://github.com/google-research/google-research/blob/master/cogentic_research_papers/integer_factorization/paper.pdf
    — Cogentic, "Unconditional Integer Factorization in Time $L_N[1/3,O(1)]$": Las Vegas algorithm,
    worst-case expected time $L_N[1/3,105]$, workspace $L_N[1/3,40]$, explicit finite constants,
    "relies on no unproven hypotheses." PDF opened directly (`raw.githubusercontent.com`/`pdftotext`)
    this session.
  - 2026-11-25 — https://github.com/google-research/google-research/blob/master/cogentic_research_papers/discrete_logarithm/paper.pdf
    — Cogentic, "Discrete Logarithms in Finite Fields of Fixed Characteristic in Sub-Quasi-Polynomial
    Time": unconditional Las Vegas algorithm, worst-case expected time $(pn)^{o(\log n)}$,
    improving on Kleinjung–Wesolowski (2022) and Lido (2026)'s quasi-polynomial bounds. PDF opened
    directly this session.
  - 2026-11-25 — https://github.com/google-research/google-research/blob/master/cogentic_research_papers/deterministic_factoring_l34/paper.pdf
    — Cogentic, "Unconditional Deterministic Subexponential Integer Factoring and Quadratic
    Nonresidue Construction": a DETERMINISTIC companion to the Las Vegas factoring result above —
    every composite $N\ge4$ factored deterministically in worst-case bit complexity
    $O(\exp(3(\ln N)^{3/4}))=L_N[3/4,o(1)]$ (zero randomness, zero unproven hypotheses), plus a
    deterministic quadratic-nonresidue construction surpassing the Burgess (1957/63)/Vinogradov
    (1927) exponential barrier. CAPTURE-LEAK fix: part of the same 2026-11-25 six-paper batch as
    this trend's other two evidence lines but missed when the trend was created yesterday (only 2
    of the 6 papers were individually triaged per the BATCH PRODUCERS 5-item cap) — found this
    session by re-opening the batch's own README. PDF opened directly via `raw.githubusercontent.com`
    + `pdftotext` this session.
- notes: 2026-11-26 (daily, seed creation): caught via Hacker News front page ("Google releases
  Cogentic papers on integer factorization, discrete logs and more," 473 points). Four further
  companion results in the same Nov-25 batch (a log-rank-conjecture exponent improvement, edge
  reconstruction, bimatrix Nash, plus two Nov-18/23 items on prophet inequalities/fictitious play)
  queued separately below the landmark bar — see `observation_queue`; triaged per the BATCH
  PRODUCERS rule (5-item cap on individual triage, most significant first — these two factoring/
  dlog results chosen as by far the most significant). Chase next session: any independent
  cryptography/computational-number-theory community reaction to the factoring claim specifically
  (the most consequential of the two if correct — it would be new, citable progress on a question
  of direct relevance to RSA's security foundations).
  - 2026-11-27 (daily, capture-leak fix): re-opened the Nov-25 batch's own README and found a
    THIRD on-theme paper missed yesterday — the deterministic factoring/quadratic-nonresidue
    companion (see evidence above), directly on this trend's own landmark sub-theme rather than a
    separate below-bar item. Appended as evidence (cap 3/10, no rotation needed). last_evidence
    unchanged (2026-11-25 — same batch date). No stage/confidence change (`seed`/`low` — still zero
    independent engagement found). The other four companion results (log-rank, edge reconstruction,
    bimatrix Nash, prophet-inequalities/fictitious-play) remain correctly queued below-bar.

## observation_queue

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).
- 2026-11-26 — hexagonmath.org, Dave Goel, "Turán's Hermite strip problem (1967) is resolved: the
  sharp half-width is 0.90366…" — https://hexagonmath.org/2611.01106v1 — resolves a 59-year-old
  open problem from Hayman's 1967 research-problems collection (Turán asked whether a single strip
  |Im z|≤c contains a zero of every polynomial 1+2z+aH_n(z)+bH_m(z) for Hermite polynomials H_n,
  H_m): finds the sharp half-width for the FULL two-parameter family, extending Makai-Turán's
  existence result and Schmeisser's 1971 trinomial-case value (0.52892…). Long-standing but a
  solo, unrefereed hexagonmath submission with zero independent engagement found this
  session — below the landmark bar (not yet celebrated/independently engaged) despite the age.
  Opened directly this session.
- 2026-11-26 — hexagonmath.org, Ivan Besevic, "Nested-Ovals Fewnomial Systems: A Universal
  Two-Parameter Disproof of Kouchnirenko's Conjecture for All $(t_1,t_2)\ge(3,3)$" —
  https://hexagonmath.org/2611.01126v1 — a 51-year-old conjecture (Kouchnirenko, 1975, on the
  maximum number of positive real solutions of sparse polynomial systems) disproven via an
  explicit nested-ovals curve-family construction, for the whole $(t_1,t_2)\ge(3,3)$ range at
  once. Solo, unrefereed hexagonmath submission, zero independent engagement — below the landmark
  bar. CONCENTRATION NOTE: same submitter's 2nd same-day item (see next entry). Opened directly
  this session.
- 2026-11-26 — hexagonmath.org, Ivan Besevic, "Breaking the Linear-Ansatz Barrier for the
  Sum-of-Square-Roots Problem" — https://hexagonmath.org/2611.01119v1 — a bound improvement
  ($r(n,k)=O(n^{-2k+1/2})$ for all $k\ge2$, with sharp $k=2$ separation bounds and a Lean 4
  formalization) on the sum-of-square-roots problem, a well-known open problem in computational
  geometry/complexity — a partial result, not a resolution. CONCENTRATION: this submitter's 2nd
  tracked item today (see prior entry, the Kouchnirenko disproof). Opened directly this session.
- 2026-11-26 — hexagonmath.org, Bernhard Boehmler, "A Proof of Linckelmann's Conjecture on Outer
  Derivations of Blocks" — https://hexagonmath.org/2611.01094v1 — a claimed proof of a named
  conjecture in modular representation theory of finite groups. Solo, unrefereed hexagonmath
  submission, zero independent engagement, age/provenance not independently confirmed this
  session — below the landmark bar. Opened directly this session.
- 2026-11-26 — hexagonmath.org, Greta Panova, "Counting contingency tables, Kostka numbers, and
  Littlewood-Richardson coefficients with unary inputs is #P-complete" —
  https://hexagonmath.org/2611.01117v1 — a complexity-hardness classification in algebraic
  combinatorics, from an established researcher in the field (Panova), but a hexagonmath
  self-posting with no independent engagement found this session and not itself the resolution of
  a long-standing NAMED conjecture — below the landmark bar, flagged for a closer read next
  session given the author's standing. Title/author/abstract opened directly this session.
- 2026-11-25 — Cogentic (Google Research/DeepMind), "Breaking the Square-Root Barrier for the
  Log-Rank Conjecture" — https://github.com/google-research/google-research/blob/master/cogentic_research_papers/logrank_conjecture/paper.pdf
  — PARTIAL progress toward the Log-Rank Conjecture of Lovász–Saks (1988, 38 years old, a leading
  open problem in communication complexity): improves the deterministic-communication-complexity
  exponent from Lovett's (2016) $O(\sqrt r\log r)$ and Sudakov–Tomon's (2023) $O(\sqrt r)$ to
  $O(r^{1/2-\varepsilon})$, $\varepsilon=5\times10^{-6}$ — a genuine but small polynomial
  improvement, not a resolution (the conjecture itself predicts $\mathrm{polylog}(r)$). Same
  Nov-25 Cogentic batch as the new factoring/discrete-log seed trend above. PDF opened directly
  this session.
- 2026-11-25 — Cogentic, four further same-batch items, each below the landmark bar, triaged by
  title/abstract only (BATCH PRODUCERS cap): "An Exact Polynomial-Time Algorithm for 1/5-Approximate
  Nash Equilibria in Bimatrix Games"; "Unconditional Edge Reconstruction of Simple Graphs of Linear
  Density"; "Nearly Tight $O(\log\log\log m)$ Prophet Inequalities for Subadditive Combinatorial
  Auctions" (2026-11-23); "Polynomial Dimension Dependence for Fictitious Play Convergence"
  (2026-11-23) — https://github.com/google-research/google-research/tree/master/cogentic_research_papers
  — game-theory/algorithms results, axis-1-adjacent but narrow-specialist, none a named
  long-standing conjecture resolution.
- 2026-11-26 — Gravitational collapse to extremal Schwarzschild-de Sitter black holes with
  $\Lambda>0$: counterexamples to the third law of black-hole thermodynamics without charge —
  https://arxiv.org/abs/2611.34542 — constructs regular Einstein-scalar-field Cauchy data forming
  an EXACTLY extremal black hole (or white hole/Nariai solution) in finite time, for any scalar
  mass including zero — a notable mathematical-GR result on black-hole third-law violations.
  Axis 2 (gr-qc/hep-th/math-ph cross-listed). Abstract verified via today's arXiv RSS title-triage
  sweep; chase next session for any independent commentary (this is a specialist but genuinely
  new result, not yet assessed against the landmark bar).
- 2026-11-26 — Non-Perturbative Resolution of Luttinger's Theorem Violations in Strongly Correlated
  Systems — https://arxiv.org/abs/2611.07933 — resolves a known paradox (apparent violations of
  Luttinger's theorem, which relates electron number to the Luttinger count, in strongly correlated
  systems) by showing the mismatch is a pure zero-frequency boundary term the conventional proof
  implicitly drops. Axis 3 (cond-mat.str-el), physics-axis item (flagging per the W46
  physics-crowding-out concern). Abstract verified via today's arXiv RSS title-triage sweep.
- 2026-11-26 — The Transverse Finiteness Conjecture for pseudo-Anosov flows via universal circles
  — https://arxiv.org/abs/2611.33320 — proves Mosher's 1996 conjecture (30 years old): every taut,
  finite-depth foliation of an atoroidal 3-manifold is almost transverse to only finitely many
  pseudo-Anosov flows up to orbit equivalence, plus a companion rigidity result. Narrow specialist
  (3-manifold topology/foliation theory) — no outside-fame signal found this session, held below
  the landmark bar pending any wider engagement. Axis 1. Abstract verified via today's arXiv RSS
  title-triage sweep.
- 2026-11-26 — A proof of Nakamura's conjecture — https://arxiv.org/abs/2611.19558 — proves
  Nakamura's conjecture on the relation between the 2D Toda model and solutions of the Ernst
  equation (general-relativistic integrable systems), building on the authors' own prior Pfaffian-
  solutions work. Narrow specialist (axis 1/2 interface). Abstract verified via today's arXiv RSS
  title-triage sweep.
- 2026-11-26 — The Kalton–Peck space disproves Rubio de Francia's conjecture — https://arxiv.org/abs/2611.33556
  — disproves Rubio de Francia's conjecture on intermediate UMD Banach spaces by showing the
  classical complex Kalton–Peck space is not isomorphic to any complex interpolation space between
  a UMD space and a Hilbert space. Narrow specialist (functional analysis/interpolation theory).
  Axis 1. Abstract verified via today's arXiv RSS title-triage sweep.
- 2026-11-26 — A proof of the Nevo-Peeva conjecture: Exact regularity and linear powers of gap-free
  edge ideals — https://arxiv.org/abs/2611.33501 — settles both open problems of Nevo and Peeva on
  the regularity of powers of edge ideals for gap-free graphs. Narrow specialist (commutative
  algebra). Axis 1. Abstract verified via today's arXiv RSS title-triage sweep.
- 2026-11-26 — Bolognesi's Conjecture for Nonnegative-Charge Iterated Magnetic Bags —
  https://arxiv.org/abs/2611.34557 — proves Bolognesi's magnetic-bag conjecture (Bogomolny
  monopoles) for iterated magnetic bags with nonnegative charge density. Narrow specialist
  (math-ph/gauge theory). Axis 2. Abstract verified via today's arXiv RSS title-triage sweep.
- 2026-11-23 — Wei-Chun Chen, Wei-Ting Kao, Chun-Kai Lien, "Generic Strong Regularity and the
  Branson-Gover Conjecture" — https://arxiv.org/abs/2611.30498 — proves a generic-open-dense-set
  (not fully general) case of the Branson-Gover-Canzani conjecture on conformal-GJMS-operator
  kernels — PARTIAL, narrow specialist (conformal differential geometry). Axis 1. Abstract +
  authors verified via direct arXiv API fetch this session (math.DG title-triage).
- 2026-11-23 — Udhav Fowdar, "On the quaternionic Goldberg conjecture" — https://arxiv.org/abs/2611.30608
  — proves a quaternionic-Kähler analogue of the Goldberg conjecture for compact 8-manifolds with
  an Sp(2)Sp(1)-structure. Narrow specialist (quaternionic Kähler geometry). Axis 1. Abstract +
  author verified via direct arXiv API fetch this session (math.DG title-triage).
- 2026-11-24 — Nina Lebedeva, "The Boundary Conjecture for Smoothable Alexandrov Spaces" —
  https://arxiv.org/abs/2611.30860 — full proof of a boundary-curvature result for noncollapsed
  limits of Riemannian manifolds; narrow specialist subfield (Alexandrov geometry), no fame/
  engagement signal found this session. Axis 1. Abstract + author verified via direct arXiv API
  fetch this session (math.DG/math.MG title-triage).
- 2026-11-23 — Nero Budur, Quan Shi, Huaiqing Zuo, "The monodromy conjecture for remarkable poles"
  — https://arxiv.org/abs/2611.30999 — proves the strong monodromy conjecture (Igusa's, 1988, a
  long-standing singularity-theory/arithmetic-geometry conjecture) for the special subclass of
  "remarkable" poles — PARTIAL (a subcase, not the general conjecture). Axis 1. Abstract + authors
  verified via direct arXiv API fetch this session (math.AG title-triage).
- 2026-11-23 — Alexander Pigazzini, "The Kao-Lai-Osting Conjecture for the Second Laplace
  Eigenvalue on Riemannian Two-Tori" — https://arxiv.org/abs/2611.31024 — proves the $k=2$ case of
  a recent (not long-standing) spectral-geometry conjecture. Axis 1, narrow specialist. Abstract +
  author verified via direct arXiv API fetch this session (math.DG title-triage).
- 2026-11-23 — Andrea Agazzi, David F. Anderson, Daniele Cappelletti, Lucie Laurence, Jonathan C.
  Mattingly, "A proof of the chemical recurrence conjecture in two dimensions" —
  https://arxiv.org/abs/2611.31221 — proves the long-standing (within its own subfield) chemical
  recurrence conjecture for weakly-reversible reaction networks, restricted to 2 dimensions —
  PARTIAL. Axis 1 (math.PR), narrow specialist (chemical reaction network theory). Abstract +
  authors verified via direct arXiv API fetch this session.
- 2026-11-23 — Lucas Fagan, Jon McCammond, "Fake surfaces for some potential Andrews-Curtis
  counterexamples" — https://arxiv.org/abs/2611.31420 — explores (does not resolve) the famous,
  long-standing (1965) Andrews-Curtis conjecture: constructs fake-surface combinatorics for the
  Akbulut-Kirby family of potential counterexamples. Below bar (exploratory, not a resolution) but
  flagged given the conjecture's fame — watch for whether this enables an actual counterexample or
  disproof. Axis 1. Abstract + authors verified via direct arXiv API fetch this session
  (math.GT/math.GR title-triage).
- 2026-11-23 — Durvudkhan Suragan, "A Proof of the Ovals Conjecture" — https://arxiv.org/abs/2611.31665
  — proves the Benguria-Loss ovals spectral-geometry conjecture (lowest eigenvalue of a periodic
  Schrödinger operator on a closed curve). Narrow specialist subfield, age/fame not established
  this session. Axis 1. Abstract + author verified via direct arXiv API fetch this session.
- 2026-11-24 — Guang Li, Wenqian Zhang, "A proof of the toughness conjecture for Kneser graphs" —
  https://arxiv.org/abs/2611.32376 — resolves Park et al.'s own recent conjecture on Kneser-graph
  toughness. Axis 1, narrow specialist. Abstract + authors verified via direct arXiv API fetch
  this session (math.CO title-triage).
- 2026-11-24 — Yang Cao, Zhiyu Tian, "Integral Hodge/Tate conjecture of quotients via weak
  approximation" — https://arxiv.org/abs/2611.32494 — PARTIAL progress on the integral Hodge/Tate
  conjectures for quotient varieties, related to (but a distinct technical case from) the
  already-queued "Tate conjecture for abelian fourfolds" item (2611.30237, queued 2026-11-23).
  Axis 1. Abstract + authors verified via direct arXiv API fetch this session (math.AG
  title-triage).
- 2026-11-24 — Aryeh Lev Zabokritskiy, "A Proof of the Balister-Győri-Schelp Conjecture on Perfect
  Matchings with Prescribed Differences" — https://arxiv.org/abs/2611.32557 — full proof of a
  recent (not long-standing) combinatorics conjecture named after living authors. Axis 1, narrow
  specialist. Abstract + author verified via direct arXiv API fetch this session.
- 2026-11-24 — Qi Guo, Marco Magliaro, Luciano Mari, Andreas Savas-Halilaj, "Equivariant harmonic
  maps from $\mathbb S^3$ to $\mathbb S^2$: on a counterexample to a conjecture of J. Eells" —
  https://arxiv.org/abs/2611.32603 — a RIGOROUS human construction "building on a remarkable
  AI-generated counterexample" to Eells' conjecture (Hopf invariant 0 or ±6), narrowing an existing
  disproof. Related to the already-catalogued (below-bar, `logs/results_catalog.md`) Hirst-Platt-
  Sá Earp-Stein disproof of Eells'/Ding's conjectures (2611.17697) — UNCLEAR this session whether
  this cites the SAME AI-generated example or a different one (not resolved; chase next session by
  opening this paper's reference list). If it is independent expert engagement with the already-
  catalogued item, that item should be reconsidered for promotion back to a seed at the next
  weekly per AGENTS.md's "a catalogued result is promoted when it later clears the bar" rule —
  flagged here rather than promoted outright given the citation ambiguity. Axis 1. Abstract +
  authors verified via direct arXiv API fetch this session (math.DG/math.AP Amendment J
  full-abstract pass).
- 2026-11-24 — Guantao Chen, Songling Shan, "An Asymptotically Sharp Form of the Overfull
  Conjecture" — https://arxiv.org/abs/2611.32763 — an asymptotic (not full) resolution of the
  Chetwynd-Hilton 1986 Overfull Conjecture, a well-known problem in chromatic-index/graph-coloring
  theory (40 years old, would imply several other longstanding conjectures if fully resolved) —
  PARTIAL. Axis 1. Abstract + authors verified via direct arXiv API fetch this session (math.CO
  title-triage).
- 2026-11-24 — Ziyu Neroli, "On the Fujii conjectures" — https://arxiv.org/abs/2611.32862 —
  disproves Fujii's first conjecture and proves his second (1988, analytic number theory,
  prime-counting weights), CONDITIONAL on RH for a nonprincipal character mod 4. Axis 1. Abstract +
  author verified via direct arXiv API fetch this session (math.NT title-triage).
- 2026-11-23 — Simon Foucart, "Solutions to Three Spline-Related Conjectures" —
  https://arxiv.org/abs/2611.31314 — AI-assisted paper settling (partially) three named spline-
  theory conjectures (Scherer-Shadrin, disproved; the author's own Lebesgue-function conjectures,
  proved; Schumaker, partially solved). Narrow specialist subfield, axis 1/5 watch. Abstract +
  author verified via direct arXiv API fetch this session (math.CA title-triage).
- 2026-11-24 — Guo-Hong Du, Tian-Nuo Li, Jing-Fei Zhang, Xin Zhang, "Resolving the Hubble Tension
  at $0.1\sigma$ with Early Dark Energy: Key Role of the Highest-redshift Galaxies from JWST
  Observations" — https://arxiv.org/abs/2611.32552 — a theoretical cosmology paper proposing an
  axion-EDE model reconciling $H_0$ measurements with JWST high-redshift galaxy data; one of many
  competing proposed resolutions of the Hubble tension (a major open problem in cosmology), not a
  first-of-kind detection. Axis 3. Abstract + authors verified via direct arXiv API fetch this
  session (astro-ph.CO Amendment J full-abstract pass context).
- 2026-11-23 — Andrew Strominger, Hongji Wei, "Every 3D Conformal Field Theory Has an
  $\mathcal L_\Lambda w_{1+\infty}$ Symmetry" — Phys. Rev. Lett. 137, 221601 —
  http://link.aps.org/doi/10.1103/64ht-cx15 — a universal structural result in Strominger's
  celestial-holography program, extending a recently-discovered deformed $w_{1+\infty}$ soft
  symmetry algebra from $\mathrm{AdS}_4$ gravity to every 3D CFT (incl. those dual to quantum
  gravity on $\mathrm{AdS}_4$). Programmatic progress, not a conjecture resolution or detection —
  below the trend bar. Axis 2. RSS item + abstract opened directly via `curl` this session
  (PRL DAILY-tier sweep).
- 2026-09-28 (CAPTURE-LEAK catch, found this session's mechanical id-sweep) — Freddie Illingworth,
  Raphael Steiner, "Disproof of the dominating Hadwiger conjecture" —
  https://arxiv.org/abs/2609.35361 — disproves the "dominating" strengthening of Hadwiger's 1943
  conjecture (every vertex in $T_j$, not just some, must neighbor $T_i$). This id was named in the
  "Linear Hadwiger Conjecture" trend's own `what` field, asserting it was "already queued" — it was
  not; queuing it now closes that leak. Below the seed bar on its own (a disproof of a strengthened
  variant, not the main conjecture); Steiner's co-authorship links it to the already-tracked trend
  as context, not evidence for it. Abstract + authors verified via direct arXiv API fetch this
  session.
- 2026-11-23 — Matt Broe, Ruofan Jiang, "The Tate conjecture for abelian fourfolds" —
  https://arxiv.org/abs/2611.30237 — proves the Tate conjecture for non-CM, non-ordinary abelian
  fourfolds over positive-characteristic function fields (combined with the authors' own prior
  work, this establishes it for abelian fourfolds over finitely generated fields); also proves
  Zarhin's minuscule-weights conjecture up to dimension 4 along the way. PARTIAL (a restricted
  case of the still-open general Tate conjecture, same class as the already-tracked "integral
  geometric Tate conjecture" queue item below) — below the seed bar, not a full resolution.
  Abstract + authors verified via direct arXiv API fetch this session (math.AG/math.NT
  title-triage, "conjecture" keyword hit).
- 2026-11-23 — Guowei Dai, Yingxin Sun, Yong Zhang, "Rayleigh's conjecture for clamped plates in
  dimensions four and five" — https://arxiv.org/abs/2611.29957 — proves Lord Rayleigh's 1877
  conjecture (the disk minimizes the fundamental frequency of a clamped plate of prescribed area)
  in dimensions 4 and 5 specifically. Long-standing (149 years) but a PARTIAL resolution (two
  dimensions, not the general case) — below the seed bar; persists here until the general case
  closes or independent engagement appears. Abstract + authors verified via direct arXiv API
  fetch this session (math.AP title-triage, "conjecture" keyword hit).
- 2026-11-19 (v1; arXiv mirror found 2026-11-23) — RJ Acuña, "The Strong AJ Conjecture for
  Hyperbolic Prime Knots is False" — https://arxiv.org/abs/2611.26905 — an arXiv posting of the
  SAME single-knot ($8_{11}$) counterexample to the Strong AJ conjecture already queued 2026-11-20
  as a hexagonmath item (2611.00686); AI-assisted, Lean-partial ("parts of it have been formalized
  in Lean"); the new paper notes Li-Li-Sun have since reported further counterexamples among
  non-hyperbolic prime knots. Abstract verified via direct arXiv page fetch this session — update to
  the existing queue item, not a new independent result.
- 2026-11-20 (v1) — Chalmers, "The Bapat-Sunder eigenvalue conjecture fails over the reals" —
  https://arxiv.org/abs/2611.23269 — full negative resolution (both complex and real fields now) of
  a 1986 conjecture of Bapat and Sunder on permanents of PSD matrices, with a quantum-optics
  application (a 36-mode interferometer violation). Axis 1/4-adjacent. 40 years old but a
  specialist-subfield (matrix permanent theory) conjecture; fame beyond that subfield not
  established this session — below the landmark bar pending wider engagement. Abstract + author
  verified via direct arXiv page fetch this session.
- 2026-11-20 (v1) — Zhang, Zhou, "On the Delandtsheer Conjecture" — https://arxiv.org/abs/2611.27275
  — full proof of a 1988 finite-geometry conjecture (a line-primitive automorphism group of a finite
  linear space is point-primitive). Axis 1. Long-standing but a specialist subfield; no outside
  engagement found this session. Abstract + authors verified via direct arXiv page fetch.
- 2026-11-20 (v1) — Deng, "A Proof of a Pólya–Szegő Conjecture: A PDE Approach to Capacity
  Inequalities" — https://arxiv.org/abs/2611.26633 — proves a planar capacity-ratio inequality
  (and its adjacent-dimension extension) attributed to Pólya and Szegő (their 1951 monograph on
  isoperimetric inequalities). Axis 1. Famous names, unclear whether this specific inequality is
  itself widely known beyond potential theory; single-author, unrefereed — queued pending wider
  engagement rather than seeded outright. Abstract + author verified via direct arXiv page fetch.
- 2026-11-19 (v1) — Chen, "Yau's first eigenvalue conjecture for embedded minimal hypersurfaces with
  constant scalar curvature" — https://arxiv.org/abs/2611.26893 — proves the constant-scalar-
  curvature special case of Yau's 1982 conjecture (first Laplace eigenvalue of an embedded minimal
  hypersurface of $S^n$ equals $n$). Axis 1. Yau's conjecture is famous; this is a PARTIAL (CSC-only)
  case, not the general conjecture — below the full-resolution landmark bar. Abstract + author
  verified via direct arXiv page fetch this session.
- 2026-11-20 (v1) — Barthel, Mann, Ray, Schlank, Senger, Weinstein, Zhou, "On the chromatic
  splitting conjecture in coheight 1" — https://arxiv.org/abs/2611.27879 — confirms predictions of
  Hopkins' chromatic splitting conjecture (stable homotopy theory, 1990s) in the $h=2$, $p$ odd case
  (an isomorphism) and a general retract theorem; a new "two-tower isomorphism" en route. A strong
  partial result by a notable multi-author team, not a full resolution. Abstract + authors verified
  via direct arXiv page fetch this session.
- 2026-11-20 (v1) — Inagaki, Pramatarova, "Counterexamples to a conjecture of Gao and Gu on weighted
  Catalan numbers" — https://arxiv.org/abs/2611.26953 — infinitely many counterexamples to a modern
  (not long-standing) conjecture; below the domain-cadence bar on age alone. Abstract + authors
  verified via direct arXiv page fetch this session.
- 2026-11-20 (v1) — Colmez, Nizioł, Shao, "Period maps and the $C_{\rm st}$ conjecture" —
  https://arxiv.org/abs/2611.27054 — constructs a family of elliptic curves violating the $C_{\rm
  st}$ conjecture in degree 1 over a Stein base, showing the conjecture does not extend beyond
  proper/Stein total spaces; technical arithmetic/p-adic geometry, strong authors (Colmez is a
  leading p-adic Hodge theorist). Abstract + authors verified via direct arXiv page fetch this
  session.
- 2026-11-20 (v1) — Varagnolo, Vasserot, "The non symmetric Hikita conjecture" —
  https://arxiv.org/abs/2611.27331 — partial construction of comparison maps for the Hikita
  conjecture in quiver gauge theories (non-symmetric case); isomorphism only under a dimension bound.
  Abstract + authors verified via direct arXiv page fetch this session.
- 2026-11-20 (v1) — Ai, Shi, "The categorical graph minor conjecture and matching complexes" —
  https://arxiv.org/abs/2611.27657 — disproves the categorical graph minor conjecture of Miyata-
  Proudfoot-Ramos (a modern, representation-stability-era conjecture) via a counterexample module,
  while proving it for modules depending on minor morphisms through induced edge-set injections
  (incl. matching complexes). Below the long-standing-age bar. Abstract + authors verified via
  direct arXiv page fetch this session.
- 2026-11-18 (v1) — Sherman, "Semi-exact functors and the conjecture of Coulembier and Flake" —
  https://arxiv.org/abs/2611.24471 — proves a weak form of a modern tensor-category conjecture
  (support theory vs. the Balmer spectrum). Below the long-standing-age bar. Abstract + author
  verified via direct arXiv page fetch this session.
- 2026-11-20 (v1) — He, "Calabi-Yau at 50: mathematical discovery in the age of AI" —
  https://arxiv.org/abs/2611.26974 — Yang-Hui He's historical/reflective survey on Calabi-Yau
  manifolds, the math-physics interface, and the growth of AI-assisted mathematics through 2026,
  written around the 50th anniversary of Yau's proof of the Calabi conjecture. Axis 5 WATCH (notes
  the AI-assisted-math wave; does not itself claim a new result). Abstract + author verified via
  direct arXiv page fetch this session.
- 2026-11-20 (v1) — Guu, "Moonshine Conjecture Formalized" — https://arxiv.org/abs/2611.27001 — NOT
  a straightforward formalization announcement: an epistemic/methodological essay arguing that a
  Lean-checked, agent-produced formalization of the Monstrous Moonshine conjecture does not by
  itself settle (1) whether the formal statements express the intended mathematics or (2) whether
  that meaning survives as dependencies evolve — directly relevant to this ledger's own axis-5
  AI-formalization-trust watch (and to the new GRH/Euler-NS trends above). Axis 5 WATCH. Abstract +
  author verified via direct arXiv page fetch this session.
- 2026-11-19 (v1) — Tomov, "A reciprocal-matrix proof of Sendov's theorem and applications to
  control theory" — https://arxiv.org/abs/2611.26766 — an independent, human, non-AI alternate-
  technique paper proving a known partial inequality (Tang-Zhang's quadratic inequality) in the
  Sendov-conjecture circle of ideas; connects to this ledger's already-tracked `study_shelf` item on
  the AI-assisted proofatlas.ai Sendov-conjecture claim (2026-08-05) as an independent, differently-
  motivated (control-theoretic) technique in the same territory, not a resolution of the full
  conjecture itself. Abstract + author verified via direct arXiv page fetch this session.
- 2026-11-26 — Teng Zhang, "When $D$-companion matrix meets Sendov's conjecture" —
  https://hexagonmath.org/2611.01092v1 — a THIRD independent proof in the same already-tracked
  Sendov-conjecture circle (after Mazur's AI-assisted original and Tomov's reciprocal-matrix
  paper above): removes the computer-assisted-verification step from Tao's own simplified proof
  by treating two parameter ranges separately, replacing finite verification with uniform
  analytic estimates. Opened directly via hexagonmath's `/rss/all` feed this session. Strengthens
  (does not change the stage of) the existing `study_shelf` Sendov item's vetting signal —
  independent human engagement now spans three distinct techniques.
- 2026-11-18 — Vals AI blog, "GPT-6.2 Astra Formalizes Smoktunowicz's Gap Theorem" —
  https://vals.ai/blogs — AI-watch-lane item (axis 5), a Lean formalization of a named theorem by a
  third-party AI-benchmarking firm, same pattern as this source's already-tracked Thomson-problem
  item. Not independently opened beyond the blog listing this session (title/date only) — unverified.
- 2026-11-21 (W47 capture-leak sweep: named only in the Ramsey-lower-bound trend's notes as a
  same-author-portfolio escalation, "logged for engagement, not independently re-queued" — never
  given its own queue line) — Gvozdić, Hunter, Milojević, Sudakov, "Sharp bounds for off-diagonal
  and tripartite canonical Ramsey numbers" — https://arxiv.org/abs/2610.03358 (2026-10-02) —
  Hunter-Milojević-Sudakov's own follow-up on Ramsey-adjacent canonical/tripartite bounds, not an
  independent group on the trend's own off-diagonal/hypergraph sub-theme. Axis 1. Title/authors
  verified via arXiv API this session; not independently re-opened in full.
- 2026-11-21 (W47 capture-leak sweep, same source as above) — Kaizhe Chen, "A note on the
  logarithmic exponent of Ramsey number $r(4,t)$" — https://arxiv.org/abs/2610.15293 (2026-10-11)
  — a short note on Lin-Zhang's result below (2610.17891), excluded from the Ramsey trend as
  below-bar. Axis 1. Title/author verified via arXiv API this session; not independently
  re-opened in full.
- 2026-11-21 (W47 capture-leak sweep, same source as above) — Martin Balko, Klára Grinerová, "A
  General Upper Bound on Multicolor Ordered Ramsey Numbers" — https://arxiv.org/abs/2609.28075
  (2026-09-23) — the Ramsey trend's own notes name this as "already tracked on the Harary-Hill
  conjecture trend"; no such evidence line was found there this session (a second, compounding
  leak) — an off-theme (ordered/upper-bound, not the trend's off-diagonal lower-bound sub-theme)
  Ramsey paper. Axis 1. Title/authors verified via arXiv API this session; not independently
  re-opened in full.
- 2026-11-21 (W47 capture-leak sweep, same source as above) — Qizhong Lin, Qiuyang Zhang, "The
  logarithmic exponent of the Ramsey number $r(4,t)$" — https://arxiv.org/abs/2610.17891
  (2026-10-13) — Lin's own follow-up (Lin is already a tracked author on this trend via the
  Lin-Niu evidence line), not an independent group. Axis 1. Title/authors verified via arXiv API
  this session; not independently re-opened in full.
- 2026-11-21 (W47 capture-leak sweep: named only in the Non-invertible-symmetries trend's notes
  as a same-author escalation, never given its own queue line) — Jie Han, Ferdinand Ihringer,
  Hendrik Van Maldeghem, "Optimally pseudorandom $K_4$-free graphs" — https://arxiv.org/abs/2609.32461
  (2026-09-26) — Ihringer's own follow-up (already a tracked author on the Ramsey trend via the
  Ihringer-Mattheus evidence line); pseudorandom-graph construction, not independently assessed
  against either trend's own bar. Axis 1. Title/authors verified via arXiv API this session; not
  independently re-opened in full.
- 2026-11-19 (v2, revised 2026-11-19 from a 2025-01-31 v1; CAPTURE-LEAK CATCH surfaced via the
  revision) — Benedek Kovács, Zoltán Lóránt Nagy, Dávid R. Szabó, "Settling the no-$(k+1)$-in-line
  problem when $k$ is not small" — https://arxiv.org/abs/2502.00176 — PARTIAL: settles the
  century-old no-$(k+1)$-in-line problem (max points in an $n\times n$ lattice with no $k+1$
  collinear) with the exact answer $kn$, but only for $n\ge k\ge C\log n$; the original $k=2$
  (no-three-in-line) case and other small-$k$ regimes remain open. Axis 1. Abstract + authors
  verified via direct arXiv page fetch this session.
- 2026-08-25 (v1), revised 2026-11-19 (v5) — Qihang Wang, "Fröberg's Conjecture for Products of
  Linear Forms: Split Powers and Inherited Syzygies" — https://arxiv.org/abs/2608.24797 — PARTIAL:
  an explicit "split powers" construction matching Fröberg's predicted Hilbert series for products
  of linear forms in four variables for $1\le d\le30$, with an asymptotic agreement result for
  large $d$; not a resolution of the general conjecture. Axis 1. Abstract + author verified via
  direct arXiv page fetch this session.
- 2026-11-19 — Felix Schwarzfischer, "A proof of the Lyons-Pemantle-Peres monotonicity conjecture
  for high offspring laws" — https://arxiv.org/abs/2611.25882 — PARTIAL: proves the LPP
  monotonicity conjecture (speed $\ell'(\lambda)<0$ throughout the transient biased-random-walk
  regime on a Galton-Watson tree) only for offspring laws with $Z\ge4$ a.s.; general case open.
  Axis 1. Abstract + author verified via direct arXiv page fetch this session.
- 2026-11-19 — Shutao Bi, "On the Type E case of the Brown Wemyss realization conjecture" —
  https://arxiv.org/abs/2611.25467 — PARTIAL/CONDITIONAL: constructs geometric realizations for
  the last (Type E) case of the Brown-Wemyss numerical-realization conjecture, completing the
  classification program begun by Brown-Wemyss's own Type A/D cases, but only under the
  hypothesis "radical growth dimension at most one." Axis 1. Abstract + author verified via direct
  arXiv page fetch this session.
- 2026-04-27 (v1), revised 2026-11-19 (v3) — Heath Pearson, "The maximum Cox complexity of a
  Fano-type variety and the Mukai conjecture" — https://arxiv.org/abs/2604.25023 — PARTIAL: defines
  a new "maximum Cox complexity" invariant and uses it to prove the Mukai conjecture only for
  "ambiently smooth" Fano varieties (a subclass containing 45% of smooth Fano threefold
  deformation families); general conjecture remains open. Axis 1. Abstract + author verified via
  direct arXiv page fetch this session.
- 2026-10-12 (v1), revised 2026-11-19 (v2) — E. Minguzzi, "A Cauchy Busemann function approach to
  the geometry of cosmological spacetimes with applications to Bartnik's conjecture" —
  https://arxiv.org/abs/2610.17092 — CONDITIONAL structural result toward Bartnik's splitting
  conjecture for timelike-complete spacetimes satisfying the timelike convergence condition: shows
  any counterexample must contain a specific causally-convex "cosmological wall" structure; not a
  resolution. Axis 2/3 (gr-qc). Abstract + author verified via direct arXiv page fetch this
  session.
- 2026-11-19 — Xiyu Hu, "A One-Sided Liouville Theorem and a Critical Sparse-Support Inverse
  Theorem for Discrete Harmonic Functions" — https://arxiv.org/abs/2611.25952 — answers an open
  question of Buhovsky, Logunov, Malinnikova, and Sodin (Duke Math. J. 171 (2022), Remark 1.4): a
  nonnegative-on-most-of-every-large-square discrete harmonic function on $\mathbb Z^2$ is
  constant. A genuine resolution of a specific posed open problem by well-known analysts, not a
  named conjecture — below the landmark bar on that technicality. Axis 1. Abstract + author
  verified via direct arXiv page fetch this session.
- 2026-11-19 (unrefereed, AI-discovered — EXTREME caution) — Mario Krenn, Moritz Firsching, George
  Tsoukalas, Rishikesh Gajjala, Xuemei Gu, Swarat Chaudhuri, "A Tensor-Algebraic No-Go Theorem for
  High-Dimensional Photonic Greenberger-Horne-Zeilinger States Discovered with AlphaProof Nexus" —
  https://arxiv.org/abs/2611.26300 — a new no-go theorem in quantum optics (no complex-weighted
  monochromatic quantum graph exists for even $N\ge4$ photons when the target dimension $D\ge N$,
  ruling out a class of GHZ-state constructions), with the proof explicitly "discovered through
  AI-assisted formal proof search in Lean using AlphaProof Nexus" — a tool name not previously
  seen on this ledger (distinct from DeepMind's "AlphaProof"; provenance not independently
  confirmed this session). Axis 4 (quantum information physics) + axis-5 AI-watch (note the
  assistance, track the result). Abstract + authors verified via direct arXiv page fetch this
  session.
- 2026-11-20 (hexagonmath, AI-assisted, EXTREME caution) — RJ Acuna, "The strong AJ conjecture for
  hyperbolic prime knots is false" — https://hexagonmath.org/2611.00686 — despite the title, the
  actual claim is narrower: for the specific knot $8_{11}$, verifies Lê's $\widehat P=\widehat A$
  conjecture and Lê's "weak AJ conjecture" (confirming Zhang's prior composite-knot
  counterexample family carries an extra trefoil factor); explicitly cross-references Li, Li, and
  Sun's counterexamples among non-hyperbolic prime knots (already evidenced on this ledger's "AJ
  conjecture's failure for Whitehead doubles of torus knots" trend). A below-bar companion
  single-knot result, AI-assisted and partly Lean-formalized per the paper's own statement. Axis 1.
  Page opened directly via `curl` this session.
- 2026-11-17 (Anthropic's own disclosure page, AI-watch, EXTREME caution — unrefereed preprints,
  hexagonmath) — "Claude solves two open problems in the physics of black holes" —
  https://www.anthropic.com/research/claude-black-hole-physics — TWO distinct axis-2 results, both
  attributed to Claude agents and both WITHOUT a named conjecture (so below the landmark bar even
  before caution is applied): (a) finds the Hawking-Page-type deconfinement transition in weakly-
  coupled $\mathcal N=4$ super Yang-Mills is abrupt (not smooth), extending Hawking-Page (1983),
  Sundborg (1999), and Aharony-Marsano-Minwalla-Papadodimas-Van Raamsdonk's 2003 setup — preprint
  at hexagonmath.org/2611.00175v1, independently cross-checked twice by different agents/methods
  and once by an outside physicist using Claude, no formal Lean check reported; (b) proves an
  exact optimal ceiling $M_1\le c/\Lambda$ with $\Lambda\approx9.1266$ on the lightest black-hole
  mass in the (spin-free) modular bootstrap for 3D gravity (method due to Hellerman 2009, prior
  numerics from Hellerman-Hartman-Mazáč-Rastelli) — preprint at hexagonmath.org/2611.00174v1,
  Lean-formalized in September per the post, and "a physicist checked every main result"; this
  part reportedly reuses the strategy of an already-tracked OpenAI sphere-packing proof. Axis 2
  (math-ph/hep-th, holography and quantum gravity) + axis-5 AI-watch. Post opened directly via
  `WebFetch` this session; corroborated on the same day by a 2026-11-17 Hacker News front-page
  story (intake only).
- 2026-11-18 (v1) — Alexander Sherman, "Semi-exact functors and the conjecture of Coulembier and
  Flake" — https://arxiv.org/abs/2611.24471 — PARTIAL: proves only a "weak form" of the
  conjecture (per the paper's own wording) for symmetric tensor categories; the full conjecture
  (agreement of the new support theory with the Balmer spectrum) stays open. Axis 1. Abstract +
  author verified via direct arXiv page fetch this session.
- 2026-10-09 (v1), revised 2026-11-18 (v2; CAPTURE-LEAK CATCH surfaced via the revision) — Lukas
  Brantner, "The Tate Conjecture for Ordinary Calabi-Yau Threefolds" —
  https://arxiv.org/abs/2610.13939 — PARTIAL: proves the integral geometric Tate conjecture only
  for ORDINARY Calabi-Yau threefolds over finite fields (plus divisor classes on certain ordinary
  CY varieties), a restricted case of the general (still-open) Tate conjecture for CY threefolds.
  Axis 1. Abstract + author verified via direct arXiv page fetch this session.
- 2026-02-16 (v1), revised 2026-11-18 (v2; CAPTURE-LEAK CATCH, ~9 months old, surfaced via the
  revision) — Nikola Adžaga, Tomislav Gužvić, "Completing the classification of torsion over
  sextic fields for elliptic curves defined over $\mathbb Q$" — https://arxiv.org/abs/2602.14718
  — completes a specific classification program (the last open case, $C_3\oplus C_{18}$, shown
  not to occur) rather than resolving a named conjecture — below the landmark bar but a genuine,
  definitive result. Axis 1. Abstract + authors verified via direct arXiv page fetch this
  session.
- 2026-11-18 (v1) — C. L. Liu, "No-Go Theorems for Ordered Universal Entanglement Purification" —
  https://arxiv.org/abs/2611.24603 — a new no-go result for fidelity-ordered universal $n$-to-1
  entanglement-purification protocols in quantum networks — a new theorem, not a named-conjecture
  resolution. Axis 4. Abstract + author verified via direct arXiv page fetch this session.
- 2024-06-28 (v1), revised 2026-11-18 (v4; CAPTURE-LEAK CATCH, ~2.3 YEARS old, surfaced via the
  revision) — Valentijn Karemaker, Chia-Fu Yu, "Supersingular Ekedahl-Oort strata and Oort's
  conjecture" — https://arxiv.org/abs/2406.19748 — PARTIAL: confirms Oort's conjecture only for
  even $g$ with $p\ge5$, and separately for $g=4$, $p>2$ — general case remains open. Axis 1.
  Abstract + authors verified via direct arXiv page fetch this session. Flag for the weekly: a
  2.3-year-old paper surfacing only now via a v4 revision is a severe capture-leak case — worth
  checking whether the v1-v3 history (2024-2025) contains anything else this ledger never had a
  chance to see (this ledger itself only started 2026-07-02, so v1-v3 predate the radar entirely —
  likely a non-issue, but the pattern (several multi-month/multi-year-old revision-triggered
  catches today: this item, the sextic-torsion item above, Rump's Retraction Conjecture and the
  Goemans-analysis paper among today's new seeds/evidence) suggests the "replace"/revision stream
  is a real, under-exploited capture channel — consider whether `radar-source-sweep` should
  explicitly check arXiv's `announce_type:replace` entries, not just `:new`, each rotation).
- 2026-11-18 (v1) — Jean-Marie Morvan, "On a conjecture of Elie Cartan concerning the Gauss
  equation of a flat submanifold" — https://arxiv.org/abs/2611.24415 — MIXED: for flat symmetric
  bilinear forms on $\mathbb R^n$ with values in $\mathbb R^p$, Cartan's 1919/1920 results
  "either can be extended to this setting or fail," depending on $n,p$ — not a clean resolution
  either way. Axis 1. Abstract + author verified via direct arXiv page fetch this session.
- 2026-11-17 (v1) — Unknown authors, "Periodicity of Entire Solutions of $ff''=H^2$" —
  https://arxiv.org/abs/2611.23511 — PARTIAL: proves Yang's conjecture (periodic $ff^{(k)}$
  implies $f$ periodic) only for the $k=2$ case with $H$ itself periodic, not the general
  conjecture. Axis 1 (math.CV Amendment J full-abstract pass, continuing the rotation). Abstract
  verified via direct arXiv page fetch this session.
- 2026-10-27 (published) — "Proof of hiding conjecture in Gaussian boson sampling," Quantum 10,
  2248 (2026) — https://quantum-journal.org/papers/q-2026-10-27-2248/ — PARTIAL: proves the GBS
  "hiding conjecture" only for input states with all modes squeezed (an experimentally-realized
  special case), not the full conjecture. Axis 4, peer-reviewed. Abstract opened directly via
  `curl` this session.
- 2026-11-18 (vals.ai blog post) — "GPT-6.2 Astra Formalizes Smoktunowicz's Gap Theorem" —
  https://vals.ai/blogs/smoktunowicz-gap-theorem — a Lean formalization (94 minutes, OpenAI's
  GPT-6.2 Astra, Vals AI's Autoform-Hard benchmark) of an ALREADY-PUBLISHED 2006 theorem of Agata
  Smoktunowicz on Gelfand-Kirillov dimension gaps in noncommutative algebra — a benchmark
  demonstration, not new mathematics; no independent outside review. Axis 5 AI-watch. Opened
  directly via `WebFetch` this session.
- 2026-11-18 (unverified — Not Even Wrong, Peter Woit) — "Getting Access" —
  https://www.math.columbia.edu/~woit/wordpress/?feed=rss2 (post dated 2026-11-18) — reports a
  secret "shepherd" theorist group (formed at an invitation-only OpenAI-organized KITP workshop)
  getting preferred compute/model access from OpenAI/Anthropic/Google DeepMind to work on
  Yang-Mills/QCD/"Standard Model completion" proofs given to them, and that some KITP panels were
  "academics only" over fear of idea theft by lab-connected attendees. A governance/sociology
  development on the AI-watch lane (axis 5), not a mathematical result — no primary artifact to
  evidence. Opened directly via `curl` this session. Chase for any named individual or institution
  going on record.
- 2026-11-15 (unverified, primary not locatable this session) — Sabine Hossenfelder,
  "A Big Problem Has Appeared in Physics" (video post) —
  https://backreaction.blogspot.com/2026/11/a-big-problem-has-appeared-in-physics.html — flags a
  new "experiment against experiment" particle-physics anomaly/discrepancy (two measurements of
  the same quantity disagreeing); the post's text/summary names neither experiment nor quantity
  (details are in the linked video only, not transcribed). Axis 3. Chase next session via the
  video transcript or a dedicated search once the specific experiments are identifiable.
- 2026-11-15, UPDATED 2026-11-20 (still unverified, STILL no paper located — MathHelm forum
  thread, opened in full this session) — Mark Lewko, "The sharp Kakeya maximal inequality in all
  dimensions" — https://mathhelm.org/t/385/the-sharp-kakeya-maximal-inequality-in-all-dimensions —
  a credentialed harmonic analyst reports using ChatGPT, building on OpenAI's October-25 local-
  smoothing manuscript (= result-family #079 on the OpenAI mass-disclosure trend above), to derive
  the sharp Kakeya maximal inequality $\|K_\delta f\|_{L^n(S^{n-1})}\lesssim_n(\log\tfrac2\delta)
  ^{(n-1)/n}\|f\|_{L^n}$ in EVERY dimension $n\ge2$, with a weighted-tube corollary giving the
  matching Kakeya-set volume lower bound; states the two upper estimates are Lean-formalized in
  the (unpublished) repository, that the construction has been "submitted to Palomar for review"
  (the Lean-verified-mathematics registry tracked via icarm.io above), but that he has NOT
  formalized the matching sharpness construction (credited to Fernández-Delgado and de la Salle).
  Thread also shows a live exchange with Ruixiang Zhang (UC Berkeley, a genuine Kakeya/restriction
  specialist) probing the proof's structure — a real expert engaging with the claim, though not
  yet endorsing it. STILL no arXiv/preprint primary exists for this specific claim (unlike the
  companion Temur paper on the OpenAI mass-disclosure trend, which is a distinct, narrower
  consequence of the same Oct-25 manuscript and IS on arXiv). If true, a sharp ALL-DIMENSIONS
  Kakeya maximal inequality would be an extraordinary extension of Wang-Zahl's 3D Kakeya
  resolution (already on this ledger's `study_shelf`/2026-Fields-Medal entries) and of the OpenAI
  #079 cascade itself. HIGH chase priority next session: look for an actual arXiv write-up or a
  Palomar verification record, and treat with the same unrefereed/AI-assisted-claim caution as
  this ledger's other AI-watch items pending one.
- 2026-11-18 (hexagonmath, below landmark bar, all opened/read directly via `WebFetch`/`curl` this
  session; different author groups, no submitter concentration): "An Averaged Iwasawa Approach to
  Mordell over Q" (https://hexagonmath.org/2611.00576v1) — a NEW PROOF TECHNIQUE for the Mordell
  conjecture via the Chabauty-Kim method; the conjecture itself was already resolved by Faltings
  in 1983, so this is not new territory, just an alternate proof route. "A Universal
  Square-Root-of-Six Bound for Kissing Numbers" (https://hexagonmath.org/2611.00586v1) — proves
  $\sqrt6$ is the sharp constant for the classical spherical-cap-style asymptotic kissing-number
  bound (not a resolution of the kissing-number problem itself, which stays open in most
  dimensions); states a Lean 4/Mathlib certificate is registered in "Palomar." "Cluster monomials
  and finite type" (https://hexagonmath.org/2611.00589v1) — an iff characterization of finite-type
  cluster algebras via their cluster monomials forming a basis; a self-contained structural
  theorem, no named conjecture cited. "Convex-body volume counterexamples to hyperplane
  equipartition" (https://hexagonmath.org/2611.00588v1) — constructs convex-body counterexamples
  to volume-equipartition by affine hyperplanes for $d\ge4$; names no specific prior conjecture by
  author. "An upper bound 0.4893562 for the upper density of the integers p+2^k"
  (https://hexagonmath.org/2611.00570v1) — a record-chasing incremental improvement on a known
  sequence of density bounds (Habsieger-Roblot, Chen-Dai-Li, Patankar, et al.), not a named
  conjecture.
- 2026-11-18 — Daoqiang Liu, "Spectral Geroch conjecture and noncompact area enlargeable
  summands" — https://arxiv.org/abs/2608.24853 (v2, resurfaced today) — proves spectral-constant
  inequalities and an iff characterization for area-enlargeable connect sums (both summands
  possibly noncompact); does not explicitly state a full resolution of "the spectral Geroch
  conjecture" by name — below bar pending a clearer resolution statement. Axis 1. Abstract
  verified via direct arXiv abstract-page fetch this session.
- 2026-11-18 — "A no-go theorem for closed timelike curves in globally null-foliated
  spacetimes" — https://arxiv.org/abs/2610.33706 — a new no-go theorem (gr-qc/math-ph), not a
  named-conjecture resolution — below bar. Abstract verified via direct arXiv abstract-page
  fetch this session.
- 2026-11-18 — Chi Hoi Yip, "A resolution of the Erdős similarity problem in the large" —
  https://arxiv.org/abs/2611.14056 (v2) — PARTIAL: resolves the Erdős similarity problem only
  "in the large" (a strong density/asymptotic form), not the full open problem. Axis 1. Abstract
  verified via direct arXiv abstract-page fetch this session.
- 2026-11-18 — hexagonmath.org batch, below-landmark-bar items (all opened/read this session,
  none independently assessed for correctness): "A self-contained proof of the exponent
  threshold 0.4875754036 for worst-case Subset Sum" (https://hexagonmath.org/2611.00558v1,
  removes a prior conditionality from an algorithmic running-time bound — a technical
  achievement, not a named-conjecture resolution); "Sun's supercongruence for two Apéry-like
  binomial sums" (https://hexagonmath.org/2611.00550v1, companion to today's Sun's-Conjecture-3.7
  seed trend, no explicit numbered-conjecture attribution found this session); "Svinin's
  Conjectures 5.2, 5.3 and 3.1 ... for sequences with all entries nonzero"
  (https://hexagonmath.org/2611.00567v1, PARTIAL — restricted to the nonzero-coordinate domain;
  fails in general); "A Full-Sequence Quantitative Gap Between the Chromatic and Cochromatic
  Numbers of a Random Graph" (https://hexagonmath.org/2611.00562v1, extends Heckel's partial
  answer to the Erdős–Gimbel conjecture; full-resolution status unclear from the abstract alone,
  chase next session); "Obligatory triple systems: atoms, spectra and decompositions"
  (https://hexagonmath.org/2611.00563v1, structural description for Erdős Problem 593, not a
  yes/no resolution).
- 2026-11-18 (unverified, primary not independently opened this session — science.org 403'd,
  no PMC mirror located) — Science Advances RSS, "Discovery of a likely supermassive neutron
  star in a remarkably wide binary" (DOI 10.1126/sciadv.aeg3307, Vol 12 Iss 46, Nov 2026) — a
  possible axis-3 first-of-kind detection (an unusually massive neutron star); chase next
  session via a PMC mirror or the underlying arXiv preprint.
- 2026-11-13 — Kashyap, Kaveh, Manon, Tsvelikhovskiy, "A Helly theorem for the Bruhat-Tits
  building" — https://arxiv.org/abs/2611.17844 — proves a Radon/Helly-type theorem for
  $\mathcal O$-lattices (equivalently, simplices in the Bruhat-Tits building of $\mathrm{GL}(m)$):
  a finite family lies in a common apartment iff every subfamily of size $\le m+1$ does. A new
  theorem, not a resolved open conjecture — below the landmark bar. Axis 1 (arithmetic geometry).
  Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-16 — Chen, Chong, Wang, "Non-tempered GGP conjecture for classical groups: the Bessel
  case" — https://arxiv.org/abs/2611.20494 — PARTIAL: proves relevance of two A-parameters is
  sufficient (and, for co-tempered A-parameters, necessary) for existence/uniqueness of a Bessel
  period in Gan–Gross–Prasad's non-tempered conjecture, but gives counterexamples to necessity in
  the fully general case. Below bar (partial — closes the co-tempered case, leaves the general
  case genuinely open with counterexamples). Axis 1. Abstract verified via direct arXiv `/abs/`
  fetch this session.
- 2026-11-16 — Chen, Liu, Ratz, Stewart, "Lean-Verified No-Go Theorems for $R$-Symmetries and
  Modular Symmetries in 4D GUTs" — https://arxiv.org/abs/2611.20386 — axis-2/5 crossover: Lean 4
  formalization of the existing no-go theorem restricting $R$-symmetries in SUSY SU(5) GUTs;
  identifies and closes a gap in the published argument's general case, and discusses implications
  for modular-symmetry GUT models. A formalization + gap-fix of an established theorem, not a new
  open-conjecture resolution — below the landmark bar but a genuine axis-5 formalization artifact.
  Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-13 — Johansson, Jensen, Nielsen, Adams, Borge (FRIB), "Resolving the isospin-mixing
  anomaly in $^{26}$Si from $^{26}$P $\beta$-decay" — https://arxiv.org/abs/2611.18015 — a new
  high-resolution FRIB measurement of $^{26}$P $\beta$-delayed charged-particle decay revisiting a
  prior "record-high isospin mixing matrix element" claim in $^{26}$Si. Axis 3 (nuclear
  experiment); below bar (a specific-anomaly refinement, not a field-level landmark). Abstract
  verified via direct arXiv `/abs/` fetch this session.
- 2026-11-13 — Yin, Liang, Sun, Yang, Pan, "EP260411a": https://arxiv.org/abs/2611.18210 — an
  ~8s extragalactic fast X-ray transient (Einstein Probe WXT) temporally coincident with short
  GRB 260411A, with pulse-width/peak-time anticorrelations versus burst duration; a specific new
  catalogued event, not yet a field-level landmark. Axis 3. Abstract verified via direct arXiv
  `/abs/` fetch this session.
- 2026-11-12 — Cineli, Ginzburg, Gurel, continuation of the Hofer–Zehnder conjecture for Reeb
  pseudo-rotations — https://arxiv.org/abs/2611.17542 — PARTIAL: bounds on alternating/prime
  closed orbits for $n\ge3$ dynamically-convex non-degenerate Reeb pseudo-rotations of
  $S^{2n-1}$; continues, does not close, the standing Hofer–Zehnder conjecture investigation.
  Axis 1 (symplectic geometry). Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-16 — "Pair Correlation Conjecture for the Zeros of Artin $L$-functions I" —
  https://arxiv.org/abs/2611.20347 — extends the Montgomery pair-correlation-conjecture-implies-
  simple-zeros argument (via Goldston et al.'s horizontal-multiplicity method) to Artin
  $L$-functions; a conditional/partial result (Part I of a series), not a resolution of PCC
  itself. Axis 1. Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-16 — "Pair correlation of $L$-zeros and Hooley's conjecture" —
  https://hexagonmath.org/2611.00509v1 — proves the CUE random-matrix prediction for Dirichlet
  $L$-function zero pair correlation unconditionally for $|\alpha|<1$ and (under GRH + the
  Hardy–Littlewood twin-primes conjecture) for $|\alpha|<2$; for $|\alpha|\ge1$ shows the CUE
  prediction is EQUIVALENT to Hooley's conjecture, not a proof of it. Conditional/equivalence
  result, below bar. Axis 1. Opened directly via hexagonmath RSS/`WebFetch` this session.
- 2026-11-17 — "Double-Pulsar Drag Bounds Dissipative Sources of Diósi–Penrose Decoherence" —
  https://hexagonmath.org/2611.00499v1 — a calculation finding that a ground-state bath (free
  linearized gravitational field) cannot produce the Diósi–Penrose decoherence rate for a static
  mass superposition; uses double-pulsar drag data as an observational bound. Axis 4 (quantum
  foundations); a null/bounding result, below the landmark bar. Opened directly via hexagonmath
  RSS/`WebFetch` this session.
- 2026-11-13 (W46 weekly-swept IAS sweep; UNVERIFIED, underlying piece not opened this session) —
  IAS news, "'Ahead of His Time': AI Helps Unlock Discoveries Hidden in Notebooks of Man Who
  Transformed Maths" — https://www.ias.edu/news — IAS's own one-line gloss (via `tvly search`,
  direct fetch 403'd/Cloudflare) says this points to a Guardian feature on AI-assisted analysis of
  (apparently) Ramanujan's notebooks; axis-5 AI-watch territory (track the mathematical RESULT if
  any, not the AI method) — the underlying Guardian article and any concrete new
  formula/result were NOT located this session. Chase next session: locate the Guardian piece and
  determine whether it names a genuinely new mathematical result or is purely a historical/outreach
  feature.
- 2025-?? (undated in the citing context; accessed 2026-11-14, W46 capture-leak sweep) — Chen, Gui,
  Li, Sun, a lattice-QCD prediction of a pseudoscalar glueball at 2395±14 MeV —
  https://arxiv.org/abs/2605.01757 — named only as "below-bar context" in the X(2370)-glueball
  trend's own evidence prose (never given its own queue line, a genuine capture leak per this
  week's mandatory sweep) — supporting lattice-QCD context for the BESIII X(2370) glueball-identity
  trend (now dormant); not independently opened this session, below-bar on its own, kept for the
  cross-reference.
- 2026-11-06 — Fermilab news, "The SBND collaboration releases first neutrino results" —
  https://news.fnal.gov/feed/ (RSS item; underlying collaboration result/paper not yet located
  this session) — Short-Baseline Near Detector first physics results, axis 3 (neutrino
  phenomenology). Below bar pending the underlying collaboration paper/arXiv preprint — chase next
  session. Opened directly via `curl` this session.
- 2026-11-06 — Qiyue Tang, hexagonmath.org — two further same-session, same-author items from the
  gap-recovery batch, below the landmark bar (routine technical, no named-conjecture resolution):
  "Supremum estimates for $\bar\partial$ on bounded convex domains in $\mathbb{C}^2$"
  (https://hexagonmath.org/2611.00121v1) and "Finite Field Grothendieck Inequality, Finite Field
  Johnson-Lindenstrauss Flattening and Finite Field Bourgain-Tzafriri Restricted Invertibility
  Problems" (https://hexagonmath.org/2611.00124v1). Noted alongside the two seeded items from the
  same author/burst (finite-field factorization, CAD disproof) per the "watch this author" note.
- 2026-11-06 — Gogokhia, Barnaföldi, "The Mass Gap Approach to QCD. III. Solution of the gluon
  confinement problem" — https://arxiv.org/abs/2611.07897 — part III of a continuing, non-AI,
  classical analytic-QCD research program claiming to resolve gluon confinement via an exact
  gluon-propagator expression and infrared-singularity resummation (axis 2, theoretical
  physics); explicitly states gluons remain massless and confinement is addressed separately
  from the mass-gap question. ADJACENT to but NOT evidence for the already-tracked
  "OpenAI's claimed proof of Yang–Mills existence..." trend (different authors, non-AI, a
  distinct classical approach, and the claim itself is confinement, not the Clay Millennium
  mass-gap problem) — cross-referenced, not merged. UNREFEREED PREPRINT — CLAIM (hype-
  skepticism rule): a "solution" to a decades-old confinement problem is PROVISIONAL until
  independent vetting. Below the landmark bar pending corroboration. Abstract/authors verified
  via `WebFetch` this session (v1 2026-11-05).
- 2026-11-06 (capture-leak, found via today's math.AG full-abstract rotation pass) — Shuhong
  Gao, "Counterexamples to the Jacobian conjecture in dimensions greater than two" —
  https://arxiv.org/abs/2608.00222 — generalizes the already-tracked "tangent-sweep" mechanism
  (originally a dim-3 counterexample, 2026-07) from plane curves to direction fields on
  hypersurfaces, yielding counterexamples in EVERY dimension above two, of arbitrarily large
  degree, claimed inequivalent to the existing dim-4+ counterexamples; identities checked in
  exact rational arithmetic. Companion item to the standing Jacobian-conjecture queue cluster
  above/below. CAPTURE-LEAK: first posted 2026-07-31, revised 2026-11-04, sat uncaptured for
  over 3 months — no swept lane's title-triage flagged it until today's full-abstract pass.
  Abstract/authors verified via `WebFetch` this session.
- 2026-11-06 (hexagonmath, unrefereed) — Borcea–Brändén generalized Lax conjecture, "The
  generalized Lax conjecture holds for mixed determinants" — https://hexagonmath.org/2611.00117v1
  — proves spectrahedral representability of the hyperbolicity cone of Borcea–Brändén mixed
  determinants (real algebraic geometry/convex optimization, axis 1), answering four of
  Borcea–Brändén's open problems negatively. UNREFEREED PREPRINT — CLAIM, same caution tier as
  arXiv. Below the landmark bar (a sub-case of the broader generalized Lax conjecture, not its
  full resolution). Title/abstract triaged via the `/rss/all` feed this session.
- 2026-11-06 (hexagonmath, unrefereed) — "The L'vov–Kaplansky conjecture for polynomials of
  degree four" — https://hexagonmath.org/2611.00119v1 — proves the L'vov–Kaplansky conjecture
  (images of multilinear polynomials on matrix algebras are vector spaces) for the degree-4
  case over algebraically closed characteristic-zero fields, extending the known degree ≤3
  cases. UNREFEREED PREPRINT — CLAIM. Below the landmark bar (one more case in a sequence, not
  the general conjecture). Title/abstract triaged via the `/rss/all` feed this session.
- 2026-11-04 — Gyivan Lopez-Campos, "On Diameter Graphs Problems: A proof of Brass's Conjecture" —
  https://arxiv.org/abs/2611.05631 — proves Brass's conjecture that at most 1 point need be
  removed from a finite $S\subset\mathbb{R}^3$ to make its diameter graph 3-colorable (discrete
  geometry, axis 1). Below the landmark bar (single author, narrower-profile named conjecture).
  Abstract + author verified via arXiv API this session.
- 2026-10-05 (capture-leak fix, found 2026-11-05 via Gil Kalai's blog) — Gábor Damásdi,
  "Geometric Realizations with Strong Self-Duality Part II: Diameter Graphs, Reuleaux Polyhedra,
  and Thrackles" — https://arxiv.org/abs/2610.06340 — full characterization of the combinatorial
  structure of diameter graphs and Reuleaux polyhedra in $\mathbb{R}^3$; confirms a converse
  conjectured by Kupitz–Martini–Perles. Companion result to the Brass's-Conjecture item above
  (same sub-area, discrete geometry/diameter graphs). Below bar. Abstract + author verified via
  arXiv API this session.
- 2026-11-04 — Rui Tan, Fanghan Xiang, "On the proof of multi-variable $n/d$-conjecture for
  hyperplane arrangements" — https://arxiv.org/abs/2611.06398 — proves Budur's multi-variable
  $n/d$-conjecture via Wu's method (algebraic geometry/singularity theory, axis 1). Below bar
  (single-paper proof of a research-level, non-ancient conjecture). Abstract + authors verified
  via arXiv API this session.
- 2026-11-04 — Marius Wesle, "A Counterexample to the Weak Gibbs and Regularity Conjectures" —
  https://arxiv.org/abs/2611.06617 — a spin-one translation-invariant nearest-neighbor system on
  the square lattice whose unique KMS state lacks the weak Gibbs/regularity properties (math-ph /
  statistical mechanics, axis 2). Below bar (single author). Abstract + author verified via arXiv
  API this session.
- 2026-11-04 — Jianxi Mao, Wenle Shi, Bao-Xuan Zhu, "Proof of two conjectures on the log-concavity
  of partition ranks and cranks" — https://arxiv.org/abs/2611.06757 — proves Ji–Zang's two
  log-concavity conjectures for partition crank/rank sequences (axis 1, combinatorics/number
  theory). Below bar (recent-vintage conjectures). Abstract + authors verified via arXiv API this
  session.
- 2026-11-03 — Olivia Aubone, José Iovino, "Infinitary real-valued logic and a refinement of the
  Kochen-Specker theorem" — https://arxiv.org/abs/2611.05656 — axiomatizes the Bell–Kochen–Specker
  theorem in real-valued $L_{\omega_1\omega}$ logic via a model-existence game, recovering
  Gleason's theorem in standard models (axis 4, quantum foundations). A refinement/new technique,
  not a resolution of an open problem. Below bar. Abstract + authors verified via arXiv API this
  session.
- 2026-11-03 — Yang Jiang, Qing-Guo Huang, "Observational Test of the Maximum-Entropy Conjecture
  for Black-Hole Mergers with GW250114" — https://arxiv.org/abs/2611.05718 — tests the proposed
  maximum-Bekenstein–Hawking-entropy selection principle for BBH merger remnants against the real
  GW250114 event (axis 3, gravitational-wave observational test). Below bar (a test, outcome not
  yet a landmark confirmation/refutation per the abstract snippet read). Abstract + authors
  verified via arXiv API this session.
- 2026-11-04 — Péter P. Pálfy, "Galois's lost proof on $PSL(2,p)$" —
  https://arxiv.org/abs/2611.06054 — reconstructs, using only methods available to Galois in his
  "testamentary letter," a proof that $PSL(2,p)$ has a subgroup of index $p$ only for $p\le11$ (a
  result otherwise known as a corollary of Gierster's 1881 enumeration). Historical/expository
  reconstruction rather than a new mathematical result; a nice item for a mathematically-literate
  reader but not landmark-tier. Below bar. Abstract + author verified via arXiv API this session.
- 2026-11-04 — Martin Bierbaumer, Matija Bucić, "Polylogarithmic bound for the Gyárfás-Sumner
  conjecture" — https://arxiv.org/abs/2611.06699 — improves the known chromatic-number bound for
  the (still-open) Gyárfás–Sumner conjecture from $|G|^{o(1)}$ to $(\log|G|)^{O(1)}$ (axis 1,
  extremal combinatorics). Progress, not resolution. Below bar. Abstract + authors verified via
  arXiv API this session.
- 2026-11-04 — Máté Róbert Kepes, Anita Kercsó-Molnár, Viczián András, "A family of symmetric
  counterexamples to the bent sum decomposition conjecture" — https://arxiv.org/abs/2611.06744 —
  infinite family of counterexamples to Tokareva's conjecture (every Boolean function of degree
  $\le n/2$ in $n$ even variables is a sum of two bent functions) for every $n=2^k\ge8$ (axis 1,
  coding theory/Boolean functions). Below bar. Abstract + authors verified via arXiv API this
  session.
- 2026-11-03 — Zhen Liu, Chuanshu Wu, "Four-colour counterexamples for monochromatic path
  partitions" — https://arxiv.org/abs/2611.06362 — pins the exact smallest number of colours (4)
  for which Gyárfás's 1989 monochromatic-path-partition conjecture fails, following Li–Wang's
  disproof for "sufficiently large" $r$ (axis 1, Ramsey-type combinatorics). Below bar. Abstract +
  authors verified via arXiv API this session.
- 2026-11-04 — Shulang Peng, Jun Tao, Mian Zhu, Yi-Fu Cai, "A Geometric No-Go Theorem for Regular
  Black Holes in Scalar-Tensor Theories" — https://arxiv.org/abs/2611.06460 — shows scalar-tensor
  theories that stabilize non-singular bounces/wormholes cannot also stabilize static, spherically
  symmetric regular black holes with a two-horizon structure (axis 2/3, gravity). Below bar.
  Abstract + authors verified via arXiv API this session.
- 2026-11-04 (hexagonmath, unrefereed) — "Fully ordinary subfamilies and the Fontaine-Mazur
  conjecture in the residually reducible mixed case" (https://hexagonmath.org/2611.00096v1) and
  "On the Fontaine-Mazur conjecture for $2$-adic representations" (https://hexagonmath.org/2611.00067v1)
  — two partial-case results on the Fontaine–Mazur conjecture (Galois representations/number
  theory, axis 1); hexagonmath is an unrefereed arXiv-style venue, treat with the same caution as
  an arXiv preprint. Below bar (partial cases). Titles/abstracts triaged via the `/rss/all` feed
  this session; not independently cross-checked against arXiv.
- 2026-11-03 (hexagonmath, unrefereed) — "Serre modularity over real quadratic fields" —
  https://hexagonmath.org/2611.00071v1 — extension of Serre's modularity conjecture (already
  resolved over $\mathbb{Q}$ by Khare–Wintenberger) to real quadratic fields. Below bar. Title/
  abstract triaged via the feed this session.
- 2026-11-03 (hexagonmath, unrefereed) — "Computer-assisted bounds 0.556921 <= p_c <= 0.6463 for
  site percolation on the square lattice" — https://hexagonmath.org/2611.00065v1 — rigorous
  computer-assisted bounds on the still-unknown exact site-percolation threshold (statistical
  mechanics, axis 2). Below bar. Title/abstract triaged via the feed this session.
- 2026-11-05 (exploration slot, off-axis rotation: cs.CC) — Karthik Sheshadri, "The determinantal
  complexity of the 4*4 permanent is 15" — https://arxiv.org/abs/2611.06658 — first known EXACT
  value of the determinantal complexity of the $n=4$ permanent (previously only $n=3$ was known
  exactly; the general quadratic bound gives only 8, best prior lower bound was 10), via Grenet's
  construction (upper bound, optimal at $n=3,4$) and a normal-form case analysis (lower bound), all
  certificates public. SIGNIFICANT, OFF-AXIS: computational/algebraic complexity theory (Valiant's
  model) is adjacent to but outside this radar's core math/physics scope (closer to the sibling
  AI/CS radars' beat) — queued rather than seeded per the off-axis significance rule. Abstract +
  author verified via arXiv API this session.
- 2026-11-05 (community pulse, DESI blog, opened directly this session) — "DESI Weighs in on the
  Milky Way's Mass," Joan Najita (NOIRLab) — https://www.desi.lbl.gov/ (same-day post, 2026-11-05)
  — a DESI Milky Way Survey measurement of the Galaxy's mass. Below bar (single press blog post,
  no DOI/arXiv id located this session — chase next session). Opened directly via `WebFetch`.
- 2026-11-04 (community pulse, Simons Foundation feed, opened directly this session) — Shyam
  Menon, Aaron Smith, "A Cosmic 'Leaf Blower'" (Astrophysical Journal, DOI 10.3847/1538-4357/aeaed6)
  — simulation-based result: Lyman-alpha radiation pressure can expel low-density gas/dust from
  early galaxies, making them appear brighter (axis 3, cosmology/ISM). Peer-reviewed journal
  (primary), below bar (single simulation study). Opened directly via `WebFetch`.
- 2026-10-28 (community pulse, Sabine Hossenfelder's blog, opened directly this session; RESOLVES
  the "LHC extra dimension claim remains unlocated" open item carried in the 2026-11-04 report) —
  "Large Hadron Collider Sees Extra Dimension, Physicists Claim" —
  https://backreaction.blogspot.com/2026/10/large-hadron-collider-sees-extra.html — Hossenfelder
  reports (video-based post, full detail not in the text) that two unnamed physicists in France
  claim LHC data shows heavy particles implying an extra spatial dimension, and that "there are
  some problems with their story." UNVERIFIED — no underlying preprint/paper located this session
  despite a targeted `WebSearch` (no author names, collaboration, or arXiv id found); marked
  unverified pending the primary artifact. Chase next session: the French physicists' own paper.
- 2026-11-04/2026-11-05 (axiommath.ai, AI-watch-lane, opened directly this session) — "The Stacks
  Project, formalized in Lean" — https://stacks.axiommath.ai/ — a new Lean/Mathlib formalization
  project translating the tagged results of the Stacks Project (the standard algebraic-geometry
  reference) into machine-checked Lean code, with a two-tier human-reviewed/AI-written
  contribution workflow. Axis 5 (formalized mathematics). No coverage/progress figures were
  loaded at the time this session opened the page (counters still placeholders) — re-check
  coverage next session. Below bar (a new formalization effort, not yet a specific theorem
  milestone). Opened directly via `WebFetch`.
- 2026-11-03 — Felix Gotti, Omar Graia, Neil Panse, "The Bi-LF Positive Conjecture Holds" —
  https://arxiv.org/abs/2610.40688 — resolves a semidomain-theory conjecture (bi-length-
  factoriality ⟺ bi-factoriality); recent-vintage conjecture, below the landmark bar. Abstract +
  authors verified via arXiv abstract page this session.
- PROMOTED 2026-11-17 (reconciliation under the W46-ratified fame/recency-blind seed bar — see
  `routines/daily.md` §3): the two Dave Goel items formerly queued here on 2026-11-03 ("The
  Hibi–Li (2016) conjecture is fully resolved," arXiv:2610.40703; "The Cranston–Li–Su–Wang–Xu
  (2026) conjecture is true," arXiv:2610.40863) were held below-bar under the OLD
  fame/recency-sensitive standard ("recent-vintage conjecture," "same-year conjecture-and-
  resolution") that the W46 ratification explicitly superseded. Both are full resolutions of
  genuinely named conjectures and now seed — see the new "Full resolution of the Hibi–Li (2016)
  conjecture" and "Proof of the Cranston–Li–Su–Wang–Xu (2026) nowhere-zero-flow reconfiguration
  conjecture" trends above. Cleared from this queue.
- 2026-11-03 — Samuel J. Ferguson, Joshua Iosevich, "Tiling without a subspace complement: a sharp
  counterexample in dimension nine over the field with two elements" —
  https://arxiv.org/abs/2610.42005 — completes the classification of when an $\mathbb F_2^d$ tile
  has a linear-subspace tiling complement (true iff $d\le8$); NOT a counterexample to Fuglede's
  conjecture (explicitly noted in the abstract). Abstract + authors verified this session.
- 2026-11-03 — "Haiman's conjecture for n ≤ 10: Kazhdan–Lusztig positivity of monomial immanants" —
  https://arxiv.org/abs/2610.41555 — extends Haiman's own computer verification from $n\le7$ to
  $n\le10$ via an exact large-scale computation; a stronger computer check, not a general proof.
  Abstract verified this session.
- 2026-11-03 — "A conjecture on Galois groups and large fields" — https://arxiv.org/abs/2610.41843
  — Will Johnson PROPOSES a new conjecture (with partial supporting evidence), not a resolution;
  watch item only, logged for completeness. Abstract + author verified this session.
- 2026-11-03 — Jonah Kudler-Flam, "Proof of the entropic $c$-theorem" —
  https://arxiv.org/abs/2610.40874 — a new proof of Zamolodchikov's c-theorem in 2D QFT via mutual
  information between spacelike-separated wedges (relative entropy), following Casini–Huerta;
  notable technique, not a new conjecture resolution — also added to `study_shelf` below. Abstract
  + author verified this session.
- 2026-11-03 (hexagonmath.org) — "A Bound Helium Dianion Does Not Exist" —
  https://hexagonmath.org/2611.00041 — proves no bound 4-electron helium ion exists (extends
  Lieb's 1984 bound via a weighted identity); atomic-physics/math-physics-interface result,
  below the landmark bar. Unrefereed preprint — claim. Description meta verified this session.
- 2026-11-03 (hexagonmath.org) — "Linear independence of even Dirichlet beta values" —
  https://hexagonmath.org/2611.00044 — asymptotic lower bound $\dim_{\mathbb Q}\mathrm{span}_{\mathbb
  Q}\{\beta(2),\ldots,\beta(s)\}\ge0.21\sqrt{s/\log s}$, in the Rivoal-style odd/even-zeta-values
  irrationality tradition. Unrefereed preprint — claim. Description meta verified this session.
- 2026-11-03 (hexagonmath.org) — "Projected stated $(SL_n)$-skein algebras and the Huang–Wang
  conjectures" — https://hexagonmath.org/2611.00013 — proves two named conjectures of Huang and
  Wang on skein algebras equaling their quantum cluster algebras; technical/recent-vintage,
  below the landmark bar. Unrefereed preprint — claim. Description meta verified this session.
- 2026-11-03 (AxiomMath, via `axiommath.ai/research/publications` index, resolving the 6
  teaser-post backlog flagged 2026-11-02) — seven AI-assisted (AxiomProver-verified), Ken-Ono-
  co-authored results, each below the landmark bar (technical number-theory/combinatorics,
  AI-watch-lane, unrefereed preprint — claim): Colin Defant & Ken Ono, "Proof of the Lyons–White
  conjecture" — https://arxiv.org/abs/2608.27708 ("Faster Is Not Nearer"); Evan Chen, Michal
  Mogielnicki & Ken Ono, "Record compositions of alternating permutations and noncommutative
  symmetric functions" — https://arxiv.org/abs/2607.12873 ("The Purpose of the Object"); Simon
  Mahns, Ken Ono & Jujian Zhang, "A problem of Andrews and Dhar on partitions" —
  https://arxiv.org/abs/2606.05117 ("The Address Before the Room"); "Ramanujan's tau function is
  almost never prime" — https://arxiv.org/abs/2603.29970 ("Infinitely Rare"); Rekha Biswal, Ken
  Ono & Jujian Zhang, "Chebyshev quotients, Demazure multiplicities, and Dyck-path models" —
  https://arxiv.org/abs/2604.25246 ("The Figure and the Remainder"); a lattice-triangle
  classification result — https://arxiv.org/abs/2603.23928 ("The Reveal"); Claudia Alfes, Ken Ono
  & Ashvin Swaminathan, "Beyond Mock Modularity: Elliptic Corrections for Higher Dyson Ranks" —
  https://arxiv.org/abs/2607.13159 ("Cut to the Same Measure"). Each post's "Paper and code"
  section opened directly via `tvly extract` this session; GitHub repos under github.com/AxiomMath
  not independently opened (companion-org GitHub access still 403s this session, standing since
  10-28).
- 2026-10-30 (v1; found today via today's math category-rotation title-triage, cross-ref) —
  José Edson Sampaio, "The metric Zariski multiplicity conjecture in dimension 4" —
  https://arxiv.org/abs/2610.41954 — proves the METRIC Zariski multiplicity conjecture TRUE in
  dimension 4, explicitly distinct from (and responding to) OpenAI's own announced counterexample
  to the (non-metric) Zariski multiplicity conjecture in dimension 4. Abstract + author verified
  via arXiv API this session. Cross-reference: OpenAI mass-disclosure trend (cap full, routed here
  per capture discipline rather than that trend's notes).
- 2026-10-30 (v1; found today) — Juliette Bruce, "A Tropical Viewpoint on the Nagata–Biran–Szemberg
  Conjecture" — https://arxiv.org/abs/2610.41931 — gives an independent tropical-geometry
  perspective on OpenAI's announced arguments for Nagata's conjecture and the Nagata–Biran–Szemberg
  conjecture (Nagata's conjecture: open since 1959). Abstract + author verified via arXiv API this
  session. Cross-reference: OpenAI mass-disclosure trend (cap full, same Nagata-conjecture
  sub-theme as the already-evidenced Tevelev exposition).
- 2026-10-30 (v1) — Junran Yu, Gexin Yu, "A Counterexample to the Alon-Krivelevich Conjecture and a
  New Lower Bound for Choosability of Bipartite Graphs" — https://arxiv.org/abs/2610.42094 —
  extremal graph theory (axis 1, math.CO). Abstract + authors verified via arXiv API this session.
  Specialized sub-field — queued.
- 2026-10-30 (v1) — Julius A. Zeiss, "Hedetniemi's conjecture for Shannon OR-capacity:
  counterexamples and asymptotic separation" — https://arxiv.org/abs/2610.41977 — disproves the
  Shannon-OR-capacity analogue of Hedetniemi's conjecture (the ORIGINAL graph-coloring Hedetniemi
  conjecture was already disproved by Shitov 2019; this is a distinct analogue). Abstract + author
  verified via arXiv API this session. Queued.
- 2026-10-30 (v1) — Chi-Heng Lo, "On the generic case of Jiang's conjecture" —
  https://arxiv.org/abs/2610.41765 — $p$-adic representation theory (axis 1, math.RT): proves
  Jiang's conjecture (Aubert–Zelevinsky involution triviality) for the generic case of a general
  quasi-split group, under assumptions on the conjectural local Langlands correspondence. Abstract
  + author verified via arXiv API this session. Partial/conditional — queued.
- 2026-10-30 (v1) — Xuli Qi, Xin Tian, Gregory Gutin, "Hilton-Zhao vertex-splitting conjecture for
  triangle-free graphs" — https://arxiv.org/abs/2610.41984 — confirms a revised Hilton-Zhao
  conjecture for triangle-free base graphs (excluding a known Wagner-graph exception). Abstract +
  authors verified via arXiv API this session. Specialized case — queued.
- 2026-10-30 (v1) — Lars Andersson, Mattias Dahl, Gustav Nilsson, "On the Geroch conjecture for
  toric gravitational instantons" — https://arxiv.org/abs/2610.41875 — mathematical general
  relativity (axis 2, gr-qc/math.DG): a solitonic-form result for Geroch's conjecture restricted to
  toric gravitational instantons, building on Hauser–Ernst and Belinski–Zakharov. Abstract +
  authors verified via arXiv API this session. Case-specific — queued.
- 2026-10-30 (v1) — Florian Naef, Thomas Willwacher, "An odd version of the Grothendieck–Teichmüller
  Lie algebra and the odd Deligne–Drinfeld conjecture" — https://arxiv.org/abs/2610.41766 — defines
  an odd analogue of a classical conjecture and proves it within the same paper (self-posed-and-
  solved, not a longstanding independently-posed conjecture). Abstract + authors verified via arXiv
  API this session. Queued.
- 2026-10-30 (v1) — Lorenzo Pettinari, "A Finite-Range, Translation-Invariant Counterexample to Weak
  Gibbsianity" — https://arxiv.org/abs/2610.41871 — statistical mechanics (axis 2, math-ph):
  constructs a counterexample to Weak Gibbsianity for quantum spin systems on $\mathbb{Z}^2$.
  Abstract + author verified via arXiv API this session. Specialized — queued.
- 2026-10-30 (v1) — Ian P. McCulloch, Jesse J. Osborne, "Resolving the spinon hierarchy of the
  Heisenberg antiferromagnet" — https://arxiv.org/abs/2610.42127 — condensed matter theory (axis 3):
  resolves the zero-temperature dynamical structure factor through six spinons in the thermodynamic
  limit, reaching ~99% of the integrated intensity. Abstract + authors verified via arXiv API this
  session. Solid technical result, not landmark-tier — queued.
- 2026-10-30 (found via today's Fermilab news feed, primary opened directly) — SBND Collaboration,
  "Measurements of transverse kinematic imbalance in muon neutrino charged-current interactions on
  argon..." — https://arxiv.org/abs/2610.39042 — the FIRST neutrino-argon cross-section measurement
  from the Short-Baseline Near Detector at Fermilab (feeds into DUNE); a methodology/calibration
  milestone, not a discovery/anomaly. Fermilab news page + arXiv abstract both opened this session.
  Queued (first-of-kind for the detector, but an interaction-modeling result, not landmark-tier).
- 2026-10-28 (Quantum journal, opened directly) — "A Counterexample to the Optimality Conjecture in
  Convex Quantum Channel Optimization" — https://doi.org/10.22331/q-2026-10-28-2253 — disproves the
  trace-distance optimal-state-transformation optimality conjecture of Coutts et al. (Quantum 5,
  448, 2021). Abstract opened via the journal's own RSS feed this session. Axis 4 — queued.
- 2026-10-27 (Quantum journal, opened directly) — "Proof of hiding conjecture in Gaussian boson
  sampling" — https://doi.org/10.22331/q-2026-10-27-2248 — proves the "hiding conjecture" underlying
  the classical-hardness argument for Gaussian boson sampling, a quantum-computational-advantage
  protocol. Abstract opened via the journal's own RSS feed this session. Axis 4 — queued.
- 2026-10-29 (v1; hexagonmath.org `/rss/all`, found via today's large batch sweep) — "Every real
  primitive Dirichlet L-function has de Bruijn–Newman constant at most 9/32: a kernel-checked proof
  in Lean 4" — https://hexagonmath.org/2610.00714 — a Lean-kernel-checked generalization of the
  de Bruijn–Newman-constant bound (which relates to RH) to all real primitive Dirichlet characters;
  the page's own text states "the mathematics is not new, and we say exactly whose it is" —
  suggesting this is a FORMALIZATION of existing human mathematics rather than a new result.
  Abstract opened via `curl` this session; no author byline resolved. Cross-reference: axis-5
  formalization watch + the quasi-Riemann-Hypothesis trend family (related constant, distinct
  claim) — queued, not merged into either.
- 2026-11-02 (v1; hexagonmath.org, same batch) — "Positive polytopes and the full Fock–Goncharov
  conjecture" — https://hexagonmath.org/2611.00015 — proves the origin-interior form of the
  Gross–Hacking–Keel–Kontsevich polytope criterion for full Fock–Goncharov positivity of a
  principal-coefficient cluster variety (a criterion result, not a full resolution of the parent
  conjecture in general). Abstract opened via `curl` this session; no author byline resolved. Axis
  1 — queued.
- 2026-11-02 (v1; hexagonmath.org, same batch) — "Claw-free perfect graphs are chromatic-choosable"
  — https://hexagonmath.org/2610.00713 — proves $\mathrm{ch}(G)=\chi(G)=\omega(G)$ for every
  claw-free perfect graph, with a precoloring-extension strengthening. Abstract opened via `curl`
  this session; no author byline resolved. Axis 1 — queued.
- 2026-10-30 (found via today's Perimeter Institute news sweep — `tvly extract`, HEALED this
  session after standing degraded) — "How a 'tropical' shortcut could help particle collider
  experiments" (Michael Borinsky) — https://perimeterinstitute.ca/news/how-tropical-shortcut-could-help-particle-collider-experiments
  — tropical-geometry methods applied to scattering-amplitude/Feynman-integral computation, the
  math↔physics interface (axis 2). Perimeter's own news page opened directly this session; the
  underlying paper not independently located. Queued.
- 2026-11-02 (v1; axiommath.ai/research/ blog index, several teaser-style posts whose underlying
  papers were NOT resolved to an arXiv id this session — the page is JS-rendered and links are not
  present in the static HTML; `tvly extract`'s markdown conversion also dropped the links) —
  flagged for next session to resolve via the org's "Selected publications" index
  (axiommath.ai/research/publications) instead: "Cut to the Same Measure" (higher Dyson systems /
  Jacobi-theta elliptic law), "The Purpose of the Object" (a combinatorial-identity paper), "The
  Address Before the Room" (a bijective-matching result), "The Figure and the Remainder" (a
  Demazure/Dyck-path multiplicity count), "The Reveal" (a density-1 lattice-triangle result),
  "Infinitely Rare" (on Ramanujan's $\tau$ function taking prime values). NOT independently opened
  — titles/one-line descriptions only, from the blog index page. Unverified.
- 2026-11-02 (v1; hexagonmath.org, same batch) — "On a Family of Counterexamples to Richard Guy's
  Mex Sequence Problem" — https://hexagonmath.org/2610.00735 — a combinatorial-game-theory
  counterexample family. Title opened via `curl` this session; abstract not independently read.
  Axis 1 — queued, low priority.
- 2026-10-22 (v1; capture-leak fix, W44 mandatory sweep) — unsigned/unidentified-author note,
  "Rigidity, flexibility, and a sign error" — https://arxiv.org/abs/2610.30976 — the first
  technical post-mortem of WHY OpenAI's withdrawn Hodge-conjecture manuscripts [OAI26a, OAI26b,
  OAI26c] failed ("we discuss the source of the error"); named in the OpenAI mass-disclosure
  trend's 2026-10-23 note as "cited here, URL is the citable primary" but never given its own
  evidence or queue line (that trend's evidence cap was already full) — a genuine capture leak,
  fixed this session. Cross-reference: OpenAI mass-disclosure trend.
- 2026-10-21 (v1; found this session via a Henri Cohen MathOverflow thread) — Robinson, "Elements
  of the Green ring related to Alperin's weight conjecture" — https://arxiv.org/abs/2610.27988 —
  modular representation theory (axis 1, math.RT): a tribute/exploratory contribution reframing
  numerical questions from Alperin's celebrated weight conjecture via projective modules and the
  Green ring — explicitly NOT a claimed resolution. Abstract + author verified via arXiv API this
  session. Context on a major open conjecture, not a resolution — queued, watch for an actual
  resolution attempt.
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
  - 2026-09-03 (daily) — INDEPENDENT VETTING SIGNAL (strongest yet on this item): Youness
    Lamzouri (York University), "A new proof that more than 2/3 of the zeros of the Riemann zeta
    function are simple and on the critical line," arXiv:2609.02882 —
    https://arxiv.org/abs/2609.02882 — a fully independent, unconditional, human-authored proof
    reaching the SAME two numeric bounds (>67.25% simple-and-on-the-line, ≥83.62% distinct) as
    the Claude/Anthropic claim, via a shorter, more transparent route (a Hilbert-space inequality
    replacing Claude's finite-dimensional matrix framework, applied directly to Montgomery's
    pair-correlation theorem in the unconditional Baluyot–Goldston–Suriajaya–Turnage-Butterbaugh
    form). Lamzouri's own abstract explicitly names the Claude proof and states it "was
    subsequently verified by Alpöge and Furman" (the two in-house Anthropic mathematicians named
    in the original paper's acknowledgments) — the clearest public confirmation yet that the
    claimed bound holds, though this is a NEW independent proof of the same numbers rather than a
    line-by-line audit of Claude's original argument, and still no formal referee outcome or
    published statement from Conrey/Goldston. Abstract + author verified via arXiv API this
    session (v1 2026-09-02). Upgrades this item from "provisional, informally examined" to
    "provisional, now independently re-derived by a specialist" — track for a peer-reviewed
    outcome. Also added to `study_shelf` (see below) — the vetting event itself is the story.
  - 2026-10-17 (v1; found this session via today's math category-rotation batch) — J. Arias de
    Reyna, "Human Exposition of Claude's 2/3 Theorem on the zeros of zeta" —
    https://arxiv.org/abs/2610.24612 — a human mathematician's own detailed write-up/exposition of
    Claude's original proof (not a new independent re-derivation like Lamzouri's, but a direct
    exposition of the ORIGINAL argument's actual steps), stating it is "simpler than the previous
    ones and takes a different approach." Abstract + author verified via arXiv API this session.
    Upgrades the vetting picture further: a working number theorist has now gone through Claude's
    own argument closely enough to re-expose and simplify it, a step beyond Lamzouri's independent
    re-derivation. Still not a formal referee outcome. Also added to `study_shelf`.
  - 2026-10-21 (daily) — VETTING-STATUS CORRECTION (a genuine "gap found in review" signal, per the
    hard rule's hype-skepticism caution): the full text of Arias de Reyna's own exposition
    (2610.24612, above — HTML full text opened this session, `arxiv.org/html/2610.24612v1`) states
    plainly that the original Anthropic/Claude proof "[a]s it's written... doesn't work," calling it
    "filled with bad notations, wrong assertions and unneeded statements," and flags one bound as
    insufficient ("Their bound is of the order of N and it is not sufficient") — while judging the
    necessary fix minor ("the necessary modification deserves [no] more than a note"). This was
    present in the paper when it was first captured 2026-10-17 but not surfaced in this ledger's
    note at the time (only "simpler... different approach" was recorded) — a capture-depth miss,
    corrected now. Surfaced via a MathOverflow thread opened today, "Reliability of Anthropic's Lean
    verifications" (Henri Cohen, 2026-10-20, https://mathoverflow.net/questions/516206/) asking how a
    Lean-verified proof can contain false statements that invalidate it — a named specialist raising
    exactly this question, unanswered as of this session (intake-only; the primary full-text check
    above is the actual evidence). Net effect: the original Claude/Anthropic argument as published
    contained a real, acknowledged defect (not merely informally examined and found sound); the
    headline 2/3-bound result itself is NOT contradicted (Lamzouri's fully independent re-derivation
    reaches the same numeric bounds via a different route, and Arias de Reyna's own exposition
    presents a working proof), but "Lean verified it" no longer reads as a clean correctness signal
    for the ORIGINAL manuscript specifically. Confidence/stage unaffected (still a queue item, not a
    seed trend); flagged for continued watch — whether Anthropic itself corrects the original
    paper/repo, and whether Henri Cohen's reliability question gets an on-record answer.
  - 2026-10-23 (daily) — EXPOSITORY SURVEY + A NEW PRIORITY-DISPUTE LEAD. Caroline Turnage-
    Butterbaugh (co-author of the underlying BGST-B papers) posted a guest exposition on Terence
    Tao's blog, "Simple and critical zeros of the Riemann zeta-function"
    (https://terrytao.wordpress.com/2026/10/22/simple-and-critical-zeros-of-the-riemann-zeta-function/,
    2026-10-22, opened directly via `WebFetch` this session), surveying the full history (Levinson,
    Heath-Brown, Conrey, Pratt et al., Montgomery's conditional pair-correlation result) alongside
    this item's standing claims — a clean, named-specialist restatement of the same vetting picture
    already on file (Anthropic's announcement + in-house verification by Alpöge/Furman; Lamzouri's
    independent re-derivation), not a new correctness signal. NEW LEAD (intake-only, NOT verified
    this session): a comment on the post from Nathan Ng states Farzad Aryan proved an unconditional
    version of Montgomery's 1973 pair-correlation theorem in a 2022 Journal of Number Theory paper —
    if correct, this could bear on priority for the ≥2/3-simple-and-critical bound predating the
    2026 results tracked here. NOT independently verified this session (a blog comment, no arXiv/
    DOI opened) — flagged for next session or the weekly to chase (locate the actual 2022 JNT paper
    and assess whether it changes the priority picture for this item).
  - 2026-W43 recalibration (Nathan Ng lead CHASED): located and opened Aryan's paper directly —
    "On an extension of the Landau-Gonek formula," J. Number Theory 233 (2022) 389-404 (arXiv
    preprint 1902.05473, 2019-02-14, verified via arXiv API). PRIORITY QUESTION RESOLVED, no
    change to this item: Aryan's own abstract states the ≥2/3-simple-zeros corollary holds only
    "under a zero density hypothesis, which is weaker than the Riemann hypothesis" — i.e.
    CONDITIONAL on an unproved (if weaker-than-RH) hypothesis, not unconditional. The 2026 results
    tracked here (Claude/Anthropic, Lamzouri, the unconditional BGST-B form) are unconditional —
    Aryan's 2022 result does not predate or undercut their priority on the unconditional bound;
    Nathan Ng's blog comment (as characterized in the 2026-10-23 report) appears to overstate
    Aryan's result as unconditional. Not itself a primary for this ledger's own tracked claim
    (a different, weaker/conditional result) — not added as a new evidence/queue line.
- 2026-11-18 (RECONCILIATION — removed, promoted to a seed trend): the Long xz-/Mathieu-
  Conjecture-for-SU(2) counterexample (arXiv:2607.19012) that previously lived here was promoted
  to "Disproof and classification of the Mathieu (Mathieu–Zhao) conjecture..." this session —
  see `## Active trends`; no longer a queue item.
- 2026-07-17 → 07-23 (Pass 2) — community-pulse (intake, UNVERIFIED — never evidence) — a multi-model AI-assisted-mathematics WAVE now landing CONCRETE arXiv artifacts, not just chatter: (07-17, r/math) GPT-5.6 reported to solve all six IMO 2026 problems + a claimed Lean-verified closing of a ~30-year gap in convex optimization; (07-20→23, HN front page + r/math) the JACOBIAN-CONJECTURE counterexample now the center of gravity — "Terence Tao is left scratching his head about the Jacobian Conjecture counterexample" (r/math top) + "Terence Tao's ChatGPT conversation about the Jacobian Conjecture counterexample" (HN front page), David Speyer's "The new counterexample to the Jacobian conjecture" (Secret Blogging Seminar) working through it; the counterexample (3-variable, refuting the general conjecture) attributed to Anthropic's Claude Fable 5 (Levant Alpöge's X announcement, >20M views per Fortune); an AMS Notices interview with Fields-frontrunner Jacob Tsimerman on AI in math; (07-22) an unverified RUMOR that the 2026 Fields Medal winner list leaked ahead of the ICM opening ceremony — https://www.reddit.com/r/math/ · https://news.ycombinator.com/ — WATCH area per scope: AI-assisted math is the sibling AI radars' beat. STATUS OF PRIMARIES (re-checked this session): the wave now has FIVE distinct AI-assisted results (four with concrete arXiv artifacts, one off-arXiv): OpenAI Cycle-Double-Cover proof (Geelen 2607.15399 + Oum 2607.16356 expositions), Batyrev-conjecture counter-example via ChatGPT (2607.19184), mod-4 Kawauchi proof via Claude Fable 5 (2607.18655), the Jacobian-conjecture counterexample via Claude Fable 5 — whose FIRST on-arXiv mathematical analysis appeared 07-22 (Shaska, 2607.20210, captured; the counterexample MAP itself is still announced only OFF-arXiv → the map stays intake, the analysis paper is the primary) — and NEW THIS PASS (07-23), a claimed disproof of the ~30-year-old DINITZ–GARG–GOEMANS conjecture on single-source unsplittable flows (Kleinberg/Dinitz–Garg–Goemans 1999: any fractional single-source flow can be rounded to an unsplittable one raising each edge by < d_max), attributed to Dmitry Rybin using GPT-5.6 Pro — announced OFF-arXiv (X post + Digg, surfaced via r/math + r/mathematics this pass); NO arXiv primary locatable this session (searched arXiv for Rybin/unsplittable-flow, only pre-existing DGG-related works) → stays UNVERIFIED community-pulse intake exactly like the Jacobian map, WATCH area (track the RESULT if/when a primary lands, not the method), extraordinary-claim caution (a 30-yr conjecture "disproof" is provisional until vetting). Community engaging = a vetting SIGNAL, not an OUTCOME (all unrefereed; Tao publicly scrutinizing). STILL NO IMU primary for the Fields Medal "leak": the mathunion.org Fields-Medal page (RE-OPENED this Pass 2, ~13:48 UTC) is STILL the static statute page — no 2026 laureates listed; a broad news search returned zero Fields-Medal hits (only sports/politics noise) → the announcement has NOT propagated as of this pass (ICM opening ceremony 23–30 Jul in Philadelphia; Fields Medals announced at the ceremony — still pending). CONFIRMED this pass that the 20th IMU General Assembly IS in session (NYC 20–21 Jul): r/math surfaced the GA vote selecting GLASGOW as ICM 2030 host (ecosystem, intake). Chase the official Fields announcement first thing next run. IMO-2026 results still have no arXiv artifact.
  - RE-CHECKED 2026-10-17 (W42 weekly, queue-aging review): the Fields-Medal-"leak" thread above is
    now MOOT — the official 2026 Fields Medals (Deng, Pardon, Tsimerman, Wang) were announced and
    captured as their own evidence/study_shelf line on 2026-07-24 (see elsewhere on this ledger).
    The Dmitry Rybin / GPT-5.6-Pro claimed Dinitz–Garg–Goemans-conjecture disproof remains
    UNVERIFIED — still no arXiv primary locatable this session; still watched, not yet promoted or
    dropped.
  - RESOLVED 2026-11-07 (W45 weekly, queue-aging review): PROMOTED — the missing primary was never
    going to be an arXiv paper; it is an Isabelle/AFP formal-verification entry
    (isa-afp.org/entries/Dinitz_Garg_Goemans_Counterexample.html, opened this session). See the new
    "Disproof of Goemans's cost-preserving unsplittable-flow conjecture" seed trend above.
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
- 2026-09-04 (surfaced via community pulse — a Hacker-News front-page thread pointing to a
  Reddit post — chased to the primary same session; also see `study_shelf`) — Claude (Anthropic)
  with human author Justin Leder, "θ(p_c) = 0 for Bernoulli bond percolation on ℤ^d in all
  dimensions d ≥ 2, in Lean 4 / Mathlib" —
  https://github.com/anthropics/formal-math/blob/795efb86f191735c5481675763537cfb4ff37e55/percolation/README.md
  (proof-sketch PDF at the same commit,
  .../percolation/summary.pdf) — probability theory / percolation (axis 1, math.PR) / AI-WATCH +
  axis 5 (formal verification): a complete Lean 4/Mathlib formalization proving the "dying
  percolation" conjecture — that the percolation probability θ vanishes at the critical point,
  θ(p_c) = 0, for nearest-neighbour Bernoulli bond percolation on ℤ^d for EVERY d ≥ 2. The result
  was known only for d = 2 (Harris 1960, Kesten 1980) and d ≥ 11 (lace expansion, Hara–Slade 1990/
  Fitzner–van der Hofstad 2017); the intermediate cases 3 ≤ d ≤ 10 (crucially including ℤ³) were a
  famous open problem, cited in Grimmett's *Percolation* (2nd ed., pp. 14, 202–203) and as
  Conjecture 1 of Duminil-Copin's ICM 2018 problem list. The route: proves Kozma–Nitzan's
  Conjecture 3 ("near-one gluing," arXiv:2401.12397, 2024) — which Kozma–Nitzan's own Theorem 6
  shows implies θ(p_c) = 0 — via a new "additive gluing inequality" derived from a "conditioned
  slack hierarchy" of covariance inequalities; every classical input (Harris, van den Berg–
  Häggström–Kahn, the four-functions theorem, Gladkov's decision-tree Harris–Kleitman inequality,
  the Barsky–Grimmett–Newman half-space theorem, Kesten's p_c(ℤ²)=1/2) is re-proved from Mathlib,
  so the Lean statement has no hypothesis beyond `2 ≤ d`. README + proof-sketch PDF opened via
  `tvly extract` this session (repo commit 795efb86, README states the toolchain as Lean
  `v4.32.0` / Mathlib `v4.32.0`). HEAVY HYPE-SKEPTICISM + AI-WATCH CAUTION (track the RESULT and
  the formalization artifact, not the AI method — sibling AI radars' beat): the repository's own
  README states plainly "The work has not yet been refereed by anyone independent of the author;
  correctness rests on the mechanical checks recorded in AUDIT.md" — PROVISIONAL until an
  independent Lean audit or expert statement, despite the formal (machine-checked, axiom-minimal:
  only `propext`, `Classical.choice`, `Quot.sound`) nature of the proof, which is a materially
  stronger evidence class than an unrefereed prose preprint. Surfaced via Gil Kalai's blog
  ("Amazing: There is no Percolation at the Critical Probability in all Dimensions," posted
  2026-09-03, h/t Itai Benjamini) — https://gilkalai.wordpress.com/2026/09/03/amazing-there-is-no-percolation-at-the-critical-probability-in-all-dimensions-solved-by-ai-via-a-conjecture-of-gady-kozma-and-shahaf-nitzan/
  — opened via `tvly extract` this session; Kalai calls it, if verified, "a remarkable
  breakthrough." RESOLVES a standing open lead from the 2026-09-03 and 2026-09-01 daily reports
  ("Kozma-Nizan"/"Another Leaked Result" — the correct name is Kozma–Nitzan; the earlier
  Reddit-sourced spelling was a mishearing, now confirmed via Kalai's primary post). Related
  expert-commentary context (opened this session, not evidence): Fields medalist Hugo
  Duminil-Copin (percolation theory; the ICM18 problem-list author cited above) published "Care
  for a little more AI?" on 2026-08-30 (https://proofsandprompts.com/2026/08/30/care-for-a-little-more-ai/),
  predicting AI would likely resolve a famous percolation conjecture before humans do — written
  four days before this specific claim surfaced, so not a direct comment on it, but relevant
  standing context from the field's leading authority. Watch for: an independent Lean-proof audit,
  a statement from Kozma, Nitzan, or Duminil-Copin specifically on this claim, and any arXiv/
  journal write-up. Also on `study_shelf`. Source-discovery: github.com/anthropics (the
  `anthropics/formal-math` org/repo) staged below as a new AI-disclosure-lane candidate, distinct
  from the already-tracked anthropic.com/research pages.
  - 2026-10-22 (daily): PROMOTED to its own seed trend — "AI-claimed resolution of the
    percolation-criticality conjecture (Benjamini–Schramm; Claude and OpenAI, independently)" — see
    Active trends above. OpenAI independently claimed essentially the same landmark (preprints dated
    2026-09-24, disclosed 2026-10-06), and Scientific American (2026-09-30) plus a human exposition
    note (Gouéré, 2610.30063, 2026-10-21) now provide sustained multi-source engagement. This entry
    kept in place (not deleted) for its original capture detail; superseded for trend tracking.
- 2026-09-17 (blog announcement, not a result; discovered via Terence Tao's blog this session) —
  https://terrytao.wordpress.com/2026/09/16/sair-competition-lean-kernel-challenge/ — Terence Tao
  (SAIR Foundation, with Joachim Breitner, Kim Morrison, Leonardo de Moura), "SAIR competition –
  Lean Kernel Challenge" — axis 5 (computer-assisted & formalized mathematics, ecosystem/tooling):
  launches Stage 1 of a multi-stage competition to develop faster verified-computation algorithms/
  representations for the Lean 4 kernel (eight fixed problems: Fibonacci, integer partitions, the
  Mertens function, prime counting, matrix permanent, Rule 110, SHA-256, polynomial discriminant;
  deadline 2026-11-20). Blog post opened in full via `tvly extract` this session. NOT a result — a
  second axis-5 competition launch this month (after the Andrews-Curtis Conjecture Challenge,
  09-11, already queued) — queued purely as a WATCH item for future submissions, same pattern.
- 2026-11-19 (daily, VETTING-STATUS DEVELOPMENT) — Zhen Lei, Xiao Ren, "Finite-Time Blowup for
  Navier-Stokes with Smooth Forcing, Part I" — https://arxiv.org/abs/2609.35406 — found via a new
  source this session, MathHelm (research-mathematician forum, staged in SOURCES.md): an
  independent, named Navier-Stokes researcher's own "readable and accessible" reconstruction of
  the profile-construction part of OpenAI's claimed proof, stating plainly "We regard OpenAI's
  work as a major advance on the Navier-Stokes Millennium Prize Problem" — the first substantive
  CONSTRUCTIVE (not merely critical) expert engagement with the mathematical content of this claim
  this ledger has tracked, over two months after the original announcement. This is a positive
  vetting-engagement signal, NOT independent verification or reproduction of the complete claimed
  proof (Lei/Ren's own paper covers only the profile-construction part; a "Part II" on cancellation
  of the divergence-form residual is referenced but not located this session — chase next
  session). Also added as evidence on the OpenAI mass-disclosure trend above. Abstract + authors
  verified via direct arXiv page fetch this session.
- 2026-10-21 (v1) — Yang Chen, "The Kemper–Malle conjecture and isolated linear quotient
  singularities" — https://arxiv.org/abs/2610.29849 — algebra (axis 1, math.AC/RA): proves the
  Kemper–Malle conjecture (a modular analogue of Chevalley–Shephard–Todd), reducing classification
  of isolated linear quotient singularities in positive characteristic to the classical
  Zassenhaus–Vincent–Wolf classification. Below bar. Abstract + author verified via arXiv API this
  session.
- 2026-10-21 (v1) — Mahtab Alghasi, Bertrand Guenin, Levent Tunçel, "The Local Dyadic Conjecture" —
  https://arxiv.org/abs/2610.29197 — combinatorial optimization (axis 1, math.CO/OC): a local
  version of Paul Seymour's long-standing dyadic conjecture for ideal clutters, with an important
  special case proved (not the full conjecture). Below bar. Abstract + authors verified via arXiv
  API this session.
- 2026-10-21 (v1) — Seick Kim, Hocheol Shin, "Kelly's conjectures on Condorcet winner probabilities
  for odd electorates" — https://arxiv.org/abs/2610.29904 — probability/social choice (axis 1,
  math.PR): proves two monotonicity conjectures of Kelly on Condorcet-winner probability under
  random preferences. Below bar. Abstract + authors verified via arXiv API this session.
- 2026-10-22 (v1) — el Houcein el Abdalaoui, "OpenAI partially disproves Littlewood's 1961 $L^\alpha$-
  flat theorem" — https://arxiv.org/abs/2610.30797 — harmonic analysis (axis 1/5, math.NT): an
  OpenAI-produced counterexample to Littlewood's theorem on $L^\alpha$-flat trigonometric
  polynomials, but the author's own abstract states it is "only a limited refutation, as such
  sequences fail to satisfy an implicit assumption of Littlewood's theorem" — a self-admitted
  partial result. Cross-referenced to "OpenAI's mass mathematical-results disclosure" above (same
  Oct-6 release); not added as evidence there (cap full). Below bar. Abstract + author verified via
  arXiv API this session.
- 2026-10-22 (v1) — Samuel J. Ferguson, Joshua Iosevich, "Fuglede's conjecture holds in
  $\mathbb{F}_p^d$ for $p=2,d=8$ and $p=11,d=3$" — https://arxiv.org/abs/2610.30712 — harmonic
  analysis/combinatorics (axis 1, math.CO/CA): confirms Fuglede's spectral-set conjecture (1974)
  for two specific finite-field cases, completing a dimension-eight reduction left open by
  Kadowaki. Partial (specific cases, not the general conjecture) — below bar. Abstract + authors
  verified via arXiv API this session.
- 2026-10-22 (v1) — Dániel Gábor Simon, "Conway's thrackle conjecture: a new upper bound of
  $\frac{4}{3}n$" — https://arxiv.org/abs/2610.31589 — graph drawing (axis 1, math.CO): improves
  the best known upper bound on thrackleable-graph edge count toward Conway's 1960s conjecture
  (edges ≤ vertices); not a resolution. Below bar. Abstract + author verified via arXiv API this
  session.
- 2026-10-21 (v1) — Peter Sziklai, "The linearity Conjecture" — https://arxiv.org/abs/2610.30503 —
  finite geometry (axis 1, math.CO): proves the Linearity Conjecture (every minimal blocking set in
  PG(2,q) is a linear point set over a subfield) for all cases except exponent $p^e=3,4$ — a
  near-complete resolution with two small exceptional cases outstanding, by an established finite-
  geometry researcher. Held below the seed bar pending the exceptional cases or independent
  engagement, but flagged as the strongest single item in today's batch after the two already-
  seeded results above. Abstract + author verified via arXiv API this session.
- 2026-10-22 (v1) — Yen-Chi Roger Lin, Valjakas Djaljapayan, Wei-Hsuan Yu, "The Ternary and
  Quaternary Cases of the $\{2,4\}$-Distance Code Conjecture" — https://arxiv.org/abs/2610.30615 —
  coding theory (axis 1, math.CO/IT): settles the two remaining alphabet sizes (ternary,
  quaternary) of the Boyvalenkov–Delchev–Zinoviev–Zinoviev distance-code conjecture, completing it
  alongside the previously-settled binary case. Specialized coding-theory conjecture, full
  resolution — below the seed bar (niche sub-field) but a genuine completed-conjecture result.
  Abstract + authors verified via arXiv API this session.
- 2026-10-22 (v1) — Jianxun Hu, Hua-Zhong Ke, Changzheng Li, Jiayu Song, "Gamma conjectures for
  Milnor hypersurfaces" — https://arxiv.org/abs/2610.31150 — mirror symmetry (axis 1/2, math.AG):
  proves Gamma conjectures I and II of Galkin–Golyshev–Iritani for Milnor hypersurfaces, a further
  case in the same ongoing verification program as the already-queued Fano-fourfold case
  (2610.13331, 2026-10-09). Below bar. Abstract + authors verified via arXiv API this session.
- 2026-10-22 (v1) — Yutian Li, "Pólya's conjecture for Neumann eigenvalues of spherical shells" —
  https://arxiv.org/abs/2610.31464 — spectral geometry (axis 1/2, math.AP/SP): the Neumann
  companion to the already-queued Dirichlet case (2610.27707, 2026-10-20) — extends Pólya-type
  inequalities to a further eigenvalue boundary condition on the same family of domains. Below
  bar. Abstract + author verified via arXiv API this session.
- 2026-10-22 (v1) — Hiranmoy Ghorui, Suman Mondal, Samya Kumar Ray, "Failure of noncommutative
  Rota's theorem with $L\log L$ endpoint" — https://arxiv.org/abs/2610.31560 — operator algebras
  (axis 4, math.OA): answers a question of Anantharaman-Delaroche (2006) in the negative via an
  explicit factorizable Markov-map construction. Specialized, below bar. Abstract + authors
  verified via arXiv API this session.
- 2026-10-22 — Simons Foundation, "Now Fully Online, Simons Observatory Begins Probe of Universe's
  Birth" — https://www.simonsfoundation.org/news/now-fully-online-simons-observatory-begins-probe-of-universes-birth/
  — axis 3 (cosmology/CMB) ecosystem/instrument milestone, opened directly via `WebFetch` this
  session: the Simons Observatory (Atacama Desert, Chile — 3 Small Aperture Telescopes + the Large
  Aperture Telescope, ~98,000 detectors) is now fully operational, with early maps already deeper
  than Planck's; main science target is inflationary B-mode polarization (results "a few more
  years" out per the article). Not itself a discovery/detection — an instrument-commissioning
  milestone, same below-bar ecosystem-event treatment as the Simons Collaboration on Defects launch
  above. Watch for: the first B-mode/inflation results in coming years.
- 2026-09-20 (v1, Vals AI blog by Geby Jaff; found 2026-10-26 via today's vals.ai/blogs sweep) —
  "C-HD": a claimed formally-verified improvement over the 2025 Duan-Mao-Shu-Yin single-source-
  shortest-paths bound (arXiv:2504.17033) and its 2026 follow-up (arXiv:2602.07868), produced by ten
  coordinated Claude Opus 5.5 agents over ~15 hours — https://github.com/spicylemonade/c-hd-proof
  (no arXiv preprint; Lean proof + informal paper + verification records only, Comparator-checked).
  Axis-1/5, heavy hype-skepticism caution: self-admitted "not benchmarked on large real graphs,"
  "constants are very large," "no practical speedup is established." Opened directly via `WebFetch`
  this session. Queued, not seeded (no peer-reviewed/arXiv venue, self-admitted impracticality).
- 2026-10-08 (post date; found 2026-10-26 via today's anthropic.com/research sweep) — "The missing
  map of the sky" — https://www.anthropic.com/research/the-missing-map-of-the-sky — Brice Ménard
  (Johns Hopkins/Anthropic), with "Claude Science" coordinating many AI agents, describes building a
  claimed "first complete map of the sky in UV light" combining GALEX/Swift/FIMS-SPEAR/TD-1 data with
  a learned gap-filling model — roughly 1/3 of the map, including much of the galactic plane, is
  model-PREDICTED, not observed, plus Gaia-inferred stellar UV added on top. No arXiv preprint or
  published paper; self-published blog post only. Axis-3/5, below bar: a data/tooling showcase
  (axis-5 watch), not a peer-reviewed first-of-kind detection — "complete" refers to coverage
  including synthetic infill. Opened directly via `WebFetch` this session.
- 2026-10-23 (v1) — Braun, Machado-style follow-on extending Braun-Llibre/Llibre-Mello planar
  criteria — "Global injectivity and real Jacobian conjecture in $\mathbb{R}^n$" —
  https://arxiv.org/abs/2610.32391 — gives necessary/sufficient conditions and a new sufficient
  condition for the real Jacobian conjecture in $\mathbb{R}^n$ via weighted Poincaré compactification.
  Axis 1, below bar: a technical extension, not a resolution, of the already-tracked real-Jacobian-
  conjecture cluster — cross-referenced, not added as evidence there. Abstract verified via arXiv
  API this session.
- 2026-10-23 (v1) — "An improved upper bound on the chromatic number of the n-dimensional sphere" —
  https://arxiv.org/abs/2610.32408 — improves $\chi(S^n_R)\le(\xi_R+o(1))^n$ via recent Euclidean-
  space chromatic-number bounds. Axis 1, below bar (incremental bound, not a resolution; context-
  adjacent to the already-tracked double-cap-conjecture trend's measurable-chromatic-number
  consequence, cross-referenced not merged). Abstract verified via arXiv API this session.
- 2026-10-23 (v1) — "Finite stabilization, socle extensions, and Faith's conjecture" —
  https://arxiv.org/abs/2610.32544 — gives length-two counterexamples to several specific
  sub-questions (Bergman's Question 3.1, a semidirect-product version of Question 3.2) related to
  Faith's conjecture, but its own abstract states "The general Faith conjecture remains unresolved."
  Axis 1, below bar (partial/technical, explicitly not a resolution). Abstract verified via arXiv
  API this session.
- 2026-10-23 (v1) — "Prime Numbers of the Form $24m+1$ and Erdös-Straus Conjecture" —
  https://arxiv.org/abs/2610.32302 — gives polynomial/numerical conditions and a numerically-tested
  (not proved) partial approach toward the Erdős–Straus conjecture restricted to primes p=24m+1 (the
  only case the conjecture is open for), plus a related modular Goldbach observation. Axis 1, below
  bar: numerically-tested, not a proof. Abstract verified via arXiv API this session.
- 2026-10-24 (v1, hexagonmath.org) — Wang, Zheng, "A Counterexample to Huppert's Conjecture" —
  https://hexagonmath.org/2610.00529 — claims an explicit finite-group counterexample (an index-2
  extension G of S=PSL4(5) sharing S's full set of irreducible character degrees while G is centerless
  and not S×A for abelian A) to Huppert's conjecture. Page itself is flagged "Primarily AI-generated
  text" — heavy hype-skepticism caution, no author track record found this session, unrefereed, on
  hexagonmath.org's own no-peer-review venue. Axis 1, flag "unrefereed preprint — claim," below bar
  pending any independent engagement. Opened directly via `WebFetch` this session.
- 2026-10-23 (v1) — "The Galactic Center Gamma-Ray Excess and the Look-Elsewhere Effect" —
  https://arxiv.org/abs/2610.32845 — a methodological critique arguing part of the statistical
  significance claimed for the long-standing Galactic Center GeV excess (a standing dark-matter-
  interpretation-candidate anomaly) is attributable to the look-elsewhere effect. Axis 3, below bar
  but vetting-relevant to a standing anomaly (hype-skepticism-rule relevant) — queued for the record.
  Abstract verified via arXiv API this session.
- 2026-10-23 (v1) — "Three subpopulations of binary black holes in mass, spin magnitudes and tilts
  following GWTC-5" — https://arxiv.org/abs/2610.32935 — a population-synthesis follow-up analysis
  of the already-published GWTC-5.0 catalog, identifying three sub-populations by mass/spin. Axis 3,
  below bar (statistical follow-up on an already-catalogued dataset, not a new detection). Abstract
  verified via arXiv API this session.
- 2026-10-25 (v1) — "A proof of the Grothendieck join-meet positivity" — https://arxiv.org/abs/2610.34607
  — Guo, Kang, Liu, Xiong resolve a (signed) Grothendieck-polynomial positivity conjecture posed by
  Thomas and Yong via geometric Satake. Axis-1, below bar (specialist algebraic-combinatorics named
  conjecture, not yet judged broad/famous enough for a standalone trend). Abstract verified via
  arXiv API this session.
- 2026-10-25 (v1) — "The generalized Dixmier conjecture and the two-dimensional Jacobian conjecture"
  — https://arxiv.org/abs/2610.33919 — proves $\mathrm{JC}_2\Rightarrow\mathrm{DC}_1'$ (a reduction,
  not a resolution of either conjecture); cross-referenced to this ledger's standing Jacobian-
  conjecture/Keller-map cluster (see evidence/notes on the real-Jacobian-conjecture entries
  elsewhere in this queue). Abstract verified via arXiv API this session.
- 2026-10-26 (hexagonmath) — "A proof Gauss might have found" — https://hexagonmath.org/2610.00568v1
  — claims a proof of a Gauss class-number-one-style conjecture using only material published by
  1808. UNVERIFIED this session (title/abstract-only triage); hexagonmath-tier caution (unrefereed,
  arXiv-analog).
- 2026-10-26 (hexagonmath) — "The regular pentagonal system and the Smith–Ward problem" —
  https://hexagonmath.org/2610.00567v1 — a claimed counterexample to the operator-system
  formulation of the Smith–Ward problem. UNVERIFIED this session (title/abstract-only triage);
  hexagonmath-tier caution.
- 2026-10-26 (hexagonmath) — "Uniqueness of four-body convex central configurations for all masses"
  — https://hexagonmath.org/2610.00551v1 — claims to answer Problem 10 of Albouy–Cabral–Santos (a
  named problem from the same canonical central-configurations tradition as the already-tracked
  Smale's-sixth-problem trend); cross-referenced there as a related but distinct (4-body uniqueness
  vs. 5-body finiteness) problem. UNVERIFIED this session (title/abstract-only triage);
  hexagonmath-tier caution.
- 2026-10-26 (hexagonmath) — "Explicit Finite $p$-Group Counterexamples to the Amit–Ashurst
  Conjecture" — https://hexagonmath.org/2610.00563v1 — claims counterexamples for every prime.
  UNVERIFIED this session; hexagonmath-tier caution.
- 2026-10-26 (hexagonmath) — "The rank of $3\times3$ matrix multiplication over $\mathbb F_2$ is 23"
  — https://hexagonmath.org/2610.00548v1 — a classical open algebraic-complexity question, claims
  Lean-checked certificates. UNVERIFIED this session (title/abstract-only triage); hexagonmath-tier
  caution.
- 2026-10-26 (hexagonmath) — "Sorting networks on 13 inputs need 45 comparators" —
  https://hexagonmath.org/2610.00549v1 — claims $S(13)=45$, the 13-input case of the Bose–Nelson
  sorting-network problem. UNVERIFIED this session (title/abstract-only triage — possible overlap
  with a prior SAT-solver-based community result not checked this session); hexagonmath-tier
  caution.
- 2026-10-26 (hexagonmath) — "Area law for three-dimensional U(1) lattice gauge theory with the
  Wilson action at every coupling" — https://hexagonmath.org/2610.00552v1 — claims a long-open
  area-law result in lattice gauge theory. UNVERIFIED this session (title/abstract-only triage);
  hexagonmath-tier caution; axis 2.
- 2026-10-26 (hexagonmath) — "A modular obstruction to the $P$-adic Leopoldt conjecture for the
  Carlitz module" — https://hexagonmath.org/2610.00525v1 — claims statements by Anglès and Lucas
  fail in general. UNVERIFIED this session (title/abstract-only triage); hexagonmath-tier caution.
- 2026-10-26 (hexagonmath) — "Robin's Inequality and Superabundant Counterexamples" —
  https://hexagonmath.org/2610.00519v1 — a partial/conditional result toward the Riemann Hypothesis
  via Robin's inequality, NOT an unconditional resolution (per the feed's own characterization).
  UNVERIFIED this session; hexagonmath-tier caution.
- 2026-10-27 (v1; math category-rotation batch) — Hong, Hu, Lv, "Resolving a Problem of Lv and
  Koolen on the Smallest Eigenvalue of Distance-Regular Graphs" — https://arxiv.org/abs/2610.37010
  — answers an open eigenvalue-bound question (not a decades-old named conjecture, below the
  trend bar) in distance-regular-graph theory. Abstract + authors verified via arXiv API this
  session.
- 2026-10-27 (hexagonmath) — "The maximum Laplacian ratio of a tree: a complete answer to a
  question of Brualdi and Goldwasser, kernel-checked in Lean" — https://hexagonmath.org/2610.00565v1
  — resolves a specific named open question in spectral graph theory, Lean-checked. UNVERIFIED
  this session (title/abstract-only triage); hexagonmath-tier caution.
- 2026-10-27 (hexagonmath) — "Periodic Forcing, Echo Constraints and the Non-Periodicity of the
  Rule 30 Centre Column" — https://hexagonmath.org/2610.00573v1 — PARTIAL progress toward
  Wolfram's Rule 30 Prize Problem 1 (NKS Prize); the paper's own abstract states the key "Echo
  Lemma," and with it Problem 1 itself, "remains open" — NOT a resolution, a verified partial
  framework. Abstract opened directly via `curl` this session.
- 2026-10-27 (hexagonmath) — "Sun's supercongruence for an Apéry-like sequence" —
  https://hexagonmath.org/2610.00578v1 — a modular supercongruence result. UNVERIFIED this
  session (title/abstract-only triage); hexagonmath-tier caution.
- 2026-10-27 (hexagonmath) — "Analytic q-inequalities and a proof of Bergeron's conjecture" —
  https://hexagonmath.org/2610.00579v1 — proves a positivity conjecture on differences of
  Gaussian binomial coefficients, plus a Troyka-proposed strengthening. UNVERIFIED this session
  (title/abstract-only triage); hexagonmath-tier caution.
- 2026-10-27 (hexagonmath) — "The Generalized Vanishing Conjecture: The Two-Variable Theorem and
  the First Failing Dimension" — https://hexagonmath.org/2610.00580v1 — claims the two-variable
  case plus identifying the first dimension where a generalization fails. UNVERIFIED this
  session (title/abstract-only triage); hexagonmath-tier caution.
- 2026-10-26 (hexagonmath) — "Infinitely many elliptic curves with torsion
  $\mathbb{Z}/2\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ and rank at least six" —
  https://hexagonmath.org/2610.00586v1 — a new record/infinite family in elliptic-curve
  rank/torsion research. UNVERIFIED this session (title/abstract-only triage); hexagonmath-tier
  caution.
- 2026-10-27 (Quantum journal RSS) — "Proof of hiding conjecture in Gaussian boson sampling" —
  https://quantum-journal.org/papers/q-2026-10-27-2248/ (title opened directly via `curl` this
  session, full text not opened) — a complexity-theoretic quantum-information conjecture, axis 4.
  UNVERIFIED (title-only triage this session).
- 2026-10-29 (MathOverflow, community-pulse) — an anonymous question claims a counterexample to
  the REASONING in Theorem 6.5.4 of Skinner–Urban's "The Iwasawa Main Conjectures for GL(2)"
  (Inventiones 2014) — a landmark, heavily-cited Iwasawa-theory paper — specifically a claimed
  dimension mismatch in the isomorphism underlying Lemma 6.3.9 —
  https://mathoverflow.net/questions/516518/ (opened directly via `curl` this session, WebFetch
  blocked on this domain as before, see `logs/strategy_notes.md`). EXTREME CAUTION: brand-new
  (posted hours before this session), no answer or expert response yet, single anonymous poster —
  UNVERIFIED; a potential integrity question on an EXISTING landmark result rather than a new
  result. Watch for: any response from Skinner, Urban, or another Iwasawa-theory specialist;
  whether the claim survives scrutiny.
- 2026-10-29 (arXiv math category-rotation, Wed 10-28 batch) — Kaiyi Chen, Zeyu Wang, "Gross–Prasad
  conjecture in geometric Langlands" — https://arxiv.org/abs/2610.36377 — proves part of the global
  Gross–Prasad conjecture for G=SO_n×SO_{n-1}, H=SO_{n-1} in the unramified de Rham geometric-
  Langlands setting of Ben-Zvi–Sakellaridis–Venkatesh. Abstract + authors verified via arXiv API
  this session. Below-bar (partial case of a named conjecture, inside the broader geometric-
  Langlands program).
- 2026-10-29 (arXiv math category-rotation, Wed 10-28 batch) — George A. Elliott, Chun Guang Li,
  Zhuang Niu, "Classification of reduced free products of nuclear C*-algebras" —
  https://arxiv.org/abs/2610.36459 — extends the Elliott classification program: finite/countable
  reduced free products of unital separable nuclear UCT C*-algebras (w.r.t. faithful traces),
  after adjoining one further algebra D, are classified by the Elliott invariant. Abstract +
  authors verified via arXiv API this session. Below-bar (a classification-program extension, not
  a named open conjecture).
- 2026-10-29 (arXiv math category-rotation, Wed 10-28 batch) — Samuel J. Ferguson, Joshua Iosevich,
  "Fuglede's conjecture holds in eight dimensions over the field with two elements" —
  https://arxiv.org/abs/2610.36417 — proves Fuglede's conjecture (tile iff spectral) in the
  specific finite setting of the 8-dimensional vector space over F_2; every spectral set/tile in
  this space has a linear-subspace tiling complement. Abstract + authors verified via arXiv API
  this session. Below-bar (a specific finite case of a famous conjecture already known false in
  general; not the general conjecture).
- 2026-10-29 (arXiv math category-rotation, Wed 10-28 batch) — Zhang, Xu, Li, Sarkar, Sun,
  Viswanathan, "Agentic Swarms Discover Enhancement of Fractional Chern Insulator Gaps Beyond
  Ideal Quantum Geometry" — https://arxiv.org/abs/2610.35934 — axis-3 condensed-matter result
  (enhancing fractional-Chern-insulator energy gaps, relevant to anyon robustness at higher
  temperature) obtained via MOSAIC, a multi-agent AI-swarm (Claude Opus 5.5) open-ended-discovery
  system — AXIS-5 WATCH overlap (note the AI-assistance, track the PHYSICS result, not the
  method). Abstract + authors verified via arXiv API this session. Below-bar single result.
- 2026-10-29 (Quantum journal RSS) — "A Counterexample to the Optimality Conjecture in Convex
  Quantum Channel Optimization" — https://arxiv.org/abs/2512.22863 (journal publication
  2026-10-28) — disproves a 2021 conjecture (Coutts et al., Quantum 5, 448) on trace-distance-
  based optimal state transformation, via an explicit 2-dimensional counterexample. Abstract
  verified via arXiv API this session. Axis-4, below-bar (a technical, narrowly-scoped conjecture,
  now peer-reviewed published).
- 2026-10-29 (Terence Tao's blog, opened directly this session) — Daniel Carter, Kevin O'Bryant,
  Terence Tao, "On the diameter and distribution of Sidon sets" — https://arxiv.org/abs/2610.36207
  — improves the best known upper bound on the maximum size of a Sidon set in {1,...,N} (Erdős
  problem #30), continuing a sequence of constant-factor refinements an "optimization constants"
  repository has tracked; stems from an AlphaEvolve-assisted exploration begun on Tao's blog last
  year (the final method does not itself use 2026-era AI tools). Abstract + authors verified via
  arXiv API this session. Below-bar (a quantitative improvement, not a resolution of the
  Erdős–Turán conjecture itself).
- 2026-10-29 (hexagonmath.org /rss/all, Wed-Thu batch) — Mark Kisin (submitter), "Serre's
  conjecture on the Artin character for a regular local ring" — https://hexagonmath.org/2610.00597v1
  — proves the conjecture for a finite group G acting on a regular local ring A with ISOLATED
  FIXED POINTS (positive-characteristic case credited to Abe; new contribution is mixed
  characteristic, via equivariant deformation + Beraldo–Pippi's twisted conductor formula) — not a
  full resolution. AI-assisted: provenance statement says GPT Astra was used extensively for the
  proof search and first draft, with significant human checking by Kisin (a prominent arithmetic
  geometer, Harvard). Abstract read directly via WebFetch this session; hexagonmath-tier
  unrefereed-preprint caution applies regardless of the named author.
- 2026-10-29 (found via AxiomMath's publications index, opened this session per Amendment M —
  the 10-28 staging run had only opened the two triggering CFSG pages, not the org's own
  publications index; closing that gap one day late) — Vasily Ilin, Ken Ono, "Ternary polynomial
  relations and periods of cusp forms" — https://arxiv.org/abs/2610.19309 — resolves the
  Bachmann–van Ittersum conjecture (ternary polynomial relations) over every field of
  characteristic zero, identifying all homogeneous solutions and linking them to binary period
  polynomials. Human authors (no AI-assistance flag in the abstract); listed by AxiomMath as one
  of its own publications without further explanation. Abstract + authors verified via arXiv API
  this session.
- 2026-10-29 (AxiomMath publications index) — Angdinata, Lau, Ono, Swaminathan, Vemulapalli,
  "Local Factors in the BSD Conjecture: A Unified Statistical View" —
  https://arxiv.org/abs/2610.10243 — a statistical/distributional study of Tamagawa numbers for
  elliptic curves over Q (limiting distributions, covariances, moment/tail bounds), not a proof or
  disproof of BSD itself. Abstract + authors verified via arXiv API this session. Below-bar.
- 2026-10-29 (AxiomMath publications index) — Kenny Lau / AxiomProver, "Explicit Positive Lower
  Density for the Collatz Conjecture" — https://hexagonmath.org/2610.00249v1 — an explicit (but
  astronomically small) positive-lower-density refinement of an earlier Collatz-trajectory-length
  result by Lech Mazur; a density result, NOT a proof of the Collatz conjecture. AI-assisted:
  provenance statement says AxiomProver (the AxiomMath formal system, same org behind the CFSG-in-
  Lean claim above) autonomously produced the mathematics and its Lean formalization. Abstract
  read directly via WebFetch this session.
- 2026-10-29 (hexagonmath.org /rss/all) — Qiyue Tang, "A note of the Gorenstein symmetry
  conjecture (II)" — https://hexagonmath.org/2610.00540v1 — proves the Gorenstein symmetry
  conjecture for finite-dimensional split square-zero extensions of algebras derived-equivalent to
  hereditary algebras — a narrow special case, not a general resolution. AI-assisted (extracted
  from multi-turn AI conversations, adversarially AI-reviewed). Abstract read directly via WebFetch
  this session.
- 2026-10-29 (arXiv math category-rotation, Wed 10-28 batch) — Elżbieta Adamus, Zbigniew Hajto,
  "The Legendre potential and the gradient case of the differential Galois criterion for the
  Jacobian Conjecture" — https://arxiv.org/abs/2610.36736 — continues this ledger's standing
  Jacobian-Conjecture/Keller-map cluster (observation_queue, since 2026-07): in the GRADIENT case,
  reduces the differential-Galois criterion's n membership conditions to a single one. Ordinary
  human mathematics, not AI-attributed. Abstract + authors verified via arXiv API this session.
  Below-bar incremental technical progress (not itself a resolution/counterexample).
- 2026-10-30 (arXiv math category-rotation, Thu 10-29 batch) — Dongjian Wu, Nantao Zhang, "The
  Kawatani–Okawa conjecture in dimensions three and four" — https://arxiv.org/abs/2610.39838 —
  proves smooth projective 3- and 4-folds with no nontrivial semiorthogonal decomposition have nef
  canonical divisor, confirming the conjecture in these dimensions only (not the general case).
  Abstract + authors verified via arXiv API this session. Below-bar partial progress.
- 2026-10-30 (arXiv math category-rotation, Thu 10-29 batch) — Kaiwen Yang, "Petty's
  equilateral-set conjecture in dimension five" — https://arxiv.org/abs/2610.39967 — proves every
  5-dimensional real normed space contains 6 equidistant points, extending Petty's/Makeev's dim-3/4
  results by one more dimension (general n-dimensional case remains open). Abstract + authors
  verified via arXiv API this session. Below-bar partial progress, incremental sequence.
- 2026-10-30 (hexagonmath.org `/rss/all`, opened directly) — Zeng Chunping, "A lattice-theoretic
  approach to the abc conjecture: Weighted arithmetic derivatives, a master inequality, and the
  structure of the residual family" — https://hexagonmath.org/2610.00630v1 (v1, 2026-10-28/29) —
  a CONDITIONAL partial result (limsup q≤2 under an explicit unproven gap hypothesis; unconditional
  only for the special case a+b=r^e); the author explicitly states "no claim of a proof of the abc
  conjecture is made" and that the full conjecture is "structurally unreachable inside this
  framework." Below-bar by its own author's framing. Abstract read directly via WebFetch this
  session.
- 2026-10-30 (hexagonmath.org `/rss/all`, opened directly) — Zeng Chunping, "An Integral-Structure
  Inflation in the Hull Operation of IUT Corollary 3.12" — https://hexagonmath.org/2610.00646v1
  (v1, 2026-10-29) — identifies a THIRD independent gap claim in the step from Mochizuki's IUT
  Theorem 3.11 to Corollary 3.12 (the step IUT needs to derive the abc conjecture), alongside the
  established Scholze–Stix critique (2018) and a compatibility gap reported by the "LANA project"
  — argues the hull-operation's integral-structure inflation grows doubly-exponentially and alone
  would block Corollary 3.12 regardless of the other two gaps. Author states "this paper is not a
  verdict on IUT." No independent IUT/abc trend exists yet on this ledger (first capture of this
  long-running controversy) — flagged for the weekly to assess whether 3 independent gap-critiques
  (Scholze-Stix, LANA, this one) now clear the convergence bar for a dedicated "IUT/abc vetting
  status" trend. Abstract read directly via WebFetch this session.
  - 2026-W44 recalibration: NOT PROMOTED to a trend this session — of the three named gap-critiques,
    only Zeng's (this item) has an actual primary URL opened and verified by this radar; the
    Scholze–Stix 2018 report and the "LANA project" compatibility-gap report are named only via
    Zeng's own characterization, with no independently-opened primary on file (the hard evidence
    rule: cite only URLs actually opened this/a prior session). Held as a queue item pending a
    session that directly locates and opens the Scholze–Stix report and the LANA project's own
    write-up — only then would this cluster have ≥3 independently-verified sources + artifacts and
    clear the trend bar. Not a landmark single result either (a 2010s-vintage ongoing controversy,
    not a new 2026 landmark), so the domain-cadence seed-bar adaptation doesn't apply on its own.
- 2026-10-30 (community pulse, Hossenfelder's "Backreaction" blog/video, 2026-10-28) — UNVERIFIED,
  no primary located: "Large Hadron Collider Sees Extra Dimension, Physicists Claim" reports that
  "two physicists in France say they have spotted something odd in data from the Large Hadron
  Collider" (a heavy-particle signal suggestive of an extra spatial dimension), but the post names
  no authors, institution, or paper, and contains no link to one; INSPIRE-HEP and arXiv
  (hep-ph/hep-ex, keyword + recent-date searches) this session found no matching candidate paper.
  Secondary-source-only per the hard rules — cannot cite as evidence until the primary is located.
  Flagged for next session: re-check INSPIRE/arXiv and other physics-news outlets for the
  underlying paper/preprint.
- 2026-11-03 — https://arxiv.org/abs/2611.02454 — Iosevich, Yavicoli, "The geometric case of the
  Erdős Similarity Conjecture. A human exposition of the OpenAI proof": a detailed human
  exposition (finite probability + basic measure theory) of one specific named result within
  OpenAI's Oct 6 mass disclosure (not yet individually captured on that trend) — a positive-
  measure subset of $[0,1]$ avoiding every translate/dilate of $\{q^n\}$. Below the split-trend
  bar (one exposition so far, cf. Harary-Hill's two); part of the already-tracked OpenAI
  mass-disclosure wave. Abstract/authors verified via arXiv API this session.
- 2026-11-03 — https://arxiv.org/abs/2611.03572 — Bernal-González, Calderón-Moreno, Prado-Bassas,
  "Counterexamples to the Jacobian Conjecture from the viewpoint of lineability": studies the
  algebraic genericity (affine-coneability, 1- but not 2-lineability) of the polynomial
  counterexample family to the already-queued Jacobian Conjecture ($N\ge3$, 2026-07). A follow-up
  analysis of the existing cluster, not a new independent artifact. Abstract/authors verified via
  arXiv API this session.
- 2026-11-03 — https://hexagonmath.org/2611.00026 — "Iterating the
  Gupta–Ndiaye–Norin–Wei method: a computer-verified bound $R(k)\le 3.7698^{k+o(k)}$": a Ramsey-
  number UPPER-bound improvement (distinct sub-axis from the tracked LOWER-bound trend above;
  computer-verified, unrefereed hexagonmath preprint). Title verified via direct page fetch this
  session.
- 2026-11-03 — https://arxiv.org/abs/2611.05300 — Aichholzer, Dorfer, Kramer, Rieck, Vogtenhuber,
  "Counterexamples to the Happy Edge Conjecture in Plane Spanning Trees": disproves a folklore
  conjecture (computationally verified for small cases) about flip-graph reconfiguration of plane
  spanning trees. Below the landmark bar (folklore, not individually named/attributed). Abstract/
  authors verified via arXiv API this session.
- 2026-11-03 — https://arxiv.org/abs/2611.02544 — Santiago Pineda Montoya, "Counterexamples to a
  Cubic Nondegeneracy Conjecture": disproves a Morier-Genoud–Ovsienko conjecture on cubic Boolean
  generating functions. Below the landmark bar (specialized, niche subfield). Abstract/author
  verified via arXiv API this session.
- 2026-11-03 — https://arxiv.org/abs/2611.03151 — Hu, Li, "Counterexamples to Relaxed
  Multiplication in List Coloring": answers a 2019 Jiang–Zhu question negatively. Below the
  landmark bar. Abstract/authors verified via arXiv API this session.
- 2026-11-03 — https://arxiv.org/abs/2611.02719 — Xu, Hu, "A counterexample to a three-step
  convergence bound for BFGS with exact line search": disproves a numerical-optimization error
  estimate. Below the landmark bar (axis-adjacent, math.OC). Abstract/authors verified via arXiv
  API this session.
- 2026-11-03 — several below-bar hexagonmath.org items from today's `/rss/all` sweep (new since
  the 2026-11-02 cutoff at 2611.00019): "Hecke eigenvalues in level 1 modulo powers of 2 and 3:
  Hatada's question (1981) and the Coleman-Stein conjecture" (2611.00035 — answers Hatada's 1981
  question and gives an independent proof of the level-1 Coleman–Stein case, but explicitly notes
  both "also follow from Rustom's recent classification," i.e. not the first proof); "A Bound
  Helium Dianion Does Not Exist" (2611.00041, atomic physics, axis 3); "The binary Collatz
  dynamics of the trinomials $x^n+x+1$: proof of two conjectures of Gallardo and Rahavandrainy"
  (2611.00031). All unrefereed hexagonmath preprints, below the landmark bar; titles/descriptions
  verified via direct page fetch this session.
- 2026-10-30 — https://news.fnal.gov/2026/10/the-sbnd-collaboration-releases-first-neutrino-results/
  — "The SBND collaboration releases first neutrino results": the Short-Baseline Near Detector's
  first result, improving neutrino-interaction modeling ahead of DUNE — an experimental milestone,
  not yet a landmark discovery. Opened directly via the Fermilab RSS feed this session.
  **UNDERLYING PAPER LOCATED 2026-11-10 (closes the 11-09 daily's standing chase):
  arXiv:2610.39042 — "Measurements of transverse kinematic imbalance in muon neutrino
  charged-current interactions on argon with a single proton and no pions in the final state
  with SBND" (SBND Collaboration, v1 2026-10-28, submitted to PRL) — 12,804 signal candidates at
  91% purity; no event-generator model describes all three kinematic-imbalance variables.
  Abstract verified directly via arXiv (plain `curl`, the API's `search_query` endpoint was
  429-rate-limited all session) this session.**
- 2026-11-07 — https://arxiv.org/abs/2611.11615 and https://arxiv.org/abs/2611.11620 — two
  independent follow-up papers ("what survives" Talenti-type rigidity theorems, one planar, one
  valid in every dimension $N\ge2$) on the already-queued 2026-08 Pompeiu/Schiffer-conjecture
  computer-assisted counterexamples (arXiv:2608.01579, 2608.05114) — axis 1, analysis/spectral
  geometry. Not new counterexamples; below-bar incremental follow-on. Abstracts verified via
  direct arXiv `/abs/` fetch this session.
- 2026-10-28 — https://quantum-journal.org/papers/q-2026-10-28-2253/ — "A Counterexample to the
  Optimality Conjecture in Convex Quantum Channel Optimization": disproves a 2021 Coutts et al.
  conjecture on trace-distance-optimal state transformation (axis 4, quantum information). Opened
  directly via the Quantum journal RSS feed this session.
- 2026-11-03 — https://arxiv.org/abs/2611.05174 — "Evidence for a Dirac Spin Liquid in the Kagome
  Heisenberg Antiferromagnet from High-Precision Neural-Network Quantum States": numerical
  (not experimental) evidence for a long-sought quantum spin-liquid phase via neural-network
  quantum-state simulation (axis 3, condensed matter theory). Abstract/title verified via arXiv
  API this session.
- 2026-11-07 — https://arxiv.org/abs/2611.11002 — Michailidis, "The Herzog–Schönheim Conjecture
  for Solvable Groups": proves the 1958 Herzog–Schönheim conjecture (coset-partition indices
  can't all be distinct) for all solvable groups, finite or infinite — the general conjecture
  (arbitrary groups) remains open. Axis 1, group theory. Abstract verified via direct arXiv
  `/abs/` fetch this session.
- 2026-11-08 — https://arxiv.org/abs/2611.11250 — "Rayleigh's conjecture in dimensions four and
  five": proves the 1894 clamped-plate Rayleigh conjecture in two new dimensions via a sharp
  comparison with the first Dirichlet eigenvalue; higher dimensions remain open. Axis 1,
  spectral geometry/analysis. Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-07 — https://arxiv.org/abs/2611.10978 — "Unramified case of Colliot-Thélène conjecture
  on quadratic forms": proves the conjecture for semilocal regular domains geometrically regular
  over a DVR with 2 invertible (incl. unramified mixed-characteristic local rings) — a restricted
  case, general conjecture open. Axis 1, algebraic geometry/quadratic forms. Abstract verified
  via direct arXiv `/abs/` fetch this session.
- 2026-11-08 — https://arxiv.org/abs/2611.11128 — "Triangle-overlap cores and density bounds for
  Tuza's conjecture": proves $\tau(G)\le2\nu(G)$ under bounded-triangle-multiplicity and
  max-average-degree conditions — a conditional density bound, not a general resolution. Axis 1,
  extremal graph theory. Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-08 — https://arxiv.org/abs/2611.11404 — "Revisiting the conjectures of Shapiro and
  Schanuel": shows Shapiro's conjecture (on common zeros of exponential polynomials) follows from
  the still-unproved Schanuel's conjecture — a conditional implication, not an unconditional
  resolution. Axis 1, number theory/transcendence. Abstract verified via direct arXiv `/abs/`
  fetch this session.
- 2026-11-08 — https://arxiv.org/abs/2611.11589 — "$C_{st}$-conjecture for compactly supported
  pro-étale cohomology": proves the étale-de Rham direction only, for smooth partially proper
  rigid analytic varieties over mixed-characteristic local fields. Axis 1, arithmetic geometry/
  p-adic Hodge theory. Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-09 — https://arxiv.org/abs/2611.11945 — "Rigidity and existence of profiled expansive
  solutions of the $N$-body problem with homogeneous potentials": asymptotic rigidity results and
  power-log expansions for expansive $N$-body solutions, extending Chazy's classical Newtonian
  result to general homogeneous potentials. Axis 1/2, celestial mechanics/dynamics (adjacent to
  the standing Smale's-sixth-problem seed trend, but a different sub-problem — not folded in as
  evidence). Abstract verified via direct arXiv `/abs/` fetch this session.
- PROMOTED 2026-11-17 (reconciliation under the W46-ratified fame/recency-blind seed bar): this
  2026-11-10 item (Muyan Jiang, "A proof of the constant-width numerical range conjecture,"
  arXiv:2611.13461, proving the Chien–Nakazato–Meng conjecture) was held below-bar under the OLD
  standard ("narrower/less-established named conjecture... pending wider significance signal") —
  a full resolution of a genuinely named conjecture now seeds regardless of fame per the ratified
  bar. See the new "Proof of the Chien–Nakazato–Meng constant-width numerical range conjecture"
  trend above. Cleared from this queue.
- 2026-11-10 — https://arxiv.org/abs/2611.13745 — Chen, Lan, Liu, "The anisotropic De Giorgi
  conjecture in $\mathbb R^4$": one-dimensional symmetry for entire solutions of the anisotropic
  Allen–Cahn equation under a limiting assumption. Axis 1/2, PDE/geometric analysis; a restricted
  case (anisotropic variant, dimension 4, limiting assumption), not an unconditional resolution.
  Abstract verified via direct arXiv `/abs/` fetch this session.
- 2026-11-10 — https://hexagonmath.org/2611.00285v1 — "Watkins's Conjecture for Elliptic Curves
  with Rational Two-Torsion": proves the modular degree of $E/\mathbb Q$ with $E(\mathbb Q)[2]\ne0$
  is divisible by $2^{\operatorname{rank}E(\mathbb Q)}$ — the rational-2-torsion case only, not the
  general conjecture. Axis 1, arithmetic geometry. Opened directly via page fetch this session.
- 2026-11-10 — https://hexagonmath.org/2611.00260v1 — "The Cereceda (2007) conjecture holds for
  bipartite 2-degenerate graphs": settles the $d=2$ bipartite case of the recolouring-diameter
  conjecture, not the general-$d$ conjecture. Axis 1, combinatorics. Opened directly via page
  fetch this session.
- 2026-11-10 — https://hexagonmath.org/2611.00266v1 — "A Counterexample to the Subtraction-Free
  Conjecture for Bounded Ratios of Minors": disproves the Boocher–Froehle subtraction-free
  conjecture via an explicit order-3207 minor construction. Axis 1, combinatorics/total
  positivity; full disproof of a named conjecture, held at queue (not seed) given its narrower
  profile — flag for weekly reconsideration against the generous seed bar applied elsewhere this
  session. Opened directly via page fetch this session.
- 2026-11-10 — https://hexagonmath.org/2611.00275v1 — "The Schur–Siegel–Smyth trace problem: the
  lower bound 1.8022246": a numerical improvement on the famous still-open trace problem, not a
  resolution. Axis 1, number theory. Opened directly via page fetch this session.
- 2026-11-10 — https://arxiv.org/abs/2611.13606 — Bruce Zimov, "A Threshold-Crossing Condition for
  the Least Colossally Abundant Counterexample to Robin's Inequality": a structural/conditional
  constraint on a hypothetical counterexample to Robin's inequality (equivalent to RH on colossally
  abundant numbers), not itself a resolution. Axis 1, analytic number theory. Abstract verified via
  direct arXiv `/abs/` fetch this session.
- 2026-11-10 — https://news.fnal.gov/2026/11/worlds-largest-neutrino-experiment-begins-construction-a-mile-underground-in-us/
  — DUNE (Deep Underground Neutrino Experiment): Fermilab, CERN, and SURF begin construction of the
  cryostats housing ~17,000 tons of liquid argon for the far detector, nearly a mile underground at
  SURF (South Dakota) — a major facility-construction milestone, not yet a physics result. Axis 3,
  neutrino/collider-adjacent experimental physics. DUNE was a long-standing "(agent: add...)"
  candidate in SOURCES.md's Experiments block; promoted to a tracked entry this session (see
  SOURCES.md). Opened directly via `tvly extract` this session.
- 2026-11-11 — https://arxiv.org/abs/2611.13266 — Croft, García-Moreno, Pani, "Challenging the
  hoop conjecture with spinning pancakes and baguettes": tests (not resolves) Thorne's hoop
  conjecture on axisymmetric rotating-dust initial data; finds it holds (within ~14-25% depending
  on the mass definition used) for the configurations studied. Axis 3, numerical general
  relativity. Below bar (a numerical test, not a resolution). Abstract verified via direct arXiv
  page fetch this session.
- 2026-11-11 — https://arxiv.org/abs/2611.13910 — Dai, Zhao, "Pólya's conjecture for hyperbolic
  balls and Berezin–Li–Yau type inequalities": proves shifted Dirichlet-Pólya/Berezin–Li–Yau
  inequalities for hyperbolic balls, giving a concrete domain family satisfying Laptev's 2023
  conjectures, plus a global estimate toward a 1996 Strichartz conjecture. Axis 1, spectral
  geometry. Below bar (a specific domain family, not the general conjectures; Laptev's
  conjectures are only 3 years old, not long-standing). Abstract verified via direct arXiv page
  fetch this session.
- 2026-11-11 — https://arxiv.org/abs/2611.14161 — Shilun Wang, "Sun's conjecture on a certain
  ternary quadratic form": proves an asymptotic (sufficiently-large-integer) form of one of
  Zhi-Wei Sun's representation conjectures via the Shimura lift/Waldspurger's formula. Axis 1,
  number theory. Below bar (asymptotic, not a fully effective resolution). Abstract verified via
  direct arXiv page fetch this session.
- 2026-11-11 — https://arxiv.org/abs/2611.13226 — de Winter, Tokarsky, "Unilluminable rooms:
  minimal examples, classifications and exceptions": new vertex-minimal "lattice room"
  constructions extending Tokarsky's classical mutually-invisible-points problem, with exhaustive
  computer-search-based classifications. Axis 1, discrete geometry. Below bar (a construction/
  classification extension, not a named-conjecture resolution). Abstract verified via direct
  arXiv page fetch this session.
- 2026-11-11 — https://arxiv.org/abs/2611.14144 — Shen, Su, "Linear circle quotients of products
  of odd-dimensional spheres: classification and geometric applications": classifies orbit
  manifolds of free diagonal circle actions on $S^{2n+1}\times S^{2n+1}$, with applications to
  moduli spaces of Einstein metrics and Sasakian structures. Axis 1, geometry/topology. Below bar
  (a classification result, not a named-conjecture resolution). Abstract verified via direct
  arXiv page fetch this session.
- 2026-11-11 — https://arxiv.org/abs/2611.14367 — Geunho Lim, "No 13-vertex triangulation of the
  three-torus": excludes the 13-vertex case of Lutz's conjecture that Kühnel–Lassmann's 15-vertex
  triangulation is vertex-minimal (14-vertex case remains open). Axis 1/5, combinatorial topology.
  Below bar (partial — one of two remaining cases). Abstract verified via direct arXiv page fetch
  this session.
- 2026-11-11 — https://arxiv.org/abs/2611.13208 — Valeriano Aiello, "Thompson indices of knots and
  the invertibility problem": computes four Thompson-group knot indices for all prime knots up to
  13 crossings; finds hundreds of non-invertible knots distinguishable by these indices, incl.
  the Conway knot vs. its Kinoshita–Terasaka mutant. Axis 1, knot theory. Below bar (a
  computational enumeration, not a named-conjecture resolution) — candidate study-shelf item for a
  future session. Abstract verified via direct arXiv page fetch this session.
- 2026-11-11 — https://arxiv.org/abs/2611.14234 — Alexander Klotz, "LLM-Assisted Advances in the
  Ropelength Problem": axis-5 AI-WATCH, ordinary-math result. Improves the universal ropelength
  lower bound (crossing-number exponent 3/4) from $L\ge1.105C^{3/4}$ to $L\ge2.0996C^{3/4}$ and
  gives a new ropelength-vs-stick-number bound, with the assistance of "ChatGPT-5.6 Luna" (a
  consumer-facing OpenAI model name not previously seen on this ledger — distinct from the
  internal Astra/Sol models of the mass-disclosure trend). Author states the LLM could not help
  with several other sub-problems. Below bar (incremental numerical improvement). Abstract
  verified via direct arXiv page fetch this session.
- 2026-11-12 — https://hexagonmath.org/2611.00339v1 — Manvir Jaswal, "An effective André–Oort
  theorem for Shimura varieties": gives effective (explicit) bounds for special subvarieties in
  Shimura varieties, CONDITIONAL on a zero-free-region result of Cureton–Thorner (already staged
  in SOURCES.md's hexagonmath promotion note, Lean-formalized). Axis 1, arithmetic geometry. Below
  bar (the qualitative André–Oort theorem was already resolved ~2014; this is a conditional
  effectivization, not a first resolution). Opened and read via the hexagonmath `/rss/all` feed
  this session.
- 2026-11-12 — https://hexagonmath.org/2611.00321v1 — Goldstein, Guevara, "Osterwalder–Schrader
  axioms for scalar QED$_3$ in the Higgs phase": a rigorous constructive-QFT result verifying the
  Osterwalder–Schrader axioms for the 3D lattice abelian Higgs model in the continuum limit. Axis
  2, mathematical physics (constructive field theory is a rare, high-rigor sub-area). Below bar
  (no named-conjecture resolution claimed) but a solid candidate for a future study pick. Opened
  and read via the hexagonmath `/rss/all` feed this session.
- 2026-11-12 — https://hexagonmath.org/2611.00344v1 — Sunay Venkat, "Exact projector-rank
  thresholds for state-independent contextuality": constructs, for every rank $r$, an exclusivity
  graph exhibiting state-independent contextuality only at rank $r$ and above. Axis 4, quantum
  foundations. Below bar (a construction, not a named-conjecture resolution). Opened and read via
  the hexagonmath `/rss/all` feed this session.
- 2026-11-12 — https://hexagonmath.org/2611.00329v1 — Antony Lewis, "Genuinely multipartite bound
  entanglement of three qubits": exhibits a three-qubit PPT state whose entanglement is bound
  under all three bipartitions yet is genuinely multipartite. Axis 4, quantum information/
  foundations. Below bar (a construction, not a named-conjecture resolution). Opened and read via
  the hexagonmath `/rss/all` feed this session.
- 2026-11-12 — https://hexagonmath.org/2611.00320v1 — Zhang, Xuan, "An Elementary Proof of
  Fundamental Theorem of Algebra over Rationals": axis-5 AI-WATCH ("with the aid of AI," unnamed
  model) — a constructive/elementary proof that for a nonconstant rational-coefficient polynomial
  and any rational $\varepsilon>0$, a rational complex number exists with $|Q(f(z))|<\varepsilon$.
  Below bar (an elementary/alternative proof technique, not a new result). Opened and read via the
  hexagonmath `/rss/all` feed this session.
- 2026-11-11 — https://arxiv.org/abs/2611.14512 — Bajaj, Lin, "Solving the SU(2) BFSS model": a
  NUMERICAL (not closed-form) ground-state and scattering-amplitude study of the SU(2) BFSS
  matrix model, confirming bound states "closely related to the bound states whose existence
  was recently discovered by OpenAI." Axis 2, string/M-theory (BFSS matrix model). Below bar
  (numerical study); the referenced OpenAI bound-state discovery is NOT yet independently
  located/verified this session — chase next session (check the already-tracked OpenAI
  mass-disclosure trend and openai.com/research for a BFSS/matrix-model item). Abstract verified
  via direct arXiv page fetch this session.
- 2026-11-12 (unverified, primary not located this session) — Sabine Hossenfelder's blog
  ("Backreaction"), "Something Isn't Adding Up in Particle Physics": reports a long-standing
  anomaly in particles containing bottom quarks that has grown to 4.8σ, "just short of a
  discovery" — likely a continuation of the LHCb/Belle II B-meson lepton-flavor-universality
  anomaly saga, but the post names neither the experiment/collaboration nor an arXiv id, and no
  matching primary was found via INSPIRE-HEP or `tvly search` this session. Axis 3, experimental
  HEP. Community-pulse intake only — chase the underlying collaboration paper next session
  (candidate search terms: LHCb/Belle II, "4.8 sigma", B-meson anomaly, 2026).
  SECOND CHASE ATTEMPT 2026-11-13: `tvly search`/INSPIRE-HEP again found only the same social
  pointer, nLab background, and unrelated ATLAS/B-meson coverage — still no specific matching
  collaboration paper/arXiv id. Not yet heal-owed (a chase-method, not a source-access, failure);
  try a different primary-source class next (LHCb's own publication page / INSPIRE
  author-list search) per the W45 self-amendment proposal on this exact failure pattern.
- 2026-11-13 — Euclid (ESA) Data Release 1 — https://arxiv.org/abs/2611.16510 (Euclid
  Collaboration, "Euclid Data Release 1 (DR1) - Data release overview") plus 8 companion
  instrument/calibration/processing papers same day (astrometric calibration, photometric masks,
  Science Ground Segment architecture, NIR processing, PHZ galaxy-properties pipeline, external
  imaging colouring, spacecraft performance, calibration strategy) — Euclid's first major public
  data release, a flagship ESA dark-energy/cosmology survey mission. Below the landmark bar as
  caught (an infrastructure/data-release overview, not yet a specific discovery claim built on
  the data) but a significant axis-3 event worth tracking for follow-on science results. Overview
  paper's abstract/authors verified via arXiv API this session; companion papers title-triaged
  only. SOURCE-DISCOVERY: Euclid/ESA is not yet in SOURCES.md's Experiments block (alongside
  LIGO/DESI/CERN/IceCube/LZ/DUNE) — staged in SOURCES.md → "Discovered-source candidates" this
  session.
- 2026-11-13 — hexagonmath.org `/rss/all` batch, below-landmark-bar progress on named open
  problems (grouped, all opened/read this session, none independently assessed for correctness):
  "A thrackle on n vertices has fewer than 4n/3 edges" (https://hexagonmath.org/2611.00383v1,
  progress toward the thrackle conjecture's n-edge bound, not a resolution); "The kissing numbers
  in dimensions five and seven are at most 43 and 132" (https://hexagonmath.org/2611.00376v1, new
  upper bounds on the kissing-number problem, exact values remain open in these dimensions); "A
  lower bound of 0.8366 for Lebesgue's universal covering problem"
  (https://hexagonmath.org/2611.00382v1, incremental bound improvement on a famous open
  covering-constant problem); "The Steiner ratio is at least 0.8564"
  (https://hexagonmath.org/2611.00379v1, lower-bound progress on the Gilbert–Pollak/Steiner-ratio
  conjecture, conjectured value √3/2≈0.866); "The automorphism group of an extremal [72,36,16]
  code is trivial" (https://hexagonmath.org/2611.00380v1, rules out nontrivial automorphisms for
  the long-studied, still-unresolved extremal-code-existence question in coding theory). All five
  are genuine incremental progress on named/famous open problems, not full resolutions — below the
  domain-cadence landmark bar, queued rather than seeded.
- 2026-11-13 (capture-leak backfill, found via today's axiommath.ai/research/ blog-index sweep) —
  Evan Chen, Ken Ono, et al. (20 authors), "Almost all primes are partially regular" —
  https://arxiv.org/abs/2602.05090 (v1, 2026-02-04) — proves a density-one subset of odd primes
  is "partially regular" (a bound on vanishing Galois eigenspaces of cyclotomic class groups),
  yielding a PARTIAL (density-one, not universal) Vandiver Theorem via Leopoldt reflection —
  genuine progress toward Vandiver's conjecture (a famous open problem in Iwasawa theory) but not
  a full resolution. Fully Lean/Mathlib-formalized, "produced automatically by AxiomProver from a
  natural-language statement," with Ken Ono (a leading number theorist) among the human
  co-authors — the same credible-coauthor pattern already tracked elsewhere for this
  AxiomMath/Ono collaboration. Below the landmark bar (partial, not full, resolution) — this item
  sat uncaptured for ~9 months (predates this radar). Abstract/authors verified via arXiv API
  this session.
- 2026-11-13 — https://hexagonmath.org/2611.00373v1 — "Re-proving native_decide facts in Lean's
  kernel: a study of 16 public packages and a converter": axis-5 WATCH (formal-proof tooling
  integrity) — surveys whether `native_decide`-dependent facts across 16 public Lean packages can
  be re-proved via the kernel directly, with a converter tool; relevant background for this
  ledger's own reliance on "sorry-free"/"kernel-checked" Lean claims as a vetting signal. Below
  bar (a tooling study, not a new mathematical result). Opened and read via the hexagonmath
  `/rss/all` feed this session.
- 2026-11-12 (v2 revision resurfaced in today's RSS batch; accessed 2026-11-16) — Jingyin Huang,
  "Bestvina metric and tree reduction for $K(\pi,1)$-conjecture" — https://arxiv.org/abs/2602.17982
  — and Nima Hoda, Jingyin Huang, "From Trees to Tripods: Proof of $K(\pi,1)$ for Artin groups
  with $ABI$-type spherical parabolics" — https://arxiv.org/abs/2602.17983 — two related Feb 2026
  papers reducing the 50+-year-old $K(\pi,1)$-conjecture for Artin groups (geometric group theory)
  to tree-type Coxeter diagrams, then proving it for a specific subclass (ABI-type spherical
  parabolics). PARTIAL resolution only (not all Artin groups) — below the landmark bar. Abstracts/
  authors verified via arXiv API this session.
- 2026-08-17 (resurfaced in today's RSS batch; accessed 2026-11-16) — Longfei Fang, Mingqing Zhai,
  Yuhan Zhang, "The Brualdi–Hoffman–Turán problem for odd wheels: Resolving a conjecture of Yu, Li
  and Peng" — https://arxiv.org/abs/2608.16127 — resolves a research-level (not decades-old-named)
  spectral-graph-theory conjecture for odd-wheel-forbidding graphs. Below the landmark bar (narrow
  sub-conjecture, not a long-standing famous problem). Abstract/authors verified via arXiv API
  this session.
- 2026-11-03 — Olivia Aubone, José Iovino, "Every obstruction to noncontextual hidden variables is
  finite: well-founded refutations in infinitary real-valued logic" —
  https://arxiv.org/abs/2611.05656 — axis-4 quantum-foundations result on contextuality
  obstructions, in infinitary real-valued logic. Below bar (a general structural theorem, not a
  named-conjecture resolution) but genuinely on-axis foundational content. Abstract/authors
  verified via arXiv API this session.
- 2026-11-13 — Guoxing Ji, "A counterexample to Arveson's finiteness question for subdiagonal
  algebras" — https://arxiv.org/abs/2611.17636 — operator-algebras counterexample (von Neumann
  factor subdiagonal algebras); distinct from the already-tracked Arveson's hyperrigidity
  counterexample (2026-10-19 entry). Below bar (a "question," not a long-standing named
  conjecture, and narrow). Abstract/author verified via arXiv API this session.
- 2026-10-30 — LHCb Collaboration, "Evidence for the decay $B^0\to\mu^+\mu^-$ and improved
  measurements of the decay $B^0_s\to\mu^+\mu^-$" — https://arxiv.org/abs/2611.00230 — first
  single-experiment EVIDENCE (not yet 5σ discovery) for the rare decay $B^0\to\mu^+\mu^-$, plus
  the world's most precise $B^0_s\to\mu^+\mu^-$ measurements; all results consistent with the
  Standard Model (no anomaly). Below bar (evidence-tier, not discovery-tier; no deviation from
  SM). Abstract/authors verified via arXiv API this session.
- 2026-11-11 — Peter Woit's "Not Even Wrong" blog, "The Yang-Mills Publicity Stunt" — two
  independent human write-ups of the OpenAI Yang-Mills Lean proof named but not yet independently
  opened this session: Martin Hairer (Fields Medalist), https://github.com/hairer/humanise-yang-mills;
  Scott Armstrong, https://github.com/scottnarmstrong/yang-mills-informalization. Chase next
  session (see the Yang-Mills trend's notes for full context).
- 2026-11-13 — "A Statement on Sharing Research Results Produced by AI Companies in Theoretical
  High-Energy Physics" — https://hep-open-release.org/ — a governance/advocacy statement (not
  itself a research result) calling for open release of AI-company physics results, signed by 39
  initial signatories (Edward Witten, Juan Maldacena, Michael Peskin, Cumrun Vafa, David Tong) plus
  216 further signatories. Axis-5 AI-watch-lane vetting-status signal, directly relevant to the
  OpenAI Yang-Mills trend's release-practice debate (Woit cites it the same day). Opened directly
  via `WebFetch` this session; new source staged in SOURCES.md.

## source_rotation

Append-only coverage log MOVED to `logs/source_rotation.md`. Each run APPENDS one dated line
THERE and reads only the recent tail (~7 days) — do not write scans into TRENDS.md.

## strategy_notes

Append-only strategy log MOVED to `logs/strategy_notes.md`. Runs APPEND dated entries
THERE and read only the recent tail (~10 entries) — do not write strategy notes into
TRENDS.md. Curator scope input and vetoes also live there.

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-11-26 (shelf-added; event dated 2026-11-25) — [Unconditional Integer Factorization in Time L_N[1/3, O(1)]](https://github.com/google-research/google-research/blob/master/cogentic_research_papers/integer_factorization/paper.pdf) —
  Google Cogentic's claimed removal of all unproven-hypothesis reliance from the fastest known
  rigorous classical factoring bound, closing a 34-year gap (Lenstra–Pomerance 1992) and matching
  the heuristic NFS exponent unconditionally — directly relevant to RSA's security foundations if
  correct. MAXIMUM caution: hours old, wholly AI-generated (a new, first-sighted disclosure
  channel), unrefereed, zero independent engagement yet. See the matching new seed trend above.
- 2026-11-26 (shelf-added; event dated 2026-08-19/2026-10-25) — [A simple construction of smooth counterexamples to the Loewner and Carathéodory conjectures](https://arxiv.org/abs/2610.34036) —
  an explicit, AI-assisted (Alpöge/Smith, Anthropic's Claude) disproof of the 102-year-old
  Carathéodory conjecture and the Loewner conjecture — the last of Osserman's "three obdurate
  conjectures of differential geometry" still open — with an independent, simpler confirming
  construction by Ando–Umehara. A genuine ~99-day capture-leak catch; note the standing
  Guilfoyle–Klingenberg counter-claim (a different regularity class) tracked alongside it. See the
  matching new seed trend above.
- 2026-11-25 (shelf-added; event dated 2026-11-24) — [The matrix multiplication exponent is nine fourths](https://github.com/openai/math/blob/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf) —
  OpenAI's claimed exact resolution of the matrix-multiplication exponent ($\omega=9/4$), via a new
  lower bound matching its own already-known upper bound — a surprising REFUTATION of the long-hoped
  $\omega=2$ conjecture, one of the most famous open problems in theoretical computer science.
  MAXIMUM caution: hours old at discovery, wholly AI-generated, unrefereed, zero independent
  engagement yet on the lower bound — but the scale and surprise of the claim belong on a frontier
  researcher's radar now. See the matching new seed trend above.
- 2026-11-24 (shelf-added; event dated 2026-11-23) — [VP ≠ VNP over every field](https://hexagonmath.org/2611.00954v1) —
  a claimed resolution of Valiant's 1979 algebraic-complexity flagship conjecture, discovered by an
  internal Anthropic research Claude model and deposited directly by Anthropic to hexagonmath.
  MAXIMUM caution: AI-generated, unrefereed, no Lean repository link given to check the claimed
  formalization — but the conjecture itself is famous well beyond complexity theory, and a result
  this significant, however provisional, belongs on a frontier-researcher's radar now. See the
  matching new seed trend above.
- 2026-11-23 (shelf-added; events dated 2026-11-20/22) — [A proof of the Riemann Hypothesis](https://alpo.ge/remark.pdf) —
  Levent Alpöge's own announcement, "working with Claude," of a Lean-formalized proof of RH and GRH
  for Dirichlet L-functions, independently Lean-kernel-verified (multiple kernels, zero errors, no
  extra axioms) by Andrew Sutherland (MIT) at https://math.mit.edu/~drew/grh/ — by far the largest
  claim this radar has ever tracked. EXTREME caution: days old, the formalized statement's fidelity
  to true RH/GRH is explicitly NOT yet independently confirmed, and no human has yet published an
  understood, checked account of the ~17-million-line argument. See the matching new seed trend
  above for the full picture, incl. the independent rival (and currently shakier) Masullo attempt.
- 2026-11-23 (shelf-added; event dated 2026-11-20) — [Finite-Time Singularity Formation for the Three-Dimensional Euler Equations](https://cims.nyu.edu/~tristanb/cc.pdf) —
  Alpöge, Buckmaster (2019 Clay Research Award) and Coiculescu's claimed UNFORCED 3D Euler blowup,
  with a companion unforced Navier-Stokes blowup claim (github.com/tristanbuckmaster/navier-stokes)
  — if it holds, a direct resolution of the Clay Millennium Problem; Terence Tao calls the Euler
  paper "technically human-readable" with a clear strategy, see the matching new seed trend above.
  EXTREME caution: unrefereed, days old, an acknowledged un-rebuilt Lean patch outstanding.
- 2026-11-20 — [Claude solves two open problems in the physics of black holes](https://www.anthropic.com/research/claude-black-hole-physics) —
  Anthropic's own disclosure of two Claude-produced results (an abrupt Hawking-Page-type
  transition in weak-coupling N=4 SYM; an exact optimal modular-bootstrap mass ceiling for 3D
  gravity) — worth knowing given the scale of the claims and the same-day independent
  cross-checks reported, but EXTREME caution: unrefereed hexagonmath preprints, same AI-watch
  skepticism tier as every other AI-lab self-disclosure this ledger tracks.
- 2026-11-20 — [Certified Discovery of Quantum Phase Diagrams](https://arxiv.org/abs/2611.25064) —
  Liu, Preskill, and Huang construct an efficient quantum algorithm that outputs a phase diagram
  with a verifiable certificate for every transition, from only a classical Hamiltonian family
  description and unverified reference-state preparations — a genuine, rigorously-certified
  result at the complexity-of-quantum-systems/axis-4 frontier, not an AI-assisted-math claim.
  Opened directly via arXiv this session (quant-ph/cond-mat.str-el title-triage hit).
- 2026-11-19 — [Finite-Time Blowup for Navier-Stokes with Smooth Forcing, Part I](https://arxiv.org/abs/2609.35406) —
  Zhen Lei and Xiao Ren's independent, readable reconstruction of the profile-construction core of
  OpenAI's claimed Navier-Stokes Millennium-Prize proof, by an established Navier-Stokes
  researcher who states plainly "we regard OpenAI's work as a major advance" — worth reading as
  the first real mathematical engagement (not just commentary) with this radar's single biggest
  tracked claim. Opened directly via arXiv this session; found via MathHelm, a new source.
- 2026-11-19 — [Uniform Spectral Gap for the AKLT Model on the Square Lattice](https://hexagonmath.org/2611.00580v1) —
  a claimed resolution of the long-open 2D-square-lattice case of the AKLT spectral-gap conjecture
  (1988); worth knowing about given the problem's fame, but read with EXTREME caution — hexagonmath,
  unrefereed, "Human understanding: no parts." Opened directly via `WebFetch` this session.
- 2026-11-18 — [Power loss for the local Mizohata–Takeuchi estimate on smooth hypersurfaces](https://arxiv.org/abs/2611.22465) —
  Hannah Cairo and five co-authors disprove the local Mizohata–Takeuchi conjectures for the
  paraboloid and sphere, a finer sibling of the general conjecture Cairo already disproved last
  year — worth knowing both for the Fourier-restriction-theory implications and as her second
  landmark result on this ledger. Found via today's mandatory math.CA full-abstract pass
  (title-blind); abstract opened directly via arXiv this session.
- 2026-11-18 — [The Minimal Model Program, formalized in Lean](https://axiommath.ai/research/the-minimal-model-program-formalized/) —
  AxiomMath's claimed ~2.1-million-line Lean formalization of the Minimal Model Program in
  dimensions 2–4, folding in OpenAI's claimed resolution of the remaining 4-dimensional cases —
  worth knowing as a large-scale formalization artifact algebraic geometers will want to
  evaluate, though EXTREME caution applies (new org, no independent verification yet; see new
  seed trend). Opened directly via `WebFetch` this session.
- 2026-11-17 — [DES final-dataset cosmology results](https://arxiv.org/abs/2605.27221) (Dark
  Energy Survey collaboration, combined with DESI + CMB) — an independent flagship survey's own
  analysis finding a ~3σ preference for evolving dark energy over ΛCDM, with the CMB/clumping/
  supernova datasets disagreeing pairwise in a way not traceable to any one of them — essential
  context for the DESI dynamical-dark-energy story now promoted to this ledger's own multi-group
  trend. Discovered via a Quanta/Fermilab-syndicated pointer, arXiv abstract opened directly via
  `WebFetch` this session.
- 2026-11-17 — [Full resolution of the Osserman (1990) conjecture](https://hexagonmath.org/2611.00544v1) —
  a genuine, 36-year-old differential-geometry conjecture (Riemannian manifolds with
  direction-independent Jacobi-operator eigenvalues are flat or locally rank-one symmetric),
  closed by resolving its last remaining algebraic case (Nikolayevsky's 2009 reduction) — worth
  knowing about REGARDLESS of its unrefereed, AI-assisted, single-submitter provenance (see this
  ledger's EXTREME-caution flag on the trend itself): a notable claim researchers in the field
  will likely encounter and want to evaluate independently. Opened directly via hexagonmath
  RSS/`WebFetch` this session.
- 2026-11-16 — [MathHelm](https://mathhelm.org/) (guest-announced on Terence Tao's "What's new") —
  a new nonprofit forum for mathematicians to discuss AI-generated papers (born directly from
  OpenAI's Oct 6 722-manuscript release), open worldwide, real-name registration, no stance for
  or against AI, prohibits using forum content to train AI — worth knowing as new axis-5
  vetting-status infrastructure directly relevant to this ledger's own hype-skepticism tracking
  (same class as the already-tracked mathcommunity.github.io/oai-math-revised). Opened directly
  via the Tao-blog post this session (mathhelm.org itself not independently verified this
  session — staged in SOURCES.md, chase on next sighting).
- 2026-11-16 — [Validation of the OpenAI Yang–Mills construction](https://github.com/yang-mills-group/YM/blob/main/docs/assessment-1.pdf)
  (the shepherding committee, Nov 10) — the actual document resolving this ledger's longest-
  running top-priority chase item: a primary-sourced, precise statement of what the Oct 28 Lean
  submission does and does not establish (weak existence via compactness; no mass gap, no
  uniqueness) — essential reading for anyone following the Yang–Mills Millennium Problem story,
  and a model of how a vetting committee should state scope precisely. Read directly via
  `pdftotext` this session (see the Yang-Mills trend for full context).
- 2026-11-13 — [Euler's 1747 conjecture on sums of integers with restricted prime factors](https://hexagonmath.org/2611.00370v1) —
  a genuine 279-year-old conjecture (Euler to Goldbach, 1747), fully resolved: every integer ≡2
  mod 4 is a sum of two integers whose prime factors are all ≡1 mod 4, closed via quaternionic
  Hecke bounds plus a finite arithmetic certificate — worth knowing as a clean, complete result
  in a session otherwise dominated by partial progress and AI-claimed/unrefereed landmarks.
  Opened directly this session.
- 2026-11-12 — [Osterwalder–Schrader axioms for scalar QED₃ in the Higgs phase](https://hexagonmath.org/2611.00321v1)
  (Goldstein, Guevara) — a rare rigorous constructive-QFT result: verifies the
  Osterwalder–Schrader axioms for the 3D lattice abelian Higgs model in the continuum limit —
  worth knowing as a genuine rigor achievement in a field dominated by non-rigorous/AI-claimed
  results this session; opened directly this session.
- 2026-11-11 — [Cluster Algebras, formalized in Lean](https://axiommath.ai/research/cluster-algebras-formalized-in-lean)
  (AxiomMath) — a Lean library covering the first seven chapters of Fomin–Williams–Zelevinsky's
  "Introduction to Cluster Algebras," continuing AxiomMath's formalization-of-foundational-texts
  pattern (Stacks Project, Weil conjectures, CFSG) — opened directly this session.
- 2026-11-10 — [Z is Diophantine in Q](https://github.com/elliotglazer/diophantine-z-q) — Glazer
  et al.'s claimed disproof of Mazur's 1992 finite-components conjecture and independent second
  route to a negative resolution of Hilbert's Tenth Problem over ℚ — worth knowing as the story,
  not as confirmed mathematics (EXTREME caution tier, Lean formalization incomplete; see new seed
  trend). Opened directly via `WebFetch` this session.
- 2026-11-06 — [The Weil conjectures, formalized in Lean](https://axiommath.ai/research/the-weil-conjectures-formalized-in-lean/) —
  AxiomMath's sorry-free Lean formalization of Deligne's four Weil conjectures (rationality,
  functional equation, Betti-number comparison, Riemann-hypothesis-analogue bound), reusing its
  own Stacks Project formalization — worth knowing for anyone tracking the formalized-mathematics
  frontier (axis 5), though EXTREME-caution tier pending outside review (see new seed trend).
  Opened directly via `WebFetch` this session.
- 2026-11-05 — [A Note On Lattice Definition of Gauge Theories With Chiral Fermions](https://arxiv.org/abs/2611.05051) —
  Edward Witten's own engagement with Nathaniel Craig's candidate nonperturbative lattice
  definition of chiral gauge theories (the Standard Model's gauge structure): a variant
  construction, a flagged practical obstruction (non-positive path integral blocks Monte Carlo),
  and a nod to Claude Opus 5.5 for technical help — essential reading for anyone following the
  lattice-chiral-fermion story. Abstract verified via arXiv API this session.
- 2026-11-05 — [The Stacks Project, formalized in Lean](https://stacks.axiommath.ai/) — a new
  Lean/Mathlib formalization of the Stacks Project, the standard reference for modern algebraic
  geometry, with a dependency graph and a human-reviewed/AI-written two-tier contribution model —
  worth knowing for anyone tracking the formalized-mathematics frontier (axis 5). Opened directly
  via `WebFetch` this session.
- 2026-11-04 — [Statement by the shepherding committee on OpenAI's Yang–Mills proof](https://www.kitp.ucsb.edu/sites/default/files/YM_working_group.pdf) —
  Douglas, Gross (chair), Jaffe, Klebanov, Nekrasov's own account of how they are vetting OpenAI's
  claimed Yang–Mills existence proof before release: existence only (mass gap still open), still
  validating the Lean formalization, 1147-page manuscript pending release — essential reading for
  anyone following the field's single highest-magnitude open claim. Read directly via `pdftotext`
  this session.
- 2026-11-04 — [On the abc conjecture](https://arxiv.org/abs/2611.05217) — Christophe Soulé
  proves a weak form of the abc conjecture and a genus-two case of Vojta's conjecture via adelic
  intersection theory, following a method envisioned by Parshin and Moret-Bailly — a rare piece
  of genuine forward motion, by a highly credible author, on one of number theory's most famous
  (and most hype-scarred) open problems. Abstract verified via arXiv API this session.
- 2026-11-03 — [Proof of the entropic $c$-theorem](https://arxiv.org/abs/2610.40874) — Jonah
  Kudler-Flam's new proof of Zamolodchikov's c-theorem in 2D QFT, building a $c$-function from
  mutual information between spacelike-separated wedges via relative entropy (following
  Casini–Huerta, replacing strong subadditivity with an entropic argument that needs no UV
  cutoff) — an elegant, modern entanglement-entropy technique a mathematical-physicist should
  know, caught via today's math category-rotation sweep (cross-listed hep-th/math-ph). Abstract +
  author verified via direct arXiv abstract page this session.
- 2026-10-30; shelf-added 2026-11-02 — [Report of the Summit on Math Research in the Age of
  AI](https://terrytao.wordpress.com/2026/10/30/__trashed/) — a guest post by the summit's
  organizers (Dan Freed, Larry Guth, Bryna Kra, Emily Riehl, Mohammed Abouzaid) on Terence Tao's
  blog; alongside Frank Calegari's "Mathematics has changed. Let's act like it"
  (https://terrytao.wordpress.com/2026/11/01/mathematics-has-changed-lets-act-like-it/) and a UK
  Academy for the Mathematical Sciences report, the clearest single read this week on how the
  working-mathematician community is organizing its response to the AI-disclosure wave; see the
  OpenAI mass-disclosure trend's 2026-11-02 note.
- 2026-10-27; shelf-added 2026-10-28 — [CFSG in Lean (AxiomMath)](https://cfsg.axiommath.ai/) —
  a claimed complete Lean 4 formalization of the Classification of Finite Simple Groups, ~43.1M
  lines, surfacing a genuine gap in the published Unbalanced Group Theorem proof; EXTREME caution
  (new, self-published org, no independent verification yet) but a working mathematician tracking
  the frontier should know this exists and is being discussed; see new seed trend.
- 2026-10-26; shelf-added 2026-10-27 — [Working with academic communities to build scientific
  understanding (OpenAI)](https://openai.com/index/building-scientific-understanding-with-academic-communities/)
  — OpenAI's announced (not yet public) claimed proof of Yang–Mills existence and a QCD/Standard-
  Model completion — if the mass-gap scope holds up, this is a Clay Millennium Prize Problem claim;
  see new seed trend and Peter Woit's critical same-day read.
- 2026-10-25/26; shelf-added 2026-10-27 — [Independent same-day Exponential-Time-Hypothesis
  refutation claims (Anthropic via hexagonmath.org/2610.00577; OpenAI via github.com/openai/math
  #378)](https://github.com/anthropics/formal-math/blob/main/eth) — two AI labs, same week, same
  foundational complexity hypothesis, each with a Lean-checked claim; see new seed trend.
- 2026-10-10 (v1); shelf-added 2026-10-26 — [A counterexample to Vaught's Conjecture for
  $L_{\omega_1,\omega}$ (Ackerman, Freer, Knight)](https://arxiv.org/abs/2610.15217) — completes
  Robin Knight's 24-year-old (2002) construction disproving Vaught's famous 1961 conjecture for
  infinitary logic, with heavy AI-coding-agent assistance (Claude Code, Codex, GPT) in the Lean
  formalization, Comparator-checked and on the Palomar Registry; see new seed trend.
- 2026-10-23 (v1); shelf-added 2026-10-26 — [On the Propeller Conjecture
  (Steven Heilman)](https://arxiv.org/abs/2610.32158) — an independent human simplification,
  sharpening, and de-computerization of OpenAI's AI-generated proof of Khot and Naor's 2008
  propeller conjecture (which underlies a Unique-Games-based NP-hardness result for clustering); a
  clean example of productive human engagement with an AI math claim. See new seed trend.
- 2026-10-22 (v1); shelf-added 2026-10-23 — [Simple and critical zeros of the Riemann zeta-function
  (Caroline Turnage-Butterbaugh, guest post on Terence Tao's blog)](https://terrytao.wordpress.com/2026/10/22/simple-and-critical-zeros-of-the-riemann-zeta-function/)
  — the clearest single exposition on file of the full history and current vetting state of the
  "≥2/3 of zeta zeros are simple and on the critical line" result (Levinson through Claude/
  Anthropic, Lamzouri, and this session's new Guo elementary-proof lead); a model survey for a
  researcher wanting the whole picture in one place.
- 2026-10-22 (v1); shelf-added 2026-10-23 — [The classification of smooth 3-fold flops
  (Gavin Brown, Michael Wemyss)](https://arxiv.org/abs/2610.31073) — a complete analytic
  classification of simple 3-fold flops via their contraction algebras, from two established
  birational geometers; a foundational advance in the minimal model program, held below the trend
  bar (no single named conjecture resolved) but worth a researcher's attention on its own.
- 2026-10-21 (v1); shelf-added 2026-10-22 — [On OpenAI's proof of the Nagata conjecture
  (Jenia Tevelev)](https://arxiv.org/abs/2610.30050) — a leading algebraic geometer's own
  non-expert-accessible exposition of an AI-claimed proof of the 1959 Nagata conjecture (plane-curve
  interpolation / Seshadri constants), one result-family within OpenAI's October mass disclosure;
  a model of how to responsibly digest an AI claim into the literature.
- 2026-10-04/2026-09-24 (v1); shelf-added 2026-10-22 — [Independent AI-lab convergence on the
  percolation-criticality conjecture (Claude/Anthropic and OpenAI)](https://github.com/openai/math)
  — two separate frontier models independently resolved the same landmark open problem
  (Benjamini–Schramm criticality) within three weeks of each other, via different routes; see new
  seed trend for the full picture and the standing vetting caveats.
- 2026-10-20 (v1); shelf-added 2026-10-21 — [A proof of the double-cap conjecture
  (Ibiapina, Gomes, Pio, Belo, Ferreira)](https://arxiv.org/abs/2610.27523) — settles Witsenhausen's
  1974 problem / Kalai's 2009 conjecture on orthogonal-pair-free subsets of the sphere, with a
  direct consequence for the measurable chromatic number of Euclidean space; see new seed trend.
- 2026-10-19 (v1); shelf-added 2026-10-21 — [Tree Lattices and the Neumann-Zagier conjecture
  (Greene, Issa, McCoy)](https://arxiv.org/abs/2610.27095) — resolves a 1985 conjecture in
  low-dimensional topology via a new rigidity theorem for tree lattices; see new seed trend.
- 2026-10-19 (v1); shelf-added 2026-10-20 — [Proof of the Erdős-Szemerédi sunflower conjecture
  (Bucić, He, Lee)](https://arxiv.org/abs/2610.26686) — resolves a famous 1970s Erdős conjecture in
  full for every $k\ge3$, directly continuing the celebrated cap-set/polynomial-method breakthrough
  that settled the $k=3$ case; see new seed trend.
- 2026-09-16 (v1); shelf-added 2026-10-20 — [A Strongly Aperiodic Monotile in Three Dimensions
  ("Chair44," Tsiokos; rapid expert corroboration by Flicker and Goodman-Strauss)](https://arxiv.org/abs/2609.19214)
  — the 3D analogue of the celebrated 2023 2D "einstein" tile, with the co-discoverer of that
  original result (Goodman-Strauss) posting his own clarifying presentation of the same
  construction within days; see new seed trend for the full AI-provenance/reception caveats.
- 2026-01-05 (v1); shelf-added 2026-10-19 — [Resummation of the C-Parameter Sudakov Shoulder Using
  Effective Field Theory (Schwartz)](https://arxiv.org/abs/2601.02484) — a new factorization
  theorem for a QCD precision-calculation problem, notable both on its own physics merits and as a
  genuine (AI-assisted-but-human-steered) axis-5 case study; see queue entry above for the
  AI-watch framing.
- 2026-08-09 (v1); shelf-added 2026-10-16 — [The Mathieu group M23 is a Galois group over ℚ
  (Huang, Jackson, Lee, Poonen, Pries, Zhang)](https://arxiv.org/abs/2608.08538) — completes a
  ~40-year program, realizing the last of the 26 sporadic finite simple groups as a Galois group
  over ℚ via an explicit degree-23 polynomial; see new seed trend (backfilled capture-leak
  closure).
- 2026-10-15 (v1); shelf-added 2026-10-16 — [A Proof of the Area Vanishing Square Peg Conjecture
  (Valerio)](https://arxiv.org/abs/2610.21076) — resolves a Tao-posed open problem via Lagrangian
  Floer homology, an elegant cross-pollination of symplectic topology into a classical planar-
  geometry question; see new seed trend.
- 2026-10-14 (v1); shelf-added 2026-10-15 — [Proof of the Penrose Conjecture for Maximally
  Parameterized Initial Data Sets (Bray, Dolmen, Khuri, Schmidt)](https://arxiv.org/abs/2610.20559)
  — unconditional resolution of a ~50-year-old conjecture in mathematical GR for a broad class of
  data, by one of the 2001 Riemannian case's original provers; explicitly engages with OpenAI's
  concurrent general-case AI claim — see new seed trend.
- 2026-10-14 (v1); shelf-added 2026-10-15 — [A starlike 3-dimensional counterexample to the hot
  spots conjecture (Atar, Burdzy)](https://arxiv.org/abs/2610.19908) — extends the refutation of
  Rauch's hot spots conjecture to simply-connected (starlike) domains, by the author of the
  original 1999 counterexample; see new seed trend.
- 2026-10-13; shelf-added 2026-10-14 — [Evidence of galaxy cluster rotation in the CMB (Goldstein–Hill)](https://link.aps.org/doi/10.1103/lz37-crg1)
  — first robust detection of the rotational kinematic Sunyaev–Zel'dovich effect, PRL 137, 161001;
  clean peer-reviewed first-of-kind, no AI/hype-skepticism caveat; see new seed trend.
- 2026-10-13; shelf-added 2026-10-14 — [A proof of the rational exponents conjecture](https://arxiv.org/abs/2610.18713)
  — Erdős–Simonovits's decades-old extremal-graph-theory conjecture, proof claimed by Epoch AI
  (a third AI org disclosing a major math claim) and human-verified/written up by eight prominent
  combinatorialists; see new seed trend.
- 2026-09-30/10-05; shelf-added 2026-10-13 — [OpenAI's quasi-Riemann-Hypothesis claim](https://github.com/openai/math/blob/main/preprints/The-Quasi-Riemann-Hypothesis-September-30-2026/paper.pdf)
  — a claimed fixed-width zero-free region (ℜs>7/8, companion ℜs>11/12) for Dirichlet/Hecke
  L-functions; wholly unrefereed and AI-generated, but the first result of this kind in decades —
  see new seed trend for the vetting-status watch.
- 2026-10-06; shelf-added 2026-10-13 — [A gauge-invariant measure for lattice chiral fermions
  (Craig)](https://arxiv.org/abs/2610.09093) — a candidate nonperturbative lattice definition of
  the Standard Model, addressing the long-standing chiral-fermion lattice obstruction; see new
  seed trend.
- 2026-10-09 (v1); shelf-added 2026-10-12 — [Finiteness of planar central configurations of five
  bodies for all positive masses (Tomar)](https://arxiv.org/abs/2610.13100) — settles Smale's sixth
  problem for n=5, closing the exceptional-mass-set gap left by Albouy–Kaloshin (2012); see new
  seed trend.
- 2026-03-19 (announced); shelf-added 2026-10-10 — [2026 Abel Prize — Gerd Faltings (Max Planck
  Institute for Mathematics, Bonn)](https://abelprize.no/) — a towering figure in arithmetic
  geometry (the Mordell conjecture/Faltings' theorem among his landmark results); COVERAGE-GAP
  CATCH — this ledger's annual-prize lane had never captured this year's Abel Prize at all until
  this weekly. Official laureate page opened directly this session.
- 2026-10-05 (v1); shelf-added 2026-10-09 — [Truly Subquadratic 3SUM and Truly Subcubic APSP via
  Triangles in Sparse Lopsided Graphs (Alman, Vassilevska Williams)](https://arxiv.org/abs/2610.06783)
  — refutes the 3SUM and APSP hypotheses; AI-discovered (Claude) and Lean-verified; see new seed
  trend.
- 2026-10-08 (v1); shelf-added 2026-10-09 — [Hyperkähler SYZ conjecture (Engel, Mauri)](https://arxiv.org/abs/2610.12277)
  — full proof of the hyperkähler analogue of the Strominger–Yau–Zaslow conjecture; see new seed
  trend.
- 2026-10-07 (v1); shelf-added 2026-10-08 — [A solid-state nuclear clock based on VUV absorption
  spectroscopy of $^{229}$Th (Wang, Pan, et al.)](https://arxiv.org/abs/2610.10056) — first
  sustained, operating thorium-229 nuclear clock (30-hour feedback-locked record); see new seed
  trend.
- 2026-10-07 (v1); shelf-added 2026-10-08 — [Transverse rational curves and the LeBrun–Salamon
  conjecture (Hu, Liu, Wan)](https://arxiv.org/abs/2610.10410) — full resolution of a 30-year-old
  named conjecture in quaternionic-Kähler geometry; see new seed trend.
- 2026-10-06; shelf-added 2026-10-07 — [2026 Nobel Prize in Physics: Francis Halzen](https://www.nobelprize.org/prizes/physics/2026/press-release/)
  — "for decisive contributions to the IceCube Neutrino Observatory and the discovery of
  high-energy neutrinos of astrophysical origin"; see new seed trend.
- 2026-10-06 (v1); shelf-added 2026-10-07 — [OpenAI's mass math-results release, github.com/openai/math](https://github.com/openai/math)
  — 722 AI-generated manuscripts/372 result families across 17 fields, including a claimed partial
  Birch–Swinnerton-Dyer resolution; EXTREME hype-skepticism — see new seed trend.
- 2026-10-06 (v1); shelf-added 2026-10-07 — [An AI-Assisted Formalization of the Poincaré Conjecture (Zhang, Delaval, et al.)](https://arxiv.org/abs/2610.08329)
  — second independent AI-assisted Lean formalization of the Hamilton–Perelman proof; see
  promoted seed trend (with the first effort, arXiv:2609.33842, already shelved 2026-09-29).
- 2026-10-04 (v1); shelf-added 2026-10-06 — [A Proof of the Linear Hadwiger Conjecture (Norin,
  Steiner)](https://arxiv.org/abs/2610.05291) — claims full resolution of the linear/asymptotic
  form of Hadwiger's conjecture (K_t-minor-free graphs are Ct-colorable), by the field's own leading
  expert (Norin), proof credited to GPT-6 Astra under the authors' direction; EXTREME
  hype-skepticism caution (2 days old, unrefereed, zero independent engagement yet) — see
  `observation_queue`, new `seed` trend.
- 2026-09-22 (PRL publication); shelf-added 2026-10-05 — [Observation of e/4 Charge at ν=1/2 in a
  Wide GaAs Quantum Well (Alkalay, Hajigeorgiou, Gupta, Senapati, Tiwari, Tai, Singh, Baldwin,
  Pfeiffer, Shayegan, Banerjee, Heiblum)](http://link.aps.org/doi/10.1103/c73x-q4z7) — peer-reviewed
  (PRL) shot-noise measurement of e/4-charged quasiparticles in the ν=1/2 fractional quantum Hall
  state, evidence for a non-Abelian (Pfaffian-class) topological order; same Weizmann (Heiblum)
  group as the already-shelved/queued ν=5/2 anyon-braiding result — see `observation_queue`.
- 2026-10-01 (v1); shelf-added 2026-10-02 — [A proof of Lehmer's 1965 permutation conjecture for
  neighbor-swap graphs (Verhoeff)](https://arxiv.org/abs/2610.01240) — resolves a 61-year-old
  conjecture posed as an unsolved problem in Knuth's *TAOCP*, with a complete accompanying Lean 4 /
  Mathlib formalization checked against brute-force graphs — see `observation_queue`, new `seed`
  trend.
- 2026-08-23/24 (original claim); 2026-09-27 (independent extension); shelf-added 2026-10-01 —
  [The Hopf problem: a complex structure on S⁶ (Alpöge/Claude; independently extended by Viaclovsky)](https://arxiv.org/abs/2609.33785)
  — a claimed resolution of one of differential geometry's most famous 20th-century open problems
  (1947), via an AI-assisted construction now also independently extended by a credentialed
  geometer; EXTREME unrefereed-preprint caution (mixed MathOverflow reaction, a history of prior
  flawed claims on this exact problem) — see `observation_queue`, new `seed` trend.
- 2026-09-24 (PRL publication; v1 2025-12; shelf-added 2026-09-30) — [A possible resolution of the gallium anomaly (Cadeddu, Cargioli, Dordei, Ferro, Giunti, Pitzalis)](https://arxiv.org/abs/2512.20560)
  — a revised, peer-reviewed (PRL) neutrino-capture cross-section calculation that potentially closes
  a ~30-year, >5σ discrepancy (GALLEX/SAGE/BEST) without new physics; found via the PRL RSS sweep.
  Theoretical proposal, not yet an experimental confirmation — see `observation_queue`.
- 2026-09-28 (v1; shelf-added 2026-09-29) — [A Lean Formalization of the Hamilton–Perelman Proof of the Three-Dimensional Poincaré Conjecture (Qin, Liao, Khaitan, Chow)](https://arxiv.org/abs/2609.33842)
  — formalizes the full Ricci-flow-with-surgery proof of the smooth (and, via Moise smoothing, the
  topological) 3D Poincaré conjecture in Lean; a formalization landmark on the scale of the
  already-shelved Lean FLT proof. Unrefereed, no independent verification of the artifact yet — see
  `observation_queue`.
- 2026-02-17 (final paper; shelf-added 2026-09-29) — [Resolution of Graham's rearrangement conjecture (Pham, Sauermann, closing a 4-paper, 4-group chain from 2022-2026)](https://arxiv.org/abs/2602.15797)
  — a 1971 conjecture on rearranging residues mod p so all partial sums are distinct, resolved
  across four independent groups' papers; caught via a 2026-09-28 Quanta piece. Also a new `seed`
  trend.
- 2026-09-14 (v1; shelf-added 2026-09-28) — [Two proofs of the Cassels–Swinnerton-Dyer conjecture for cubic surfaces (Alexeev, Schreieder)](https://arxiv.org/abs/2609.15930)
  — completes a ~50-year reduction chain (Coray 1976, Voisin 2026) to resolve the Cassels–
  Swinnerton-Dyer conjecture for smooth cubic surfaces over arbitrary fields. Also a new `seed` trend.
- 2026-08-late (computation); 2026-09-25 (guest post; shelf-added 2026-09-28) — [Yes, Claude Can Do Nine Loops (Anthropic)](https://www.anthropic.com/research/yes-claude-can-do-nine-loops)
  — an AI-assisted computation of the nine-loop MHV six-particle amplitude in planar N=4 super
  Yang-Mills, independently verified by Lance Dixon (SLAC/Stanford); notable technique demonstration
  for computational amplitudeology. AI-watch: track the physics result, not the method — see
  `observation_queue`.
- 2026-09-17 (Fauzan claim; Firsching's independent Lean verification 2026-09-23; shelf-added
  2026-09-26) — [Irrationality of ζ(5) (Fauzan; Lean-verified by Firsching)](https://github.com/mo271/zeta5)
  — the first individual-odd-zeta irrationality result since Apéry 1978; an off-arXiv, no-track-record
  claim now backed by a Google DeepMind Lean/Mathlib contributor's complete, `sorry`-free independent
  formalization (technically a variant derivation, not a literal check of the original argument). Also
  a new `seed` trend.
- 2026-09-25 (v1; shelf-added 2026-09-25) — [Proof of the positive trace gap conjecture (Nikolay Bogachev)](https://arxiv.org/abs/2609.29033)
  — resolves Sarnak's ~18-year-old positive trace gap conjecture for cocompact Fuchsian/Kleinian
  lattices via a quaternion-algebra characterization; also new for lattices in $SL_d(\mathbb R)$,
  $d\ge3$. Credible single-author landmark; unrefereed-preprint caution stands. Also a new `seed`
  trend.
- 2026-08-26 (Science Advances, published; shelf-added 2026-09-25) — [Direct experimental test of Feynman's path integral postulates with single photons (Wen, Zhu et al.)](https://pmc.ncbi.nlm.nih.gov/articles/PMC13510607/)
  — first direct experimental verification of Feynman's 1948 path-integral postulates, reconstructing
  amplitudes for >1.4M single-photon paths; peer-reviewed, but note Hossenfelder's skeptical read of
  the press framing vs. the measured precision (17.4% MAPE on postulate II) — see `observation_queue`.
- 2025-10-23 (v1; capture-leak catch via a 2026-09-18 Quanta piece, shelf-added 2026-09-24) — [A proof of the Kim-Vu sandwich conjecture (Behague, Iľkovič, Montgomery)](https://arxiv.org/abs/2510.20765)
  — proves in full generality (all $d=\omega(\log n)$) the 2004 Kim-Vu sandwich conjecture, that a
  random $d$-regular graph can be coupled between two random binomial graphs of asymptotically equal
  edge probability; extends Gao-Isaev-McKay's 2020 partial result. A landmark ~20-year-old
  random-graph-theory conjecture, missed for ~11 months until Quanta's coverage.
- 2026-09-22 (v1; shelf-added 2026-09-24) — [A separably representable counterexample to Naimark's problem in ZFC (Ryotaro Tanaka)](https://arxiv.org/abs/2609.26930)
  — an unconditional (ZFC, no extra set-theoretic axiom) counterexample to Naimark's ~70-year-old
  problem on C*-algebras with a unique irreducible representation, going beyond Akemann-Weaver's
  2004 ◊-dependent example; single-author, unrefereed — see `observation_queue` for the full caveat.
- 2026-09-21 (guest post; shelf-added 2026-09-22) — [Announcing the Advisory Group on Mathematics and Artificial Intelligence](https://agmai.org)
  — nine senior mathematicians (Charles, De Lellis, Gowers, Hairer, Srivastava, Tillmann, Vakil,
  Witten, Wood), hosted at IAS, formed to advise OpenAI on releasing the 100+ open-problem claims its
  internal model reportedly resolved — a field-shaping governance response every frontier researcher
  in this ledger's scope should know about; see `observation_queue` for the underlying (still
  unverified) claim.
- 2026-09-22 (v1 2026-09-20; shelf-added 2026-09-22) — [Fractional illumination and the optimal exponential rate in Hadwiger's covering conjecture (Yegor Gorodzha)](https://arxiv.org/abs/2609.23913)
  — pins the correct exponential growth rate on Hadwiger's covering conjecture, open since 1957 and
  one of convex geometry's most famous unsolved problems.
- 2026-09-17 (arXiv v1; shelf-added 2026-09-21) — [Observation of the doubly charmed baryon $\Omega^+_{cc}$ (LHCb Collaboration)](https://arxiv.org/abs/2609.21921)
  — first observation (8.7σ) of a new doubly-charmed baryon, only the second ever seen after LHCb's
  2017 $\Xi^{++}_{cc}$ discovery.
- 2026-09-17 (arXiv v1; shelf-added 2026-09-21) — [The full De Giorgi conjecture in R^4 is true (Liu, Luo, Wang, J. Wei, Y. Wei, Wu)](https://arxiv.org/abs/2609.21680)
  — resolves the 1978 De Giorgi conjecture unconditionally in dimension 4, building on this year's
  Chan-Fernández-Real-Figalli-Serra breakthrough.
- 2025-12-04 (citation-chase catch, found 2026-09-19) — [The PFR/Marton Conjecture in Integers and Finite Fields via Spectral Stability (Kazemi Moghadam)](https://arxiv.org/abs/2512.04433)
  — claims to extend GGMT's 2024 resolution of Marton's conjecture from bounded-torsion groups to
  the integers and cyclic groups; single-author, unrefereed, ~9.5 months old and missed by every
  recency-triaged daily sweep until this week's arXiv-citation chase.
- 2026-09-11 (weekly-tier coverage catch, found 2026-09-19) — [Navier-Stokes Announcement (Clay Mathematics Institute)](https://www.claymath.org/news/navier-stokes-announcement/)
  — the Millennium Prize steward's own first public statement on the OpenAI Navier-Stokes claim:
  CMI "shares in the excitement" that the problem "has apparently been settled" but stresses its
  evaluation process "is deliberately unhurried" — acknowledgment without an outcome, on a live
  $1M-prize claim.
- 2026-09-18 (CERN news 2026-09-17; primary arXiv:2603.26463, v1 2026-03-27) — [Strong evidence of quantum entanglement between Z bosons (ATLAS, with an independent CMS result)](https://arxiv.org/abs/2603.26463)
  — the first measurement of entanglement between Z-boson pairs (spin qutrits) from Higgs decays at
  the LHC, disfavoring separability at 4.7σ; extends the collaborations' 2023-24 top-quark-
  entanglement observation to a new energy/spin regime — jointly announced by CERN,
  https://home.cern/strong-evidence-for-quantum-entanglement-between-z-bosons-found-by-atlas-and-cms/.
- 2026-09-18 (v1 2026-09-17) — [Proof of the Pach-Tardos conjecture (Gishboliner, Li)](https://arxiv.org/abs/2609.20726)
  — resolves the ~20-year-old central open problem on the extremal function of acyclic forbidden
  0-1 matrix patterns ($\operatorname{Ex}(n,P)=n^{1+o(1)}$), the surviving qualitative form of the
  2005 conjecture after its stronger polylog version was refuted in 2024.
- 2026-09-17 (v1 2026-09-16) — [A proof of Chvátal's conjecture via a sharp correlation inequality (Chang, Liu, Liu)](https://arxiv.org/abs/2609.19123)
  — resolves Chvátal's 1972 conjecture that every hereditary family of subsets has a largest
  intersecting subfamily that is a star, via a sharp correlation inequality for increasing Boolean
  functions with independent interest beyond the conjecture itself — a clean half-century-old
  combinatorics landmark.
- 2026-09-04 (capture-leak catch, found 2026-09-15) — [Formalizing Fermat's Last Theorem (Anthropic/Claude, verified by Kevin Buzzard)](https://www.anthropic.com/research/formalizing-fermats-last-theorem)
  — the first complete, end-to-end computer-checked Lean proof of FLT (13.4M lines, largely
  autonomous), independently compiled and confirmed ("it checks out") by Kevin Buzzard, the human
  academic lead of the EPSRC-funded FLT-in-Lean project this leapfrogs — see `observation_queue`.
- 2026-09-15 — [A short proof of the Erdős–Sós Conjecture (Riordan, Scott)](https://arxiv.org/abs/2609.15893)
  — established human mathematicians reproduce and simplify GPT-6 Astra's claimed full proof of the
  ~63-year-old Erdős–Sós conjecture, the strongest independent-vetting signal yet on any GPT-6 Astra
  math claim — see `observation_queue`.
- 2026-09-11 — [A Severe Misalignment of AI in Mathematics (25 Fields Medallists, incl. Terence Tao)](https://terrytao.wordpress.com/2026/09/11/a-severe-misalignment-of-ai-in-mathematics/)
  — a public declaration, modeled on the Leiden Declaration, that AI companies' push to solve
  mathematical problems as a benchmark is "severely misaligned" with the goals of the mathematical
  community; not a research result, but a field-shaping community event every frontier researcher in
  this ledger's scope should know about, directly tied to the OpenAI/Buckmaster-Alpöge/Anandkumar
  Navier-Stokes-Euler saga tracked above.
- 2026-09-10 (v1 2026-09-10) — [Connes' bicentralizer problem settled (Houdayer, Marrakchi)](https://arxiv.org/abs/2609.11462)
  — settles a 1970s-open foundational problem in von Neumann algebra theory (together with Takesaki's
  classification problem for flows on the hyperfinite II_1 factor), central to the classification of
  type III factors; unrefereed single preprint, but arguably today's top story.
- 2026-03-25 (v1; surfaced via Quanta Magazine, 2026-09-10) — [The Four Color Theorem with linearly many reducible configurations (Inoue, Kawarabayashi, Miyashita, Mohar, Thomassen, Thorup)](https://arxiv.org/abs/2603.24880)
  — a structurally new proof of the Four Color Theorem giving a near-linear-time 4-coloring
  algorithm (vs. the 1996 quadratic-time algorithm), by exploiting previously-overlooked "flat"
  regions of planar graphs; a ~5.5-month capture-leak catch, now peer-attention-confirmed via Quanta.
- 2026-09-07 (self-published, opened via Terence Tao's blog, 2026-09-10) — [Stable Singularity of the Euler Equations on R^3 without forcing (Ganeshram, Duruisseaux, Anandkumar)](https://anima-ai.org/2026/09/07/stable-singularity-of-the-euler-equations-on-r3-without-forcing/)
  — a PINN-discovered, interval-arithmetic-argued self-similar blowup for UNFORCED 3D incompressible
  Euler, the fourth entry in this week's AI-assisted fluid-blowup cluster and the closest yet to the
  actual open free-space problem; reviewed pre-release by Tom Hou and Terence Tao. Off-arXiv,
  unrefereed, heavily AI-assisted — provisional.
- 2026-09-09 (v1 2026-09-09) — [Pierce-Birkhoff conjecture is false (Lai, Lim, Ren)](https://arxiv.org/abs/2609.10420)
  — refutes the Pierce-Birkhoff conjecture (1956, ~70 years open) via an explicit piecewise-quadratic
  counterexample not expressible as a finite lattice combination of polynomials in real algebraic
  geometry; unrefereed and found with multi-agent AI assistance (GPT 5.6/6, Claude Opus 5, Claude
  Fable 5.1), but a genuine landmark-scale claim against one of the field's classical named conjectures.
- 2026-09-09 (v1 2026-09-09) — [Distribution of Singular Data Generated by Compact Forced Navier-Stokes Blowup (Cao, Chi)](https://arxiv.org/abs/2609.10262)
  — the first independent mathematical engagement with OpenAI's claimed Navier-Stokes blowup
  construction, one day after its announcement: takes the construction as given and derives a sharp
  $H^{1/2}$ density threshold for which smooth forces reproduce it — a notable vetting-status data
  point (the claim is already being worked with, not yet independently verified) worth knowing
  alongside the OpenAI item below.
- 2026-09-08 — [On the Navier–Stokes Millennium Prize Problem (OpenAI, internal model)](https://openai.com/index/navier-stokes-solution/)
  — OpenAI claims an internal AI system produced an analytical proof and Lean formalization that a
  smooth, finite-energy 3D incompressible fluid under smooth forcing can blow up in finite time,
  resolving the Navier-Stokes Millennium Prize Problem; the single biggest claim this radar has ever
  tracked, but wholly AI-generated, unrefereed, and its announcement circumstances are themselves
  publicly disputed (see the queue entries for full context) — essential to know, not to trust yet.
- 2026-09-08 (v1 2026-09-08) — [Blowup for the Euler Equations with Smooth Forcing (Alpöge, Buckmaster)](https://cims.nyu.edu/~tristanb/euler.pdf)
  — a genuine, substantial 112-page construction of finite-time singularity formation for the 3D
  incompressible Euler equations under smooth forcing, continuing the Córdoba–Martínez-Zoroa program
  and the same authors' already-shelved Boussinesq result; heavily AI-assisted and unrefereed, but
  the clearest human-legible technical escalation this week toward the Navier-Stokes Millennium
  problem, independent of the OpenAI claim above.
- 2026-09-07 (v1 2025-02-20, published Science Advances 2026-09-02) — [Observation of quantum free fall and the consistency with the equivalence principle (Dobkowski, Trok, Skakunenko, Japha, Groswasser, Efremov, Marletto, Fuentes, Penrose, Vedral, Schleich, Folman)](https://arxiv.org/abs/2502.14535)
  — the first direct observation of the quantum phase of a freely-falling matter wave, confirming
  consistency with Einstein's equivalence principle at the quantum level via a new "Quantum
  Galileo Interferometer"; an international collaboration including Nobel laureate Roger Penrose,
  now peer-reviewed in Science Advances — a landmark first-of-kind test at the quantum/general-
  relativity interface a physicist should know.
- 2026-09-07 — [Blowup for the Boussinesq Equations with Smooth Forcing (Alpöge, Buckmaster)](https://cims.nyu.edu/~tristanb/boussinesq.pdf)
  — building on Córdoba–Martínez-Zoroa's multiscale program, constructs finite-time blowup with
  smooth forcing for the 2D Boussinesq equations (with a companion Euler-equations result per
  Terence Tao's commentary) — substantial, heavily AI-assisted, unrefereed partial progress on the
  approach toward the Clay Millennium Navier-Stokes problem, discussed in detail by Tao himself;
  worth knowing as the story the analysis community is actively discussing, not as settled math.
- 2026-09-04 — [A Complete Resolution of Forsythe's Conjecture for Restarted Conjugate Gradients (Colbrook, Stepaniants, Townsend)](https://arxiv.org/abs/2609.04659)
  — settles a 1968 conjecture on restarted conjugate-gradient convergence after ~58 years: true
  for restart lengths 1-3, false for every length ≥4, via an explicit counterexample built from a
  transverse-Hopf-point analysis; the same author group's fourth classical-conjecture refutation
  this ledger has tracked (after the Pompeiu, Schiffer and Berenstein counterexamples), this time
  in numerical linear algebra.
- 2026-09-04 — [Major progress on the Erdős-Sós conjecture, and a 51-year-old Erdős-Graham problem solved as a corollary (Reed, Stein)](https://arxiv.org/abs/2609.05417)
  — two companion papers prove the 1962 Erdős-Sós tree-embedding conjecture for all k ≥ γn and
  resolve its extremal cases; en route, a corollary fully answers a half-century-old Erdős-Graham
  question on multicolor Ramsey numbers of trees — a clean example of partial progress on a famous
  open conjecture yielding a complete resolution of a named companion problem.
- 2026-03-06 (shelf-added 2026-09-05, W36 weekly queue-cleanup — leading date is the original
  preprint's v1, not the add date, so a future 120-day shelf-pruning check does not misread this
  as stale) — [Oort's conjecture on automorphisms of generic supersingular abelian varieties (Viehmann)](https://arxiv.org/abs/2603.06033)
  — proves Oort's conjecture in full generality: generically on the supersingular locus of the
  moduli space of principally polarized abelian varieties of genus g in characteristic p, the
  automorphism group of the universal abelian variety is {±1} (explicit exceptions at g=2,3, p=2);
  a domain-cadence landmark that sat as an unpromoted queue item for 5.5 months (a near-miss
  capture-leak) until a same-day follow-up (Karemaker–Yu, arXiv:2608.16405) cited it, and now a
  further pair of Oort's-conjecture papers (2609.03711, 2609.04072/2609.03188) is active in the
  queue — worth surfacing here rather than leaving buried.
- 2026-09-04 — [θ(p_c) = 0 for Bernoulli bond percolation on ℤ^d in all dimensions (Claude / Justin Leder, Lean 4/Mathlib)](https://github.com/anthropics/formal-math/blob/795efb86f191735c5481675763537cfb4ff37e55/percolation/README.md)
  — a complete formal proof of the "dying percolation" conjecture in every dimension d ≥ 2,
  closing a famous open problem (3 ≤ d ≤ 10, incl. ℤ³) from Grimmett's textbook and
  Duminil-Copin's ICM 2018 list, via Kozma–Nitzan's 2024 reduction; unrefereed but formally
  verified in Lean/Mathlib — a landmark AI-assisted-math claim to watch for independent audit.
- 2026-09-04 — [Bounded gaps between primes down to 186, and an improved large-gaps bound (OpenAI, GPT-6 Astra)](https://cdn.openai.com/pdf/51126fac-1b68-4128-9666-c908bcc16033/short_gaps.pdf)
  — the first improvement on the bounded-gaps-between-primes record since Polymath8b's 246 (2014),
  paired with a further improvement on the Ford–Green–Konyagin–Maynard–Tao large-gaps bound
  (itself built on an intermediate GPT-5.6-Sol result); both Lean-formalized, unrefereed OpenAI
  preprints disclosed alongside the GPT-6 Astra launch.
- 2026-09-03 — [A new, independent proof that >2/3 of the Riemann zeta zeros are simple and on the critical line (Lamzouri)](https://arxiv.org/abs/2609.02882)
  — a human mathematician (York University) independently re-derives, via a shorter and more
  transparent unconditional argument, the SAME record bound (>67.25% simple-on-the-line, ≥83.62%
  distinct) that an unreleased Anthropic Claude research model claimed on 2026-08-10; the paper's
  own abstract states the Claude proof "was subsequently verified by Alpöge and Furman" — the
  strongest public vetting signal yet for one of the biggest AI-assisted-math claims this radar
  has tracked, and a clean worked example (Hilbert-space inequality + Montgomery pair-correlation)
  a number theorist should read regardless of the AI provenance.
- 2026-09-02 — [LZ's most compelling dark-matter hint to date: a single 248 keV nuclear-recoil event](https://newscenter.lbl.gov/2026/09/01/lz-sees-surprising-result-in-search-for-dark-matter)
  — the LUX-ZEPLIN collaboration's own account of an unexplained event in its WIMP search window,
  presented at TeV Particle Astrophysics 2026; explicitly NOT a claimed detection ("we are not
  claiming to have seen dark matter" — spokesperson Rick Gaitskell), but the field's most talked-
  about single data point of the week, already drawing same-day theoretical interpretation papers
  (e.g. [arXiv:2609.01583](https://arxiv.org/abs/2609.01583)); see also [Nature News](https://www.nature.com/articles/d41586-026-01985-9).
- 2026-09-01 — [Supercritical sharpness of percolation (Diskin, Easo, Radhakrishnan, Sudakov, Tassion)](https://arxiv.org/abs/2603.03257)
  — resolves a percolation-theory conjecture open since the 1980s (exponential decay of
  finite-cluster tails above criticality on every infinite transitive graph); newly spotlighted by
  Quanta Magazine (2026-08-31) as "a gem" of a proof.
- 2026-09-01 — [A 112-vertex counterexample to the Petersen Coloring Conjecture (Putman; independently verified by Jooken)](https://arxiv.org/abs/2608.10012)
  — refutes Jaeger's Petersen Coloring Conjecture via an explicit SAT-verified graph, with a
  second, fully independent hand-checkable proof ([Jooken](https://arxiv.org/abs/2608.10028))
  published one day later — a backlog catch, dated 2026-08-08/09.
- 2026-08-31 — [Evidence for coherent elastic scattering of solar neutrinos (LZ 4.5σ; XENONnT 3.3σ)](https://arxiv.org/abs/2512.08065)
  — two independent dark-matter direct-detection collaborations, LZ and XENONnT, each report
  evidence for coherent elastic neutrino-nucleus scattering (CEνNS) from solar ⁸B neutrinos in
  companion PRL papers published the same day (2026-08-28) — the "neutrino fog" floor that will
  also bound future dark-matter search sensitivity; see also the [XENONnT paper](https://arxiv.org/abs/2604.06002).
- 2026-08-31 (v1) — [The Twist Conjecture and the Isomorphism Problem for Coxeter groups (Fioravanti)](https://arxiv.org/abs/2608.28348)
  — proves Mühlherr's Twist Conjecture, which combined with prior work completes the resolution of
  the Isomorphism Problem for Coxeter groups — closing a classification question standing since
  Coxeter groups were first studied via generators and relations.
- 2026-08-28 (v1 2026-08-27) — [A proof of the Arnold-Givental conjecture (Bai, Shelukhin, Wang, Xu)](https://arxiv.org/abs/2608.27242)
  — proves the Arnold-Givental conjecture in full generality: for a closed symplectic manifold with
  an anti-symplectic involution, the Floer-theoretic Lagrangian intersection lower bound holds
  unconditionally — a 1989 conjecture resolved via integral Floer theory and a new Z/2-equivariant
  localization argument.
- 2026-08-28 (v1 2026-08-27) — [Proof of the AGT Conjecture at Generic β (Chen, Zhang)](https://arxiv.org/abs/2608.27447)
  — an all-level proof of the four-point SU(2) AGT correspondence at generic β, completing the
  17-year-old Alday-Gaiotto-Tachikawa link between 4d N=2 gauge theory and 2d Liouville/Toda CFT
  beyond the special/rational-β cases covered by prior partial proofs.
- 2026-08-27 (v1 2026-08-26) — [Matching complements in subcubic graphs and a proof of the 3-Decomposition Conjecture (Jicheng Ma)](https://arxiv.org/abs/2608.25385)
  — resolves Hoffmann-Ostenhof's 3-Decomposition Conjecture in full: every finite connected cubic
  loopless multigraph decomposes into a spanning tree, a 2-regular subgraph, and a matching — a
  long-standing "wide open" problem in structural graph theory, previously known only for
  Hamiltonian/planar cubic graphs and a special 2-factor case.
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
- 2026-08-20 (shelf-added 2026-09-12, W37 weekly queue-cleanup) — [First Search for Ultraheavy Dark Matter Using a Magnetically Levitated Particle (POLONAISE collaboration), arXiv:2608.20464](https://arxiv.org/abs/2608.20464)
  — the first search for ultraheavy dark matter using a milligram-scale ferromagnet magnetically
  levitated in a superconducting trap, a first-of-kind detection technique (axis 3, dark-matter
  detection). Abstract + authors verified via arXiv API this session.
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
- 2026-08-19 (shelf-added 2026-09-12, W37 weekly queue-cleanup) — [Thompson's Conjecture for Finite Simple Groups of Lie Type over Small Fields (Liao, Wang, Zhang), arXiv:2608.17891](https://arxiv.org/abs/2608.17891)
  — completes the proof of J. G. Thompson's conjecture in full, by settling the remaining case of
  finite simple groups of Lie type over fields of order ≤8 (axis 1, finite group theory). Abstract
  + authors verified via arXiv API this session (v1 2026-08-18). Unrefereed preprint — standard
  caution.
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
- 2026-08-18 (shelf-added 2026-09-12, W37 weekly queue-cleanup, published Phys. Rev. Lett. 137, 086501) — [Discovery of Berezinskii-Kosterlitz-Thouless Correlations in the Quantum Kagome Compound Cs2Cu3SnF12 (Grbić, Jakovac, Kupčić, Tanaka, Horvatić)](http://link.aps.org/doi/10.1103/bm42-z87g)
  — $^{63,65}$Cu NQR below $T_N=20\,$K finds signatures of Berezinskii-Kosterlitz-Thouless
  correlations in this quantum kagome antiferromagnet, a first-of-kind observation in this
  compound (axis 3, condensed-matter physics). Abstract/authors/date verified via the APS PRL RSS
  feed this session. Peer-reviewed.
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
- 2026-08-17 (shelf-added 2026-09-12, W37 weekly queue-cleanup) — [A counterexample to the Albertson-Berman conjecture about induced forests in planar graphs (Makarov), arXiv:2608.13964](https://arxiv.org/abs/2608.13964)
  — an independent, non-AI 39-vertex counterexample to the Albertson-Berman conjecture (open since
  1979) on induced forests in planar graphs, a 46-year-old named conjecture independently refuted
  by a human-only proof (axis 1, extremal/structural combinatorics). Abstract verified via arXiv
  API this session (v1 2026-08-14). Unrefereed preprint — standard caution.
- 2026-08-13 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [The Hayman–Wu constant is π² (Ivanisvili)](https://arxiv.org/abs/2608.12844) —
  determines the exact sharp constant in the 1981 Hayman–Wu problem (the bound, over every
  conformal map from the disk and every line, on the length of the preimage of the line intersected
  with the image domain); a ~45-year-old sharp-constant question settled by an established harmonic
  analyst. Unrefereed single-author preprint — PROVISIONAL, track the vetting outcome.
- 2026-08-13 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [Heat kernel geometry and Gromov's volume growth conjecture (Ge)](https://arxiv.org/abs/2608.13553)
  — answers Gromov's 1986 question affirmatively via the heat-kernel Fisher metric and Nash entropy,
  bounding the volume growth of complete noncompact manifolds with nonnegative Ricci and scalar
  curvature ≥1; a ~40-year-old named conjecture in comparison geometry. Unrefereed — PROVISIONAL.
- 2026-08-13 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [A positive answer to the generalized Chang-Yang conjecture on S^N (Gui, Li, Wei, Ye)](https://arxiv.org/abs/2608.13497)
  — proves a Beckner-inequality rigidity statement on spheres of every dimension N≥3, by an
  established PDE group (Juncheng Wei). Unrefereed — PROVISIONAL, track the vetting outcome.
- 2026-08-13 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [SOP₂=SOP₃ (Chernikov)](https://arxiv.org/abs/2608.13291) — proves the classes of
  SOP₂ and SOP₃ first-order theories coincide, answering a 2004 Džamonja–Shelah question in
  Shelah's classification-theory stability hierarchy, by a leading model theorist. Unrefereed —
  PROVISIONAL, track the vetting outcome.
- 2026-08-13 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [The Bosch and Simó conjecture on the Shilnikov-Hopf bifurcation (Rodrigues)](https://arxiv.org/abs/2608.13021)
  — proves the 1993 conjecture that "large" strange attractors persistently and robustly arise in
  the unfolding of a Shilnikov–Hopf bifurcation, with SRB measures on a positive-measure parameter
  set. Unrefereed single-author preprint — PROVISIONAL, track the vetting outcome.
- 2026-08-12 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [A Proof of Gluck's Conjecture (Zhang)](https://arxiv.org/abs/2608.11525) — settles
  a ~41-year-old open problem in finite solvable-group theory (|G:F(G)| ≤ b(G)²). Unrefereed
  single-author preprint — PROVISIONAL, track the vetting outcome.
- 2026-08-12 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [A solution to Butler's positivity conjecture (Guo, Kang, Xiong)](https://arxiv.org/abs/2608.11543)
  — proves the 1994 Butler positivity conjecture (Schur-expansion coefficients of a
  Macdonald-intersection-polynomial ratio lie in Z≥0[q,t]); a three-author, internally
  cross-verified preprint — lower epistemic risk than a single-author claim. PROVISIONAL, track
  the vetting outcome.
- 2026-08-12 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [The 196560 auxiliary-function conjecture for the Leech lattice (Zhang, Yang)](https://arxiv.org/abs/2608.12094)
  — resolves Cohn–Kumar's 2009 conjecture on a radial Schwartz function realizing the Leech-lattice
  kissing-number identity, building on the Viazovska-program Fourier-interpolation basis that
  produced the Fields-Medal-winning 8D/24D sphere-packing results. Unrefereed — PROVISIONAL.
- 2026-08-12 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [Evidence for the First Globular Cluster Stellar Stream beyond the Milky Way (Holm et al.)](https://arxiv.org/abs/2608.12254)
  — Hubble Space Telescope imaging of ultra-diffuse galaxy UGC9050-Dw1 gives the first evidence for
  an extragalactic globular-cluster tidal stream, with a dark-matter-halo mass constraint for the
  host; a first-of-kind observational claim from a single team, track for independent confirmation.
- 2026-08-11 (shelf-added 2026-09-05, W36 weekly queue-cleanup) — [Kohayakawa's conjecture and clique coverings of complements of paths and cycles (Ning)](https://arxiv.org/abs/2608.11132)
  — proves Kohayakawa's 1991 conjecture on the growth rate of maximum induced paths in a
  Kneser-graph-related bipartite construction, a ~35-year-old named conjecture in extremal
  combinatorics. Unrefereed single-author preprint — PROVISIONAL, track the vetting outcome.
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

## calibration

Append-only self-evaluation log MOVED to `logs/calibration.md` (see `radar-self-eval`).
Weekly runs APPEND there, never here.
