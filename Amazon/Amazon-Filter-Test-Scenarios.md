## 📌 Feature: Product Filters

---

## ✅ Filter Valid Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| AF-V-01 | Filter products by selected category | Only products from the selected category are displayed | High |
| AF-V-02 | Filter products by selected brand | Only products from the selected brand are displayed | High |
| AF-V-03 | Filter products by selected price range | Only products within the selected price range are displayed | High |
| AF-V-04 | Filter products by customer rating | Only products with the selected rating or higher are displayed | Medium |
| AF-V-05 | Apply multiple filters together (Brand + Price + Rating) | Products matching all selected filters are displayed | High |
| AF-V-06 | Verify product count after applying filters | Number of displayed products decreases | Medium |
| AF-V-07 | Verify filter accuracy | No unrelated products are displayed | High |
| AF-V-08 | Apply filters immediately after selection | Filters are applied without delay | Medium |
| AF-V-09 | Verify applied filters visibility | Applied filters are clearly visible | Low |
| AF-V-10 | Persist filters while navigating pages | Filter selection remains applied | Medium |
| AF-V-11 | Persist filters after page refresh (if supported) | Filters remain applied | Low |
| AF-V-12 | Filters with sponsored products | Sponsored products respect filters | Medium |
| AF-V-13 | Filters with sorting applied | Filters and sorting work together correctly | Medium |
| AF-V-14 | Filters on different screen sizes | Filters work correctly on desktop and mobile | Medium |

---

## ❌ Filter Invalid Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| AF-I-01 | Apply filters with no matching products | No products are displayed | High |
| AF-I-02 | No results message is shown | “No results found” message is displayed | Medium |
| AF-I-03 | Verify no unrelated products appear | No unrelated products are shown | High |
| AF-I-04 | Apply and remove filters repeatedly | System behaves correctly without errors | Medium |
| AF-I-05 | Apply conflicting filters | System handles conflicts correctly | High |
| AF-I-06 | Click “Clear all” filters | All filters are removed | High |
| AF-I-07 | Restore product list after clearing filters | Original product list is restored | High |
| AF-I-08 | Apply filters without selecting any option | No filter is applied | Low |
| AF-I-09 | Invalid filter combinations | No system crash or error occurs | High |

---

## ⚠️ Filter Edge / Boundary Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| AF-E-01 | Select minimum price boundary | Products at minimum price are displayed | Low |
| AF-E-02 | Select maximum price boundary | Products at maximum price are displayed | Low |
| AF-E-03 | Filter resulting in one product | Single product is displayed correctly | Low |
| AF-E-04 | Select all available filter options | System handles all filters correctly | Medium |
| AF-E-05 | Rapid filter selection/deselection | System remains responsive | Medium |
| AF-E-06 | Apply filters on last page | Filters work without navigation issues | Low |
| AF-E-07 | Navigate back after filters applied | Filter state is retained or reset correctly | Low |

---

## 🎨 Filter UI & Usability Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| AF-U-01 | Filter options visibility | Filters are clearly visible and readable | Low |
| AF-U-02 | Selected filters highlight | Selected filters are visually highlighted | Low |
| AF-U-03 | Remove filters individually | Each filter can be removed independently | Medium |
| AF-U-04 | “Clear all” button visibility | Button is visible and clickable | Low |
| AF-U-05 | Filter naming clarity | Filter labels are clear and understandable | Low |
| AF-U-06 | Keyboard accessibility | Filters are accessible via keyboard | Low |
| AF-U-07 | Expand/collapse filter sections | Sections expand and collapse correctly | Low |
| AF-U-08 | Filters layout | Filters do not overlap product listings | Low |

---

## ⚡ Filter Performance Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| AF-P-01 | Filter response time | Filters are applied within acceptable time | Medium |
| AF-P-02 | Multiple filters performance | System performs well with multiple filters | Medium |
| AF-P-03 | UI responsiveness during filtering | No page lag or freezing occurs | Medium |
| AF-P-04 | Filters under slow network | Filters work without crash or timeout | Medium |
| AF-P-05 | Stability under heavy usage | System remains stable | Low |
