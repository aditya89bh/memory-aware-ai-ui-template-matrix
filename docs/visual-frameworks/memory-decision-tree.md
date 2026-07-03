# Memory Decision Tree

## Purpose

Help teams decide whether a product should remember something, ask first, keep it temporary, or avoid saving it.

## When to use

Use this during product planning, prototype review, or memory capture design.

## Diagram

```text
Should the product remember this?
|
|-- Is it useful beyond the current moment?
|   |-- No -> Keep as session context only.
|   |-- Yes
|       |-- Is it sensitive or high-impact?
|       |   |-- Yes -> Require explicit consent and narrow scope.
|       |   |-- No
|       |       |-- Was it directly stated by the user?
|       |       |   |-- Yes -> Offer explicit save prompt.
|       |       |   |-- No -> Treat as inference and ask for confirmation.
|       |-- Could it affect other users?
|           |-- Yes -> Use shared-memory permission review.
|           |-- No -> Save as personal or project memory.
```

## How product teams should apply it

Run every proposed memory object through the tree before choosing a capture pattern.

## Common mistakes

- Saving inferred memory as if it were confirmed.
- Treating useful memory as automatically appropriate to store.
- Ignoring whether memory affects other users.
- Skipping narrow scope for sensitive details.
