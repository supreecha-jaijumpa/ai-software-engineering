# Module 05: AI-Orchestrated Engineering

> Status: 🔒 Locked (complete Level 4 first)
> Estimated Time: 4 weeks (Weeks 13–16)
> Level: 5
> Fast Track: None. If you already run multiple agents, start with Exercise 5.7 — measure your current setup against a single-agent baseline before learning more patterns.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Define agent roles with clear responsibility boundaries — and no more roles than the work needs
- [ ] Decompose a task and decide what to delegate, in parallel or in sequence
- [ ] Write handoff contracts with explicit inputs and output formats
- [ ] Assign ownership of shared state and artifacts so agents do not collide
- [ ] Use git worktrees to isolate parallel changes, then integrate and verify them
- [ ] Judge, with numbers, whether a multi-agent workflow was worth its cost

---

## Example Roles

| Role | Responsibility |
|------|----------------|
| Orchestrator | Clarify goal, decompose work, coordinate, integrate |
| Architect / Researcher | Inspect codebase and propose design |
| Backend Engineer | Implement backend changes |
| Frontend Engineer | Implement frontend changes |
| Test Engineer | Design and execute tests |
| Security Reviewer | Review security risks |
| Code Reviewer | Review correctness and maintainability |

These are example responsibilities, not a requirement to create one agent for every role.

## Parallelization Rules

Parallel work is appropriate when tasks are independent or have stable contracts.

| Good candidates | Poor candidates |
|-----------------|-----------------|
| Independent research tasks | Multiple agents editing the same files |
| Security and performance review of the same read-only diff | Frontend implementation before an unstable API contract is defined |
| Frontend and backend work after the API contract is agreed | Concurrent schema and dependent API changes without coordination |
| Separate modules with clear ownership | Parallelizing a task whose steps are inherently sequential |

---

## Topics

- [5.1 Agent Roles & Responsibility Boundaries](5.1-agent-roles-and-responsibility-boundaries.md)
- [5.2 Orchestrator Patterns](5.2-orchestrator-patterns.md)
- [5.3 Delegation & Task Decomposition](5.3-delegation-and-task-decomposition.md)
- [5.4 Parallel vs Sequential Execution](5.4-parallel-vs-sequential-execution.md)
- [5.5 Context Isolation & Handoff Contracts](5.5-context-isolation-and-handoff-contracts.md)
- [5.6 Shared State & Artifact Ownership](5.6-shared-state-and-artifact-ownership.md)
- [5.7 Dependency Graphs & Execution Ordering](5.7-dependency-graphs-and-execution-ordering.md)
- [5.8 Git Worktrees & Isolated Working Directories](5.8-git-worktrees.md)
- [5.9 Merge Conflicts & Integration Strategy](5.9-merge-conflicts-and-integration-strategy.md)
- [5.10 Maker-Checker & Independent Review at Scale](5.10-maker-checker-and-independent-review.md)
- [5.11 Agent Failure, Timeout, Retry & Escalation](5.11-agent-failure-timeout-retry-escalation.md)
- [5.12 Cost & Latency Trade-offs of Multi-Agent Systems](5.12-cost-and-latency-tradeoffs.md)

Cross-cutting, scheduled with this level: [7.4 Delegation, Model Selection & Deterministic Scripts](../07-token-context-optimization/7.4-delegation-model-selection-deterministic-scripts.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 5.1: Create an orchestrator workflow that delegates bounded tasks.
- [ ] Exercise 5.2: Run parallel read-only architecture, security, and test research.
- [ ] Exercise 5.3: Define explicit inputs and output formats for each agent.
- [ ] Exercise 5.4: Implement separate frontend and backend tasks after agreeing on a contract.
- [ ] Exercise 5.5: Explore Git worktrees for isolated changes.
- [ ] Exercise 5.6: Test integration, conflict handling, and final verification.
- [ ] Exercise 5.7: Compare quality, elapsed time, token use, and rework against a single-agent workflow.

---

## Module Assessment
- Pass when: all exercises done with evidence + the comparison table from Exercise 5.7 reviewed by mentor
- Milestone: You can determine when multiple agents add value, define safe boundaries, coordinate work, and integrate results with independent verification.
- Unlocks: Level 6 (AI Engineering Architecture)
