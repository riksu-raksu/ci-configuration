# Azure Pipelines

The CI-pipeline has preliminary support for running in [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/). This document points out some differences from how configuring [GitLab's CI/CD pipeline](../gitlab/index.md) works,

## Acquiring Kólga

There are two Docker images devops/azure-kolga-demo:master and 

## **Configuration variables**

To run the CI-pipeline in Azure Pipelines, you need to provide values for these variables:

- ENVIRONMENT_SLUG
- K8S_NAMESPACE
- ENVIRONMENT_URL

Check their meaning in the **STAGES** docs.

