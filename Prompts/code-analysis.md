# 🚀 "GitHub Copilot in Action: Code, Refactor & Automate Like a Pro!

[Start with the overview](../Overview.md) - Please make sure to read the Overview.md file first to understand the prerequisites and important notes before executing the prompts below.

### Code Analysis:
- `@workspace find all the dependencies of third-party libraries and Java components. List them in a tabular format with 1. Name (with group: ' ', name: ' ', version: ' ') 2. Target version that is compatible with Java 21, Spring 6.x, Spring Boot 3.x, Hibernate 6.x, JUnit 5, and Mockito 5.x migration 3. Complexity (scale like low, medium, high) considering the underlying technical challenges and the level of refactoring required during the upgrade of the dependency and testing. For example, upgrading to Hibernate 6.x from 3.x is tedious as the Hibernate framework has undergone major revamping, then complexity may be high.5. Remarks to highlight what are the anticipated key changes with some examples. This will help the dev team and architect to understand the complexity and effort estimation.`

- `@workspace You are an AI assistant specialized in Java migration projects. Your task is to generate a discovery and compatibility report for the modules and libraries found from the given context below. The migration should ideally target to upgrade all the dependencies and code to Java 21, Spring 6.x, Spring Boot 3.x, Hibernate 6.x, JUnit 5, and Mockito 5.x compatibility.`

- `@workspace You are a code reviewer for java migration project targets to Java 21 from Java 8. Migration also includes Junit5, Hibernate 6.x, Spring 6.x, SpringBoot 3.x and all other libraries upgrades. Can you analysis the migrated code and configs in the given context and post your review comments. Important: do not give summary of general recommendation, identify missed/pending changes.`

- `@workspace You are an AI assistant specialized in Java migration projects. Your task is to carefully assess every line of the code, configuration, and libraries given in the workspace context. Highlight the technical compatibility issues found targeting to Java 21, Spring 6.x, Spring Boot 3.x, Hibernate 6.x, JUnit 5, and Mockito 5.x versions but not limited. Additional Context: During the migration, we experienced a large number of runtime errors due to.XML file-based Spring bean creation, Hibernate upgrade to 6.x, Mockito upgrade and Powermock replacement with Mockito changes but not limited. Important: Do not give general recommendations. Provide all the findings as much as in a tabular format with issue found, file/class name, potential impact and ideal fix as needed by each file wise. Avoid markdown or detailed analysis section.- Ask questions if you need further details to generate a relevant response before generating a final response.`

### ⚠️Important Note:
- AI-generated code is not always 100% correct – review, validate, and refine it..
- Your prompt clarity determines the quality of Copilot's response.
- Use iterative refinement – start broad, then refine your prompt for better results.