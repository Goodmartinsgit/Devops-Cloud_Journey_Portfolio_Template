# Multi-Cloud & FinOps

This subdirectory houses cloud resource cost audit files, tagging policies, and unused assets cleanup scripts.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Deploy to AWS + GCP Using Terraform — Test Failover**
  * **Objective**: Deploy the same application (a simple web server) to both AWS and GCP using Terraform. Demonstrate that if you point your DNS to the GCP deployment, the application continues to work — simulating failover.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-deploy-to-aws-gcp-using-terraform/](./tasks/task-01-deploy-to-aws-gcp-using-terraform/)`
- [ ] **Task 2: Build a FinOps Dashboard in Grafana**
  * **Objective**: Build a Grafana dashboard showing daily cloud spend by service, with anomaly detection and budget tracking.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-build-a-finops-dashboard-in-grafana/](./tasks/task-02-build-a-finops-dashboard-in-grafana/)`
- [ ] **Task 3: Rightsizing Exercise**
  * **Objective**: Analyse EC2 instances in your AWS account, identify over-provisioned instances, resize them, and document the savings.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-rightsizing-exercise/](./tasks/task-03-rightsizing-exercise/)`
- [ ] **Task 4: Purchase Reserved Instances and Calculate Break-Even**
  * **Objective**: Using your EC2 usage data, identify suitable workloads, purchase Reserved Instances for the baseline, and calculate the break-even point and annual savings.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-purchase-reserved-instances-and-calculate-break/](./tasks/task-04-purchase-reserved-instances-and-calculate-break/)`
- [ ] **Task 5: Spot Instances for Non-Critical Workloads**
  * **Objective**: Configure a CI/CD build agent ASG using mixed instances (on-demand baseline, Spot scale-out). Implement graceful shutdown on interruption.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-spot-instances-for-non-critical-workloads/](./tasks/task-05-spot-instances-for-non-critical-workloads/)`
- [ ] **Task 6: Set Up Kubecost and Identify Top Cost Drivers**
  * **Objective**: Install Kubecost on your K8s cluster, identify the top 5 cost drivers at namespace level, and document rightsizing recommendations.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-set-up-kubecost-and-identify-top/](./tasks/task-06-set-up-kubecost-and-identify-top/)`
- [ ] **Task 7: Integrate Infracost into GitHub Actions**
  * **Objective**: Set up the full Infracost GitHub Actions integration so that every infrastructure PR shows a cost diff.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-integrate-infracost-into-github-actions/](./tasks/task-07-integrate-infracost-into-github-actions/)`

---
[⬅️ Back to Advanced Architecture Module](../README.md)
