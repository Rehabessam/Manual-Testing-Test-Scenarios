# Facebook Test Scenarios

## 📌 Feature: Login

---

## ✅ Valid Login Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| FB-LG-001 | Verify login with valid registered email and correct password | User logs in successfully and is redirected to the home page | High |
| FB-LG-002 | Verify login with valid registered phone number and correct password | User logs in successfully and is redirected to the home page | High |
| FB-LG-003 | Verify redirection to home page after successful login | User is redirected to the home page | High |
| FB-LG-004 | Verify no validation error messages appear with valid credentials | No validation errors are displayed | High |
| FB-LG-005 | Verify email/phone field accepts valid email address | System accepts valid email format | Medium |
| FB-LG-006 | Verify email/phone field accepts valid phone number | System accepts valid phone number format | Medium |
| FB-LG-007 | Verify international phone numbers are accepted | System accepts international numbers | Medium |
| FB-LG-008 | Verify copy-paste works in email/phone field | Copy-paste works correctly | Low |
| FB-LG-009 | Verify trimming of leading/trailing spaces in email/phone field | Spaces are removed automatically | Medium |
| FB-LG-010 | Verify password field accepts correct password | Password is accepted | High |
| FB-LG-011 | Verify password field masks characters | Password characters appear masked | High |
| FB-LG-012 | Verify copy-paste works in password field (if allowed) | Copy-paste works correctly | Low |
| FB-LG-013 | Verify login button submits form with valid inputs | Form is submitted successfully | High |
| FB-LG-014 | Verify single click triggers only one login request | Only one login request is sent | Medium |
| FB-LG-015 | Verify login works in different supported languages | Login works correctly in all supported languages | Medium |
| FB-LG-016 | Verify loading indicator appears during login (if applicable) | Loading indicator is displayed | Low |
| FB-LG-017 | Verify "Forgot Password?" redirects to recovery page | User is redirected to password recovery page | Medium |
| FB-LG-018 | Verify "Create New Account" redirects to Sign-Up page | User is redirected to Sign-Up page | Medium |
| FB-LG-019 | Verify Login page loads correctly from Sign-Up page | Login page loads successfully | Low |
| FB-LG-020 | Verify correct URL opens for navigation links | Correct URL is opened | Low |
| FB-LG-021 | Verify login page responsiveness across devices | Page displays correctly on different screen sizes | Medium |

---

## ❌ Invalid Login Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| FB-LG-022 | Verify error when email/phone field is empty | Proper error message is displayed | High |
| FB-LG-023 | Verify error for invalid email format | Error message appears | High |
| FB-LG-024 | Verify error for invalid phone number | Error message appears | High |
| FB-LG-025 | Verify email containing spaces is rejected | Email is rejected with error message | Medium |
| FB-LG-026 | Verify email containing multiple "@" symbols is rejected | Email is rejected with error message | Medium |
| FB-LG-027 | Verify unregistered email/phone is rejected | Appropriate error message appears | High |
| FB-LG-028 | Verify error when password field is empty | Proper error message is displayed | High |
| FB-LG-029 | Verify incorrect password is rejected | Login is blocked and error message appears | High |
| FB-LG-030 | Verify passwords containing only spaces are rejected | Password is rejected with error message | Medium |
| FB-LG-031 | Verify passwords shorter than minimum length are rejected (if validated during login) | Error message appears | Medium |
| FB-LG-032 | Verify login blocked when all mandatory fields are empty | Login submission is blocked | High |
| FB-LG-033 | Verify login blocked when one mandatory field is missing | Login submission is blocked | High |
| FB-LG-034 | Verify validation errors prevent login submission | Form is not submitted | High |
| FB-LG-035 | Verify multiple rapid clicks do not trigger multiple requests | Only one login request is processed | Medium |
| FB-LG-036 | Verify error message appears when credentials are invalid | Appropriate error message is displayed | High |
| FB-LG-037 | Verify error message appears on server error | Proper system error message appears | Medium |
| FB-LG-038 | Verify login blocked when network connection is lost | Login fails with proper notification | Medium |
| FB-LG-039 | Verify application does not crash on login failure | Application remains stable | High |

---

## 📝 Notes
- These scenarios focus on functional and usability validation.
- Scenarios cover positive and negative testing.


