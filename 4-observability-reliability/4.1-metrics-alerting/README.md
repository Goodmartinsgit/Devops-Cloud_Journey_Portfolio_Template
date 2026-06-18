# Metrics & Alerting

This subdirectory stores configurations, rules files, and dashboards validating metrics gathering and alerting setups.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Deploy the Full LGTM Stack on Kubernetes Using Helm**
  * **Objective**: Deploy Loki, Grafana, Tempo, and Mimir on a Kubernetes cluster using Helm, and verify all components are communicating.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-deploy-the-full-lgtm-stack-on/](./tasks/task-01-deploy-the-full-lgtm-stack-on/)`
- [ ] **Task 2: Write 10 Production PromQL Queries**
  * **Objective**: **Setup:** Prometheus scraping your Node.js app (Task 2) or kube-prometheus-stack (Task 11).
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-write-10-production-promql-queries/](./tasks/task-02-write-10-production-promql-queries/)`
- [ ] **Task 3: Instrument a Node.js App with prom-client**
  * **Objective**: **Setup:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-instrument-a-nodejs-app-with-prom/](./tasks/task-03-instrument-a-nodejs-app-with-prom/)`
- [ ] **Task 4: Deploy kube-prometheus-stack — Complete K8s Monitoring**
  * **Objective**: Deploy the complete kube-prometheus-stack: Prometheus, Alertmanager, Grafana, node_exporter, kube-state-metrics, and pre-built dashboards.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-deploy-kube-prometheus-stack-complete-k8s/](./tasks/task-04-deploy-kube-prometheus-stack-complete-k8s/)`
- [ ] **Task 5: Build a Complete RED + USE Grafana Dashboard**
  * **Objective**: **Dashboard structure:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-build-a-complete-red-use-grafana/](./tasks/task-05-build-a-complete-red-use-grafana/)`
- [ ] **Task 6: Configure Alertmanager Three-Tier Routing**
  * **Objective**: **Complete `alertmanager.yml`:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-configure-alertmanager-three-tier-routing/](./tasks/task-06-configure-alertmanager-three-tier-routing/)`
- [ ] **Task 7: Configure Multi-Window Multi-Burn-Rate SLO Alerts**
  * **Objective**: Configure Google-style multi-window multi-burn-rate alerts for a 99.9% availability SLO.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-configure-multi-window-multi-burn-rate/](./tasks/task-07-configure-multi-window-multi-burn-rate/)`
- [ ] **Task 8: Deploy Thanos in Sidecar Mode with 90-Day Retention**
  * **Objective**: **Step 1: Set up local MinIO for object storage**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-deploy-thanos-in-sidecar-mode-with/](./tasks/task-08-deploy-thanos-in-sidecar-mode-with/)`
- [ ] **Task 9: Set up Datadog Agent on EKS — Compare with Prometheus/Grafana**
  * **Objective**: **Step 1:** Sign up for a free trial at datadoghq.com. Get your API key from Organisation Settings → API Keys.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-set-up-datadog-agent-on-eks/](./tasks/task-09-set-up-datadog-agent-on-eks/)`
- [ ] **Task 10: Configure CloudWatch Container Insights on EKS**
  * **Objective**: **Step 1: Create IAM permissions** (see Chapter 13) and attach to EKS node role.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-configure-cloudwatch-container-insights-on-eks/](./tasks/task-10-configure-cloudwatch-container-insights-on-eks/)`
- [ ] **Task 11: Write a Custom Python Exporter for Business Metrics**
  * **Objective**: Write a Python exporter exposing orders/min, revenue/hr, and active shopping carts.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-write-a-custom-python-exporter-for/](./tasks/task-11-write-a-custom-python-exporter-for/)`
- [ ] **Task 12: Simulate a Memory Leak — Detect, Alert, Respond, Write the Runbook**
  * **Objective**: The most realistic task in this book. Simulate a memory leak in a containerised application, detect it in Grafana as it grows, allow the alert to fire, and write the runbook response.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-12-simulate-a-memory-leak-detect-alert/](./tasks/task-12-simulate-a-memory-leak-detect-alert/)`

---
[⬅️ Back to Observability Module](../README.md)
