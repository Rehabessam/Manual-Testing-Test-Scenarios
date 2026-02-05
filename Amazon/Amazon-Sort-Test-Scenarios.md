## 📌 Feature: Sort Products (Amazon)

---

## ✅ Sort – Valid Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| AM-SORT-001 | Verify products are sorted by Price: Low to High | Products displayed in ascending price order | High |
| AM-SORT-002 | Verify products are sorted by Price: High to Low | Products displayed in descending price order | High |
| AM-SORT-003 | Verify products are sorted by Average Customer Review | Products sorted by highest rating first | High |
| AM-SORT-004 | Verify products are sorted by Newest Arrivals | Recently added products displayed first | Medium |
| AM-SORT-005 | Verify products are sorted by Best Sellers | Best-selling products displayed first | Medium |
| AM-SORT-006 | Verify sort option is applied immediately after selection | Products update without page errors | High |
| AM-SORT-007 | Verify loading indicator appears while sorting is applied (if applicable) | Loading indicator shown correctly | Medium |
| AM-SORT-008 | Verify sorting works correctly with applied filters | Sorting respects active filters | High |
| AM-SORT-009 | Verify sorting works correctly with search results | Search results sorted correctly | High |

---

## ❌ Sort – Invalid / Negative Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| AM-SORT-010 | Verify sorting behavior when no products are available | Empty state message displayed without error | High |
| AM-SORT-011 | Verify sort options behave correctly when no products are available | Sort options disabled or handled gracefully | Medium |
| AM-SORT-012 | Verify sorting behavior when only one product is displayed | Product remains unchanged | Medium |
| AM-SORT-013 | Verify sorting behavior after navigating between result pages | Sorting remains consistent across pages | High |
| AM-SORT-014 | Verify selected sort option is preserved after opening a product and returning | Previously selected sort option remains applied | High |
| AM-SORT-015 | Verify sorting behavior when changing sort options multiple times rapidly | Correct sorting applied without glitches | Medium |
| AM-SORT-016 | Verify sorting works correctly with a large number of products | Products sorted accurately without performance issues | High |
| AM-SORT-017 | Verify system behavior when sort request fails (server error) | Proper error handling without page crash | Medium |

---

## 🔄 Sort – Edge / Boundary Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| AM-SORT-018 | Verify sorting behavior with products having the same price | Products grouped correctly without duplication | Medium |
| AM-SORT-019 | Verify sorting behavior with products having the same rating | Stable sorting maintained | Medium |
| AM-SORT-020 | Verify sorting behavior when products have missing price or rating | Products handled gracefully | Medium |

---

## 🎯 Sort – UI & Usability Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| AM-SORT-021 | Verify sort dropdown is clearly visible and accessible | Sort control visible and usable | Medium |
| AM-SORT-022 | Verify currently selected sort option is highlighted | Selected option clearly indicated | Medium |
| AM-SORT-023 | Verify sort options are readable and not truncated | All sort labels displayed correctly | Low |

---

## ⚡ Sort – Performance Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| AM-SORT-024 | Verify sorting response time with large result sets | Sorting completes within acceptable time | Medium |
| AM-SORT-025 | Verify no UI freeze during sorting | Page remains responsive | Medium |

