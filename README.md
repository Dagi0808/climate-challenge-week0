## Branch Strategy

This project follows a task-based Git workflow:

- `main` → stable branch
- `setup-task` → environment setup and repository configuration
- `eda-ethiopia` → exploratory data analysis for Ethiopia dataset

## Pull Request Workflow

Changes are developed in feature branches and merged through Pull Requests.

Example:
setup-task → Pull Request → main
eda-ethiopia → Pull Request → main

## CI Trigger

GitHub Actions runs automatically on:
- push
- pull_request