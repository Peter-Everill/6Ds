# AI assistant architecture and handoffs

## Design intent

Five specialised Custom GPT instruction specifications divide the work of moving from economic opportunity to an evidence-based improvement case.

```text
Business Model Analyst
  └─ Priority Decision Brief
       ↓
Decision Architect
  └─ Decision Definition Brief
       ↓
Causal Decision Architecture Analyst
  └─ Causal Decision Architecture Brief
       ↓
Decision Performance & Root Cause Analyst
  └─ Loss & Root Cause Summary
       ↓
Decision Improvement Analyst
  └─ Improvement Case
```

## Why specialised stages?

Each stage has a bounded responsibility: **prioritise → define → model/measure → diagnose → improve**. Earlier stages are explicitly constrained from prematurely recommending solutions or claiming causality. Later stages inherit the agreed scope, evidence and uncertainty.

## Handoff contract

Every transition should carry: (1) focal problem and economic objective, (2) decision/process scope and grain, (3) evidence status and sources, (4) relevant constraints and assumptions, (5) required output for the next stage, and (6) unresolved questions or triggers for revisiting earlier analysis.

The uploaded instructions contain more detailed stage-specific handoff fields. The summaries here are curated, not verbatim prompt specifications.

## Handling errors and changes

If new evidence invalidates upstream scope, economics, architecture or attribution, the receiving assistant should flag the issue, propose a revision and identify which earlier output needs updating. It should **not silently redefine** the problem.

## Implementation boundaries

- **Specified:** Custom GPT roles, analytical sequences, output structures, evidence rules, guardrails and handoffs.
- **Not established by these documents:** automatic agent orchestration, integrations or tool calls, production deployment, model selection, security controls, latency/cost measurements, user adoption or empirically validated performance.
- **Possible future extension:** instrumented handoffs, test suites, human review checkpoints and integration into an end-to-end workflow. These are roadmap ideas, not implemented capabilities.

[Return to repository homepage](../README.md).
