---
title: 分配 Pod 安全策略
weight: 2260
---

_Pod 安全策略_（PSP）是控制 Pod 安全的规范（如是否可以使用 root 权限等）的对象。

## 添加默认 Pod 安全策略

使用 RKE 创建新集群时，你可以将其配置为立即应用 PSP。创建集群时，使用**集群选项**来启用 PSP。分配给集群的 PSP 将是集群内项目的默认 PSP。

:::note 先决条件：

在 Rancher 中创建 Pod 安全策略。在将默认 PSP 分配给新集群之前，你必须有一个可分配的 PSP。有关说明，请参阅[创建 Pod 安全策略](../authentication-permissions-and-global-configuration/create-pod-security-policies.md)。

:::

:::note

出于安全考虑，我们建议你在创建集群时分配 PSP。

:::

要启用默认 Pod 安全策略，请将 **Pod 安全策略支持**选项设置为**启用**，然后从**默认 Pod 安全策略**下拉框中进行选择。

集群完成配置后，你选择的 PSP 将应用于集群内的所有项目。
