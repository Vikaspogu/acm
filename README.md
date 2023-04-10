# ACM IaC

## Getting Started

Pre-requisites:

- OpenShift 4.x cluster

Install OpenShift-GitOps operator(ArgoCD)

```bash
oc apply -f bootstrap/openshift-gitops/subscription.yaml
```

Update Argo instance to enable helm plugin, ability to refer from root directory and custom health checks

```bash
oc apply -f bootstrap/openshift-gitops/argocd.yaml
```
