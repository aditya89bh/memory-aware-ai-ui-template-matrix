# Memory Drawer

## Problem

Users need a fast way to inspect relevant memory without leaving their current task. A full settings page is too distant from the moment where memory matters.

## When to use

Use this pattern in products where memory frequently influences outputs, recommendations, or workflow defaults. It works well as a side panel or expandable drawer attached to the active workspace.

## UI pattern

A drawer opens from the current screen and shows:

- Relevant memories for the current task
- Scope filters
- Source labels
- Last updated timestamps
- Edit and forget controls
- Link to full memory manager

The drawer should prioritize task-relevant memory, not every stored item.

## User controls

- Search memories
- Filter by scope or category
- Edit memory
- Forget memory
- View source
- Open full manager

## Edge cases

- No relevant memory exists.
- Too many memories match the current task.
- The same memory exists in multiple scopes.
- A memory is visible but cannot be edited due to permissions.
- A memory is outdated but still active.

## Trust risk

The main risk is superficial transparency. If the drawer shows memory but does not allow action, users may feel informed but powerless.

## Example product context

A project planning tool shows a memory drawer beside a generated roadmap, listing the project constraints, team preferences, and prior decisions that shaped the roadmap.
