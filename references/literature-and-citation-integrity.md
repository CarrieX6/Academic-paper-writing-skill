# Literature and Citation Integrity

## Define the purpose before searching

Literature work can serve different purposes:

- establish a background fact or accepted paradigm;
- identify the closest technical or scientific precedent;
- test a novelty claim;
- find contradictory, negative, or boundary evidence;
- select baselines, datasets, metrics, or reporting standards;
- synthesize a field for Related Work.

Translate each purpose into explicit search facets. Do not measure adequacy by a fixed number of references.

## Search along multiple facets

For a research manuscript, cover the facets relevant to its claims:

1. exact problem and deployment/scientific setting;
2. closest method family and alternative formulations;
3. domain-specific applications;
4. theoretical or statistical foundations;
5. foundational papers and terminology origins;
6. recent work, including current proceedings or online-first articles;
7. counterexamples, failure analyses, negative results, and competing explanations;
8. standards, datasets, or reporting guidelines.

Use backward citation tracing from close papers and forward citation tracing when available. Search synonyms, older terminology, task names, and neighboring fields. For a formal systematic or scoping review, follow the applicable protocol and reporting standard; this ordinary manuscript workflow is not a substitute.

## Prefer authoritative, primary records

- Use model memory, search snippets, blogs, and another paper's Related Work only to discover candidates. They are not final evidence and must not be used to fabricate metadata.
- Use the original research paper for a method, theorem, dataset, or empirical result.
- Use the venue proceedings, publisher page, DOI registry, standard body, or official project page to verify bibliographic facts.
- Use reviews and surveys to navigate and synthesize, then inspect primary sources for consequential claims.
- Prefer the peer-reviewed published version when it materially matches the cited claim. If only a preprint exists or the preprint contains distinct material, identify it honestly.
- Check corrections, retractions, expressions of concern, and major version changes when relevant.
- Do not present a workshop paper, poster, preprint, and archival publication as equivalent evidence without qualification.

## Verify every citation before using it

For each consequential citation, record:

`claim | source identity | stable locator/DOI | publication status | exact supporting location | support strength | limitation`

Then confirm:

1. The paper exists and its authors, title, year, and venue are correct.
2. The cited version contains the claimed content.
3. The nearby sentence does not generalize beyond the source population, task, assumptions, or result.
4. The source supports the claim directly rather than merely citing another paper for it.
5. A citation to an abstract is not used for a detail only available in inaccessible full text.
6. Several citations after one sentence each support the sentence; do not create decorative citation clusters.

Cross-check high-risk or conflicting metadata against an independent trusted index such as Crossref, PubMed, DBLP, or arXiv as appropriate. Metadata services verify identity; they do not replace reading the paper for scientific support.

For Chinese-language sources, verify the original journal, publisher, standard body, institution, or official repository and preserve the authoritative Chinese metadata; read [chinese-academic-writing.md](chinese-academic-writing.md). Do not translate a title or romanise an author name and present the generated form as official metadata.

If full verification is impossible, narrow the claim, mark the source unverified internally, or omit it. Never invent a plausible BibTeX entry.

## Establish literature coverage by saturation

Related Work is sufficiently researched when all material claims and novelty boundaries have appropriate sources and additional structured searches stop revealing new close families or claim-changing evidence.

Use these practical exit conditions:

- each core claim has at least one appropriate primary source or is explicitly the paper's own hypothesis/result;
- the closest works are compared on the dimensions that define the paper's claimed difference;
- foundational, recent, domain-specific, and countervailing work are represented where relevant;
- backward and forward tracing of the closest works produces no unaddressed category that changes the positioning;
- recent targeted searches produce mainly already-covered works or refinements rather than a new nearest precedent;
- search queries, sources, dates, inclusion logic, and unresolved access gaps are recorded internally.

Saturation is claim-relative. A broad claim requires broader coverage than a narrowly bounded one. Never assert exhaustiveness without a method capable of supporting it.

For a doctoral dissertation, assess saturation both for the overarching research program and for specialized chapter claims. A long standalone literature chapter does not excuse missing nearest work inside a later chapter, but repeated citations should serve a distinct local purpose rather than reproduce the same review.

## Write Related Work as synthesis

Organize paragraphs around a research question, assumption, information regime, method family, or evaluation difference. A useful paragraph typically states:

1. what a body of work establishes;
2. the shared assumption or boundary relevant here;
3. how the present paper differs without dismissing prior work.

Avoid paper-by-paper chronology unless historical development itself is the argument. Give the most space to the nearest work, not to papers that are easiest to summarize.

Use positive, bounded positioning such as “prior work optimizes transfer from a preselected source; we study selection among source configurations for a fixed student.” Avoid unsupported priority language.

## Keep the bibliography auditable

- Derive BibTeX or equivalent metadata from a trusted record when possible.
- Preserve DOI, URL or stable identifier, publication status, and canonical venue metadata.
- Deduplicate preprint and published versions unless both are substantively needed.
- Ensure every bibliography entry cited in the manuscript is intentional and every citation key resolves.
- Compile and inspect undefined citations, duplicate keys, capitalization loss, author truncation, and venue-name inconsistencies.
- Do not cite a source that was never read sufficiently to verify its use.
- Do not retain references solely to inflate breadth or imitate the citation density of accepted papers.
- For included or adapted publications in a dissertation, distinguish citation of the scientific work from disclosure of text reuse, publication status, version, candidate contribution, and copyright permission.

## Red-team novelty and attribution

Before freezing Introduction, Related Work, and Contributions, ask:

- Is there an earlier paper with the same target but different vocabulary?
- Is the claimed novelty actually a combination of known components?
- Does the closest work already cover the supposedly new setting in an appendix or experiment?
- Are we claiming a mechanism when we observed only an association?
- Have negative or contradictory studies been omitted?
- Does every “unlike prior work” sentence compare matched dimensions?
- Are borrowed definitions, problem formulations, algorithms, data, or figures attributed?

If the answer threatens the contribution, revise the scientific claim rather than obscuring the precedent.
