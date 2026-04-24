# Azure-Synapse-Analytics

Azure Synapse Analytics is used as a unified data platform to handle everything from data ingestion to advanced analytics—all in one place.

This project demonstrates an end-to-end data engineering workflow built on Azure Synapse Analytics. It showcases how to ingest, transform, and analyze NYC datasets using pipelines, Spark notebooks, and SQL scripts within a unified analytics environment.

### The solution leverages Synapse’s integrated capabilities to:

Ingest data from external sources
Transform and process data using Spark
Orchestrate workflows with pipelines
Perform analysis using SQL

Data Source → Linked Services → Pipeline → Spark Notebooks → SQL Analysis

## Components Explained
### Integration Runtime
AutoResolveIntegrationRuntime
Handles secure data movement across services.

### Linked Services
Define connections to external data sources (e.g., storage, databases).

### Notebooks (Apache Spark)
Load raw data
Perform transformations and cleaning
Execute analysis

### Pipelines
Automate workflow execution
Manage dependencies between tasks

### SQL Scripts
Perform exploratory data analysis (EDA)
Query processed datasets

