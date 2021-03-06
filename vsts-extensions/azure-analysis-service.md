---
uid: vsts/azureanalysisservice/overview
title: Azure Analysis Service release extension
description: This extension adds release tasks related to Azure Analysis Service to Azure DevOps.
tags: [
    { "name": "AzureDevOps" },
    { "name": "azure-pipelines" }, 
    { "name": "Azure" },
    { "name": "release" },
    { "name": "pipelines" },
    { "name": "Analysis Service" }
]
system: {
    document_id: dcb1b597-e63d-4180-ac35-79d8db8bae4d,
    program_github: liprec/vsts-release-aas
}
---
# Azure Analysis Service

This extension adds release tasks related to Azure Analysis Service to Azure DevOps.

## Azure Analysis Service Deployment

Azure DevOps deploy task that will deploy a Tabular model to an existing Azure Analysis Service instance. Also option to change the connected source datasource during release.

At this moment the following configuration are tested and working:

- Model 1400 and a single SQL Server database as datasource

More configuration will follow. Feel free to contact me for a specific configuration.

[More information](xref:vsts/azureanalysisservice/deploy)

## Azure Analysis Service TMSL Script

Azure DevOps task can be added to a pipeline to execute a custom TMSL script against an Azure Analysis Service instance.

[More information](xref:vsts/azureanalysisservice/execute)

## Feedback

### [**Documentation**](#tab/docs)

If you have any comment related to the documentation, like corrections, unclear features or missing documentation, feel free to leave feedback below via GitHub. Or correct it yourself and submit a PR; see [CONTRIBUTING.md](https://github.com/liprec/azurebi-docs/blob/master/.github/CONTRIBUTING.md) for more details.
*GitHub account required.*

### [**Product**](#tab/product)

If you have any comment related to the working of the described product, feel free to leave feedback below via GitHub.
*GitHub account required.*

***

### [**Open**](#tab/docs-open/docs)

### [**Closed**](#tab/docs-closed/docs)

### [**Open**](#tab/product-open/product)

### [**Closed**](#tab/product-closed/product)

***
