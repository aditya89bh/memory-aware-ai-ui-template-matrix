# Forget Single Memory

## Problem

A user wants to remove one specific memory without resetting the entire product or deleting unrelated data.

## When to use

Use this pattern for memory cards, drawers, managers, timelines, and correction flows where a single memory is visible and actionable.

## UI pattern

Provide a direct "Forget" action on the memory item. The confirmation should explain:

- The memory being forgotten
- Where it currently applies
- Whether source content remains
- Whether the action can be undone
- What future behavior changes

For low-risk memory, inline confirmation may be enough. For high-risk or shared memory, use stronger confirmation.

## User controls

- Forget memory
- Cancel
- Undo when safe
- Delete source too when appropriate
- Stop using without deleting source
- View related memories

## Edge cases

- The same fact exists in multiple memories.
- The source content may recreate the memory later.
- The memory belongs to a shared workspace.
- The user wants to forget all similar memories.
- The memory is required for compliance or audit history.

## Trust risk

The main risk is incomplete forgetting. If the product appears to forget something but continues using related memory, the user may feel deceived.

## Example product context

A user opens a memory card that says "Prefers weekend work sessions" and selects "Forget this" because the preference is no longer true.
