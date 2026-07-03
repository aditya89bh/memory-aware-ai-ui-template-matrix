# Memory Capture Templates

Memory capture templates define how a product asks, suggests, or decides that something should be remembered.

Capture is the first trust moment in a memory-aware experience. If users feel surprised by what has been saved, later inspection and deletion controls cannot fully repair the trust gap.

## Design goal

Make remembering intentional, understandable, and scoped.

## Templates in this family

- [Explicit Memory Save Prompt](explicit-memory-save-prompt.md)
- [Inferred Preference Confirmation](inferred-preference-confirmation.md)
- [Contextual Memory Boundary](contextual-memory-boundary.md)

## Use this family when

- The product identifies information that may be useful later.
- A user states a durable preference or constraint.
- The product infers a pattern from repeated behavior.
- Memory could cross from the current session into future experiences.
- The user needs to choose whether memory should be personal, project-level, or workspace-level.

## Design cautions

Capture should not become constant interruption. Use confirmation when the memory is important, sensitive, inferred, or likely to affect future outcomes. For low-risk convenience memory, lightweight notice may be enough.
