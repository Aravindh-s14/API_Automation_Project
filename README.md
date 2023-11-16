# API_Automation_CI/CD

Dummy API's forked from Valentino Artisan
## Continuous Integration/Continuous Deployment (CI/CD)

This repository utilizes GitHub Actions for continuous integration and continuous deployment.

### CI/CD Workflow

- **Build**: The build workflow is triggered on every commit to the repository.
- **Deployment**: Automatic deployment is configured for specific branches (e.g., `main` or `production`).

### GitHub Actions

Details about GitHub Actions workflows and scripts.

- `.github/workflows/postman.yml`: Configuration for the build workflow upon new code commit/push.
- `.github/workflows/postman_cronJob.yml`: Cron job scheduled for every 5 hours to check the test.

### Build Status
Status Badge<br>
  - For New Commits <br>
    - ![example workflow](https://github.com/Aravindh-s14/API_Automation_Project/actions/workflows/postman.yml/badge.svg)
  - Scheduled/Crone_Job [Every 5 hour] <br>
    - [![Scheduled/ Crone Job Checking the test [Every 5 Hours]](https://github.com/Aravindh-s14/API_Automation_Project/actions/workflows/postman_cronJob.yml/badge.svg)](https://github.com/Aravindh-s14/API_Automation_Project/actions/workflows/postman_cronJob.yml)
