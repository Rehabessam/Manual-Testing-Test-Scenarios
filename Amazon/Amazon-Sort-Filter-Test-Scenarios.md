## 📌 Feature: Sort & Filter Integration

---

## ✅ Valid Sort & Filter Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| SF-V-01 | Verify that sorting works correctly after applying filters | Products are sorted correctly based on the selected sort option while filters remain applied | High |
| SF-V-02 | Verify that filters work correctly after applying sorting | Filters are applied correctly without affecting the selected sort order | High |
| SF-V-03 | Verify that changing the sort order does not reset applied filters | Applied filters remain active after changing sort order | High |
| SF-V-04 | Verify that removing filters keeps the selected sort order | Selected sort option remains unchanged after removing filters | Medium |
| SF-V-05 | Verify that sort and filter work together without breaking the product listing | Product list updates correctly without errors or missing products | High |

---

## ❌ Invalid Sort & Filter Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| SF-I-01 | Apply sorting when no products are returned after filtering | Sorting is disabled or handled gracefully without errors | Medium |
| SF-I-02 | Apply invalid or unsupported sort option | System ignores the option or shows a proper message | Low |
| SF-I-03 | Rapidly switch between different sort options after filtering | System does not crash or display incorrect results | High |
| SF-I-04 | Remove sorting while filters are active | Filters remain applied correctly | Medium |
| SF-I-05 | Apply filters while an invalid sort state exists | Product list loads correctly without UI or data issues | High |

---

## ⚠️ Edge / Boundary Sort & Filter Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| SF-E-01 | Apply sort and filter resulting in a single product | Product is displayed correctly | Low |
| SF-E-02 | Apply sort and filter resulting in the last page of results | Pagination and product list behave correctly | Medium |
| SF-E-03 | Apply minimum filter value with different sort options | Sorting works correctly at boundary values | Low |
| SF-E-04 | Apply maximum filter value with different sort options | Sorting works correctly at boundary values | Low |
| SF-E-05 | Quickly apply and remove both sort and filter options | System remains stable and responsive | Medium |

---

## ⚡ Performance Sort & Filter Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| SF-P-01 | Measure response time when applying sort after filters | Sorting is applied within acceptable response time | Medium |
| SF-P-02 | Measure response time when applying filters after sorting | Filters are applied without noticeable delay | Medium |
| SF-P-03 | Apply sort and filter under slow network conditions | System does not freeze or crash | Medium |
| SF-P-04 | Apply multiple sort and filter changes continuously | UI remains responsive without lag | Medium |
| SF-P-05 | System stability under heavy usage of sort & filter | No performance degradation or errors occur | Low |
