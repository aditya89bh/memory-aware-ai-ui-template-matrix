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
