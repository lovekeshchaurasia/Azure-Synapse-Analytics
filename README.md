# Azure Synapse Analytics – End-to-End Implementation

This repository contains my complete hands-on learning and implementation of Azure Synapse Analytics, covering architecture, SQL pools, Spark pools, data lake integration, distributed tables, and advanced data loading techniques.

The project demonstrates how Synapse can be used to build scalable data warehousing and analytics solutions.

📌 Topics Covered
🔹 Azure Synapse Fundamentals

Azure Synapse Analytics Overview

Synapse Workspace Setup

Synapse Architecture (Compute Node & Control Node)

Dedicated SQL Pool

Serverless SQL Pool

Spark Pool

🔹 Synapse Architecture & Design

Medallion Architecture (Bronze, Silver, Gold layers)

Distributed Tables in Dedicated SQL Pool

Distribution Strategies:

Hash Distribution

Round Robin

Replicated Tables

🔹 Data Lake Integration

Azure Data Lake Storage Gen2

Managed Identity

Database Scoped Credentials

External Data Source

Linked Services

🔹 External Data Handling

Create External File Formats

Create External Tables

Query data using Serverless SQL Pool

Create Views in Serverless SQL

🔹 Data Loading & Transformation

COPY INTO command

PolyBase

CTAS (Create Table As Select)

CETAS (Create External Table As Select)

Loading external data into Synapse

🛠️ Technologies Used

Azure Synapse Analytics

Dedicated SQL Pool

Serverless SQL Pool

Azure Data Lake Storage Gen2

Azure Spark Pool

T-SQL

PolyBase

COPY INTO

🏗️ Architecture Overview

The implementation follows modern data warehouse best practices:

Raw data stored in Azure Data Lake (Bronze Layer)

Data processed and transformed using Spark / SQL

Structured tables created in Dedicated SQL Pool

External tables used for scalable querying

Optimized distribution strategies for performance

🚀 Key Learning Outcomes

Understanding Synapse MPP architecture

Designing distributed tables efficiently

Choosing correct distribution strategy

Using Serverless SQL for data lake querying

Implementing high-performance data loading techniques

Applying Medallion architecture in Synapse

🎯 Use Cases

Enterprise Data Warehousing

Big Data Analytics

ELT Processing

Lakehouse Architecture

Scalable Cloud Data Platforms
