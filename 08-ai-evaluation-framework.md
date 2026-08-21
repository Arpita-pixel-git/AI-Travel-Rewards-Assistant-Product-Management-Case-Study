# 08 — AI Evaluation Framework

## Why Evaluation Matters

Incorrect reward recommendations can directly impact user trust and potentially lead to financial loss or poor redemption decisions.

Therefore, AI quality must be evaluated across both **model performance and product outcomes**.

## Evaluation Dimensions

### 1. Recommendation Accuracy

Does the recommendation correctly reflect the available reward and redemption information?

### 2. Data Freshness

Is the recommendation based on current reward rules, transfer ratios, availability, and point requirements?

### 3. Relevance

Does the recommendation match the user's travel goal and preferences?

### 4. Explainability

Can the user understand why the recommendation was selected?

### 5. Hallucination Rate

Does the AI generate unsupported reward rules, partners, prices, or redemption options?

### 6. Constraint Adherence

Does the recommendation respect user-defined constraints?

## Product Guardrails

- Ground recommendations in verified reward data
- Display data freshness where relevant
- Avoid unsupported claims
- Surface uncertainty
- Provide alternative options
- Allow users to verify important details

## Evaluation Approach

Create a representative evaluation dataset containing travel scenarios and expected recommendation outcomes.

Measure:

**Accuracy + Relevance + Groundedness + Explainability + Constraint adherence**

before expanding the AI experience.
