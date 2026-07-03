# Sensitive Memory Consent Gate

## Problem

Some memories involve sensitive personal, organizational, or regulated information. The product needs stronger consent before saving or applying them.

## When to use

Use this pattern when memory may involve health, finance, legal issues, employment, identity, location, confidential business information, or vulnerable personal context.

## UI pattern

Insert a consent gate before saving:

- Clear statement of the sensitive memory
- Why saving may help
- Where it will apply
- Who can access it
- How to delete it
- Conservative default action

The safer default should be not saving unless the user explicitly agrees.

## User controls

- Save with defined scope
- Do not save
- Save for this session only
- Edit before saving
- Learn how it will be used
- Open privacy controls

## Edge cases

- Sensitive and non-sensitive details are mixed.
- A user is not authorized to save shared sensitive memory.
- The product cannot reliably classify sensitivity.
- Consent is later revoked.
- Legal or organizational policy requires retention limits.

## Trust risk

The main risk is perceived surveillance or misuse. Sensitive memory requires explicit control and conservative reuse.

## Example product context

A workplace assistant detects a medical scheduling constraint in a planning conversation and asks whether to keep it for this session only instead of saving it as durable memory.
