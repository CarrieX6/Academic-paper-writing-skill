# Trustworthy AI, Privacy, and Security

“Trustworthy” is an umbrella, not an outcome. Name the exact property—robustness, privacy, fairness, calibration, interpretability, security, misuse resistance, or safety—and use the corresponding evidence standard.

- Define the threat or failure model: protected asset, adversary or perturbation capabilities, knowledge, access, budget, objective, deployment surface, and defender assumptions.
- Evaluate adaptive attacks against the complete defense. Non-adaptive attacks, weak parameter settings, or apparent gradient failure do not establish robustness.
- Report clean utility, attacked utility, attack success, resource cost, and uncertainty under matched conditions. A defense may change the task or reject inputs rather than solve the advertised threat.
- Distinguish empirical attack resistance from certified robustness, and state the certificate's norm, radius, probability, and assumptions.
- For privacy, define adjacency, mechanism, accounting, composition, and the meaning of privacy parameters. Empirical membership or extraction tests do not prove differential privacy; differential privacy does not establish every confidentiality property.
- For fairness, justify group definitions, outcome/label validity, parity criterion, reference population, thresholds, and intersectional analysis. A parity metric encodes a normative choice and does not alone establish justice or absence of harm.
- For calibration, uncertainty, and out-of-distribution detection, define the target distribution, shift, score, threshold-selection data, and selective-decision policy. Performance on one synthetic OOD set does not imply open-world reliability.
- For explanations or interpretability, distinguish plausibility, faithfulness, stability, usefulness, and causal mechanism. User preference for an explanation is not proof that it faithfully represents model behavior.
- For red teaming and safety evaluations, document coverage and elicitation effort but do not treat failure to find an attack as proof of safety. Bound claims to the tested threat surface.
- Follow responsible-disclosure, dual-use, access-control, and participant-protection procedures appropriate to the risk. Verify current institutional, legal, and venue requirements rather than inferring permission from publishability.
