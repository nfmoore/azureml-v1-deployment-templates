# AML Deployment Templates

Machine Learning Operations (MLOps) is based on DevOps principles and practices that increase the efficiency of Machine Learning workflows. It aims to facilitate faster experimentation, development and production deployment of Machine Learning models while ensuring high-quality standards. A standard end-to-end MLOps workflow will consist of model training, registration, deployment and monitoring.

This repository has references to several related MLOps deployment templates built using [Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml) and [Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines) (part of Azure DevOps). The templates contain code and DevOps pipeline definitions to automate the end-to-end deployment of a machine learning platform, machine learning models as a web service for real-time inferencing or as a pipeline for batch inferencing using MLOps principles and practices.

These templates include unit tests and code coverage, model training and registration, controlled deployments (via approvals), [web service](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-app-insights) or [pipeline](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-log-pipelines-application-insights) monitoring and data [drift monitoring and detection](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-monitor-datasets). 

## Projects

#### [AML Platform Deployment Template](https://github.com/nfmoore/aml-platform-deployment-template) 
- Automated deployment of a machine learning platform using Azure DevOps
- The template serves as a foundation for other deployment templates but can also be used independently

#### [AML Real-Time Scoring Deployment Template](https://github.com/nfmoore/aml-real-time-deployment-template) 
- Automated end-to-end deployment of machine learning models as a web service for real-time inferencing
- Useful for scenarios where machine learning models are integrated as part of real-time applications or Power BI reports and dashboards

#### [AML Batch Scoring Deployment Template](https://github.com/nfmoore/aml-batch-deployment-template) 
- Automated end-to-end deployment of machine learning models as an AML Pipeline for batch inferencing
- Useful for scenarios where machine learning models generate insights at a regular frequency (e.g. every week) or as part of a wider data engineering pipeline (e.g. with [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/transform-data-machine-learning-service))

## Prerequisites

- Azure subscription (contributor or owner)
- Azure DevOps project
- GitHub account

## References

- [Azure Machine Learning documentation](https://docs.microsoft.com/en-us/azure/machine-learning/)
- [Azure Pipelines documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/)
- [Azure Machine Learning Python SDK](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py)
- [Azure Machine Learning CLI](https://docs.microsoft.com/en-us/azure/machine-learning/reference-azure-machine-learning-cli)
