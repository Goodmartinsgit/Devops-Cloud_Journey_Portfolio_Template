# Data Engineering for DevOps

This subdirectory contains database replication configurations, replication diagnostic logs, and data processing task configs.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Build a Data Pipeline (App Events → Kafka → Kinesis Firehose → S3 → Athena → Grafana)**
  * **Objective**: Build an end-to-end data pipeline that ingests application events, streams them through Kafka and Kinesis Firehose, lands them in S3, makes them queryable via Athena, and visualises them in Grafana.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-build-a-data-pipeline-app-events/](./tasks/task-01-build-a-data-pipeline-app-events/)`
- [ ] **Task 2: Set Up Airflow on Kubernetes — Build a DAG That Runs Daily ETL**
  * **Objective**: Deploy Airflow on a Kubernetes cluster using the KubernetesExecutor, then build a DAG that runs a daily ETL pipeline.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-set-up-airflow-on-kubernetes-build/](./tasks/task-02-set-up-airflow-on-kubernetes-build/)`
- [ ] **Task 3: Write dbt Models That Transform Raw App Data into Analytics-Ready Tables**
  * **Objective**: Build a complete dbt project with staging, intermediate, and mart layers that transform the raw event data from Task 1 into analytics-ready tables.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-write-dbt-models-that-transform-raw/](./tasks/task-03-write-dbt-models-that-transform-raw/)`
- [ ] **Task 4: Build a Streaming Analytics Dashboard**
  * **Objective**: Build a real-time dashboard showing event counts and user activity using Kafka Streams, with output visible in Grafana.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-build-a-streaming-analytics-dashboard/](./tasks/task-04-build-a-streaming-analytics-dashboard/)`
- [ ] **Task 5: (Continued): Great Expectations Setup — Data Quality Tests on Pipeline, Fail on Schema Drift**
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-continued-great-expectations-setup-data-quality/](./tasks/task-05-continued-great-expectations-setup-data-quality/)`
- [ ] **Task 6: Set Up a Data Lake on S3 with Iceberg Table Format — Query with Athena, Visualise in Grafana**
  * **Objective**: Set up a production-grade data lake using Apache Iceberg on S3, register tables in AWS Glue, query with Athena, and visualise in Grafana.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-set-up-a-data-lake-on/](./tasks/task-06-set-up-a-data-lake-on/)`
- [ ] **Task 7: Write dbt Models for Analytics — Full Pipeline Test**
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-write-dbt-models-for-analytics-full/](./tasks/task-07-write-dbt-models-for-analytics-full/)`

---
[⬅️ Back to Advanced Architecture Module](../README.md)
