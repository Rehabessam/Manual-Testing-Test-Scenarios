# Facebook Test Scenarios

## 📌 Feature: Sign Up

---

## ✅ Valid Sign Up Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| FB-SU-001 | Verify sign-up is successful when all mandatory fields are filled with valid data | User account is created successfully | High |
| FB-SU-002 | Verify Sign-Up works correctly in different supported languages | Sign-Up process works in all supported languages | Medium |
| FB-SU-003 | Verify no validation error messages appear for valid data | No validation errors are displayed | High |
| FB-SU-004 | Verify redirection to next step after successful sign-up | User is redirected to next step or confirmation page | High |
| FB-SU-005 | Verify First Name and Surname accept valid alphabetic characters | System accepts valid names | High |
| FB-SU-006 | Verify First Name and Surname accept minimum allowed characters (2) | Names are accepted | Medium |
| FB-SU-007 | Verify First Name and Surname accept maximum allowed characters (50) | Names are accepted | Medium |
| FB-SU-008 | Verify trimming of leading/trailing spaces in name fields | Spaces are removed automatically | Medium |
| FB-SU-009 | Verify mixed-case characters are accepted in name fields | Mixed-case names are accepted | Low |
| FB-SU-010 | Verify valid Date of Birth meeting minimum age requirement is accepted | Date is accepted and validation passes | High |
| FB-SU-011 | Verify sign-up works when age equals minimum allowed age | Account is created successfully | High |
| FB-SU-012 | Verify leap-year dates are accepted | Valid leap-year dates are accepted | Medium |
| FB-SU-013 | Verify changing Date of Birth updates age validation | Age validation updates correctly | Medium |
| FB-SU-014 | Verify date selection from dropdown works correctly | Date is selected successfully | Low |
| FB-SU-015 | Verify only one gender option can be selected at a time | Only one option remains selected | High |
| FB-SU-016 | Verify switching between gender options works correctly | Gender selection updates correctly | Medium |
| FB-SU-017 | Verify selecting Custom gender opens additional options (if applicable) | Additional fields appear correctly | Medium |
| FB-SU-018 | Verify gender selection is mandatory (if required) | User cannot proceed without selecting gender | High |
| FB-SU-019 | Verify sign-up using valid unregistered email address | Account is created successfully | High |
| FB-SU-020 | Verify sign-up using valid mobile number with country code | Account is created successfully | High |
| FB-SU-021 | Verify international mobile numbers are accepted | Mobile number is accepted | Medium |
| FB-SU-022 | Verify copy-paste works in email and mobile fields | Copy-paste functions correctly | Low |
| FB-SU-023 | Verify trimming spaces in email and mobile inputs | Spaces are removed automatically | Medium |
| FB-SU-024 | Verify password meeting complexity rules is accepted | Password is accepted | High |
| FB-SU-025 | Verify password minimum length is accepted (6 characters) | Password is accepted | Medium |
| FB-SU-026 | Verify password maximum length is accepted | Password is accepted | Medium |
| FB-SU-027 | Verify password with uppercase, lowercase, numbers, and symbols is accepted | Password is accepted | High |
| FB-SU-028 | Verify password field masks characters | Password is masked | High |
| FB-SU-029 | Verify Sign-Up button submits valid form successfully | Form is submitted successfully | High |
| FB-SU-030 | Verify single click triggers only one Sign-Up request | Only one request is sent | Medium |
| FB-SU-031 | Verify loading indicator appears during submission (if applicable) | Loading indicator is displayed | Low |
| FB-SU-032 | Verify Sign-Up page responsiveness across devices | Page displays correctly on all devices | Medium |
| FB-SU-033 | Verify "Already have an account?" redirects to Login page | User is redirected to Login page | Medium |
| FB-SU-034 | Verify Login page loads successfully after clicking link | Login page loads correctly | Low |
| FB-SU-035 | Verify correct Login page URL opens | Correct URL is opened | Low |
| FB-SU-036 | Verify Login navigation works in supported languages | Navigation works correctly | Low |
| FB-SU-037 | Verify clicking Login link does not submit Sign-Up form | Sign-Up form remains unsubmitted | Medium |
| FB-SU-038 | Verify Sign-Up data is not retained after navigating to Login (if expected) | Form data is cleared | Low |
| FB-SU-039 | Verify Login link is clickable and visually highlighted on hover | Link interaction works correctly | Low |
| FB-SU-040 | Verify first name containing apostrophe is accepted | Name is accepted | Medium |

