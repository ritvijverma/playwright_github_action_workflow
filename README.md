# Playwright GitHub Actions Demo 🎭

This is a simple demo project to understand how **Playwright tests can be integrated with GitHub Actions**.

## Setup

Create a new Playwright project using:

```bash
npm init playwright@latest
```

During setup, select:

* TypeScript
* `tests` as the test directory
* **Yes** for GitHub Actions workflow
* **Yes** to install Playwright browsers

This creates the basic Playwright project along with the GitHub Actions workflow.

## Run Tests Locally

Run Playwright tests using:

```bash
npx playwright test
```

## GitHub Actions

After creating the Playwright project:

1. Create a repository on GitHub.
2. Initialize Git in the project.
3. Commit the project files.
4. Push the code to the GitHub repository.
5. The `.github/workflows/playwright.yml` workflow is triggered automatically.
6. GitHub Actions installs the dependencies and runs the Playwright tests.

### Workflow

```text
Playwright Project
       ↓
Create GitHub Repository
       ↓
Push Code to GitHub
       ↓
GitHub Actions Workflow
       ↓
Install Dependencies
       ↓
Run Playwright Tests
       ↓
Test Result
```

## Purpose

The purpose of this project is to demonstrate the basic integration of **Playwright E2E testing with GitHub Actions CI

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/8fe679eb-f6cb-4d77-9ab3-0c9ca9dd15c5" />


## 🚀 More Coming Soon...

More Playwright tests and GitHub Actions examples coming soon!

