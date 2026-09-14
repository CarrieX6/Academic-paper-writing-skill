# Academic Paper Writing Skill

**English** | [简体中文](README.zh-CN.md)

`academic-paper-writing` is a Codex skill for planning, drafting, structurally reviewing, humanizing, and rewriting evidence-grounded academic manuscripts. It combines argument architecture, author-voice recovery, non-defensive scientific storytelling, and claim-evidence control in one routed skill.

The skill is designed for:

- Chinese- and English-language conference papers;
- Chinese- and English-language journal articles;
- Chinese doctoral dissertations governed by Chinese degree-granting institutions;
- method, theory, empirical, benchmark/dataset, systems, clinical, human-subject, qualitative, mixed-methods, review, position, replication, and negative-result studies;
- medical AI and major AI domains, including ML, CV, multimodal learning, NLP/LLMs, RL, ML systems, robotics, HCI, trustworthy AI, security, and scientific discovery;
- evidence-preserving removal of formulaic AI-sounding prose and reconstruction around an author's documented academic voice;
- persuasive narrative design that foregrounds the strongest defensible contribution, omits non-consequential exploratory dead ends, and retains required or claim-changing evidence.

It does not treat a doctoral dissertation as a long journal article, Chinese prose as translated English, or a polished sentence as a substitute for scientific evidence. Humanization is not AI-detector evasion, disclosure avoidance, synonym spinning, or permission to alter the research record.

## Installation

Clone the repository into the Codex skills directory using the folder name expected by the skill:

```bash
git clone https://github.com/CarrieX6/Academic-paper-writing-skill.git ~/.codex/skills/academic-paper-writing
```

To update an existing installation:

```bash
git -C ~/.codex/skills/academic-paper-writing pull --ff-only
```

The required entry point is `SKILL.md`. Automatic skill discovery remains enabled. You can also invoke it explicitly with `$academic-paper-writing`.

## What to provide

The skill can infer many settings from the manuscript and repository, but results are more reliable when the request identifies:

- document mode: conference paper, journal article, or Chinese doctoral dissertation;
- target venue or degree-granting institution and current stage;
- manuscript language and, for English, required English variety;
- research type and intended audience;
- files or sections in scope;
- evidence status: completed, exploratory, running, planned, or disputed;
- protected content such as numbers, equations, citation keys, terminology, or published text;
- whether the task is review-only, surface humanization, paragraph reconstruction, or full narrative reconstruction;
- two to five author-approved writing samples when close voice matching is desired;
- whether the task authorizes file edits.

Do not paste invented results as placeholders. Give the skill access to the manuscript, verified bibliography, experiment artifacts, theorem/proof files, official template, and institutional or venue instructions when those materials are relevant.

## Usage examples

### 1. Review an English conference-paper Introduction

```text
Use $academic-paper-writing to review and restructure the Introduction and Related Work of my English ICLR method paper.

Target: ICLR 2027 initial submission
Language: American English
Audience: general ML reviewers
Evidence: the method is frozen, but the main experiments are still running
Constraints: do not invent results or claim that planned experiments are complete
Files: manuscript/sections/01_introduction.tex and 02_related_work.tex

First give a macro/meso/micro structural audit and a paragraph-function map. Then rewrite only the evidence-supported passages and list unresolved claims separately.
```

Expected behavior: the skill uses the conference, method-paper, argument, literature, and review routes; it keeps running results out of submission-ready claims and checks the current official venue rules before claiming compliance.

### 2. Rewrite a Chinese journal-paper Method and Experiments section

```text
请使用 $academic-paper-writing 重构这篇中文人工智能期刊论文的方法和实验章节。

目标：中文核心期刊，正式投稿模板稍后提供
语言：简体中文正文，英文摘要
范围：第3章方法、第4章实验
保护项：所有数字、公式、公式编号、引用键和图表数据必须保持不变
任务：允许调整小节顺序、拆分或合并段落，但不能补造实验设置或结果

请先建立主张—证据表和受保护元素清单，再修改正文；最后检查中英文术语和摘要主张是否需要同步。
```

