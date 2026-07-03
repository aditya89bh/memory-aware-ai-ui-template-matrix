# Team Collaboration Flow

## Product context

A collaboration workspace helps product, design, and research teams maintain shared context across projects. Memory can preserve team norms, decisions, and project constraints, but shared memory needs clear permissions and review.

## User goal

A team wants the product to remember project-specific decisions and workspace-level practices without turning individual preferences into team rules.

## Memory involved

- Project memory: accessibility review is required before handoff
- Workspace memory: decision notes should include owner and due date
- Personal memory: one designer prefers visual summaries
- Conflict memory: project requires formal client language, while personal memory prefers casual drafts

## UI sequence

1. A user highlights a project decision and selects "Save as project memory."
2. The save prompt shows scope, source, and who can edit it.
3. A reviewer approves workspace-level memory before it becomes active for everyone.
4. When the product drafts a handoff checklist, it shows source-linked memory cards for project requirements.
5. The workspace memory manager lists shared memories by project, owner, status, and review date.

## Correction moment

A team member notices that the product applies a personal tone preference to a client-facing deliverable. They open the conflicting memory resolver and choose the project-level formal tone for this client workspace.

## Forgetting moment

When the project closes, the team archives project memory. The archive flow explains that the memory will remain in project history but will not influence new work.

## Trust risk

Shared memory can become governance without consent. If one person's preference affects the whole team, users may perceive the workspace as unpredictable or unfair.

## Success criteria

- Users can distinguish personal, project, and workspace memory.
- Shared memory shows source and owner.
- Conflicts between personal and shared memory are resolved visibly.
- Closed project memory stops affecting active work.

## Templates used

- [Remember Across Workspace](../templates/memory-scope-permissions/remember-across-workspace.md)
- [Source-Linked Memory Card](../templates/memory-inspection/source-linked-memory-card.md)
- [Conflicting Memory Resolver](../templates/memory-correction/conflicting-memory-resolver.md)
- [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md)
