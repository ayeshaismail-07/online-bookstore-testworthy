# Online Book Store – Testworthy Test Case Management

## 📘 Project Overview
This repository contains the complete QA documentation and test case design for the **Online Book Store** project managed and executed in **Testworthy**.

The project focuses on verifying all key modules of an online book store—authentication, search, shopping, checkout, and notifications—through structured test suites, systematic planning, and detailed execution reporting.

---

##  Learning Objectives
From this project, you will learn to:
- Write effective, traceable **test cases** from refined user stories
- Plan and organize **test suites** by modules
- Execute and manage **test runs** in **Testworthy**
- Classify test cases into **Smoke, Regression, Negative, and Automation**
- Generate and maintain **execution reports**

---

##  Project Components

| Component | Description |
|------------|--------------|
| **Test Suites** | Six suites aligned with project modules |
| **Test Cases** | Functional, regression, and negative cases for each suite |
| **Execution Plan** | Runs performed and tracked in Testworthy |
| **Reports** | PDF/Excel execution summary reports |
| **Resources** | References, screenshots, and video guides |

---

##  Test Suites Overview

| Suite | Module | Description |
|--------|----------|--------------|
| 1 | **Authentication & Account Management** | Login, signup, password management, and profile features |
| 2 | **Catalog & Search** | Browsing, searching, filtering, and sorting books |
| 3 | **Shopping Cart & Wishlist** | Add/remove items, view totals, and save books for later |
| 4 | **Checkout & Payment** | Shipping, promo codes, and secure payment validation |
| 5 | **Reviews & Ratings** | Submitting, viewing, and sorting book reviews |
| 6 | **Notifications & Reports** | User notifications and admin-level reporting |

---

##  Example Test Case (As Entered in Testworthy)

**Title:** Login with Valid Credentials  
**Section:** Login  
**Type:** Functional  
**Priority:** High  
**Automation Type:** Manual  

**Description:**  
Verify that the user can successfully log in using valid credentials.  

**Preconditions:**  
User account already exists in the database.  

**Test Data:**
Username: testuser@example.com
Password: Password123

markdown
Copy code

**BDD Gherkin:**
Given a registered user
When the user enters valid credentials and clicks Login
Then the system should redirect to the homepage

markdown
Copy code

**Steps:**
1. Navigate to login page.  
2. Enter registered email and password.  
3. Click “Login” button.  

**Expected Result:**  
User is successfully logged in and redirected to the homepage.

---

##  Step-by-Step Guide for Testworthy

1. **Login to Testworthy** → https://testworthy.io  
2. **Create a New Project** → “Online Book Store”  
3. **Add Suites** (Create 6 suites listed above)  
4. **Add Sections** (e.g., Login, Signup under Authentication Suite)  
5. **Add Test Cases** under each section using the “Add Test Case” button  
6. **Fill Details:**
   - Type: Functional / Regression / Negative  
   - Priority: High / Medium / Low  
   - Automation Type: Manual / Automated  
7. **Run Execution:**  
   - Go to *Executions → New Execution → Select Suite & Cases*  
   - Mark test status as **Pass / Fail / Blocked**  
8. **Generate Reports:**  
   - Click *Reports → Export Execution Results* (PDF or Excel)  
9. **Attach Reports** to this repo under `/reports` folder.

---

##  Classification of Test Cases

| Type | Example Scenarios |
|------|-------------------|
| **Smoke Tests** | Login, Add to Cart, Checkout |
| **Regression Tests** | Search, Payment, Wishlist |
| **Negative Tests** | Invalid login, Expired card |
| **Automation Candidates** | Login, Add to Cart, Search Filters |

---

##  Reporting & Tracking
Execution Reports contain:
- Total test cases executed
- Pass / Fail / Blocked ratio
- Execution trends by suite
- Key defects identified

All reports are exported from Testworthy and stored in `/reports/`.

---

##  Tools & Technologies
- **Testworthy** for test case & plan management  
- **Gherkin** for BDD-style test writing  
- **Excel / PDF** for report exports  
- **GitHub** for version control  

