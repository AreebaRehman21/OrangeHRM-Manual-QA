# OrangeHRM - Manual QA Testing

## Project Overview

This project demonstrates manual software testing of the OrangeHRM application. The objective was to test key HR management functionalities, execute manual test cases, identify defects, and document the testing results.

Jira was also used for defect tracking and Scrum-based project management.

## Project Objectives

- Create a structured Test Plan
- Design and execute manual test cases
- Perform functional and UI testing
- Identify and document software defects
- Track defects using Jira
- Use Scrum workflow for defect management
- Perform defect retesting
- Prepare a Test Execution Summary
- Document the complete manual QA testing process

## Scope of Testing

The following modules and functionalities were tested:

- Login
- Dashboard
- My Info
- Change Password
- Logout

## Testing Process

The project followed these manual QA activities:

1. Test Planning
2. Test Scenario Creation
3. Test Case Design
4. Test Case Execution
5. Defect Identification
6. Bug Reporting
7. Bug Tracking in Jira
8. Defect Retesting
9. Test Execution Reporting
10. Scrum Sprint Management

## Test Cases

A total of **25 test cases** were created and executed for the OrangeHRM application.

The test cases covered the Login, Dashboard, My Info, Change Password, and Logout modules.

## Test Execution Results

| Result | Count |
|---|---:|
| Total Test Cases | 25 |
| Passed | 18 |
| Failed | 7 |
| Pass Rate | 72% |
| Fail Rate | 28% |

## Bug Report

A total of **7 bugs** were identified and documented during testing.

### Major Defects Identified

1. Login allows SQL Injection input
2. Dashboard does not display a proper error message when network connection is interrupted
3. My Info allows saving a record with mandatory fields left blank
4. Date of Birth accepts a future date
5. Password is updated even when the current password is incorrect
6. Dashboard is accessible after user logout using the Dashboard URL
7. User session remains active in another browser tab after logout

All identified defects were documented in the Bug Report and tracked using Jira.

## Jira Defect Tracking

Jira was used for defect tracking and Scrum project management.

The OrangeHRM Jira project includes:

- Scrum project
- Product backlog
- 7 Bug issues
- Bug assignment
- Sprint planning
- Scrum board
- Bug status tracking
- Defect workflow

### Jira Bugs

| Bug ID | Bug Summary | Module | Priority | Status |
|---|---|---|---|---|
| OHRM-1 | Login allows SQL Injection input | Login | High | To Do |
| OHRM-2 | Dashboard does not display a proper error message when network connection is interrupted | Dashboard | Medium | In Progress |
| OHRM-3 | My Info allows saving record with mandatory fields left blank | My Info | High | To Do |
| OHRM-4 | Date of Birth accepts a future date | My Info | Medium | To Do |
| OHRM-5 | Password is updated even when the current password is incorrect | Change Password | High | To Do |
| OHRM-6 | Dashboard is accessible after user logout using the Dashboard URL | Logout | High | To Do |
| OHRM-7 | User session remains active in another browser tab after logout | Logout | High | To Do |

### Jira Workflow

`To Do → In Progress → Done`

The identified bugs were added to the Jira backlog and included in the OrangeHRM Sprint 1 for tracking.

## Tools Used

- **Microsoft Excel** - Test Cases, Bug Report, and Test Execution Summary
- **Microsoft Word** - Test Plan
- **Jira** - Bug Tracking and Scrum Project Management
- **Google Chrome** - Test Execution
- **OrangeHRM** - Application Under Test
- **GitHub** - Project Documentation and Version Control

## Project Deliverables

| File | Description |
|---|---|
| `Test Plan OrangeHRM.docx` | Test planning document |
| `Test Cases OrangeHRM.xlsx` | 25 manual test cases |
| `Bug Report OrangeHRM.xlsx` | Documented defects |
| `Test Execution Summary OrangeHRM.xlsx` | Test execution results |
| `OrangeHRM Jira Bugs Report.xlsx` | Jira bug tracking documentation |
| `README.md` | Project documentation |

## Repository Structure

```text
OrangeHRM-Manual-QA/
│
├── Test Plan OrangeHRM.docx
├── Test Cases OrangeHRM.xlsx
├── Bug Report OrangeHRM.xlsx
├── Test Execution Summary OrangeHRM.xlsx
├── OrangeHRM Jira Bugs Report.xlsx
│
├── Jira Screenshots/
│   ├── Jira Backlog - 7 Bugs.png
│   ├── Jira Sprint Board.png
│   └── Jira OHRM-1 Bug.png
│
└── README.md
