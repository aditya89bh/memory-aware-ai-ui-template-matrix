# Explicit Memory Save Prompt

## Problem

A user says something that may be useful in future interactions, but saving it silently could feel presumptive or intrusive. The product needs a clear moment where the user can approve memory creation.

## When to use

Use this pattern when memory is durable, user-specific, and likely to shape future behavior. It works especially well for preferences, constraints, recurring instructions, and project norms.

Do not use it for every minor statement. Over-prompting makes memory feel noisy and needy.

## UI pattern

Show a compact confirmation prompt near the relevant interaction:

- Summary of the proposed memory
- Scope label such as personal, project, or workspace
- Primary action: remember
- Secondary action: not now
- Optional action: edit before saving

The prompt should be close to the moment of capture so the source is obvious.

## User controls

- Remember this
- Edit wording
- Change scope
- Not now
- Never remember this type of detail

## Edge cases

- The user statement contains sensitive information mixed with harmless preference.
- The proposed memory is too broad or vague.
- A similar memory already exists.
- The memory conflicts with an older preference.
- The user is in a shared workspace and personal memory would be inappropriate.

## Trust risk

The main risk is consent failure. If the product saves memory without a clear user decision, users may feel watched rather than helped.

## Example product context

A writing tool notices the user says, "For client summaries, keep the tone direct and avoid hype." It asks: "Remember this writing preference for this project?" The user can save, edit, or dismiss it.
