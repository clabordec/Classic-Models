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
| <b>Tool/Technology</b> | <b>Description</b> |
| --- | --- |
| MySQL	Database | platform for ClassicModels schema. |
| JIRA | Bug tracking and issue management. |
| Zephyr Scale | Test case management and reporting. |

## 🗂️ Project Structure
graphql
Copy code
ClassicModels/
├── sql/
│   ├── create_schema.sql    # Script to create the ClassicModels schema
│   ├── seed_data.sql        # Script to populate sample data
│   └── test_queries.sql     # Queries for testing
├── test_cases/
│   ├── functional/          # Functional test cases for CRUD operations
│   ├── integration/         # Integration test cases
│   └── performance/         # Performance test cases
├── reports/
│   ├── test_execution/      # Test execution reports
│   └── bug_reports/         # Exported JIRA bug reports
├── README.md                # Project documentation
└── .gitignore               # Git ignore file
🚀 Getting Started
Prerequisites
Ensure you have the following tools installed:

MySQL (v8.0 or higher)
JIRA account with access to Zephyr Scale
Any MySQL client (e.g., MySQL Workbench, DBeaver)
Installation Steps
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ClassicModels.git
cd ClassicModels
Set up the database:

Import the schema:
bash
Copy code
mysql -u username -p < sql/create_schema.sql
Populate the data:
bash
Copy code
mysql -u username -p < sql/seed_data.sql
Run initial test queries:

bash
Copy code
mysql -u username -p < sql/test_queries.sql
Configure JIRA and Zephyr Scale for test management:

Link your JIRA account.
Set up a project named ClassicModels Testing.
Import or manually create test cases.
🧪 Testing Workflow
Test Case Management:

All test cases are documented in Zephyr Scale under the project ClassicModels Testing.
Test cases are categorized into:
Functional tests
Integration tests
Performance tests
Test Execution:

Execute test cases directly via Zephyr Scale.
Log defects in JIRA with detailed bug reports.
Bug Tracking:

Bugs are tracked using JIRA, linked to their respective test cases.
Reports are available in the reports/bug_reports/ directory.
Test Automation (Optional):

Extend testing with automated scripts if necessary.
📈 Reporting
Test Execution Reports: Located in reports/test_execution/.
Bug Reports: Exported from JIRA and stored in reports/bug_reports/.
🤝 Contribution
We welcome contributions to enhance this project! Please follow these steps:

Fork the repository.
Create a new feature branch:
bash
Copy code
git checkout -b feature/your-feature-name
Commit your changes:
bash
Copy code
git commit -m "Add your feature description"
Push the changes:
bash
Copy code
git push origin feature/your-feature-name
Create a pull request.
🛡️ License
This project is licensed under the MIT License.

📧 Contact
For any queries or suggestions, feel free to reach out:

Author: [Your Name]
Email: your.email@example.com
GitHub: Your GitHub Profile
Happy Testing! 🎉
