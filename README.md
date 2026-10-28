# Azure Data Factory - File Storage

Description: Pipelines, datasets, and configurations for managing, migrating, and processing file storage using Azure Data Factory (ADF).

## 🚀 Features
* Automated Ingestion: Seamlessly copy data from on-premises, SFTP, or external clouds to Azure Blob Storage and ADLS Gen2.
* Format Conversion: Transform raw files (CSV, JSON, Excel) into optimized analytical formats like Parquet.
* Event-Driven Processing: Trigger data workflows automatically as soon as new files arrive in storage.

## 📂 Repository Structure
* `/pipelines/` - JSON definitions for data movement and orchestration.
* `/datasets/` - Source and sink file configurations.
* `/linkedServices/` - Connection setups (secured via Azure Key Vault and Managed Identities).
* `/triggers/` - Storage event and schedule-based triggers.

## 🛠️ Deployment
1. Clone this repository.
2. Update the `linkedServices` configurations with your specific Key Vault and Storage Account endpoints.
3. Deploy the artifacts to your ADF instance using the provided ARM templates via your preferred CI/CD tool.
