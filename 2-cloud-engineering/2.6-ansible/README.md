# Ansible & Configuration Management

This subdirectory stores Ansible Inventories, Playbooks, Roles structures, and logs showing node provisioning automation.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Install Ansible and Configure 5 EC2 Instances as Managed Nodes**
  * **Objective**: **Scenario:** You have just been given five newly-launched EC2 instances. Your job is to install Ansible on your control node and verify you can manage all five instances.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-install-ansible-and-configure-5-ec2/](./tasks/task-01-install-ansible-and-configure-5-ec2/)`
- [ ] **Task 2: Write a Playbook That Configures a Complete Web Server**
  * **Objective**: **Scenario:** Write a playbook that configures nginx with SSL, a custom configuration, and a firewall. This mirrors what a DevOps engineer would write for a production web server.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-write-a-playbook-that-configures-a/](./tasks/task-02-write-a-playbook-that-configures-a/)`
- [ ] **Task 3: Dynamic Inventory + Variable-Driven Configuration**
  * **Objective**: **Scenario:** Your team uses the same playbook for both staging and production. Configure it using variables so that only the values differ between environments, not the logic.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-dynamic-inventory-variable-driven-configuration/](./tasks/task-03-dynamic-inventory-variable-driven-configuration/)`
- [ ] **Task 4: Generate nginx Virtual Host Configs from Inventory Variables**
  * **Objective**: **Scenario:** You manage 10 websites on the same server. Instead of maintaining 10 nginx config files manually, use a Jinja2 template and inventory variables to generate all configs automatically.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-generate-nginx-virtual-host-configs-from/](./tasks/task-04-generate-nginx-virtual-host-configs-from/)`
- [ ] **Task 5: tasks/main.yml**
  * **Objective**: - name: Include installation tasks include_tasks: install.yml tags: nginx_install
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-tasksmainyml/](./tasks/task-05-tasksmainyml/)`
- [ ] **Task 6: tasks/install.yml**
  * **Objective**: - name: Install nginx (RHEL/CentOS) yum: name: nginx
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-tasksinstallyml/](./tasks/task-06-tasksinstallyml/)`
- [ ] **Task 7: tasks/configure.yml**
  * **Objective**: - name: Remove default nginx site file: path: /etc/nginx/sites-enabled/default
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-tasksconfigureyml/](./tasks/task-07-tasksconfigureyml/)`
- [ ] **Task 8: Build a 'Baseline' Role**
  * **Objective**: **Scenario:** Every server in your organisation must meet a baseline: specific users created, security packages installed, SSH hardened, fail2ban configured.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-build-a-baseline-role/](./tasks/task-08-build-a-baseline-role/)`
- [ ] **Task 9: Encrypt All Sensitive Vars with CI-Safe Vault Pattern**
  * **Objective**: **Scenario:** Set up a Vault-secured variable structure that works in CI/CD.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-encrypt-all-sensitive-vars-with-ci/](./tasks/task-09-encrypt-all-sensitive-vars-with-ci/)`
- [ ] **Task 10: Write a Playbook That Updates, Tests, and Rolls Back**
  * **Objective**: **Scenario:** Write a playbook that updates all packages on a server, runs a health check, and automatically rolls back if the check fails.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-write-a-playbook-that-updates-tests/](./tasks/task-10-write-a-playbook-that-updates-tests/)`
- [ ] **Task 11: Strategy: Controlling Task Order Across Hosts**
  * **Objective**: Ansible's **strategy** controls how tasks are distributed across hosts.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-strategy-controlling-task-order-across-hosts/](./tasks/task-11-strategy-controlling-task-order-across-hosts/)`
- [ ] **Task 12: Configure Serial Rolling Update**
  * **Objective**: **Scenario:** Deploy a new application version to 20 web servers with zero downtime using serial rolling updates.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-12-configure-serial-rolling-update/](./tasks/task-12-configure-serial-rolling-update/)`
- [ ] **Task 13: Write a Playbook Using AWS Collections**
  * **Objective**: **Scenario:** Use the `amazon.aws` collection to provision infrastructure.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-13-write-a-playbook-using-aws-collections/](./tasks/task-13-write-a-playbook-using-aws-collections/)`
- [ ] **Task 14: Write a Molecule Test for Your nginx Role**
  * **Objective**: **Complete test scenario checking port 80, 443, and config validity:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-14-write-a-molecule-test-for-your/](./tasks/task-14-write-a-molecule-test-for-your/)`
- [ ] **Task 15: TASK [nginx : Install nginx] ******
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-15-task-nginx-install-nginx/](./tasks/task-15-task-nginx-install-nginx/)`
- [ ] **Task 16: TASK [Assert nginx is active] **** ok**
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-16-task-assert-nginx-is-active-ok/](./tasks/task-16-task-assert-nginx-is-active-ok/)`
- [ ] **Task 17: TASK [Assert port 80 is listening] **** ok**
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-17-task-assert-port-80-is-listening/](./tasks/task-17-task-assert-port-80-is-listening/)`
- [ ] **Task 18: TASK [Assert nginx config is valid] **** ok**
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-18-task-assert-nginx-config-is-valid/](./tasks/task-18-task-assert-nginx-config-is-valid/)`
- [ ] **Task 19: Deploy AWX and Set Up a Job Template**
  * **Objective**: **Step-by-step walkthrough:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-19-deploy-awx-and-set-up-a/](./tasks/task-19-deploy-awx-and-set-up-a/)`

---
[⬅️ Back to Cloud Engineering Module](../README.md)
