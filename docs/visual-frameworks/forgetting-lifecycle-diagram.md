# Forgetting Lifecycle Diagram

## Purpose

Help teams distinguish deletion, deactivation, expiry, archive, and source removal.

## When to use

Use this when designing forgetting controls or reviewing privacy-sensitive memory behavior.

## Diagram

```text
Active memory
|-- Forget single memory -> Removed from future use
|-- Disable use -> Stored but inactive
|-- Archive -> Historical, not active
|-- Expire -> Automatically inactive after trigger
|-- Delete source -> Source removed, derived memory reviewed
```

## How product teams should apply it

For every forgetting option, write the user-facing explanation and backend consequence. The user should know whether the memory is gone, inactive, archived, or still present in another scope.

## Common mistakes

- Using "delete" when the product only disables use.
- Forgetting derived memories after source deletion.
- Not explaining shared-memory impact.
- Allowing expired memory to keep influencing outputs.
