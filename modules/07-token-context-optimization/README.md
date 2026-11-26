# Module 07: Token & Context Optimization

> Status: 🔒 Locked (first topic unlocks with Level 1)
> Estimated Time: 5 sessions, spread across Weeks 1–20
> Level: Cross-cutting — one topic alongside each of Levels 1, 2, 3, 5, and 6
> Fast Track: None. Study this throughout the roadmap, not only at the end.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Explain where tokens go in a session: input, output, cached input, tool results
- [ ] Keep the context window focused through loading discipline and compaction
- [ ] Explore a codebase and handle command output without flooding the context
- [ ] Decide when delegation, a different model, or a deterministic script is the cheaper route
- [ ] Optimize cost per successfully verified task — not token count in isolation

---

## The Ten Practices

1. Load only the context relevant to the current task.
2. Keep the root instruction file concise.
3. Use references and skills for detailed knowledge that is needed selectively.
4. Search for relevant files before reading broad areas of the repository.
5. Filter logs and command output before asking the model to analyze them.
6. Use scripts for deterministic work such as formatting, searching, and test execution.
7. Delegate only when the task benefits from independent context or parallel work.
8. Avoid having multiple agents repeat the same exploration.
9. Preserve concise state summaries for long-running work.
10. Measure cost alongside correctness and rework.

> Optimize **cost per successfully verified task**, not token count in isolation. Reducing context too aggressively can increase mistakes and rework.

---

## Topics

| Topic | Scheduled with |
|-------|----------------|
| [7.1 Token Economics — Input, Output & Cached Tokens](7.1-token-economics.md) | Level 1 |
| [7.2 Context-Window Utilization & Loading Discipline](7.2-context-utilization-and-loading-discipline.md) | Level 3 |
| [7.3 Targeted Exploration & Output Filtering](7.3-targeted-exploration-and-output-filtering.md) | Level 2 |
| [7.4 Delegation, Model Selection & Deterministic Scripts](7.4-delegation-model-selection-deterministic-scripts.md) | Level 5 |
| [7.5 Cost per Successfully Verified Task](7.5-cost-per-verified-task.md) | Level 6 |

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 7.1: Inspect the context usage of a real session and list what is permanent, what is growing, and what is wasted.
- [ ] Exercise 7.2: Cut your always-loaded instructions and show that a representative task still succeeds.
- [ ] Exercise 7.3: Do the same investigation twice — broad reading versus search-first with filtered output — and compare tokens and accuracy.
- [ ] Exercise 7.4: Replace one repeated model-driven chore with a deterministic script, and decide for one task whether a subagent pays for itself.
- [ ] Exercise 7.5: Compute cost per successfully verified task for two workflow versions on your evaluation set.

---

## Module Assessment
- Pass when: all five exercises done with measurements, not estimates
- Milestone: You can explain where a session's tokens went, and make a cost decision that is justified by verified outcomes rather than by token count alone.
- Unlocks: nothing by itself — each topic supports the level it is scheduled with
