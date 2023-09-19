# IDS 706 Data Engineering Mini Project 1

This repository sets up an environment with codespaces and Github Actions to create a Python Github template. 

***

### Key components in the repository are:

  1. **Makefile**: contains instructions defining how to install packages, test source code, and perform other development tasks such as formatting and linting the code. 
  2. **requirements.txt**: lists external libraries and packages which are required to be installed for running the project. More packages may be added depending on projects over time. This also indicates a specific version of the package to be installed to ensure that collaborators working on a project can use the same version of libraries without reproducibility and compatibility issues. 
  3. **Dockerfile**: defines environment variables to ensure that everyone working on the project can avoid conflicts and version mismatch issues. 
  4. **devcontainer.json**: specifies the settings for the development container including the installed extensions in the virtual environment 
  5. **main.py**: contains basic functions 
  6. **test_main.py:** python file which tests the function in main 
  7. **workflows**: contains configuration files for defining and automating various tasks, processes, and workflows within the GitHub repository.
  8. **README**: a markdown file that gives developers a basic description and instructions for the GitHub project.
  9. **.gitignore**: specifies files and directories that should be ignored by Git, the version control system used by Github. Changes in files or directories in the .gitignore file will not be tracked by Git, and they will not be included in the version history. 
