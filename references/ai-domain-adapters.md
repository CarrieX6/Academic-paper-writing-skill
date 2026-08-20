# AI-Domain Evidence Adapters

Use this reference when an AI manuscript needs field-specific evidence checks beyond its paper type and venue mode. These adapters govern what the prose may claim from the reported study; they are not fixed experiment checklists.

## Set the boundary before routing

- Identify the scientific object being evaluated: an algorithm, learned model, dataset, system, human–AI interaction, security property, robot policy, or scientific hypothesis.
- State the unit of independence and the intended generalization axis. Images, prompts, frames, trajectories, repeated measurements, and model-generated samples are often not independent experimental units.
- Distinguish interpolation, distribution shift, domain transfer, temporal transfer, compositional generalization, and deployment validity. Do not use “generalizes” without naming which one was tested.
- Separate an algorithmic contribution from advantages due to additional data, modalities, pretraining, parameters, retrieval, inference compute, tools, human labor, or hardware.
- Match every comparison on the resource that the claim treats as controlled. If exact matching is impossible, report the asymmetry and bound the conclusion.
- Report uncertainty at the correct experimental unit and over the sources of variation relevant to the claim. More test examples do not replace independent training runs when optimization randomness matters.
- Treat benchmark scores, ablations, examples, and user studies as different evidence types. None automatically establishes mechanism, safety, causality, or real-world utility.

This skill supports argument and evidence auditing; it does **not** replace a qualified statistician, formal-proof reviewer, domain scientist, clinician, security assessor, qualitative-methods expert, or ethics review. When a central conclusion depends on specialist judgment, expose the dependency and seek that review rather than converting a writing heuristic into a validity certificate.

Do not hardcode changing venue rules, benchmark versions, reporting checklists, or legal requirements here. Verify their current official sources for the target submission.

## Route to focused adapters

Read only the adapter or adapters whose evidence standards are material to the manuscript. Do not load every adapter by default. Apply every relevant adapter to hybrid work—for example, a clinical vision-language model may require the [vision and multimodal](ai/vision-multimodal.md), [NLP/LLM](ai/nlp-llm.md), and [medical-AI](medical-ai.md) adapters.

- [General machine learning and learning theory](ai/general-ml-theory.md)
- [Computer vision and multimodal learning](ai/vision-multimodal.md)
- [NLP and large language models](ai/nlp-llm.md)
- [Reinforcement learning](ai/reinforcement-learning.md)
- [Benchmarks, datasets, and machine-learning systems](ai/benchmarks-systems.md)
- [Robotics and embodied AI](ai/robotics.md)
- [Human-centered AI and HCI](ai/human-centered-ai.md)
- [Trustworthy AI, privacy, and security](ai/trustworthy-ai-security.md)
- [Scientific and biomedical discovery AI](ai/scientific-discovery.md)

## Convert checks into manuscript controls

For each applicable adapter:

1. Add decisive assumptions and protocols to Methods, not only Limitations.
2. Put diagnostic and uncertainty results next to the headline result they qualify.
3. Constrain the Abstract, Introduction, title, and contribution list to the tested generalization axis and validation level.
4. Record unresolved evidence gaps in the claim-evidence ledger. Use a bounded claim or an explicit planned analysis; never fill the gap with confident prose.
5. Ask a specialist to review any proof, statistical model, clinical inference, qualitative analysis, security claim, or scientific mechanism on which acceptance or downstream safety materially depends.
