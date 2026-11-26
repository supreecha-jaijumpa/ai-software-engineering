# Roadmap — Phase 2 (Workflows: Levels 3–4)
> Weeks 6–12 | Goal: Design a maintainable AI workflow architecture, then turn one-shot instructions into bounded, evidence-driven loops

---

## Level 3: AI Workflow Engineering (Weeks 6–8)
> Goal: Design a maintainable AI workflow architecture for a real software project

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M03 | Context architecture & context boundaries | 🔒 | — | — |
| M03 | Context layers — global, project, feature, task, runtime | 🔒 | — | — |
| M03 | Progressive disclosure & just-in-time context loading | 🔒 | — | — |
| M03 | Context isolation & context pollution | 🔒 | — | — |
| M03 | Context compaction & summarization | 🔒 | — | — |
| M03 | Persistent task state & handoff notes | 🔒 | — | — |
| M03 | Knowledge retrieval & documentation discovery | 🔒 | — | — |
| M03 | Skill design — the quality checklist | 🔒 | — | — |
| M03 | Reusable workflow composition | 🔒 | — | — |
| M03 | Naming, ownership, versioning & deduplication of AI instructions | 🔒 | — | — |
| M03 | A reference project structure (`.ai/` + `.claude/`) | 🔒 | — | — |
| M07 | Context-window utilization & loading discipline *(cross-cutting)* | 🔒 | — | — |

**Level 3 Milestone:** Audit the AI configuration of your practice repo for duplication, oversized context, and unclear ownership. Redesign it: a concise `CLAUDE.md` that points to detailed references, one feature-specific context package, and skills for a frontend task, an API contract change, a full-stack feature, and feature verification. Document why each file exists and who or what loads it.

> **Why structure before loops?** A loop multiplies whatever context it is given. If the context is bloated, contradictory, or stale, every iteration of a Level 4 loop pays for it and repeats its mistakes.

---

## Level 4: Loop Engineering & Pstack (Weeks 9–12)
> Goal: Turn one-shot AI instructions into bounded, evidence-driven engineering workflows

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M04 | The core loop — goal, action, observation, evaluation, adjustment | 🔒 | — | — |
| M04 | Feedback loops & verification loops | 🔒 | — | — |
| M04 | Deterministic checks vs model judgment | 🔒 | — | — |
| M04 | Bounded iteration, retry policy & stop conditions | 🔒 | — | — |
| M04 | Escalation to a human | 🔒 | — | — |
| M04 | Maker-checker patterns | 🔒 | — | — |
| M04 | State persistence, recovery & attempt records | 🔒 | — | — |
| M04 | Pstack overview — Control App, Feature Map, `/verify-feature` | 🔒 | — | — |
| M04 | Control App — tasks, stages & task states | 🔒 | — | — |
| M04 | Feature Map — scope, dependencies & impact | 🔒 | — | — |
| M04 | `/verify-feature` — evidence-based verification | 🔒 | — | — |
| M04 | Failure classification & workflow observability | 🔒 | — | — |

**Level 4 Milestone:** Build a requirement-to-verification workflow in your practice repo with explicit task states (`draft`, `planned`, `approved`, `implementing`, `verifying`, `blocked`, `completed`), a feature map for an existing feature, and an evidence-based `/verify-feature`. Then simulate a failing test, a missing requirement, and a blocked dependency — and show that the workflow stops safely instead of guessing or looping indefinitely.

> **About Pstack:** Pstack (Poteto Stack) is your project-specific workflow concept — not a universal industry standard. Loop engineering, maker-checker, and bounded retries are the general ideas; Pstack is one concrete way to package them.

**Phase 2 Project:** Run one real feature of your practice repo end-to-end through the Level 4 workflow. Deliver the task record, the feature map, the approved plan, and the verification report with evidence — plus a short note on where the loop stopped or escalated and why.
