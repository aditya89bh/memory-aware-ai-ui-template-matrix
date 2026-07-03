# Memory Risk Rubric

This rubric helps teams classify memory by the level of user trust, privacy, and product impact involved.

## Risk levels

| Level | Description | Examples | Default design posture |
|---|---|---|---|
| Low | Memory improves convenience with limited downside if wrong. | Formatting preference, summary length, dashboard view. | Lightweight notice and easy edit. |
| Medium | Memory affects workflow quality, collaboration, or recurring decisions. | Project norms, planning constraints, customer preferences. | Source, scope, edit, and forget controls. |
| High | Memory may affect sensitive, consequential, or identity-adjacent outcomes. | Health context, financial goals, employment constraints, confidential business details. | Explicit consent, narrow scope, conservative reuse. |
| Critical | Memory could create safety, legal, or material harm if wrong or misused. | Safety procedures, regulated decisions, access constraints. | Human review, audit trail, strong permissions, expiration. |

## Classification questions

- Would a wrong memory cause embarrassment, wasted work, or harm?
- Could the memory reveal sensitive personal or organizational context?
- Does the memory affect other people besides the user who created it?
- Is the memory inferred rather than directly confirmed?
- Does the product use the memory to automate consequential actions?
- Does the memory need to expire or be reviewed periodically?

## Required controls by risk level

| Control | Low | Medium | High | Critical |
|---|---|---|---|---|
| Inspect | Recommended | Required | Required | Required |
| Edit | Required | Required | Required | Restricted but available |
| Forget | Required | Required | Required | Policy-governed |
| Source visibility | Optional | Required | Required | Required |
| Explicit consent | Optional | Recommended | Required | Required |
| Scope selector | Optional | Required | Required | Required |
| Review date | Optional | Recommended | Required | Required |
| Audit trail | Optional | Optional | Recommended | Required |

## How to apply the rubric

Use the highest applicable risk level. A memory about a simple preference becomes higher risk if it is shared across a workspace, inferred without confirmation, or used in consequential automation.

## Review cadence

- Low-risk memory can be reviewed on demand.
- Medium-risk memory should be reviewed when it becomes stale or conflicts.
- High-risk memory should have visible review dates and conservative defaults.
- Critical memory should have ownership, auditability, and operational review.
