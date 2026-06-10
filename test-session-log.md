www.hasznaltauto.hu

# Exploratory Test Session Log – TC-1

**Date:** 2026-04-29  
**Duration:** 40 minutes  
**Tester:** Julia Kabodi  
**Target:** https://www.hasznaltauto.hu/

## Areas Tested

- Brand search
- Model search
- Fuel type filtering
- Price filtering
- Year filtering
- Sorting behavior
- Combined filters
- Edge cases (invalid / extreme inputs)
- Empty result handling

## Observations

Search and filtering features are generally functional, and combinations reduce result sets correctly.

However, multiple inconsistencies were observed:

- Result counts differ across UI elements
- Some filter combinations produce contradictory outputs
- Sorting logic does not always match selected criteria
- Edge case inputs produce unclear or inconsistent behavior

## Impact

Issues do not block functionality but may confuse users and reduce trust in results accuracy.
