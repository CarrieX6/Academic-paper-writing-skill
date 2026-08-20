# Argument Architecture

## Treat structure as an argument, not a container

Start from the paper's inferential chain:

`real or scientific context -> existing knowledge/practice -> unresolved limitation -> precise question -> difficulty -> response -> evidence -> bounded significance`

The chain is diagnostic. It does not prescribe eight paragraphs or eight sections. A short conference Introduction may combine context with the established paradigm and combine the solution with contributions. A broad journal Introduction may separate the same moves because different claims need different evidence. The deciding test is whether a prepared but non-specialist reader can reconstruct the argument without guessing.

For a Chinese doctoral dissertation, the whole document is hierarchical rather than one enlarged version of this chain: an overarching question is decomposed into chapter-level questions and reunited through cross-chapter synthesis. Read [chinese-doctoral-dissertation.md](chinese-doctoral-dissertation.md).

## Use rhetorical moves adaptively

For an Introduction, consider these moves:

1. Establish the concrete scientific or deployment context.
2. Explain the accepted paradigm or most natural existing response.
3. Identify exactly what that response cannot establish or solve.
4. State the research question, target, or decision induced by the gap.
5. Explain why the question is technically or scientifically difficult.
6. Introduce the proposed idea at natural-language level, then name it.
7. State verified contributions and key evidence.

These are **moves**, not paragraphs. Combine them only if the combined paragraph still has one controlling function. Split one move if it introduces multiple abstractions, distinct evidence bases, or a necessary change in audience level. Do not target a fixed number of paragraphs.

## Climb the audience ladder

Move from what the intended reader already understands to the paper's formal object:

1. concrete object, workflow, or phenomenon;
2. field-specific concept;
3. precise technical abstraction;
4. notation or formal problem.

For mixed medical-ML readers, explain what information exists in the clinical workflow before calling it a privileged modality, and explain the decision before giving its estimand.

## Give every paragraph one controlling function

A strong expository paragraph commonly contains:

`controlling claim/function -> clarification or definition -> evidence/example -> implication -> transition`

Not every paragraph needs all five elements. The invariant is one necessary function, not a fixed sentence template.

Acceptable controlling openings include:

- a claim that the paragraph supports;
- a bridge that contrasts the previous position with the next;
- a definition that establishes the paragraph's object;
- a research question the paragraph then resolves or sharpens;
- a theorem, proposition, algorithm step, or experimental question.

Formal definitions and theorem statements need not be preceded by decorative topic sentences. A short transition paragraph can be valid when it performs a necessary structural bridge, but it should be merged if it merely repeats neighboring content.

The controlling function is semantic, not an English sentence template. In Chinese prose, a concise setup or contrast may precede the explicit claim when it improves logic and remains locally recoverable; read [chinese-academic-writing.md](chinese-academic-writing.md).

## Test paragraph necessity and order

Use four tests:

1. **Deletion:** What definition, evidence, inference, or transition becomes unavailable if this paragraph is removed? If nothing material is lost, delete or merge it.
2. **One-function:** Can the paragraph be summarized by one accurate clause? If not, split or establish hierarchy.
3. **Known-new:** Does the opening connect to established information before introducing the next abstraction?
4. **Dependency:** Are concepts defined before use, and does every “therefore,” “however,” or “this” have an explicit target?

Reverse-outline the manuscript using one line per paragraph. Reorder the outline before rewriting sentences.

## Control concept release

- Introduce one main abstraction at a time unless the reader already knows the others.
- Define operationally before naming where possible.
- Give a concrete example before dense formalization when the example reduces ambiguity.
- Delay method names and acronyms until the problem and design principle are intelligible.
- Avoid synonyms for core technical objects; lexical variety is less important than referential stability.

## Maintain section-level progression

Adjacent paragraphs need an identifiable relation: elaboration, cause, consequence, contrast, qualification, evidence, synthesis, or transition. Repeated parallel facts without synthesis usually belong in a table, a condensed Related Work paragraph, or nowhere.

An Introduction should not become a compressed bibliography. Related Work should not become an annotated list. Results should not repeat Methods, and Discussion should not merely restate Results.

## Make figures and tables part of the proof

Every figure or table SHOULD answer a specific question or support a paper claim.

- State its intended message before designing it.
- Keep visual encodings semantically consistent across panels and figures.
- Make the caption self-contained enough to identify setup, comparison, metric, uncertainty, and takeaway without duplicating the full text.
- Refer to the figure where its evidence enters the argument, not only after the fact.
- Do not add decorative complexity or imply causality, safety, or generality beyond the underlying evidence.

## Recognize structural failure modes

- Beginning with the authors' formalism before establishing the real problem.
- Using a literature catalogue as background.
- Announcing the method before the reader knows the target or difficulty.
- Giving one paragraph multiple jobs to save space.
- Repeating the same limitation in Introduction, Related Work, and Discussion.
- Using polished transitions to hide a missing inference.
- Writing internal project-management language, reviewer-defense language, or experiment status into submission prose.
