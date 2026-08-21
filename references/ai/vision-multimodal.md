# Computer Vision and Multimodal Learning

## Computer vision

- Define the sampling unit and split boundary: patient, scene, video, camera, geographic site, object instance, or image. Prevent leakage through adjacent frames, crops of the same source, burst captures, identities, or duplicated web images.
- Audit overlap with pretraining and benchmark data when memorization or transfer is relevant. Exact deduplication alone may miss resized, cropped, captioned, or near-duplicate content.
- Report resolution, cropping, augmentation, test-time augmentation, proposal generation, post-processing, and checkpoint selection when they affect the comparison.
- Match the metric to the visual task and deployment threshold. Aggregate accuracy can conceal class, scale, occlusion, subgroup, calibration, localization, or rare-event failures.
- Separate natural distribution shift from synthetic corruption robustness. Performance under one corruption family does not establish robustness to real deployment shift.
- For video or temporal tasks, preserve temporal order and report clip/video aggregation; do not treat correlated frames as independent evidence.
- For generative vision, evaluate fidelity, diversity, memorization, and task-specific utility separately. A single perceptual score or cherry-picked gallery cannot establish all of them.
- State how qualitative examples were sampled. Include typical failures and fixed or random selection rules; do not let hand-selected images carry a population-level claim.

## Multimodal learning

- Specify each source's role at training, validation, model selection, and deployment. Distinguish paired, weakly paired, asynchronous, missing, privileged, retrieved, and generated information.
- Establish whether every modality is genuinely available at the claimed deployment point. A modality that contains post-outcome text, future observations, or label-derived metadata may create leakage rather than useful fusion.
- Compare unimodal models, simple fusion, matched-capacity controls, and appropriate modality or source oracles. Improvements from more parameters or supervision do not by themselves demonstrate cross-modal synergy.
- Test whether the model uses each source rather than relying on the dominant modality. Report source ablations, counterfactual or shuffled-source controls, and performance conditional on informative source combinations when they are probative.
- Describe pairing quality, alignment, temporal synchronization, preprocessing, encoders, and missing-source handling. Misalignment can change the estimand rather than merely add noise.
- Evaluate missingness and corruption patterns that match the claim. Random modality dropout does not establish robustness to informative or workflow-dependent missingness.
- Distinguish source complementarity, redundancy, transfer, and privileged-information benefit. A stronger multimodal teacher does not establish that its additional information transfers to a deployment-limited student.
- If acquisition cost, latency, privacy, or availability motivates source selection, measure or operationally define it and report the resulting utility trade-off.
