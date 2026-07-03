# Inferred Preference Confirmation

## Problem

The product notices a repeated behavior and wants to convert it into memory. Because the user did not explicitly state the preference, the product needs confirmation before treating the inference as durable truth.

## When to use

Use this pattern when behavior repeats enough to suggest a stable preference, but uncertainty remains. It is useful for formatting preferences, workflow habits, notification preferences, and recurring content choices.

Avoid using it for sensitive, identity-related, health, financial, legal, or employment-related inference unless the product has a strong consent model.

## UI pattern

Present the inference as a question, not a conclusion:

- "It looks like you often choose short summaries. Remember that preference?"
- Include evidence in brief form, such as "Based on your last 4 summaries"
- Provide actions to confirm, reject, or adjust

The pattern should make uncertainty visible.

## User controls

- Yes, remember this
- No, do not remember
- Edit the preference
- Use only in this project
- Stop suggesting this

## Edge cases

- Repetition was caused by temporary circumstances.
- The behavior varies across projects.
- The inference is technically correct but socially awkward.
- Multiple users contributed to the behavior in a shared account.
- The user rejects the inference repeatedly.

## Trust risk

The main risk is false personalization. If the product treats an inference as fact, the user may lose confidence in all memory-driven behavior.

## Example product context

A research assistant sees that a user repeatedly asks for tables when comparing vendors. It asks whether comparison outputs should default to structured tables in that workspace.
