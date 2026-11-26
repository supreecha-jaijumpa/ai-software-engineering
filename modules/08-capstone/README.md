# Module 08: Capstone — AI Software Engineering System

> Status: 🔒 Locked (complete Level 6 first)
> Estimated Time: end of the roadmap — take the time it needs
> Level: Capstone
> Fast Track: None. This is where the previous six levels are assembled into one working system.
> Working checklist: [projects/capstone/README.md](../../projects/capstone/README.md)

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Run the full target operating model — eleven stages from requirement intake to QA handoff
- [ ] Take a full-stack feature from a written requirement to verified, reviewed delivery through your own workflow
- [ ] Show evidence for every claim the workflow makes
- [ ] Evaluate the workflow's cost, time, quality, and human intervention
- [ ] Explain the trade-offs of your system and teach it to another engineer

---

## Target Operating Model

```text
 1. REQUIREMENT INTAKE       business goal · clarify ambiguity · scope and acceptance criteria
 2. CODEBASE EXPLORATION     architecture and conventions · related features and tests · dependencies and risks
 3. FEATURE MAPPING          affected modules · dependencies and data flow · impact and unknowns
 4. TECHNICAL SPECIFICATION  design and contracts · schema and API changes · test strategy
 5. HUMAN PLAN APPROVAL      review scope, risks, trade-offs · approve or revise
 6. IMPLEMENTATION           small, scoped changes · existing conventions · traceable to requirements
 7. VERIFICATION             relevant tests · type check, lint, build · acceptance criteria · inspect the diff
 8. REVIEW                   correctness and edge cases · security and performance · maintainability and regressions
 9. CORRECTION LOOP          diagnose with evidence · bounded corrections · re-verify · escalate if blocked or unsafe
10. HUMAN FINAL REVIEW       confirm behavior and scope · approve final changes
11. QA HANDOFF               summary · test evidence · limitations and known issues · documentation
```

AI may perform many steps, but the human engineer remains accountable for requirements, architecture, risk acceptance, and final delivery.

---

## Topics

- [8.1 The Target Operating Model — 11 Stages](8.1-target-operating-model.md)
- [8.2 From Requirement Intake to Human Plan Approval](8.2-intake-to-plan-approval.md)
- [8.3 From Implementation to QA Handoff](8.3-implementation-to-qa-handoff.md)
- [8.4 Capstone Brief — Creator Product Submission](8.4-capstone-brief-creator-product-submission.md)
- [8.5 Capstone Acceptance & the Definition of Mastery](8.5-capstone-acceptance-and-definition-of-mastery.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 8.1: Map each of the eleven stages to the artifact it produces and the mechanism you built for it in Levels 2–6. Mark the gaps.
- [ ] Exercise 8.2: Run stages 1–5 for the capstone scenario and obtain plan approval.
- [ ] Exercise 8.3: Run stages 6–11, including at least one real correction loop, and produce the QA handoff.
- [ ] Exercise 8.4: Evaluate the run — cost, time, quality, human intervention — and name the three changes you would make next.
- [ ] Exercise 8.5: Teach the system to another engineer (or to the mentor acting as one) in fifteen minutes.

---

## Module Assessment
- Pass when: all ten acceptance criteria in `projects/capstone/README.md` are met with evidence
- Milestone: An AI Software Engineering System that supports a full-stack feature from written requirement to QA handoff — and never claims success without verification.
- Unlocks: Roadmap complete. Next: apply the system to real project work and keep improving it from observed failures.
