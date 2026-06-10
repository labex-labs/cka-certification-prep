# CKA 培训 Certification Prep Path

## 支持语言

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/zh/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/开始路径-whitesmoke?style=for-the-badge)](https://labex.io/zh/learn/cka)

通过结构化的动手学习路径备考 Certified Kubernetes Administrator（CKA）考试。本路线图侧重 Kubernetes 上的集群管理、安装与配置、工作负载与调度、服务与网络、存储以及故障排查，以及贴近 CKA 风格的性能型考试任务与真实场景。后续将逐步加入 CKA 课程、实验环境与模拟考试练习，帮助你建立与 CKA 目标一致的能力。

**课程**: 3 · **实验**: 88

## 课程

### 1. [CKA 备考指南](https://labex.io/zh/courses/cka-prep)

这是一门面向初学者的 CKA 备考课程，包含 48 个引导式 Kubernetes 管理实验，内容涵盖从集群入门到工作负载、架构、网络、存储、故障排查及维护的全方位实践。

[开始课程](https://labex.io/zh/courses/cka-prep) · 实验: 48

#### 集群导览与管理基础

|   序号 | 名称                             | 难度   | 练习                                                                                                     |
|------|--------------------------------|------|--------------------------------------------------------------------------------------------------------|
|    1 | 🧩  检查 kubeconfig 和上下文          | 初级   | [开始实验](https://labex.io/zh/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|    2 | 🧩  探索节点与集群版本                   | 初级   | [开始实验](https://labex.io/zh/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|    3 | 🧩  检查 API 资源与命名空间              | 初级   | [开始实验](https://labex.io/zh/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|    4 | 🧩  读取事件与对象状态                   | 初级   | [开始实验](https://labex.io/zh/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|    5 | 🧩  使用标签、选择器和字段选择器              | 初级   | [开始实验](https://labex.io/zh/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|    6 | 🧩  管理行政工作流的命名空间                | 初级   | [开始实验](https://labex.io/zh/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|    7 | 🧩  使用 Dry Run 和 Explain 处理清单文件 | 初级   | [开始实验](https://labex.io/zh/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### 工作负载与调度

|   序号 | 名称                               | 难度   | 练习                                                                                                      |
|------|----------------------------------|------|---------------------------------------------------------------------------------------------------------|
|    1 | 🧩  检查 Deployment 和 ReplicaSet 行为 | 初级   | [开始实验](https://labex.io/zh/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|    2 | 🧩  执行受控的 Deployment 滚动更新         | 初级   | [开始实验](https://labex.io/zh/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|    3 | 🧩  回滚损坏的部署                       | 初级   | [开始实验](https://labex.io/zh/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|    4 | 🧩  使用 ConfigMap 和 Secret 配置工作负载  | 初级   | [开始实验](https://labex.io/zh/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|    5 | 🧩  设置请求、限制与资源证据                  | 初级   | [开始实验](https://labex.io/zh/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|    6 | 🧩  使用节点选择器（Node Selectors）调度 Pod | 初级   | [开始实验](https://labex.io/zh/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|    7 | 🧩  使用亲和性规则放置工作负载                 | 初级   | [开始实验](https://labex.io/zh/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|    8 | 🧩  使用污点（Taints）与容忍度（Tolerations） | 初级   | [开始实验](https://labex.io/zh/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|    9 | 🧩  使用 PodDisruptionBudgets 保护可用性 | 初级   | [开始实验](https://labex.io/zh/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### 集群架构、安装与配置

|   序号 | 名称                      | 难度   | 练习                                                                                                 |
|------|-------------------------|------|----------------------------------------------------------------------------------------------------|
|    1 | 🧩  检查控制平面组件             | 初级   | [开始实验](https://labex.io/zh/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|    2 | 🧩  探索 kubeadm 配置工件      | 初级   | [开始实验](https://labex.io/zh/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|    3 | 🧩  检查证书与集群信任            | 初级   | [开始实验](https://labex.io/zh/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|    4 | 🧩  授予命名空间操作员 RBAC 权限    | 初级   | [开始实验](https://labex.io/zh/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|    5 | 🧩  委派只读集群诊断权限           | 初级   | [开始实验](https://labex.io/zh/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|    6 | 🧩  使用 Helm 部署插件         | 初级   | [开始实验](https://labex.io/zh/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|    7 | 🧩  使用 Kustomize 自定义集群资源 | 初级   | [开始实验](https://labex.io/zh/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|    8 | 🧩  定义并使用自定义资源           | 初级   | [开始实验](https://labex.io/zh/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|    9 | 🧩  检查 CNI、CSI 和 CRI 接口  | 初级   | [开始实验](https://labex.io/zh/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### 服务与网络

|   序号 | 名称                         | 难度   | 练习                                                                                               |
|------|----------------------------|------|--------------------------------------------------------------------------------------------------|
|    1 | 🧩  使用 Service 暴露应用         | 初级   | [开始实验](https://labex.io/zh/labs/expose-applications-with-services-663774?course=cka-prep)        |
|    2 | 🧩  修复 EndpointSlice 服务访问   | 初级   | [开始实验](https://labex.io/zh/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|    3 | 🧩  排查服务 DNS 解析问题           | 初级   | [开始实验](https://labex.io/zh/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|    4 | 🧩  配置 CoreDNS 条件转发         | 初级   | [开始实验](https://labex.io/zh/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|    5 | 🧩  使用 NetworkPolicy 限制出口流量 | 初级   | [开始实验](https://labex.io/zh/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|    6 | 🧩  修复 NetworkPolicy 访问权限   | 初级   | [开始实验](https://labex.io/zh/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|    7 | 🧩  使用 Ingress 路由 HTTP 流量   | 初级   | [开始实验](https://labex.io/zh/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|    8 | 🧩  使用网关路由发布 API            | 初级   | [开始实验](https://labex.io/zh/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### 存储

|   序号 | 名称                         | 难度   | 练习                                                                                                      |
|------|----------------------------|------|---------------------------------------------------------------------------------------------------------|
|    1 | 🧩  检查 StorageClass 与动态存储供应 | 初级   | [开始实验](https://labex.io/zh/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|    2 | 🧩  为应用程序数据创建 PVC           | 初级   | [开始实验](https://labex.io/zh/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|    3 | 🧩  绑定静态 PersistentVolume   | 初级   | [开始实验](https://labex.io/zh/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|    4 | 🧩  配置访问模式与卷模式              | 初级   | [开始实验](https://labex.io/zh/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|    5 | 🧩  使用回收策略保留数据              | 初级   | [开始实验](https://labex.io/zh/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|    6 | 🧩  排查 PVC 绑定与挂载故障          | 初级   | [开始实验](https://labex.io/zh/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### 故障排查与维护

|   序号 | 名称                         | 难度   | 练习                                                                                             |
|------|----------------------------|------|------------------------------------------------------------------------------------------------|
|    1 | 🧩  诊断集群资源压力                | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|    2 | 🧩  使用 Metrics 和 Top 监控 Pod | 初级   | [开始实验](https://labex.io/zh/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|    3 | 🧩  管理容器输出流                 | 初级   | [开始实验](https://labex.io/zh/labs/manage-container-output-streams-663783?course=cka-prep)        |
|    4 | 🧩  调试镜像拉取失败                | 初级   | [开始实验](https://labex.io/zh/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|    5 | 🧩  诊断 Init Container 故障    | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|    6 | 🧩  修复崩溃的静态 Pod 清单          | 初级   | [开始实验](https://labex.io/zh/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|    7 | 🧩  安全地驱逐与恢复节点              | 初级   | [开始实验](https://labex.io/zh/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|    8 | 🧩  恢复基于指标的扩缩容信号            | 初级   | [开始实验](https://labex.io/zh/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|    9 | 🧩  恢复中断的服务流量               | 初级   | [开始实验](https://labex.io/zh/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [CKA 模拟考试 01](https://labex.io/zh/courses/cka-practice-exam-01)

这是一场实战型 CKA 模拟考试，包含 20 个独立的 Kubernetes 管理挑战，涵盖存储、故障排查、工作负载与调度、集群架构以及服务与网络等核心领域。

[开始课程](https://labex.io/zh/courses/cka-practice-exam-01) · 实验: 20

#### 存储

|   序号 | 名称                                 | 难度   | 练习                                                                                                                      |
|------|------------------------------------|------|-------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 PersistentVolumeClaim 挂载应用数据 | 初级   | [开始挑战](https://labex.io/zh/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|    2 | 🎯  为归档数据绑定静态 PersistentVolume      | 初级   | [开始挑战](https://labex.io/zh/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### 故障排查

|   序号 | 名称                              | 难度   | 练习                                                                                                                 |
|------|---------------------------------|------|--------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  恢复故障服务的流量                    | 初级   | [开始挑战](https://labex.io/zh/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|    2 | 🎯  恢复失败的 Deployment 滚动更新        | 初级   | [开始挑战](https://labex.io/zh/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|    3 | 🎯  在带有污点的节点上调度 Pending 状态的 Pod  | 初级   | [开始挑战](https://labex.io/zh/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|    4 | 🎯  修复命名空间之间的 NetworkPolicy 访问权限 | 初级   | [开始挑战](https://labex.io/zh/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|    5 | 🎯  恢复 CoreDNS 域名解析              | 初级   | [开始挑战](https://labex.io/zh/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|    6 | 🎯  诊断集群资源压力                     | 初级   | [开始挑战](https://labex.io/zh/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### 工作负载与调度

|   序号 | 名称                                | 难度   | 练习                                                                                                                             |
|------|-----------------------------------|------|--------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  执行受控的 Deployment 滚动更新          | 初级   | [开始挑战](https://labex.io/zh/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|    2 | 🎯  使用 ConfigMap 和 Secret 配置应用程序设置 | 初级   | [开始挑战](https://labex.io/zh/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|    3 | 🎯  使用亲和性与资源控制进行工作负载调度             | 初级   | [开始挑战](https://labex.io/zh/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### 集群架构、安装与配置

|   序号 | 名称                            | 难度   | 练习                                                                                                                  |
|------|-------------------------------|------|---------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 RBAC 授予命名空间操作员权限        | 初级   | [开始挑战](https://labex.io/zh/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|    2 | 🎯  创建 etcd 快照备份               | 初级   | [开始挑战](https://labex.io/zh/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|    3 | 🎯  安全地排空并恢复节点                 | 初级   | [开始挑战](https://labex.io/zh/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|    4 | 🎯  使用 Helm 和 Kustomize 部署集群插件 | 初级   | [开始挑战](https://labex.io/zh/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|    5 | 🎯  定义并使用自定义资源                 | 初级   | [开始挑战](https://labex.io/zh/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### 服务与网络

|   序号 | 名称                             | 难度   | 练习                                                                                                                 |
|------|--------------------------------|------|--------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 Service 暴露应用程序           | 初级   | [开始挑战](https://labex.io/zh/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|    2 | 🎯  使用 Ingress 路由 HTTP 流量       | 初级   | [开始挑战](https://labex.io/zh/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|    3 | 🎯  使用 NetworkPolicy 强制执行命名空间隔离 | 初级   | [开始挑战](https://labex.io/zh/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|    4 | 🎯  配置内部 DNS 别名                 | 初级   | [开始挑战](https://labex.io/zh/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [CKA 模拟考试 02](https://labex.io/zh/courses/cka-practice-exam-02)

第二套独立的 CKA 风格模拟考试，包含 20 个 Kubernetes 管理挑战，涵盖了 CKA 考试大纲中涉及的各个核心领域及不同的运维场景。

[开始课程](https://labex.io/zh/courses/cka-practice-exam-02) · 实验: 20

#### 存储

|   序号 | 名称                            | 难度   | 练习                                                                                                                 |
|------|-------------------------------|------|--------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 StorageClass 提供应用程序日志存储 | 初级   | [开始挑战](https://labex.io/zh/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|    2 | 🎯  保留已释放卷中的数据                 | 初级   | [开始挑战](https://labex.io/zh/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### 故障排查

|   序号 | 名称                               | 难度   | 练习                                                                                                                  |
|------|----------------------------------|------|---------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复崩溃的静态 Pod 清单                | 初级   | [开始挑战](https://labex.io/zh/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|    2 | 🎯  修复损坏的 kubelet 镜像拉取路径          | 初级   | [开始挑战](https://labex.io/zh/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|    3 | 🎯  恢复基于指标的扩缩容信号                  | 初级   | [开始挑战](https://labex.io/zh/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|    4 | 🎯  诊断 Init 容器启动失败                | 初级   | [开始挑战](https://labex.io/zh/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|    5 | 🎯  维护偏差后的节点调度恢复                  | 初级   | [开始挑战](https://labex.io/zh/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|    6 | 🎯  修复无头服务（Headless Service）的服务发现 | 初级   | [开始挑战](https://labex.io/zh/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### 工作负载与调度

|   序号 | 名称                              | 难度   | 练习                                                                                                                     |
|------|---------------------------------|------|------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  配置水平 Pod 自动扩缩容               | 初级   | [开始挑战](https://labex.io/zh/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|    2 | 🎯  使用 PodDisruptionBudget 保护可用性 | 初级   | [开始挑战](https://labex.io/zh/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|    3 | 🎯  使用准入控制和运行时设置约束 Pod           | 初级   | [开始挑战](https://labex.io/zh/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### 集群架构、安装与配置

|   序号 | 名称                                 | 难度   | 练习                                                                                                                  |
|------|------------------------------------|------|---------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  委派只读集群诊断权限                      | 初级   | [开始挑战](https://labex.io/zh/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|    2 | 🎯  检查并更新 kubeadm 证书                | 初级   | [开始挑战](https://labex.io/zh/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|    3 | 🎯  为计划内升级准备节点                      | 初级   | [开始挑战](https://labex.io/zh/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|    4 | 🎯  使用 Kustomize 安装分阶段的 CSI Mock 驱动 | 初级   | [开始挑战](https://labex.io/zh/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|    5 | 🎯  验证 Operator 管理的自定义资源            | 初级   | [开始挑战](https://labex.io/zh/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### 服务与网络

|   序号 | 名称                          | 难度   | 练习                                                                                                            |
|------|-----------------------------|------|---------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 Gateway API 路由发布 API  | 初级   | [开始挑战](https://labex.io/zh/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|    2 | 🎯  修复基于 EndpointSlice 的服务访问 | 初级   | [开始挑战](https://labex.io/zh/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|    3 | 🎯  使用 NetworkPolicy 限制出口流量  | 初级   | [开始挑战](https://labex.io/zh/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|    4 | 🎯  配置 CoreDNS 条件转发          | 初级   | [开始挑战](https://labex.io/zh/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

