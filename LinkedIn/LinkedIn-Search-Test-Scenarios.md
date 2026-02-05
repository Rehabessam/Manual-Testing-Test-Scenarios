## 📌 Feature: Search

---

## ✅ Valid Search Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| LI-SR-001 | Verify search results displayed when searching valid person name | Relevant people results displayed | High |
| LI-SR-002 | Verify search results displayed using partial name | Relevant results displayed | High |
| LI-SR-003 | Verify search results displayed when searching valid job title | Relevant job results displayed | High |
| LI-SR-004 | Verify search results displayed when searching valid company name | Relevant company results displayed | High |
| LI-SR-005 | Verify relevant results displayed when searching using keywords | Relevant results displayed across categories | High |
| LI-SR-006 | Verify search works correctly using uppercase letters | Results displayed correctly | Medium |
| LI-SR-007 | Verify search works correctly using lowercase letters | Results displayed correctly | Medium |
| LI-SR-008 | Verify search triggered when pressing Enter key | Search results displayed | High |
| LI-SR-009 | Verify search triggered when clicking "See all results" | Full search results page displayed | High |
| LI-SR-010 | Verify user can switch between tabs (People, Jobs, Companies, Posts, Groups, Products, etc.) | Results displayed correctly for selected tab | High |

---

## ❌ Invalid Search Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| LI-SR-011 | Verify no results displayed when searching random characters | No results or "No results found" message displayed | High |
| LI-SR-012 | Verify system processes special characters without errors | System handles input without crash | Medium |
| LI-SR-013 | Verify system stability when entering unexpected characters | Application remains stable | High |
| LI-SR-014 | Verify numeric-only search input handled correctly | Appropriate results or message displayed | Medium |
| LI-SR-015 | Verify behavior when searching with empty field | Search not triggered or suggestion displayed | High |
| LI-SR-016 | Verify search does not return irrelevant results for invalid keywords | Results remain relevant or empty | High |
| LI-SR-017 | Verify system stability with very long search input | System remains stable and responsive | Medium |
| LI-SR-018 | Verify filters do not cause errors when results empty | Filters apply safely without crash | Medium |
| LI-SR-019 | Verify clear/remove option disabled when search history empty | Clear option remains disabled | Low |

---

## ⚠️ Edge / Boundary Search Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| LI-SR-020 | Verify search behavior with single character input | Appropriate suggestions or results displayed | Medium |
| LI-SR-021 | Verify search behavior with minimum allowed characters | Results displayed correctly | Medium |
| LI-SR-022 | Verify search behavior with maximum allowed characters | Results displayed without system failure | Medium |
| LI-SR-023 | Verify search behavior with leading spaces | Spaces trimmed and results displayed correctly | Medium |
| LI-SR-024 | Verify search behavior with trailing spaces | Spaces trimmed and results displayed correctly | Medium |
| LI-SR-025 | Verify search behavior with mixed language input | Results displayed correctly | Medium |
| LI-SR-026 | Verify search behavior when keywords changed rapidly | Results update correctly without crash | Medium |
| LI-SR-027 | Verify search behavior when filters repeatedly applied/removed | Results update correctly without crash | Medium |

---

## 🎨 UI & Usability Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| LI-SR-028 | Verify search bar visibility on page | Search bar clearly visible | High |
| LI-SR-029 | Verify placeholder text displayed correctly | Placeholder text visible and readable | Low |
| LI-SR-030 | Verify search suggestions appear while typing | Suggestions displayed dynamically | High |
| LI-SR-031 | Verify search results displayed in readable format | Results layout clear and user-friendly | High |
| LI-SR-032 | Verify applied filters clearly visible | Active filters displayed clearly | Medium |
| LI-SR-033 | Verify filters can be removed easily | Filters removable without issues | Medium |
| LI-SR-034 | Verify user can clear search history when available | History cleared successfully | Low |

