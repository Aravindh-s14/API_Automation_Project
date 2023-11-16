# API_Automation_CI/CD

Dummy API's forked from Valentino Artisan
## Continuous Integration/Continuous Deployment (CI/CD)

This repository utilizes GitHub Actions for continuous integration and continuous deployment.

### CI/CD Workflow

- **Build**: The build workflow is triggered on every commit to the repository.
- **Deployment**: Automatic deployment is configured for specific branches (e.g., `main` or `production`).

### GitHub Actions

Details about GitHub Actions workflows and scripts.

- `.github/workflows/build.yml`: Configuration for the build workflow.
- `.github/workflows/deploy.yml`: Configuration for the deployment workflow.

### Build Status

Show the build status badge.

Status Badge<br>
  - For New Commits <br>
    - ![example workflow](https://github.com/Aravindh-s14/API_Automation_Project/actions/workflows/postman.yml/badge.svg)
  - Scheduled/Crone_Job [Every 5 hour] <br>
    - [![Automated API tests using Postman CLI](https://github.com/Aravindh-s14/API_Automation_Project/actions/workflows/postman_cronJob.yml/badge.svg)](https://github.com/Aravindh-s14/API_Automation_Project/actions/workflows/postman_cronJob.yml)
