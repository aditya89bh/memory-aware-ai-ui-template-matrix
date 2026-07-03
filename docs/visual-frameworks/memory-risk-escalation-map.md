# Memory Risk Escalation Map

## Purpose

Show when a memory design should move from lightweight controls to stronger consent, review, and governance.

## When to use

Use this during risk review, stakeholder alignment, or launch readiness checks.

## Diagram

```text
Low risk
  -> Lightweight notice
  -> Inline edit
  -> Single-memory forget

Medium risk
  -> Source and scope labels
  -> Correction receipt
  -> Review stale memory

High risk
  -> Explicit consent
  -> Narrow scope
  -> Conservative reuse
  -> Easy deletion

Critical risk
  -> Human review
  -> Audit trail
  -> Owner and review date
  -> Policy-governed forgetting
```

## How product teams should apply it

Classify the memory using the risk rubric, then check whether the product provides the controls at that level or higher.

## Common mistakes

- Using low-risk controls for high-risk memory.
- Treating shared memory as personal memory.
- Hiding review dates for safety-relevant assumptions.
- Using confidence labels without source visibility.
