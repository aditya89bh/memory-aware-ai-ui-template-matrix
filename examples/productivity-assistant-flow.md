# Productivity Assistant Flow

## Product context

A personal productivity assistant helps a user plan work, summarize tasks, and prepare for recurring routines. Memory improves continuity, but the user must be able to inspect and correct preferences that shape planning behavior.

## User goal

The user wants the product to remember durable work preferences, such as preferred planning style and meeting preparation format, while keeping temporary project details scoped to the right context.

## Memory involved

- Preferred planning format: weekly priorities first, then daily blocks
- Preferred summary length: concise unless the task is strategic
- Recurring constraint: no deep work blocks after late meetings
- Temporary session context: planning for a launch week only

## UI sequence

1. During planning, the product proposes: "Remember that you prefer weekly priorities before daily blocks?"
2. The user chooses a scope: personal memory or current project only.
3. A memory drawer appears beside the generated plan showing the preferences used.
4. Each memory card includes source, scope, last updated date, and edit action.
5. The plan output includes a subtle note: "Built using 3 remembered planning preferences."

## Correction moment

The assistant schedules deep work after a late meeting. The user selects "That's wrong" next to the plan note. The correction flow reveals the memory "Avoid deep work after late meetings" and lets the user refine it to "Avoid deep work after meetings ending after 6 PM."

## Forgetting moment

After launch week, the user opens the memory drawer and forgets the temporary launch planning constraint. The confirmation explains that the source conversation remains, but the constraint will no longer shape future plans.

## Trust risk

The product may over-personalize planning based on stale routines. If memory silently shapes the calendar, the user may not know why plans feel wrong.

## Success criteria

- User can identify which memories shaped a plan.
- User can correct a planning preference from the generated plan.
- Temporary memory expires or can be forgotten without affecting durable preferences.
- Future plans reflect the corrected memory.

## Templates used

- [Explicit Memory Save Prompt](../templates/memory-capture/explicit-memory-save-prompt.md)
- [Memory Drawer](../templates/memory-inspection/memory-drawer.md)
- [That's Wrong Correction Flow](../templates/memory-correction/thats-wrong-correction-flow.md)
- [Forget Single Memory](../templates/memory-forgetting/forget-single-memory.md)
