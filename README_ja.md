# CKA トレーニング Certification Prep Path

## 言語

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ja/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/パスを開始-whitesmoke?style=for-the-badge)](https://labex.io/ja/learn/cka)

Certified Kubernetes Administrator（CKA）試験に向けた、体系的かつ実践的な学習パスです。Kubernetes におけるクラスター管理、インストールと構成、ワークロードとスケジューリング、サービスとネットワーク、ストレージ、トラブルシューティング、および CKA 形式のパフォーマンスベースのタスクと現実的なシナリオに焦点を当てます。CKA コース、ラボ、模擬試験の演習は順次追加され、CKA の目標に沿ったスキルを育成します。

**コース**: 3 · **ラボ**: 88

## コース

### 1. [CKA 対策コース](https://labex.io/ja/courses/cka-prep)

初心者向けの CKA 対策コースです。クラスターの基本からワークロード、アーキテクチャ、ネットワーク、ストレージ、トラブルシューティング、メンテナンスまで、48 のガイド付き Kubernetes 管理実験を通じて体系的に学習できます。

[コースを開始](https://labex.io/ja/courses/cka-prep) · ラボ: 48

#### クラスターの概要と管理の基礎

|   インデックス | 名前                                 | 難易度   | 練習                                                                                                      |
|----------|------------------------------------|-------|---------------------------------------------------------------------------------------------------------|
|        1 | 🧩  kubeconfig とコンテキストの調査           | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|        2 | 🧩  ノードとクラスターバージョンの調査               | 初級    | [ラボを開始](https://labex.io/ja/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|        3 | 🧩  API リソースとネームスペースの調査             | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|        4 | 🧩  イベントとオブジェクトのコンディションの確認          | 初級    | [ラボを開始](https://labex.io/ja/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|        5 | 🧩  ラベル、セレクター、フィールドセレクターの使用         | 初級    | [ラボを開始](https://labex.io/ja/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|        6 | 🧩  管理用ワークフローのための名前空間（Namespace）の管理 | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|        7 | 🧩  マニフェストのドライランと Explain の活用       | 初級    | [ラボを開始](https://labex.io/ja/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### ワークロードとスケジューリング

|   インデックス | 名前                                     | 難易度   | 練習                                                                                                       |
|----------|----------------------------------------|-------|----------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Deployment と ReplicaSet の動作を調査する    | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|        2 | 🧩  制御されたデプロイメントのロールアウトを実行する            | 初級    | [ラボを開始](https://labex.io/ja/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|        3 | 🧩  壊れたロールアウトのロールバック                    | 初級    | [ラボを開始](https://labex.io/ja/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|        4 | 🧩  ConfigMaps と Secrets を使用したワークロードの設定 | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|        5 | 🧩  リクエスト、リミット、およびリソースエビデンスの設定          | 初級    | [ラボを開始](https://labex.io/ja/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|        6 | 🧩  Node Selector を使用した Pod のスケジューリング   | 初級    | [ラボを開始](https://labex.io/ja/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|        7 | 🧩  アフィニティルールによるワークロードの配置               | 初級    | [ラボを開始](https://labex.io/ja/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|        8 | 🧩  Taints（テイント）と Tolerations（容認）の使用    | 初級    | [ラボを開始](https://labex.io/ja/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|        9 | 🧩  PodDisruptionBudget を使用した可用性の保護     | 初級    | [ラボを開始](https://labex.io/ja/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### クラスターのアーキテクチャ、インストール、および構成

|   インデックス | 名前                                 | 難易度   | 練習                                                                                                  |
|----------|------------------------------------|-------|-----------------------------------------------------------------------------------------------------|
|        1 | 🧩  コントロールプレーンコンポーネントの調査            | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|        2 | 🧩  kubeadm 設定アーティファクトの探索           | 初級    | [ラボを開始](https://labex.io/ja/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|        3 | 🧩  証明書とクラスターの信頼関係の調査               | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|        4 | 🧩  Namespace Operator の RBAC 権限付与  | 初級    | [ラボを開始](https://labex.io/ja/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|        5 | 🧩  読み取り専用クラスター診断の委任                | 初級    | [ラボを開始](https://labex.io/ja/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|        6 | 🧩  Helm を使用したアドオンのデプロイ             | 初級    | [ラボを開始](https://labex.io/ja/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|        7 | 🧩  Kustomize を使用したクラスターリソースのカスタマイズ | 初級    | [ラボを開始](https://labex.io/ja/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|        8 | 🧩  カスタムリソースの定義と利用                  | 初級    | [ラボを開始](https://labex.io/ja/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|        9 | 🧩  CNI、CSI、CRI インターフェースの調査         | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### サービスとネットワーキング

|   インデックス | 名前                                    | 難易度   | 練習                                                                                                |
|----------|---------------------------------------|-------|---------------------------------------------------------------------------------------------------|
|        1 | 🧩  Service を使用したアプリケーションの公開           | 初級    | [ラボを開始](https://labex.io/ja/labs/expose-applications-with-services-663774?course=cka-prep)        |
|        2 | 🧩  EndpointSlice サービスアクセスの修復          | 初級    | [ラボを開始](https://labex.io/ja/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|        3 | 🧩  Service DNS 解決のトラブルシューティング         | 初級    | [ラボを開始](https://labex.io/ja/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|        4 | 🧩  CoreDNS 条件付きフォワーディングの設定            | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|        5 | 🧩  NetworkPolicy を使用したエグレス（Egress）の制限 | 初級    | [ラボを開始](https://labex.io/ja/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|        6 | 🧩  NetworkPolicy アクセスの修復              | 初級    | [ラボを開始](https://labex.io/ja/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|        7 | 🧩  Ingress を使用した HTTP トラフィックのルーティング   | 初級    | [ラボを開始](https://labex.io/ja/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|        8 | 🧩  Gateway ルーティングによる API の公開          | 初級    | [ラボを開始](https://labex.io/ja/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### ストレージ

|   インデックス | 名前                               | 難易度   | 練習                                                                                                       |
|----------|----------------------------------|-------|----------------------------------------------------------------------------------------------------------|
|        1 | 🧩  StorageClass と動的プロビジョニングの調査   | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|        2 | 🧩  アプリケーションデータ用の PVC を作成する       | 初級    | [ラボを開始](https://labex.io/ja/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|        3 | 🧩  静的 PersistentVolume のバインド     | 初級    | [ラボを開始](https://labex.io/ja/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|        4 | 🧩  アクセスモードとボリュームモードの設定           | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|        5 | 🧩  リクレイムポリシーによるデータの保持            | 初級    | [ラボを開始](https://labex.io/ja/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|        6 | 🧩  PVC のバインディングとマウントのトラブルシューティング | 初級    | [ラボを開始](https://labex.io/ja/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### トラブルシューティングとメンテナンス

|   インデックス | 名前                             | 難易度   | 練習                                                                                              |
|----------|--------------------------------|-------|-------------------------------------------------------------------------------------------------|
|        1 | 🧩  クラスターリソースの負荷診断              | 初級    | [ラボを開始](https://labex.io/ja/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|        2 | 🧩  Metrics と Top を使用した Pod の監視 | 初級    | [ラボを開始](https://labex.io/ja/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|        3 | 🧩  コンテナの出力ストリームの管理             | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-container-output-streams-663783?course=cka-prep)        |
|        4 | 🧩  イメージプル失敗のデバッグ               | 初級    | [ラボを開始](https://labex.io/ja/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|        5 | 🧩  失敗した Init コンテナの診断           | 初級    | [ラボを開始](https://labex.io/ja/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|        6 | 🧩  クラッシュする静的 Pod マニフェストの復旧     | 初級    | [ラボを開始](https://labex.io/ja/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|        7 | 🧩  ノードの安全なドレインと復旧              | 初級    | [ラボを開始](https://labex.io/ja/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|        8 | 🧩  メトリクスベースのスケーリングシグナルの復旧      | 初級    | [ラボを開始](https://labex.io/ja/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|        9 | 🧩  壊れたサービス通信の復旧                | 初級    | [ラボを開始](https://labex.io/ja/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [CKA 模擬試験 01](https://labex.io/ja/courses/cka-practice-exam-01)

ストレージ、トラブルシューティング、ワークロードとスケジューリング、クラスターアーキテクチャ、サービスとネットワーキングを網羅した、20 の独立した Kubernetes 管理課題からなる実践的な CKA 模擬試験です。

[コースを開始](https://labex.io/ja/courses/cka-practice-exam-01) · ラボ: 20

#### ストレージ

|   インデックス | 名前                                             | 難易度   | 練習                                                                                                                          |
|----------|------------------------------------------------|-------|-----------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  PersistentVolumeClaim を使用したアプリケーションデータのマウント | 初級    | [チャレンジを開始](https://labex.io/ja/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|        2 | 🎯  アーカイブデータ用の静的 PersistentVolume のバインド         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### トラブルシューティング

|   インデックス | 名前                                                | 難易度   | 練習                                                                                                                     |
|----------|---------------------------------------------------|-------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  停止したサービスへのトラフィック復旧                             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|        2 | 🎯  失敗したデプロイメントのロールアウトを復旧する                        | 初級    | [チャレンジを開始](https://labex.io/ja/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|        3 | 🎯  テイント（Taint）が設定されたノードへの Pending 状態の Pod のスケジュール | 初級    | [チャレンジを開始](https://labex.io/ja/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|        4 | 🎯  名前空間間の NetworkPolicy アクセスを修復する                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|        5 | 🎯  CoreDNS 名前解決の復旧                                | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|        6 | 🎯  クラスターリソース負荷の診断                                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### ワークロードとスケジューリング

|   インデックス | 名前                                       | 難易度   | 練習                                                                                                                                 |
|----------|------------------------------------------|-------|------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  制御されたデプロイメントのロールアウトを実行する              | 初級    | [チャレンジを開始](https://labex.io/ja/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|        2 | 🎯  ConfigMap と Secret を使用したアプリケーション設定の構成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|        3 | 🎯  アフィニティとリソース制御によるワークロードの配置             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### クラスターのアーキテクチャ、インストール、設定

|   インデックス | 名前                                      | 難易度   | 練習                                                                                                                      |
|----------|-----------------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  RBAC を使用したネームスペースオペレーター権限の付与         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|        2 | 🎯  etcd スナップショットバックアップの作成               | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|        3 | 🎯  ノードの安全なドレインと復旧                       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|        4 | 🎯  Helm と Kustomize を使用したクラスターアドオンのデプロイ | 初級    | [チャレンジを開始](https://labex.io/ja/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|        5 | 🎯  カスタムリソースの定義と利用                       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### サービスとネットワーキング

|   インデックス | 名前                                  | 難易度   | 練習                                                                                                                     |
|----------|-------------------------------------|-------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  サービスによるアプリケーションの公開               | 初級    | [チャレンジを開始](https://labex.io/ja/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|        2 | 🎯  Ingress を使用した HTTP トラフィックのルーティング | 初級    | [チャレンジを開始](https://labex.io/ja/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|        3 | 🎯  NetworkPolicy を使用した名前空間の分離       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|        4 | 🎯  内部 DNS エイリアスの設定                  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [CKA 模擬試験 02](https://labex.io/ja/courses/cka-practice-exam-02)

CKA 試験対策用の第 2 回模擬試験です。Kubernetes 管理に関する 20 の課題を通じて、実際の試験範囲を網羅した多様な運用シナリオを体験できます。

[コースを開始](https://labex.io/ja/courses/cka-practice-exam-02) · ラボ: 20

#### ストレージ

|   インデックス | 名前                                       | 難易度   | 練習                                                                                                                     |
|----------|------------------------------------------|-------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  StorageClass を使用したアプリケーションログのプロビジョニング | 初級    | [チャレンジを開始](https://labex.io/ja/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|        2 | 🎯  保持されたボリュームから解放されたデータを保護する             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### トラブルシューティング

|   インデックス | 名前                           | 難易度   | 練習                                                                                                                      |
|----------|------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  クラッシュする静的 Pod マニフェストの復元   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|        2 | 🎯  壊れた kubelet イメージプルパスの修復   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|        3 | 🎯  メトリクスベースのスケーリングシグナルの復旧    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|        4 | 🎯  Init コンテナの起動失敗の診断         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|        5 | 🎯  メンテナンス後のノードスケジューリングの復旧    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|        6 | 🎯  ヘッドレスワークロードのサービスディスカバリの修復 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### ワークロードとスケジューリング

|   インデックス | 名前                                     | 難易度   | 練習                                                                                                                         |
|----------|----------------------------------------|-------|----------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Horizontal Pod Autoscaling の設定      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|        2 | 🎯  PodDisruptionBudget で可用性を保護する       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|        3 | 🎯  Admission および Runtime 設定による Pod の制限 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### クラスターのアーキテクチャ、インストール、設定

|   インデックス | 名前                                               | 難易度   | 練習                                                                                                                      |
|----------|--------------------------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  読み取り専用クラスター診断の委任                              | 初級    | [チャレンジを開始](https://labex.io/ja/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|        2 | 🎯  kubeadm 証明書の確認と更新                             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|        3 | 🎯  計画的なアップグレードに向けたノードの準備                         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|        4 | 🎯  Kustomize を使用したステージング済み CSI Mock ドライバーのインストール | 初級    | [チャレンジを開始](https://labex.io/ja/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|        5 | 🎯  オペレーター管理下のカスタムリソースの検証                         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### サービスとネットワーキング

|   インデックス | 名前                                   | 難易度   | 練習                                                                                                                |
|----------|--------------------------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Gateway API ルーティングによる API の公開     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|        2 | 🎯  EndpointSlice ベースのサービスアクセスの修復     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|        3 | 🎯  NetworkPolicy を使用したエグレス（Egress）制限 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|        4 | 🎯  CoreDNS 条件付きフォワーディングの設定           | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

