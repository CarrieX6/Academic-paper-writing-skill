# Benchmarks, Datasets, and Machine-Learning Systems

## Benchmarks and datasets

- Define the construct the resource is intended to measure and identify important capabilities or populations it does not represent.
- Document provenance, collection and filtering, consent or lawful basis where relevant, licensing, governance, annotation instructions, annotator population, adjudication, and known uncertainty.
- Justify sampling and coverage against the target population or use. Dataset size alone does not establish representativeness, diversity, or difficulty.
- Audit duplicate entities, benchmark leakage, label leakage, temporal overlap, contamination by source models, and train/test dependencies. Publish enough grouping information to permit leakage-safe use when possible.
- Establish label or measurement validity, not only inter-annotator agreement. Disagreement may reflect ambiguity, plural valid perspectives, or a poor construct rather than annotation noise.
- Design splits and evaluation protocols around the intended generalization claim; random splitting is not a neutral default when entities, time, sites, creators, or families repeat.
- Use baseline systems to characterize the measurement, artifacts, shortcuts, and ceilings—not merely to launch a leaderboard.
- State versioning, maintenance, correction, withdrawal, access, and deprecation plans. Claims tied to a living resource should name its version.
- Separate evidence that a benchmark is difficult from evidence that it is scientifically valid. Low scores can arise from ambiguity, annotation error, or distribution artifacts.
- Do not infer broad scientific progress from leaderboard movement without showing that the movement tracks the intended construct.

## Machine-learning systems

- Define the workload, input distribution, service-level objective, scale, deployment topology, and quality constraint before reporting speed or efficiency.
- Report hardware, software, compiler/runtime, precision, parallelism, batch size, memory limits, and relevant power settings. Avoid comparisons across unmatched stacks unless the claim explicitly concerns complete deployed systems.
- Specify warm-up, caching, compilation, data loading, preprocessing, communication, concurrency, and measurement windows. Clearly separate end-to-end results from isolated kernels or components.
- Report throughput together with latency distributions and operating load; averages can conceal tail behavior and queueing collapse. Use trade-off curves when no single operating point dominates.
- Compare at matched output quality or task performance when claiming efficiency. Faster execution at materially lower quality is a different operating point, not an unqualified systems win.
- Repeat measurements and disclose run-to-run variability, failures, timeouts, and excluded runs. Benchmark noise and shared-infrastructure interference may be material.
- Evaluate the bottleneck, scale, reliability, recovery, or resource constraint named in the contribution. A microbenchmark cannot establish an end-to-end deployment claim.
- Measure cost, energy, or carbon with stated boundaries and instrumentation if they are claimed; do not infer them solely from runtime or hardware labels.
- Distinguish an algorithmic advance from implementation craftsmanship and platform-specific optimization, while crediting both accurately.
