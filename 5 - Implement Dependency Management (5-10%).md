# Implement Dependency Management (5-10%)
## Design a Dependency Management Strategy
- Recommend Artifact Management Tools and Practices, for example:
    - Azure Artifacts
    - npm
    - maven
    - NuGet
- Abstract Common Packages to Enable Sharing and Reuse
- Inspect Codebase to Identify Code Dependencies that can be Converted to Packages
- Identify and Recommend Standardized Package Types and Versions across the Solution
- Refactor Existing Build Pipelines to implement Version Strategy that Publishes Packages

## Manage Security and Compliance
- Inspect Open Source Software Packages for Security and License Compliance to Align with Corporate Standards, for example:
    - GPLv3
- Configure Build Pipeline to Access Package Security and License Rating, for example:
    - Black Duck
    - [WhiteSource](https://www.azuredevopslabs.com/labs/vstsextend/WhiteSource/)
- Configure [Secure Access to Package Feeds](https://docs.microsoft.com/en-us/azure/devops/artifacts/feeds/feed-permissions)