# Dog-profile ranking guide

## Goal

Offer an understandable ordering of approved dog profiles. Ranking is a conversation starter, never an adoption decision.

## Inputs

The current match flow asks about:

1. Whether the visitor wants a dog or a cat.
2. Other resident animals.
3. Children in the household.
4. Daily activity.
5. Home environment.

Only the dog path ranks dog profiles. A cat choice must not return dog recommendations until cat profiles have been supplied and reviewed.

## Rules

1. **Exclude only documented incompatibilities.** For example, a dog marked not compatible with cats is excluded when cats live in the household.
2. **Keep unknowns.** Do not assume they are suitable or unsuitable; label the result “Laten we samen kijken.”
3. **Score documented alignment.** Known compatibility with a resident dog, cat, or children earns three points; a matching activity or environment earns two points.
4. **Sort by score.** Use the dog’s name only as a stable tie-breaker.
5. **Do not add hidden signals.** Photos, breed guesses, age assumptions, or incomplete notes must not affect rank.

## Data quality check

Before publishing a profile, verify its compatibility values are `yes`, `no`, or `unknown`; its energy is `low`, `medium`, `high`, or `unknown`; and every statement maps to an approved source.

## Human review

The adoption team has the final say. Any important unknown, medical requirement, behavior concern, or special placement need belongs on the official profile and in the adoption conversation.
