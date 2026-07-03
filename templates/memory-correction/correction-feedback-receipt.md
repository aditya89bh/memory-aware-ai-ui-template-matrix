# Correction Feedback Receipt

## Problem

After correcting memory, users need confirmation that the correction was understood and will affect future behavior. A generic success toast is not enough for consequential memory repair.

## When to use

Use this pattern after any correction that changes stored memory, deletes incorrect memory, updates scope, or resolves a conflict.

## UI pattern

Show a receipt that summarizes:

- What was changed
- Previous memory
- New memory or action taken
- Scope affected
- Future behavior impact
- Undo or review option

The receipt can be a modal, inline confirmation, or activity log entry depending on risk.

## User controls

- Review updated memory
- Undo correction
- Edit further
- View affected scope
- Close receipt
- Report if issue persists

## Edge cases

- The correction updates several related memories.
- Some changes require approval in a shared workspace.
- Undo is not available after source deletion.
- The correction affects future outputs but not the current generated result.
- The system could not determine which memory was wrong.

## Trust risk

The main risk is uncertainty after repair. If users cannot tell what changed, they may assume correction did not work.

## Example product context

A customer support workspace confirms: "Updated customer preference from phone follow-up to email follow-up. This applies to the Acme account only."
