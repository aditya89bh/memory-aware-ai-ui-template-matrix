# Memory Scope and Permission Templates

Scope and permission templates define where memory applies and who can create, inspect, edit, or remove it.

Memory becomes riskier when it crosses boundaries. A detail that is helpful in one chat may be inappropriate across a workspace. A team norm may conflict with a personal preference.

## Design goal

Make memory boundaries explicit and controllable.

## Templates in this family

- [Remember for This Chat Only](remember-for-this-chat-only.md)
- [Remember Across Workspace](remember-across-workspace.md)
- [Sensitive Memory Consent Gate](sensitive-memory-consent-gate.md)

## Use this family when

- Memory can apply at multiple levels.
- Users collaborate in shared workspaces.
- A memory may expose sensitive information.
- Permissions affect who can edit or delete memory.
- The product needs to distinguish private preferences from shared operating context.

## Design cautions

Scope labels must be plain. Users should not need to understand internal data architecture to know where memory will be used.
