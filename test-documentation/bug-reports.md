# Bug Reports
---
## BUG-001
Title: Secure page accessable via browser Back button after logout
Environment: Chrome 125, Windows 11
Steps:
1.  Login successfully
2.  Click Logout
3.  Press browser Back button
Actual result: Secure page is displayed
Expected result: User should be redirected to login page
Severity: Major
Priority: High

---

## BUG-002
Title: Error message reveals whether username exists
Steps: 
1. Enter invalid username
2. Enter random password
3. Observe error message
Actual result: Message differs from invalid password case
Expected result: Generic error message for both cases
Severity: Major
Priority: Medium
