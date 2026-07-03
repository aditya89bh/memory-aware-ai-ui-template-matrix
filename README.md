# Memory-Aware AI UI Template Matrix

A design reference for creating inspectable, editable, correctable, and forgettable memory experiences in AI products.

## Why this repository exists

AI memory is becoming a core part of product experience. Applications increasingly remember user preferences, ongoing projects, prior conversations, behavioral patterns, and context gathered across sessions. Yet most memory experiences are still treated as backend features: hidden, automatic, difficult to inspect, and hard to correct.

This repository takes a different position: **memory is a first-class design material**.

Memory should be visible when it matters, controllable when it affects outcomes, and reversible when it is wrong. People should be able to understand what a system remembers, why it matters, how it is used, and how to change or remove it. Product teams need reusable design patterns for that work.

## What this repository provides

This is a **template matrix**, not a frontend component library. It focuses on product patterns, interaction models, decision points, and documentation that help teams design trustworthy memory experiences before choosing an implementation stack.

## Start here

- [Vision](docs/vision.md)
- [Taxonomy](docs/taxonomy.md)
- [Memory Design Principles](docs/memory-design-principles.md)
- [Template Schema](templates/template-schema.md)
- [Template Matrix Index](templates/matrix-index.md)
- [Review Checklist](docs/review-checklist.md)
- [Scenario Map](examples/scenario-map.md)

## Visual matrix

| Memory design job | Template family | Primary trust question |
|---|---|---|
| Decide what gets remembered | [Memory Capture](templates/memory-capture/README.md) | Did the user understand and approve memory creation? |
| See what is remembered | [Memory Inspection](templates/memory-inspection/README.md) | Can the user inspect relevant memory at the right moment? |
| Change stored memory | [Memory Editing](templates/memory-editing/README.md) | Can the user maintain memory without friction? |
| Fix wrong memory | [Memory Correction](templates/memory-correction/README.md) | Can the user repair mistakes and see what changed? |
| Remove memory | [Memory Forgetting](templates/memory-forgetting/README.md) | Can the user reverse memory with clear consequences? |
| Control where memory applies | [Scope and Permissions](templates/memory-scope-permissions/README.md) | Are boundaries between chat, personal, project, and workspace memory clear? |
| Understand memory origin | [Provenance and Confidence](templates/provenance-confidence/README.md) | Can the user judge where memory came from and how reliable it is? |

## Template families

- [Memory Capture](templates/memory-capture/README.md)
  - [Explicit Memory Save Prompt](templates/memory-capture/explicit-memory-save-prompt.md)
  - [Inferred Preference Confirmation](templates/memory-capture/inferred-preference-confirmation.md)
  - [Contextual Memory Boundary](templates/memory-capture/contextual-memory-boundary.md)
- [Memory Inspection](templates/memory-inspection/README.md)
  - [Memory Drawer](templates/memory-inspection/memory-drawer.md)
  - [Remembered Facts Timeline](templates/memory-inspection/remembered-facts-timeline.md)
  - [Source-Linked Memory Card](templates/memory-inspection/source-linked-memory-card.md)
- [Memory Editing](templates/memory-editing/README.md)
  - [Inline Memory Edit](templates/memory-editing/inline-memory-edit.md)
  - [Profile-Level Memory Manager](templates/memory-editing/profile-level-memory-manager.md)
  - [Temporary Session Override](templates/memory-editing/temporary-session-override.md)
- [Memory Correction](templates/memory-correction/README.md)
  - [That's Wrong Correction Flow](templates/memory-correction/thats-wrong-correction-flow.md)
  - [Conflicting Memory Resolver](templates/memory-correction/conflicting-memory-resolver.md)
  - [Correction Feedback Receipt](templates/memory-correction/correction-feedback-receipt.md)
- [Memory Forgetting](templates/memory-forgetting/README.md)
  - [Forget Single Memory](templates/memory-forgetting/forget-single-memory.md)
  - [Forget by Category](templates/memory-forgetting/forget-by-category.md)
  - [Memory Expiry Control](templates/memory-forgetting/memory-expiry-control.md)
- [Scope and Permissions](templates/memory-scope-permissions/README.md)
  - [Remember for This Chat Only](templates/memory-scope-permissions/remember-for-this-chat-only.md)
  - [Remember Across Workspace](templates/memory-scope-permissions/remember-across-workspace.md)
  - [Sensitive Memory Consent Gate](templates/memory-scope-permissions/sensitive-memory-consent-gate.md)
- [Provenance and Confidence](templates/provenance-confidence/README.md)
  - [Why Remembered This](templates/provenance-confidence/why-remembered-this.md)
  - [Confidence and Source Indicator](templates/provenance-confidence/confidence-and-source-indicator.md)

## Who it is for

This repository is designed for product designers, UX researchers, AI application builders, AI consultants, product managers, and researchers exploring human-centered AI memory.

## Strategic framing

A memory-aware product does not simply store more context. It gives people meaningful control over the context that shapes future experiences.

Good memory design answers questions like:

- What should the product remember?
- When should memory be suggested rather than silently saved?
- How can users inspect what memory contains?
- How can incorrect memories be fixed?
- How can sensitive or outdated memories be forgotten?
- How should uncertainty, source, and confidence be communicated?
- How should memory behave across individuals, teams, and shared workspaces?

## Repository structure

```text
docs/
  vision.md
  taxonomy.md
  memory-design-principles.md
  review-checklist.md

templates/
  template-schema.md
  matrix-index.md
  memory-capture/
  memory-inspection/
  memory-editing/
  memory-correction/
  memory-forgetting/
  memory-scope-permissions/
  provenance-confidence/

examples/
  scenario-map.md
```

## Design stance

This repository favors transparency over hidden automation, correction over silent persistence, consent over surprise, progressive disclosure over information overload, and practical product patterns over abstract principles alone.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.
