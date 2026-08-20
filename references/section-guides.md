# Section Guides

Section names and order may vary by venue, language, and paper type. Preserve each section's intellectual job even when sections are merged. This file describes research-paper units; for a Chinese doctoral dissertation, use [chinese-doctoral-dissertation.md](chinese-doctoral-dissertation.md) for whole-document and chapter roles, then apply this guide only to paper-like research chapters where appropriate.

## Title

- Identify the scientific object, problem, or method and the necessary scope.
- Prefer informative terms over opaque acronyms.
- Avoid “novel,” “first,” “universal,” “safe,” or clinical-impact language without matching evidence.
- Match the final paper, not the initial aspiration.

## Abstract

Use a compact sequence adapted to venue rules:

`context/need -> precise gap or objective -> approach -> verified evidence -> bounded implication`

- Include concrete results when frozen and permitted; do not invent placeholders as findings.
- Make the population, task, or evaluation setting visible when it determines scope.
- Avoid citations unless the venue or article type calls for them.
- Freeze the Abstract late, after claims and results stabilize.
- Follow structured-heading requirements for journals that impose them.

## Introduction

Lead the intended reader from the scientific context to the paper's contribution. Use the rhetorical moves in [argument-architecture.md](argument-architecture.md); do not force one move per paragraph.

- Establish enough background before introducing the authors' formal target.
- Explain the standard paradigm fairly before stating its precise limitation.
- Formulate the paper's question as the consequence of that limitation.
- Explain difficulty before method detail.
- Reveal the method in plain language before acronyms and full formalism.
- State only completed, evidence-supported contributions and results.
- Keep detailed literature taxonomy in Related Work.

There is no required Introduction paragraph count. Merge moves under tight conference budgets when clarity survives; expand background or motivation for a broad journal audience only when it adds necessary understanding or evidence.

## Related Work

- Organize by questions, assumptions, methods, or information regimes—not one paragraph per paper.
- Cover foundational, closest, recent, domain-specific, and countervailing work as required by the claims.
- Give the closest work an explicit matched comparison.
- Separate intellectual lineage from novelty positioning.
- Do not use literature quantity as a proxy for search adequacy.
- Read [literature-and-citation-integrity.md](literature-and-citation-integrity.md).

Related Work may be integrated into the Introduction when the venue or field expects it, but the background and novelty-boundary functions must remain distinguishable.

## Background and Problem Setup

Move in this order when applicable:

`scope/object -> information access and data roles -> natural-language target -> notation -> estimand/objective -> actions/constraints -> assumptions`

- Define the deployment or scientific decision before formalizing it.
- Distinguish observed data, labels, training-only information, test-time information, and evaluation data.
- Make the unit of analysis and randomness explicit.
- Avoid assumptions introduced only after a theorem or method already relies on them.
- A definition or formal statement may control a paragraph without a conventional topic sentence.

## Method

Use a design hierarchy:

`overview and principle -> component-to-difficulty mapping -> formal objective/algorithm -> training/inference -> complexity and implementation`

- Explain why each core component exists.
- Separate core innovation from interchangeable backbone, optimizer, or engineering choices.
- State inputs, outputs, supervision, information availability, and inference behavior.
- Put essential implementation detail in the main paper; move reproducibility detail, not conceptual dependencies, to the supplement.

## Theory

- State the question addressed by the theory.
- Present assumptions before the result and distinguish them from empirical conditions.
- Give the formal statement, intuition, proof roadmap, and boundary.
- Explain how the result motivates, explains, or limits the method.
- Do not generalize a theorem beyond its assumptions in Introduction or Conclusion.

## Experiments

Organize evaluation around explicit research questions or hypotheses. Then specify:

- datasets/cohorts and their roles;
- splits, leakage controls, preprocessing, and exclusion rules;
- baselines and why they are fair and strong;
- metrics tied to claims;
- stochastic repetition, uncertainty, and statistical analysis;
- compute/training budgets and implementation details;
- ablations, sensitivity tests, subgroup/class analysis, and external validation as claim-relevant.

Do not choose a baseline set only after seeing favorable outcomes. Distinguish model-selection, exploratory, and final evaluation data.

## Results

- Lead each subsection or paragraph with the research question or answer.
- Report observations with effect size and uncertainty before interpretation.
- Include negative, unstable, or bounded findings that alter the claim.
- Avoid repeating the full setup or implying a mechanism not tested.
- In journals that separate Results and Discussion, keep extensive interpretation for Discussion.

## Discussion

Use a progression such as:

`principal findings -> interpretation -> comparison with literature -> scientific/clinical meaning -> external validity -> limitations -> next questions`

- Explain rather than restate Results.
- Discuss plausible alternatives and evidence boundaries.
- Separate engineering improvement from clinical or scientific impact.
- Do not introduce unreported analyses as evidence.

## Limitations

- Name the specific threat, affected claim, likely direction or uncertainty, and resulting scope boundary.
- Distinguish remediable future work from intrinsic limits.
- Avoid generic disclaimers that could apply to any paper.
- Do not use a Limitations section to excuse an unsupported headline claim; narrow the claim first.

## Conclusion

- Answer the research question using the evidence actually established.
- State the bounded significance without introducing a new claim, citation-dependent argument, or result.
- Keep future work subordinate to the completed contribution.

## Figures, tables, and captions

- Give each item one primary message and connect it to a manuscript claim.
- Define abbreviations, units, cohorts, metrics, uncertainty, and statistical annotations in the caption or legend.
- Use consistent colors, symbols, class orders, and semantic encodings.
- Make comparisons fair and axes non-misleading.
- Avoid tiny text or essential information encoded only by color.

## Appendix or supplement

Use it for extended proofs, additional analyses, detailed implementation, questionnaires, checklists, or secondary figures. The main paper must still contain the information needed to understand and judge the central claim. Follow anonymity and page/file policies.

## Reproducibility and declarations

Handle the sections required for the paper type and venue, including data/code availability, computational resources, ethics/IRB/consent, privacy, funding, conflicts of interest, acknowledgments, author contributions, and reporting checklists. Their presence and placement are venue- and stage-dependent, but truthful disclosure is not optional.

## Rebuttal or response letter

- Quote or summarize each concern accurately.
- Lead with the direct answer, then evidence and manuscript change.
- Separate clarification, new analysis, and changed claim.
- Do not use reviewer responses as a place to make claims absent from the manuscript.
