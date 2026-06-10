# BUG-2 – Fuel filter combination produces inconsistent results

## Severity: Medium (3)

## Description

The fuel type filter produces inconsistent result counts when combining multiple fuel types.

Observed behavior:

- Diesel + CNG combined: 37,984 results
- Diesel alone: 37,982 results
- CNG alone: 0 results

This indicates contradictory aggregation logic in filter combination handling.

## Steps to reproduce

1. Open search page
2. Select fuel type filter
3. Choose Diesel
4. Add CNG
5. Observe result count
6. Compare with individual selections

## Expected result

Combined filters should produce a logically consistent subset of individual filter results.

## Actual result

Combined selection produces inconsistent or contradictory result counts.

## Environment

https://www.hasznaltauto.hu/

## Evidence

See screenshot-image002.png, image003.png, image004.png

## Impact

Reduces trust in filtering accuracy and may confuse users when comparing fuel type options.
