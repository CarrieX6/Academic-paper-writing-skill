# Medical-Imaging Information-Interface Methods

## Contents

- scope and route selection;
- controlled learning questions;
- source authority and evidence invariants;
- cross-study synthesis and negative evidence;
- leakage, privacy, and terminology.

## Scope

Use this adapter when the scientific object is how information available at training, selection, evaluation, or evidence acquisition becomes usable under a narrower deployment interface. The information may include expert annotations, geometry, auxiliary grades, concepts, reports, paired modalities, prior examinations, or other evidence. Deployment may expose images alone, predicted auxiliary variables, or a cost-constrained evidence pathway.

This adapter specializes [medical-ai.md](medical-ai.md). It is not a source of project facts and does not replace an approved manuscript, frozen result panel, evidence ledger, protocol, or author decision. Do not infer that privileged information transfers, improves prediction, identifies a mechanism, or yields clinical utility merely because it exists.

## Route by scientific object, not keywords

Use the current manuscript or artifact identity and its controlled scientific question before considering terminology. An isolated occurrence of `distillation`, `concept bottleneck`, `cross-fitting`, `multimodal`, or `privileged information` is not enough to select this adapter.

Route each consequential claim and its evidence to one primary scientific object. A single study normally has one primary evidence route; supporting analyses may have secondary roles. Cross-study or program-level synthesis is allowed only when the user requests it or the document mode requires it. Keep project identity, evidence maturity, and validation status visible, and never transfer a result or mechanism conclusion from one study to another.

## Controlled privileged-supervision studies

When a method assigns different supervision sources to different parts of a training target, define exactly which source controls which quantity. Preserve distinctions among:

- target-class probability quality and conditional allocation among non-target classes;
- a source-specific increment and universal superiority over simple supervision;
- ranking/discrimination, raw probability quality, calibrated probability quality, and decision utility;
- matched-target controls and baselines that change multiple factors;
- training-only information and the interface actually available at deployment.

The publishable object may be controlled source assignment and mechanism attribution rather than a new loss alone. Task-dependent, null, or cross-zero findings that materially delimit transfer, reliability, or applicability remain part of the scientific answer. Results with no bearing on the final claim may be compressed, moved to supplementary material, or omitted from the manuscript narrative.

## Predicted auxiliary-input studies

When deployment exposes predicted rather than annotated concepts or auxiliary variables, separate:

- matching training inputs to deployment inputs from choosing a representation form;
- upstream auxiliary prediction quality from downstream task use;
- a fixed auxiliary predictor from a selected downstream model;
- shared hyperparameters from fair representation-specific selection;
- annotated or oracle inputs as reference conditions from deployable evidence.

Cross-fitting or out-of-fold generation is a leakage-control design, not automatically a performance mechanism. An invertible transformation can still interact with parameterization and regularization; do not infer that one representation is intrinsically more informative, faithful, causal, interpretable, or universally best without direct evidence.

## Distillability and report-privileged studies

- A stronger teacher is not necessarily more distillable to a constrained student.
- Generic out-of-fold predictions may depend on artifacts fitted outside the fold; rebuild the dependency-closed learner pipeline when the claim requires leakage-safe estimation.
- Aggregate transfer does not establish rare-class recovery, calibration, or clinical benefit.
- Training-only report access and test-time consultation define different deployment contracts and must not be merged rhetorically.

Use this as the primary route only when the current artifact explicitly makes distillability or report-privileged learning its central scientific object.

## Reliability-aware evidence acquisition

For work on selective prediction, abstention, retrieval, added sequences, prior examinations, or expert escalation, define:

- the base evidence interface and each optional evidence source;
- the reliability signal and whether it is estimated without evaluation leakage;
- acquisition cost, stopping rule, abstention or escalation action, and decision objective;
- whether utility, safety, workload, or patient benefit is measured rather than assumed;
- the maturity of cohort governance, reference standards, missingness handling, and external evaluation.

Do not describe a development-stage design as externally validated, deployed, safe, or beneficial to patients. A future test bed may motivate a direction but cannot validate a separate completed study.

## Separate task authority from scientific-fact authority

For task scope, document identity, output form, and authorized edits, use the user's current instruction together with the current artifact's explicit identity and active project decisions.

