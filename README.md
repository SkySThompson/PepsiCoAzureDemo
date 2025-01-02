# PepsiCoAzureDemo
DEMO- Azure Static Web App
To implement a continuous delivery pipeline for the Augur frontend that automatically builds and deploys to Azure every time a commit is made to the main branch, we can use GitHub Actions for CI/CD and Azure Static Web Apps for hosting the frontend. Here's a detailed approach to set up the pipeline and deployment process.

Pipeline Overview
CI/CD Framework: GitHub Actions (a modern, widely used CI/CD service tightly integrated with GitHub).
Azure Service: Azure Static Web Apps (a service specifically designed for deploying static frontend apps with continuous deployment from GitHub).
Process:
Automatically build the project on every commit to the main branch.
Deploy the latest build to Azure Static Web Apps.
Handle provisioning, build, and deployment automatically.
