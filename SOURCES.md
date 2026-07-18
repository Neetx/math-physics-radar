# Sources registry — Math-Physics Radar

Agent-owned registry of monitored sources. The radar maintains and evolves this file
itself (add/remove/mark-dead entries, with a one-line reason in the day's or week's report)
— no curator sign-off needed. Skills describe the *method*; this file is the *data* (the
lists the skills iterate by force).

Hard-rule reminder: peer-reviewed journal papers and their arXiv preprints, official arXiv category listings, official experiment/collaboration and research-institute results (CERN, LIGO/Virgo/KAGRA, Fermilab, Perimeter, IAS, Clay, Simons), and formal-proof repositories (Lean/mathlib, Rocq) are PRIMARY sources (citable evidence).
Social/community sources are an INTAKE LANE ONLY — never evidence; when a social signal
links to or names a primary artifact, follow the link and verify the artifact (that artifact,
not the post, becomes evidence). Track and cite; never invent URLs/dates.

A source listed under a "swept every run" heading is a coverage PROMISE — log it opened or
`degraded: <reason>` every run. Mark each entry **[verified YYYY-MM-DD]** (URL/feed opened and
confirmed) or **[candidate]** (plausible, not yet opened — the first sweep must verify before
citing, then heal or drop). NEVER seed this file from memory: search + open real sources
(Tavily), and reject SEO/aggregator results.

---

## Cadence tiers (applied 2026-W29 — amendment A; motivated by the 3-week coverage miss W27/W28/W29 on the slow block)

The swept lists below carry TWO cadences. The **DAILY** operator owes a full CHECK of the DAILY
tier every run; the **WEEKLY** operator owes the WEEKLY-SWEPT tier once per weekly run. This makes
the daily coverage promise honest (the daily stopped iterating the slow block ~W27 in practice) and
hands the genuinely low-frequency sources to the weekly. **A source's cadence tag here OVERRIDES the
"swept EVERY run" wording in its section heading below.** Coverage honesty still applies per-tier: a
DAILY-tier source absent from a daily log line, or a WEEKLY-tier source absent from the weekly log
line, is a coverage lie for that operator.

- **DAILY tier (high-frequency — daily FULL CHECK):** CERN Courier, Fermilab, Simons Foundation (RSS);
  arXiv (all in-scope cats, RSS/API), PRL/PRX/RMP, Nature Physics, Quantum, INSPIRE-HEP, SciPost;
  the Experiments block (LIGO, DESI, CERN, IceCube — the real artifact-drop lane, tvly-light);
  Social/curator INTAKE: r/math, r/mathematics, Hacker News, MathOverflow, Mathstodon, and the full
  digest/explainer-blog lane (Quanta, Tao, Woit/Not-Even-Wrong, n-Category Café, Gowers, Kalai, Baez,
  Strassler, Hossenfelder); Discovery/exploration: arXiv-NEW listings + SciRate + Quanta-as-pointer.
- **WEEKLY-SWEPT tier (slow — weekly operator sweeps once/week):** Mathematics institutes (IHES,
  SLMath, MPIM, Fields Institute, Isaac Newton, KITP, Perimeter, IAS, Clay); slow venues (Annals of
  Mathematics, AMS Notices & Bulletin, Forum of Mathematics); low-yield extra-social (r/Physics,
  r/cosmology, r/ParticlePhysics, r/AskPhysics, Physics SE); annual prizes (Abel, Breakthrough, Shaw,
  IMU/Fields Medal). **EXCEPTION — chase daily when a ceremony is live:** the IMU/Fields lane during
  ICM season (ICM 2026: 23–30 Jul) is a daily chase, not weekly.

## Primary feeds (Phase 1 — swept EVERY run)

