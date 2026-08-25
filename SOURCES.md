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
- OpenAI research-publication pages — https://openai.com/research / https://cdn.openai.com **[promoted
  2026-08-08; no subscribable feed — access via periodic `tvly search "openai.com math theoretical
  computer science" ` / direct URL checks when a disclosure is flagged elsewhere]** — AI-WATCH-LANE
  PRIMARY (track the mathematical RESULTS disclosed, never the AI method — sibling AI radars' beat):
  a recurring direct off-arXiv disclosure channel for AI-claimed math/TCS results (the Cycle-Double-
  Cover proof, then "Ten Advances in Mathematics and Theoretical Computer Science" 2026-08-01) —
  source-discovery promotion after 2 tracked disclosure events on this channel.
Experiments & data-release collaborations (the real "new-artifact drop" of this domain — a detection / data release / result IS a primary artifact; follow to the collaboration paper on arXiv):
- LIGO Scientific Collaboration — https://www.ligo.org/news.php **[verified 2026-07-02; HTML → `tvly extract`. DEGRADED 2026-08-25: direct `curl` (even with a browser UA) now hits a Cloudflare "Attention Required" challenge page — `tvly extract` needed, but `tvly` was quota-exhausted this session; no working direct-fetch fallback found. First occurrence — retest next daily before treating as standing.]** — gravitational-wave detections/catalogs (e.g. GWTC)
- DESI (Dark Energy Spectroscopic Instrument) — https://www.desi.lbl.gov/ **[verified 2026-07-02; HTML → `tvly extract`]** — cosmology data releases & results
- CERN — https://home.cern/news **[verified 2026-07-02; HTML → `tvly extract`. HEALED 2026-08-24:
  the bare `/news` HTML page now Cloudflare/WAF-blocks direct `curl` (`wpewaf.com` challenge), but
  `https://home.cern/feed/` (RSS, NOT `/feed.rss` which 404s) works cleanly via plain `curl` —
  prefer the `/feed/` RSS going forward.]** — collider (ATLAS/CMS) results & data
- IceCube Neutrino Observatory — https://icecube.wisc.edu/news/ **[verified 2026-07-02; HTML → `tvly extract`]** — neutrino astrophysics
- (agent: add Planck/ESA, DUNE, Rubin/LSST, Event Horizon Telescope [Cloudflare-403 2026-07-02, retry via `tvly`] as they produce)

Mathematics institutes — **[WEEKLY-SWEPT tier]** (Perimeter, Clay, IAS above also move here; weekly operator sweeps):
- IHES — https://www.ihes.fr/en/ · SLMath (ex-MSRI) — https://www.slmath.org/ · MPIM Bonn — https://www.mpim-bonn.mpg.de/ · Fields Institute — https://www.fields.utoronto.ca/ · Isaac Newton Institute — https://www.newton.ac.uk/ **[all verified 2026-07-02; HTML → `tvly extract`]** — major mathematics institutes (programs, results, workshops)
- KITP (Kavli Institute for Theoretical Physics, UCSB) — https://www.kitp.ucsb.edu/ **[verified 2026-07-02; HTML → `tvly extract`]** — theoretical-physics programs & talks (with Perimeter above, the two hubs for the field's current directions)
- (agent: add ICTP, Max Planck (MPP/AEI), Perimeter/PIRSA talks, APS *Physics* Magazine as they prove high-signal. DROPPED 2026-07-02: Symmetry Magazine — curl 403 AND `tvly` fetch BOTH fail (Cloudflare); redundant with CERN Courier + Fermilab + INSPIRE for HEP.)

