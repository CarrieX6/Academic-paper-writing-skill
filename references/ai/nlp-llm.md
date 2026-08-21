# NLP and Large Language Models

- Record the exact model or checkpoint, access date for mutable services, system and user prompts, chat template, tool permissions, retrieval corpus/index snapshot, and decoding configuration needed to identify the evaluated system.
- Separate model capability from scaffolding due to retrieval, tools, demonstrations, self-consistency, verifier calls, prompt search, or additional test-time compute. Compare systems under the resource interpretation used by the claim.
- Audit benchmark contamination, prompt leakage, memorization, and overlap with fine-tuning, retrieval, or synthetic-data generators. Absence of known overlap is not proof of uncontaminated evaluation.
- Predefine or disclose prompt and demonstration selection. Report sensitivity when conclusions depend on prompt wording, order, few-shot examples, or output parsing.
- For stochastic generation, report sampling and retry budgets, aggregation rules, invalid-output handling, and uncertainty across prompts/items and model calls as appropriate.
- Validate automated judges against the construct being claimed. Disclose judge identity and prompt, order/randomization, ties, parsing, and potential self-, family-, verbosity-, or position-preference. Judge agreement alone is not ground truth.
- For human evaluation, define the sampling frame, instructions, blinding, annotator qualifications, compensation where relevant, adjudication, and uncertainty. Agreement metrics do not replace construct validity.
- Distinguish task success, factuality, calibration, citation correctness, harmlessness, preference, and linguistic quality. Do not collapse them into an undefined “quality” or “reasoning” claim.
- Treat chain-of-thought text as generated output, not direct evidence of the model's internal mechanism. Behavioral success on selected tasks does not prove a general reasoning faculty.
- For evolving API models, acknowledge reproducibility limits and archive all observable configuration and outputs permitted by policy.
