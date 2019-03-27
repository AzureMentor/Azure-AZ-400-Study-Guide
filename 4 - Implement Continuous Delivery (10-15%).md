# Implement Continuous Delivery (10-15%)
## Design a Release Strategy
- Recommend Release Tools
- Identify and Recommend Release Approvals and Gates
- Recommend Strategy for Measuring Quality of Release and Release Process
- Recommend strategy for Release Notes and Documentation
- Select Appropriate Deployment Pattern

## Set up a release management workflow
- Automate Inspection of Health Signals for Release Approvals by using Release Gates
- Configure Automated Integration and [Functional Test](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/test/run-functional-tests) Execution
- Create a Release Pipeline, for example:
    - Azure Kubernetes Service (AKS)
    - Service Fabric
    - WebApp
- [Create Multi-Phase Release Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/define-multistage-release-process)
- Integrate Secrets with Release Pipeline
- Provision and Configure Environments
- Manage and Modularize Tasks and Templates, for example:
    - [Task Groups](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/task-groups)
    - [Variable Groups](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/variable-groups)

## Implement an Appropriate Deployment Pattern
- Implement [Blue-Green deployments](https://azure.microsoft.com/en-us/blog/blue-green-deployments-using-azure-traffic-manager/)
- Implement Canary Deployments
- Implement [Progressive Exposure Deployments](https://blogs.msdn.microsoft.com/devops/2018/05/07/release-gates-enable-progressive-exposure-and-phased-deployments/)
- Scale a Release Pipeline to Deploy to Multiple Endpoints, for example:
    - [Deployment Groups](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/deployment-groups)
    - Azure Kubernetes Service (AKS)
    - Service Fabric