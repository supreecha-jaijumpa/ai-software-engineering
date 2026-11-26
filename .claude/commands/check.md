# Check

Review and score what the student just submitted.

## Usage

```
/check
```

Paste or type the answer above this command, then run `/check`.

## Behavior

1. Read the student's answer from the conversation above
2. Evaluate against the exercise criteria — and against the evidence provided (command output, diff, test result)
3. Respond with:
   - **Score** — e.g. 7/10
   - **What's good** — 1–2 specific strengths (not empty praise)
   - **What to fix** — 1–3 concrete, actionable improvements
   - **Verdict** — Pass / Needs Revision
4. If Pass: offer to run `/next` to advance the topic
5. If Needs Revision: point to the most important fix and ask the student to revise

## Scoring Guide

| Score | Meaning |
|-------|---------|
| 9–10 | Excellent — correct, verified with evidence, trade-offs explained |
| 7–8 | Good — correct core, minor gaps |
| 5–6 | Partial — missing key parts or unverified, fixable |
| < 5 | Needs rework — misunderstood the concept |

## Notes

- Honest feedback only — no empty praise
- Be specific: "your skill description never says when to trigger, so it will not load on its own" beats "good job"
- A claim without evidence caps the score at 6 — ask for the output, diff, or test run
- If the answer relies on a Claude Code behavior you have not verified, say so and check the official docs before scoring it
- Always end with one clear next step
