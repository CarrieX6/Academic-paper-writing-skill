# Venue Modes and Language

## Separate independent axes

Do not equate conference with ML, journal with medicine, or length with rigor. Choose independently:

- venue mode: conference, journal, or venue-neutral;
- paper type: method, theory, empirical, benchmark/dataset, systems, clinical, or review;
- audience: technical, clinical, or mixed;
- submission stage: initial, revision, camera-ready, or resubmission.

Current official venue rules override every default below.

## Conference defaults

Conference papers, especially in ML, often benefit from:

- reaching the precise technical gap and contribution earlier;
- a narrower central thesis and tighter scope;
- a compact Related Work section organized around the nearest novelty boundaries;
- a self-contained main paper despite supplementary proofs or extended experiments;
- prioritizing the evidence needed to assess novelty, correctness, fair comparison, and reproducibility.

These are tendencies, not permission to overclaim. Conference prose should not become more aggressive, and page limits do not justify omitting evidence needed for the central claim.

Experiments and Results may be combined if the venue and paper type favor it, but setup, observation, and interpretation must remain distinguishable.

## Journal defaults

Journal papers often allow or require:

- fuller scientific and application context;
- more explicit separation of prior work, materials/data, methods, results, and discussion;
- broader robustness, sensitivity, external-validity, and reproducibility evidence;
- a Discussion that interprets findings, compares them with literature, and states scope and limitations;
- article-type-specific declarations, reporting checklists, and structured abstracts.

Additional space is not a reason to repeat the same argument. Journal writing should not become more verbose; expansion must add evidence, explanation, validation, or scope analysis.

## Venue-neutral drafting

When the target venue is undecided:

- use a clean semantic source structure rather than an arbitrary venue template;
- avoid optimizing wording around a guessed page limit;
- keep figures, tables, references, and declarations modular;
- mark venue-dependent choices for later resolution;
- do not claim compliance with any venue.

## Initial submission, revision, and camera-ready

- **Initial submission:** enforce anonymity, page limits, permitted supplements, and contemporaneous-submission rules.
- **Revision/rebuttal:** answer reviewer concerns without silently changing the scientific target; distinguish new evidence from clarification.
- **Camera-ready:** remove required anonymization, integrate accepted changes, update metadata, and follow proceedings or publisher production instructions.
- **Journal resubmission:** remove previous-venue artifacts and adapt the scientific presentation, not merely the formatting.

## Choose English variety deliberately

English variety is a consistency constraint, not a measure of scholarly quality.

1. Follow an explicit journal or conference house-style requirement when one exists.
2. Otherwise preserve the manuscript's dominant, internally consistent variety.
3. For a new manuscript with no rule or established style, use the authors' preference; if unavailable, select one variety and record it rather than switching opportunistically.

Check pairs such as `behavior/behaviour`, `modeling/modelling`, `randomized/randomised`, and punctuation around quotations. Also check capitalization, hyphenation, number style, date format, and abbreviation conventions.

Do not normalize:

- official dataset, method, organization, or software names;
- article titles inside references beyond the bibliography style's transformations;
- verbatim quotations;
- established technical spellings whose official form differs from the manuscript's variety.

Use the target template's bibliography and heading styles rather than manually imposing a national style. Consistency within author prose is the goal.

## Mixed clinical and technical audiences

- Introduce the clinical workflow and endpoint before the ML abstraction.
- Give natural-language meaning before notation in Problem Setup.
- Keep Method technically precise rather than replacing terms with vague clinical analogies.
- Make Experiments answer both technical validity and data/cohort credibility.
- Use Discussion for clinical or operational interpretation; do not place unsupported utility claims in the Introduction.
