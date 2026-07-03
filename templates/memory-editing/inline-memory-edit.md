# Inline Memory Edit

## Problem

A user notices a remembered detail is almost right but needs a small change. Sending them to a separate settings area creates friction and may prevent correction.

## When to use

Use this pattern when memory appears in context and can be safely edited without a complex review process. It works well for preferences, labels, project facts, and short constraints.

## UI pattern

Display the memory statement with an inline edit affordance:

- Current memory text
- Edit icon or link
- Lightweight text field
- Scope indicator
- Save and cancel actions
- Optional preview of effect

The editing surface should preserve context so users know what they are changing.

## User controls

- Edit text
- Save change
- Cancel change
- Change scope
- View source
- Forget instead

## Edge cases

- The memory is generated from multiple underlying records.
- The user edits wording in a way that changes meaning significantly.
- Another user edits the same workspace memory simultaneously.
- The user lacks permission to edit shared memory.
- The memory has downstream dependent memories.

## Trust risk

The main risk is unclear consequence. If users edit a visible statement but product behavior does not change, control feels fake.

## Example product context

A scheduling product shows "Prefers morning meetings" in a planning sidebar. The user edits it inline to "Prefers morning meetings on Tuesdays and Thursdays."
