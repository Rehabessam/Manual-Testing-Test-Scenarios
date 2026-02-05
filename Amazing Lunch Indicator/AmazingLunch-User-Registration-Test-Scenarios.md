## 📌 Feature: User Registration

---

## ✅ User Registration Valid Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| UR-V-01 | Validate successful registration with valid mandatory fields only | User is registered successfully using mandatory fields only | High |
| UR-V-02 | Validate successful registration with valid mandatory and optional fields | User is registered successfully with all fields filled | High |
| UR-V-03 | Validate registration with various valid username formats | System accepts valid username formats | Medium |
| UR-V-04 | Validate registration with various valid e-mail address formats | System accepts valid email formats | High |
| UR-V-05 | Validate registration with various valid password formats | System accepts passwords that meet complexity rules | High |
| UR-V-06 | Validate registration with various valid phone number formats | System accepts valid phone number formats | Medium |
| UR-V-07 | Validate redirect to the search page after successful registration | User is redirected to the search page | High |
| UR-V-08 | Validate registration with minimum allowed field lengths | Registration succeeds with minimum valid input lengths | Medium |
| UR-V-09 | Validate registration with maximum allowed field lengths | Registration succeeds with maximum valid input lengths | Medium |
| UR-V-10 | Validate registration with international phone formats (+20, +966, etc.) | International phone formats are accepted | Medium |
| UR-V-11 | Validate whitespace is trimmed from input fields | Leading and trailing spaces are trimmed automatically | Low |
| UR-V-12 | Validate auto-login after successful registration | User is logged in automatically after registration | Medium |

---

## ❌ User Registration Invalid Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| UR-I-01 | Validate registration with missing mandatory fields | Registration is blocked and validation messages are displayed | High |
| UR-I-02 | Validate registration with an invalid e-mail address format | Error message is displayed for invalid email | High |
| UR-I-03 | Validate registration with a duplicate username | Registration is rejected with appropriate error message | High |
| UR-I-04 | Validate registration with an invalid password (not meeting complexity rules) | Password validation error is displayed | High |
| UR-I-05 | Validate registration with an invalid phone number format | Error message is displayed for invalid phone number | Medium |
| UR-I-06 | Validate registration without accepting terms and conditions (if applicable) | Registration is blocked until terms are accepted | Medium |
| UR-I-07 | Validate registration with special characters in the username | Username is rejected with validation message | Medium |
| UR-I-08 | Validate registration when the e-mail address already exists | Registration is rejected with duplicate email error | High |
| UR-I-09 | Validate registration when internet connection is lost | Proper error message is displayed and registration fails safely | High |
| UR-I-10 | Validate registration with input exceeding maximum length | Input is rejected or error message is displayed | Medium |
| UR-I-11 | Validate registration with only whitespace in required fields | Registration is blocked with validation errors | High |
| UR-I-12 | Validate registration with password and confirm password mismatch | Error message is displayed indicating mismatch | High |
| UR-I-13 | Validate registration with SQL injection attempts | Input is rejected and system remains secure | High |

---

## ⚠️ User Registration Edge / Boundary Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| UR-E-01 | Validate registration when entering minimum allowed characters for username | Registration succeeds without validation errors | Medium |
| UR-E-02 | Validate registration when entering maximum allowed characters for username | Registration succeeds without system issues | Medium |
| UR-E-03 | Validate registration when entering minimum allowed password length | Password is accepted and registration succeeds | Medium |
| UR-E-04 | Validate registration when entering maximum allowed password length | Password is accepted and stored correctly | Medium |
| UR-E-05 | Validate registration when entering minimum allowed phone number length | Phone number is accepted | Low |
| UR-E-06 | Validate registration when entering maximum allowed phone number length | Phone number is accepted | Low |
| UR-E-07 | Validate registration when switching input language (Arabic / English) | Input is handled correctly without errors | Low |
| UR-E-08 | Validate registration when user submits the form very quickly | System processes registration correctly | Medium |
| UR-E-09 | Validate registration when navigating back during submission | No duplicate account is created | High |
| UR-E-10 | Validate registration when browser refreshes during submission | System handles refresh safely without data corruption | High |

---

## ⚡ User Registration Performance Scenarios

| ID | Test Scenario | Expected Result | Priority |
|----|---------------|----------------|----------|
| UR-P-01 | Measure registration response time with valid data | Registration completes within acceptable response time | Medium |
| UR-P-02 | Validate system performance during peak registration times | System remains responsive without errors | Medium |
| UR-P-03 | Validate registration under slow internet connection | Proper loading indicators appear without freezing | Medium |
| UR-P-04 | Validate registration when multiple users register simultaneously | System handles concurrent registrations correctly | Medium |
| UR-P-05 | Validate system stability during repeated registration attempts | No memory leaks, crashes, or performance degradation | Low |
