# Azure Data Factory Learning Plan

This repository is now organized as a learning workspace for Azure Data Factory (ADF).

## Goals

- Learn ADF core concepts and architecture
- Build sample pipelines using key ADF activities
- Practice deployment patterns with ARM templates or Azure Resource Manager
- Understand monitoring, debugging, and security in ADF

## Suggested learning path

1. **Introduction to ADF**
   - What is Azure Data Factory?
   - Data movement vs. data transformation
   - Integration runtime types (Azure, Self-hosted, Azure-SSIS)

2. **Linked services and datasets**
   - Create and configure linked services for Azure Blob Storage, Azure SQL Database, Azure Data Lake Storage Gen2
   - Define datasets and dataset parameters

3. **Pipelines and activities**
   - Build a pipeline with Copy Data activity
   - Use lookup, ForEach, Until, Filter, and stored procedure activities
   - Work with mappings and parameterization

4. **Triggers and scheduling**
   - Create schedule, tumbling window, and event-based triggers
   - Understand trigger run history and pipeline invocation

5. **Debugging and monitoring**
   - Use pipeline debug mode and activity run output
   - Monitor pipeline runs, activity runs, and integration runtimes
   - Handle failures using alerts and retry policies

6. **Deployment and infrastructure as code**
   - Export ARM templates from the ADF UI
   - Use `az datafactory` or Azure Resource Manager for deployments
   - Manage source control integration with Git

7. **Advanced topics**
   - Parameterize pipelines and datasets
   - Understand data flows and mapping data flows
   - Secure sensitive values using Azure Key Vault
   - Optimize performance and cost

## Repository structure

- `README.md` – Overview and learning guide
- `docs/learning-plan.md` – Learning modules and suggested path
- `examples/` – Store sample ADF JSON, pipeline definitions, and demos

## Next steps

1. Create an Azure subscription and an Azure Data Factory instance.
2. Set up Visual Studio Code and install the Azure Data Factory extension.
3. Add sample ADF JSON definitions to `examples/`.
4. Track your progress in this repository by adding notes and sample pipelines.
