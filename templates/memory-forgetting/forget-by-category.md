# Forget by Category

## Problem

A user wants to remove or disable a whole class of memories rather than manage items one by one.

## When to use

Use this pattern when memories are organized into meaningful categories such as writing style, scheduling preferences, project history, location hints, customer context, or recommendation history.

## UI pattern

Show categories with counts, examples, and consequences:

- Category name
- Description
- Number of memories
- Example items
- Scope selector
- Forget, archive, or disable controls

The user should understand what belongs to the category before acting.

## User controls

- Select category
- Preview included memories
- Forget category
- Disable future capture for category
- Archive instead of delete
- Export before deletion where appropriate

## Edge cases

- Categories overlap.
- Some memories in the category are shared or locked.
- The category contains sensitive items.
- Deleting the category may degrade product quality.
- Future behavior may recreate the category unless capture is disabled.

## Trust risk

The main risk is over-deletion or under-deletion. Users need confidence that the category boundary matches their intent.

## Example product context

A user decides that a planning app should forget all location-based routine memories while keeping writing and project preferences.
