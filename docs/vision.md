# Vision

## Memory as a design surface

AI products increasingly rely on memory: remembered preferences, working context, long-running goals, team knowledge, task history, personal facts, and behavioral signals. These memories influence what the product suggests, prioritizes, explains, automates, and avoids.

When memory is invisible, users cannot reliably understand why the product behaves the way it does. They may not know whether a suggestion came from current context, long-term memory, a mistaken inference, or an outdated preference. This weakens trust and makes correction difficult.

The central vision of this repository is simple:

> Memory should be designed as an inspectable, editable, correctable, and forgettable part of the user experience.

## The problem

Many memory-enabled products expose memory only through narrow settings screens or vague statements such as "we remember your preferences." That is not enough for serious products where memory affects decisions, recommendations, personalization, collaboration, or automation.

Common product gaps include:

- Users cannot see what has been remembered.
- Users cannot tell when memory is being used.
- Incorrect memories persist across sessions.
- Sensitive memories are saved without adequate user awareness.
- Users can delete account data but not manage specific memories.
- Product teams lack shared terminology for memory behavior.
- Design teams treat memory as a technical capability rather than an interaction model.

These gaps create practical risks: confusion, loss of trust, poor personalization, privacy concerns, and brittle user experiences.

## The opportunity

Memory-aware design can make AI products feel more understandable, respectful, and useful. The best memory experiences do not overwhelm users with raw data. They reveal the right level of memory at the right moment, with clear controls and predictable outcomes.

A strong memory design system helps teams decide:

- Which memories should be explicit versus implicit
- Which memories need confirmation before saving
- Which memories should expire
- Which memories require source visibility
- Which memories can be edited directly
- Which memories should be scoped to a person, project, team, or organization
- Which memories should never be stored

## What success looks like

A mature version of this repository should help a product team move from a vague feature statement like "the assistant remembers users" to a precise set of user-facing design decisions:

- What memory exists
- Where it appears
- How it is explained
- How it is corrected
- How it is forgotten
- How it is evaluated
- How it changes over time

The repository should become useful for early product discovery, UX reviews, design critique, prototyping, product requirements, and research planning.

## Repository principles

This project is intentionally not organized around code components. Code components are implementation details. The harder problem is deciding what the experience should be.

The repository is organized around reusable product templates that describe:

- User intent
- Memory behavior
- Interaction pattern
- Trust and safety considerations
- Content guidance
- Research questions
- Failure modes
- Example applications

## Long-term direction

Over time, this repository should grow into a reference library for memory design. It should include template matrices, example flows, review checklists, evaluation rubrics, terminology guides, and scenario libraries that teams can adapt to their own products.

The long-term goal is to make transparent memory design a normal part of AI product development.
