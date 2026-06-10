# BUG-5 – Invalid range handling in total weight filter

## Severity: Medium (3)

## Description

The total weight filter does not properly handle invalid input ranges where minimum value is greater than maximum value.

## Steps to reproduce

1. Open filter panel (e.g. boats section)
2. Locate total weight filter
3. Enter minimum value higher than maximum value
4. Apply filter

## Expected result

System should validate input and prevent invalid range submission or display an error message.

## Actual result

Filter accepts invalid range and produces unclear or unexpected results.

## Environment

https://www.hasznaltauto.hu/

## Impact

May lead to incorrect filtering behavior and confusion in advanced search scenarios.
