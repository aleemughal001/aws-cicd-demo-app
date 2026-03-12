# AWS CI/CD Demo App

## Overview

This project demonstrates a complete CI/CD pipeline on AWS that automatically builds and deploys a static web application to an EC2 instance.

It covers:
- Source control with AWS CodeCommit
- Build and packaging with AWS CodeBuild
- Pipeline automation with AWS CodePipeline
- Deployment to EC2 using AWS CodeDeploy
- Static site hosting with NGINX

## Project Files

- `appspec.yml` — deployment instructions for CodeDeploy
- `buildspec.yml` — build instructions for CodeBuild
- `index.html` — static website content
- `scripts/install_nginx.sh` — installs NGINX
- `scripts/start_nginx.sh` — starts or restarts NGINX
- `Screenshot from 2026-03-13 00-32-34.png` — deployed application screenshot
- `README.md` — project documentation

## Deployment Flow

CodeCommit → CodeBuild → CodePipeline → CodeDeploy → EC2

## Result

The application was deployed successfully:

![Deployment screenshot](./Screenshot%20from%202026-03-13%2000-32-34.png)

## Author

Muhammad Ali Mughal
