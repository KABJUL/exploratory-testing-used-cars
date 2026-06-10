# BUG-4 – Featured listings override sorting logic

## Severity: Low-Medium (2)

## Description

Featured listings appear to override the selected sorting logic, causing inconsistent ordering in the results list.

Example:

- Item at position 7 is visually highlighted
- Item at position 8 appears above item at position 1 in logical order

## Steps to reproduce

1. Open listing page
2. Apply sorting (e.g. price ascending)
3. Observe featured listings in results

## Expected result

Sorting order should remain consistent regardless of featured status or be clearly separated.

## Actual result

Featured listings disrupt expected sorting order.

## Environment

https://www.hasznaltauto.hu/

## Evidence

See screenshot-image005.png, image006.png

## Impact

Reduces predictability of result ordering and may confuse users navigating sorted lists.
