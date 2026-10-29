# Eircom CP4I GitOps Repository

This repository contains declarative OpenShift / CP4I manifests managed by OpenShift GitOps (ArgoCD).

## Workloads
- `mq-workloads/`: IBM MQ QueueManager and MQSC configurations deployed into namespace `mq-argocd`.
- `ace-workloads/`: IBM App Connect Enterprise IntegrationRuntime and configurations deployed into namespace `ace-argocd`.
