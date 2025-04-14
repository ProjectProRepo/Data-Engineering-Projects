# Azure Project: Build and Deploy CI/CD Pipeline Using Azure DevOps and Databricks

## Overview

In this DevOps-focused Azure project, you will learn how to build a **CI/CD pipeline** using **Azure DevOps** and **Azure Databricks** to streamline development and deployment of notebooks across development and production environments. This project replicates enterprise-grade DevOps practices where data engineers and ML teams collaborate through automated workflows to ensure consistency, code quality, and reproducible deployments.

You’ll use tools like **Azure Repos**, **DevOps Pipelines**, **Databricks CLI**, and **YAML configuration** to implement version-controlled, secure, and automated deployments from Git to Azure Databricks.

## Project Objectives

- Set up **Azure DevOps Repos** for notebook versioning.  
- Create **Dev and Prod Azure Databricks workspaces**.  
- Establish **branching workflows** for development and production.  
- Use **service connections** and **library groups** in Azure DevOps for deployment.  
- Configure the **Dev workspace** to sync with Git repositories.  
- Create **CI pipelines** to automate test builds on every push.  
- Design **CD pipelines** to deploy notebooks into the Prod workspace.  
- Write **YAML files** to define and version-control the pipeline logic.  
- Enable **email notifications** on deployment status and failures.  

## Prerequisites

Before you begin, ensure the following:

- An active **Azure subscription** with permissions to create Databricks workspaces, service principals, and resource groups.  
- An **Azure DevOps organization** with access to Pipelines and Repos.  
- **Basic Git skills** (commit, push, pull, branch, merge).  
- Working knowledge of **YAML**, **Azure CLI**, and **Databricks notebooks**.  
- Familiarity with **Databricks workspace UI** and development lifecycle.  
- Optional: Prior completion of **Azure Medallion Architecture project (Part 1)** for continuity.

## Tech Stack

- **Languages**: Python, Scala  
- **DevOps Tools**: Azure DevOps, Azure Pipelines, Azure Repos  
- **Data Platform**: Azure Databricks  

## Expected Outcomes

By completing this project, you will:

- Learn how to build and manage a **CI/CD pipeline** for Databricks notebooks.  
- Understand the flow from **code commit to production deployment**.  
- Automate **build and release pipelines** using YAML.  
- Manage **workspace-level access** and **secrets** securely through DevOps.  
- Build **production-ready deployment workflows** used by data engineering teams.  
- Improve team collaboration through **source control and PR-based workflows**.  

## Key Features of the Project

- **Dev and Prod Workspace Management**: Keep dev and prod environments in sync.  
- **Version-Controlled Deployment**: Notebooks stored and managed via Git.  
- **YAML-Based Automation**: Portable and customizable pipeline definitions.  
- **Secure Integration**: Use service principals for secure access between DevOps and Databricks.  
- **Pipeline Notifications**: Stay informed with automatic alerts on build and release status.  
- **Pull Request Strategy**: Merge-reviewed production deployments using PRs.

## Important Notes

- **Pipeline Parallelism**: If you see *“No hosted parallelism has been purchased or granted”*, request free parallelism from Azure DevOps settings.  
- **Cookbook Access**: A complete **text-based execution guide** is provided for step-by-step implementation.  
- **Cost Management**: Monitor your Azure usage and Databricks resources regularly.  
- **Databricks Git Integration**: Ensure Git credentials are correctly configured inside the workspace.  
- **Branch Protection**: Enforce policies on the main/prod branch for safe deployments.

## Dataset Overview

This project uses **Databricks notebooks**, which can be used to read from any structured or semi-structured dataset. You may use a sample dataset (e.g., sales, IoT, or healthcare logs) to simulate Dev → Prod deployments of ETL jobs or machine learning pipelines.

Sample fields may include:

- `customer_id`  
- `transaction_time`  
- `product_category`  
- `region`  
- `device_type`  
- `revenue`  

These notebook jobs can be versioned, tested, and pushed to production as part of the CI/CD pipeline.

## Project Link

[Azure Project: Build and Deploy CI/CD Pipeline Using Azure DevOps and Databricks](https://www.projectpro.io/project-use-case/azure-devops-ci-cd-pipeline)

## Project Series

This is **Part 2** of a multi-project Azure data engineering series:

- **Part 1** – Build a Data Pipeline Using Azure Medallion Architecture  
- **Part 2** – Build and Deploy CI/CD Pipeline Using Azure DevOps and Databricks  
- **Part 3** – Real-Time Pipeline Using ADF, Logic Apps, and Stream Processing  
