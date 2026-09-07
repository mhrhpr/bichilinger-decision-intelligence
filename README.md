# Bichilinger Decision Intelligence

Evidence-grounded strategic decision system inspired by the documented decision patterns of Otto von Bismarck, Winston Churchill, and Henry Kissinger.

## Historical data model

Each historical decision is represented with:
- actor
- date / period
- context
- decision
- alternatives
- rationale reconstructed from evidence
- immediate outcome
- long-term impact
- failure / criticism
- historical significance
- impact scores
- confidence
- source references

**Important:** scores are analytical judgments by the dataset designers, not historical facts. Reconstructed counsel is not a quotation or a claim about private thoughts.

## Impact scoring

`impact_score` is a 0–100 composite:
- 30% scale of consequences
- 25% durability
- 20% strategic leverage
- 15% counterfactual importance
- 10% breadth of affected stakeholders

Each component is scored 0–10 and normalized to 0–100. `risk_score`, `reversibility_score`, and `confidence` are separate dimensions.

## Data quality principle

Prefer primary documents, official archives, scholarly biographies, diplomatic records, and reputable historical reference works. Where historians disagree, the record should preserve the disagreement rather than force a single narrative.

No fabricated quotations. No invented private thoughts. Historical facts and analytical reconstruction are explicitly separated.
