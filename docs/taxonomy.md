# Memory Design Taxonomy

This taxonomy defines the core terms used throughout the repository. It is meant to help product, design, research, and engineering teams discuss memory behavior with precision.

## 1. Memory object

A memory object is a discrete piece of information the product may reuse later.

Examples:

- A user prefers concise summaries.
- A project uses a specific design system.
- A team has a recurring weekly planning ritual.
- A user corrected a prior misunderstanding.
- A customer does not want certain topics used for personalization.

Design questions:

- Is this memory useful enough to persist?
- Is it factual, inferred, behavioral, or preference-based?
- Does it require user confirmation?
- Who can view, edit, or delete it?

## 2. Memory source

The source explains where a memory came from.

Common sources include:

- Direct user statement
- User correction
- Repeated behavior
- Imported profile or settings data
- Project documentation
- Team workspace content
- System-generated summary

Source visibility helps users decide whether memory is trustworthy. A memory based on a direct statement should be presented differently from one inferred from behavior.

## 3. Memory confidence

Confidence describes how certain the product is that a memory is accurate, current, and useful.

Confidence can be shaped by:

- Recency
- Frequency
- Explicit confirmation
- Contradictory signals
- Source reliability
- User corrections

Design guidance:

- High-confidence memories can be used with less friction.
- Medium-confidence memories may need lightweight confirmation.
- Low-confidence memories should be suggested, not silently applied.

## 4. Memory scope

Scope defines where a memory applies.

Common scopes:

- **Session memory:** applies only to the current interaction.
- **Personal memory:** applies to one person across sessions.
- **Project memory:** applies within a specific project or workspace.
- **Team memory:** applies to a group of collaborators.
- **Organization memory:** applies across a broader institution.
- **Public reference memory:** applies to shared published knowledge.

Scope should be visible when a memory could affect multiple people or contexts.

## 5. Memory lifecycle

Lifecycle describes how a memory is created, reviewed, updated, archived, or deleted.

Typical lifecycle states:

- Proposed
- Confirmed
- Active
- Stale
- Conflicted
- Archived
- Deleted

Lifecycle design matters because memory is not static. People change preferences, projects evolve, teams reorganize, and facts become outdated.

## 6. Memory action

Memory actions are user-facing controls that allow people to manage memory.

Core actions:

- Inspect
- Add
- Confirm
- Edit
- Correct
- Merge
- Archive
- Forget
- Restore
- Export

Actions should use plain language. "Forget this" is often more understandable than "delete memory object," while "archive" may be better when historical context should remain available but inactive.

## 7. Memory visibility pattern

Visibility patterns define how and when memory appears in the interface.

Examples:

- Memory drawer
- Inline memory chip
- Review queue
- Source card
- Preference panel
- Correction prompt
- Before-save confirmation
- Periodic memory digest
- Context banner

The right pattern depends on user intent, risk, and task complexity.

## 8. Memory risk level

Risk level describes the potential harm or confusion caused by storing or using a memory incorrectly.

Example risk levels:

- **Low:** harmless formatting preference
- **Medium:** project-specific workflow preference
- **High:** personal, financial, medical, legal, employment, or sensitive identity-related information

Higher-risk memories require stronger consent, clearer source visibility, easier deletion, and more conservative reuse.

## 9. Memory conflict

A conflict occurs when two or more memories disagree or when current behavior contradicts stored memory.

Examples:

- A user previously preferred short answers but now asks for detailed explanations.
- A project uses two different naming conventions.
- A team memory conflicts with an individual preference.

Design patterns should make conflicts understandable and resolvable rather than silently choosing one memory.

## 10. Memory outcome

The outcome is the product behavior shaped by memory.

Examples:

- Personalizing a response
- Prioritizing a recommendation
- Auto-filling a workflow
- Avoiding a repeated question
- Warning about a project constraint
- Suppressing an unwanted topic

Users should be able to connect important outcomes back to the memory that influenced them.

## Taxonomy use

Templates in this repository should reference these taxonomy terms consistently. Each template should clarify the memory object, source, confidence, scope, lifecycle, action, visibility pattern, risk level, conflict handling, and expected outcome.
