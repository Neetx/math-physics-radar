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
- LIGO Scientific Collaboration — https://www.ligo.org/news.php **[verified 2026-07-02; HTML → `tvly extract`]** — gravitational-wave detections/results (a GW detection is PRIMARY — follow to the collaboration paper on arXiv gr-qc)
- IHES — https://www.ihes.fr/en/ **[verified 2026-07-02; HTML → `tvly extract`]** · SLMath (ex-MSRI) — https://www.slmath.org/ **[verified 2026-07-02; HTML → `tvly extract`]** · MPIM Bonn — https://www.mpim-bonn.mpg.de/ **[verified 2026-07-02; HTML → `tvly extract`]** — major mathematics institutes (programs, results, workshops)
- (agent: add ICTP, Max Planck (MPP/AEI), Perimeter/PIRSA talks, APS *Physics* Magazine as they prove high-signal. DROPPED 2026-07-02: Symmetry Magazine — curl 403 AND `tvly` fetch BOTH fail (Cloudflare); redundant with CERN Courier + Fermilab + INSPIRE for HEP.)

## Research / publication venues (primary)
- arXiv — THE core primary venue. Math: `math.NT AG GT AT DG AC AP CO PR RT ...`; Physics: `hep-th hep-ph gr-qc cond-mat.* quant-ph astro-ph.* math-ph`. Listings `https://arxiv.org/list/<cat>/recent` **[verified 2026-07-02]**; per-category RSS `https://rss.arxiv.org/rss/<cat>` **[verified 2026-07-02; e.g. math.NT, hep-th]**; metadata via the API `https://export.arxiv.org/api/query?...` **[verified 2026-07-02]**.
- Physical Review Letters — RSS https://feeds.aps.org/rss/recent/prl.xml **[verified 2026-07-02]**
- Physical Review X — RSS https://feeds.aps.org/rss/recent/prx.xml **[verified 2026-07-02]**
- Reviews of Modern Physics — RSS https://feeds.aps.org/rss/recent/rmp.xml **[verified 2026-07-02]** (authoritative reviews)
- Nature Physics — RSS https://www.nature.com/nphys.rss **[verified 2026-07-02]**
- Annals of Mathematics — https://annals.math.princeton.edu/ **[verified 2026-07-02; HTML → `tvly extract` the latest issue]**
- Quantum (open journal) — https://quantum-journal.org/feed/ **[verified 2026-07-02; RSS]** (quantum information / foundations)
- INSPIRE-HEP — API https://inspirehep.net/api/literature?sort=mostrecent&q=<query> **[verified 2026-07-02; JSON]** — the high-energy-physics literature database (papers + citations); primary lane for hep-th/hep-ph/gr-qc and a discovery signal (most-recent / most-cited).
- **[candidate]** Inventiones Mathematicae, JAMS, Acta Mathematica, Communications in Mathematical Physics, PRD, PRB, Nature/Science research articles — verify feeds/ToC on first sweep; most pure-math journals lack clean RSS → `tvly extract` the current issue.

## GitHub watch (Phase 5 — repos, profiles, and fork trees)

Method: `radar-repo-watch`. Watch releases (`<repo>/releases.atom`), notable forks, and
profile activity. New releases/tools are citable artifacts; issue/PR/fork/profile movement is
a queue signal. (Agent owns and grows these lists.)

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

- (empty — the daily fills this; the weekly drains it)

## Social & community channels (Phase 2 — INTAKE ONLY, never evidence)

Method: `radar-pulse`. Intake feeds `observation_queue` (unverified) + the pulse note; never
name/quote individuals beyond a bare URL. Multi-channel earthquake check.
- r/math — https://www.reddit.com/r/math/.rss **[verified 2026-07-02; Atom]** — research-leaning threads; the "what just got proved" pulse
- r/Physics — https://www.reddit.com/r/Physics/.rss **[verified pattern; hit 429 rate-limit 2026-07-02 → retry or `tvly`]**
- r/mathematics, r/AskPhysics — via `tvly` **[candidate]** (broader pulse)
- Hacker News — Algolia API https://hn.algolia.com/api/v1/search?tags=front_page (+ `&query=<term>`) **[known-reliable pattern]** — earthquake check for math/physics stories
- MathOverflow — https://mathoverflow.net/feeds/ **[healed 2026-07-02: trailing slash required — `/feeds` returns empty, `/feeds/` returns 30 entries; Atom]** — research-level Q&A; a recurring hard question can flag an emerging topic (intake → follow to a paper)
- Physics Stack Exchange — https://physics.stackexchange.com/feeds **[candidate]**
- Mathstodon (mathstodon.xyz) — the research-math Mastodon instance **[candidate; `tvly` / public timeline]** — intake only; link the thread, never name/quote individuals

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
- **[candidate]** Shtetl-Optimized (scottaaronson.blog/?feed=rss2) — complexity / quantum foundations (shared with the quantum radar); CERN Courier & Symmetry (above) also serve as HEP digests

## Discovery / exploration venues (Phase 4 — iterated EVERY run by radar-explore)

Where NEW / not-yet-tracked important work surfaces; read top/most-attention items REGARDLESS
of sub-topic, advancing the date window.
- arXiv NEW listings, rotating across the math + physics categories in scope (advance the date window each run; read the top / cross-listed items REGARDLESS of sub-topic). The core discovery lane.
- INSPIRE-HEP most-recent / most-cited — API `https://inspirehep.net/api/literature?sort=mostrecent` **[verified 2026-07-02; JSON]** — HEP attention/discovery signal (also a primary venue, above).
- Quanta Magazine (above) doubles as a discovery pointer — what the field is excited about
- **[candidate — access UNRESOLVED 2026-07-02]** SciRate (scirate.com) — arXiv "scites" ranking (quant-ph/hep-th), but curl 403 AND `tvly extract` BOTH fail (Cloudflare). First sweep: try `tvly search --include-domains scirate.com` or the SciRate API; if still unreachable, DROP (discovery is already covered by arXiv listings + INSPIRE + Quanta).
