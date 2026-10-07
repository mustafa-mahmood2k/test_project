# Test Project

This is a test repository generated to verify my automated data engineering workflow. 

## How this project was created

This repository and its corresponding local environment were automatically generated using a custom Bash script (`new_project.sh`). Running `./new_project.sh test_project` executed the following automated steps:

1. **Scaffolding:** Duplicated a standardized project template directory structure.
2. **Database Provisioning:** Started the local `sqlserver2025` Docker container and automatically executed a SQL command to create a dedicated `test_project` database.
3. **Environment Setup:** Initialized an isolated Python virtual environment (`venv`) and installed the core data stack (`pandas`, `pyodbc`, `sqlalchemy`).
4. **Version Control:** Initialized a local Git repository, created this private remote repository via the GitHub CLI (`gh`), and pushed the initial commit.

## Local Environment Details
* **Database Connection:** `localhost:1433`
* **Database Name:** `test_project`
* **Python Environment:** `./venv`
