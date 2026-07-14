# Development Planning

This directory organizes the novel as a product backlog without turning the creative process into busywork.

## Priority system

- **P0:** Blocks drafting or protects core canon. Do first.
- **P1:** Required for a strong outline or reliable draft.
- **P2:** Required before revision or publication, but does not block early design.
- **P3:** Optional enhancement or future-facing work.

## Status system

- `TODO`: ready or waiting on dependencies
- `IN PROGRESS`: actively being developed
- `BLOCKED`: cannot proceed until a named decision or task is complete
- `DONE`: accepted and reflected in canonical files

## Working order

1. Foundation and novel bible
2. World and internal science
3. Story design
4. First draft
5. Cooling period and revision
6. Reader and professional feedback
7. Publication preparation

The phase epics live in `planning/epics/`. `BACKLOG.md` mirrors the operational task list, `MILESTONES.md` defines completion gates, and `GITHUB_ISSUES.md` maps active tasks to their discussion threads.

Use GitHub Issues for comments, decisions, and status. A comment does not authorize implementation. Add the `codex-ready` label when the issue is ready for Codex to act. After implementation, the repository bible and outline become the durable source of truth.

Author questions and Codex work must not be mixed. Use `owner: user` for decisions that genuinely require creative input. Use `owner: codex` for research, planning artifacts, and implementation. A blocked Codex issue may carry `codex-ready`, but work still waits for its documented dependencies.
