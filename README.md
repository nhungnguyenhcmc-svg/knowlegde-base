# knowlegde-base
Personal data analytics &amp; engineering knowledge base

# A.  Key components of a modern data stack
A modern data platform consists of serveral layers, each handling a different aspect of data processing.

# A.1. Data Sources
we need to ingest and integrate it into our platform
- Structured Data - transactional databases (PostgreSQL, MySQL, Oracle, etc.).
- Semi-Structured Date & Unstructured Data - logs, documents, emails.
- Web & User Interaction Date - clickstream, mobile app interactions.
- APIs & Third-Party Data - partner integrations, SaaS applications.
- Media & Entertainment Data - images, videos, audio files.

# A.2. Orchestration - keeping data workflows in sync
schedule, trigger, and monitor data workflows
- Apache Airflow, Dagster, Prefect, Astronomer - popular orchestration tools for managing data pipelines.
- Azure Data Factory (ADF), AWS Glue - cloud-native solutions that integrate directly with their respective ecosystems.
- dbt (data build tool) - primarily for transforming data in a warehouse using SQL.

# A.3. Data ingestion & integration
# A.3.1. Batch data integration & ETL
- Apache Spark - the go-to framework for distributed data processing.
- Stitch, Fivetran, Matillion - low-code ETL tools that sync data from SaaS applications.
- Azure Data Factory, AWS Glue, Airbyte - cloud-based ETL solutions.

# A.3.2. Streaming & Real-time data processing
- Azure Event Hub, AWS Kinesis, GCP Pub/Sub - cloud-native event streaming services.
- Apache Kafke, Apache Flink, Apache Beam - open-source stream processing frameworks.
- Spark Streaming - real-time data processing using Apache Spark.

# A.4. Data Warehousing - storing and querying large datasets
- Snowflake - data warehouse
- Databricks - a lakehouse that combines data lakes and warehouses.
- Azure Synapse, AWS Redshift, GCP BigQuery - cloud-based enterprise solutions.

# A.5. Data Storage - object storage & file formats
- Azure ADLS2, AWS S3, GCP Storage, HDFS - store raw data before transformation.
- Note: to store data efficiently, we rely on optimized file formats like: Parquet, ORC, Avro, Delta, Iceberg, Hudi - columnar and transactional formats; JSON, csv, xml - tradional formats for compatibility.

# A.6. Platform Management - security, governance & observability

IAM & Security
- Azure AD, AWS Cognito, GCP Identity, Okta - identity & access management (IAM).
- CyberArk, HashiCorp Vault - secure credentials & secrets.

Data governance & metadata management
- Collibra, Apache Atlas, Azure Purview - define policies, track lineage, and manage metadata.
- Unity Catalog, Hive Metastore, Dremio - manage structured metadata.

Observability & monitoring
- Grafana, Prometheus, Splunk, Datadog - monitor pipelines & infrastructure health.

# A.7. Data Consumption - unlocking insights from data

Dashboarding & BI tools
- Tableau, Power BI, Qlik Sense, LookerStudio

APIs & Data sharing
- GraphQL, FastAPI - expose data via APIs
- Delta Sharing, Snowflake Data Sharing - secure data collaboration across organizations.

# A.8. Machine Learning & AI - unlocking advanced insights
- Databricks ML, AWS SageMaker, GCP VertexAI, Azure ML - Cloud ML platforms.
- TensorFlow, PyTorch, Scikit-learn, MLflow - open-source frameworks for AI/ML.


