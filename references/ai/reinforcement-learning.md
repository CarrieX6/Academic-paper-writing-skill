# Reinforcement Learning

- Specify the MDP/POMDP elements relevant to the claim: observations, actions, rewards/costs, horizon, termination, reset, stochasticity, and environment or wrapper version.
- Report interaction, gradient, wall-clock, and evaluation budgets when they differ. Steps, frames, episodes, and environment instances are not interchangeable measures of sample efficiency.
- Use independent seeds and show learning behavior over the training horizon, not only the best checkpoint or terminal mean. Predefine checkpoint selection, smoothing, evaluation frequency, and failure handling.
- Separate training returns from evaluation-policy returns. State whether evaluation is deterministic or stochastic and whether reward normalization, exploration, or environment randomization changes at evaluation.
- Match hyperparameter-search and environment-interaction budgets across methods, especially when instability permits selective reporting of successful runs.
- For offline RL, document behavior-policy coverage, dataset composition, trajectory dependence, action support, model-selection access, and any online interaction. High estimated value outside data support is not reliable evidence of improvement.
- Treat off-policy evaluation as an estimator with assumptions and uncertainty, not as observed deployment performance. Validate it when it bears the primary conclusion.
- Evaluate safety or constraint claims with constraint-specific metrics, violation severity, tail risk, and interventions; high mean reward does not establish safe behavior.
- Distinguish generalization across seeds, initial states, levels, dynamics, tasks, and real systems. Name and test the claimed axis rather than using a single unseen-level score as universal generalization.
