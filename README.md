# CI/CD Website Deployment Project

## Overview
This project demonstrates automated deployment of a website to AWS EC2 using GitHub Actions.

## Technologies Used
- Visual Studio Code
- GitHub
- GitHub Actions
- AWS EC2
- Nginx
- YAML

## Deployment Workflow
1. Website developed locally using VS Code
2. Code pushed to GitHub repository
3. GitHub Actions automatically triggers workflow
4. Workflow connects securely to AWS EC2
5. Website is deployed automatically to Nginx server

## CI/CD Pipeline
The deployment pipeline is written in YAML and located in:

.github/workflows/pipeline.yml

## Live Deployment
The website is hosted on AWS EC2 and deployed automatically on every push to the main branch.