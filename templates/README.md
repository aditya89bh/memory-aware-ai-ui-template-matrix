# Templates

This directory will contain the reusable template matrix for memory-aware product design.

The templates are intended to help teams design experiences before implementation. They should describe interaction patterns, product decisions, content guidance, risks, and evaluation questions. They are not tied to any specific frontend framework or design tool.

## Template categories

Future templates should be organized around user-facing memory jobs.

### 1. Capture templates

Patterns for deciding when and how memory is created.

Example templates:

- Suggested memory confirmation
- Explicit preference save
- Project context capture
- Repeated behavior detection
- Imported memory review

### 2. Inspection templates

Patterns for helping users understand what the product remembers.

Example templates:

- Memory drawer
- Memory dashboard
- Inline memory chip
- Source-linked memory card
- Periodic memory digest

### 3. Editing and correction templates

Patterns for fixing memory that is wrong, outdated, vague, or incomplete.

Example templates:

- Edit memory detail
- Correct mistaken inference
- Replace stale preference
- Merge duplicate memories
- Resolve conflicting memories

### 4. Forgetting templates

Patterns for removing or deactivating memory.

Example templates:

- Forget this memory
- Stop using this source
- Archive project memory
- Expire old preferences
- Bulk review and delete

### 5. Scope and permission templates

Patterns for controlling where memory applies and who can manage it.

Example templates:

- Personal versus project memory selector
- Team memory approval
- Workspace-level memory setting
- Sensitive memory warning
- Shared context boundary

### 6. Provenance and confidence templates

Patterns for communicating source, certainty, recency, and reliability.

Example templates:

- Source card
- Confidence label
- Last confirmed timestamp
- Conflicting source comparison
- Evidence trail

## Recommended template format

Each template should include:

- **Template name**
- **User problem**
- **When to use**
- **When not to use**
- **Memory objects involved**
- **Source and scope rules**
- **Primary user actions**
- **Interaction flow**
- **Content guidance**
- **Trust and safety considerations**
- **Accessibility considerations**
- **Failure modes**
- **Research questions**
- **Example product contexts**

## Quality bar

A useful template should be specific enough for a product team to apply in a design review, but general enough to work across multiple product categories. It should clarify decisions rather than merely describe a UI screen.

Templates should avoid implementation-specific language unless implementation constraints affect the design decision.
