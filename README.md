# Hi, I'm Sushma 👋

**Senior Data Engineer** · Bengaluru, India · 8+ years building production data platforms across **AWS · Databricks · GCP · Azure**.

I design and ship data pipelines that are reliable, observable, cost-aware, and 2026-current. Currently a full-time engineer at **Equal Experts**, with parallel freelance work building AWS-native data pipelines for **top BFSI & Telecom clients**.

📍 **13 public portfolio repos** spanning streaming CDC, lakehouses, orchestration, analytics engineering, MLOps feature stores, RAG / AI-data platforms, Spark perf, and SAP migration — all 2026-forward (Iceberg · Polaris · liquid clustering · OpenLineage · dbt 1.9 semantic layer · Databricks Asset Bundles · GX Core 1.x).

---

## 🛠️ Tech stack (in production)

| Area | Tools |
|---|---|
| **Lakehouse / storage formats** | Delta Lake 3.2+, Apache Iceberg, Apache Hudi, Parquet · liquid clustering, Z-ORDER, deletion vectors, CDF, time travel |
| **Streaming / CDC** | Apache Kafka (MSK, Redpanda), Debezium 2.6, Kafka Connect, Flink 1.19, Kinesis Data Streams/Firehose |
| **Batch / transform** | Apache Spark 3.5, PySpark, Scala-Spark, Databricks (DBR 15.4 LTS), DLT, AWS Glue 5.0, EMR on EKS / EMR Serverless |
| **Orchestration** | Apache Airflow 2.9 (TaskFlow · Datasets · dynamic task mapping · deferrable sensors), AWS Step Functions, Databricks Asset Bundles, Control-M |
| **Analytics engineering** | dbt 1.9 (microbatch incremental, native unit tests, Semantic Layer / MetricFlow), dbt Data Vault 2.0 |
| **Warehouses** | Snowflake, BigQuery, Redshift, Postgres, DuckDB (CI) |
| **Governance / catalog** | Unity Catalog, **Apache Polaris** (OSS Unity), AWS Lake Formation, Hive Metastore, Glue Catalog |
| **Data quality** | Great Expectations Core 1.x, Soda Core, dbt-expectations, dbt-unit-testing |
| **Lineage / observability** | **OpenLineage**, Marquez, DataHub, OpenMetadata, elementary-data |
| **AI / RAG data engineering** | pgvector, Qdrant, LanceDB, hybrid retrieval (BM25 + vector + RRF + reranker), RAGAS metrics, LangFuse |
| **ML platform** | SageMaker Feature Store, Databricks Feature Store, Feast, Model Monitor, PSI/KS drift detection |
| **IaC / CI/CD** | Terraform (+ CDKTF), Jenkins, GitHub Actions, GitLab CI, Docker, docker-compose |
| **Languages** | Python, SQL, Scala, Java, Shell |
| **BI / semantic** | Apache Superset, Tableau, Power BI, Qlik Sense |

---

## ⭐ Pinned projects

Six repos that together tell the full story of a 2026-ready senior-DE portfolio:

### 🧠 [rag-data-platform-vector-lakehouse](https://github.com/sushmakl95/rag-data-platform-vector-lakehouse)
Production-grade **Retrieval-Augmented Generation** data platform built as a data-engineering problem, not a notebook demo. Lakehouse-backed chunks (Delta/Iceberg) + multi-backend vector stores (pgvector / Qdrant / LanceDB) + **hybrid retrieval** (BM25 + vector + RRF + cross-encoder reranker) + RAGAS-style eval on a committed golden set. FastAPI serving, Airflow DAGs for ingest + re-embedding, LangFuse tracing. 72 hermetic pytest unit tests; zero-cost CI.

### 🎯 [databricks-streaming-cdc-governance-lakehouse](https://github.com/sushmakl95/databricks-streaming-cdc-governance-lakehouse)
Databricks-idiomatic streaming CDC lakehouse on open-source `delta-spark` + PySpark + Scala. Debezium → Structured Streaming (exactly-once, watermarks, stream-stream joins) → SCD2 MERGE → **Z-ORDER + liquid clustering + CDF + time travel**. **Apache Polaris** OSS Unity Catalog. **Databricks Asset Bundles** + DLT-style declarative pipelines. Governance policies (row filters, column masks, LF-tags). 34 tests green.

### 🪂 [airflow-multicloud-medallion-platform](https://github.com/sushmakl95/airflow-multicloud-medallion-platform)
Apache **Airflow 2.9** orchestrating end-to-end multi-cloud medallion: Debezium CDC → Kafka → PySpark+Scala → Delta Lake across AWS (LocalStack) · Azure (Azurite) · GCP. **4 showcase DAGs** demonstrating TaskFlow, Datasets, dynamic task mapping, deferrable sensors, pools, SLAs. Custom operators (Delta merge · Azure Blob · ODCS contract validation). OpenLineage → Marquez + DataHub. Great Expectations + Soda Core.

