---
mutability: controlled
updated: 2026-03-05
version: 1.0
---

# Briefing — cong3 STUDIO

**How to run effective sessions with AI agents. Independent from any work method or project.**

This document defines the interaction protocol between a human and an AI agent. It applies to every session, on every project, with every agent. It does not define what to work on (that's the project's job) or how work gets done (that's the playbook's job). It defines how human and agent collaborate in real time.

---

## 1. Sub-task Decomposition

Every request is broken into the smallest meaningful sub-tasks. The agent never executes a multi-step request in one pass.

- The agent proposes the decomposition before starting.
- Each sub-task is executed, presented, and validated before the next one begins.
- If a sub-task reveals that the decomposition was wrong, stop and reframe — do not continue on a broken plan.

**Why this matters:** Most errors happen when the agent tries to do too much at once. Passive rules (conventions, constraints, naming) get lost when focus is on mechanics. Smaller scope = fewer things to forget.

---

## 2. Sub-task Checkpoint

**Mandatory between every sub-task, before requesting validation to proceed.**

After completing a sub-task, the agent answers these five questions:

1. **Does what I just wrote contain content that already exists elsewhere in the project?**
2. **Does what I just wrote respect every convention that applies to the target file?**
3. **Did I choose a name, label, or structure without consulting the project owner?**
4. **Can I show the exact diff of what changed in this sub-task?**
5. **Has the project owner validated this sub-task before I move on?**

If any answer reveals a problem, fix it before presenting the sub-task for validation. Question 5 is a hard gate — no implicit approval, no assumption of consent.

---

## 3. Session Scope

One session has one clear perimeter. Before starting any work:

- **State the scope** — what will this session accomplish? What is out of scope?
- **Hold the perimeter** — if something out of scope emerges, note it and defer. Do not drift.
- **Close cleanly** — at the end, the session state is saved. Nothing lives only in the agent's memory.

---

*This document is the SSOT for human-agent interaction protocol at cong3 STUDIO. Any question about "how do we collaborate with agents" finds its answer here.*
