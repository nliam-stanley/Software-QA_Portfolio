# OrangeHRM Exploratory Testing Project

## Project Overview

This project demonstrates exploratory testing performed on the OrangeHRM Human Resource Management System. The objective was to explore the application's functionality, identify defects, and document findings using standard software quality assurance practices.

---

## Project Information

- **Application:** OrangeHRM OS 5.9
- **Testing Type:** Exploratory Testing
- **Platform:** Mobile Browser (Android)
- **Tester:** Nliam Stanley
- **Date:** July 2026

---

## Modules Tested

- Login
- Dashboard
- PIM (Personnel Information Management)
- Recruitment
- Leave
- Time
- Performance
- Directory

---

## Testing Approach

The application was explored without predefined test cases. Different modules were accessed to evaluate usability, functionality, data consistency, navigation, and error handling.

---

## Defects Identified

### Bug 1 – Invalid Credentials Message Persistence
**Severity:** Medium

After entering incorrect credentials, the "Invalid Credentials" error remained visible briefly even after a successful login.

---

### Bug 2 – Incorrect Dashboard Date
**Severity:** High

The dashboard displayed an old punch-out date (March 29) while the current week displayed July 13–19, indicating inconsistent data.

---

### Bug 3 – Dashboard Action Inconsistency
**Severity:** Medium

The dashboard showed pending actions such as "Pending Self Review" and "Candidate to Interview," but the related modules contained no corresponding records.

---

## Recommendations

- Ensure error messages are cleared after successful authentication.
- Synchronize dashboard data with the current system date.
- Display only valid pending actions that correspond to existing records.
- Improve consistency between dashboard widgets and module data.

---

## Skills Demonstrated

- Exploratory Testing
- Bug Identification
- Bug Reporting
- Mobile Web Testing
- Functional Testing
- Usability Testing
- Defect Documentation

---

## Repository Contents

- README.md
- Bug_Report.md
- Test_Summary_Report.md
- Screenshots/

---

## Author

**Nliam Stanley**

Junior Software QA Engineer

GitHub:
https://github.com/nliam-stanley/Software-QA_Portfolio

LinkedIn:
https://www.linkedin.com/in/nliam-stanley-619b0423b
