# Customer Support Flow

## Product context

A support workspace helps teams respond to customers with continuity across conversations. Memory can preserve customer preferences and account facts, but incorrect or stale memory can damage trust quickly.

## User goal

A support representative wants relevant customer context available during a conversation while giving customers and support teams clear ways to correct or remove remembered details.

## Memory involved

- Customer preference: email follow-up instead of phone calls
- Account fact: enterprise plan with analytics add-on
- Temporary issue context: current billing dispute
- Sensitive detail: personal contact availability shared for one case

## UI sequence

1. The support thread shows a right-side customer memory drawer.
2. Memory cards include source, account scope, confidence, and last confirmed date.
3. When the representative drafts a reply, the product indicates which customer memories influenced the draft.
4. Sensitive details are hidden by default and require explicit case-level relevance.
5. The representative can mark a memory as verified during the conversation.

## Correction moment

The customer says they no longer want email follow-up. The representative uses inline memory edit to update the preference and receives a correction receipt confirming account-level impact.

## Forgetting moment

After the billing dispute closes, the representative sets the dispute memory to expire. The product confirms that it will remain in case history but not appear as active customer context.

## Trust risk

Wrong customer memory can lead to poor service, privacy mistakes, or repeated frustration. Support memory must be source-linked and easy to correct during live work.

## Success criteria

- Representative can see account memory without leaving the support thread.
- Customer-stated corrections update future support behavior.
- Sensitive case details are scoped narrowly.
- Expired case memory stops appearing as active context.

## Templates used

- [Memory Drawer](../templates/memory-inspection/memory-drawer.md)
- [Inline Memory Edit](../templates/memory-editing/inline-memory-edit.md)
- [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md)
- [Sensitive Memory Consent Gate](../templates/memory-scope-permissions/sensitive-memory-consent-gate.md)
