# Test Plan – New Joiner Onboarding & Training System

## 1. Introduction
This document defines the test strategy, scope, and approach for validating the New Joiner Onboarding & Training Management System.

---

## 2. Scope

### In-Scope
- Authentication & role-based access
- Document upload & verification
- HRMS, IAM, Payroll integration
- Training & certification workflows
- Buddy feedback & readiness scoring
- Notifications and audit logs

### Out-of-Scope
- Performance testing
- Security testing
- Production data validation

---

## 3. Test Objectives
- Validate end-to-end onboarding workflow
- Ensure data accuracy across integrations
- Identify functional and workflow gaps
- Ensure compliance and audit readiness

---

## 4. Test Strategy
- Manual Functional Testing
- Workflow-based testing
- Role-based testing
- Positive & negative scenario coverage

---

## 5. Test Types
- Functional Testing
- Integration Testing
- Regression Testing
- UAT Testing

---

## 6. Test Environment
- Environment: UAT / Staging
- Platform: Web Application
- Browser: Chrome, Edge
- Roles: HR, New Joiner, Trainer, QA Evaluator, Buddy

---

## 7. Entry Criteria
- Approved requirements
- Test environment available
- Test data prepared
- Access provided to all roles

---

## 8. Exit Criteria
- All critical test cases executed
- No open blocker/critical defects
- Test summary shared
- Stakeholder sign-off

---

## 9. Roles & Responsibilities
| Role | Responsibility |
|----|----|
| QA Tester | Test execution & defect logging |
| HR | Business validation |
| Developer | Defect resolution |
| PM | Final approval |

---

## 10. Defect Management
- Tool: JIRA
- Severity: Blocker, Critical, Major, Minor
- Status Flow: New → In Progress → Fixed → Retest → Closed

---

## 11. Risks & Mitigation
| Risk | Mitigation |
|----|----|
| Integration failures | Early integration testing |
| Delayed fixes | Daily follow-ups |
| Data issues | Controlled test data |

---

## 12. Test Deliverables
- Test Plan
- Test Scenarios
- Test Cases
- Defect Reports
- Test Summary Report