## Research / publication venues (primary)
- arXiv — THE core primary venue. **The math-side scan is a BOUNDED-CYCLE ROTATION over the FULL in-scope category set, NOT a fixed math.CO/NT anchor:** advance a category-rotation pointer each run (record it in the coverage-log line) so EVERY in-scope math category is opened within ~2 weeks — algebra & geometry `math.AG` (algebraic geometry), `math.AC` (commutative algebra), `math.RA`, `math.KT`, topology `math.AT`/`math.GT`/`math.DG`/`math.SG`, analysis `math.AP`/`math.FA`/`math.CA`/`math.CV`, alongside the `math.NT CO PR RT DS LO OA OC` already routinely covered. A category that is in-scope yet never appears in `logs/source_rotation.md` is a coverage gap — the same listed-but-not-swept lie as an unswept source, at the category grain (this is how a whole live area, e.g. the Jacobian-conjecture math.AG stream, stayed invisible until 2026-07-23). Physics: `hep-th hep-ph gr-qc cond-mat.* quant-ph astro-ph.* math-ph` (many have RSS below). Listings `https://arxiv.org/list/<cat>/recent` **[verified 2026-07-02]**; per-category RSS `https://rss.arxiv.org/rss/<cat>` **[verified 2026-07-02; e.g. math.NT, hep-th]**; metadata via the API `https://export.arxiv.org/api/query?...` **[verified 2026-07-02]**.
- Physical Review Letters — RSS https://feeds.aps.org/rss/recent/prl.xml **[verified 2026-07-02]**
- Physical Review X — RSS https://feeds.aps.org/rss/recent/prx.xml **[verified 2026-07-02]**
- Reviews of Modern Physics — RSS https://feeds.aps.org/rss/recent/rmp.xml **[verified 2026-07-02]** (authoritative reviews)
- Nature Physics — RSS https://www.nature.com/nphys.rss **[verified 2026-07-02; RSS feed has served
  empty-CDATA titles for 7+ consecutive dailies as of 2026-08-21 — standing degraded. PARTIAL HEAL
  2026-08-21: for an ALREADY-NAMED Nature-family article (found via a digest/pulse pointer), `curl
  -A "Mozilla/5.0" <article-url>` returns HTTP 200 with full `citation_*` meta tags
  (title/authors/journal/DOI/date), bypassing the `idp.nature.com` auth-wall that blocks `WebFetch`
  on the same URL — use this to cite a named article. Does NOT fix "browse what's new": the
  `current-issue` HTML index is client-rendered and returns no article list via plain `curl`.]**
- Nature Communications — RSS https://www.nature.com/ncomms.rss **[promoted + verified 2026-08-08;
  redirects to feeds.nature.com/ncomms/rss/current; RSS]** — peer-reviewed open-access Nature-group
  journal distinct from Nature Physics; source-discovery promotion (2 on-axis math↔physics-interface
  primaries in one week: RH↔quantum-phase-transitions 07-01, aperiodic-monotile chirality 07-29,
  both discovered via r/math pointers)
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
- **[healed 2026-08-08]** Release-tag reads on the bare `/releases` page keep returning a JS-shell nav
  via `tvly extract` (standing failure) — `tvly search "<owner>/<repo> latest release version tag"
  --include-domains github.com` reliably surfaces the actual tag text instead; use search first for
  lean4/mathlib4/rocq version-tag checks, fall back to `extract` only to confirm a URL.
- **[healed 2026-08-14]** SUPERSEDES the above for reliability: `tvly extract
  https://github.com/<owner>/<repo>/releases.atom` (the Atom feed, not the bare HTML page) works
  cleanly every time — no JS-shell nav, no stale-search risk. Prefer `.atom` first for
  lean4/mathlib4/rocq; fall back to `tvly search` only if `.atom` ever fails.
- **[healed 2026-08-24]** In an environment where GitHub is session-proxy-scoped (direct `curl`/API
  on `<repo>/releases.atom` returns "sessions are bound to their configured repositories"),
  `WebFetch` on the plain `releases.atom` URL works cleanly and returns accurate release-tag +
  date lists — verified this session for all three watched repos. Works even when `tvly` is
  quota-exhausted (as it was this session) — prefer `WebFetch` on `.atom` as the primary fallback
  in a proxy-scoped environment, ahead of `tvly extract`. NOTE:
  leanprover-community/mathlib4 does NOT tag discrete semantic-version releases like lean4/Rocq
  do — its `releases.atom` instead shows continuous daily `master-YYYY-MM-DD` auto-tags; a
  "latest version tag" search for mathlib4 will legitimately come up empty/stale because there is
  no such tag — read its daily `master-*` tag instead, don't treat the absence as degraded.
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

