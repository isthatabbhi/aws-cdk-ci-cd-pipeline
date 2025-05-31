# AWS CDK CI/CD Pipeline

A fully automated CI/CD pipeline built using AWS Cloud Development Kit (CDK). This project leverages AWS CodePipeline, CodeBuild, CodeDeploy, and CodeCommit to provision and manage infrastructure using Infrastructure as Code (IaC), and automate the deployment of application code across environments.

---

## 🚀 Project Overview

This project demonstrates how to:
- Use AWS CDK to define and provision cloud infrastructure.
- Set up a CI/CD pipeline with AWS CodePipeline.
- Automate builds and unit testing with AWS CodeBuild.
- Deploy applications using AWS CodeDeploy.
- Integrate source control using AWS CodeCommit.
- Create a multi-stage pipeline (e.g., dev → prod) with environment isolation.

---

## 🛠️ AWS Services Used

- **AWS CDK** – Infrastructure as Code
- **AWS CodeCommit** – Source code repository
- **AWS CodeBuild** – Build and test automation
- **AWS CodeDeploy** – Deployment automation
- **AWS CodePipeline** – CI/CD orchestration
- **AWS CloudFormation** – Backend provisioning via CDK

---

## 📂 Project Structure

aws-cdk-ci-cd-pipeline/
├── bin/
│ └── pipeline.ts # Entry point for CDK app
├── lib/
│ └── pipeline-stack.ts # Pipeline definition
├── src/
│ └── app/ # Sample application source code
├── test/
│ └── unit-tests/ # Unit tests for the app
├── cdk.json
├── package.json
└── README.md