Expected behavior: the skill applies native Chinese information structure rather than literal English syntax, records unknown journal rules as unresolved, and verifies protected elements after editing.

### 3. Convert an English conference paper into a journal article

```text
Use $academic-paper-writing to plan the conversion of this English conference paper into a journal submission.

Do not merely expand the prose. Identify what new scientific value is required, which evidence must remain in the main article, what belongs in supplementary material, and how prior-publication overlap must be disclosed. Produce a claim-evidence gap analysis before proposing the journal outline.
```

Expected behavior: conference-to-journal conversion is treated as a scientific extension requiring broader or deeper evidence, not as a lengthening exercise.

### 4. Audit a medical-AI manuscript

```text
请使用 $academic-paper-writing 从医学AI与机器学习审稿人的双重视角审查这篇英文医学影像论文。

重点检查：intended use、患者级数据划分、标签和参考标准、信息泄漏、类别不平衡、校准、外部验证、临床主张边界，以及模型比较是否公平。只做审查，不修改文件。
```

Expected behavior: the skill first distinguishes clinical/translational work from biomedical discovery or infrastructure work, then applies the corresponding medical and technical evidence rules. Retrospective predictive gains are not silently promoted to clinical utility or safety.

### 5. Build the main line of a Chinese doctoral dissertation

```text
请使用 $academic-paper-writing 复盘并重构我的中文医学AI博士毕业论文主线。

学校与阶段：某大学博士学位论文，准备盲审；学校细则和模板见 docs/degree_rules/
论文形态：待根据学校规定确认
研究内容：三个研究章节，其中两章来自已发表论文，一章为未发表研究
目标：建立“总体问题—子问题—章节贡献—证据—跨章综合—博士层面贡献”的完整链路
约束：不能把共同作者的贡献写成本人贡献，不能把未发表研究写成已经完成

请先输出博士论文级论证图、两级主张—证据台账和本人贡献矩阵，再判断哪些章节需要重写。
```

Expected behavior: the skill uses the Chinese doctoral-dissertation mode, verifies the institution's current rules, separates scholarly closure from institutional compliance, and does not concatenate paper abstracts into a dissertation contribution.

### 6. Integrate published papers into a Chinese dissertation

```text
请使用 $academic-paper-writing 将三篇已发表论文规划为中文博士论文中的研究章节。

在改写前，逐章检查：学校是否允许收录、可使用的论文版本、版权与公开仓储限制、共同作者同意、本人贡献、文本复用和重复证据。对于尚未核实的权限，只列为 unresolved，不要直接复制或翻译已发表正文。
```

Expected behavior: scientific attribution, text reuse, copyright permission, and candidate contribution are audited separately.

### 7. Review an LLM or multimodal paper

```text
Use $academic-paper-writing to audit this multimodal LLM paper for a top-tier AI conference. Focus on training/deployment information access, dataset contamination, prompt and decoding configuration, test-time compute, automated-judge validity, human evaluation, missing modalities, matched-resource baselines, and unsupported reasoning or generalization claims.
```

Expected behavior: only the common AI, vision/multimodal, and NLP/LLM adapters are loaded; unrelated RL, robotics, or HCI guidance is not loaded by default.

### 8. Request a reviewer-style audit without edits

```text
Use $academic-paper-writing to evaluate whether this manuscript's central claim is supported. Do not edit files. Lead with the overall verdict, then list critical, major, and minor issues using:

location | diagnosis | why it matters | evidence | concrete repair

Separate current evidence from planned experiments and identify any claim that must be narrowed or removed.
```

### 9. Humanize and sharpen a medical-AI methods paper

```text
请使用 $academic-paper-writing 重构并润色这篇英文医学影像论文，使论证更像作者本人、贡献更集中，但不要以规避 AI 检测为目标。

研究对象：训练信息与部署接口不一致的医学影像方法研究
改写权限：允许重排段落和贡献顺序，不改变实验记录
作者声线：以我提供的三段已确认文本为风格样本，不复用其中的主张或句子
保护项：所有数值、置信区间、方向、引用键、公式、数据划分、预设/探索性标签保持不变

请先确定最强的证据支持型贡献，再把其他结果组织为解释、验证或适用边界。只保留会改变主张、迁移边界或可靠性判断的跨零区间、任务异质性和关键负结果；与最终主张无关的探索性失败不必主动写入正文。最后单独执行主张完整性核对。
```

