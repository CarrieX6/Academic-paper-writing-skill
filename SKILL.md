---
name: academic-paper-writing
description: Plan, draft, structurally review, or rewrite peer-reviewed research manuscripts with venue-aware section logic, argument-led paragraphs, official-format compliance, and traceable claim-evidence control. Use for conference or journal papers, including machine-learning and medical-AI manuscripts, when working on outlines, sections, narrative coherence, literature positioning, citations, or reviewer-style audits. Do not use for citation retrieval alone, grammar-only proofreading, grants, theses, or general non-research prose.
---

# Academic Paper Writing

Build a defensible scientific argument before polishing its prose. Adapt the manuscript to its paper type, audience, evidence maturity, and current target-venue rules. Never turn a useful example structure into a universal paragraph count.

## Interpret rule strength

Use these levels throughout this skill:

- **MUST**: validity, integrity, or submission-compliance requirement. Do not relax it silently.
- **SHOULD**: strong default supported by effective scholarly writing. Adapt it when the venue, paper type, or argument gives a concrete reason.
- **MAY**: optional pattern or example, never a hidden acceptance criterion.

Paragraph counts, sentence counts, section names, and Introduction length are never universal MUST rules. An Introduction's logical moves may be combined or split according to reader knowledge, argument complexity, and page budget.

Resolve conflicts in this order: research integrity and current official venue MUST rules; explicit project constraints from the user; then this skill's SHOULD/MAY defaults. Follow a user's fixed paragraph count or style when it does not force noncompliance, unsupported claims, empty paragraphs, or destructive redundancy. If only one part conflicts, reject or revise that part and continue the safe remainder.

## Establish the writing contract

Infer the following from the request, manuscript, repository, and author instructions. Ask only when an unresolved choice would materially change the result.

1. Target venue and submission stage: conference, journal, venue-neutral; initial submission, revision, camera-ready, or resubmission.
2. Paper type: method, theory, empirical study, benchmark/dataset, systems, clinical/translational study, or review.
3. Audience: general ML, specialist technical, clinical/biomedical, or mixed.
4. Task: outline, draft, review, rewrite, shorten, expand, or venue conversion.
5. Section scope and page/word budget.
6. Evidence maturity: exploratory, mixed, or frozen; then track each claim separately.
7. Manuscript language and house style: required English variety when applicable, dominant manuscript variety, or author preference.
8. Source of truth: manuscript files, experiment artifacts, theorem files, verified bibliography, and decision/audit documents.
9. Project-specific style constraints: for example, adaptive paragraph openings or a strict first-sentence controlling-claim requirement.
10. Collaboration language for explanations and audits; keep it separate from the manuscript's language.

If the target venue is known and formatting or submission prose is in scope, inspect the venue's **current official** author guide and template before finalizing. Do not rely on remembered page limits or old templates. Read [template-exemplar-compliance.md](references/template-exemplar-compliance.md).

Before AI-assisted drafting or reference work, check the target venue's current policy on generative-AI use, prohibited tasks, authorship, and disclosure. If the requested assistance is prohibited for that venue or article type, stop the prohibited work and explain the boundary; do not treat disclosure as permission.

## Route to the necessary references

Read only the references needed for the task, but read each selected file completely.

- For conference/journal differences, audience, or English variety, read [venue-modes-and-language.md](references/venue-modes-and-language.md).
- For paper-type differences, read [paper-types.md](references/paper-types.md).
- For whole-paper logic, Introduction structure, paragraph coherence, figures, or captions, read [argument-architecture.md](references/argument-architecture.md).
- For any section draft or audit, read [section-guides.md](references/section-guides.md).
- For Introduction, Related Work, novelty, citations, or bibliography work, read [literature-and-citation-integrity.md](references/literature-and-citation-integrity.md).
- For medical or clinical AI, read [medical-ai.md](references/medical-ai.md).
- For outlining or first drafting, read [workflow-outline-draft.md](references/workflow-outline-draft.md).
- For structural review, rewriting, shortening, or conversion, read [workflow-review-rewrite.md](references/workflow-review-rewrite.md).

## Apply non-negotiable integrity constraints

