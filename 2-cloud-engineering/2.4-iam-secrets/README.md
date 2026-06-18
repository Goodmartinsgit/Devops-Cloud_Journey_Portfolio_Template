# IAM & Secrets Management

This subdirectory contains configurations, policy templates, and scripts validating cloud-level authorization models and application secrets lifecycle management.

## 📋 Task Checklist & Progress

- [ ] **Task 1: **
  * **Objective**: **Task: IAM Audit — Review all users/roles in your AWS account, remove all unused permissions**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-task/](./tasks/task-01-task/)`
- [ ] **Task 2: **
  * **Objective**: Create an IAM policy that allows EC2 instance management, but only in `us-east-1` and `eu-west-1`, and only for `t3.micro`, `t3.small`, and `t3.medium` instance types.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-task/](./tasks/task-02-task/)`
- [ ] **Task 3: **
  * **Objective**: **Task: Set up AWS Secrets Manager with Lambda rotation for an RDS password — verify rotation works**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-task/](./tasks/task-03-task/)`
- [ ] **Task 4: **
  * **Objective**: There is no standalone task for this chapter — Parameter Store is used extensively in Chapters 5, 7, and 8. However, as an exercise:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-task/](./tasks/task-04-task/)`
- [ ] **Task 5: **
  * **Objective**: **Task: Deploy HashiCorp Vault on K8s using Helm, configure AWS auth, database secret engine for RDS**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-task/](./tasks/task-05-task/)`
- [ ] **Task 6: **
  * **Objective**: **Task: Implement Vault dynamic secrets for PostgreSQL — verify credentials are unique per request**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-task/](./tasks/task-06-task/)`
- [ ] **Task 7: **
  * **Objective**: **Task: Configure OIDC between GitHub Actions and AWS — deploy to EKS without static AWS credentials**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-task/](./tasks/task-07-task/)`
- [ ] **Task 8: **
  * **Objective**: **Task: Set up External Secrets Operator in K8s — sync secrets from Vault to K8s Secrets automatically**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-task/](./tasks/task-08-task/)`
- [ ] **Task 9: **
  * **Objective**: **Task: Configure cert-manager in K8s with Let's Encrypt — auto-issue and renew TLS certificates**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-task/](./tasks/task-09-task/)`
- [ ] **Task 10: **
  * **Objective**: **Task: Run TruffleHog and gitleaks on your entire git history — remediate any findings**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-task/](./tasks/task-10-task/)`
- [ ] **Task 11: **
  * **Objective**: **Task: Build a secrets management runbook: how to rotate, audit, and respond to a leaked secret**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-task/](./tasks/task-11-task/)`
- [ ] **Task 12: **
  * **Objective**: This chapter's principles tie together all previous chapters. The task is to implement a complete zero-trust posture for a sample microservices application:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-12-task/](./tasks/task-12-task/)`

---
[⬅️ Back to Cloud Engineering Module](../README.md)
