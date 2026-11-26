# Module 03: AI Workflow Engineering

> Status: 🔒 Locked (complete Level 2 first)
> Estimated Time: 3 weeks (Weeks 6–8)
> Level: 3
> Fast Track: None — even power users rarely design their context deliberately. Start with the audit exercise; it shows where to spend time.
> Convention note: the `.ai/` layout in this module is a proposed convention, not a Claude Code standard. Adapt it; do not create every file by default.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Design a context architecture with clear boundaries between global, project, feature, task, and runtime context
- [ ] Apply progressive disclosure so that context arrives just in time
- [ ] Recognize and prevent context pollution
- [ ] Keep long work recoverable with task state and handoff notes
- [ ] Design a skill that passes the quality checklist
- [ ] Compose reusable workflows and keep AI instructions owned, versioned, and free of duplication

---

## Skill Quality Checklist

A useful skill defines:

1. Name and clear description / trigger
2. Objective and expected output
3. Required inputs and preconditions
4. Steps in a sensible order
5. Constraints and things not to do
6. References to load only when needed
7. Verification and failure handling
8. Completion report

---

## Topics

- [3.1 Context Architecture & Context Boundaries](3.1-context-architecture-and-boundaries.md)
- [3.2 Context Layers — Global, Project, Feature, Task, Runtime](3.2-context-layers.md)
- [3.3 Progressive Disclosure & Just-in-Time Context Loading](3.3-progressive-disclosure-jit-loading.md)
- [3.4 Context Isolation & Context Pollution](3.4-context-isolation-and-pollution.md)
- [3.5 Context Compaction & Summarization](3.5-compaction-and-summarization.md)
- [3.6 Persistent Task State & Handoff Notes](3.6-persistent-task-state-and-handoff.md)
- [3.7 Knowledge Retrieval & Documentation Discovery](3.7-knowledge-retrieval-and-doc-discovery.md)
- [3.8 Skill Design — the Quality Checklist](3.8-skill-design.md)
- [3.9 Reusable Workflow Composition](3.9-reusable-workflow-composition.md)
- [3.10 Naming, Ownership, Versioning & Deduplication of AI Instructions](3.10-ownership-versioning-deduplication.md)
- [3.11 A Reference Project Structure (.ai/ + .claude/)](3.11-reference-project-structure.md)

Cross-cutting, scheduled with this level: [7.2 Context-Window Utilization & Loading Discipline](../07-token-context-optimization/7.2-context-utilization-and-loading-discipline.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 3.1: Audit the existing AI configuration and identify duplication, oversized context, and unclear ownership.
- [ ] Exercise 3.2: Create a concise `CLAUDE.md` that points to detailed references.
- [ ] Exercise 3.3: Build a feature-specific context package.
- [ ] Exercise 3.4: Design reusable skills for a frontend task, an API contract change, a full-stack feature, and feature verification.
- [ ] Exercise 3.5: Compare a workflow with all context loaded up front against progressive disclosure.
- [ ] Exercise 3.6: Document why each file exists and who or what loads it.

---

## Module Assessment
- Pass when: all exercises done with evidence + the load map from Exercise 3.6 reviewed by mentor
- Milestone: You can design a small, understandable, low-maintenance AI workflow structure that provides the right context at the right time.
- Unlocks: Level 4 (Loop Engineering & Pstack)
