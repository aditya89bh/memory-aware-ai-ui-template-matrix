# Figma-Ready Specs

Use this guide to turn repository templates into design files, workshop boards, or presentation assets.

## Purpose

The repository is Markdown-first, but many teams need visual design artifacts. This guide explains how to translate templates, canvases, and diagrams into reusable design frames.

## Recommended file structure

```text
Memory Design System
├── 01 Overview
├── 02 Template Matrix
├── 03 Memory Lifecycle
├── 04 Capture Patterns
├── 05 Inspection Patterns
├── 06 Correction Patterns
├── 07 Forgetting Patterns
├── 08 Scope and Permissions
├── 09 Provenance and Confidence
├── 10 Canvases and Workshop Boards
```

## Frame types

| Frame | Recommended content |
|---|---|
| Template card | Problem, when to use, UI pattern, controls, edge cases, trust risk |
| Flow frame | User goal, memory involved, UI sequence, correction moment, forgetting moment |
| Canvas frame | Fillable fields, review questions, decision output |
| Risk frame | Risk level, required controls, escalation trigger |
| Critique frame | Screenshot area, memory moments, missing controls, next actions |

## Layout guidance

Use a consistent three-column layout for template cards: context, interaction, trust considerations. Use color sparingly to distinguish scope and risk, not to decorate.

## Product review usage

Create one board per product flow. Add the selected templates, relevant canvas, risk rubric, and screenshots of the current design. End with a decision frame listing blockers and owners.

## Common mistakes

- Turning templates into static UI components without decision guidance.
- Removing edge cases to make slides look cleaner.
- Hiding correction and forgetting flows outside the main board.
- Using visual polish before memory scope and controls are clear.
