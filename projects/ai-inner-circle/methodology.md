# The AI Inner Circle — methodology, edition 01

The original sample was reviewed on 14 October 2026; a targeted connection
survey was added on 27 October 2026. Individual source and relationship review
dates are retained. This is a versioned historical, purposive
relationship catalogue, not a live directory or a representative census of AI.

## Formal history and institutional affiliations

The separate affiliation layer records employment, founding, internships,
education, public memberships, governance and fellowships. Each record has a
person ID, institution ID, role, sources, A/B evidence grade, review date and
nullable dates. Education explicitly distinguishes completed qualifications,
attendance without completion, studies ongoing at source, and unknown completion.
Honorary qualifications are not treated as earned degrees. Missing dates are
never guessed from a biography’s publication day. Roles marked ongoing refer to
the supporting source date, not a claim that they are current in October 2026.

Person–institution links are kept separate from interpersonal records. Shared
employers, alma maters or clubs do not produce cliques, shorten person-only paths
or enter person-only centralities. Institution views show only recorded members
within this sample. Public reading groups and society memberships need explicit
evidence; event attendance, awards and satire do not establish membership.

`history-coverage.json` tracks partial review separately for career, education and
organisations for every profile. The dataset records 280 affiliations for 49
partially reviewed profiles; employment has been reviewed for 48 people, education
for 31, and organisations for 23. The other 211 profiles await structured history
review. Even reviewed histories are partial. Existing source-backed profile fields
remain available for all 260 people; unrecorded jobs, degrees and clubs are unknown,
not absent.

The company survey adds sourced records for Apple, Microsoft, Google, NVIDIA,
AMD, Oracle, IBM and Meta. Their records appear in the person–institution view.
They include historical founders and leadership snapshots; they are not a census
of employees and do not imply that everyone at the same company knows each other.
Companies are relevant to this investigation through their people and documented
connections to the AI network; a company partnership alone does not establish a
personal relationship. A `partnership` edge requires a specific, named
representative-level professional partnership, such as executives publicly
announcing and describing a joint effort. It records the business connection,
not friendship.

The October connection survey adds individually sourced introductions,
friendships, relationships, and early investments. An introduction record may be
directed from the introducer to one recipient, with the other participant named
in `introduced_person_ids`; where the documented link is between the two people
being introduced, it may instead be recorded as an undirected event between them,
with the intermediary named in `introduced_by_person_ids`. Introduction records
describe a specific event, not a claim of continuing friendship. An investment
record describes investment in a founder's company, not money transferred to that
person. Roles and relationships marked
ongoing are current only at the time of the cited source. Some published reports
give conflicting accounts of who introduced Clark and Amodei; the Clark-to-Schmidt
introduction remains a B-grade reported claim with its sources and alternatives
documented in the survey notes.

A further multi-agent source survey adds individually documented family,
friendship, teaching, mentoring, introduction and collaboration ties. It also
corrects an Apple leadership role to reflect the December 2025 announcement that
its holder was stepping down. The survey is selective, and does not claim that
all relationships or career histories have been found.

Named signatories to the September 2026 White House Accord are recorded pairwise
as a shared signing event. The record captures the joint signature and stated
collective commitment only; it does not assert bilateral work or that subsequent
meetings occurred.

The 30 October 2026 expansion and subsequent research passes add roster-to-roster
coauthor links from 80 selected high-overlap papers: the original GAN, Transformer and BERT
papers; GPT-3 and scaling laws; the LLaMA, Llama 2, Code Llama, Mistral 7B,
Mixtral, Pixtral, Magistral, Playing Atari, Asynchronous Methods, Decoupled
Neural Interfaces, GPT-4o System Card, two Anthropic model-evaluation and safety
papers, Sleeper Agents, two factor-graph papers, NAPS, four GLM-family papers,
BLOOM, the BigScience case study, Stronger Together and Economies of Open
Intelligence. Later passes add Dropout, Toronto research-lineage papers, a HyperNetworks coauthorship link between David Ha and Quoc V. Le, three CMU coauthored speech-recognition papers by Kai-Fu Lee and Raj Reddy, and 15 papers involving William W. Cohen with Zhilin Yang, Ruslan Salakhutdinov, Zihang Dai, Kaiming He or Yann LeCun (1986, 1989 and 1990),
LaMDA, PaLM, the GPT-4 Technical Report, Gemini 1.0 and Gemini 1.5, the Aya
23 and Aya Expanse reports, the Gopher scaling paper, two 2006 papers coauthored by Andrew Ng and William W. Cohen; three Jégou–Grave papers (2016, 2019, 2024), a Jégou–Lample paper (2019), and additional Jégou–Joulin sources; and four AlphaGo,
AlphaGo Zero, AlphaZero and MuZero papers, plus
complete founder-team links for the original OpenAI cohort, Anthropic, SenseTime,
Thinking Machines Lab and Perplexity. A source-level audit completed all
roster-to-roster pairs among represented authors for 113 cited paper sources,
retaining 592 paper-specific evidence assertions on consolidated coauthor links.
These are explicit professional ties, not claims of friendship. The selection still
does not cover every publication, every roster member on every source, or every
public relationship type. Research is ongoing and the graph is not yet exhaustive.

