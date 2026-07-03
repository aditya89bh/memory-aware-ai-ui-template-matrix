# Examples

This directory will contain practical examples showing how memory design templates can be applied to real product scenarios.

Examples should make the repository concrete. A strong example should show the user situation, the memory involved, the interface decision, and the tradeoffs behind the pattern.

## Example scenario types

### Personal productivity

Memory helps a product adapt to a person's recurring preferences, writing style, planning habits, and task workflows.

Possible scenarios:

- Remembering preferred summary length
- Correcting a mistaken work schedule
- Forgetting an outdated project priority
- Reviewing stale task assumptions

### Team collaboration

Memory supports shared context across a workspace, but must distinguish individual preferences from team-level norms.

Possible scenarios:

- Team memory approval before reuse
- Resolving conflict between personal and workspace preferences
- Showing which project decision influenced a recommendation
- Archiving memory after a project ends

### Customer support

Memory can improve continuity across conversations, but must be clear, scoped, and easy to correct.

Possible scenarios:

- Remembering a customer's preferred contact method
- Showing source for account-specific context
- Correcting a mistaken product ownership assumption
- Forgetting sensitive information after resolution

### Creative tools

Memory can preserve style, constraints, and creative direction across sessions.

Possible scenarios:

- Saving brand voice preferences
- Comparing conflicting creative direction memories
- Applying project-only memory to generated drafts
- Reviewing memory before using it in a client deliverable

### Research and evaluation

Memory design needs usability and trust evaluation, not only technical evaluation.

Possible scenarios:

- Testing whether users notice memory use
- Evaluating correction success
- Measuring confidence in memory controls
- Comparing deletion, archive, and disable flows

## Recommended example format

Each example should include:

- **Scenario title**
- **Product context**
- **User goal**
- **Memory involved**
- **Relevant template category**
- **Interaction walkthrough**
- **What the user can inspect**
- **What the user can change**
- **How forgetting works**
- **Risks and edge cases**
- **Success criteria**

## Quality bar

Examples should be realistic and decision-oriented. They should not only describe a polished happy path. They should include failure modes such as wrong memory, stale memory, sensitive memory, unclear source, and conflicts across scopes.

The best examples should help a product team ask better questions before building.
