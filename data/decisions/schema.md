# Historical Decision Record Schema

Required fields:
- `id`: stable identifier
- `actor`: bismarck | churchill | kissinger
- `date`: date or period
- `title`: decision label
- `context`: strategic situation before the decision
- `decision`: observable action/policy choice
- `alternatives`: plausible alternatives available at the time
- `rationale_reconstruction`: analytical reconstruction, explicitly not a quote
- `outcome`: immediate result
- `long_term_impact`: durable consequences
- `criticism`: major failure mode, controversy, or limitation
- `scores`: analytical scorecard
- `confidence`: 0–1 evidence confidence
- `sources`: source labels

## Scorecard

All component scores are 0–10.

`impact_score = 10 * (0.30*scale + 0.25*durability + 0.20*strategic_leverage + 0.15*counterfactual + 0.10*stakeholder_breadth)`

Additional dimensions:
- `risk`: estimated strategic downside at decision time
- `reversibility`: how easy it was to reverse the decision after commitment; 1 = extremely difficult, 10 = easily reversible

These values are analytical judgments, not historical facts.

## Next data-expansion stage

Before production use, each record should be expanded with exact primary-document references, verified quotations where useful, competing historian interpretations, actor objectives vs. stated objectives, information available at the time vs. hindsight knowledge, stakeholder graphs, counterfactual branches, causal links to later decisions, and claim-level confidence.
