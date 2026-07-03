# Memory Scope Map

## Purpose

Clarify where memory applies and who is affected by it.

## When to use

Use this whenever memory can move between chat, personal, project, workspace, or organization contexts.

## Diagram

```text
Organization
└── Workspace
    └── Project
        └── Personal
            └── Session / Chat
```

Memory can move outward only with stronger justification, clearer visibility, and more review.

## How product teams should apply it

Place each memory object at the narrowest useful scope. If a proposed memory affects a broader scope, document who can see it, edit it, approve it, and forget it.

## Common mistakes

- Applying chat memory across a workspace.
- Saving personal preferences as team norms.
- Hiding scope labels in settings only.
- Not explaining what happens when a project is archived.
