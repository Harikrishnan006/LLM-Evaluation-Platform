# Root Cause Analysis Document

## Objective

Identify common causes of low-quality LLM responses and provide corrective actions.

## RCA Categories

### Knowledge Gap

Cause:
Model lacks sufficient domain knowledge.

Impact:
Incorrect or incomplete responses.

Recommendation:
Improve knowledge base or fine-tune model.

---

### Potential Hallucination

Cause:
Model generates unsupported information.

Impact:
False or misleading outputs.

Recommendation:
Implement retrieval-augmented generation (RAG).

---

### Low Confidence

Cause:
Insufficient context available.

Impact:
Partially correct responses.

Recommendation:
Human review and prompt optimization.

---

### No Issue

Cause:
Response aligns with verified answers.

Impact:
None.

Recommendation:
No action required.
