---
name: academic-paper-writing
description: Plan, draft, structurally review, or rewrite Chinese- or English-language peer-reviewed research papers and Chinese doctoral dissertations with document-aware argument structure, official-format compliance, and traceable claim-evidence control. Use for conference and journal manuscripts across AI fields, including medical AI, and for monograph, publication-based, or hybrid Chinese doctoral dissertations when permitted by the degree institution. Do not use for citation retrieval alone, grammar-only proofreading, grants, non-doctoral theses, English-language dissertations, or general non-research prose.
---

# Academic Paper Writing

Build a defensible scholarly argument before polishing prose. First identify the document mode, language, research type, audience, evidence maturity, governing authority, and submission or degree stage. Do not treat a doctoral dissertation as a long journal article or Chinese academic prose as translated English.

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
- For domain-specific evidence risks in other AI research, read [ai-domain-adapters.md](references/ai-domain-adapters.md) and select only the relevant domain subsection.
- For outlining or first drafting, read [workflow-outline-draft.md](references/workflow-outline-draft.md).
- For structural review, rewriting, shortening, or conversion, read [workflow-review-rewrite.md](references/workflow-review-rewrite.md).

## Apply non-negotiable integrity constraints

- Do not invent references, quotations, datasets, equations, proofs, experiments, numerical results, institutional rules, or venue rules.
- Do not upgrade a hypothesis, plan, running result, bounded observation, or chapter-level finding into a settled paper- or dissertation-level conclusion.
- Make every consequential claim traceable to a verified internal artifact or a source that supports it at the stated strength.
- Verify novelty and originality claims with a current, structured literature search. Avoid “first,” “only,” “unprecedented,” “填补空白,” and equivalent priority language unless the search scope makes it defensible.
- Distinguish observation, interpretation, mechanism, implication, clinical claim, and cumulative dissertation contribution.
- Preserve material limitations, negative evidence, and disagreements among included studies. Fluent synthesis must not erase them.
- Follow the current official venue or institution instructions. Never alter official style files, margins, fonts, spacing, or required structure to evade limits.
- Follow current venue, institutional, and collaborator rules for AI-assisted writing, reference handling, confidentiality, authorship, and disclosure. Disclosure is not permission for a prohibited task.
- For publication-based dissertation material, verify text-reuse, copyright, version, co-author contribution, and attribution rules before rewriting or reproducing published content.
- Maintain one language and house style within each intended component; keep bilingual titles, abstracts, keywords, symbols, and core terms semantically aligned.
- Use accepted papers and approved dissertations only as advisory style corpora, never as authority over official rules or as text to imitate.

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
- **Venue conversion:** change argument density, validation depth, section division, reporting, and overlap disclosures, not just length and template.
- **Dissertation integration:** preserve each study's evidence boundary while constructing an explicit cross-chapter synthesis; never concatenate paper abstracts and call the result a cumulative contribution.

When the user requests analysis or review only, do not edit files. When the user requests implementation, edit the source of truth and validate the compiled or rendered result when feasible.

## Run the final audit

Before declaring completion, confirm:

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
