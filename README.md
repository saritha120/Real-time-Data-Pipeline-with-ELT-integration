# Real-Time Recommendation System Pipeline

## Project Goal
Create a real-time recommendation system to suggest products to users based on their transaction history and product details. The system will be scalable, efficient, and capable of integrating with various tools to manage data flow from ingestion to recommendation generation.

## Setup Instructions

### 1. Data Ingestion
- **Tool:** Apache Kafka
- **Setup:** Create Kafka topics, set up producers to push data.

### 2. Data Storage
- **Tool:** Azure Blob Storage
- **Setup:** Create storage containers, configure data ingestion from Kafka.

### 3. Data Loading
- **Tool:** Snowpipe (Snowflake)
- **Setup:** Create Snowflake stages, configure Snowpipe.

### 4. Data Transformation
- **Tool:** dbt (Data Build Tool)
- **Setup:** Develop dbt models, set up transformations and tests.

### 5. Recommendation System Development
- **Tool:** Custom Python Scripts
- **Setup:** Implement recommendation algorithms.

### 6. Data Orchestration
- **Tool:** Apache Airflow
- **Setup:** Create Airflow DAGs for ETL tasks.

### 7. CI/CD
- **Tool:** GitHub Actions
- **Setup:** Create CI/CD pipelines for testing and deployment.

## Data Sets
- [Sales Data](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)
- [Product Data](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset)

## Directory Structure
- `ingestion/`: Kafka configurations and producers
- `storage/`: Azure Blob Storage setup
- `loading/`: Snowpipe configurations
- `transformation/`: dbt models and configurations
- `recommendation/`: Python scripts for recommendation algorithms
- `orchestration/`: Airflow DAGs
- `ci_cd/`: CI/CD configurations

## How to Run the Project
1. **Set up Kafka and create topics.**
2. **Configure Azure Blob Storage and data ingestion.**
3. **Load data into Snowflake using Snowpipe.**
4. **Transform data with dbt.**
5. **Develop and test recommendation algorithms.**
6. **Orchestrate tasks with Apache Airflow.**
7. **Automate testing and deployment with CI/CD pipelines.**
