# Kubeadm — Kubernetes Cluster Setup Tool

## 1. What is kubeadm?

`kubeadm` is a Kubernetes command-line tool used to initialize a control plane and join nodes to a Kubernetes cluster.

## 2. Important Commands

- `kubeadm init` — Initializes the control plane.
- `kubeadm join` — Joins a node to the cluster.
- `kubeadm upgrade plan` — Checks available upgrade paths.
- `kubeadm upgrade apply` — Applies a control-plane upgrade.
- `kubeadm reset` — Removes kubeadm-managed local configuration.

## 3. Requirements

- Linux servers or virtual machines
- A compatible container runtime
- `kubelet` and `kubeadm`
- `kubectl`
- A compatible CNI networking plugin

## 4. Kubeadm vs EKS

- `kubeadm`: Bootstraps a self-managed Kubernetes cluster.
- `EKS`: AWS-managed Kubernetes service; AWS manages the control plane.

## 5. Interview Answer

Kubeadm is a tool used to bootstrap Kubernetes clusters. It simplifies control-plane initialization and node joining, but infrastructure provisioning and ongoing cluster maintenance remain the operator's responsibility.
