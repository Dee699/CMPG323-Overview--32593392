## CMPG323-Overview-32593392

*This project is about the development of a Telemetry Data Management System using Agile methodologies, specifically Scrum and Kanban. The overall system aims to manage telemetry data for various automation projects, enabling effective tracking of time and cost savings. By leveraging a RESTful API built with .NET and hosted on Azure, the project will facilitate collaboration, flexibility, and responsiveness to changing requirements.
## CMPG 323 Project Repositories and their Links*

**Project 1: Agile and Scrum implementation - 32593392**

This repository will contain the overall project structure and initial setup for the CMPG 323 module.
  
  *Link*: https://github.com/Dee699/CMPG323-Overview--32593392


**Project 2: API Basics and Security - 32593392**

This repository will focus on building a .NET Web API that connects to a SQL Server database, with full CRUD functionality for telemetry data.

   *Link*: https://github.com/Dee699/CMPG323-PROJECT-2-32593392


**Project 3: Architecture and Design Patterns - 32593392**

This repository will contain the UiPath RPA automation for the User Acceptance Testing (UAT) process, including automation scripts and test results.

   *Link*: https://github.com/Dee699/CMPG-323-Project-3--32593392


**Project 4: Testing and Automated Testing - 32593392**

This repository will involve data visualization and reporting tasks, along with SQL queries for the in-depth analysis of the Airbnb dataset.

   *Link*: https://github.com/Dee699/CMPG-323-Project-4---32593392


**Project 5: Data Analytics and Visualisation-32593392**

  This repository will serve as the final project portfolio, consolidating all tasks and showcasing the complete solution for CMPG 323, including documentation and reflections.

   *Link*: https://github.com/Dee699/CMPG-323-Project-5--32593392

     
### Documentation:

 Below is a link to my documentation:
 
  *Link*: https://github.com/Dee699/CMPG323-Overview--32593392/blob/main/Lean_Technical_Documentation_Template.docx  

### Burndown Chart

   Below is a link to my Burndown Chart:
  
   https://github.com/Dee699/CMPG323-Overview--32593392/blob/991f4ac180f4accec550aefe08946b7159e37daa/BurndownChart_32593392.xlsx

### **Branching Strategy**

For all projects, I will use a **single branch strategy** where all work is conducted on the main branch. The workflow will be streamlined to ensure stability while minimizing complexity.

### **Main Branch (`main`)**

- The main branch will be the **sole branch** used for development and deployment of my work.
 
- All code changes, feature additions, bug fixes, and updates will be made directly on the main branch.

- Each change will be thoroughly tested before being committed to ensure the stability of the branch.
  
### **Workflow**

- Instead of managing multiple branches, I will focus on keeping the main branch **stable** and **up-to-date**.

- Features will be developed directly on the main branch with regular commits.

- Before committing any changes, I will run **unit tests** and **integration tests** to verify that the new code does not introduce bugs or instability.

 -Code reviews will be performed before pushing changes to the main branch.

This streamlined strategy simplifies the development process while maintaining the stability of the codebase. It also reduces the overhead of managing multiple branches.


#### Understanding the .gitignore File

The .gitignore file is a crucial part of any Git repository, specifying which files and directories Git should ignore. This helps maintain a clean repository by ensuring that only relevant files those which contribute to the project’s development are tracked.

#### Importance of the .gitignore File

In development, many files are generated that do not need to be shared or tracked. These may include logs, build artifacts, and personal configurations that differ from one developer to another. Using a .gitignore file allows developers to avoid committing files that may contain sensitive information or are unnecessary for the project’s functionality.

### Each Project's .gitignore File Will Include the Following:

1. **Sensitive Information**: Exclude files that contain credentials, API keys, or other sensitive information to protect against security breaches.
  
2. **Build Artifacts**: Ignore compiled code, build directories, and other temporary files generated during the build process to keep the repository clean.

3. **Dependency Directories**: Exclude directories used by package managers, such as node_modules for Node.js or venv for Python, as these can be restored from package management tools.

4. **System Files**: Ignore system-specific files like .DS_Store (used in macOS) and Thumbs.db (used in Windows) to prevent cluttering the repository with irrelevant files.

### Example of a .gitignore File for a General Project

Here’s an example of a .gitignore file tailored for a general software project:


```plaintext
# Ignore environment configuration files
.env
*.local

# Ignore sensitive information
credentials.json
secrets.yaml

# Ignore compiled files and build artifacts
*.class
*.o
*.exe
dist/
build/

# Ignore log files
*.log

# Ignore cache and temporary files
cache/
temp/
*.tmp

# Ignore dependency directories
node_modules/
venv/
vendor/

# Ignore IDE-specific files
.idea/
*.sublime-workspace

# Ignore system-specific files
Thumbs.db
.DS_Store
```


In this example, the .gitignore file is configured to exclude:

- **Sensitive information**: Prevents exposure of credentials and sensitive data.

- **Build artifacts**: Keeps compiled files and build directories out of version control.

- **Log files**: Excludes log data that is not necessary for collaboration.

- **Cache and temporary files**: Prevents tracking of temporary files created during development.
  
- **Dependency directories**: Excludes third-party libraries that can be restored easily.
  
- **IDE-specific files**: Prevents local settings from affecting the repository.
  
- **System-specific files**: Keeps unnecessary OS-generated files from being committed.

By carefully configuring the .gitignore file, i can ensure that my Git repository remains focused and efficient, enabling better collaboration and management of my codebase.


### Storage of Credentials and Sensitive Information

When developing applications, it’s crucial to manage credentials and sensitive information securely. Here are some best practices for handling this information:

1. **Environment Variables**: Store sensitive information such as API keys, database connection strings, and credentials in environment variables. This keeps them out of your codebase and makes it easier to change them without modifying the source code. For example, in a .NET application, you can access environment variables using Environment.GetEnvironmentVariable("VARIABLE_NAME").

2. **Configuration Files**: Use configuration files that are not tracked by version control to store sensitive information. These files should be added to your .gitignore file to prevent them from being committed. For example, a file named appsettings.Development.json can contain sensitive data for local development, while production secrets can be stored securely on the server.

3. **Secret Management Services**: Leverage secret management tools and services, such as Azure Key Vault, AWS Secrets Manager, or HashiCorp Vault, to store and manage sensitive information securely. These services provide encrypted storage and access controls to ensure that only authorized applications and users can access the secrets.

4. **Encryption**: Always encrypt sensitive data, both at rest and in transit. Use established encryption algorithms and libraries to protect sensitive information from unauthorized access.

5. **Least Privilege Principle**: Follow the principle of least privilege when assigning access rights to sensitive information. Only grant access to the credentials that are necessary for a user or application to perform its tasks.

By following these practices,i will definetely enhance the security of my application and protect sensitive information from unauthorized access and breaches.


