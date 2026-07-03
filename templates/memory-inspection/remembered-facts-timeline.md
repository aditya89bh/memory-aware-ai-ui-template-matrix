# Remembered Facts Timeline

## Problem

Users need to understand how memory changed over time, especially when older information may conflict with newer behavior or decisions.

## When to use

Use this pattern for products where chronology matters: project history, customer support, research workflows, long-running planning, or evolving user preferences.

## UI pattern

Show memories as a timeline with:

- Creation date
- Source event
- Edits and corrections
- Scope changes
- Expiration or archive events
- Current status

The timeline should distinguish facts, preferences, corrections, and system summaries.

## User controls

- Filter timeline by category
- View source event
- Restore previous version
- Mark stale
- Archive old memory
- Correct current memory

## Edge cases

- The source event is no longer available.
- A memory was generated from multiple sources.
- A correction changes the meaning of earlier timeline entries.
- Team members disagree about whether a memory is still valid.
- Sensitive items should appear with limited detail.

## Trust risk

The main risk is historical opacity. Without a timeline, users may not know why a product keeps acting on old assumptions.

## Example product context

A customer success product shows how a customer's implementation preference evolved from "pilot only" to "roll out to the analytics team next quarter."