---

## ❌ Invalid Sign Up Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| FB-SU-041 | Verify error when First Name or Surname is empty | Proper error message is displayed | High |
| FB-SU-042 | Verify numeric characters are rejected in name fields | Input is rejected with error message | High |
| FB-SU-043 | Verify special characters are rejected in name fields | Input is rejected with error message | High |
| FB-SU-044 | Verify names containing only spaces are rejected | Error message appears | High |
| FB-SU-045 | Verify names exceeding max length (>50 characters) are rejected | Error message appears | Medium |
| FB-SU-046 | Verify emojis are rejected in name fields | Input is rejected | Medium |
| FB-SU-047 | Verify error when Date of Birth is not selected | Proper error message is displayed | High |
| FB-SU-048 | Verify sign-up blocked when age is below minimum allowed | Account creation is blocked | High |
| FB-SU-049 | Verify future dates are rejected as Date of Birth | Error message appears | High |
| FB-SU-050 | Verify invalid date combinations are rejected (e.g., 30 Feb) | Error message appears | Medium |
| FB-SU-051 | Verify 29 February rejected for non-leap years | Error message appears | Medium |
| FB-SU-052 | Verify error when gender is not selected | Proper error message is displayed | High |
| FB-SU-053 | Verify Custom gender without required fields is rejected | Error message appears | Medium |
| FB-SU-054 | Verify error when email field is empty | Proper error message is displayed | High |
| FB-SU-055 | Verify invalid email format is rejected | Error message appears | High |
| FB-SU-056 | Verify email without '@' symbol is rejected | Error message appears | High |
| FB-SU-057 | Verify email with multiple '@' symbols is rejected | Error message appears | Medium |
| FB-SU-058 | Verify email without valid domain is rejected | Error message appears | High |
| FB-SU-059 | Verify email containing spaces is rejected | Error message appears | Medium |
| FB-SU-060 | Verify registered email is rejected | Proper error message is displayed | High |
| FB-SU-061 | Verify error when mobile number is empty | Proper error message is displayed | High |
| FB-SU-062 | Verify invalid mobile number format is rejected | Error message appears | High |
| FB-SU-063 | Verify mobile number containing letters is rejected | Error message appears | Medium |
| FB-SU-064 | Verify mobile number shorter than allowed length is rejected | Error message appears | Medium |
| FB-SU-065 | Verify mobile number longer than allowed length is rejected | Error message appears | Medium |
| FB-SU-066 | Verify registered mobile number is rejected | Proper error message is displayed | High |
| FB-SU-067 | Verify error when password field is empty | Proper error message is displayed | High |
| FB-SU-068 | Verify passwords shorter than minimum length are rejected | Error message appears | High |
| FB-SU-069 | Verify passwords longer than maximum length are rejected | Error message appears | Medium |
| FB-SU-070 | Verify passwords not meeting complexity requirements are rejected | Error message appears | High |
| FB-SU-071 | Verify passwords containing only spaces are rejected | Error message appears | Medium |
| FB-SU-072 | Verify weak/common passwords are rejected | Error message appears | Medium |
| FB-SU-073 | Verify sign-up blocked when mandatory fields are missing | Submission is blocked | High |
| FB-SU-074 | Verify validation errors prevent form submission | Form is not submitted | High |
| FB-SU-075 | Verify submission blocked when network connection is lost | Proper error notification appears | Medium |
| FB-SU-076 | Verify server error message is displayed correctly | System error message appears | Medium |
| FB-SU-077 | Verify Login link does not trigger validation errors when fields empty | User navigates without validation | Low |
| FB-SU-078 | Verify Login link does not show validation when some fields are filled | No validation errors displayed | Low |
| FB-SU-079 | Verify clicking Login during submission does not crash application | Application remains stable | Medium |
| FB-SU-080 | Verify Login link is not broken and does not lead to error page | Correct page loads | Low |
| FB-SU-081 | Verify multiple clicks on Login link do not open multiple pages | Only one page opens | Low |
| FB-SU-082 | Verify Login link accessibility on small screens | Link remains accessible | Low |

