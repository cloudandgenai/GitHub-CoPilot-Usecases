# 🚀 "GitHub Copilot in Action: Code, Refactor & Automate Like a Pro!

[Start with the overview](../Overview.md) - Please make sure to read the Overview.md file first to understand the prerequisites and important notes before executing the prompts below.

### Advanced Prompts:
####  Infrastructure as Code (IaC)
- `Generate a Terraform script to create an AWS ECS Fargate instance and deploy the latest jar file from a Nexus repository into it.`
  - `Modify the Terraform script to include an EKS deployment instead of ECS Fargate.`
  - `Translate the Terraform script to an Ansible playbook.`

#### SQL/ETL Automation
- `Create a Snowpipe-based ETL to transfer Parquet files from S3 into a Snowflake instance.`

- `Generate a SQL query to perform a left outer join between profiles and assessment tables.`
  - `Add a condition to the user_name field to match names ending with 'n' or 'i' and starting with 'd' or 'w' in the WHERE clause.`
  - `Refactor the user_name condition using regex.`
  - `Optimize the SQL query for performance.`

#### UI/API Component Generation
- `Generate code for a React component that includes a button named "Search", two dropdowns named "Districts" and "States", and two checkboxes named "Filter by Program" and "Filter by Subject". Style the components using the Materialize styles. Position the checkboxes at the top left corner, the dropdowns at the top right corner, and the button at the center of the component.`

- `Generate code for a responsive React component that includes a bar chart, three textboxes for student name, course name, and score, a download report button, and two dropdowns for the list of districts and states. The dropdown for districts should dynamically update its values based on the selected state in the states dropdown. This means that the available districts should be filtered based on the selected state.`

- `Create a method in a Nest.js service that validates a JWT token received from the Salesforce Identity Provider (IdP) and returns the user object extracted from the token.`

- `Create a graphql api in nest.js for validating the credentials received and to save those credentials in the postgres database`

### ⚠️Important Note:
- AI-generated code is not always 100% correct – review, validate, and refine it..
- Your prompt clarity determines the quality of Copilot's response.
- Use iterative refinement – start broad, then refine your prompt for better results.