- Do not invent references, quotations, datasets, equations, proofs, experiments, numerical results, or venue rules.
- Do not upgrade a hypothesis, plan, running result, or bounded observation into a settled conclusion.
- Make every consequential claim traceable to a verified internal artifact or a source that actually supports it.
- Verify novelty claims with a current, structured literature search. Avoid “first,” “only,” and “unprecedented” unless the search scope makes the wording defensible.
- Distinguish observation, interpretation, mechanism, implication, and clinical claim; do not let prose silently cross these evidence levels.
- Preserve material limitations and negative evidence. Fluent prose must not conceal an open dependency or contradicted claim.
- Follow current official venue instructions. Never modify margins, fonts, spacing, or style files to gain space.
- Follow current venue rules for AI-assisted writing and reference handling, including any required use statement. Do not perform a prohibited drafting or citation task.
- Keep one English variety and house style throughout unless quoting titles or source text. Follow an explicit venue rule first; otherwise preserve the manuscript's dominant variety or the author's stated preference.
- Use published papers as an advisory style corpus, not as authority over the official guide and not as text to imitate.

## Build two internal maps before substantial prose

Create these maps internally or show them when useful.

### Claim-evidence ledger

Track:

`Claim ID | exact claim | claim type | evidence status | source/artifact | locator | required qualifier | allowed sections`

Use evidence states such as `established_external`, `verified_internal`, `bounded_internal`, `hypothesis`, `planned`, `unverified`, and `contradicted_or_retired`. A manuscript can contain claims at different states.

### Argument and paragraph map

Track:

`Section/paragraph | controlling function or claim | support | relation to previous/next | supported paper claim | consequence if removed`

Every paragraph MUST perform one necessary controlling function. Its first sentence SHOULD make that function visible, but formal definitions, theorem statements, short transitions, and deliberately delayed-claim paragraphs may use another clear controlling form. Do not mechanically rewrite every first sentence into the same template.

If the user explicitly requires first-sentence topic claims for a project, treat that as a project-level MUST for ordinary argumentative paragraphs. Preserve narrowly justified exceptions for definitions, theorems, algorithms, structured abstracts, captions, and essential transitions, and make those exceptions visible rather than accidental.

## Revise in three passes

1. **Macro:** align research question, gap, contribution, evidence, and scope.
2. **Meso:** assign each section and paragraph a unique function; repair order, missing links, duplication, and transitions.
3. **Micro:** improve topic sentences, syntax, terminology, notation, English variety, rhythm, and concision.

Do not begin with sentence-level polishing when the macro argument is unstable.

## Use an adaptive argument chain

A common research-paper chain is:

`context -> established paradigm -> precise limitation -> research question -> difficulty -> solution -> evidence -> implication`

Treat these as rhetorical moves, not required paragraphs. Combine adjacent moves when one paragraph can carry them without overload; split a move when it needs distinct evidence or a new abstraction. Omit a move only when the intended reader can safely recover it and the omission does not break the argument.

## Match the requested workflow

- **Outline:** produce the thesis, reader/venue assumptions, move-level logic, section responsibilities, claim-evidence ledger, unresolved dependencies, and prohibited claims.
- **Draft:** write and test controlling sentences first, then add definitions, evidence, citations, formulas, results, implications, and transitions.
- **Review:** lead with the overall structural verdict; identify critical, major, and minor issues with exact evidence and actionable repairs.
- **Rewrite:** preserve verified facts, symbols, citations, and scope; restructure whole paragraphs before line editing; list unresolved evidence gaps separately.
- **Venue conversion:** change argument density, section division, validation depth, reporting, and compliance—not just page length.

When the user requests analysis or review only, do not edit files. When the user requests implementation, edit the source of truth and validate the compiled or rendered result when feasible.

## Run the final audit

Before declaring completion, confirm:

1. The paper's one-sentence thesis, estimand or central question, method, evidence, and conclusion agree.
2. Each paragraph is necessary, has one controlling function, and has a meaningful relation to its neighbors.
3. Section boundaries are respected; Introduction, Related Work, Results, and Discussion are not duplicates.
4. Every citation is real, retrievable, correctly attributed, and supports the nearby claim at the stated strength.
5. Literature coverage includes foundational, closest, recent, and challenging or countervailing work until search saturation—not an arbitrary citation count.
6. Title, Abstract, Contributions, figures, tables, and captions contain no claim stronger than the body evidence.
7. Terminology, notation, acronym expansion, spelling variety, and capitalization are consistent.
8. The current official template and author instructions are followed when a target venue is fixed.
9. Anonymity, ethics, reporting, data/code, disclosure, and supplemental requirements are handled for the submission stage.
10. Open experiments or proofs remain visibly open and are not disguised as completed contributions.
