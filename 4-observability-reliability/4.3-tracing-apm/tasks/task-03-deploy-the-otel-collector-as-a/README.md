# Task 3: Deploy the OTel Collector as a Kubernetes DaemonSet

## Objective

A **DaemonSet** ensures one pod runs on every node in your cluster. For the OTel Collector, this means every node has a local Collector that applications can send spans to, without going over the network to a central Collector.

<!-- LOG_OUTPUT -->
