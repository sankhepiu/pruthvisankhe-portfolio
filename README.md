# AWS Static Portfolio Deployment

A cloud-hosted portfolio website deployed on AWS using S3 and CloudFront, with automated CI/CD integration via GitHub Actions.

## Overview

This project demonstrates a production-style deployment workflow:

- Static website hosted on Amazon S3  
- Global content delivery using Amazon CloudFront  
- HTTPS enabled  
- Automated CI/CD pipeline triggered on every push to `main`  
- Secure authentication using IAM and GitHub Secrets  

## Architecture

GitHub → GitHub Actions → S3 → CloudFront → Live Website

Every commit automatically updates the live site without manual uploads.

## Tech Stack

- Amazon S3  
- Amazon CloudFront  
- AWS IAM  
- GitHub Actions  
- HTML & CSS  

## Live Demo

🔗 [View Live Portfolio](https://d15538ljjsrlck.cloudfront.net/)