Specific personal-event roles, such as officiating a wedding, are recorded as
`personal_event` informal ties without implying friendship or kinship. Brockman’s
wedding event is dated only to 2019, the precision independently established in
the reporting. Dated wealth estimates are profile annotations, not financial
relationships or node-size weights. The available Bloomberg snapshot supports
$25.5 billion on 7 October 2026; the July date and detailed asset composition in
the user’s lead were not independently established here.

## Scope and inclusion

The original attachment contains the execution brief only. The prior chat titled
“Construire un graphe de réseau IA” was located, but the readable response contains
content references rather than its original files, and lists no attachments. The
216-candidate prototype and its source evidence could not be retrieved. This
edition was independently reconstructed; it does not imply the old claims passed
an audit.

Research began with PayPal, Y Combinator, OpenAI and its diaspora, academic AI,
Google/DeepMind, venture founders and newer laboratories. Explicit connections
expanded the catalogue into European and Chinese research networks and open-model
collaborations. Some historical collaborators are included as connecting figures;
inclusion does not imply current industry influence. Large-paper authors without
a selected verified relationship remain explicitly unconnected profiles.

The reviewed research fragments in `research/` are the authoritative input.
They preserve profile evidence, individual source records and discovery notes.
Research involved original announcements, papers, thesis acknowledgments, public
first-person essays/interviews, official biographies and specific reporting.
Some pages were reviewed through indexed source text when direct retrieval was
unavailable; the relevant source summary records that limitation. Full page
archives are not bundled. A review date means evidence was inspected, not that a
source link will always be live or that the relationship is still current.

## Evidence and privacy

- **A:** primary material or authoritative reporting specifically supporting the
  described tie. In this edition primary evidence is preferred, and secondary
  informal claims are generally graded B.
- **B:** credible, sufficiently specific secondary accounts. These remain visible
  by default, with their grade shown; users can restrict the graph to A.
- **C:** unresolved claims. These appear only in `research-backlog.json`, never in
  the published graph or network calculations.

Confidence describes support for a proposition, not relationship closeness or
economic importance. A corporate biography supports that biography's claims,
not an independently measured power ranking. A publication coauthor list supports
coauthorship, not a claim that every author knows every other author personally.

Shared employment, matching universities, event attendance, photographs and
social-media interactions do not create interpersonal edges. No private
addresses, unpublished personal details or speculative romantic claims were
investigated. Documented family ties are included only when explicitly public.

## Schema

`people.csv` / `people.json`:

| Field | Meaning |
| --- | --- |
| id | Stable normalized person identifier |
| name | Public full name |
| affiliation | Source-supported affiliation, often historical |
| historical_affiliations | Other documented affiliation labels |
| role | Documented role or contribution |
| communities | Overlapping curated research communities |
| region | Known documented region, or null; never inferred from a name |
| source_ids | Profile-supporting source IDs |
| profile_status | verified means basic profile facts have evidence, not all possible ties |

`relationships.csv` / `relationships.json`:

| Field | Meaning |
| --- | --- |
| id | Stable relationship record identifier |
| source, target | Person IDs |
| type, category | Specific tie and analytical category |
| description, evidence | Proposition and concise paraphrase of supporting evidence |
| start_date, end_date | Supported dates or source observation, null if unknown |
| status | historical, ongoing_at_source, or unknown |
| directed | Whether direction is part of the stated relationship |
| source_ids | One or more references into the source register |
| confidence | A or B for public records |
| verification_status | verified for public records |
| checked_on | Evidence review date |
| discovery_note | How the source and tie were reviewed |
| assertions | Source-specific original propositions after duplicate consolidation |

CSV array/object cells contain JSON, and null scalar fields are empty. CSV uses
UTF-8 and RFC-style quoting; JSON preserves nulls and booleans without ambiguity.
The consolidated `dataset.json` contains people, ties, sources and metadata.

Source records carry an ID, URL, title, publisher, primary/secondary classification,
publication date when known, review date and concise evidence description.
Assertions keep their own dates and source IDs. The input fragments remain
available for auditing any consolidation.

## Relationship taxonomy

