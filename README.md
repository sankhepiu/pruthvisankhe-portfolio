# AWS Static Portfolio Deployment

A production-ready static portfolio deployed on AWS using Amazon S3 for hosting and CloudFront for global content delivery, with automated CI/CD integration via GitHub Actions.

## Overview

This project demonstrates a real-world cloud deployment workflow:

- Static website hosted on Amazon S3
- Global content delivery using Amazon CloudFront
- HTTPS enabled through CloudFront
- Automated CI/CD pipeline triggered on every push to the `main` branch
- Secure credential management using AWS IAM and GitHub Secrets

## Architecture

### Deployment Flow

1. Code is pushed to the GitHub `main` branch  
2. GitHub Actions workflow is triggered automatically  
3. Updated files are synced to an Amazon S3 bucket  
4. CloudFront distributes content globally over HTTPS  
5. End users access the live portfolio via CloudFront  

This setup ensures consistent, automated, and reliable deployments without manual file uploads.

## Tech Stack

- Amazon S3
- Amazon CloudFront
- AWS IAM
- GitHub Actions (CI/CD)
- HTML & CSS

## Live Demo

🔗 [View Live Portfolio](https://d15538ljjsrlck.cloudfront.net/)
