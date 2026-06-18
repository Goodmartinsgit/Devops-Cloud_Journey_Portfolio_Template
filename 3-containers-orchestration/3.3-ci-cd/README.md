# CI/CD & Pipeline Engineering

This subdirectory houses automated pipeline configuration files (GitHub Actions, GitLab CI) demonstrating continuous integration and delivery.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Mindset Audit**
  * **Objective**: Before writing any YAML, do this exercise:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-mindset-audit/](./tasks/task-01-mindset-audit/)`
- [ ] **Task 2: Build a GitHub Actions CI/CD Pipeline**
  * **Objective**: Build a complete pipeline: lint → unit test → build Docker image → scan → push to ECR → deploy to EKS
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-build-a-github-actions-cicd-pipeline/](./tasks/task-02-build-a-github-actions-cicd-pipeline/)`
- [ ] **Task 3: GitLab CI Pipeline with Review Apps**
  * **Objective**: Build a complete `.gitlab-ci.yml` that: - Lints and tests on every push - Deploys a review app for every merge request
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-gitlab-ci-pipeline-with-review-apps/](./tasks/task-03-gitlab-ci-pipeline-with-review-apps/)`
- [ ] **Task 4: Jenkins Declarative Pipeline**
  * **Objective**: Create a complete Jenkins declarative pipeline with a shared library:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-jenkins-declarative-pipeline/](./tasks/task-04-jenkins-declarative-pipeline/)`
- [ ] **Task 5: task-lint.yaml**
  * **Objective**: apiVersion: tekton.dev/v1     # Tekton API version kind: Task                    # Kubernetes resource kind metadata:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-task-lintyaml/](./tasks/task-05-task-lintyaml/)`
- [ ] **Task 6: task-docker-build-push.yaml**
  * **Objective**: apiVersion: tekton.dev/v1 kind: Task metadata:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-task-docker-build-pushyaml/](./tasks/task-06-task-docker-build-pushyaml/)`
- [ ] **Task 7: Tekton Pipeline Mirroring GitHub Actions**
  * **Objective**: Build a Tekton pipeline that mirrors your GitHub Actions workflow (lint → test → build → scan → deploy):
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-tekton-pipeline-mirroring-github-actions/](./tasks/task-07-tekton-pipeline-mirroring-github-actions/)`
- [ ] **Task 8: Canary Deployment**
  * **Objective**: **Canary deployment** routes a small percentage of real traffic to the new version. If the new version performs well (no increase in errors, latency stays low), you gradually increase traffic. If something goes wrong, you route traffic back to the stable version.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-canary-deployment/](./tasks/task-08-canary-deployment/)`
- [ ] **Task 9: Implement Blue/Green with Auto-Rollback**
  * **Objective**: Using the scripts and YAML in this chapter, build a complete blue/green deployment pipeline that: 1. Deploys the new version to the inactive environment 2. Runs smoke tests against it before switching traffic
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-implement-bluegreen-with-auto-rollback/](./tasks/task-09-implement-bluegreen-with-auto-rollback/)`
- [ ] **Task 10: Implement Feature Flags with Unleash**
  * **Objective**: Build a complete feature flag workflow:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-implement-feature-flags-with-unleash/](./tasks/task-10-implement-feature-flags-with-unleash/)`
- [ ] **Task 11: OIDC + SLSA Level 2**
  * **Objective**: Build a complete secure pipeline:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-oidc-slsa-level-2/](./tasks/task-11-oidc-slsa-level-2/)`
- [ ] **Task 12: Build a Release Pipeline**
  * **Objective**: Create a complete release pipeline:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-12-build-a-release-pipeline/](./tasks/task-12-build-a-release-pipeline/)`

---
[⬅️ Back to Containers Module](../README.md)
