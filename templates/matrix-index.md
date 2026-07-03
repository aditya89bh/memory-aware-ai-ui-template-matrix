# Memory-Aware UI Template Matrix Index

This index maps the first usable set of memory design templates by family, user need, and trust function.

## Matrix overview

| Family | User need | Trust function | Templates |
|---|---|---|---|
| Memory capture | Decide what should be remembered | Consent and clarity | [Explicit Memory Save Prompt](memory-capture/explicit-memory-save-prompt.md), [Inferred Preference Confirmation](memory-capture/inferred-preference-confirmation.md), [Contextual Memory Boundary](memory-capture/contextual-memory-boundary.md) |
| Memory inspection | Understand what is remembered | Transparency | [Memory Drawer](memory-inspection/memory-drawer.md), [Remembered Facts Timeline](memory-inspection/remembered-facts-timeline.md), [Source-Linked Memory Card](memory-inspection/source-linked-memory-card.md) |
| Memory editing | Change stored memory | Control and accuracy | [Inline Memory Edit](memory-editing/inline-memory-edit.md), [Profile-Level Memory Manager](memory-editing/profile-level-memory-manager.md), [Temporary Session Override](memory-editing/temporary-session-override.md) |
| Memory correction | Repair wrong memory | Recourse | [That's Wrong Correction Flow](memory-correction/thats-wrong-correction-flow.md), [Conflicting Memory Resolver](memory-correction/conflicting-memory-resolver.md), [Correction Feedback Receipt](memory-correction/correction-feedback-receipt.md) |
| Memory forgetting | Remove or deactivate memory | Reversibility | [Forget Single Memory](memory-forgetting/forget-single-memory.md), [Forget by Category](memory-forgetting/forget-by-category.md), [Memory Expiry Control](memory-forgetting/memory-expiry-control.md) |
| Scope and permissions | Decide where memory applies | Boundary control | [Remember for This Chat Only](memory-scope-permissions/remember-for-this-chat-only.md), [Remember Across Workspace](memory-scope-permissions/remember-across-workspace.md), [Sensitive Memory Consent Gate](memory-scope-permissions/sensitive-memory-consent-gate.md) |
| Provenance and confidence | Understand why memory exists | Explainability | [Why Remembered This](provenance-confidence/why-remembered-this.md), [Confidence and Source Indicator](provenance-confidence/confidence-and-source-indicator.md) |

## How to use the matrix

Start with the user question, not the interface. For example:

- "How does the user know this preference was saved?" Use memory capture and inspection templates.
- "How does the user fix a wrong assumption?" Use correction and editing templates.
- "How does the user limit where memory applies?" Use scope and permission templates.
- "How does the user know whether memory is reliable?" Use provenance and confidence templates.

## Risk-based guidance

- Low-risk memory can use lightweight prompts and inline controls.
- Medium-risk memory should expose source, scope, and edit actions.
- High-risk memory should require explicit consent, conservative reuse, and clear forgetting controls.

## Matrix principle

No single template creates a trustworthy memory experience. A strong product usually combines capture, inspection, correction, forgetting, and provenance patterns into a coherent lifecycle.

## Applied workflow references

Use these examples when selecting template combinations for product work:

- [Productivity Assistant Flow](../examples/productivity-assistant-flow.md) shows personal planning preferences, correction, and forgetting.
- [Team Collaboration Flow](../examples/team-collaboration-flow.md) shows shared memory, permissions, and conflict resolution.
- [Customer Support Flow](../examples/customer-support-flow.md) shows account memory, source visibility, and expiry.
- [Education Tutor Flow](../examples/education-tutor-flow.md) shows learning preferences, skill confidence, and temporary goals.
- [Robotics Operator Flow](../examples/robotics-operator-flow.md) shows site-scoped operational memory and auditability.
- [Research Assistant Flow](../examples/research-assistant-flow.md) shows evidence, assumptions, and confidence.
- [Creative Tool Flow](../examples/creative-tool-flow.md) shows brand memory, project constraints, and temporary overrides.

## Review tools

- [Memory Risk Rubric](../docs/memory-risk-rubric.md)
- [Design Review Scorecard](../docs/design-review-scorecard.md)
- [Memory Lifecycle Rubric](../docs/memory-lifecycle-rubric.md)
- [Product Team Workshop Guide](../docs/product-team-workshop-guide.md)
- [Stakeholder Review Questions](../docs/stakeholder-review-questions.md)
- [Pattern Combinations](../docs/pattern-combinations.md)
- [Anti-Patterns](../docs/anti-patterns.md)

## Selection support

Before choosing a template, use:

- [Template Selection Guide](../docs/template-selection-guide.md) to select patterns by user need, risk level, maturity, and scope.
- [Memory Risk Rubric](../docs/memory-risk-rubric.md) to determine required controls.
- [Pattern Combinations](../docs/pattern-combinations.md) to combine templates into full workflows.
- [Memory Flow Audit Worksheet](../worksheets/memory-flow-audit.md) to map memory moments in a product journey.

## Visual and canvas support

Use these Phase 5 artifacts when teaching or presenting the matrix:

- [Visual Frameworks](../docs/visual-frameworks/README.md)
- [Canvases](../canvases/README.md)
- [AI Product Memory Pattern Guides](../docs/ai-product-patterns/README.md)
- [Figma-Ready Specs](../docs/figma-ready-specs.md)
