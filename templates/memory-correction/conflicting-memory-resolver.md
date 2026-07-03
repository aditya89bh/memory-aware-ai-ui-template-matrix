# Conflicting Memory Resolver

## Problem

Two or more memories disagree, and the product needs user help to decide which one applies. Silent resolution can produce confusing or inappropriate outcomes.

## When to use

Use this pattern when memory conflict affects an output, workflow, or shared decision. It is especially important across personal, project, and workspace scopes.

## UI pattern

Show conflicting memories side by side:

- Memory statements
- Source and date
- Scope
- Current status
- Recommended resolution if safe
- User action to choose, merge, edit, or forget

The resolver should explain why the conflict matters now.

## User controls

- Choose one memory
- Merge memories
- Edit memory
- Apply one memory only in a scope
- Forget outdated memory
- Decide later

## Edge cases

- Both memories are valid in different contexts.
- A workspace memory overrides personal preference.
- The user lacks permission to change one memory.
- The conflict appears during a high-pressure task.
- More than two memories conflict.

## Trust risk

The main risk is hidden arbitration. If the product chooses a memory without explanation, users may not understand why behavior changed.

## Example product context

A team workspace says reports should be formal, while the user's personal memory prefers informal summaries. Before generating a client report, the product asks which tone applies.
