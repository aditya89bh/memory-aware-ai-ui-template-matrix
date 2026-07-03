# That's Wrong Correction Flow

## Problem

The product uses an incorrect memory, and the user needs a fast way to say it is wrong and fix the underlying cause.

## When to use

Use this pattern whenever memory visibly influences an answer, recommendation, personalization, or automation. The correction entry point should be available near the mistake.

## UI pattern

Provide a direct correction affordance such as "That's wrong" or "Fix memory." The flow should show:

- The memory that influenced the output
- A plain-language correction field
- Scope affected by the correction
- Option to update, forget, or disable memory
- Confirmation after repair

## User controls

- Mark memory wrong
- Enter correction
- Choose affected scope
- Forget incorrect memory
- Keep output but fix future behavior
- Undo correction shortly after submission

## Edge cases

- The output is wrong for reasons unrelated to memory.
- Multiple memories contributed to the mistake.
- The user correction is ambiguous.
- The wrong memory came from a shared workspace source.
- The correction conflicts with a verified source.

## Trust risk

The main risk is correction dead-end. If users report a wrong memory but the product repeats the mistake, trust drops sharply.

## Example product context

A career planning product says the user prefers management roles. The user clicks "That's wrong" and corrects the memory to "Prefers research and prototyping roles."
