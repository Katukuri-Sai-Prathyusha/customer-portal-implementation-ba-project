# 08 - UAT Plan & Test Cases

## 1. UAT Purpose

User Acceptance Testing (UAT) is performed to confirm that the customer portal meets approved business requirements and is ready for business use.

UAT will be performed by selected business users representing customer support and relevant business teams.

The Business Analyst will coordinate UAT activities and work with business users, QA, Product, and Development teams to resolve requirement-related questions.

---

## 2. UAT Objectives

The objectives of UAT are to:

- Validate business requirements.
- Confirm expected customer workflows.
- Validate portal usability.
- Identify business defects.
- Confirm integrations work as expected.
- Verify notifications.
- Confirm request tracking.
- Obtain business sign-off before go-live.

---

## 3. UAT Entry Criteria

UAT can begin when:

- Development is completed for the agreed scope.
- System testing is completed.
- Critical defects are resolved.
- UAT environment is available.
- UAT test cases are prepared.
- Test data is available.
- Business users are identified.
- Requirements and acceptance criteria are approved.

---

## 4. UAT Exit Criteria

UAT can be completed when:

- All critical test scenarios are passed.
- No unresolved critical or high-severity defects remain.
- Business users confirm the solution meets requirements.
- Defects have been reviewed and dispositioned.
- Business stakeholders provide UAT sign-off.

---

# 5. UAT Test Cases

## UAT-01 - Customer Login

**Requirement:** BR-01

**Scenario:** Customer logs into the portal using valid credentials.

**Test Steps:**
1. Open the customer portal.
2. Enter valid username.
3. Enter valid password.
4. Click Login.

**Expected Result:**
Customer successfully logs in and is directed to the portal dashboard.

**Priority:** High

**Status:** Pass

---

## UAT-02 - Invalid Login

**Requirement:** BR-01

**Scenario:** Customer enters invalid credentials.

**Test Steps:**
1. Open the login page.
2. Enter invalid credentials.
3. Click Login.

**Expected Result:**
The system rejects the login and displays an appropriate error message.

**Priority:** High

**Status:** Pass

---

## UAT-03 - Knowledge Base Search

**Requirement:** BR-02

**Scenario:** Customer searches for an article.

**Test Steps:**
1. Log into the portal.
2. Navigate to Knowledge Base.
3. Enter a relevant search term.
4. Select Search.

**Expected Result:**
Relevant knowledge articles are displayed.

**Priority:** Medium

**Status:** Pass

---

## UAT-04 - Create Support Request

**Requirement:** BR-03

**Scenario:** Customer creates a support request.

**Test Steps:**
1. Log into the portal.
2. Select Create Support Request.
3. Enter required information.
4. Add an attachment.
5. Submit the request.

**Expected Result:**
The request is successfully created and a unique reference number is generated.

**Priority:** High

**Status:** Pass

---

## UAT-05 - Mandatory Field Validation

**Requirement:** BR-03

**Scenario:** Customer attempts to submit a request without required information.

**Test Steps:**
1. Open Create Support Request.
2. Leave mandatory fields empty.
3. Click Submit.

**Expected Result:**
The system prevents submission and identifies the missing required information.

**Priority:** High

**Status:** Pass

---

## UAT-06 - Request Tracking

**Requirement:** BR-04

**Scenario:** Customer tracks an existing support request.

**Test Steps:**
1. Log into the portal.
2. Navigate to My Requests.
3. Select an existing request.

**Expected Result:**
The current request status and relevant details are displayed.

**Priority:** High

**Status:** Pass

---

## UAT-07 - Request History

**Requirement:** BR-05

**Scenario:** Customer views previous requests.

**Test Steps:**
1. Log into the portal.
2. Navigate to Request History.
3. Select a previous request.

**Expected Result:**
Previous request information is displayed correctly.

**Priority:** Medium

**Status:** Pass

---

## UAT-08 - Submission Notification

**Requirement:** BR-06

**Scenario:** Customer submits a support request.

**Test Steps:**
1. Create a valid support request.
2. Submit the request.
3. Check the registered email.

**Expected Result:**
Customer receives a confirmation notification containing the request reference.

**Priority:** High

**Status:** Pass

---

## UAT-09 - Status Change Notification

**Requirement:** BR-06

**Scenario:** Support team changes the request status.

**Test Steps:**
1. Create a support request.
2. Change the request status.
3. Check the customer's notification.

**Expected Result:**
Customer receives a notification about the status change.

**Priority:** Medium

**Status:** Pass

---

## UAT-10 - CRM Request Synchronization

**Requirement:** BR-07

**Scenario:** Portal request is synchronized with the support system.

**Test Steps:**
1. Create a support request through the portal.
2. Open the support/CRM system.
3. Search for the request reference.

**Expected Result:**
The request is available in the support system with the correct customer and request information.

**Priority:** High

**Status:** Pass

---

## UAT-11 - Portal Usage Reporting

**Requirement:** BR-08

**Scenario:** Authorized user views portal usage metrics.

**Test Steps:**
1. Log in as an authorized business user.
2. Open reporting.
3. Select portal usage report.

**Expected Result:**
Portal usage information is displayed correctly.

**Priority:** Medium

**Status:** Pass

---

## UAT-12 - Access Control

**Requirement:** BR-09

**Scenario:** User attempts to access information outside their permissions.

**Test Steps:**
1. Log in with a restricted user account.
2. Attempt to access unauthorized information.

**Expected Result:**
The system prevents unauthorized access.

**Priority:** High

**Status:** Pass

---

# 6. Defect Management

During UAT, defects will be recorded with:

- Defect ID
- Test Case ID
- Description
- Severity
- Priority
- Environment
- Steps to reproduce
- Expected result
- Actual result
- Assigned owner
- Status

---

# 7. Defect Severity

| Severity | Definition |
|---|---|
| Critical | Blocks a major business process |
| High | Significant business functionality is affected |
| Medium | Functionality is affected but workaround exists |
| Low | Minor issue with limited business impact |

---

# 8. UAT Defect Workflow

```text
Defect Identified
       ↓
Defect Logged
       ↓
BA / QA Review
       ↓
Assigned to Development
       ↓
Fix Implemented
       ↓
Retesting
       ↓
Business Validation
       ↓
Closed
9. UAT Sign-Off

UAT sign-off should confirm that:

Approved business requirements have been validated.
Critical business scenarios have passed.
Critical and high-severity defects are resolved or formally accepted.
Business users are satisfied with the solution.
The project is ready to proceed toward go-live.

UAT Outcome: Pending formal business sign-off.
