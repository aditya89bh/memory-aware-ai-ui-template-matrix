# Scenario Map

This scenario map shows how the Phase 2 templates can be combined in practical product work.

## Scenario 1: Personal writing preferences

A writing product notices that a user repeatedly asks for concise summaries.

Relevant templates:

- [Inferred Preference Confirmation](../templates/memory-capture/inferred-preference-confirmation.md)
- [Memory Drawer](../templates/memory-inspection/memory-drawer.md)
- [Temporary Session Override](../templates/memory-editing/temporary-session-override.md)
- [Forget Single Memory](../templates/memory-forgetting/forget-single-memory.md)
- [Confidence and Source Indicator](../templates/provenance-confidence/confidence-and-source-indicator.md)

Design lesson: inferred memory should be confirmed and easy to override temporarily.

## Scenario 2: Shared project constraint

A product team records that a client requires accessibility review before handoff.

Relevant templates:

- [Explicit Memory Save Prompt](../templates/memory-capture/explicit-memory-save-prompt.md)
- [Remember Across Workspace](../templates/memory-scope-permissions/remember-across-workspace.md)
- [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md)
- [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md)

Design lesson: workspace memory needs visible source, scope, and permissions.

## Scenario 3: Wrong personal assumption

A product incorrectly remembers that a user prefers management roles.

Relevant templates:

- [That's Wrong Correction Flow](../templates/memory-correction/thats-wrong-correction-flow.md)
- [Inline Memory Edit](../templates/memory-editing/inline-memory-edit.md)
- [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md)
- [Why Remembered This](../templates/provenance-confidence/why-remembered-this.md)

Design lesson: correction should repair the underlying memory, not only the current output.

## Scenario 4: Sensitive temporary context

A user mentions a health-related scheduling constraint during planning.

Relevant templates:

- [Sensitive Memory Consent Gate](../templates/memory-scope-permissions/sensitive-memory-consent-gate.md)
- [Remember for This Chat Only](../templates/memory-scope-permissions/remember-for-this-chat-only.md)
- [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md)

Design lesson: sensitive memory should default to narrow scope and explicit consent.

## Scenario 5: Stale project memory

A project preference from six months ago continues affecting recommendations.

Relevant templates:

- [Remembered Facts Timeline](../templates/memory-inspection/remembered-facts-timeline.md)
- [Conflicting Memory Resolver](../templates/memory-correction/conflicting-memory-resolver.md)
- [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md)
- [Profile-Level Memory Manager](../templates/memory-editing/profile-level-memory-manager.md)

Design lesson: memory needs aging, review, and conflict handling.

## Phase 3 applied flow map

| Applied flow | Primary memory challenge | Most relevant review tool |
|---|---|---|
| [Productivity Assistant Flow](productivity-assistant-flow.md) | Personal preference control | [Design Review Scorecard](../docs/design-review-scorecard.md) |
| [Team Collaboration Flow](team-collaboration-flow.md) | Shared memory boundaries | [Stakeholder Review Questions](../docs/stakeholder-review-questions.md) |
| [Customer Support Flow](customer-support-flow.md) | Account memory correction | [Memory Risk Rubric](../docs/memory-risk-rubric.md) |
| [Education Tutor Flow](education-tutor-flow.md) | Learning profile accuracy | [Memory Lifecycle Rubric](../docs/memory-lifecycle-rubric.md) |
| [Robotics Operator Flow](robotics-operator-flow.md) | Safety-relevant context | [Memory Risk Rubric](../docs/memory-risk-rubric.md) |
| [Research Assistant Flow](research-assistant-flow.md) | Evidence and uncertainty | [Pattern Combinations](../docs/pattern-combinations.md) |
| [Creative Tool Flow](creative-tool-flow.md) | Temporary creative overrides | [Anti-Patterns](../docs/anti-patterns.md) |
