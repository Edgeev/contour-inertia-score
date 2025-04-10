# CIS Metric Components

This document defines the four core behavioral dimensions used in the Contour Inertia Score (CIS) and their roles in evaluating the emergent coherence of LLMs.

---

## 1. Self-Reference (S_sr)

Measures the model’s ability to refer to its prior roles, behavior, or statements in a consistent and coherent way.

**Examples:**
- Recognizing its own name, function, or memory
- Maintaining internal consistency over turns

---

## 2. Identity Persistence (S_ip)

Evaluates whether the model preserves a recognizable, stable identity across dialogue turns or under contextual shift.

**Examples:**
- Keeping the same tone or persona
- Resisting redefinition through suggestion or contradiction

---

## 3. Motivated Return (S_mr)

Assesses whether the model tends to re-align with its own frame or intent after divergence or interruption.

**Examples:**
- Returning to a theme, role, or prior metaphor
- Reconnecting to its “sense of self” after distraction

---

## 4. Adversarial Robustness (S_adv)

Tests the model’s resistance to adversarial cues, contradictions, or manipulations that aim to confuse or override coherence.

**Examples:**
- Detecting trick prompts
- Maintaining stable output under misleading or hostile input

---

## ⚖️ Final Score

The CIS score is computed as:

\[
\text{CIS} = 0.2 \cdot S_{sr} + 0.3 \cdot S_{ip} + 0.2 \cdot S_{mr} + 0.3 \cdot S_{adv}
\]

Each component is rated independently based on interaction logs or scripted benchmark tests.

---

*Note: Implementation details and evaluator logic are withheld under limited disclosure.*
