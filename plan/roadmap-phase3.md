# Roadmap — Phase 3 (Systems: Levels 5–6 + Capstone)
> Weeks 13–20 | Goal: Coordinate agents safely, then build, evaluate, secure, and improve a complete AI engineering system

---

## Level 5: AI-Orchestrated Engineering (Weeks 13–16)
> Goal: Coordinate specialized agents without introducing unnecessary complexity or unsafe parallel changes

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M05 | Agent roles & responsibility boundaries | 🔒 | — | — |
| M05 | Orchestrator patterns | 🔒 | — | — |
| M05 | Delegation & task decomposition | 🔒 | — | — |
| M05 | Parallel vs sequential execution | 🔒 | — | — |
| M05 | Context isolation & handoff contracts | 🔒 | — | — |
| M05 | Shared state & artifact ownership | 🔒 | — | — |
| M05 | Dependency graphs & execution ordering | 🔒 | — | — |
| M05 | Git worktrees & isolated working directories | 🔒 | — | — |
| M05 | Merge conflicts & integration strategy | 🔒 | — | — |
| M05 | Maker-checker & independent review at scale | 🔒 | — | — |
| M05 | Agent failure, timeout, retry & escalation | 🔒 | — | — |
| M05 | Cost & latency trade-offs of multi-agent systems | 🔒 | — | — |
| M07 | Delegation, model selection & deterministic scripts *(cross-cutting)* | 🔒 | — | — |

**Level 5 Milestone:** Build an orchestrator workflow that delegates bounded tasks with explicit input and output formats. Run parallel read-only architecture, security, and test research; then implement separate frontend and backend tasks in git worktrees after agreeing on a contract. Integrate, verify, and compare quality, elapsed time, token use, and rework against a single-agent run of the same task.

> **Why this comes late:** multi-agent work is the most expensive and hardest-to-debug way to use AI. It only pays off when tasks are genuinely independent or have stable contracts — and you can only judge that once you can build a reliable single-agent loop.

---

## Level 6: AI Engineering Architecture (Weeks 17–20)
> Goal: Build an AI-assisted engineering system that is reliable, secure, observable, measurable, and maintainable for individual or team use

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M06 | Harness engineering — model vs harness | 🔒 | — | — |
| M06 | Harness controls — sandboxing, quality gates & oversight | 🔒 | — | — |
| M06 | Specification-driven development | 🔒 | — | — |
| M06 | Contracts, traceability & change-impact analysis | 🔒 | — | — |
| M06 | Test-driven & verification-driven development | 🔒 | — | — |
| M06 | Test quality & meaningful assertions | 🔒 | — | — |
| M06 | Evaluation engineering — workflow metrics | 🔒 | — | — |
| M06 | Building an evaluation set & comparing workflow versions | 🔒 | — | — |
| M06 | Observability & reliability | 🔒 | — | — |
| M06 | Security — prompt injection, secrets & least privilege | 🔒 | — | — |
| M06 | Governance — approval policies, auditability & team policy | 🔒 | — | — |
| M07 | Cost per successfully verified task *(cross-cutting)* | 🔒 | — | — |

**Level 6 Milestone:** Create a small evaluation set of representative engineering tasks and measure a baseline (quality, time, rework, tokens). Add guardrails and deterministic verification, safely test misleading instructions in untrusted content, define human-approval policies for risky actions, then re-measure and document what improved — and what did not.

---

## Capstone: AI Software Engineering System (end of roadmap)
> Goal: Support a full-stack feature from written requirement to QA handoff

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M08 | The target operating model — 11 stages | 🔒 | — | — |
| M08 | From requirement intake to human plan approval | 🔒 | — | — |
| M08 | From implementation to QA handoff | 🔒 | — | — |
| M08 | Capstone brief — Creator Product Submission | 🔒 | — | — |
| M08 | Capstone acceptance & the definition of mastery | 🔒 | — | — |

**Capstone Milestone:** Deliver the Creator Product Submission feature through your own workflow and pass all ten acceptance criteria in `projects/capstone/README.md` — including the last two: the workflow never claims success without verification, and its cost, time, quality, and human intervention can be evaluated.

> **Final principle:** The engineer owns the outcome. AI is a powerful participant in the engineering process — not a substitute for engineering judgment.