For numbers, comparisons, analysis status, validation status, and scientific conclusions, prefer:

1. frozen result tables, de-identified aggregate panels, validation receipts, manifests, hashes, and approved analysis outputs;
2. the latest scientific artifact explicitly marked approved, integrated, frozen, or superseding;
3. current evidence ledgers, protocols, and decision records;
4. the current manuscript source;
5. project-status documents;
6. older manuscripts, exploratory notes, recovery logs, and historical plans.

A user may change scope or framing and may request re-verification, but a writing instruction does not by itself override a verified scientific fact. If corrected evidence supersedes an older record, update the source of truth and its status explicitly. A newer timestamp alone is not authority.

Prefer frozen de-identified aggregates, approved figures, receipts, and manifests for prose verification. Access patient-level or re-identifiable material only when the task genuinely requires it, the user has placed it within the governed scope, and the minimum necessary access is possible.

## Maintain evidence invariants

Keep the following separate:

- AUC or ranking, raw NLL or probability quality, calibrated NLL, and decision utility;
- training information, selection information, deployment information, evaluation-only information, and oracle references;
- patient-, examination-, lesion-, image-, slice-, and site-level units;
- internal holdout, external validation, exploratory reuse, and an untouched test set;
- observation, controlled attribution, mechanism hypothesis, causal claim, and clinical consequence;
- inspectable representation, semantic fidelity, causal explanation, and clinical interpretability;
- predictive improvement, selective prediction, workflow utility, safety, and patient benefit.

For every numerical or comparative statement, verify cohort, split, model-selection stage, independent unit, metric variant, direction, interval, and evidence status. Use “significant” only for an explicitly supported statistical claim. Do not infer equivalence from a non-significant comparison or robustness from one dataset, perturbation, or missingness pattern.

## Use negative and heterogeneous evidence constructively

For a controlled negative or heterogeneous finding:

1. state the question or estimand;
2. report the comparison, effect direction, and uncertainty;
3. identify which broad explanation the control rules out or weakens;
4. state which alternatives remain compatible;
5. narrow the transferable claim to the supported settings.

Do not write a failure diary or invent a rescue story. An outcome-informed metric or analysis may be used as post hoc exploratory evidence when clearly labeled; summarize the selection scope and data reuse when they affect interpretation. Do not silently redefine a frozen primary result or turn a task-specific effect into a claim of consistent superiority. Retain the internal analysis record.

## Enforce leakage, privacy, and redistribution boundaries

- Keep repeated examinations from one patient in the same partition when patient independence is required.
- Do not use final diagnoses, target labels, post-outcome notes, identifiers, or identifier hashes as model features.
- For report-derived inputs, use only governance-approved structured fields or text processed under the project's leakage policy; de-identification alone does not remove label leakage.
- Retrieval must respect the active training partition and must not expose evaluation labels through cached artifacts.
- DICOM conversion does not by itself prove de-identification; metadata and burned-in pixels require separate checks.
- Do not inspect patient-level tables, free-text reports, DICOM headers, case adjudications, clinical images, videos, embeddings, or prediction caches merely to enrich prose.
- Local availability is not redistribution permission. Preserve dataset, image, figure, and derivative-work attribution and licensing.
- Internal audit records may retain necessary locators under project governance. Manuscripts, public repositories, and public responses must not expose internal paths, private project identifiers, patient-level examples, small-cell details, or unreleased values.
- Do not infer IRB/consent, funding, conflicts, author order/contributions, data/code availability, AI-use disclosure, or venue eligibility. Use author-confirmation placeholders.

## Keep terminology stable

Use the project's approved term when one exists. Potentially useful distinctions include `privileged information`, `deployment interface`, `image-only deployment`, `supervision-source assignment`, `matched-target control`, `predicted auxiliary input`, `exposure mismatch`, `nested score generation`, `cross-fitting`, `out-of-fold`, `selective prediction`, `abstention`, and `expert escalation`.

Do not rotate among synonyms merely to vary prose. Maintain an explicit Chinese–English term map when planning is in Chinese and the manuscript is in English.

Use mechanism-first, decision-relevant prose: name the inferential problem, isolate what the comparison changes, report the decisive evidence, and state the boundary. Avoid both universal-benefit hype and defensive lists of everything the study did not attempt.
