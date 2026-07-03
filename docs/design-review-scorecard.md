# Design Review Scorecard

Use this scorecard to evaluate memory-aware product flows during critique, prototype review, or launch readiness.

## Scoring method

Score each area from 0 to 3.

- 0: Missing or unclear
- 1: Present but weak
- 2: Usable with minor gaps
- 3: Strong and ready for production review

## Scorecard

| Area | Review question | Score |
|---|---|---|
| Capture clarity | Does the user understand what may be remembered? | 0-3 |
| Consent | Is consent appropriate for the risk level? | 0-3 |
| Scope | Is it clear where memory applies? | 0-3 |
| Inspection | Can users see relevant memory at the right moment? | 0-3 |
| Editing | Can users change memory directly? | 0-3 |
| Correction | Can users repair wrong memory from the error moment? | 0-3 |
| Forgetting | Can users remove or deactivate memory with clear consequences? | 0-3 |
| Provenance | Can users see where memory came from? | 0-3 |
| Confidence | Are uncertain or stale memories marked? | 0-3 |
| Accessibility | Are controls understandable and reachable for different users? | 0-3 |

## Interpreting results

- 24-30: Strong foundation. Run scenario testing and edge-case review.
- 16-23: Promising but needs targeted improvements before launch.
- 8-15: Memory controls are likely incomplete or hard to trust.
- 0-7: The experience should not ship as memory-aware.

## Review notes template

For each weak area, capture:

- What the user may misunderstand
- Which memory template applies
- What change would improve control or clarity
- Whether the issue blocks launch

## Common blockers

A memory-aware flow should not ship if:

- Users cannot tell memory is being used.
- Users cannot correct wrong memory.
- Sensitive memory is saved without explicit consent.
- Shared memory has no owner or permission model.
- Forgetting does not explain future behavior impact.
