# Exercise

Give a practical exercise for the current topic matched to the student's level.

## Usage

```
/exercise
```

## Behavior

1. Get current topic from `CURRENT.md` and level/language/practice repo from `me.md` — skip the reads if they're already in context this session
2. Check the module README's exercise list for the roadmap exercise that matches the topic
3. Generate one focused exercise appropriate for the topic and level
4. State clearly: what to do, what to submit, what evidence to bring, and what "good" looks like
5. Wait for the student's answer — do not give hints unprompted; when asked, hint progressively instead of giving the full solution
6. After submission, use `/check` to review

## Exercise Format

```
**Exercise: <title>**

<Scenario or prompt — 2–4 sentences>

**Your task:**
1. <Step or deliverable>
2. <Step or deliverable>

**Submit:** <the artifact + the evidence that it works>
```

## Notes

- One exercise per topic — not a list of drills
- Prefer real artifacts in the practice repo: a CLAUDE.md, a rule, a skill, a hook, a loop definition, an eval table, or a written decision
- Many good exercises are comparisons: run the same task two ways and compare correctness, rework, and cost
- Keep it safe: exercises about permissions, hooks, or prompt injection run in a throwaway branch or sandbox repo, never against real credentials or production systems
- Adjust complexity to level: level 3 = guided steps, level 7 = open-ended design
