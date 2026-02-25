# Kubernetes in Docker

* kind [installation](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
* kubectl [installation](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-kubectl-binary-with-curl-on-linux)

## Install Cluster

```bash
kind create cluster --name nebula --config cluster.yaml
kind create cluster --name orion --config cluster.yaml

kubectl cluster-info --context kind-nebula
kubectl get nodes
```
