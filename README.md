# Hi, I'm Sushma 👋

**Senior Data Engineer** · Bengaluru, India · 8+ years building data platforms across AWS and GCP.

I design and ship production data pipelines that are reliable, observable, and cost-aware. Currently a full-time engineer on the PDP J3 Sell team at **John Lewis Partnership**, with parallel freelance work building AWS-native data pipelines for **Mensa Brand Technologies**.

---

## 🛠️ Tech Stack

**Cloud & Infra:** AWS (Glue, Lambda, Step Functions, Redshift, Kinesis, EventBridge, Bedrock), GCP (BigQuery, Cloud Composer, GCS), Terraform, Docker

**Data Processing:** PySpark, Databricks, Delta Lake, dbt, Airflow (Cosmos), Apache Kafka, Debezium

**Storage:** Snowflake, Redshift, BigQuery, PostgreSQL, OpenSearch, S3, Delta Lake

**Languages:** Python, SQL, Bash

---

## 📚 Featured Projects

These four repos cover the breadth of a modern data engineering role — streaming CDC, batch analytics, lakehouse patterns, and performance engineering.

### 🏞️ [lakehouse-iot-telemetry-pipeline](https://github.com/sushmakl95/lakehouse-iot-telemetry-pipeline)
Multi-tenant IoT Lakehouse on **Databricks + Delta Lake** with Auto Loader, Delta Live Tables, medallion architecture (Bronze → Silver → Gold), SCD2 tracking, and Z-ORDER benchmarks (37× query speedup). 13 Terraform modules for full AWS deployment.

### 🔄 [aws-glue-cdc-framework](https://github.com/sushmakl95/aws-glue-cdc-framework)
Production-grade CDC pipeline: **MySQL → Debezium → Kinesis → S3 → AWS Glue (PySpark) → Redshift + Postgres + OpenSearch**. Multi-sink fanout with SCD2 merges, DynamoDB-backed idempotency, Step Functions orchestration, and complete local dev stack via Docker Compose.

### 📊 [dbt-bigquery-analytics-platform](https://github.com/sushmakl95/dbt-bigquery-analytics-platform)
Modern data stack reference: **dbt + BigQuery + Airflow (Cloud Composer)** with medallion layering (staging → intermediate → marts), SCD2 snapshots, exposures, source freshness SLAs, custom tests, and a documented 45× cost reduction via partition + cluster + incremental tuning.

### 🚀 [spark-performance-optimization-playbook](https://github.com/sushmakl95/spark-performance-optimization-playbook)
Battle-tested **Apache Spark tuning patterns with reproducible benchmarks**. 10 techniques — partition pruning, broadcast joins, AQE, skew handling, Z-ORDER, predicate pushdown, executor sizing, and more — each paired with measured before/after speedups runnable on a laptop.

---

## 💼 What I'm good at

- **End-to-end data platform design** — from ingestion (CDC, streaming, batch) through transformation to BI/ML serving layers
- **Performance tuning** — consistent 5-50× speedups on real production workloads through partition design, join strategy, and executor right-sizing
- **Cost engineering** — every pipeline I design has documented cost-per-run, lifecycle policies, and idle-cost minimization
- **Testing rigor** — DQ gates, custom generic + singular dbt tests, CI for every change

---

## 📫 Get in touch

- 💼 [LinkedIn](https://www.linkedin.com/in/sushmakl1995/)
- ✉️ sushmakl95@gmail.com

---

_Looking for senior / staff data engineering roles. Open to AWS / Databricks-heavy platforms, analytics engineering, and data-platform team leadership positions._
