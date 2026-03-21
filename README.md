# Kiran Tech Lab – DevOps CI/CD Project

## Project Overview
This project demonstrates a complete CI/CD pipeline using Azure DevOps.

## Architecture
Developer → GitHub → Azure DevOps Pipeline → Microsoft-hosted Agent → AWS EC2 → Nginx → Website

## Tools Used
- Git
- GitHub
- Azure DevOps Pipelines
- AWS EC2
- Nginx
- Rsync

## CI/CD Workflow
- Code pushed to GitHub
- Azure DevOps pipeline is triggered
- Build runs on Microsoft-hosted agent
- Files deployed to AWS EC2 via SSH
- Nginx serves updated website

## Live Project
https://kirantechlab.online
