# Temporary Session Override

## Problem

A user wants the product to ignore or modify a durable memory for the current task without permanently changing the saved preference.

## When to use

Use this pattern when users often need exceptions. It is useful for writing style, planning constraints, recommendation filters, project modes, and temporary collaboration needs.

## UI pattern

Offer a temporary override control near the active memory influence:

- Current memory being applied
- Override field or toggle
- Duration label such as "this chat" or "this task"
- Option to make the override permanent
- Clear override action

The interface should distinguish temporary behavior from saved memory.

## User controls

- Override for this session
- Clear override
- Make permanent
- View saved memory
- Disable memory for this task

## Edge cases

- The user forgets an override is active.
- Several memories are overridden at once.
- The override conflicts with workspace policy.
- A temporary override is mistaken for correction.
- The session becomes a project artifact and the override should expire.

## Trust risk

The main risk is persistence confusion. If users cannot tell whether a change is temporary or durable, they may stop trusting memory controls.

## Example product context

A writing assistant normally uses concise style, but the user selects "Use detailed explanations for this draft only" without changing the saved writing preference.