Method: `radar-source-sweep`. Iterate EVERY entry; prefer the feed, fall back to `tvly extract`
for feed-less ones. Filter for on-scope relevance; skip product/marketing.
These carry official RESULTS (a discovery, a data release, a solved-problem announcement = PRIMARY)
mixed with general PR (= intake — follow to the paper). Filter for on-axis research substance.
- CERN Courier — https://cerncourier.com/feed/ **[verified 2026-07-02; RSS]** — particle / high-energy physics results & reviews
- Fermilab news — https://news.fnal.gov/feed/ **[verified 2026-07-02; RSS]** — particle physics / neutrinos
- Simons Foundation — https://www.simonsfoundation.org/feed/ **[verified 2026-07-02; RSS]** — math + theoretical physics research (incl. Flatiron Institute)
- Perimeter Institute — https://perimeterinstitute.ca/news **[verified 2026-07-02; HTML → `tvly extract`]** — theoretical physics (quantum gravity, cosmology, quantum foundations)
- Clay Mathematics Institute — https://www.claymath.org/ **[verified 2026-07-02; HTML → `tvly extract`]** — Millennium Problems, math research news
- IAS (Institute for Advanced Study) — https://www.ias.edu/news **[verified 2026-07-02 via `tvly extract` — curl is 403 (Cloudflare) but tvly gets through]** — math + theoretical physics
Experiments & data-release collaborations (the real "new-artifact drop" of this domain — a detection / data release / result IS a primary artifact; follow to the collaboration paper on arXiv):
- LIGO Scientific Collaboration — https://www.ligo.org/news.php **[verified 2026-07-02; HTML → `tvly extract`]** — gravitational-wave detections/catalogs (e.g. GWTC)
- DESI (Dark Energy Spectroscopic Instrument) — https://www.desi.lbl.gov/ **[verified 2026-07-02; HTML → `tvly extract`]** — cosmology data releases & results
- CERN — https://home.cern/news **[verified 2026-07-02; HTML → `tvly extract` (the `/feed.rss` 404s)]** — collider (ATLAS/CMS) results & data
- IceCube Neutrino Observatory — https://icecube.wisc.edu/news/ **[verified 2026-07-02; HTML → `tvly extract`]** — neutrino astrophysics
- (agent: add Planck/ESA, DUNE, Rubin/LSST, Event Horizon Telescope [Cloudflare-403 2026-07-02, retry via `tvly`] as they produce)

Mathematics institutes — **[WEEKLY-SWEPT tier]** (Perimeter, Clay, IAS above also move here; weekly operator sweeps):
- IHES — https://www.ihes.fr/en/ · SLMath (ex-MSRI) — https://www.slmath.org/ · MPIM Bonn — https://www.mpim-bonn.mpg.de/ · Fields Institute — https://www.fields.utoronto.ca/ · Isaac Newton Institute — https://www.newton.ac.uk/ **[all verified 2026-07-02; HTML → `tvly extract`]** — major mathematics institutes (programs, results, workshops)
- KITP (Kavli Institute for Theoretical Physics, UCSB) — https://www.kitp.ucsb.edu/ **[verified 2026-07-02; HTML → `tvly extract`]** — theoretical-physics programs & talks (with Perimeter above, the two hubs for the field's current directions)
- (agent: add ICTP, Max Planck (MPP/AEI), Perimeter/PIRSA talks, APS *Physics* Magazine as they prove high-signal. DROPPED 2026-07-02: Symmetry Magazine — curl 403 AND `tvly` fetch BOTH fail (Cloudflare); redundant with CERN Courier + Fermilab + INSPIRE for HEP.)

