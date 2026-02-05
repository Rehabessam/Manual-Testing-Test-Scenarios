## 📌 Feature: Upload CV

---

## ✅ Valid Upload CV Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| WZ-CV-001 | Verify supported CV formats (PDF / DOC / DOCX) are accepted | CV uploaded successfully | High |
| WZ-CV-002 | Verify uppercase/lowercase file extensions are accepted | CV uploaded successfully | Medium |
| WZ-CV-003 | Verify mixed-case file extensions are accepted | CV uploaded successfully | Medium |
| WZ-CV-004 | Verify CV file with minimum allowed file size is accepted | CV uploaded successfully | Medium |
| WZ-CV-005 | Verify CV file within allowed size limit (≤ 5MB) is accepted | CV uploaded successfully | High |
| WZ-CV-006 | Verify CV file with maximum allowed size (5MB) is accepted | CV uploaded successfully | High |
| WZ-CV-007 | Verify CV upload using "Browse / Upload Your CV" button | CV uploaded successfully | High |
| WZ-CV-008 | Verify CV upload using drag and drop | CV uploaded successfully | Medium |
| WZ-CV-009 | Verify CV accepted regardless of file name | CV uploaded successfully | Low |
| WZ-CV-010 | Verify CV with special characters in file name accepted | CV uploaded successfully | Low |
| WZ-CV-011 | Verify system allows uploading only one CV file | Only one CV stored successfully | High |
| WZ-CV-012 | Verify loading indicator displayed during upload | Loading indicator visible until upload completes | Medium |
| WZ-CV-013 | Verify success confirmation message appears after upload | Success message displayed to user | Medium |
| WZ-CV-014 | Verify user can replace existing CV with a new file | Old CV replaced successfully | High |
| WZ-CV-015 | Verify user can delete uploaded CV | CV removed successfully | Medium |
| WZ-CV-016 | Verify uploaded CV can be previewed or downloaded | CV preview/download works correctly | Medium |

---

## ❌ Invalid Upload CV Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| WZ-CV-017 | Verify unsupported file formats (JPG / PNG) are rejected | Error message displayed and upload blocked | High |
| WZ-CV-018 | Verify executable files (EXE) are rejected | Upload blocked with validation message | High |
| WZ-CV-019 | Verify compressed files (ZIP / RAR) are rejected | Upload blocked with validation message | High |
| WZ-CV-020 | Verify script files (JS / HTML) are rejected | Upload blocked with validation message | High |
| WZ-CV-021 | Verify files with multiple extensions (cv.pdf.exe) are rejected | Upload blocked with validation message | High |
| WZ-CV-022 | Verify renamed executable files (EXE renamed to PDF) are rejected | Upload blocked after validation | High |
| WZ-CV-023 | Verify files smaller than minimum allowed size are rejected | Error message displayed | Medium |
| WZ-CV-024 | Verify files exceeding maximum allowed size (>5MB) are rejected | Error message displayed | High |
| WZ-CV-025 | Verify zero size file (0 KB) is rejected | Upload blocked with validation message | High |
| WZ-CV-026 | Verify corrupted or unreadable CV file rejected | Upload blocked with error message | High |
| WZ-CV-027 | Verify system prevents uploading multiple CV files | User restricted to one file only | High |
| WZ-CV-028 | Verify upload fails when internet connection lost during upload | Upload fails with appropriate error message | High |
| WZ-CV-029 | Verify upload resumes or restarts after internet restored (if supported) | Upload resumes or restarts correctly | Medium |
| WZ-CV-030 | Verify system stability with slow internet connection | System remains responsive without crash | Medium |

---

## 🔐 Security Test Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| WZ-CV-031 | Verify virus-infected CV files are rejected | Upload blocked after security scan | High |
| WZ-CV-032 | Verify system scans file content and not only file extension | Malicious files rejected | High |
| WZ-CV-033 | Verify file containing embedded scripts or macros is handled securely | Upload blocked or sanitized | High |

---

## ⚡ Performance Test Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| WZ-CV-034 | Verify upload performance for CV file near 5MB limit | Upload completes within acceptable time | Medium |
| WZ-CV-035 | Verify system handles multiple users uploading CVs simultaneously | System remains stable and responsive | Medium |

---

## 🎯 Usability Test Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| WZ-CV-036 | Verify clear error messages displayed for rejected uploads | User understands upload failure reason | High |
| WZ-CV-037 | Verify upload progress indicator displays percentage | Upload progress visible to user | Medium |
| WZ-CV-038 | Verify uploaded CV file name displayed correctly after upload | File name shown accurately | Medium |

---

## ♿ Accessibility Test Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| WZ-CV-039 | Verify upload button accessible via keyboard navigation | User can upload using keyboard only | Medium |
| WZ-CV-040 | Verify upload status readable using screen reader | Screen reader announces upload status correctly | Medium |

