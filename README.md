# Project Azure with Terraform, AKS and Docker

# Overview
This repository contains resources and code for setting up and managing an Azure environment using Terraform and AKS (Azure Kubernetes Service). The project aims to provide a practical approach to deploying cloud resources while maintaining cost-efficiency.

# Key Features:
Azure DevOps Integration: Utilize Azure DevOps for efficient project management.
Terraform for Infrastructure as Code: Automate infrastructure deployment using Terraform scripts.
Kubernetes (AKS) Deployment: Leverage AKS for container orchestration.
Cost Management: Strategies to minimize Azure costs.

# Prerequisites
Basic understanding of Azure, Terraform, and Kubernetes.
Azure CLI installed and configured.
Terraform installed.
Familiarity with Kubernetes and YAML configurations.

# Setup and Configuration

# Initial Configuration
- Terraform Directory: Create a directory for Terraform scripts.

- Main Terraform File: Initialize a main.tf file with resource group and virtual network (vnet) configurations.
  
# Azure Provider Configuration
- Use the Azure provider from Terraform, ensuring compatibility with the latest version.
  
- Replace placeholder names with specific project identifiers.
  
# Kubernetes (AKS) Setup
- Resource Group and Cluster Configurations: Define AKS cluster and associated resources.
  
- Cost-effective VM Selection: Use AzurePrice.net to choose an affordable VM for the AKS master node.
  
- Tagging: Implement tagging for resource organization and billing.
  
# Terraform Execution
Initialization: Run terraform init to prepare your Terraform working directory. 

Authentication: Ensure Azure CLI is authenticated (use az login).

Plan and Apply: Execute terraform plan and terraform apply to deploy resources.

# Kubernetes Configuration
Credentials: Retrieve AKS credentials using Azure CLI.

Deployments and Services: Use kubectl commands to create and manage Kubernetes deployments and services.

# Running the Project
Deployment Creation: Utilize kubectl create deployment to deploy a REST API.

Service Exposure: Expose the deployment using kubectl expose.

Resource Monitoring: Monitor the deployment and services through the Azure portal.

# Repository Structure
/Terraform: Contains Terraform configuration files.

/AKS: Houses Kubernetes deployment and service configurations.
