# Confidence and Source Indicator

## Problem

A product may use memories with different reliability levels, but users often see them as equally authoritative. The interface needs to distinguish confirmed memory from uncertain inference.

## When to use

Use this pattern when memory is visible in decision-making contexts, review surfaces, recommendations, or generated outputs.

## UI pattern

Add a compact indicator to memory items:

- Confidence label such as confirmed, likely, needs review, or stale
- Source type such as user confirmed, inferred from behavior, imported, or workspace source
- Recency label
- Action to review or confirm

Avoid numeric confidence scores unless the audience can interpret them.

## User controls

- Confirm memory
- Review source
- Edit memory
- Mark as stale
- Reject inference
- Change scope

## Edge cases

- Confidence differs by scope.
- A low-confidence memory is still useful as a suggestion.
- The confidence label may create false certainty.
- Source quality changes over time.
- Users may ignore indicators if they are visually subtle.

## Trust risk

The main risk is false authority. If uncertain memory looks definitive, users may blame the product when personalization fails.

## Example product context

A research workspace labels a project assumption as "Needs review" because it came from an older meeting summary and has not been confirmed in three months.
