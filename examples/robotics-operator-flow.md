# Robotics Operator Flow

## Product context

A robotics operations interface helps operators supervise robot tasks, review incidents, and configure site-specific operating preferences. Memory can reduce repeated setup, but operator-facing memory must be precise and auditable.

## User goal

An operator wants the interface to remember site procedures and display preferences while ensuring that safety-relevant assumptions are confirmed, source-linked, and easy to revoke.

## Memory involved

- Site memory: loading dock route avoids zone C after 5 PM
- Operator preference: show camera view before task summary
- Temporary incident context: wet floor near bay 2
- Safety-sensitive memory: restricted operating area during maintenance

## UI sequence

1. The operator saves a site-specific route constraint from an incident review.
2. The capture prompt requires source, scope, and review date.
3. During route planning, the interface shows source-linked memory cards for active constraints.
4. Safety-sensitive memory appears with a confidence and review status indicator.
5. A timeline shows when site constraints were created, corrected, or expired.

## Correction moment

A route warning references the wrong bay. The operator opens the source-linked card, marks the memory wrong, and corrects the affected zone. The receipt confirms the corrected site memory and review owner.

## Forgetting moment

After maintenance ends, the operator expires the restricted-area memory. The interface confirms that the restriction will no longer block route suggestions but remains visible in the incident timeline.

## Trust risk

In robotics operations, stale or wrong memory can create operational and safety risk. Memory should never silently override current sensor data, operator judgment, or safety procedures.

## Success criteria

- Safety-relevant memory is source-linked and scoped to the site.
- Operators can see active constraints before execution.
- Corrections are auditable and reflected in future planning.
- Temporary incident memory expires cleanly.

## Templates used

- [Contextual Memory Boundary](../templates/memory-capture/contextual-memory-boundary.md)
- [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md)
- [Remembered Facts Timeline](../templates/memory-inspection/remembered-facts-timeline.md)
- [Correction Feedback Receipt](../templates/memory-correction/correction-feedback-receipt.md)
