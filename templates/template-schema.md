# Template Schema

This schema defines the standard structure for every memory design template in this repository. It keeps the matrix usable across product design, UX research, product strategy, and implementation planning.

## Required sections

Each template must include the following sections.

### Problem

Describe the user-facing problem the template solves. The problem should explain why memory needs a designed interaction instead of being hidden system behavior.

### When to use

Define the situations where the pattern is appropriate. Include product maturity, risk level, and user intent where relevant.

### UI pattern

Describe the interface structure. This can include panels, cards, prompts, banners, review queues, timelines, or inline controls. Do not specify a frontend framework.

### User controls

List the actions available to the user. Controls should be concrete, such as save, edit, confirm, ignore, forget, scope, restore, or view source.

### Edge cases

Identify situations that may break the pattern or require special handling, such as stale memory, conflicting memory, sensitive content, shared workspace behavior, or uncertain inference.

### Trust risk

Explain the main risk if the pattern is designed poorly. Trust risk should include confusion, overreach, wrong personalization, privacy concern, or lack of recourse.

### Example product context

Provide at least one practical product context where the template could be used.

## Recommended optional sections

Templates may also include:

- Content guidance
- Accessibility notes
- Research questions
- Success metrics
- Related templates
- Variations by scope or risk level

## Naming conventions

Use short, descriptive filenames in kebab case. Folder names should reflect template families, such as `memory-capture`, `memory-inspection`, or `memory-forgetting`.

## Quality bar

A template is ready when a product team can use it in a design review and answer:

- What memory is involved?
- Why does the user need to see or control it?
- What actions are available?
- What could go wrong?
- How does the pattern support trust?
