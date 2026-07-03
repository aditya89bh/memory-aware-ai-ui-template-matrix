# Memory Design Principles

These principles guide the templates and examples in this repository. They are written for product teams designing user-facing memory experiences.

## 1. Make memory visible when it matters

Not every memory needs to be shown all the time. But when memory affects an important answer, recommendation, automation, or decision, users should be able to understand that memory played a role.

Good patterns include:

- Inline memory indicators
- "Why am I seeing this?" explanations
- Memory source cards
- Expandable context drawers
- Reviewable memory summaries

Visibility should reduce confusion, not create noise.

## 2. Separate remembering from using

Saving a memory and applying a memory are different product moments.

A product may remember a preference but still ask before using it in a high-impact context. A memory may be stored for convenience but excluded from sensitive workflows. Designers should define both the storage behavior and the usage behavior.

Key questions:

- When is memory captured?
- When is it applied?
- When should the user be asked first?
- When should memory be ignored?

## 3. Prefer confirmation for high-impact memory

Some memories are low-risk, such as a preferred writing style. Others can shape meaningful outcomes, such as work preferences, personal constraints, health-related context, hiring context, or financial goals.

High-impact memories should not be silently inferred and reused. They should be confirmed, scoped, and easy to correct.

## 4. Design correction as a primary flow

Memory will be wrong sometimes. A trustworthy product treats correction as normal, not exceptional.

Correction flows should allow users to:

- Edit inaccurate memories
- Explain what changed
- Replace outdated memories
- Resolve conflicting memories
- Prevent the same mistake from recurring

A correction should update future behavior, not merely change a display label.

## 5. Make forgetting specific and understandable

"Delete all data" is not the only useful control. Users often need targeted forgetting.

Useful forgetting controls include:

- Forget this preference
- Stop using this for recommendations
- Remove this from project memory
- Archive this as historical context
- Delete this source and related memories

The result of forgetting should be clear. Users should know whether the memory is removed, inactive, archived, or still present in another scope.

## 6. Show source and scope

A memory without source or scope is difficult to trust.

Source answers: "Where did this come from?"

Scope answers: "Where will this apply?"

When memory crosses boundaries between personal, project, team, and organization contexts, scope should be especially explicit.

## 7. Let memory age

Preferences, facts, and project context become stale. Memory design should include aging, review, and expiration patterns.

Examples:

- "Last confirmed 6 months ago"
- "Review stale project assumptions"
- "This preference has not been used recently"
- "Archive memories from completed projects"

Aging makes memory feel maintained rather than permanent by default.

## 8. Handle conflict openly

Conflicting memories should not be silently resolved when the conflict affects the user experience.

A product can say:

- "You previously preferred short summaries, but this project asks for detailed notes. Which should apply here?"
- "This team setting conflicts with your personal preference. Use team setting for this workspace?"

Conflict handling is part of trust design.

## 9. Use progressive disclosure

Memory systems can become complex. Users should not need to inspect a database to feel in control.

Start with simple, task-relevant controls. Offer deeper inspection when users need it.

A good pattern often has three layers:

1. A lightweight signal that memory is being used
2. A summary of the relevant memory
3. A detailed inspection and editing view

## 10. Design for shared responsibility

Memory is both a system capability and a user relationship. The product should help users understand what it remembers, but it should not shift all responsibility to them.

The product should prevent obvious bad memory behavior, avoid sensitive overreach, surface uncertainty, and make control easy.

## 11. Keep language concrete

Avoid vague labels such as "enhanced personalization" when the product means "remember writing preferences" or "use project history." Clear language builds trust.

Prefer:

- "Remember this preference"
- "Use this only in this project"
- "Forget this detail"
- "Review memories from this source"

Avoid:

- "Optimize experience"
- "Improve context"
- "Enable intelligent memory"

## 12. Evaluate memory as experience, not only accuracy

Memory quality is not just whether stored information is correct. Teams should also evaluate whether users understand, trust, and control the memory experience.

Useful evaluation questions:

- Can users find what the product remembers?
- Can users correct memory without friction?
- Do users understand when memory affects outcomes?
- Do users know how to forget something?
- Are memory controls accessible at the right moment?

## Applying these principles

Every template in this repository should make these principles practical. A template should not only describe an ideal; it should help a team decide what to show, what to ask, what to save, what to forget, and what failure modes to watch for.
