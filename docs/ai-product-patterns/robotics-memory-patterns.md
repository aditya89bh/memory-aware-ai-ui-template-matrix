# Robotics Memory Patterns

## Product context

A robotics operations product remembers site constraints, operator preferences, and incident context.

## Memory objects involved

Site rules, route constraints, operator display preferences, safety review dates.


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

Critical when memory affects safety or operations.

## Example product moment

A route-planning interface shows a source-linked site constraint with review date before applying it.
