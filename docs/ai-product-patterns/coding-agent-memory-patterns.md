# Coding Agent Memory Patterns

## Product context

A coding assistant remembers repository conventions, review preferences, and task-specific constraints.

## Memory objects involved

Code style preferences, repository decisions, project constraints, test commands.


## User controls

- Inspect remembered context
- Edit or correct memory
- Forget single memory
- Change scope where applicable
- View source or confidence when memory affects output

## Recommended templates from the matrix

- [Memory Drawer](../../templates/memory-inspection/memory-drawer.md)
- [That's Wrong Correction Flow](../../templates/memory-correction/thats-wrong-correction-flow.md)
- [Forget Single Memory](../../templates/memory-forgetting/forget-single-memory.md)
- [Why Remembered This](../../templates/provenance-confidence/why-remembered-this.md)

## Anti-patterns

- Treating inferred memory as confirmed fact
- Hiding memory use behind vague personalization language
- Providing correction feedback without changing future behavior
- Making forgetting all-or-nothing

## Risk level

Medium, high when memory affects production changes or security-sensitive work.

## Example product moment

The assistant shows remembered repo conventions before proposing a refactor and allows the user to correct stale guidance.