## Research / publication venues (primary)
- arXiv — THE core primary venue. Math: `math.NT AG GT AT DG AC AP CO PR RT ...`; Physics: `hep-th hep-ph gr-qc cond-mat.* quant-ph astro-ph.* math-ph`. Listings `https://arxiv.org/list/<cat>/recent` **[verified 2026-07-02]**; per-category RSS `https://rss.arxiv.org/rss/<cat>` **[verified 2026-07-02; e.g. math.NT, hep-th]**; metadata via the API `https://export.arxiv.org/api/query?...` **[verified 2026-07-02]**.
- Physical Review Letters — RSS https://feeds.aps.org/rss/recent/prl.xml **[verified 2026-07-02]**
- Physical Review X — RSS https://feeds.aps.org/rss/recent/prx.xml **[verified 2026-07-02]**
- Reviews of Modern Physics — RSS https://feeds.aps.org/rss/recent/rmp.xml **[verified 2026-07-02]** (authoritative reviews)
- Nature Physics — RSS https://www.nature.com/nphys.rss **[verified 2026-07-02]**
- Annals of Mathematics — https://annals.math.princeton.edu/ **[verified 2026-07-02; HTML → `tvly extract` the latest issue]** — **[WEEKLY-SWEPT tier]**
- Quantum (open journal) — https://quantum-journal.org/feed/ **[verified 2026-07-02; RSS]** (quantum information / foundations)
- INSPIRE-HEP — API https://inspirehep.net/api/literature?sort=mostrecent&q=<query> **[verified 2026-07-02; JSON]** — the high-energy-physics literature database (papers + citations); primary lane for hep-th/hep-ph/gr-qc and a discovery signal (most-recent / most-cited).
- SciPost Physics — API `https://scipost.org/api/publications/?limit=N` **[verified/healed 2026-07-04; JSON, newest-first — the `/rss/…` and `/journals/…` paths serve JS-rendered HTML, not a feed; use the API]** — open-access, community-refereed physics (hep-th / quant / cond-mat), high signal
- AMS Notices & Bulletin — https://www.ams.org/journals/notices/ **[verified 2026-07-02; HTML → `tvly extract`]** — surveys / "what's big in math" expository pieces (great for spotting a field-shaping result) — **[WEEKLY-SWEPT tier]**
- Forum of Mathematics (Pi / Sigma) — https://www.cambridge.org/core/journals/forum-of-mathematics-pi **[verified 2026-07-02; HTML → `tvly extract`]** — open-access top-tier math — **[WEEKLY-SWEPT tier]**
- **[candidate]** Inventiones Mathematicae, JAMS, Acta Mathematica, Communications in Mathematical Physics, JHEP (open-access hep-th; also on arXiv/INSPIRE), PRD, PRB, PRResearch, Nature/Science research articles — verify feeds/ToC on first sweep; most pure-math journals lack clean RSS → `tvly extract` the current issue.

## GitHub watch (Phase 5 — repos, profiles, and fork trees)

Method: `radar-repo-watch`. Watch releases (`<repo>/releases.atom`), notable forks, and
profile activity. New releases/tools are citable artifacts; issue/PR/fork/profile movement is
a queue signal. (Agent owns and grows these lists.)

**DOMAIN NOTE (math/physics): GitHub is a MINOR lane here — keep it light, don't force it.**
Unlike software/AI, math & physics research does NOT live on GitHub — only formal-proof
libraries (Lean/mathlib, Rocq) do. The real "new-artifact drop" in this domain is (a) papers →
Research venues above, and (b) experiment/data releases & big-collaboration results (GW catalogs,
DESI/CERN/IceCube) → the Experiments block in Primary feeds above. Watch the repos below for
formalization milestones (axis 5); do NOT expect this lane to be a major signal source, and do
NOT pad it with off-axis software.

ACCESS NOTE (environment-dependent — check on first repo-watch): some scheduled-agent
environments proxy-SCOPE GitHub to only the session's own repo — external `<repo>/releases.atom`
AND `api.github.com/repos/...` both return HTTP 403 ("not enabled for this session") EVEN with
full network egress (the GitHub integration intercepts both hosts; it is not a network allowlist
to widen). If so, route the GitHub-watch lane through `tvly` — `tvly extract
https://github.com/<owner>/<repo>/releases` (Tavily fetches from its own infra, bypassing the
interception), or `tvly search` repo/tool + version + month. Lower fidelity (no commit/PR/fork
diff) but catches release tags. Retest direct `releases.atom` occasionally.

### Watched repositories
- leanprover-community/mathlib4 — **[verified 2026-07-02 via API; ~3.5k★, pushed daily]** — the Lean 4 mathematics library; a new formalization of a theorem is a citable artifact
- leanprover/lean4 — **[verified 2026-07-02 via API; active]** — the Lean theorem prover
- rocq-prover/rocq — **[verified 2026-07-02 via API; the former `coq/coq`, renamed to Rocq]** — the Rocq (ex-Coq) proof assistant
- (agent: add proof libraries / CAS as they prove high-signal — e.g. sagemath, or a repo formalizing a major theorem)

### Watched profiles/users
- github.com/leanprover-community · github.com/leanprover · github.com/rocq-prover — watch for NEW formalization repos / releases

### Fork-tree analysis
- Scan notable forks (depth ~3, scored by stars/recency) of the highest-signal repos — a
  diverging fork is often where a new capability first appears. Add a repo here once its fork
  tree proves productive. Seed targets: `leanprover-community/mathlib4` (where newly formalized mathematics first lands)

## Discovered-source candidates (auto-staged by the daily — NOT yet swept; the weekly verifies & promotes)

