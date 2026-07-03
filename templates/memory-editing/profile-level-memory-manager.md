# Profile-Level Memory Manager

## Problem

Users need one reliable place to review and maintain durable personal memory across the product. Inline controls are useful, but they do not replace a central management surface.

## When to use

Use this pattern when the product stores multiple long-term personal memories across categories such as preferences, constraints, writing style, recurring tasks, or saved facts.

## UI pattern

Create a memory manager within profile or settings:

- Category navigation
- Search
- Memory cards
- Scope and source labels
- Edit, archive, and forget actions
- Review stale memory section
- Export option where appropriate

The manager should feel like a control center, not a technical log.

## User controls

- Search memory
- Edit memory
- Forget memory
- Archive memory
- Filter by category
- Review stale items
- Export readable summary

## Edge cases

- A memory appears in both personal and workspace views.
- Deleting one memory may not delete source content.
- Some memories are locked by organization policy.
- The user expects account deletion controls here.
- Large memory sets require grouping and prioritization.

## Trust risk

The main risk is manageability failure. If the manager becomes a long, unexplained list, users may feel memory is out of control.

## Example product context

A productivity app offers a profile memory manager where users can review communication preferences, planning defaults, and recurring work constraints.