| Category | Types |
| --- | --- |
| Informal | Explicit friendship, documented classmates, family, housemates, mentorship, personal gestures |
| Professional | Cofounding, documented direct collaboration, professional advice, professional interaction, recruitment, coauthorship (papers and books), doctoral and other thesis supervision, dissertation committee service, reporting relationship, documented work under a named leader, professional partnership |
| Financial | Personal angel financing, backing for a roster member's venture fund, documented co-investment in a named round |

`co_investment` also records named people in the same documented financing
round; it indicates financial overlap only, not a social relationship. A
`fund_backing` tie records a documented investment in or financing of a
venture fund managed or launched by another roster member; it does not mean
the investor backed every startup in that fund. An
`reporting_line` records a named person's direct reporting relationship when an
authoritative source states it; it is a dated professional tie, not evidence of
friendship.
`employment` records a roster member's explicit first-person statement that they
worked under another named person. It preserves that wording without inferring a
specific project or direct reporting line.
`recruitment` records an explicit, source-backed instance of one roster member
recruiting another into a professional role. It does not imply a continuing
reporting relationship or mentorship.
`classmate` records people explicitly identified as classmates at a named
educational institution; it does not imply friendship or collaboration.
`professional_advice` records a specific, sourced instance of one roster member
giving another advice in a professional context; it does not imply a continuing
mentoring relationship.
`professional_interaction` records a confirmed direct meeting or exchange in a
professional setting when the source does not establish joint work or advice.
`personal_gesture` records a specific reported personal act between two people;
it does not imply friendship or continuing contact.

Doctoral supervision is classified as professional because it is a formal
academic relationship. Mentorship is informal where explicitly described as
advice or continuing personal guidance. Some mentorship is reciprocal; directed
records retain that distinction.
`thesis_supervision` records an explicitly documented supervisory role for a
thesis other than the doctoral dissertation; it is kept distinct from doctoral
advising and informal mentorship.
`committee_service` records an explicitly named member of a roster member's
doctoral dissertation or examination committee. Committee service does not
imply that the committee member was the student's advisor.

Personal financing of a founder's company is not a payment to the founder. It is
only included when the evidence identifies the individual investor, founder and
venture. Firm-to-company investments are not transformed into person pairs.
Co-founding a venture fund remains a professional edge; it does not establish
every subsequent investment or friendship. This makes financial coverage very
sparse. It is unsuitable for measuring capital concentration.

## Identity and duplicate audit

Unicode-normalized names reconcile accented spellings across fragments; a
recorded alias handles Ian J. Goodfellow / Ian Goodfellow. The merge log records
changes of person identifiers. Profile sources, communities and historical
affiliations are retained on identity merges.

Exact duplicate descriptions are merged. Repeated cofounder/coauthor evidence
for a typed pair is then consolidated into one record with original assertions.
Separate papers remain visible in those assertions. Multiple relationship types
for one pair remain separate records. The graph projection counts that pair
only once. Reciprocal mentorship records remain distinct directed assertions.

The pipeline validates required fields, missing sources, unknown IDs, identity
duplicates, repeated relationship records, supported types, valid date precision,
calendar dates, chronological order and A/B-only publication status. These checks
detect structural mistakes, not factual truth. A human evidence review is still
necessary to decide whether a source actually supports its proposition.

## Scientific collaboration selection

Coauthor ties were originally selected for meaningful coverage of named founders,
influential papers and cross-community research lineages. The 30 October
expansion now records every within-roster pair for the thirty cited papers above,
but does not cover every publication by every listed person. Selection is
documented in input discovery notes. Coverage remains incomplete and can change
degree, communities and shortest paths.
A full author–paper bipartite/hypergraph is a future methodological extension.
The analysis also removes all coauthor ties as a sensitivity check.

## Network calculations

Calculations use dependency-free JavaScript implementations in `graph.mjs`.
These are equivalent graph algorithms, not claims to be NetworkX, Louvain or
Leiden outputs. Known-answer tests cover paths, disconnected components,
normalized centrality, PageRank, parallel-edge collapse and modularity.

All four variants use the same full population, including isolates. A separate
connected-population analysis also excludes people with no verified tie.

- **Projection:** simple, undirected and unweighted. Direction and multiple tie
  records remain in the source data. Each distinct endpoint pair counts once.
- **Components:** breadth-first traversal, with component members and sizes.
- **Degree and distribution:** number of distinct neighbors, including zero.
- **Betweenness:** exact unweighted Brandes algorithm, endpoints excluded,
  globally normalized over the full node population. The implementation sums
  ordered traversals and divides by `(n − 1)(n − 2)`.
- **PageRank:** damping 0.85, uniform teleportation and dangling redistribution,
  L1 convergence tolerance 1e-12, maximum 500 iterations, undirected projection.
- **Communities:** deterministic greedy positive modularity-gain merging,
  resolution 1. Output includes members, method and modularity. It is not Louvain.