The source-discovery loop's staging area. The radar grows its OWN source coverage the way it
finds papers and curators: when any daily lane NAMES an on-axis primary whose publishing
org/domain is NOT already in a swept list above, the daily APPENDS/increments it here — a tally
only, NO extra fetch (you already hold the URL). The weekly VERIFIES the recurring ones (opens
the feed / HF org / repo — never from memory) and PROMOTES them into the swept registry as
`[candidate]`, pruning one-off noise. This closes the gap where an on-axis lab/vendor that
announces only on its own channel (not a tracked venue) goes untracked because no swept list
points at it. Promotion bar: ≥2 on-axis primary artifacts OR recurrence across ≥2 runs, AND it
survives verification (real feed, on-axis, not SEO). Line format:
`domain/org — times seen — last on-axis artifact (date) — first seen YYYY-MM-DD`.

- sammattheus.wordpress.com ("Points and Lines", Sam Mattheus) — 1 — Bradač off-diagonal Ramsey breakthrough (arXiv:2605.28793), reblogged by Gil Kalai (2026) — first seen 2026-07-03 — combinatorics researcher blog; pointer surface for the Ramsey-lower-bound trend.

## Social & community channels (Phase 2 — INTAKE ONLY, never evidence)

Method: `radar-pulse`. Intake feeds `observation_queue` (unverified) + the pulse note; never
name/quote individuals beyond a bare URL. Multi-channel earthquake check.
Reddit (`.rss` Atom; when a sub 429s it is rate-limit not death — retry or `tvly`). Organized by axis so gaps are visible:
- r/math — https://www.reddit.com/r/math/.rss **[verified 2026-07-02; Atom]** — the "what just got proved" pulse (pure math)
- r/mathematics — https://www.reddit.com/r/mathematics/.rss **[verified pattern]** — broader math
- r/Physics — https://www.reddit.com/r/Physics/.rss **[verified pattern; 429 2026-07-02]** — general physics — **[WEEKLY-SWEPT tier: r/Physics, r/cosmology, r/ParticlePhysics, r/AskPhysics, Physics SE — low-yield extra-social, weekly operator]**
- r/cosmology — https://www.reddit.com/r/cosmology/.rss **[verified 2026-07-02; Atom]** — cosmology / astro (axis 3)
- r/ParticlePhysics — https://www.reddit.com/r/ParticlePhysics/.rss **[verified pattern; 429 2026-07-02]** — HEP (axis 3)
- r/AskPhysics — https://www.reddit.com/r/AskPhysics/.rss **[verified pattern; 429 2026-07-02]** — broad physics pulse
- (agent: add r/QuantumComputing (foundations overlap), r/AbstractAlgebra, r/GravitationalWaves if they recur with signal)
- Hacker News — Algolia API https://hn.algolia.com/api/v1/search?tags=front_page (+ `&query=<term>`) **[known-reliable]** — earthquake check (math/physics stories, incl. big proofs)
- MathOverflow — https://mathoverflow.net/feeds/ **[healed 2026-07-02: trailing slash required (`/feeds` empty, `/feeds/` = 30 entries); Atom]** — research-level Q&A → follow to a paper
- Physics Stack Exchange — https://physics.stackexchange.com/feeds/ **[candidate; use trailing slash like MathOverflow]**
- Mathstodon (mathstodon.xyz) — public-timeline API https://mathstodon.xyz/api/v1/timelines/public **[verified 2026-07-02; JSON]** — the research-math Mastodon hub (mathematicians often post results here first). Intake only; link the thread, never name/quote individuals.

### YouTube — TRUSTED-CURATOR POINTER LANE (check EVERY run, intake only)
- (resolve each channel to its `channel_id` once, then use
  `https://www.youtube.com/feeds/videos.xml?channel_id=UC…`; follow each video's link to the
  named primary, cite the primary, never the video. Do NOT invent channel names.)