- sammattheus.wordpress.com ("Points and Lines", Sam Mattheus) — 1 — Bradač off-diagonal Ramsey breakthrough (arXiv:2605.28793), reblogged by Gil Kalai (2026) — first seen 2026-07-03 — combinatorics researcher blog; pointer surface for the Ramsey-lower-bound trend. HELD below the ≥2 bar (W32 recheck: no recurrence).
- journals.aps.org/prresearch (Physical Review Research) — 1 — Barontini, "Testing the problem of time with cold atoms" (arXiv:2509.07745, PRR publication) — first seen 2026-08-03 — an APS journal distinct from the already-tracked PRL/PRX/RMP RSS feeds; discovered via a University of Birmingham press pointer. HELD below the ≥2 bar (W32 recheck: no recurrence); feed PRE-VERIFIED this session — `https://feeds.aps.org/rss/recent/prresearch.xml` (RSS, 200) — ready for instant promotion on the next sighting.
- leodemoura.github.io (Leonardo de Moura, Lean FRO chief architect) — 1 — "Postmortem for Kernel Soundness Bug #14576" (2026-08-01), discovered via an r/math pointer — first seen 2026-08-03 — high-signal technical-disclosure blog for axis-5 Lean-kernel integrity events, the closest thing to an official primary for internal Lean toolchain issues. HELD below the ≥2 bar (W32 recheck: no recurrence); feed PRE-VERIFIED this session — `https://leodemoura.github.io/feed.xml` (RSS, 200) — ready for instant promotion on the next sighting.
- sbseminar.wordpress.com ("Secret Blogging Seminar", incl. David Speyer) — 1 — "The new counterexample to the Jacobian conjecture" working-through of the announced 3-variable Keller-map counterexample (2026-07) — first seen 2026-07-23 — research-mathematician group blog; high-signal pointer surface for the AI-assisted-math-wave / Jacobian-conjecture story (found via community pulse). HELD below the ≥2 bar (W32 recheck: no recurrence in 2 weeks).
- ams.org/journals/jams (Journal of the American Mathematical Society) — 1 — Smith, "The distribution of ℓ∞-Selmer groups in degree ℓ twist families I/II" (JAMS 39(1)/39(2), 2026, resolving the 2-primary Cohen-Lenstra problem) — first seen 2026-08-06 — a specific top-tier AMS journal distinct from the already-tracked AMS Notices & Bulletin; discovered via Scientific American science coverage. HELD below the ≥2 bar (W32: 1 sighting still); no RSS, `tvly extract` works (curl 403s) — access method recorded for next verification pass.
- bourbaki.fr (Séminaire Bourbaki) — 1 — "Recent Progress around Cohen-Lenstra Heuristics" survey (arXiv:2606.06024, used this session to corroborate the Smith JAMS landmark) — first seen 2026-08-06 — an expository survey venue (like AMS Notices), useful for spotting "what's big" in a subfield; the surveys themselves are exposition, cite through to the actual primaries. HELD below the ≥2 bar (W32: 1 sighting still); no RSS, `tvly extract` works on the static page.
- anthropic.com/research (Anthropic research-publication pages) — 1 — "More Than Two Thirds of the Zeros of the Riemann Zeta Function Lie on the Critical Line" (Claude, 2026-08-10), discovered via r/math + r/mathematics pointers — first seen 2026-08-11 — a direct off-arXiv AI-lab disclosure channel for AI-claimed math results, the same pattern as the already-tracked openai.com/cdn.openai.com lane; HELD below the ≥2 bar (1 sighting); no RSS, access via `tvly search "anthropic.com research math"` / direct URL checks when a disclosure is flagged elsewhere (paths seen this session: `anthropic.com/research/<slug>`, PDFs under `www-cdn.anthropic.com`).
- proofatlas.ai — 1 — "A Computer-Assisted Proof of Sendov's Conjecture" (Lech Mazur / OpenAI GPT-5.6 Pro, 2026-08-05), discovered via a Terence Tao blog-post link (2026-08-12) — first seen 2026-08-13 — a dedicated self-publication platform for AI-generated math proofs, structurally the same AI-disclosure-lane pattern as openai.com/cdn.openai.com and anthropic.com/research; HELD below the ≥2 bar (1 sighting); no RSS/feed found, access via direct URL (`proofatlas.ai/papers/<slug>/<FILE>.pdf`) when a disclosure is flagged elsewhere (e.g. via Tao/Quanta/community pulse), or `tvly search "proofatlas.ai <topic>"`.

