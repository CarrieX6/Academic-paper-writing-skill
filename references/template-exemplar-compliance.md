# Template and Exemplar Compliance

## Treat official instructions as the authority

When a target venue and submission stage are fixed, perform a current compliance check before final drafting or typesetting.

1. Locate the venue's current official author instructions, call for papers, submission checklist, and official template or submission portal guidance.
2. Record the venue, track or article type, submission stage, version/year, and access date.
3. Confirm page or word limits, reference treatment, anonymity, supplement policy, abstract limits, required sections/declarations, file formats, and policy constraints.
4. Obtain the template from the official venue, publisher, or linked repository—not an unrelated mirror.
5. Verify whether the repository already uses that template and whether it matches the current cycle and submission stage.
6. Compile or render the manuscript and inspect warnings, overflow, font embedding, figure legibility, bibliography, and anonymization when feasible.

Record template status as `verified_current`, `unverified_current`, `provisional_previous_cycle`, `mismatched`, `free_format`, or `not_applicable`. If the next cycle's official instructions are not yet available, a previous-cycle template is provisional and must not be described as compliant with the future cycle.

If official sources cannot be reached, record `unverified_current`, preserve the exact URL and failed check, and continue only with content work that does not depend on the unresolved rule. Do not claim compliance, perform final layout optimization, or substitute memory, a mirror, or an accepted paper as authority. Re-run the official check before submission-ready handoff.

If the current document class or style belongs to another venue, do not present the manuscript as submission-ready. Resolve or obtain author approval for migration before a formatting/finalization task; for a content-only review, continue only while explicitly flagging the mismatch.

Do not rely on memory for changing rules. Do not treat an old accepted paper as a substitute for current instructions.

## Check AI-assistance policy before drafting

Official policies may require disclosure, limit reference generation, or prohibit AI drafting for particular article types. Before substantive AI-assisted writing:

1. inspect the current venue and article-type policy;
2. classify the requested action as permitted, permitted with disclosure, or prohibited;
3. record any required AI-use statement and submission-stage placement;
4. stop any prohibited drafting, rewriting, image, review, or reference operation rather than assuming disclosure cures it;
5. remind the authors that they remain responsible for accuracy, attribution, confidentiality, and policy compliance.

Do not upload confidential manuscripts to an external service when venue, institutional, consent, or collaboration rules prohibit it.

## Use LaTeX only when appropriate

- If the venue requires or supplies a LaTeX template and the manuscript is in LaTeX, use the official class/style and sample structure.
- If the journal allows free-format initial submission, do not force a publisher template merely for appearance; still meet content and file requirements.
- If the venue requires Word, a web form, or another format, do not convert to LaTeX by default.
- For outline-only or argument-review tasks, template migration is usually unnecessary; identify future compliance work instead.
- When revising an existing official-template manuscript, preserve its class, style files, and semantic macros unless the user requests migration.

Never shrink margins, fonts, line spacing, caption size, bibliography spacing, or style definitions to evade limits. Do not edit official style files unless the venue explicitly instructs authors to do so.

## Build a target-venue exemplar corpus

Official rules specify compliance; well-chosen accepted papers reveal rhetorical norms that rules do not encode. When substantial drafting or venue conversion is requested, inspect a small, purposeful corpus rather than copying a fixed number of papers.

Choose exemplars that are:

- officially accepted or publisher-hosted;
- recent enough to reflect the current venue, while including a canonical older paper only when structurally relevant;
- the same article type or track;
- close in problem type, method/evidence balance, and intended audience;
- diverse enough to avoid mistaking one author's preference for venue convention.

Extract high-level patterns:

- abstract moves and information density;
- where the gap, method, and main result appear;
- section order and approximate allocation of attention;
- integration or separation of Related Work, Results, and Discussion;
- theorem/algorithm presentation;
- figure, table, and caption conventions;
- placement of limitations, ethics, reproducibility, and supplement pointers.

Do not copy sentences, rhetorical flourishes, citation counts, or visual designs. Do not infer a formal rule from one paper. Official instructions override exemplars.

## Cite content, not imitation

Papers consulted only to understand venue style normally do **not** need to be cited in the manuscript. Cite an exemplar when its scientific idea, definition, method, data, result, or claim is substantively used or discussed. Make that citation support the nearby sentence; do not add it merely to signal venue familiarity.

## Maintain a compliance record

For a final or near-final manuscript, preserve an internal record:

`requirement | official source | checked date | manuscript location | status | action`

At minimum audit:

- correct track/article type and template version;
- title/abstract/keyword constraints;
- page or word limits and reference counting;
- anonymity and hidden PDF/file metadata;
- author, affiliation, acknowledgment, funding, and conflict rules for the stage;
- ethics, consent, IRB, data/code, model, and generative-AI disclosures where applicable;
- permitted AI-assistance scope and required disclosure;
- accessibility, figure resolution, color, fonts, and file-size requirements;
- bibliography format and supplement linkage.

If an official requirement cannot be verified, label it unresolved and do not claim compliance.
