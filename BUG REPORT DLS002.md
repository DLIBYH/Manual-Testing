### 🐛 Bug Report

**ID:** DLS_TC_002

**Issue:** Missing validation message for mandatory fields.

**Reporting QA:** Nubila

**Date:** 11/02/2025

**Summary:**
When a user tries to update his/her profile, validation message aren't shown for NID and Office Address fields. 
When user clicks on the Update button, updating of profile fails due to not filling NID and Office Address fields.

**Steps To Reproduce**

Steps to reproduce the behavior:
1. Go to any browser
2. Open the website URL "http://etrade.dls.gov.bd/".
3. Login to the system.
4. Click on the Profile from the Sidebar menu.
5. Click on the "Edit" icon
6. Fill in all the mandatory fields.
7. Click on the "Update" button.

**Expected behavior:**
If any mandatory field is not filled up, a validation message should be shown.

**Actual behavior:**
No validation message shown for NID and Office Address even though both are mandatory fields.

**Priority:**
High

**Environment (please complete the following information):**
 - OS: [Windows 10]
 - Browser [Firefox, Chrome, Safari]
 - Version v1.0.1
 - Device [Desktop, Mobile]
