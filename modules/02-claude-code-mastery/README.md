# Module 02: Claude Code Mastery

> Status: 🔒 Locked (complete Level 1 first)
> Estimated Time: 3 weeks (Weeks 3–5)
> Level: 2
> Fast Track: If you already write skills and hooks, skim — but do topic 2.14 and defend each choice in the milestone. Knowing the features is not the same as choosing between them.
> Version note: Claude Code changes quickly. Topic files are outlines — confirm file locations, frontmatter fields, hook events, flags, and settings keys in the official docs before relying on them.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Describe Claude Code's operating model: sessions, the agent loop, and what is loaded when
- [ ] Explain how `CLAUDE.md`, rules, skills, commands, agents, hooks, MCP, and plugins differ in purpose, loading behavior, and cost
- [ ] Configure permissions so that risky actions require human approval
- [ ] Use built-in tools, terminal workflows, and Git deliberately
- [ ] Keep long work alive across compaction and resumed sessions
- [ ] Choose the correct mechanism for a use case and justify it

---

## The Distinction

| Component | Primary purpose |
|-----------|-----------------|
| `CLAUDE.md` | Entry-point instructions and essential project context |
| Rules | Constraints and conventions, optionally scoped to paths |
| Skills | Reusable knowledge and procedures, loaded when relevant or invoked |
| Commands | User-facing invocation patterns; understand current Skills-based conventions and legacy support |
| Agents | Specialized agent definitions and responsibilities |
| Subagents | Delegate bounded work, often with separate context |
| Hooks | Deterministic actions triggered by lifecycle events |
| MCP | Connect Claude Code to external tools and data |
| Plugins | Package and distribute capabilities and integrations |
| Permissions | Control which actions and tools may execute |

Do not assume these components are interchangeable just because several can contain Markdown instructions.

---

## Topics

- [2.1 Claude Code Operating Model & Sessions](2.1-operating-model-and-sessions.md)
- [2.2 CLAUDE.md & Instruction Loading](2.2-claude-md-and-instruction-loading.md)
- [2.3 .claude/rules/ & Scoped Rules](2.3-rules-and-scoped-rules.md)
- [2.4 Skills & Progressive Disclosure](2.4-skills-and-progressive-disclosure.md)
- [2.5 Slash Commands — Skills vs Legacy Custom Commands](2.5-slash-commands-skills-vs-legacy-commands.md)
- [2.6 Agents & Subagents](2.6-agents-and-subagents.md)
- [2.7 Hooks — Event-Driven Deterministic Automation](2.7-hooks.md)
- [2.8 MCP Servers & External Tool Integration](2.8-mcp-servers.md)
- [2.9 Plugins & Capability Packaging](2.9-plugins.md)
- [2.10 Permissions, Tool Approvals & Safe Execution](2.10-permissions-and-safe-execution.md)
- [2.11 Built-in Tools, Terminal Workflows & Git Integration](2.11-built-in-tools-terminal-git.md)
- [2.12 Session Continuity, Compaction & Resuming Work](2.12-session-continuity-compaction-resume.md)
- [2.13 Settings — Project vs User Configuration](2.13-settings-project-vs-user.md)
- [2.14 Choosing the Right Mechanism](2.14-choosing-the-right-mechanism.md)

Cross-cutting, scheduled with this level: [7.3 Targeted Exploration & Output Filtering](../07-token-context-optimization/7.3-targeted-exploration-and-output-filtering.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 2.1: Create a minimal project `CLAUDE.md` with only essential instructions.
- [ ] Exercise 2.2: Add one scoped frontend or backend rule.
- [ ] Exercise 2.3: Create three reusable skills — requirement-analysis, implementation-planning, verify-feature.
- [ ] Exercise 2.4: Create two read-only specialist subagents, such as architecture-researcher and code-reviewer.
- [ ] Exercise 2.5: Add one useful hook, such as a safe formatting or validation action.
- [ ] Exercise 2.6: Connect one MCP server — only if it solves a real workflow need. If none does, write down why not.
- [ ] Exercise 2.7: Test permissions and identify which actions require human approval.

---

## Module Assessment
- Pass when: all exercises done with evidence + each artifact defended (why this mechanism, not another)
- Milestone: You can choose the correct Claude Code mechanism for a use case and explain its loading behavior, scope, risks, and maintenance cost.
- Unlocks: Level 3 (AI Workflow Engineering)
