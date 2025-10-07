# Manual Testing Tutorial  

---

## 📘 Introduction  

Manual Testing is the process of testing software manually — without using automation tools — to ensure the application behaves as expected.  
It’s the **foundation of QA** because it helps you understand how users interact with the product and where real issues might appear.  

---

## 🎯 Objectives  

- Understand the software testing lifecycle (STLC)  
- Learn to design and execute test cases  
- Report and manage bugs effectively  
- Perform real-world testing scenarios  

---

## 🧩 Topics Covered  

1. **Software Testing Basics**  
2. **SDLC vs STLC**  
3. **Test Plan and Test Case Design**  
4. **Test Scenario Creation**  
5. **Bug Life Cycle**  
6. **Test Execution Process**  
7. **Exploratory & Regression Testing**  
8. **Practical Real-World Task**  

---

## 🧱 1. Software Testing Basics  

| Concept | Description |
|----------|-------------|
| **Definition** | Process of verifying that a software meets its requirements. |
| **Goal** | To identify defects early and ensure quality before release. |
| **Types** | Functional, Non-functional, Maintenance. |
| **Levels** | Unit, Integration, System, Acceptance. |

> 💡 Example: Checking if the login page accepts valid credentials and rejects invalid ones.

---

## ⚙️ 2. SDLC vs STLC  

| SDLC (Software Development Life Cycle) | STLC (Software Testing Life Cycle) |
|----------------------------------------|------------------------------------|
| Focuses on **development** activities | Focuses on **testing** activities |
| Starts with **requirement analysis** | Starts with **test planning** |
| Ends with **deployment/maintenance** | Ends with **test closure** |

---

## 🧾 3. Test Case Design  

### 🧠 What is a Test Case?
A **test case** is a set of conditions or steps used to verify a particular feature.

**Example Format:**

| Field | Description |
|--------|--------------|
| **Test Case ID** | TC_LOGIN_01 |
| **Title** | Verify login with valid credentials |
| **Pre-condition** | User is on login page |
| **Steps** | 1. Enter valid email and password <br> 2. Click on Login |
| **Expected Result** | User successfully logs in |
| **Actual Result** | To be filled after execution |
| **Status** | Pass/Fail |

> ✅ Good practice: Keep test cases clear, concise, and traceable to requirements.

---

## 🧠 4. Test Scenario vs Test Case  

| Term | Description | Example |
|------|--------------|---------|
| **Test Scenario** | High-level concept of what to test | “Verify login functionality” |
| **Test Case** | Step-by-step testing method | Enter credentials → Click Login → Check success message |

---

## 🐞 5. Bug Life Cycle  

| Stage | Description |
|--------|-------------|
| **New** | Bug is identified and reported |
| **Assigned** | Assigned to a developer |
| **Open** | Developer starts working |
| **Fixed** | Developer fixes the bug |
| **Retest** | QA retests the fix |
| **Closed** | QA confirms the issue is resolved |
| **Reopened** | If issue persists after fix |

> 🧩 **Tools:** Jira, Redmine, Trello, Monday, or Bugzilla

---

## 🔍 6. Test Execution Process  

1. Review requirements  
2. Create test plan & cases  
3. Prepare test environment  
4. Execute test cases  
5. Log defects  
6. Retest fixed bugs  
7. Prepare test summary report  

---

## 💻 7. Real-World Demo Task  

**Project:** Login Page Testing for a Demo Web App  
**URL:** [https://www.saucedemo.com/](https://www.saucedemo.com/)  

### 🎯 Task Steps  
1. Open the login page.  
2. Try the following test cases:  

| Test Case ID | Input | Expected Result |
|---------------|--------|----------------|
| TC_01 | Valid username & password | Login successful |
| TC_02 | Invalid username | Error message displayed |
| TC_03 | Blank password | Prompt for missing field |
| TC_04 | Valid login → Logout | Redirected to login page |

### 🧪 Bonus Task  
- Perform **Exploratory Testing** on the “Add to Cart” flow.  
- Write a **Bug Report** in markdown format:


### 🐞 Bug Report Example  
**Bug ID:** BUG_001  
**Title:** “Add to Cart” button unresponsive on Chrome  
**Severity:** Major  
**Priority:** High  
**Environment:** Chrome v127, Windows 11  
**Steps to Reproduce:**  
1. Login with valid credentials  
2. Click on “Add to Cart”  
3. Observe button not responding  
**Expected Result:** Product should be added to cart  
**Actual Result:** Nothing happens  
**Status:** New  

## 🧩 8. Exploratory Testing Techniques

Error Guessing: Think of what could break

Ad Hoc Testing: Test freely without predefined steps

Session-Based Testing: Test within time-boxed sessions

Boundary Testing: Check limits (e.g., empty fields, max chars)

## 📊 9. Test Summary Report Example

#### 🧾 Test Summary Report  

**Project:** SauceDemo Login Module  
**Tester:** Jubair Rahman  
**Date:** 2025-10-07  

| Metric | Count |
|--------|--------|
| Total Test Cases | 20 |
| Passed | 16 |
| Failed | 3 |
| Blocked | 1 |
| Defects Logged | 4 |

**Remarks:** Login and logout functions stable. Minor UI issues remain in cart section.

## 🧠 Learning Outcome

After completing this module, you’ll be able to:

✅ Write and execute test cases

✅ Perform manual testing effectively

✅ Report bugs professionally

✅ Communicate QA findings to dev teams

## 🧭 References

[![Software Testing Fundamentals](https://img.shields.io/badge/Software%20Testing%20Fundamentals-Visit%20Site-F0F2A6?style=for-the-badge&logo=book&logoColor=white&labelColor=2a9d8f)](https://softwaretestingfundamentals.com)
[![ISTQB Foundation Syllabus](https://img.shields.io/badge/ISTQB%20Foundation%20Syllabus-View%20Syllabus-F0F2A6?style=for-the-badge&logo=google-scholar&logoColor=white&labelColor=A9CEF4)](https://www.istqb.org)
[![Guru99 Manual Testing Guide](https://img.shields.io/badge/Guru99%20Manual%20Testing%20Guide-Read%20Now-F0F2A6?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=6a994e)](https://www.guru99.com/manual-testing.html)
[![SauceDemo Practice App](https://img.shields.io/badge/SauceDemo%20Practice%20App-Try%20Now-F0F2A6?style=for-the-badge&logo=testing-library&logoColor=white&labelColor=e76f51)](https://www.saucedemo.com)


