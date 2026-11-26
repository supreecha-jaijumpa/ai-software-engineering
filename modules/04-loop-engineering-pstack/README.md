# Module 04: Loop Engineering & Pstack

> Status: 🔒 Locked (complete Level 3 first)
> Estimated Time: 4 weeks (Weeks 9–12)
> Level: 4
> Fast Track: None. The failure simulations (Exercise 4.5 and 4.6) are the point of this module — do not skip them.
> Convention note: Pstack (Poteto Stack) is your project-specific workflow concept, not a universal industry standard. Loops, maker-checker, and bounded retries are the general ideas behind it.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Describe a workflow as a loop: goal, action, observation, evaluation, adjustment
- [ ] Separate deterministic checks from model judgment and use each where it fits
- [ ] Define a bounded retry policy, a stop condition, and an escalation path
- [ ] Apply maker-checker so that verification is independent of the implementation
- [ ] Persist state and attempt records so a workflow can recover
- [ ] Build the Pstack pieces: task control, a feature map, and an evidence-based `/verify-feature`

---

## The Core Loop

```text
GOAL
  ↓
ACTION
  ↓
OBSERVATION
  ↓
EVALUATION
  ↓
ADJUSTMENT
  ↺
```

A loop must have: a clear goal · observable outputs · independent verification criteria · a bounded retry policy · a stop condition · escalation to a human when blocked, risky, or uncertain · a record of what was attempted and what happened.

---

## Topics

**Loop Engineering**
- [4.1 The Core Loop — Goal, Action, Observation, Evaluation, Adjustment](4.1-the-core-loop.md)
- [4.2 Feedback Loops & Verification Loops](4.2-feedback-and-verification-loops.md)
- [4.3 Deterministic Checks vs Model Judgment](4.3-deterministic-checks-vs-model-judgment.md)
- [4.4 Bounded Iteration, Retry Policy & Stop Conditions](4.4-bounded-iteration-retry-stop-conditions.md)
- [4.5 Escalation to a Human](4.5-escalation-to-a-human.md)
- [4.6 Maker-Checker Patterns](4.6-maker-checker-patterns.md)
- [4.7 State Persistence, Recovery & Attempt Records](4.7-state-persistence-recovery-attempt-records.md)

**Pstack**
- [4.8 Pstack Overview — Control App, Feature Map, /verify-feature](4.8-pstack-overview.md)
- [4.9 Control App — Tasks, Stages & Task States](4.9-control-app-and-task-states.md)
- [4.10 Feature Map — Scope, Dependencies & Impact](4.10-feature-map.md)
- [4.11 /verify-feature — Evidence-Based Verification](4.11-verify-feature.md)
- [4.12 Failure Classification & Workflow Observability](4.12-failure-classification-and-observability.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 4.1: Build a requirement-to-verification workflow.
- [ ] Exercise 4.2: Define task states such as `draft`, `planned`, `approved`, `implementing`, `verifying`, `blocked`, and `completed` — with the allowed transitions.
- [ ] Exercise 4.3: Create a feature map for an existing feature.
- [ ] Exercise 4.4: Implement `/verify-feature` with evidence-based checks.
- [ ] Exercise 4.5: Simulate a failing test, a missing requirement, and a blocked dependency.
- [ ] Exercise 4.6: Confirm the workflow stops safely rather than guessing or looping indefinitely.

---

## Module Assessment
- Pass when: all exercises done with evidence + the three failure simulations demonstrated to the mentor
- Milestone: You can build a repeatable, bounded workflow that plans, implements, observes, corrects, verifies, and reports with evidence.
- Unlocks: Level 5 (AI-Orchestrated Engineering)
