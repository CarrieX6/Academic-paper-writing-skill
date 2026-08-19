# Medical-AI Writing

## Begin from the clinical information pathway

Before introducing an ML abstraction, establish:

- patient population and care setting;
- intended user and point in the workflow;
- prediction or decision target;
- information available during data collection, training, evaluation, and deployment;
- consequence of errors and whether the study actually measures that consequence.

Define “privileged information,” “multimodal,” “missing,” “costly,” or “deployment unavailable” operationally for the cohort. Do not assume all medical datasets share the same privileged source.

## Make cohort and data credibility visible

- State the unit of analysis: patient, examination, image, lesion, study, visit, or institution.
- Use patient-level or otherwise leakage-safe splits where repeated observations exist.
- Report inclusion/exclusion, dates, institutions, acquisition devices/protocols, prevalence, and missingness relevant to the claim.
- Identify label provenance, reference standard, annotator expertise, adjudication, and timing.
- Distinguish routine clinical variables from information unavailable at intended deployment.
- Prevent leakage through reports, post-outcome notes, identifiers, preprocessing, augmentation, or related studies.

## Match evaluation to the clinical claim

- Report uncertainty, calibration, class/subgroup performance, and decision-relevant metrics when applicable—not only an average discrimination score.
- Distinguish statistical significance, predictive improvement, clinical importance, workflow utility, safety, and patient-outcome benefit.
- Class-wise or subgroup non-inferiority is a statistical property under a stated margin; it is not automatically clinical safety.
- Engineering thresholds must not be described as clinical minimal important differences without clinical justification.
- External validation, prospective evaluation, silent deployment, impact analysis, and randomized trials support different claim levels.

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

## Avoid common overclaims

- “Improves care,” “clinically useful,” or “safe” from retrospective classification metrics alone.
- “Generalizable” from a single-center random split.
- “Robust” from one perturbation or missingness pattern.
- “Expert-level” from an unmatched or weak reader comparison.
- “Real-world” merely because the data came from routine care.
- causal language for retrospective associations.

Use bounded alternatives: specify the cohort, endpoint, information regime, and evaluation that were actually studied.
