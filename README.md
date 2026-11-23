
## Project Overview

This project demonstrates automated
Infrastructure as Code (IaC) validation
using Terraform and GitHub Actions.

## Objectives

- Automate Terraform formatting checks.
- Automate Terraform configuration validation.
- Integrate GitHub Actions for Continuous Integration.
- Display CI pipeline status using a workflow badge.

## Tools Used

- Terraform
- Git
- GitHub
- GitHub Actions

## CI Pipeline

The GitHub Actions workflow automatically executes:

1. Checkout Repository
2. Setup Terraform
3. Terraform Format Check
4. Terraform Initialize
5. Terraform Validate

## Expected Result

A successful GitHub Actions workflow
with all validation steps passing.
