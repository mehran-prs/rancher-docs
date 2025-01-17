---
title: 离线 Helm CLI 安装
weight: 1
---

本文介绍如何使用 Helm CLI 在离线环境中安装 Rancher Server。离线环境可以是 Rancher Server 离线安装、防火墙后面或代理后面。

Rancher 安装在 RKE Kubernetes 集群、K3s Kubernetes 集群，或单个 Docker 容器上对应的安装步骤会有所不同。

如需了解各个安装方式的更多信息，请参见[本页](installation-and-upgrade.md)。

在安装指导中，我们为不同的安装选项提供对应的 _选项卡_ 。

:::note 重要提示：

如果你按照 Docker 安装指南安装 Rancher，你将没有把 Docker 安装转换为 Kubernetes 安装的升级途径。

:::

# 安装概要

1. [设置基础设施和私有镜像仓库](../getting-started/installation-and-upgrade/other-installation-methods/air-gapped-helm-cli-install/infrastructure-private-registry.md)
2. [收集镜像到私有镜像仓库](../getting-started/installation-and-upgrade/other-installation-methods/air-gapped-helm-cli-install/publish-images.md)
3. [设置 Kubernetes 集群（如果你使用 Docker 安装，请跳过此步骤）](../getting-started/installation-and-upgrade/other-installation-methods/air-gapped-helm-cli-install/install-kubernetes.md)
4. [安装 Rancher](../getting-started/installation-and-upgrade/other-installation-methods/air-gapped-helm-cli-install/install-rancher-ha.md)

# 升级

如需在离线环境中使用 Helm CLI 升级 Rancher，请按照[升级步骤](../getting-started/installation-and-upgrade/install-upgrade-on-a-kubernetes-cluster/upgrades.md)进行操作。

### 后续操作
[准备节点](../getting-started/installation-and-upgrade/other-installation-methods/air-gapped-helm-cli-install/infrastructure-private-registry.md)
