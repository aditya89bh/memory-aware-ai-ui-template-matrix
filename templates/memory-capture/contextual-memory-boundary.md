# Contextual Memory Boundary

## Problem

Some information is useful only within a specific context. Without a boundary, memory can leak into unrelated chats, projects, teams, or future tasks where it no longer applies.

## When to use

Use this pattern when the product captures memory from a project, customer account, workspace, temporary task, or sensitive conversation. It is especially important when users switch contexts frequently.

## UI pattern

Display a scope boundary at the moment memory may be saved:

- "Remember for this chat only"
- "Remember for this project"
- "Remember across workspace"
- "Do not remember after this session"

The UI should explain what the chosen boundary changes.

## User controls

- Choose memory scope
- Save only for current session
- Save for project
- Save personally
- Do not save
- Review existing memories in this scope

## Edge cases

- A memory belongs to both personal and project contexts.
- The user lacks permission to create workspace memory.
- A shared workspace includes confidential client information.
- The context changes mid-conversation.
- A project is archived but its memory remains active.

## Trust risk

The main risk is context collapse: memory from one environment influences another without user awareness. This can create embarrassing, incorrect, or unsafe outcomes.

## Example product context

A design team is working on a confidential client project. The product asks whether a brand constraint should be remembered only inside that project rather than applied across all future work.
