# 🧪 QA Test Report — [Feature / Project Name]

> [!NOTE]
> This document is used to document QA testing, test cases, test results, and issues found during testing.
>
> The testing approach can be adapted depending on the project scope, risk, and client requirements.

---

## 📋 Test Information

| **Item** | **Details** |
|---|---|
| **Project / Feature** | `[Project / Feature Name]` |
| **Version / Release** | `[Version / Build]` |
| **Tester** | `[Name]` |
| **Date** | `[YYYY-MM-DD]` |
| **Environment** | `[Staging / Production / Local]` |
| **Browser / Device** | `[Chrome / Safari / iPhone / Android]` |

---

## 🎯 Test Objective

**What are we testing?**

[Briefly describe the feature, functionality, or change being tested.]

**Why are we testing it?**

[Briefly describe the purpose of the testing.]

### Scope

**In scope:**

- [Feature / functionality]
- [Feature / functionality]
- [Feature / functionality]

**Out of scope:**

- [Feature / functionality]
- [Feature / functionality]

---

## 📝 Test Approach

### Functional Testing

- ☐ Smoke Testing — Verify that the most important functionality works.
- ☐ Sanity Testing — Verify a specific change or bug fix.
- ☐ Functional Testing — Verify features against expected behavior.
- ☐ Integration Testing — Verify interaction between systems/modules.
- ☐ Acceptance Testing — Verify that requirements and business expectations are met.
- ☐ Regression Testing — Verify that existing functionality still works.

### Non-Functional Testing

- ☐ Performance Testing
- ☐ Load Testing
- ☐ Stress Testing
- ☐ Security Testing
- ☐ Accessibility Testing
- ☐ Cross-browser / Cross-device Testing

> [!TIP]
> Only select the testing types that are relevant to the project.

---

# 🧪 Feature Testing

## Test Case Summary

| **ID** | **Test Case** | **Expected Result** | **Actual Result** | **Evidence** | **Status** |
|---|---|---|---|---|---|
| `TC-001` | Login with valid credentials | User is successfully logged in. | User logged in successfully. | 📎 [Screenshot](#) | 🟢 **PASS** |
| `TC-002` | Login with invalid password | Error message is displayed. | Error message displayed correctly. | 📎 [Screenshot](#) | 🟢 **PASS** |
| `TC-003` | Password reset | Reset email is received. | Email was not received. | 📎 [Screenshot](#) | 🔴 **FAIL** |
| `TC-004` | Logout | User is logged out successfully. | Not tested. | — | ⚪ **NOT TESTED** |

### Test Result Legend

| **Status** | **Meaning** |
|---|---|
| 🟢 **PASS** | Expected result was achieved |
| 🔴 **FAIL** | Expected result was not achieved |
| 🟡 **BLOCKED** | Test could not be completed because of a dependency |
| ⚪ **NOT TESTED** | Test has not yet been executed |

---

## 🔎 Test Case Details

<details>
<summary>🧪 <strong>TC-001 — Login with valid credentials</strong></summary>

### Objective

Verify that a registered user can log in successfully.

### Preconditions

- User account exists.
- User is logged out.
- Login page is accessible.

### Test Steps

| **Step** | **Action** | **Expected Result** |
|---:|---|---|
| 1 | Open the login page. | Login page is displayed. |
| 2 | Enter a valid username. | Username is accepted. |
| 3 | Enter a valid password. | Password is accepted. |
| 4 | Click **Login**. | User is successfully logged in. |
| 5 | Verify the dashboard. | Dashboard is displayed. |

### Test Data

```text
Username: test@example.com
Password: ********
```

### Result
> Full context and evidence.<br>

**Actual Result:**  
Password reset email was not received.

**Evidence:**  
📎 [Screenshot](#)

**Status:** 🔴 **FAIL**

**Related Issue:** `ISSUE-001`

