# Education Tutor Flow

## Product context

An education tutor adapts lessons to a learner's goals, knowledge gaps, pacing, and preferred explanation style. Memory can make tutoring more effective, but learning profiles must remain inspectable and correctable.

## User goal

A learner wants the tutor to remember learning preferences and progress while allowing them to reset outdated assumptions or keep sensitive learning struggles private.

## Memory involved

- Learning preference: visual explanation before formulas
- Progress memory: understands linear equations, still practicing quadratic factoring
- Temporary study goal: prepare for Friday quiz
- Sensitive memory: anxiety around timed tests

## UI sequence

1. After repeated use of diagrams, the tutor asks whether to remember visual-first explanations.
2. The learner profile shows remembered skills, active goals, and preferred teaching style.
3. Before a lesson, the tutor shows a short "Using these memories" panel.
4. Skill memories have confidence labels based on recent performance and learner confirmation.
5. Sensitive learning context defaults to session-only memory unless explicitly saved.

## Correction moment

The tutor assumes the learner has mastered quadratic factoring. The learner selects "That's wrong" and updates the skill memory to "Needs guided practice with factoring by grouping."

## Forgetting moment

After the quiz, the learner deletes the temporary quiz preparation goal and keeps the broader algebra progress memory.

## Trust risk

The product may lock a learner into stale labels. If incorrect skill memory persists, the learner may receive lessons that are too hard, too easy, or discouraging.

## Success criteria

- Learner can inspect learning profile memory.
- Skill confidence is visible and reviewable.
- Wrong skill assumptions can be corrected from the lesson flow.
- Temporary study goals can expire without deleting long-term progress.

## Templates used

- [Inferred Preference Confirmation](../templates/memory-capture/inferred-preference-confirmation.md)
- [Profile-Level Memory Manager](../templates/memory-editing/profile-level-memory-manager.md)
- [Confidence and Source Indicator](../templates/provenance-confidence/confidence-and-source-indicator.md)
- [Memory Expiry Control](../templates/memory-forgetting/memory-expiry-control.md)
