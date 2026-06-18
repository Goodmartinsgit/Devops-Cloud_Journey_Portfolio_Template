# GitOps & Platform Engineering

This subdirectory houses declarative cluster deployment files and synchronization configurations using GitOps tools.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Understanding the GitOps Mental Model**
  * **Objective**: **Scenario:** You are a new DevOps engineer joining a company. They currently deploy applications by running `kubectl apply` from their CI pipeline. You have been asked to identify what problems this creates and propose a GitOps approach.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-understanding-the-gitops-mental-model/](./tasks/task-01-understanding-the-gitops-mental-model/)`
- [ ] **Task 2: Deploy ArgoCD with App of Apps on EKS**
  * **Objective**: **Scenario:** You are setting up GitOps for a company that has three Kubernetes workloads: a web frontend, an API backend, and a monitoring stack (Prometheus). All manifests should be managed in Git and automatically synced by ArgoCD.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-deploy-argocd-with-app-of-apps/](./tasks/task-02-deploy-argocd-with-app-of-apps/)`
- [ ] **Task 3: Install Flux and Migrate an Application**
  * **Objective**: **Scenario:** Your team currently uses ArgoCD to deploy a web application. You want to evaluate Flux by migrating one application from ArgoCD to Flux and comparing the experience.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-install-flux-and-migrate-an-application/](./tasks/task-03-install-flux-and-migrate-an-application/)`
- [ ] **Task 4: Multi-Environment ApplicationSet**
  * **Objective**: **Scenario:** Your company has 5 microservices and 3 environments (dev, staging, prod). You need each service deployed to each environment, with environment-specific configurations.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-multi-environment-applicationset/](./tasks/task-04-multi-environment-applicationset/)`
- [ ] **Task 5: Implement End-to-End Environment Promotion**
  * **Objective**: **Scenario:** Set up a three-tier promotion pipeline where changes flow dev → staging → prod with automated dev deployment, automated staging promotion via PR (after tests pass), and manual production promotion requiring approval.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-implement-end-to-end-environment-promotion/](./tasks/task-05-implement-end-to-end-environment-promotion/)`
- [ ] **Task 6: Build a Three-Tier Kustomize Structure**
  * **Objective**: **Scenario:** You have a web application that needs different configurations in dev, staging, and production. Build a Kustomize structure that manages all three environments with minimal duplication.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-build-a-three-tier-kustomize-structure/](./tasks/task-06-build-a-three-tier-kustomize-structure/)`
- [ ] **Task 7: Design an Internal Developer Platform**
  * **Objective**: **Scenario:** You are the first Platform Engineer at a 50-person startup that has 5 product teams. Currently, each team manages their own Kubernetes configs, each has built their own CI pipeline structure, and there is no standard way to provision databases or create new services.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-design-an-internal-developer-platform/](./tasks/task-07-design-an-internal-developer-platform/)`
- [ ] **Task 8: Set Up Backstage with Your Service Catalog**
  * **Objective**: **Scenario:** Your engineering organisation has 6 services. You need to set up Backstage, register all services, and write TechDocs for the most important one.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-set-up-backstage-with-your-service/](./tasks/task-08-set-up-backstage-with-your-service/)`
- [ ] **Task 9: Deploy Crossplane with Database and Cache Abstractions**
  * **Objective**: **Scenario:** Your platform team wants to give developers a simple way to request PostgreSQL databases and Redis caches without knowing the underlying AWS details.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-deploy-crossplane-with-database-and-cache/](./tasks/task-09-deploy-crossplane-with-database-and-cache/)`
- [ ] **Task 10: Build a Self-Service Environment Provisioner**
  * **Objective**: **Scenario:** Build a complete self-service system where a developer opens a PR and automatically gets a preview environment deployed to Kubernetes with a unique URL.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-build-a-self-service-environment-provisioner/](./tasks/task-10-build-a-self-service-environment-provisioner/)`
- [ ] **Task 11: Implement DORA Metrics Collection**
  * **Objective**: **Scenario:** Your platform team wants to establish a baseline of your current engineering performance and track improvement over time.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-implement-dora-metrics-collection/](./tasks/task-11-implement-dora-metrics-collection/)`

---
[⬅️ Back to Containers Module](../README.md)
