---
name: academic-paper-writing
description: Plan, draft, structurally review, humanize, or rewrite Chinese- or English-language peer-reviewed research papers and Chinese doctoral dissertations with document-aware argument structure, author-voice preservation, persuasive non-defensive narrative, official-format compliance, and traceable claim-evidence control. Use for conference and journal manuscripts across AI fields, including medical AI; for removing formulaic AI-sounding academic prose without altering evidence; and for monograph, publication-based, or hybrid Chinese doctoral dissertations when permitted by the degree institution. Do not use to evade AI detectors or disclosure rules, or for citation retrieval alone, grammar-only proofreading, grants, non-doctoral theses, English-language dissertations, or general non-research prose.
---

# Academic Paper Writing

Build the strongest scholarly argument the evidence can honestly sustain, then express it in the author's own academic voice. First identify the document mode, language, research type, audience, evidence maturity, governing authority, and submission or degree stage. Do not treat a doctoral dissertation as a long journal article, Chinese academic prose as translated English, or a paper as a project diary or self-audit report.

## Interpret rule strength

Use these levels throughout this skill:

- **MUST**: validity, integrity, or official-compliance requirement. Do not relax it silently.
- **SHOULD**: strong default supported by effective scholarly writing. Adapt it when the document, language, field, or governing authority gives a concrete reason.
- **MAY**: optional pattern or example, never a hidden acceptance criterion.

Paragraph counts, sentence counts, section names, chapter counts, and Introduction length are never universal MUST rules. Rhetorical moves may be combined or split according to reader knowledge, argument complexity, document mode, and space budget.

Resolve conflicts in this order: research integrity and current official MUST rules; the institution's or venue's binding requirements; explicit project constraints from the user; then this skill's SHOULD/MAY defaults. A supervisor, committee, editor, or exemplar may guide choices but cannot authorize fabricated evidence, unsupported claims, plagiarism, or violation of a binding rule.

## Establish the writing contract

Infer the following from the request, manuscript, repository, and official instructions. Ask only when an unresolved choice would materially change the result.

1. **Document mode and stage**:
   - conference or journal paper: venue-neutral, initial submission, revision/rebuttal, camera-ready, resubmission, or production proof;
   - Chinese doctoral dissertation: planning, drafting, internal review, pre-defense, external examination, defense revision, or final deposit, using the institution's actual stage names.
2. **Research type**: method/algorithm, theory, empirical/observational, benchmark/dataset, systems, clinical/translational, human-subject/qualitative/mixed-methods, review, position/perspective, replication, or negative-result study.
3. **Audience**: general AI, technical specialist, clinical/biomedical, interdisciplinary, editor/reviewer, or doctoral examiner/committee.
4. **Task**: outline, draft, review, rewrite, shorten, expand, integrate chapters, respond to review, or convert venue/document form.
5. **Scope and budget**: section, chapter, whole document, page/word limit, and permitted supplement or appendix.
6. **Evidence maturity**: exploratory, mixed, or frozen; track each claim separately.
7. **Language and house style**: Chinese or English manuscript, required English variety when applicable, bilingual elements, and terminology policy.
8. **Governing authority**: current venue/publisher instructions or, for a dissertation, the university, graduate school, degree program, faculty/department, library/deposit rules, and authorized template.
9. **Source of truth**: manuscript files, experiment artifacts, theorem/proof files, verified bibliography, protocols, decision/audit records, and dissertation contribution records.
10. **Project constraints**: required paragraph openings, protected published chapters, anonymization, author permissions, or advisor/committee requirements.
11. **Collaboration language**: keep explanations and audits distinct from the manuscript language unless the user requests otherwise.
12. **Author voice**: approved writing samples, preferred first-person use, hedge strength, sentence rhythm, terminology, punctuation, and disciplinary register. Treat samples as a style corpus, never an evidence source.
13. **Narrative freedom**: whether only surface humanization is allowed or whether sections, paragraphs, contribution order, and the paper-level storyline may be reconstructed.

For a conference or journal task with a known target, inspect the current official author guide, template, submission policy, and generative-AI policy before finalizing target-dependent prose or formatting. For a Chinese doctoral dissertation, inspect the current official degree regulations, authorized template, examination/deposit rules, and institutional AI-use policy before claiming compliance. If the governing target is unknown or inaccessible, record it as unresolved and continue only with work that does not depend on that rule. Read [template-exemplar-compliance.md](references/template-exemplar-compliance.md).

## Route to the necessary references

Read only the references needed for the task, but read every selected file completely. Combine routes when a task spans modes.

