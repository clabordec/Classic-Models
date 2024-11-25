# Classic-Models

## 📋 Project Overview
The ClassicModels database is a sample database frequently used for practice and testing database operations. In this project, we aim to ensure the data's accuracy, integrity, and functionality through rigorous testing methodologies.

Our testing workflow integrates:

- MySQL for database operations.
- JIRA for managing and tracking bugs.
- Zephyr Scale for documenting and managing test cases.

<br>

## 🔑 Features
- Comprehensive test cases for database CRUD operations.
- Validation of database schema integrity and constraints.
- Automated and manual test execution reports.
- Detailed bug tracking and resolution using JIRA.
- Real-time test management via Zephyr Scale.

<br>

## 🛠️ Tools & Technologies
| <h4>Tool/Technology</h4> | <h4>Description</h4> |
| --- | --- |
| MySQL	Database | Platform for ClassicModels schema. |
| JIRA | Bug tracking and issue management. |
| Zephyr Scale | Test case management and reporting. |

## 🗂️ Project Structure
```graphql
ClassicModels/
├── sql/
│   ├── class-models.sql    # Script to create the ClassicModels schema
│   ├── seed-data.sql        # Script to populate sample data
│   └── test-queries.sql     # Queries for testing
├── test-cases/
│   ├── functional/          # Functional test cases for CRUD operations
│   ├── integration/         # Integration test cases
│   └── performance/         # Performance test cases
├── reports/
│   ├── test_execution/      # Test execution reports
│   └── bug_reports/         # Exported JIRA bug reports
├── README.md                # Project documentation
└── .gitignore               # Git ignore file
```

<br>

## 🧪 Testing Workflow
1. Test Case Management:
All test cases are documented in Zephyr Scale under the project ClassicModels Testing.
Test cases are categorized into:
Functional tests
Integration tests
Performance tests

3. Test Execution:
Execute test cases directly via Zephyr Scale.
Log defects in JIRA with detailed bug reports.

4. Bug Tracking:
Bugs are tracked using JIRA, linked to their respective test cases.
Reports are available in the reports/bug_reports/ directory.

5. Test Automation (Optional):
Extend testing with automated scripts if necessary.

<br>

## 📈 Reporting
- <b>Test Execution Reports</b>: Located in `reports/test_execution/`.
- <b>Bug Reports</b>: Exported from JIRA and stored in `reports/bug_reports/`.

<br>

## 📧 Contact
For any queries or suggestions, feel free to reach out:

- <b>Author</b>: Chaanyah Laborde
- <b>Email</b>: chaanyahlaborde@gmail.com
- <b>GitHub</b>: [claborde](https://github.com/clabordec/)


# Happy Testing! 🎉
