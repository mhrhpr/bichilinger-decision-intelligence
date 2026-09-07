# Historical Decision Intelligence Dataset

## Purpose
This dataset is the historical evidence layer for Bichilinger Decision Intelligence. It reconstructs documented strategic decisions by Otto von Bismarck, Winston S. Churchill and Henry A. Kissinger.

## Current coverage
- 3 historical profiles
- 45 decision records
- 15 decisions per actor
- Life arcs, decision lenses and failure modes
- Context, decision, plausible alternatives, reconstructed rationale, outcome and criticism
- Five impact dimensions plus composite impact score
- Risk, reversibility and evidence confidence

## Important epistemic rule
`rationale_reconstruction` is analytical reconstruction, not a quotation or claim about private thoughts. The system must never turn a reconstruction into a fabricated historical quote.

## Impact model
Composite impact score is 0-100:

`10 * (0.30*scale + 0.25*durability + 0.20*strategic_leverage + 0.15*counterfactual + 0.10*stakeholder_breadth)`

Dimensions are analytical judgments, not objective historical facts.

## Confidence
Confidence is currently categorical (`High`, `Very High`) at record level. Production version should evolve toward claim-level confidence with separate evidence objects.

## Next expansion
1. Add primary-document IDs and URLs.
2. Add exact quotations only when verified against primary sources.
3. Separate information available at decision time from hindsight information.
4. Add competing historian interpretations.
5. Add stakeholder/network graphs.
6. Add counterfactual branches.
7. Add causal links between decisions.
8. Add failure/near-miss decisions, not only famous successes.
9. Add negative examples where the actor's preferred lens produced poor outcomes.
10. Convert CSV records into normalized JSON/SQLite/vector-search documents for retrieval.
