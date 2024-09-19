# CMPG323-Overview-32593392
## CMPG 323 Project Repositories and their Links
**Project 1: Agile (Scrum) Implementation-32593392**

   This repository will contain the overall project structure and initial setup for the CMPG 323 module.
     
     LINK: https://github.com/Dee699/CMPG323-Overview--32593392)]

**Project 2: API Basics & Security-32593392**
    This repository will focus on building a .NET Web API that connects to a SQL Server database, with full CRUD functionality for telemetry data.
    
     LINK: https://github.com/Dee699/CMPG323-PROJECT-2-32593392
     
**Project 3: Architecture & Design Patterns-32593392**
    This repository will contain the UiPath RPA automation for the User Acceptance Testing (UAT) process, including automation scripts and test results.
    
     LINK: https://github.com/Dee699/CMPG-323-Project-3--32593392
     
**Project 4: Testing & Automated Testing-32593392**
  This repository will involve data visualization and reporting tasks, along with SQL queries for the in-depth analysis of the Airbnb dataset.

      LINK: https://github.com/Dee699/CMPG-323-Project-4---32593392

**Project 5: Data Analytics & Visualisation-32593392**
  This repository will serve as the final project portfolio, consolidating all tasks and showcasing the complete solution for CMPG 323, including documentation and reflections.

      LINK:
     
### Documentation

####Branching Strategy

Each project repository will follow a standardized branching strategy to ensure consistency and ease of collaboration. The branching strategy is as follows:

1. Main Branch: This is the stable branch where all completed and tested code will be merged. This branch should always be deployable.
2. Develop Branch: This branch is used for integration and testing. All feature branches will be merged into this branch.
3. Feature Branches: Each new feature or task will have its own branch created from the develop branch. The naming convention for feature branches will be `feature/<feature-name>`.
4. Hotfix Branches: For urgent fixes that need to be addressed immediately, a branch will be created from the main branch. The naming convention for hotfix branches will be `hotfix/<fix-name>`.

##### Branching Workflow
1. Create a feature branch from develop for a new feature or task.
2. Work on the feature branch and commit changes.
3. Open a pull request (PR) to merge the feature branch into the develop branch.
4. Once reviewed and approved, merge the PR.
5. Periodically, merge the develop branch into the main branch after testing. 

###### Use of .gitignore

The `.gitignore` file is used to specify which files and directories should be ignored by Git. This helps to keep the repository clean and ensures that sensitive or unnecessary files are not committed. Each project will have a `.gitignore` file that includes the following:

1. **Sensitive Information**: Exclude files that contain credentials, API keys, or other sensitive information.
2. **Build Artifacts**: Ignore compiled code, build directories, and other temporary files generated during the build process.
3. **Dependency Directories**: Exclude directories used by package managers (e.g., `node_modules` for Node.js, `venv` for Python).
4. **System Files**: Ignore system-specific files such as `.DS_Store` (macOS) and `Thumbs.db` (Windows).