- (Scouting note 2026-07-02: research-level math/physics video is dominated by SEMINAR archives, not YouTube personalities — do NOT pad with pop-sci channels. Prefer the seminar archive **PIRSA** — https://pirsa.org (Perimeter talks) — over YouTube. Candidates, resolve `channel_id` on first use only if they repeatedly point to research primaries: IAS institute lectures, Perimeter Institute. Add a channel only when it earns it.)

### Curated digests + explainer/aggregator blogs (INTAKE LANE — swept every run)
- (follow to the named primary, verify, cite the primary, never the digest unless it is the
  original disclosure. Agent grows this list; every entry logged opened or `degraded:<reason>`.)
- Quanta Magazine — https://www.quantamagazine.org/feed/ **[verified 2026-07-02; RSS]** — the gold-standard math/physics research digest; ALWAYS follow to the named paper and cite the paper, never Quanta itself
- Terry Tao — "What's new" — https://terrytao.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — a working mathematician's research/exposition blog; follow to the arXiv/paper
- Not Even Wrong (Columbia) — https://www.math.columbia.edu/~woit/wordpress/?feed=rss2 **[verified 2026-07-02; RSS]** — math/physics (esp. HEP / string theory) commentary; intake → follow to the primary
- The n-Category Café — https://golem.ph.utexas.edu/category/ **[verified 2026-07-02; HTML → `tvly extract`]** — category theory / mathematical physics group blog
- Gowers's Weblog — https://gowers.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — Fields-medalist blog; big open problems, Polymath, expository breakthroughs
- Combinatorics and more (Gil Kalai) — https://gilkalai.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — combinatorics, convexity, and a leading QUANTUM-skeptic voice (pairs with the hype-skepticism rule)
- Azimuth (John Baez) — https://johncarlosbaez.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — mathematical physics, category theory, applied math
- Of Particular Significance (Matt Strassler) — https://profmattstrassler.com/feed/ **[verified 2026-07-02; RSS]** — HEP / particle-physics phenomenology, careful about claims
- Backreaction (Sabine Hossenfelder) — https://backreaction.blogspot.com/feeds/posts/default **[verified 2026-07-02; Atom]** — physics-foundations commentary + a prominent skeptic of hype (filter for on-axis, follow to the primary)
- **[candidate]** Shtetl-Optimized (scottaaronson.blog/?feed=rss2) — complexity / quantum foundations (shared with the quantum radar); CERN Courier (above) also serves as an HEP digest

## Discovery / exploration venues (Phase 4 — iterated EVERY run by radar-explore)

Where NEW / not-yet-tracked important work surfaces; read top/most-attention items REGARDLESS
of sub-topic, advancing the date window.
- arXiv NEW listings, rotating across the math + physics categories in scope (advance the date window each run; read the top / cross-listed items REGARDLESS of sub-topic). The core discovery lane.
- INSPIRE-HEP most-recent / most-cited — API `https://inspirehep.net/api/literature?sort=mostrecent` **[verified 2026-07-02; JSON]** — HEP attention/discovery signal (also a primary venue, above).
- Quanta Magazine (above) doubles as a discovery pointer — what the field is excited about
- Prizes & recognition — **[WEEKLY-SWEPT tier; EXCEPTION: chase the IMU/Fields lane DAILY during ICM season, 23–30 Jul 2026]** (intake — flags what the field itself deems major → follow to the laureate's actual work, cite that): Abel Prize https://abelprize.no/ **[verified 2026-07-02; HTML]** · Breakthrough Prize (math + fundamental physics) https://breakthroughprize.org/ **[verified 2026-07-02; HTML]** · Shaw Prize (Mathematical Sciences) https://www.shawprize.org/ **[verified 2026-07-12; HTML → `tvly extract` / `tvly search --include-domains shawprize.org`; the `/laureates/mathematical-sciences` path 404s, use the root + search]** · IMU / Fields Medal https://www.mathunion.org/ **[candidate — `/imu-awards` 404'd 2026-07-02, verify path]**. Sparse (mostly annual) but a strong "this was big" signal. CAPTURE the LAUREATE each cycle, not just the prize name → queue it and follow to the honored work (gap found 2026-07-12: Shaw 2026 [Candès & De Lellis] and the Breakthrough 2026 physics laureate were BOTH missed — Shaw was not even listed; the annual-laureate item must be actively chased when the ceremony date arrives).
- SciRate (scirate.com) — arXiv "scites" ranking (quant-ph/hep-th) **[healed 2026-07-04: `tvly search "<query>" --include-domains scirate.com` gets through the Cloudflare wall that 403s curl AND `tvly extract`; returns the top-scited list. KEEP — the W27 "drop" rationale was extract-only.]** — discovery/attention signal; low priority (redundant-ish with arXiv listings + INSPIRE + Quanta, but a distinct community-scited ranking).