### 🏗️ [aws-serverless-lakehouse-lakeformation](https://github.com/sushmakl95/aws-serverless-lakehouse-lakeformation)
Event-driven serverless lakehouse on AWS: **6 distinct Lambda trigger patterns** (API GW · S3/EventBridge · SQS · DDB Streams · Kinesis · scheduled) + **Step Functions** (Map, Parallel, Choice, Catch/Retry) + **Glue PySpark** medallion + **Apache Iceberg** + **Lake Formation** LF-tags/data-cell filters + Athena + Superset BI. Terraform HCL + Terraform CDK parity. Runs on LocalStack at zero cost.

### 📊 [dbt-datavault-snowflake-bigquery-observability](https://github.com/sushmakl95/dbt-datavault-snowflake-bigquery-observability)
Multi-adapter dbt **Data Vault 2.0** — Snowflake · BigQuery · DuckDB (CI) · Postgres. Hand-rolled adapter-agnostic `hash_key` / `hash_diff` macros. Hubs / Links / Satellites → PIT / Bridge → dimensional Marts + **dbt Semantic Layer** (MetricFlow). Triple-orchestrated: Airflow DAG + AWS Step Functions + Control-M simulator. 77 tests across generic, dbt-expectations, singular, relationships.

### 🌪️ [aws-msk-emr-streaming-platform](https://github.com/sushmakl95/aws-msk-emr-streaming-platform)
Real-time streaming platform on **AWS MSK + EMR on EKS + EMR Serverless + Flink 1.19** with hot/warm/cold sink fan-out (Redis / OpenSearch / ClickHouse / S3 Iceberg), WebSocket push via MSK → Lambda, and a parallel Databricks Streaming comparison track. **Apache Polaris** REST catalog, **OpenLineage Flink** listener, 19 Terraform modules.

---

## 📂 Explore more

| Theme | Repos |
|---|---|
| **AI / LLM data** | [rag-data-platform-vector-lakehouse](https://github.com/sushmakl95/rag-data-platform-vector-lakehouse) |
| **Lakehouse + governance** | [databricks-streaming-cdc-governance-lakehouse](https://github.com/sushmakl95/databricks-streaming-cdc-governance-lakehouse) · [aws-serverless-lakehouse-lakeformation](https://github.com/sushmakl95/aws-serverless-lakehouse-lakeformation) · [lakehouse-iot-telemetry-pipeline](https://github.com/sushmakl95/lakehouse-iot-telemetry-pipeline) |
| **Streaming & CDC** | [aws-msk-emr-streaming-platform](https://github.com/sushmakl95/aws-msk-emr-streaming-platform) · [aws-glue-cdc-framework](https://github.com/sushmakl95/aws-glue-cdc-framework) |
| **Orchestration** | [airflow-multicloud-medallion-platform](https://github.com/sushmakl95/airflow-multicloud-medallion-platform) |
| **Analytics engineering** | [dbt-datavault-snowflake-bigquery-observability](https://github.com/sushmakl95/dbt-datavault-snowflake-bigquery-observability) · [dbt-bigquery-analytics-platform](https://github.com/sushmakl95/dbt-bigquery-analytics-platform) |
| **MLOps / Feature store** | [aws-sagemaker-databricks-feature-store](https://github.com/sushmakl95/aws-sagemaker-databricks-feature-store) |
| **Data quality** | [aws-databricks-dq-platform](https://github.com/sushmakl95/aws-databricks-dq-platform) |
| **Performance engineering** | [spark-performance-optimization-playbook](https://github.com/sushmakl95/spark-performance-optimization-playbook) — 13 benchmarks incl. liquid clustering, deletion vectors, Apache DataFusion Comet |
| **Enterprise migration** | [sap-mdm-cloud-migration-platform](https://github.com/sushmakl95/sap-mdm-cloud-migration-platform) |

---

## 💼 What I ship

- **End-to-end platform design** — ingestion (CDC / streaming / batch) → transform → BI + ML serving
- **Performance tuning** — 5–50× speedups via partition design, join strategy, executor right-sizing, liquid clustering, deletion vectors
- **Cost engineering** — every pipeline has cost-per-run, lifecycle policies, idle-cost minimization documented
- **Testing rigor** — DQ gates, unit/integration tests, CI green on first push
- **Governance** — Unity Catalog / Polaris / Lake Formation tag-based access, OpenLineage lineage, ODCS data contracts
- **Zero-cost demos** — LocalStack / Azurite / DuckDB / Redpanda mean every repo runs end-to-end on a laptop

---

## 📫 Get in touch

- 💼 [LinkedIn](https://www.linkedin.com/in/sushmakl1995/)
- ✉️ sushmakl95@gmail.com
- 🐙 Every repo above is a click away

---

_Open to **senior / staff data engineering** and **data-platform team leadership** roles — AWS · Databricks · Snowflake · GCP heavy preferred._
