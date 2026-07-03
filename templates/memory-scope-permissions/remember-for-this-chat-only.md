# Remember for This Chat Only

## Problem

The user wants continuity within the current conversation but does not want the detail to affect future sessions or broader product behavior.

## When to use

Use this pattern for temporary instructions, exploratory tasks, sensitive conversations, drafts, interviews, and one-off workflows.

## UI pattern

Offer a scope option labeled "this chat only" or equivalent. Show it during capture, editing, or temporary override:

- Current scope indicator
- Explanation of duration
- Option to expand scope later
- Clear end-of-chat behavior

## User controls

- Remember for this chat only
- Do not remember
- Upgrade to project memory
- Clear chat memory
- Review chat-only memory

## Edge cases

- The chat is later converted into a project.
- The user expects chat memory to survive a browser refresh.
- The product summarizes the chat into long-term memory.
- A shared chat includes multiple participants.
- The user wants one item from the chat saved permanently.

## Trust risk

The main risk is scope surprise. If chat-only memory later appears elsewhere, users may feel the boundary was broken.

## Example product context

During a brainstorming session, a user asks the product to assume a fictional customer persona for the current chat only.
