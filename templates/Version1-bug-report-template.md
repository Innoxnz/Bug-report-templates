# 🐛 Bug Report Template

> [!NOTE]
> This is the template that is being used at work. As you might know every company operates differently.
> In our case all the testing is happening in 1 environment, before going to production. That is why I did not mention any environment (staging, for example)<br>
> Regarding the test steps: all developers are doing small tests before deploying into staging and once bug is found we hand it over to the same developer who created the feature.
> So basically everyone knows the steps to test the feature.<br>
> For some of you it might look reasonable for other not, but as long as it works, we find bugs and prevent any leaks in production then it should be fine!
> Have a look at the template! Let me know what you think! 👐

**Instructions:**  Use this page as a lightweight QA template for release validation. Copy it for each deployment, replace placeholders, and add rows only when needed.

 ---


## Feature Testing

| **Testing Phase** | **Date** | **Result** | **Status** |
|---|---|---|---|
| Staging | `{date}` | `{issues / no issues}` | ☐ |
| Production | `{date}` | `{issues / no issues}` | ☐ |

 

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

 ☐ Performance Testing using JMeter for load and stress testing:

   ☐ Load Testing → Tests performance under expected number of users.

   ☐ Stress Testing → Tests how the system behaves under extreme conditions.
```

---

### Test

| **Test case** | **Acceptance Criteria (Expected result)** | **Input data** | **Results** | **Status** |
|---|---|---|---|---|
| **Test_ID:** 001<br>**Title:** Enter test case title | Describe the expected result here. | Enter the input data used for the test. | Describe the actual result<br> + Evidence(screenshot, video , etc) | ☐ OK / ☐ Need to fix |



 ### 🐛Feature-Related Bugs to fix / Questions / Improvements

| **Test Name** | **Results** | **Issue Type** | **Final Results** |
|---|---|---|---|
| **Test_ID:** 001<br>**Issue_ID:** 001<br><br> |**Where:** Login page<br>**When:** After submitting the form<br>**What:** Error message is not displayed.<br> Expected error message, but no message was displayed<br> + Evidence(screenshot, video , etc) | ☐ Bug<br>☐ Question<br>☐ Improvement<br> | Fix validation message and retest. |

---

### 🔍 Testing in Production

| **Name** | **What to Check** | **Results** | **Status** |
|---|---|---|---|
| **TIP_ID:** 001<br>**Title:** Test title | Describe what needs to be checked. | Describe the actual result<br> + Evidence(screenshot, video , etc) | ☐ OK / ☐ Need to fix |
| **TIP_ID:** 002<br>**Title:** Another test | Describe what needs to be checked. | Describe the actual result<br> + Evidence(screenshot, video , etc) | ☐ OK / ☐ Need to fix |


### 🔄 Regression Test in Production

| **Name** | **What to Check** | **Results** | **Status** |
|---|---|---|---|
| **RT_ID:** 001<br>**Title:** Regression test title | Describe what needs to be checked. | Describe the actual result<br> + Evidence(screenshot, video , etc) | ☐ OK / ☐ Need to fix |
| **RT_ID:** 002<br>**Title:** Another regression test | Describe what needs to be checked. | Describe the actual result<br> + Evidence(screenshot, video , etc) | ☐ OK / ☐ Need to fix |


###  🛠️ Other Bugs / Questions / Improvements not related to the feature


| **Test Name** | **Results** | **Issue Type** | **Final Results** |
|---|---|---|---|
| Issue_ID: 001<br>**Test:** Login validation | **Where:** Login page<br>**When:** After submitting the form<br>**What:** Error message is not displayed <br> + Evidence(screenshot, video , etc)  | ☐ Bug<br>☐ Question<br>☐ Improvement<br> | Validation message needs to be added. |



Template by Innoxnz — QA Engineer


