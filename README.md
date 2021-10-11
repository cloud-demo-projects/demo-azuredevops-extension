[![Build Status](https://dev.azure.com/bahrinipun/demo-azuredevops-extension/_apis/build/status/build-package-publish-extension?branchName=main)](https://dev.azure.com/bahrinipun/demo-azuredevops-extension/_build/latest?definitionId=60&branchName=main)

# Develop, Package & Publish Custom Azure DevOps Extension
This is a sample project for developing and publishing the custom Azure DevOps extension which contains-
- Sample extension 
- Azure DevOps pipeline to build, package & publish extension in marketplace

## Prerequisites
### Local Development- Build & Packaging
- VS Code
- Node.js 
- TFX(extension packaging tool): npm install -g tfx-cli; npx tfx-cli extension create

### Local Development- Marketplace Publish
- Marketplace account

### CI/CD
- Azure Devops Organization
- Marketplace account
- PAT with access to marketplace & extensions
- Marketplace service connection
