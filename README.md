# Memory-Aware AI UI Template Matrix

A design reference for creating inspectable, editable, correctable, and forgettable memory experiences in AI products.

## Why this repository exists

AI memory is becoming a core part of product experience. Applications increasingly remember user preferences, ongoing projects, prior conversations, behavioral patterns, and context gathered across sessions. Yet most memory experiences are still treated as backend features: hidden, automatic, difficult to inspect, and hard to correct.

This repository takes a different position: **memory is a first-class design material**.

Memory should be visible when it matters, controllable when it affects outcomes, and reversible when it is wrong. People should be able to understand what a system remembers, why it matters, how it is used, and how to change or remove it. Product teams need reusable design patterns for that work.

## What this repository provides

This is a **template matrix**, not a frontend component library. It focuses on product patterns, interaction models, decision points, and documentation that help teams design trustworthy memory experiences before choosing an implementation stack.

The repository will organize templates across memory design needs such as:

- Memory capture and consent
- Memory inspection and review
- Memory editing and correction
- Memory deletion and forgetting
- Confidence, provenance, and source visibility
- Scoped memory for people, projects, teams, and organizations
- Conflict resolution when memories disagree
- Memory lifecycle and expiration
- User education and expectation-setting
- Research and evaluation flows for memory-heavy products

## Who it is for

This repository is designed for:

- Product designers creating AI product flows
- UX researchers studying trust, control, and transparency
- AI application builders designing memory-backed products
- AI consultants advising teams on user-facing memory systems
- Product managers defining memory behavior and governance
- Researchers exploring human-centered AI memory

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

The goal is to make these questions easier to answer with reusable design structures.

## Repository structure

```text
docs/
  vision.md
  taxonomy.md
  memory-design-principles.md

templates/
  README.md

examples/
  README.md
```

- `docs/` contains the conceptual foundation for the repository.
- `templates/` will contain reusable template specifications for memory-related product flows.
- `examples/` will contain practical scenarios that show how the templates can be applied.

## Current phase

Phase 1 establishes the foundation: repository structure, core documentation, contribution guidance, and licensing.

Future phases should add the first template matrix, scenario examples, evaluation rubrics, and downloadable design artifacts.

## Design stance

This repository favors:

- Transparency over hidden automation
- Correction over silent persistence
- Consent over surprise
- Progressive disclosure over information overload
- Practical product patterns over abstract principles alone
- Durable terminology that can be shared across design, product, research, and engineering teams

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.
