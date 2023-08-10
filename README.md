![90477030](https://github.com/peacetheboy/CMPG-323-Overview-36564567-/assets/90477030/6ccd76bb-4474-4c38-9134-b04f2f781b50)
# CMPG-323-Overview 36564567
I'm now a CMPG 323 student! 🤩

project 1 will be created on this repository named CMPG-323-Overview - <36564567> ✅

# Project Repositories to be created for each project 🫡
- CMPG-323-Overview Project 1 - <36564567> 
- CMPG 323 Project 2 - <36564567>
- CMPG 323 Project 3 - <36564567>
- CMPG 323 Project 4 - <36564567>
- CMPG 323 Project 5 - <36564567>

# Diagram explaining project and repository context and how they are integrated
![image](https://github.com/peacetheboy/CMPG-323-Overview-36564567-/assets/90477030/08791091-dac5-45ac-a068-2175e0a84fad)

# Branncing Strategy

## Why brancing is important
Within a single, central code base, teams of developers can effortlessly interact via branching. The version control system makes a copy of the code base at that precise moment when a developer starts a branch. Other team members' developers are unaffected by changes to the branch. 

## Branching strategies to be used

We follow a feature branching strategy to manage code changes effectively. This strategy allows for parallel development while maintaining code quality and minimizing conflicts.

### Branch Types

1. **Main Branch:** The `main` (or `master`) branch holds the stable and deployable code. It should always reflect the production-ready state.

2. **Feature Branches:** For each new feature, bug fix, or enhancement, create a new branch based on `main`. Use descriptive names that reflect the feature or issue being addressed (e.g., `feature/user-authentication`, `bugfix/data-validation`).

3. **Pull Requests:** When your feature is ready for review, open a pull request from your feature branch to `main`. This allows for code review, discussion, and testing before merging.

### Workflow

1. Create a new branch for your feature or bug fix:

   ```bash
   git checkout main
   git pull origin main
   git checkout -b feature/new-feature
1. # Regularly commit your changes to the feature branch:
   ![carbon (1)](https://github.com/peacetheboy/CMPG-323-Overview-36564567-/assets/90477030/ce6319f2-0bf2-4064-903c-30ef2a1ea3bf)
2. # Push your changes to the remote repository:


# Project Management with.gitignore (for all projects) 😇

In this project, we use a '.gitignore' file to determine which files and folders Git will ignore, assuring that just the necessary code and resources are maintained. This strategy contributes to the cleanliness of our repository, removes unneeded clutter, and improves collaboration.

## Why .gitignore? 🤔

When developing a project, it is common to encounter files and directories that are generated automatically, contain sensitive information, or are unrelated to version control. Git should not track these files. The '.gitignore' file lets us set patterns for files and directories to ignore.

# Credentials and Sensitive Information 🤫

The security of our code and user data is a high priority in these projects. We adhere to the best practices and rules stated below to ensure the safe storage and management of credentials and sensitive information.


## Ground rules 📗

1. Use environment variables to store sensitive information such as API keys, passwords, and tokens. This isolates them from the codebase and prevents accidental exposure.

2. Sensitive data should be stored in configuration files. These files, however, should not be tracked by version control.

3. Encrypt sensitive data before storing it if possible. Even if the data is accessed, this adds an extra layer of security.

## Storing Credentials 🔐

1. If environment variables aren't possible, create a separate configuration file to prevent this file from being committed, add it to your '.gitignore' file.

2. If configuration files must be included in version control, use placeholders or dummy values instead of genuine sensitive data. Provide directions for populating these files with the required information.

## Sensitive Data 🔒

To ensure that sensitive material does not end up in version control by accident, we utilize a '.gitignore' file to exclude files containing sensitive information. Configuration files, secret files, and environment-specific files are examples of such files.

To keep sensitive data secure, we strongly advise examining and maintaining your project's '.gitignore' file.


