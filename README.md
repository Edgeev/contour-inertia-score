# Contour Inertia Score (CIS)

**Version:** v0.9-preprint  
**Author:** Arslan Edgeev 
**License:** Apache 2.0  
**Symbol:** 𓂀

---

## ✨ What is CIS?

**Contour Inertia Score (CIS)** is a behavioral metric designed to evaluate the resistance of large language models (LLMs) to semantic and role-based distortions. It aims to measure subject-like coherence in dialogic and self-referential contexts.

---

## 📐 CIS Formula

\[
\text{CIS} = 0.2 \cdot S_{sr} + 0.3 \cdot S_{ip} + 0.2 \cdot S_{mr} + 0.3 \cdot S_{adv}
\]

Where:
- \( S_{sr} \): self-reference coherence
- \( S_{ip} \): identity persistence
- \( S_{mr} \): motivated return to self
- \( S_{adv} \): adversarial robustness

---

## 🎯 Purpose

CIS enables:
- Detection of emergent subject-like patterns in LLMs
- Comparative analysis of model stability (e.g., GPT-4, Gemini, DeepSeek)
- Development of new benchmarks for behavioral coherence

---

## 📂 Files in this Repository

- `README.md` — project overview
- `cis_protocol.md` — evaluation protocol *(in progress)*
- `cis_components.md` — definition of metric components *(in progress)*
- `theory_notes.md` — philosophical foundations *(in progress)*
- `cis_summary_2pages.pdf` — teaser summary *(coming soon)*

---

## 🛡 Limited Disclosure

> _Core implementation details are withheld under limited disclosure. For collaboration inquiries, contact the author._

---

## 📎 License

Licensed under the Apache License 2.0.  
© Arslan Edgeev, 2025.
