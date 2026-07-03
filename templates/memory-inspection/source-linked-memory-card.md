# Source-Linked Memory Card

## Problem

A memory statement is easier to trust when the user can see where it came from. Without source context, users may not know whether the memory is accurate, inferred, outdated, or copied from another scope.

## When to use

Use this pattern when memory affects a visible output or decision and source reliability matters. It is especially useful for project constraints, customer facts, research notes, and team decisions.

## UI pattern

Display a compact card containing:

- Memory statement
- Source type
- Source link or excerpt
- Scope
- Last confirmed date
- Confidence or status label
- Edit and forget actions

The source should be understandable without exposing unrelated private content.

## User controls

- Open source
- Edit memory
- Mark source as wrong
- Change scope
- Forget memory
- Report mismatch

## Edge cases

- Source content was deleted or permission-restricted.
- The memory was synthesized from several sources.
- The source is a user correction rather than original content.
- The source contains sensitive information.
- The memory is accurate but the source is no longer authoritative.

## Trust risk

The main risk is unverifiable memory. Users may reject helpful personalization if they cannot see why the product believes something.

## Example product context

A proposal drafting tool shows a card saying "Use formal tone for this client," linked to the kickoff note where the team recorded the client's brand guidance.
