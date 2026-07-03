# Use Cases by Industry

This guide helps teams connect the memory design matrix to practical product categories.

Memory-aware design looks different across industries. A productivity product may need lightweight preference controls, while a robotics operations interface may need stronger auditability, source visibility, and expiry. The same template family can support both, but the risk level, language, and review process should change.

## How to use this guide

For each industry, review:

- Common memory objects
- Typical user-facing risks
- Relevant template families
- Recommended review tools
- Product questions to answer before design approval

Use this guide alongside:

- [Template Matrix Index](../templates/matrix-index.md)
- [Template Selection Guide](template-selection-guide.md)
- [Memory Risk Rubric](memory-risk-rubric.md)
- [Design Review Scorecard](design-review-scorecard.md)

## Industry coverage

- Productivity tools
- Team collaboration
- Customer support
- Education
- Robotics operations
- Research tools
- Creative tools

## Productivity tools

### Common memory objects

- Planning preferences
- Summary style and detail level
- Recurring task routines
- Calendar constraints
- Project-specific priorities

### User-facing risks

Productivity memory can become annoying when it turns a temporary behavior into a durable rule. It can also create planning errors when stale preferences continue shaping recommendations.

### Useful templates

- [Inferred Preference Confirmation](../templates/memory-capture/inferred-preference-confirmation.md)
- [Memory Drawer](../templates/memory-inspection/memory-drawer.md)
- [Temporary Session Override](../templates/memory-editing/temporary-session-override.md)
- [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md)

### Review questions

- Can the user see which memories shaped a plan?
- Can temporary planning context expire?
- Can the user override memory for one task without changing long-term preferences?
- Are stale routines marked for review?

## Team collaboration

### Common memory objects

- Team norms
- Project decisions
- Client constraints
- Workspace standards
- Personal collaboration preferences

### User-facing risks

Shared memory can make one person's preference feel like a team rule. It can also spread outdated project context across future work.

### Useful templates

- [Remember Across Workspace](../templates/memory-scope-permissions/remember-across-workspace.md)
- [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md)
- [Conflicting Memory Resolver](../templates/memory-correction/conflicting-memory-resolver.md)
- [Remembered Facts Timeline](../templates/memory-inspection/remembered-facts-timeline.md)

### Review questions

- Who can create workspace memory?
- Who owns review of shared memory?
- Can personal and team memory be distinguished?
- Does archived project memory stop influencing active work?

## Customer support

### Common memory objects

- Customer preferences
- Account facts
- Support history summaries
- Case-specific context
- Communication constraints

### User-facing risks

Wrong support memory can create repeated frustration, privacy mistakes, or inaccurate account handling. Support teams need correction controls during live work.

### Useful templates

- [Memory Drawer](../templates/memory-inspection/memory-drawer.md)
- [Inline Memory Edit](../templates/memory-editing/inline-memory-edit.md)
- [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md)
- [Forget Single Memory](../templates/memory-forgetting/forget-single-memory.md)

### Review questions

- Can representatives correct customer memory from the support thread?
- Are account facts source-linked?
- Is sensitive case context scoped narrowly?
- Does forgetting explain whether case history remains?

## Education

### Common memory objects

- Learning preferences
- Skill progress
- Study goals
- Accessibility needs
- Confidence indicators for knowledge areas

### User-facing risks

Educational memory can label learners too rigidly. Stale skill assumptions can make lessons too easy, too hard, or discouraging.

### Useful templates

- [Profile-Level Memory Manager](../templates/memory-editing/profile-level-memory-manager.md)
- [Confidence and Source Indicator](../templates/provenance-confidence/confidence-and-source-indicator.md)
- [That's Wrong Correction Flow](../templates/memory-correction/thats-wrong-correction-flow.md)
- [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md)

### Review questions

- Can learners inspect their learning profile?
- Are skill memories marked by confidence and recency?
- Can temporary study goals expire?
- Are sensitive learning concerns handled with narrow scope?

## Robotics operations

### Common memory objects

- Site constraints
- Operator display preferences
- Route restrictions
- Incident context
- Review dates for operating assumptions

### User-facing risks

Operational memory can affect safety and workflow reliability. Stale or incorrect constraints must be visible, source-linked, and reviewable.

### Useful templates

- [Contextual Memory Boundary](../templates/memory-capture/contextual-memory-boundary.md)
- [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md)
- [Remembered Facts Timeline](../templates/memory-inspection/remembered-facts-timeline.md)
- [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md)

### Review questions

- Is safety-relevant memory reviewed before reuse?
- Does memory ever override current operator judgment or live system status?
- Are temporary incident constraints expired?
- Is correction auditable?

## Research tools

### Common memory objects

- Project assumptions
- Research questions
- Evidence summaries
- Participant-specific analysis context
- Synthesis preferences

### User-facing risks

Research memory can blur evidence, interpretation, and hypothesis. Source and confidence must remain visible.

### Useful templates

- [Why Remembered This](../templates/provenance-confidence/why-remembered-this.md)
- [Confidence and Source Indicator](../templates/provenance-confidence/confidence-and-source-indicator.md)
- [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md)
- [Remembered Facts Timeline](../templates/memory-inspection/remembered-facts-timeline.md)

### Review questions

- Are findings, assumptions, and hypotheses distinguished?
- Can researchers trace memory to source material?
- Can uncertain memory be downgraded or reviewed?
- Is participant context scoped appropriately?
