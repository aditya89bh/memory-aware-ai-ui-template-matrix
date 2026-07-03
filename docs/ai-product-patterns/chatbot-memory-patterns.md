# Chatbot Memory Patterns

## Product context

A conversational product remembers user preferences, recurring tasks, and prior context across chats.

## Memory objects involved

Preferences, recurring facts, conversation summaries, session-only instructions.


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

Medium, high when sensitive personal context appears.

## Example product moment

The chatbot says it remembered a dietary preference and offers "Why remembered?", "Edit", and "Forget" controls.
