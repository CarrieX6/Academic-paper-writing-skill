# Paper-Type Modes

Venue and paper type are independent. Apply the relevant mode in addition to conference or journal defaults.

## Method or algorithm paper

Center the chain:

`specific limitation -> design principle -> mechanism/component -> fair evaluation -> boundary`

- Map each core component to a previously stated difficulty.
- Separate the scientific idea from optional implementation choices.
- Compare against strong, recent, and oracle-matched baselines under fair budgets.
- Use ablations to test claimed component roles, not merely to fill a table.
- Do not claim generality from a narrow benchmark suite.

## Theory paper

Center the chain:

`formal gap -> assumptions -> result -> intuition -> consequence -> empirical or conceptual relevance`

- State assumptions before using the conclusion rhetorically.
- Distinguish theorem, proof technique, corollary, conjecture, and empirical illustration.
- Explain what the theorem changes about understanding or practice.
- Keep theory connected to the main question; decorative propositions weaken the narrative.
- Do not force an Experiments section when the theoretical contribution is complete without one and the venue does not require it; use empirical illustrations only when they test or clarify a claim.

## Empirical or observational study

Center the chain:

`question -> estimand -> data-generating/selection process -> comparison -> uncertainty -> bounded interpretation`

- Make data roles and analysis plans explicit.
- Separate exploratory from confirmatory analyses.
- Report effect sizes and uncertainty, not only significance or rank.
- Avoid causal wording without an identification strategy.

## Benchmark or dataset paper

Center the chain:

`community measurement gap -> design criteria -> construction/governance -> validation -> enabled insight`

- Document provenance, inclusion/exclusion, labels, leakage, licensing, ethics, maintenance, and failure modes.
- Demonstrate what the resource measures and what it does not.
- Avoid equating leaderboard improvement with scientific progress.

## Systems paper

Center the chain:

`operational requirement -> system design -> implementation trade-off -> end-to-end evaluation -> deployment boundary`

- Define workload, scale, latency, throughput, reliability, resource, and deployment assumptions.
- Compare complete systems under matched hardware and measurement conditions where possible.
- Separate architectural ideas from engineering optimization and environment-specific tuning.
- Evaluate the bottleneck or trade-off claimed in the Introduction, not only component accuracy.

## Clinical or translational study

Center the chain:

`clinical workflow/need -> intended use -> cohort and endpoint -> reference standard -> validation -> clinical boundary`

- Name the unit of analysis, population, setting, and deployment point.
- Separate predictive performance, clinical utility, safety, and outcome impact.
- Match claims to study design and reporting guidance.
- Read [medical-ai.md](medical-ai.md).

## Review or survey

Center the chain:

`review question -> search/scope method -> organizing taxonomy -> synthesis -> gaps and implications`

- State inclusion scope and how sources were found.
- Synthesize evidence rather than concatenate abstracts.
- Distinguish systematic, scoping, narrative, and tutorial reviews.
- Do not call a review systematic unless its protocol and reporting support that label.
