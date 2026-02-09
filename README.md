# 🚀 Kubernetes GitOps Applications

Este repositório contém **manifests Kubernetes de aplicações**, gerenciadas via **GitOps com Argo CD**, e faz parte de um projeto maior de **plataforma Kubernetes on-premise**.

Ele é observado continuamente pelo Argo CD, que garante que o estado do cluster esteja sempre sincronizado com o estado definido neste repositório.

---

## 🧠 Visão Geral

Neste modelo:

- O Argo CD sincroniza automaticamente os manifests no cluster
- Mudanças no Git refletem diretamente no ambiente

---

## 🔁 Fluxo GitOps

```text
Git Commit
   ↓
Repositório (k8s-gitops-apps)
   ↓
Argo CD
   ↓
Cluster Kubernetes
