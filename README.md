# CMPG323-Overview-32593392
## CMPG 323 Project Repositories and their Links

This repository will contain the overall project structure and initial setup for the CMPG 323 module.

Link: https://github.com/Dee699/CMPG323-Overview--32593392


**Project 2: API Basics & Security - 32593392**

This repository will focus on building a .NET Web API that connects to a SQL Server database, with full CRUD functionality for telemetry data.

[Link to Project 2](https://github.com/Dee699/CMPG323-PROJECT-2-32593392)


**Project 3: Architecture & Design Patterns - 32593392**

This repository will contain the UiPath RPA automation for the User Acceptance Testing (UAT) process, including automation scripts and test results.

[Link to Repository](https://github.com/Dee699/CMPG-323-Project-3--32593392)


**Project 4: Testing & Automated Testing - 32593392**

This repository will involve data visualization and reporting tasks, along with SQL queries for the in-depth analysis of the Airbnb dataset.

[Link to Repository](https://github.com/Dee699/CMPG-323-Project-4---32593392)


**Project 5: Data Analytics & Visualisation-32593392**

  This repository will serve as the final project portfolio, consolidating all tasks and showcasing the complete solution for CMPG 323, including documentation and reflections.

      LINK:
     
### Documentation

### **Branching Strategy**

For all projects, I will use a **single branch strategy** where all work is conducted on the `main` branch. The workflow will be streamlined to ensure stability while minimizing complexity.

### **Main Branch (`main`)**

- The `main` branch will be the **sole branch** used for development and deployment of my work.
 
- All code changes, feature additions, bug fixes, and updates will be made directly on the `main` branch.

- Each change will be thoroughly tested before being committed to ensure the stability of the branch.
  
### **Workflow**

- Instead of managing multiple branches, I will focus on keeping the `main` branch **stable** and **up-to-date**.

- Features will be developed directly on the `main` branch with regular commits.

- Before committing any changes, I will run **unit tests** and **integration tests** to verify that the new code does not introduce bugs or instability.

 -Code reviews will be performed before pushing changes to the `main` branch.

This streamlined strategy simplifies the development process while maintaining the stability of the codebase. It also reduces the overhead of managing multiple branches.


#### Understanding the .gitignore File

The `.gitignore` file is a crucial part of any Git repository, specifying which files and directories Git should ignore. This helps maintain a clean repository by ensuring that only relevant files those which contribute to the project’s development are tracked.

#### Importance of the .gitignore File

In development, many files are generated that do not need to be shared or tracked. These may include logs, build artifacts, and personal configurations that differ from one developer to another. Using a `.gitignore` file allows developers to avoid committing files that may contain sensitive information or are unnecessary for the project’s functionality.

### Each Project's .gitignore File Will Include the Following:

1. **Sensitive Information**: Exclude files that contain credentials, API keys, or other sensitive information to protect against security breaches.
  
2. **Build Artifacts**: Ignore compiled code, build directories, and other temporary files generated during the build process to keep the repository clean.

3. **Dependency Directories**: Exclude directories used by package managers, such as `node_modules` for Node.js or `venv` for Python, as these can be restored from package management tools.

4. **System Files**: Ignore system-specific files like `.DS_Store` (used in macOS) and `Thumbs.db` (used in Windows) to prevent cluttering the repository with irrelevant files.

### Example of a .gitignore File for a General Project

Here’s an example of a `.gitignore` file tailored for a general software project:


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


In this example, the `.gitignore` file is configured to exclude:

- **Sensitive information**: Prevents exposure of credentials and sensitive data.
- 
- **Build artifacts**: Keeps compiled files and build directories out of version control.
- 
- **Log files**: Excludes log data that is not necessary for collaboration.
- 
- **Cache and temporary files**: Prevents tracking of temporary files created during development.
- 
- **Dependency directories**: Excludes third-party libraries that can be restored easily.
- 
- **IDE-specific files**: Prevents local settings from affecting the repository.
- 
- **System-specific files**: Keeps unnecessary OS-generated files from being committed.

By carefully configuring the `.gitignore` file, i can ensure that my Git repository remains focused and efficient, enabling better collaboration and management of my codebase.