- For conference/journal differences, audience, submission stages, or English variety, read [venue-modes-and-language.md](references/venue-modes-and-language.md).
- For Chinese manuscript prose, bilingual elements, Chinese typography, terminology, or Chinese references, read [chinese-academic-writing.md](references/chinese-academic-writing.md).
- For any Chinese doctoral dissertation task, read [chinese-doctoral-dissertation.md](references/chinese-doctoral-dissertation.md), [chinese-academic-writing.md](references/chinese-academic-writing.md), and [template-exemplar-compliance.md](references/template-exemplar-compliance.md).
- For research-type differences, read [paper-types.md](references/paper-types.md).
- For whole-paper logic, Introduction structure, paragraph coherence, figures, or captions, read [argument-architecture.md](references/argument-architecture.md).
- For a paper section draft or audit, read [section-guides.md](references/section-guides.md); use the dissertation guide rather than treating these section names as a mandatory thesis structure.
- For Introduction, Related Work, novelty, citations, or bibliography work, read [literature-and-citation-integrity.md](references/literature-and-citation-integrity.md).
- For medical or biomedical AI, read [medical-ai.md](references/medical-ai.md).
- For medical-imaging work whose scientific object is an information mismatch between training and deployment, controlled privileged supervision, predicted auxiliary inputs, leakage-safe score generation, or reliability-aware evidence acquisition, also read [medical-imaging-methods.md](references/medical-imaging-methods.md). Do not route here from an isolated keyword such as “distillation” or “cross-fitting.”
- If `references/local-research-profile.md` exists and the current artifact belongs to that configured portfolio, read it completely after the public medical-imaging adapter. Treat it as private routing context, not as evidence, and never expose its internal identifiers or unpublished status details in public output.
- For domain-specific evidence risks in other AI research, read [ai-domain-adapters.md](references/ai-domain-adapters.md) and select only the relevant domain subsection.
- For outlining or first drafting, read [workflow-outline-draft.md](references/workflow-outline-draft.md).
- For structural review, rewriting, shortening, or conversion, read [workflow-review-rewrite.md](references/workflow-review-rewrite.md).
- For humanization, author-voice matching, abstract/Introduction/Conclusion sharpening, rebuttal language, removing formulaic AI prose, or avoiding defensive writing, read [voice-and-narrative.md](references/voice-and-narrative.md). Combine it with the review route whenever restructuring is allowed.

## Apply non-negotiable integrity constraints

- Do not invent references, quotations, datasets, equations, proofs, experiments, numerical results, institutional rules, or venue rules.
- Do not upgrade a hypothesis, plan, running result, bounded observation, or chapter-level finding into a settled paper- or dissertation-level conclusion.
- Make every consequential claim traceable to a verified internal artifact or a source that supports it at the stated strength.
- Verify novelty and originality claims with a current, structured literature search. Avoid “first,” “only,” “unprecedented,” “填补空白,” and equivalent priority language unless the search scope makes it defensible.
- Distinguish observation, interpretation, mechanism, implication, clinical claim, and cumulative dissertation contribution.
- Preserve prespecified outcomes, material limitations, negative or contrary evidence, and disagreements among included studies. Fluent or persuasive synthesis must not erase them.
- Never choose endpoints, metrics, baselines, subgroups, thresholds, or comparison framing because the observed result is more favorable. Label outcome-informed analyses as exploratory or post hoc and retain the original analysis record.
- Follow the current official venue or institution instructions. Never alter official style files, margins, fonts, spacing, or required structure to evade limits.
- Follow current venue, institutional, and collaborator rules for AI-assisted writing, reference handling, confidentiality, authorship, and disclosure. Disclosure is not permission for a prohibited task.
- For publication-based dissertation material, verify text-reuse, copyright, version, co-author contribution, and attribution rules before rewriting or reproducing published content.
- Maintain one language and house style within each intended component; keep bilingual titles, abstracts, keywords, symbols, and core terms semantically aligned.
- Use accepted papers and approved dissertations only as advisory style corpora, never as authority over official rules or as text to imitate.
- Do not optimize text to bypass AI detectors or conceal prohibited assistance. Improve authorship, specificity, and argumentative quality, and leave required AI-use disclosure to the applicable policy and author confirmation.

## Build a persuasive, non-defensive narrative

- Identify the single strongest evidence-supported contribution and make it the organizing center. Supporting analyses should explain, validate, delimit, or operationalize that contribution instead of appearing as an equal-weight experiment log.
- State what the study establishes before cataloguing what it does not. Remove generic self-disqualification, apology, and boilerplate limitation language; keep every boundary that changes validity, interpretation, reproducibility, fairness, or clinical meaning.
- Report an unfavorable or null result directly when it is prespecified, contradicts the headline, affects safety or fairness, or changes the claim. Frame a well-controlled negative result as evidence about a mechanism or applicability boundary when that interpretation is supported—not as a failed attempt and not as a hidden result.
- Narrative reconstruction may change order, emphasis, section boundaries, and the headline only within the verified record. It may not relabel a post hoc discovery as prespecified, substitute a favorable metric for the primary one, or suppress a required comparison.
- Prefer precise scope over habitual hedging. Use confident declarative language for established facts, calibrated language for bounded evidence, and explicit hypothesis language for mechanisms not identified by the design.

## Build the internal maps before substantial prose

### Claim-evidence ledger

Track:

`Claim ID | exact claim | claim type | evidence status | source/artifact | locator | required qualifier | allowed locations`