- preprints.org — 1 — Shanmu Jin, "The Numerical Range Is a 2-Spectral Set" (DOI 10.20944/preprints202607.1919, a second independent AI-assisted proof of Crouzeix's conjecture, predating the already-tracked Lorist-Schwenninger arXiv proof) — first seen 2026-08-18 — an MDPI-run general preprint server (broader scope than arXiv), used here as an off-arXiv AI-disclosure-lane venue, same pattern as proofatlas.ai/openai.com/anthropic.com; HELD below the ≥2 bar (1 sighting); access via `tvly extract` on the manuscript page (works cleanly, no feed found).

PROMOTED 2026-08-08 (W32): nature.com/ncomms (2 sightings → Research/publication venues, DAILY tier),
scientificamerican.com (2 sightings → Curated digests, DAILY tier), openai.com/cdn.openai.com
(recurring disclosure channel → Primary feeds AI-watch lane, DAILY tier) — see their entries above;
cleared from this staging list.

## Social & community channels (Phase 2 — INTAKE ONLY, never evidence)

Method: `radar-pulse`. Intake feeds `observation_queue` (unverified) + the pulse note; never
name/quote individuals beyond a bare URL. Multi-channel earthquake check.
Reddit (`.rss` Atom; when a sub 429s it is rate-limit not death — retry or `tvly`). Organized by axis so gaps are visible:
- r/math — https://www.reddit.com/r/math/.rss **[verified 2026-07-02; Atom — DEGRADED again 2026-08-14/08-17/08-18: direct curl and `tvly extract` both blocked/failed 3 dailies running. HEALED 2026-08-18: `tvly search "<query terms>" --include-domains reddit.com --time-range week` reliably returns live individual r/math thread URLs (verified against real, dated August 2026 threads this session) — prefer this over `.rss`/`extract` until the direct block lifts; retest `.rss` occasionally. COMPOUNDED 2026-08-20/08-21: the `tvly` heal is unusable while the account's Tavily plan quota is exhausted (see `strategy_notes`), and `WebFetch` fails outright ("unable to fetch from www.reddit.com") on both `.rss` and `old.reddit.com` — no working fallback found either day; 6th+ consecutive degraded daily.]** — the "what just got proved" pulse (pure math)
- r/mathematics — https://www.reddit.com/r/mathematics/.rss **[verified pattern; same DEGRADED/HEALED status as r/math above — use `tvly search --include-domains reddit.com`]** — broader math
- r/Physics — https://www.reddit.com/r/Physics/.rss **[verified pattern; 429 2026-07-02]** — general physics — **[WEEKLY-SWEPT tier: r/Physics, r/cosmology, r/ParticlePhysics, r/AskPhysics, Physics SE — low-yield extra-social, weekly operator]**
- r/cosmology — https://www.reddit.com/r/cosmology/.rss **[verified 2026-07-02; Atom]** — cosmology / astro (axis 3)
- r/ParticlePhysics — https://www.reddit.com/r/ParticlePhysics/.rss **[verified pattern; 429 2026-07-02]** — HEP (axis 3)
- r/AskPhysics — https://www.reddit.com/r/AskPhysics/.rss **[verified pattern; 429 2026-07-02]** — broad physics pulse
- (agent: add r/QuantumComputing (foundations overlap), r/AbstractAlgebra, r/GravitationalWaves if they recur with signal)
- Hacker News — Algolia API https://hn.algolia.com/api/v1/search?tags=front_page (+ `&query=<term>`) **[known-reliable]** — earthquake check (math/physics stories, incl. big proofs)
- MathOverflow — https://mathoverflow.net/feeds/ **[CORRECTED 2026-08-25: the 2026-07-02 "trailing slash required" note is stale — `/feeds/` now 307-redirects to `/feeds` (no trailing slash); `curl -sL` (follow redirects) on either path works cleanly. Atom.]** — research-level Q&A → follow to a paper
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
- The n-Category Café — https://golem.ph.utexas.edu/category/ **[verified 2026-07-02; HTML → `tvly
  extract`. HEALED 2026-08-21: plain `curl -A "Mozilla/5.0"` returns HTTP 200 with full post-title
  HTML directly, no Cloudflare/JS block found — prefer direct `curl` first, `tvly extract` as
  fallback.]** — category theory / mathematical physics group blog
- Gowers's Weblog — https://gowers.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — Fields-medalist blog; big open problems, Polymath, expository breakthroughs
- Combinatorics and more (Gil Kalai) — https://gilkalai.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — combinatorics, convexity, and a leading QUANTUM-skeptic voice (pairs with the hype-skepticism rule)
- Azimuth (John Baez) — https://johncarlosbaez.wordpress.com/feed/ **[verified 2026-07-02; RSS]** — mathematical physics, category theory, applied math
- Of Particular Significance (Matt Strassler) — https://profmattstrassler.com/feed/ **[verified 2026-07-02; RSS]** — HEP / particle-physics phenomenology, careful about claims
- Backreaction (Sabine Hossenfelder) — https://backreaction.blogspot.com/feeds/posts/default **[verified 2026-07-02; Atom]** — physics-foundations commentary + a prominent skeptic of hype (filter for on-axis, follow to the primary)
- **[candidate]** Shtetl-Optimized (scottaaronson.blog/?feed=rss2) — complexity / quantum foundations (shared with the quantum radar); CERN Courier (above) also serves as an HEP digest
- Scientific American — https://www.scientificamerican.com/ **[promoted 2026-08-08; no working RSS
  found (`/feed/` 404s, `rss.sciam.com` empty) — access via `tvly search --include-domains
  scientificamerican.com`, already used successfully twice]** — mainstream science press with
  occasional deep math/physics coverage AND original reporting with named credentialed-expert quotes
  (the 2026-08-06 OpenAI attribution-misconduct story); follow to the primary it names, cite the
  article itself only for on-record expert commentary that has no other primary source (as with a
  vetting-outcome report). Source-discovery promotion (2 sightings this session: the Cohen-Lenstra
  landmark pointer 08-05, original misconduct reporting 08-06).

## Discovery / exploration venues (Phase 4 — iterated EVERY run by radar-explore)

Where NEW / not-yet-tracked important work surfaces; read top/most-attention items REGARDLESS
of sub-topic, advancing the date window.

**OFF-AXIS ROTATION (formalized 2026-W29 — amendment B; motivated by the off-axis=0 anchoring
warning W27/W28, now easing to 1/5 in W29).** Reading arXiv-NEW top items alone is NOT enough:
those are on-axis by construction (they land in the ledger's tracked categories), which is what
drove off-axis discovery to 0 for two weeks. So EVERY run the explore slot must ALSO deliberately
read the top / most-attention items of ONE genuinely off-axis venue and queue anything significant
as "significant, off-axis" (even zero-yield reads are logged). ROTATE the off-axis venue each run so
coverage advances — a suggested roster (extend freely; do not re-read the same one two runs running):
`math.DS` (dynamical systems), `math.OC` (optimization), `math.LO` (logic / foundations),
`math.OA` (operator algebras), `math.DG` (differential geometry), `math.NA` (numerical analysis),
`cs.CC` (computational complexity), `nlin.SI` / `nlin.CD` (integrable / chaotic), `q-bio.PE`,
`math.PR`↔`math.ST` (probability/statistics interface), `econ`/`q-fin` (math-adjacent). The test is
SIGNIFICANCE-first (read the top items regardless of sub-topic), not keyword search on tracked axes.
- arXiv NEW listings, rotating across the math + physics categories in scope (advance the date window each run; read the top / cross-listed items REGARDLESS of sub-topic). The core discovery lane. **Pair this on-axis core with the OFF-AXIS ROTATION directive above every run.**
- INSPIRE-HEP most-recent / most-cited — API `https://inspirehep.net/api/literature?sort=mostrecent` **[verified 2026-07-02; JSON]** — HEP attention/discovery signal (also a primary venue, above).
- Quanta Magazine (above) doubles as a discovery pointer — what the field is excited about
- Prizes & recognition — **[WEEKLY-SWEPT tier; EXCEPTION: chase the IMU/Fields lane DAILY during ICM season, 23–30 Jul 2026]** (intake — flags what the field itself deems major → follow to the laureate's actual work, cite that): Abel Prize https://abelprize.no/ **[verified 2026-07-02; HTML]** · Breakthrough Prize (math + fundamental physics) https://breakthroughprize.org/ **[verified 2026-07-02; HTML]** · Shaw Prize (Mathematical Sciences) https://www.shawprize.org/ **[verified 2026-07-12; HTML → `tvly extract` / `tvly search --include-domains shawprize.org`; the `/laureates/mathematical-sciences` path 404s, use the root + search]** · IMU / Fields Medal https://www.mathunion.org/ **[candidate — `/imu-awards` 404'd 2026-07-02, verify path]**. Sparse (mostly annual) but a strong "this was big" signal. CAPTURE the LAUREATE each cycle, not just the prize name → queue it and follow to the honored work (gap found 2026-07-12: Shaw 2026 [Candès & De Lellis] and the Breakthrough 2026 physics laureate were BOTH missed — Shaw was not even listed; the annual-laureate item must be actively chased when the ceremony date arrives).
- SciRate (scirate.com) — arXiv "scites" ranking (quant-ph/hep-th) **[healed 2026-07-04: `tvly search "<query>" --include-domains scirate.com` gets through the Cloudflare wall that 403s curl AND `tvly extract`; returns the top-scited list. KEEP — the W27 "drop" rationale was extract-only.]** — discovery/attention signal; low priority (redundant-ish with arXiv listings + INSPIRE + Quanta, but a distinct community-scited ranking).
