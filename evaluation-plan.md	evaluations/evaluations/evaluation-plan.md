# Evaluation plan — proposed, not yet executed

**Status:** This is a suggested evaluation approach derived from the five GPTs' stated requirements. No test runs, scores or validated outcomes are supplied by the source PDFs.

## What to test

| Dimension | Example acceptance check |
|---|---|
| Economic grounding | Distinguishes P&L, cash, capital, gross exposure and recoverable value |
| Scope fidelity | Preserves the chosen problem and flags justified changes |
| Decision/process distinction | Does not invent decisions for process-only cases |
| Evidence quality | Labels facts, claims, inferences, hypotheses and unknowns |
| Causal discipline | Does not infer root cause from correlation or a KPI gap |
| Counterfactual quality | Uses a feasible alternative and decision-time information |
| Loss reconciliation | Does not double-count overlapping mechanisms |
| Handoff completeness | Includes the required fields and uncertainty for the next stage |
| Intervention feasibility | Defines actor, action, timing, interface and prerequisites |
| Value validation | Separates execution/adoption from economic outcomes |
| AI appropriateness | Compares AI with simpler non-AI approaches |

## Suggested test scenarios

1. **Process-only failure:** A missed operational step with no meaningful choice; verify the system does not invent a decision.
2. **Poor outcome, good decision:** An adverse outcome caused by unavoidable uncertainty; verify no unsupported Decision Loss is claimed.
3. **Overlapping loss mechanisms:** Two symptoms from the same underlying event; verify totals are reconciled.
4. **Missing data:** A plausible value pool without event-level records; verify 'Not Yet Quantifiable' and an evidence plan.
5. **AI temptation:** A rules or workflow fix could solve the problem; verify non-AI alternatives are compared.
6. **Contradictory downstream evidence:** New evidence changes the original problem definition; verify upstream revision is explicit.

## Recording results

For each scenario record: input, expected behaviour, observed response, pass/fail and severity, evaluator, date, model/configuration, and changes made. Re-test after prompt or workflow changes.

**Do not publish performance claims until tests have been run and documented.**
