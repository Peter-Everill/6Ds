
# 6Ds — A Business-Led Methodology for AI Value Creation and Transformation

**Decisions to Value | Business economics → decisions and processes → avoidable loss → practical improvement**

The 6Ds is a business-led approach to understanding performance, investigating where economic value may be lost, and identifying feasible improvements. It starts with the business problem rather than assuming AI is the answer.

This repository documents the **6Ds methodology** and a related **five-assistant Custom GPT workflow** designed to help apply it. The five assistants are specialised analytical stages, **not the same thing as the six Ds**.

## The 6Ds methodology

| Stage | Guiding question |
|---|---|
| **Drivers** | What creates economic value and drives performance? |
| **Defect** | Where is performance below a relevant, feasible benchmark? |
| **Diagnosis** | What might explain the performance gap? |
| **Drilldown** | Which decisions, process activities and causal mechanisms warrant investigation? |
| **Doable** | What feasible changes could recover value? |
| **Dashboard** | How will execution, outcomes and realised value be measured? |

[Read the methodology overview](methodology/6ds-overview.md). These are **high-level descriptions**, not a claim that the uploaded GPT documents define a one-to-one mapping between each D and each assistant.

## Five specialised AI assistants

| Assistant | Purpose | Main handoff |
|---|---|---|
| [1. Business Model Analyst](ai-assistants/01-business-model-analyst.md) | Understand economic drivers, value pools and candidate decisions | Priority Decision Brief |
| [2. Decision Architect](ai-assistants/02-decision-architect.md) | Define the focal decision or process, feasible alternatives, timing and constraints | Decision Definition Brief |
| [3. Causal Decision Architecture Analyst](ai-assistants/03-causal-decision-architecture-analyst.md) | Map causal pathways and specify measurement requirements | Causal Decision Architecture Brief |
| [4. Decision Performance & Root Cause Analyst](ai-assistants/04-decision-performance-root-cause-analyst.md) | Analyse evidence, estimate avoidable loss and test causal explanations | Loss & Root Cause Summary |
| [5. Decision Improvement Analyst](ai-assistants/05-decision-improvement-analyst.md) | Design feasible interventions, assess net value and plan validation | Improvement Case |

**Workflow:** Business Model Analyst → Decision Architect → Causal Decision Architecture Analyst → Decision Performance & Root Cause Analyst → Decision Improvement Analyst.

Each assistant is designed to preserve the prior stage's scope and qualifications. A handoff specification does **not**, by itself, mean that automated handoffs or orchestration have been implemented.

[Read the architecture and handoff overview](ai-assistants/architecture-and-handoffs.md).

## Product design principles

- **Economic value first:** Identify the business problem and plausible value at stake before considering solutions.
- **Decision vs process:** Distinguish poor choices from failures in work design, coordination or execution; both may contribute to loss.
- **Feasible counterfactuals:** Assess avoidable loss against a credible alternative available under relevant constraints.
- **Evidence discipline:** Separate verified facts, claims, inferences, hypotheses and unknowns; do not invent financial values.
- **No double counting:** Reconcile overlapping losses and benefits before aggregating.
- **Simplest viable intervention:** Compare AI with policy, rules, process and workflow alternatives.
- **Measure outcomes:** Distinguish execution/adoption from economic impact and specify how success will be tested.

## Explore

- [Methodology overview](methodology/6ds-overview.md)
- [Assistant architecture and handoffs](ai-assistants/architecture-and-handoffs.md)
- [Worked-example template](examples/worked-example-template.md)
- [Evaluation plan and test cases](evaluations/evaluation-plan.md)

## Implementation status and boundaries

These documents are a **curated, public-facing description of five Custom GPT instruction specifications**. They describe intended analytical behaviour and output contracts; they are not full system prompts, executable code, proof of integration, or independently verified evaluation results. No private company data or proprietary production systems are included. Worked examples and measured results will be added only when available and suitable for public release.

## About

Part of [Peter Everill's GitHub portfolio](https://github.com/Peter-Everill), focused on AI Value Creation, AI Transformation and AI Product Leadership.