- **Density:** `2m / (n(n − 1))`, where m counts unique pairs.
- **Average distance and diameter:** all ordered distinct pairs within the
  largest connected component only. Singleton distances are undefined/null.
- **Types:** relationship-record counts, distinct from the pair count.
- **Shortest paths:** breadth-first search on the selected verified projection.
  Each consecutive path pair has inspectable evidence. Paths respect evidence,
  relationship, community, affiliation and time filters. Curated modes are
  ignored during path search and neighborhood exploration.

Algorithm definitions:
[NetworkX's Brandes documentation](https://networkx.org/documentation/stable/reference/algorithms/generated/networkx.algorithms.centrality.betweenness_centrality.html),
[greedy modularity documentation](https://networkx.org/documentation/stable/reference/algorithms/generated/networkx.algorithms.community.modularity_max.greedy_modularity_communities.html).

## Dates and temporal interpretation

Supported dates retain precision: YYYY, YYYY-MM or YYYY-MM-DD. Unknowns remain
null. A year is never silently converted into a precise January 1 start date.
Sources have separate publication and review dates. Paper-observation dates in
the extension fragment identify publication of a collaboration, not first
meeting or actual start/end of an interpersonal association.

The year filter and exported timeline are **cumulative documented observations**,
not active-at-date networks. Historical ties persist. Records with unknown starts
can be explicitly included in the explorer but are excluded from the exported
dated timeline. Consolidated ties use their earliest known observation and retain
all assertion-specific dates. This cannot date undocumented earlier connections.

## Visualization and accessibility

A seeded, unbounded offline Fruchterman–Reingold layout is saved as `layout.json`. Its attraction forces and line prominence use illustrative relationship-type weights: explicit family, romantic, friendship and roommate ties are emphasized; coauthorship and co-investment are deemphasized. Other types receive intermediate weights. These are editorial display choices, not evidence or measurements of personal closeness; for pairs with multiple types the layout uses the highest display weight. The network calculations above remain unweighted.
Soft centering and node separation replace hard rectangular position limits.
Disconnected components are packed as non-overlapping disks in a compact
arrangement. Curated modes have their own cached layouts
to keep small investigations readable. Browsing does not rerun a moving simulation.
SVG renders the selected subset, with keyboard-selectable nodes and edge hit
targets, parallel curves, zoom and background panning. This custom SVG approach
is adequate for the curated hundreds-of-node dataset; it is not a WebGL engine
benchmarked for tens of thousands of nodes. A dataset at that scale should migrate
to Sigma/Graphology or Cytoscape and a spatial index.

Default exploration begins with the OpenAI diaspora and its immediate bridges,
with separate PayPal, Anthropic, investor, academic, Chinese, European, informal,
degree-ranked and full-network modes. Selected node sizes always refer to the
**full** sample, not a ranking silently recomputed after filtering. Source
communities overlap; a deterministic priority chooses one displayed color.
The inspector lists all communities. Detected-group colors repeat after nine.

An accessible list duplicates every visible person/relationship, so information
does not depend on graph geometry or color. The visualizer's initial graph,
degree distribution and source links are prerendered to HTML. Interactive filters
require JavaScript. The layout uses responsive CSS and
supports reduced-motion preferences. Browser-based visual/click verification was
blocked by the session's browser URL policy and must still be performed before
publication; build, source validation and known-answer tests are separate checks.

## Reproducibility and limits

From the repository root:

```sh
npm ci
npm run analyze:ai-inner-circle
npm run test:ai-inner-circle
npm run build
```

The data pipeline needs Node.js, not a Python scientific stack. Data, analysis,
layout and a SHA-256 manifest are regenerated from frozen reviewed fragments.
The ordinary production build prerenders the visualizer at
`/projects/ai-inner-circle`. The blog entry links directly there and the former
blog URL redirects to it. The degree distribution describes the full sample,
including isolated profiles, and stays fixed when graph filters change.
The offline file includes the same graph, chart and evidence downloads.
Reproducing the computations does not
automatically reverify sources or refresh evidence. The optional source audit
script reports HTTP availability and never upgrades evidence confidence.

Sampling is purposive; geography, language, publicity and source access are
uneven. Academic ties are selected rather than complete. Confidence thresholds
do not correct missingness. Network centrality is not ownership, capital,
authority, political influence or causal control. No matched comparison-industry
network was constructed. Do not claim AI is unusually interconnected or that a
small circle controls the industry on the basis of this edition.

Artificial Analysis research (checked 2026-10-29): the company's named backers are recorded as person–institution investment affiliations; it does not disclose amounts, dates or vehicles on its about page. These records do not assert board membership or create direct person-to-person investment edges. No board roster was confirmed. Personal and professional ties require separate evidence and are incomplete.




