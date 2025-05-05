# 🏅 Olympic Data Analysis with Azure Data Engineering
This project presents an end-to-end data engineering pipeline designed to perform advanced analytics on an Olympic dataset using Microsoft Azure's cloud ecosystem. The solution integrates multiple Azure services and modern big data practices to showcase real-world data ingestion, processing, transformation, orchestration, and continuous integration/deployment (CI/CD).
# 🚀 Project Overview
The Olympic Data Analysis project leverages Azure’s cloud-native tools to ingest, transform, and analyze Olympic datasets in a scalable and automated manner. The architecture is designed for flexibility, modularity, and real-time processing using best practices in Azure Data Engineering.
#🧱 Key Components & Technologies
🔹 Azure Data Lake Storage (ADLS Gen2)
Centralized storage of raw and curated Olympic datasets.
Hierarchical namespace enabled for efficient data management.
🔹 Azure DevOps
Used for project management, code versioning, and CI/CD pipeline automation.
Git integration with Azure Data Factory and Databricks notebooks.
🔹 Azure Data Factory (ADF)
Configured with Git-based source control for pipeline development.
Built parameterized pipelines using ForEach activity for dynamic execution.
Ingested data directly from GitHub to ADLS.
Generated ARM templates for seamless deployment across environments.
<img width="1190" alt="Screenshot 2025-05-05 at 12 05 25 AM" src="https://github.com/user-attachments/assets/ead802e2-45a1-4d1d-b4f1-de2f608eb20d" />
<img width="657" alt="Screenshot 2025-05-05 at 12 05 32 AM" src="https://github.com/user-attachments/assets/fa7e9057-72a5-4b8b-a17b-25554da619f0" />
🔹 Azure Databricks
Performed big data transformations using PySpark on Apache Spark clusters.
Managed metadata with Unity Catalog and Hive Metastore integration.
Built dynamic, parameterized notebooks using dbutils for runtime control.
Orchestrated workflows using Databricks Workflows for modular pipeline execution.
Implemented Change Data Capture (CDC) and Spark Structured Streaming for real-time processing.
<img width="1036" alt="Screenshot 2025-05-04 at 4 05 08 PM" src="https://github.com/user-attachments/assets/37f750f4-d1ec-4eb4-90e7-4751ab17f812" />
#📦 CI/CD Implementation
Developed reusable templates and pipelines for automated deployment using Azure DevOps.
Managed infrastructure and pipeline lifecycle using GitOps principles.
# 🔄 Data Flow Architecture
Source: Olympic dataset hosted on GitHub.
Ingestion: ADF pipeline ingests data to ADLS.
Processing: Databricks handles ETL with PySpark.
Cataloging: Unity Catalog registers and manages datasets.
Streaming & CDC: Enabled real-time updates via Spark Structured Streaming.
Orchestration: Databricks Workflows control job sequencing and monitoring.
#📊 Outcomes
Built a scalable, production-ready data pipeline using Azure tools.
Achieved automation and reproducibility via CI/CD and parameterization.
Enabled robust orchestration and real-time insights on complex data using Apache Spark. 
