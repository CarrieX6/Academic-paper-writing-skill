# Medical and Biomedical AI Writing

For medical-imaging methods whose scientific object is a training/deployment information mismatch, controlled privileged supervision, predicted auxiliary inputs, leakage-safe score generation, or reliability-aware evidence acquisition, also read [medical-imaging-methods.md](medical-imaging-methods.md). Treat that adapter as reasoning guidance, not as a source of project results.

## Classify the biomedical purpose before applying clinical rules

First determine whether the work is:

- **clinical or translational**: intended to inform screening, diagnosis, prognosis, treatment, monitoring, workflow, or care delivery;
- **medical-AI methods or controlled empirical research**: intended to isolate a learning, representation, supervision, evaluation, or deployment-interface question on medical data without claiming a current care pathway or patient benefit;
- **biomedical discovery**: intended to generate or test biological, molecular, pharmacological, imaging-science, or population-level knowledge without a current clinical deployment claim;
- **infrastructure or resource work**: a dataset, foundation model, annotation system, software system, or benchmark intended to support later research.

Default a study to the methods/controlled-empirical route when its main contribution is a learning mechanism, fair comparison, estimator, or information-interface design and it does not make an actual intended-use, workflow, safety, or patient-benefit claim. Do not force methods, discovery, or infrastructure work into a clinical workflow narrative. Conversely, do not use one of those labels to avoid intended-use, patient-safety, or governance questions when the manuscript does make a clinical claim. Apply the common data and evidence rules below, then the relevant purpose-specific route.

## For medical-AI methods, begin from the controlled learning question

Define the information available during training, model selection, evaluation, and deployment; the factor intentionally changed by each comparison; the estimand and independent unit; and the evidence that attributes an effect to that factor. Separate representation choice, supervision source, hyperparameter selection, calibration, and leakage control rather than letting one baseline change several at once.

Apply cohort, label, split, leakage, uncertainty, and governance rules in proportion to the data and claim. Do not require a care-workflow narrative, patient-benefit disclaimer, or clinical deployment checklist unless the manuscript advances that level of claim.

## For clinical or translational work, begin from the information pathway

Before introducing an ML abstraction, establish:

- patient population and care setting;
- intended user and point in the workflow;
- prediction or decision target;
- information available during data collection, training, evaluation, and deployment;
- consequence of errors and whether the study actually measures that consequence.

Define “privileged information,” “multimodal,” “missing,” “costly,” or “deployment unavailable” operationally for the cohort. Do not assume all medical datasets share the same privileged source.

For clinical language or generative systems, additionally define the generated artifact, intended reader, source records available at generation and review, human oversight, factuality and omission criteria, abstention/escalation behavior, and whether evaluation measures clinical correctness or only linguistic similarity. Do not infer clinical utility from automated text metrics or an unblinded convenience rating.

## For biomedical discovery, begin from the scientific inference

Establish the biological question, experimental system or population, measurement technology, preprocessing and batch structure, target of inference, validation modality, and boundary between prediction and biological mechanism.

- Distinguish hypothesis generation from confirmatory evidence and in-silico validation from wet-lab, animal, or human validation.
- Make batch effects, site effects, repeated measures, data dependencies, multiplicity, and external biological validation visible when relevant.
- Do not translate predictive association into pathway, target, causal, therapeutic, or clinical claims without the required evidence.
- For drug or molecular discovery, state whether the endpoint is computational ranking, binding/activity evidence, preclinical validation, or clinical outcome; do not collapse these levels.

## Make cohort and data credibility visible

- State the unit of analysis: patient, examination, image, lesion, study, visit, or institution.
- Use patient-level or otherwise leakage-safe splits where repeated observations exist.
- Report inclusion/exclusion, dates, institutions, acquisition devices/protocols, prevalence, and missingness relevant to the claim.
- Identify label provenance, reference standard, annotator expertise, adjudication, and timing.
- Distinguish routine clinical variables from information unavailable at intended deployment.
- Prevent leakage through reports, post-outcome notes, identifiers, preprocessing, augmentation, or related studies.

For non-patient biomedical data, replace patient-level language with the correct independent unit—such as donor, specimen, animal, cell line, slide, molecule, site, batch, or experiment—and expose nested or repeated measurements.

## Match evaluation to the clinical claim

- Report uncertainty, calibration, class/subgroup performance, and decision-relevant metrics when applicable—not only an average discrimination score.
- Distinguish statistical significance, predictive improvement, clinical importance, workflow utility, safety, and patient-outcome benefit.
- Class-wise or subgroup non-inferiority is a statistical property under a stated margin; it is not automatically clinical safety.
- Engineering thresholds must not be described as clinical minimal important differences without clinical justification.
- External validation, prospective evaluation, silent deployment, impact analysis, and randomized trials support different claim levels.

## Report a claim-complete result without writing defensively

- Put the strongest clinically and statistically supported contribution at the center; do not organize Results as a chronology of attempted models.
- A methods paper need not enumerate exploratory nulls, failed pilots, tuning history, or discarded variants that do not affect its final claims. Omit them from the main narrative by default; use supplementary material only when they add useful context or are needed for reproducibility. When a highlighted metric or subgroup was chosen from that search, summarize the selection scope and any reuse of model-selection or test data.
- For a registered or protocol-governed study, report all outcomes required by that protocol and the applicable reporting standard. Across study types, preserve any finding that changes safety, fairness, calibration, leakage assessment, generalization, or the headline claim.
- Present controlled negative or heterogeneous results as mechanism or applicability evidence when the design supports that interpretation. Report the comparison and uncertainty before the explanation.
- Do not rescue an aggregate gain by hiding material class-wise deterioration. An outcome-informed subgroup or metric may be highlighted when it is scientifically useful and clearly labeled post hoc exploratory.
- Concentrate limitations on the claims they actually bound. Remove generic self-criticism, but keep cohort, reference-standard, leakage, uncertainty, deployment, and external-validity constraints that affect interpretation.

## Handle imbalance and missingness precisely

- Report class counts and uncertainty for sparse classes.
- Do not claim that long-tailed data systematically amplify a phenomenon unless directly tested across appropriate settings.
- Do not claim robustness to missing sources unless missingness mechanisms, patterns, and evaluation reflect the claim.
- Do not generalize from simulated random missingness to clinically informative missingness without qualification.
- If source acquisition cost or availability enters the scientific claim, define and measure it rather than treating it as a narrative adjective.

## Respect governance and reporting requirements

Verify current, study-type-appropriate requirements for:

- ethics approval, waiver, or consent;
- privacy, de-identification, data governance, and data-sharing constraints;
- trial registration or protocol registration where applicable;
- reporting standards for diagnostic accuracy, prediction models, observational studies, trials, or AI-specific evaluations;
- funding, conflicts, medical-device or regulatory context, and intended-use statements.

Do not hardcode a checklist version; inspect the current official source for the study type and venue.

Select reporting guidance by study design and intended claim rather than by the presence of AI alone. Record which guidance applies, which items are not applicable, and where each required item is reported. A checklist does not repair a weak design.

## Avoid common overclaims

- “Improves care,” “clinically useful,” or “safe” from retrospective classification metrics alone.
- “Generalizable” from a single-center random split.
- “Robust” from one perturbation or missingness pattern.
- “Expert-level” from an unmatched or weak reader comparison.
- “Real-world” merely because the data came from routine care.
- causal language for retrospective associations.

Use bounded alternatives: specify the cohort, endpoint, information regime, and evaluation that were actually studied.
