# Scientific and Biomedical Discovery AI

Use this adapter for AI intended to generate or validate scientific knowledge, molecules, materials, biological hypotheses, or experimental designs. Also apply [medical-ai.md](../medical-ai.md) when the work concerns patients, clinical workflows, diagnosis, prognosis, treatment decisions, or clinical utility.

- Define the scientific target and measurement process, including specimen, assay, instrument, simulation, curation, and preprocessing. A model predicts recorded measurements, which may differ from the underlying scientific construct.
- Set independence at the relevant biological or physical unit: donor, specimen, batch, plate, site, scaffold, protein family, laboratory, time period, or simulation family. Random row splits often overstate discovery or extrapolation.
- Audit batch effects, confounding, normalization leakage, replicate handling, missingness, and label/reference uncertainty. Report whether preprocessing choices were fixed before test evaluation.
- Choose splits that test the claimed novelty: temporal, scaffold, family, organism, laboratory, instrument, geography, or prospective holdout. A random split generally measures interpolation within the collected corpus.
- Compare with domain-standard computational and experimental baselines under matched information, not only generic ML baselines.
- Distinguish in-silico score, retrospective prediction, prospective prediction, wet-lab validation, independent replication, animal evidence, and clinical evidence. These are different validation levels, not interchangeable confirmations.
- For generated candidates, report validity, uniqueness, diversity, synthesizability or feasibility, search budget, filtering, and selection process. Successful testing of handpicked candidates does not estimate the hit rate of the full generator.
- Use negative controls, blinded measurements, preregistered selection criteria, replicate experiments, and independent laboratories when the scientific claim requires them.
- Separate association, prediction, hypothesis generation, mechanism, and discovery. Model attribution or latent structure alone does not establish a biological or physical mechanism.
- Check domain constraints such as conservation laws, units, stereochemistry, assay range, or causal ordering when relevant. Apparent benchmark gains may exploit physically impossible or experimentally inaccessible regions.
- Account for multiple candidate screening and adaptive experimentation when reporting significance or discovery rates.
- Preserve raw-data provenance, metadata, code, model versions, experimental protocols, and failed or null validation attempts needed to audit the discovery chain.