Expected behavior: the skill loads the public medical-imaging methods adapter and the voice/narrative route, distinguishes narrative emphasis from record selection, and performs an integrity pass after author-voice reconstruction. An installation-specific private research profile is loaded only when it exists locally and the current artifact belongs to that configured portfolio.

## Core behavior

The skill follows several non-negotiable principles:

- build the strongest honest scientific argument before polishing sentences;
- distinguish document mode, language, research type, audience, evidence maturity, stage, and governing authority;
- identify one central contribution and assign supporting analyses clear argumentative roles rather than narrating experiment chronology;
- recover author voice from approved patterns without copying phrases or imposing mechanical word and punctuation bans;
- use current official venue or degree-institution requirements rather than remembered rules;
- verify consequential citations and novelty boundaries from real sources;
- preserve required prespecified evidence and findings that materially change the headline, uncertainty needed to interpret reported effects, material limitations, and unresolved dependencies;
- omit non-consequential exploratory failures and nulls by default, and allow outcome-informed metrics, endpoints, baselines, subgroups, thresholds, or comparisons to support a transparently labeled exploratory narrative with relevant selection context;
- never present an outcome-informed choice as prespecified or let it silently replace a required primary analysis or declared final evaluation;
- never invent references, data, equations, proofs, experiments, results, templates, or institutional rules;
- never optimize wording to evade AI detectors or required disclosure;
- avoid fixed paragraph counts and one-size-fits-all Introduction structures;
- keep Chinese and English titles, abstracts, keywords, terms, symbols, and consequential facts semantically aligned;
- load domain adapters progressively rather than applying every AI checklist to every paper.

## Supported boundaries

Current first-class support is intentionally bounded to peer-reviewed Chinese/English conference and journal papers and Chinese doctoral dissertations governed by Chinese degree-granting institutions.

English-language doctoral dissertations, master's theses, undergraduate theses, grants, citation retrieval alone, and grammar-only proofreading are outside the primary workflow. The skill also does not replace a qualified statistician, proof reviewer, clinician, domain scientist, security assessor, qualitative-methods expert, ethics committee, editor, or doctoral committee.

## Repository structure

```text
academic-paper-writing/
├── README.md
├── README.zh-CN.md
├── SKILL.md
├── THIRD_PARTY_NOTICES.md
├── agents/
│   └── openai.yaml
└── references/
    ├── chinese-academic-writing.md
    ├── chinese-doctoral-dissertation.md
    ├── medical-ai.md
    ├── medical-imaging-methods.md
    ├── voice-and-narrative.md
    ├── ai-domain-adapters.md
    ├── ai/
    │   └── focused domain adapters
    └── document, section, literature, compliance, and workflow guides
```

`SKILL.md` is the routing and integrity entry point. Files under `references/` are loaded only when their mode is relevant. A local installation may add `references/local-research-profile.md`; it is intentionally ignored by Git so unpublished project identities, development status, internal locators, and other competitive research context are not published with the reusable skill.

## Upstream integration and licenses

The author-voice and academic-humanization route adapts ideas from [AIScientists-Dev/academic-humanizer at revision `94b88b2`](https://github.com/AIScientists-Dev/academic-humanizer/commit/94b88b23703bed7df507acae7d6d5876209a0cdf). The non-defensive narrative route adapts ideas from [Adkid-Zephyr/anti-defensive-writing-Skill at revision `102c8b2`](https://github.com/Adkid-Zephyr/anti-defensive-writing-Skill/commit/102c8b21acf5eda3a0aef3d9779a65db646c8980).

Both routes were revised to distinguish legitimate narrative curation from misleading outcome switching: non-consequential exploratory negatives may be omitted, and outcome-informed metrics may support a clearly labeled exploratory narrative with relevant selection context, while required primary evidence and claim-changing findings cannot be silently suppressed or retrospectively relabeled. Full upstream notices and modification notes are in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
