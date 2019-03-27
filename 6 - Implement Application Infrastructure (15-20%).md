# Implement Application Infrastructure (15-20%)
## Design an Infrastructure and Configuration Management Strategy
- Analyze Existing and Future Hosting Infrastructure
- Analyze Existing Infrastructure as Code (IaC) Technologies
- Design a Strategy for Managing [Technical Debt on Templates](https://www.azuredevopslabs.com/labs/azuredevops/sonarcloud/)
- Design a Strategy for using [Transient Infrastructure for parts of a Delivery Lifecycle](https://docs.microsoft.com/en-us/dotnet/standard/modernize-with-azure-and-containers/modernize-existing-apps-to-cloud-optimized/reasons-to-modernize-existing-net-apps-to-cloud-optimized-applications)
- Design a Strategy to Mitigate [Infrastructure State Drift](https://blogs.msdn.microsoft.com/tomholl/2017/10/16/detecting-drift-between-arm-templates-and-azure-resource-groups/)

## Implement Infrastructure as Code (IaC)
- Create [Nested Resource Templates](https://samcogan.com/modularisation-and-re-use-with-nested-arm-templates/)
- Manage Secrets in Resource Templates
    - [Use Azure Key Vault to pass secure parameter value during deployment](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-keyvault-parameter)
- Provision Azure Resources
    - [IaC with ARM Template](https://blogs.msdn.microsoft.com/azuredev/2017/02/11/iac-on-azure-an-introduction-of-infrastructure-as-code-iac-with-azure-resource-manager-arm-template/)
- Recommend an Infrastructure as Code (IaC) Strategy
- Recommend Appropriate Technologies for Configuration Management, for example:
    - ARM Templates
    - Terraform
    - Chef
    - Puppet
    - Ansible

## Manage Azure Kubernetes Service (AKS) Infrastructure
- Provision [Azure Kubernetes Service (AKS)](https://www.azuredevopslabs.com/labs/vstsextend/kubernetes/) using:
    - ARM templates
    - CLI
- Create Deployment File for Publishing to Azure Kubernetes Service (AKS), for example:
    - kubectl
    - Helm
- Develop a [Scaling Plan](https://docs.microsoft.com/en-us/azure/devops/organizations/projects/about-projects)

## Implement Infrastructure Compliance and Security
- Implement Compliance and Security Scanning
- [Prevent Drift by using Configuration Management Tools](https://docs.microsoft.com/en-us/azure/automation/tutorial-configure-servers-desired-state)
- Automate Configuration Management by using PowerShell Desired State Configuration (DSC)
- Automate Configuration Management by using a VM Agent with Custom Script Extensions
- Set up an Automated Pipeline to Inspect Security and Compliance