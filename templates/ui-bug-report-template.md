# 🐛 Bug Report Template

**Instructions:**  Use this page as a lightweight QA template for release validation. Copy it for each deployment, replace placeholders, and add rows only when needed.

 ---



```
Production test →  done  {date} , {issues/no issues} + { ✔️  / ❎ }

Staging testing → done  {date} , {issues/no issues} + { ✔️  / ❎ }
```

 

## Test Plan  :arrow_down:

```
Assigned Person:
Date of Testing:

Test Approach:

Functional Testing (to validate user stories and workflows)

 ☐ Smoke Testing → Quick check to see if the most basic functions work (a “build verification”).

 ☐ Sanity Testing → Verifies a specific part of the application after a bug fix or minor change

 ☐ Acceptance Testing to validate if the system meets business needs and user expectations.

 ☐ Integration Testing for payment, inventory, and user authentication modules

 ☐ Regression Testing to check if old functionality still works after new changes.


Non-functional

 ☐ Security Testing to check vulnerabilities like XSS and SQL injection

 ☐ Performance Testing using JMeter for load and stress testing

 ☐ Load Testing → Tests performance under expected number of users.

 ☐ Stress Testing → Tests how the system behaves under extreme conditions.
```

---

### Test

| **Test case** | **Acceptance Criteria (Expected result)** | **Input data** | **Results** | **Status** |
|---|---|---|---|---|
| **Test_ID:** 001<br>**Title:** Enter test case title | Describe the expected result here. | Enter the input data used for the test. | Describe the actual result. | ☐ OK / ☐ Need to fix |



 ### 🐛 Bugs to fix / Questions / Improvements

| **Test Name** | **Results** | **Status** | **Final Results** |
|---|---|---|---|
| **Test_ID:** 001<br>**Issue_ID:** ISSUE_001<br><br> |**Where:** Login page<br>**When:** After submitting the form<br>**What:** Error message is not displayed.<br> Expected error message, but no message was displayed. | ☐ Bug<br>☐ Question<br>☐ Improvement<br> | Fix validation message and retest. |

---

### 🔍 Testing in Production

| **Name** | **What to Check** | **Results** | **Status** |
|---|---|---|---|
| **TIP_ID:** 001<br>**Title:** Test title | Describe what needs to be checked. | Describe the actual result. | ☐ OK / ☐ Need to fix |
| **TIP_ID:** 002<br>**Title:** Another test | Describe what needs to be checked. | Describe the actual result. | ☐ OK / ☐ Need to fix |


### 🔄 Regression Test on Production

| **Name** | **What to Check** | **Results** | **Status** |
|---|---|---|---|
| **RT_ID:** 001<br>**Title:** Regression test title | Describe what needs to be checked. | Describe the actual result. | ☐ OK / ☐ Need to fix |
| **RT_ID:** 002<br>**Title:** Another regression test | Describe what needs to be checked. | Describe the actual result. | ☐ OK / ☐ Need to fix |


###  🛠️ Other Bugs / Questions / Improvements not related to the feature


| **Test Name** | **Results** | **Status** | **Final Results** |
|---|---|---|---|
| `ISSUE_001`<br>**Test:** Login validation | **Where:** Login page<br>**When:** After submitting the form<br>**What:** Error message is not displayed.  | ☐ Bug<br>☐ Question<br>☐ Improvement<br> | Validation message needs to be added. |


