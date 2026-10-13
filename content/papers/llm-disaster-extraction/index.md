---
title: "From UNDRR Reports to Event Records: Schema-Constrained LLM Extraction of Georeferenced Disasters"
date: 2026-09-20
tags: ["large language models","information extraction","disaster risk reduction","geocoding"]
author: ["Camilla Andreozzi", "Phuong-Anh Nguyen-Le", "Zhijing Jin", "Revati Mani"]
description: "An LLM pipeline that turns UNDRR disaster-risk-reduction reports into structured, georeferenced hazard event records."
summary: "An LLM pipeline that turns disaster-risk-reduction reports into georeferenced event records with a fixed schema and controlled hazard vocabulary. Applied to 10,000 PreventionWeb documents, it produced 3,572 records across 24 hazard types."
editPost:
    URL: "https://doi.org/10.48550/arXiv.2609.23853"
    Text: "arXiv preprint"

---

---

##### Download

+ [Paper](https://arxiv.org/pdf/2609.23853)
+ [arXiv page](https://arxiv.org/abs/2609.23853)

---

##### Abstract

Disaster-risk-reduction archives describe hazard events in prose that databases such as EM-DAT (Delforge et al., 2025) cannot ingest directly. We present an LLM pipeline that generates candidate georeferenced event records using a controlled hazard vocabulary and fixed schema, retaining evidence for review. Applied to 10,000 documents from PreventionWeb, the knowledge hub managed by UNDRR, it produced 3,572 records from 1,913 documents across 24 hazard types and resolved 81% of location mentions to OpenStreetMap geometries. On 171 human-positive document windows from a stratified 217-document reference set, GPT-5 achieved 86.0% pooled attribute $F_1$, versus 44.2% for the spaCy-gazetteer baseline. Evaluation pools hazard families, location strings, and event years within documents, without assessing their assignment to individual events. GPT-5.4 ranked highest among ten LLMs (86.6% $F_1$). Verbatim evidence occurrence was 72.0% for GPT-5 and 47.2% for GPT-5.4, measuring textual traceability without establishing attribute support. We report production failure modes and automated label and location-rule compliance checks. Prompts, schema, and outputs will be released for adaptation to national reporting archives.

---

##### Citation

Andreozzi, Camilla, Phuong-Anh Nguyen-Le, Zhijing Jin, and Revati Mani. 2026. "From UNDRR Reports to Event Records: Schema-Constrained LLM Extraction of Georeferenced Disasters." arXiv:2609.23853. https://doi.org/10.48550/arXiv.2609.23853.

```BibTeX
@misc{ANJM26,
author = {Camilla Andreozzi and Phuong-Anh Nguyen-Le and Zhijing Jin and Revati Mani},
title = {From {UNDRR} Reports to Event Records: Schema-Constrained {LLM} Extraction of Georeferenced Disasters},
year = {2026},
eprint = {2609.23853},
archivePrefix = {arXiv},
primaryClass = {cs.CL},
doi = {10.48550/arXiv.2609.23853}}
```