Use evidence states such as `established_external`, `verified_internal`, `bounded_internal`, `hypothesis`, `planned`, `unverified`, and `contradicted_or_retired`.

### Argument and paragraph map

Track:

`Document unit | controlling function or claim | support | relation to previous/next | supported central claim | consequence if removed`

Every argumentative paragraph MUST perform one necessary controlling function. Its first sentence SHOULD make that function visible, but formal definitions, theorem statements, short transitions, Chinese setup–turn openings, and deliberately delayed-claim paragraphs may use another clear controlling form. Do not impose a translated English topic-sentence template on Chinese prose.

For a doctoral dissertation, additionally build the dissertation-level map defined in the doctoral guide before editing individual chapters.

## Revise at three nested levels

1. **Macro:** align the central question, contribution, evidence, scope, and conclusion across the whole paper or dissertation; for a dissertation, also align chapter subquestions and cumulative contribution.
2. **Meso:** assign each section, chapter, and paragraph a unique function; repair order, missing links, justified repetition, duplication, and transitions.
3. **Micro:** improve syntax, terminology, notation, language variety, bilingual consistency, rhythm, and concision without changing evidence.

Do not begin with sentence-level polishing when the scientific or document-level argument is unstable.

## Use adaptive argument architecture

A common research-paper chain is:

`context -> established knowledge/practice -> precise limitation -> research question -> difficulty -> response -> evidence -> bounded significance`

Treat these as rhetorical moves, not required paragraphs. A doctoral dissertation uses a hierarchy rather than one enlarged chain: an overarching question and cumulative contribution are supported by chapter-level questions, evidence, and synthesis. Qualitative, exploratory, replication, negative-result, and position work may require a different chain; route by research type rather than forcing a method-paper narrative.

## Match the requested workflow

- **Outline:** produce the central claim/question, document and reader assumptions, move- or chapter-level logic, claim-evidence ledger, unresolved dependencies, prohibited claims, and pending compliance work.
- **Draft:** write and test controlling functions before adding definitions, evidence, citations, formulas, results, implications, and transitions.
- **Review:** lead with the overall structural verdict; identify critical, major, and minor issues with exact evidence and actionable repairs.
- **Rewrite:** preserve verified facts, symbols, citations, contribution boundaries, and protected text; reconstruct whole units before line editing.
- **Humanize:** first lock claims and protected elements; recover the author's voice and narrative hierarchy; then remove formulaic prose, empty transitions, repetitive summaries, and mechanical symmetry without banning words or punctuation by rule.
- **Venue conversion:** change argument density, validation depth, section division, reporting, and overlap disclosures, not just length and template.
- **Dissertation integration:** preserve each study's evidence boundary while constructing an explicit cross-chapter synthesis; never concatenate paper abstracts and call the result a cumulative contribution.

When the user requests analysis or review only, do not edit files. When the user requests implementation, edit the source of truth and validate the compiled or rendered result when feasible.

## Run the final audit

Apply only the checks relevant to the requested scope, document stage, and claims. Complete routine checks silently; report only a failure, unresolved dependency, or boundary that materially affects the current deliverable. A short passage edit does not require a full submission-readiness report.

Before declaring completion, confirm as applicable:

1. The document mode, language, research type, audience, and stage were identified correctly.
2. The central question or claim, method/inquiry, evidence, contribution, and conclusion agree at the appropriate document level.
3. Each paragraph, section, and chapter has a necessary function and a meaningful relation to its neighbors; any repetition is justified by reader or examination needs.
4. Every citation is real, retrievable, correctly attributed, and supports the nearby claim at the stated strength.
5. Literature coverage includes foundational, closest, recent, domain-specific, and challenging work until claim-relative saturation.
6. Titles, abstracts, contributions, figures, tables, captions, chapter summaries, and conclusions contain no claim stronger than the body evidence.
7. Terminology, notation, acronym expansion, Chinese–English correspondence, spelling variety, punctuation, and capitalization are consistent where applicable.
8. The current official venue or degree-institution requirements, template, anonymity, examination, and deposit rules are satisfied or explicitly unresolved.
9. Ethics, consent, privacy, data/code, funding, conflicts, author/contributor roles, reused publications, copyright, AI disclosure, and reporting requirements are handled for the document and stage.
10. Open experiments, proofs, permissions, or chapter dependencies remain visible rather than being disguised as completed contributions.
11. For a doctoral dissertation, the overarching question, chapter subquestions, individual contributions, and final synthesis form a defensible cumulative contribution without overstating the candidate's role.
12. The final artifact compiles or renders correctly, and its references, cross-references, figures, metadata, anonymization, and required front/back matter have been inspected when feasible.
13. The strongest defensible contribution is visible early and remains the document's organizing center; the text does not read like an experiment diary, generic template, or self-rejection letter.
14. Prespecified outcomes, unfavorable findings, uncertainty, fairness/safety evidence, and material limitations remain complete and correctly labeled despite narrative sharpening.
15. The prose matches the author's documented voice without copying source phrasing, mechanically banning stylistic features, or changing numbers, citation keys, equations, LaTeX structure, terminology, or claim strength.
