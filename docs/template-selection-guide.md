# Template Selection Guide

This guide helps teams choose the right memory design templates for a product flow.

Start with the user's trust problem, not the screen type. A settings page, drawer, card, or prompt is only useful when it answers a clear memory question.

## Selection process

1. Identify the memory object.
2. Identify who is affected by it.
3. Classify its source, scope, and risk.
4. Choose templates for capture, inspection, correction, and forgetting.
5. Review the full lifecycle before implementation.

Use this guide with the [Template Matrix Index](../templates/matrix-index.md) and [Memory Risk Rubric](memory-risk-rubric.md).

## Select by user need

| User need | Recommended starting templates |
|---|---|
| "I want to approve what gets remembered." | [Explicit Memory Save Prompt](../templates/memory-capture/explicit-memory-save-prompt.md), [Inferred Preference Confirmation](../templates/memory-capture/inferred-preference-confirmation.md) |
| "I want to see what shaped this output." | [Memory Drawer](../templates/memory-inspection/memory-drawer.md), [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md) |
| "I want to fix something wrong." | [That's Wrong Correction Flow](../templates/memory-correction/thats-wrong-correction-flow.md), [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md) |
| "I want this to apply only here." | [Contextual Memory Boundary](../templates/memory-capture/contextual-memory-boundary.md), [Remember for This Chat Only](../templates/memory-scope-permissions/remember-for-this-chat-only.md) |
| "I want the product to forget this." | [Forget Single Memory](../templates/memory-forgetting/forget-single-memory.md), [Forget by Category](../templates/memory-forgetting/forget-by-category.md) |
| "I want to know why this exists." | [Why Remembered This](../templates/provenance-confidence/why-remembered-this.md), [Confidence and Source Indicator](../templates/provenance-confidence/confidence-and-source-indicator.md) |

## Select by risk level

### Low risk

Use lightweight capture, inline editing, and single-memory forgetting. Avoid heavy approval flows unless the user is already in settings or review mode.

### Medium risk

Add source, scope, and correction receipts. Memory should be visible near outputs it affects.

### High risk

Require explicit consent, narrow scope, clear source, and easy forgetting. Prefer confirmation over inference.

### Critical risk

Use human review, ownership, auditability, expiry, and conservative reuse. Do not let memory silently automate consequential decisions.

## Select by product maturity

### Prototype

Start with memory capture prompts, a simple inspection surface, and manual correction notes. Validate language before building complex settings.

### Beta

Add source-linked cards, editing, single-memory forgetting, and a review checklist. Test whether users understand scope.

### Production

Add lifecycle states, stale memory review, category deletion, permissioning, and feedback receipts.

### Enterprise or regulated environment

Add workspace ownership, audit trails, retention constraints, permission reviews, and documented risk classification.
