# Memory Design Anti-Patterns

Anti-patterns are memory behaviors that commonly weaken trust, control, or clarity.

## Silent save

The product stores durable memory without telling the user.

Why it fails: users may feel watched, especially when the memory appears later in another context.

Better pattern: use [Explicit Memory Save Prompt](../templates/memory-capture/explicit-memory-save-prompt.md) or clear lightweight notice for low-risk memory.

## Vague personalization label

The interface says an output is "personalized" without showing which memory influenced it.

Why it fails: users cannot diagnose wrong outputs.

Better pattern: use [Memory Drawer](../templates/memory-inspection/memory-drawer.md) or [Why Remembered This](../templates/provenance-confidence/why-remembered-this.md).

## All-or-nothing delete

The only memory control is deleting all account data or disabling memory entirely.

Why it fails: users often need targeted forgetting.

Better pattern: use [Forget Single Memory](../templates/memory-forgetting/forget-single-memory.md) and [Forget by Category](../templates/memory-forgetting/forget-by-category.md).

## Inference as fact

The product treats inferred behavior as confirmed preference.

Why it fails: temporary behavior becomes durable personalization.

Better pattern: use [Inferred Preference Confirmation](../templates/memory-capture/inferred-preference-confirmation.md) and confidence indicators.

## Scope leak

Memory from one chat, project, or workspace affects another without clear notice.

Why it fails: users lose confidence in boundaries and may expose sensitive context.

Better pattern: use [Contextual Memory Boundary](../templates/memory-capture/contextual-memory-boundary.md).

## Correction without receipt

The user corrects memory but receives no clear explanation of what changed.

Why it fails: users cannot tell whether future behavior will improve.

Better pattern: use [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md).

## Permanent temporary context

A short-term detail remains active indefinitely.

Why it fails: stale memory keeps shaping future work.

Better pattern: use [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md).
