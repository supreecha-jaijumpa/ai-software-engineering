# Module 06: AI Engineering Architecture

> Status: 🔒 Locked (complete Level 5 first)
> Estimated Time: 4 weeks (Weeks 17–20)
> Level: 6
> Fast Track: None. Tech leads rolling AI workflows out to a team should go deeper on 6.7–6.11 — evaluation, security, and governance decide whether a rollout survives.
> Safety note: security exercises run in a throwaway repository or sandbox with no real credentials. Never test injection or destructive commands against real systems.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Explain the harness as the system around the model, and design its controls
- [ ] Drive work from specifications with traceability from requirement to code and tests
- [ ] Use tests and deterministic checks as the basis of verification, and judge test quality
- [ ] Measure a workflow with defined metrics on a representative evaluation set
- [ ] Make a workflow observable and reliable: traces, failure classes, bounded execution
- [ ] Apply security controls and define human-approval and team policies

---

## Suggested Metrics

| Metric | Meaning |
|--------|---------|
| Task Success Rate | Tasks meeting acceptance criteria |
| First-pass Success | Tasks passing verification without rework |
| Rework Rate | Amount of correction required |
| Regression Rate | Regressions introduced |
| Test Pass Rate | Relevant tests passing |
| Token per Successful Task | Token consumption for verified outcomes |
| Human Intervention | Required human corrections or decisions |
| Cycle Time | Time from task start to verified completion |

Use representative tasks and consistent evaluation criteria when comparing workflow changes.

---

## Topics

**Harness Engineering**
- [6.1 Harness Engineering — Model vs Harness](6.1-harness-engineering-model-vs-harness.md)
- [6.2 Harness Controls — Sandboxing, Quality Gates & Oversight](6.2-harness-controls-sandboxing-gates-oversight.md)

**Specification-Driven Development**
- [6.3 Specification-Driven Development](6.3-specification-driven-development.md)
- [6.4 Contracts, Traceability & Change-Impact Analysis](6.4-contracts-traceability-change-impact.md)

**Test-Driven & Verification-Driven Development**
- [6.5 Test-Driven & Verification-Driven Development](6.5-test-driven-and-verification-driven-development.md)
- [6.6 Test Quality & Meaningful Assertions](6.6-test-quality-and-meaningful-assertions.md)

**Evaluation Engineering**
- [6.7 Evaluation Engineering — Workflow Metrics](6.7-evaluation-engineering-workflow-metrics.md)
- [6.8 Building an Evaluation Set & Comparing Workflow Versions](6.8-evaluation-set-and-comparing-versions.md)

**Observability, Security & Governance**
- [6.9 Observability & Reliability](6.9-observability-and-reliability.md)
- [6.10 Security — Prompt Injection, Secrets & Least Privilege](6.10-security-injection-secrets-least-privilege.md)
- [6.11 Governance — Approval Policies, Auditability & Team Policy](6.11-governance-approval-auditability-team-policy.md)

Cross-cutting, scheduled with this level: [7.5 Cost per Successfully Verified Task](../07-token-context-optimization/7.5-cost-per-verified-task.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 6.1: Create a small evaluation set of representative engineering tasks.
- [ ] Exercise 6.2: Measure baseline quality, time, rework, and token usage.
- [ ] Exercise 6.3: Add guardrails and deterministic verification.
- [ ] Exercise 6.4: Test malicious or misleading instructions in untrusted content — safely, in a sandbox.
- [ ] Exercise 6.5: Define human approval policies for risky actions.
- [ ] Exercise 6.6: Compare workflow versions and document improvements.

---

## Module Assessment
- Pass when: all exercises done with evidence + baseline-versus-improved comparison reviewed by mentor
- Milestone: You can design and evaluate an AI engineering workflow using evidence, security controls, operational feedback, and measurable quality criteria.
- Unlocks: Capstone (Module 08)
