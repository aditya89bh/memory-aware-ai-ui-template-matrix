# Memory Lifecycle Rubric

Memory should be designed across its full lifecycle, not only at the moment of capture.

## Lifecycle stages

| Stage | User question | Design responsibility |
|---|---|---|
| Proposed | Should this be remembered? | Show proposed memory, source, and scope. |
| Confirmed | What exactly was saved? | Provide receipt or visible memory card. |
| Active | How is memory affecting experience? | Show relevant memory near outcomes. |
| Edited | How can memory change over time? | Support direct edits and scope changes. |
| Corrected | What happens when memory is wrong? | Repair the memory and confirm future behavior. |
| Stale | Is this still true? | Mark age, review status, and uncertainty. |
| Conflicted | Which memory applies now? | Resolve openly with source and scope. |
| Forgotten | What stops being used? | Explain deletion, archive, or deactivation. |

## Lifecycle review questions

- Does each memory type have a capture path?
- Does each memory type have an inspection surface?
- Does each memory type have a correction path?
- Does each memory type have a forgetting path?
- Does each memory type have a stale or expiry strategy?

## Lifecycle maturity levels

### Level 1: Hidden persistence

Memory exists but users cannot reliably see or control it. This level is not appropriate for high-risk memory.

### Level 2: Basic controls

Users can view and delete some memory, usually in settings. Correction may be indirect.

### Level 3: Contextual control

Users can inspect, edit, correct, and forget memory at the moment it affects outcomes.

### Level 4: Governed memory lifecycle

Memory has ownership, review dates, source visibility, permissioning, expiry, and auditability where needed.

## Recommended target

Most production memory-aware products should reach Level 3 for user-facing memory and Level 4 for shared, sensitive, or safety-relevant memory.
