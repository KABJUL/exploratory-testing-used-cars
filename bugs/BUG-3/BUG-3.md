# BUG-3 – Ambiguous sorting logic for price sorting

## Severity: Medium (3)

## Description

Price-based sorting does not clearly define whether sorting is based on net price, gross price, or discounted price, resulting in misleading ordering.

## Steps to reproduce

1. Open vehicle listing page
2. Navigate to bus listings
3. Apply sorting by price (ascending/descending)
4. Observe order of results

## Expected result

Sorting should follow a clearly defined pricing logic (net or gross consistently applied).

## Actual result

Sorting appears inconsistent, with no clear indication of pricing basis.

## Environment

https://www.hasznaltauto.hu/

## Impact

Users may misinterpret pricing order, leading to incorrect comparisons between listings.
