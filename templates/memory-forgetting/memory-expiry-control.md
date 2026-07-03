# Memory Expiry Control

## Problem

Some memories are useful for a limited time. Without expiry, old context can continue shaping future behavior long after it stops being relevant.

## When to use

Use this pattern for temporary projects, seasonal preferences, trial workflows, event planning, travel context, short-term goals, and time-bound customer needs.

## UI pattern

Add expiry controls to memory creation or editing:

- No expiry
- End of session
- End of project
- Specific date
- Review after a time period
- Expire when source is archived

Expired memory should have a clear inactive state and restoration path when appropriate.

## User controls

- Set expiry
- Change expiry
- Review expiring memories
- Restore expired memory
- Archive expired memory
- Delete expired memory

## Edge cases

- The expiry date arrives during an active workflow.
- Project end dates change.
- Expired memory is still referenced by older outputs.
- A user wants a reminder before expiry.
- Shared memory expiry affects multiple people.

## Trust risk

The main risk is stale personalization. A product that remembers temporary context forever may feel careless or invasive.

## Example product context

A travel planning product remembers dietary constraints only for a specific trip and automatically expires them after the trip ends.
