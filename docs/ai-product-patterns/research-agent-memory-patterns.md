# Research Agent Memory Patterns

## Product context

A research assistant tracks assumptions, evidence, participant context, and synthesis preferences.

## Memory objects involved

Project assumptions, hypotheses, source summaries, analysis preferences.


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

High when memory affects findings or participant-sensitive context.

## Example product moment

The agent labels a remembered hypothesis as "needs review" before using it in synthesis.
