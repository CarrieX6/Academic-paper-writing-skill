# General Machine Learning and Learning Theory

## Empirical ML

- Define the task, data-generating setting, optimization budget, model-selection protocol, and evaluation estimand before comparing headline metrics.
- Audit train/validation/test independence, including preprocessing fitted on pooled data, repeated entities, temporal leakage, near-duplicates, pretrained-data overlap, and test-set-guided iteration.
- Compare against strong, applicable baselines with comparable data, supervision, architecture scale, tuning effort, and train/inference compute. Label deliberately unmatched comparisons as such.
- Separate gains from the proposed principle from gains due to backbone, initialization, augmentation, loss tuning, ensembling, or additional inference. Use targeted controls and ablations that test the claimed mechanism.
- Report per-run results or suitable uncertainty across independent runs when training randomness is material. A standard deviation across test items from one trained model does not quantify training variability.
- Define the family over which hyperparameters were selected and avoid giving the proposed method privileged tuning access. State whether baselines were retuned in the new setting.
- Account for evaluation multiplicity when many datasets, metrics, checkpoints, or variants were tried. A selectively reported win does not support a general superiority claim.
- Test the axes named in the claim. A robustness, efficiency, data-efficiency, scalability, or transfer claim requires deliberate variation of the corresponding condition and an appropriate curve or trade-off, not one operating point.
- Treat an ablation as evidence that a component mattered in the tested configuration, not as proof of the authors' proposed causal mechanism.

## Learning theory

- Define objects, probability space, quantifiers, assumptions, and asymptotic regime before stating the result's consequence.
- Keep theorem, lemma, corollary, proof sketch, conjecture, heuristic, and empirical observation visibly distinct.
- Check whether the assumptions hold for the algorithm and experiments used to motivate the theorem. If not, present the result as an idealized explanation rather than a guarantee for the implementation.
- State what is bounded, in what sense, with what probability, and which quantities are observable or tunable. Do not translate an expectation or asymptotic result into a finite-sample high-probability guarantee.
- Compare an upper bound with a lower bound only when their problem classes, information models, constants/log factors, and parameter regimes permit the comparison.
- Identify vacuous or practically unreachable regimes and avoid using order notation to hide dominant constants or dependencies central to the claim.
- Ensure every advertised theorem has a complete, traceable proof or a clearly marked dependency on an established result whose conditions are verified.
- Use machine checking, symbolic tools, or numerical illustrations as supporting aids only; they do not substitute for proof review. Request specialist review when correctness of a new proof is central.
