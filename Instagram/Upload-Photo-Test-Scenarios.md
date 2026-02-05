## 📌 Feature: Upload Photo

---

## ✅ Valid Upload Photo Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| IG-UP-001 | Verify valid photo formats (JPG / JPEG / PNG) are accepted | Photo uploads successfully | High |
| IG-UP-002 | Verify uploading photo using "Select from computer" is accepted | Photo uploads successfully | High |
| IG-UP-003 | Verify "Select from computer" button is clickable | File selector opens successfully | High |
| IG-UP-004 | Verify uploading photo using drag and drop is accepted | Photo uploads successfully | Medium |
| IG-UP-005 | Verify uploading a single photo is accepted | Photo uploads successfully | High |
| IG-UP-006 | Verify uploading multiple photos in carousel is accepted | Multiple photos upload successfully | High |
| IG-UP-007 | Verify photo within allowed file size limit is accepted | Photo uploads successfully | High |
| IG-UP-008 | Verify portrait-oriented photo is accepted | Photo uploads successfully | Low |
| IG-UP-009 | Verify landscape-oriented photo is accepted | Photo uploads successfully | Low |
| IG-UP-010 | Verify square photo is accepted | Photo uploads successfully | Low |
| IG-UP-011 | Verify uploaded photos are previewed correctly on crop screen | Photos display correctly | High |
| IG-UP-012 | Verify selecting original aspect ratio is accepted | Original ratio applied successfully | Medium |
| IG-UP-013 | Verify cropping photo to 1:1 aspect ratio is accepted | Crop applied successfully | Medium |
| IG-UP-014 | Verify cropping photo to 4:5 aspect ratio is accepted | Crop applied successfully | Medium |
| IG-UP-015 | Verify cropping photo to 16:9 aspect ratio is accepted | Crop applied successfully | Medium |
| IG-UP-016 | Verify switching between aspect ratios is accepted | Aspect ratio updates successfully | Medium |
| IG-UP-017 | Verify zooming in within allowed limit is accepted | Zoom applied successfully | Medium |
| IG-UP-018 | Verify zooming out within allowed limit is accepted | Zoom applied successfully | Medium |
| IG-UP-019 | Verify repositioning photo inside crop frame is accepted | Photo position updates successfully | Medium |
| IG-UP-020 | Verify photo quality maintained after zoom/crop | Image quality remains acceptable | Medium |
| IG-UP-021 | Verify switching between photos in carousel crop screen is accepted | User switches photos successfully | Medium |
| IG-UP-022 | Verify cropping each photo independently in carousel | Each photo retains individual crop | High |
| IG-UP-023 | Verify adding photo to carousel using (+) icon is accepted | Photo added successfully | High |
| IG-UP-024 | Verify removing photo using (X) icon is accepted | Photo removed successfully | High |
| IG-UP-025 | Verify clicking "Next" navigates to Edit screen | User moves to Edit screen | High |
| IG-UP-026 | Verify crop settings saved when moving to next screen | Crop settings retained | High |
| IG-UP-027 | Verify returning to crop screen retains applied settings | Previous crop settings remain | Medium |
| IG-UP-028 | Verify applying original (no filter) option is accepted | Original view applied | Low |
| IG-UP-029 | Verify applying available filters is accepted | Filter applied successfully | High |
| IG-UP-030 | Verify adjusting filter intensity is accepted | Filter intensity updates successfully | Medium |
| IG-UP-031 | Verify switching between filters is accepted | Filter updates successfully | Medium |
| IG-UP-032 | Verify removing applied filter is accepted | Filter removed successfully | Medium |
| IG-UP-033 | Verify manual photo adjustments are accepted | Adjustments applied successfully | Medium |
| IG-UP-034 | Verify resetting adjustments restores default values | Adjustments reset successfully | Medium |
| IG-UP-035 | Verify applying filter and manual adjustments together | Both changes apply successfully | Medium |
| IG-UP-036 | Verify adding caption up to 2,200 characters is accepted | Caption saved successfully | High |
| IG-UP-037 | Verify emojis allowed in caption | Emojis saved successfully | Low |
| IG-UP-038 | Verify hashtags allowed in caption | Hashtags saved successfully | Low |
| IG-UP-039 | Verify tagging people in caption is accepted | Tagging works successfully | Medium |
| IG-UP-040 | Verify tagging people in photo is accepted | Tags appear correctly | High |
| IG-UP-041 | Verify adding location is accepted | Location added successfully | Medium |
| IG-UP-042 | Verify adding collaborators is accepted | Collaborator added successfully | Medium |
| IG-UP-043 | Verify sharing post to Threads is accepted | Post shared successfully | Low |
| IG-UP-044 | Verify sharing post to Instagram feed is accepted | Post appears in feed | High |
| IG-UP-045 | Verify sharing post to Facebook when account linked is accepted | Post shared successfully | Medium |
| IG-UP-046 | Verify clicking Share publishes post successfully | Post is published | High |
| IG-UP-047 | Verify navigation back between Upload → Crop → Edit is accepted | Navigation works correctly | Medium |
| IG-UP-048 | Verify discard confirmation modal appears when exiting | Confirmation modal displayed | Medium |
| IG-UP-049 | Verify selecting Cancel retains edits | Edits remain saved | Medium |
| IG-UP-050 | Verify selecting Discard removes unsaved changes | Changes removed successfully | Medium |

---

## ❌ Invalid Upload Photo Scenarios

| ID | Test Scenario | Expected Result | Priority |
|------|----------------|-----------------|------------|
| IG-UP-051 | Verify invalid file formats (PDF / DOC / TXT) are rejected | Upload blocked with error message | High |
| IG-UP-052 | Verify executable file formats (EXE) are rejected | Upload blocked with error message | High |
| IG-UP-053 | Verify unsupported image formats (SVG / TIFF) are rejected | Upload blocked with error message | High |
| IG-UP-054 | Verify RAW image formats (CR2 / NEF) are rejected | Upload blocked with error message | Medium |
| IG-UP-055 | Verify photo exceeding max file size is rejected | Upload blocked with error message | High |
| IG-UP-056 | Verify corrupted or unreadable photo file is rejected | Upload blocked with error message | High |
| IG-UP-057 | Verify upload fails when internet connection is lost | Upload fails with notification | High |
| IG-UP-058 | Verify upload rejected on timeout | Upload fails with error message | Medium |
| IG-UP-059 | Verify user cannot proceed when processing fails | Navigation blocked | High |
| IG-UP-060 | Verify proceeding without selecting photo is not allowed | User prevented from continuing | High |
| IG-UP-061 | Verify zoom beyond allowed limits is not allowed | Zoom action blocked | Medium |
| IG-UP-062 | Verify uploading more than allowed number of photos is rejected | Upload blocked | Medium |
| IG-UP-063 | Verify carousel upload rejected if any photo invalid | Upload blocked with error | High |
| IG-UP-064 | Verify caption exceeding 2,200 characters is rejected | Caption validation error displayed | Medium |
| IG-UP-065 | Verify invalid collaborator account rejected | Error message displayed | Medium |
| IG-UP-066 | Verify tagging restricted or blocked user rejected | Tagging blocked | Medium |
| IG-UP-067 | Verify invalid location rejected | Error message displayed | Medium |
| IG-UP-068 | Verify sharing to Facebook without linking account rejected | Sharing blocked with message | Medium |
| IG-UP-069 | Verify posting content violating Instagram policies rejected | Post blocked with policy message | High |

