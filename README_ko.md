# CKA 교육 Certification Prep Path

## 언어

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ko/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/경로-시작-whitesmoke?style=for-the-badge)](https://labex.io/ko/learn/cka)

Certified Kubernetes Administrator(CKA) 시험을 위해 구조화된 실습 중심 학습 경로로 준비하세요. Kubernetes 에서 클러스터 관리, 설치 및 구성, 워크로드 및 스케줄링, 서비스 및 네트워킹, 스토리지, 문제 해결, CKA 형태의 성능 기반 작업, 현실 시나리오에 초점을 맞춥니다. CKA 과정, 랩, 모의고사 연습이 단계적으로 추가됩니다.

**코스**: 3 · **실습**: 88

## 코스

### 1. [CKA 준비 과정](https://labex.io/ko/courses/cka-prep)

[![CKA 준비 과정](https://course-cover.labex.io/cka-prep.png?lang=ko)](https://labex.io/ko/courses/cka-prep)

클러스터 오리엔테이션부터 워크로드, 아키텍처, 네트워킹, 스토리지, 트러블슈팅, 유지보수까지 총 48 개의 가이드형 Kubernetes 관리 실험으로 구성된 초보자 맞춤형 CKA 준비 과정입니다.

[코스 시작](https://labex.io/ko/courses/cka-prep) · 실습: 48

#### 클러스터 오리엔테이션 및 관리 기초

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                      |
|-------|------------------------------------|-------|---------------------------------------------------------------------------------------------------------|
|     1 | 🧩  kubeconfig 및 컨텍스트 검사            | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|     2 | 🧩  노드 및 클러스터 버전 탐색                 | 초급    | [실습 시작](https://labex.io/ko/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|     3 | 🧩  API 리소스 및 네임스페이스 검사             | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|     4 | 🧩  이벤트 및 객체 상태 읽기                  | 초급    | [실습 시작](https://labex.io/ko/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|     5 | 🧩  레이블, 셀렉터 및 필드 셀렉터 사용하기          | 초급    | [실습 시작](https://labex.io/ko/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|     6 | 🧩  관리 워크플로우를 위한 네임스페이스 관리          | 초급    | [실습 시작](https://labex.io/ko/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|     7 | 🧩  매니페스트를 위한 Dry Run 및 Explain 사용법 | 초급    | [실습 시작](https://labex.io/ko/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### 워크로드 및 스케줄링

|   인덱스 | 이름                                         | 난이도   | 연습                                                                                                       |
|-------|--------------------------------------------|-------|----------------------------------------------------------------------------------------------------------|
|     1 | 🧩  Deployment 및 ReplicaSet 동작 검사           | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|     2 | 🧩  제어된 배포 롤아웃 수행                           | 초급    | [실습 시작](https://labex.io/ko/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|     3 | 🧩  손상된 롤아웃 롤백하기                            | 초급    | [실습 시작](https://labex.io/ko/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|     4 | 🧩  ConfigMap 과 Secret 을 사용한 워크로드 구성        | 초급    | [실습 시작](https://labex.io/ko/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|     5 | 🧩  요청 (Requests), 제한 (Limits) 및 리소스 증명 설정  | 초급    | [실습 시작](https://labex.io/ko/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|     6 | 🧩  Node Selector 를 이용한 Pod 스케줄링            | 초급    | [실습 시작](https://labex.io/ko/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|     7 | 🧩  어피니티 규칙을 사용한 워크로드 배치                    | 초급    | [실습 시작](https://labex.io/ko/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|     8 | 🧩  테인트 (Taints) 와 톨러레이션 (Tolerations) 사용하기 | 초급    | [실습 시작](https://labex.io/ko/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|     9 | 🧩  PodDisruptionBudget 을 통한 가용성 보호         | 초급    | [실습 시작](https://labex.io/ko/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### 클러스터 아키텍처, 설치 및 구성

|   인덱스 | 이름                                      | 난이도   | 연습                                                                                                  |
|-------|-----------------------------------------|-------|-----------------------------------------------------------------------------------------------------|
|     1 | 🧩  컨트롤 플레인 구성 요소 검사                     | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|     2 | 🧩  kubeadm 구성 아티팩트 살펴보기                 | 초급    | [실습 시작](https://labex.io/ko/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|     3 | 🧩  인증서 및 클러스터 신뢰 관계 검사                  | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|     4 | 🧩  네임스페이스 운영자 RBAC 권한 부여                | 초급    | [실습 시작](https://labex.io/ko/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|     5 | 🧩  읽기 전용 클러스터 진단 권한 위임                  | 초급    | [실습 시작](https://labex.io/ko/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|     6 | 🧩  Helm 을 이용한 애드온 배포                    | 초급    | [실습 시작](https://labex.io/ko/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|     7 | 🧩  Kustomize 를 사용한 클러스터 리소스 커스터마이징      | 초급    | [실습 시작](https://labex.io/ko/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|     8 | 🧩  사용자 정의 리소스 (Custom Resource) 정의 및 사용 | 초급    | [실습 시작](https://labex.io/ko/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|     9 | 🧩  CNI, CSI 및 CRI 인터페이스 검사              | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### 서비스 및 네트워킹

|   인덱스 | 이름                               | 난이도   | 연습                                                                                                |
|-------|----------------------------------|-------|---------------------------------------------------------------------------------------------------|
|     1 | 🧩  서비스를 통한 애플리케이션 노출             | 초급    | [실습 시작](https://labex.io/ko/labs/expose-applications-with-services-663774?course=cka-prep)        |
|     2 | 🧩  EndpointSlice 서비스 액세스 복구      | 초급    | [실습 시작](https://labex.io/ko/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|     3 | 🧩  서비스 DNS 확인 문제 해결              | 초급    | [실습 시작](https://labex.io/ko/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|     4 | 🧩  CoreDNS 조건부 포워딩 구성            | 초급    | [실습 시작](https://labex.io/ko/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|     5 | 🧩  NetworkPolicy 를 이용한 Egress 제한 | 초급    | [실습 시작](https://labex.io/ko/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|     6 | 🧩  NetworkPolicy 접근 권한 복구        | 초급    | [실습 시작](https://labex.io/ko/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|     7 | 🧩  Ingress 를 이용한 HTTP 트래픽 라우팅    | 초급    | [실습 시작](https://labex.io/ko/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|     8 | 🧩  Gateway 라우팅을 통한 API 게시        | 초급    | [실습 시작](https://labex.io/ko/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### 스토리지

|   인덱스 | 이름                             | 난이도   | 연습                                                                                                       |
|-------|--------------------------------|-------|----------------------------------------------------------------------------------------------------------|
|     1 | 🧩  StorageClass 및 동적 프로비저닝 검사  | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|     2 | 🧩  애플리케이션 데이터를 위한 PVC 생성       | 초급    | [실습 시작](https://labex.io/ko/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|     3 | 🧩  정적 PersistentVolume 바인딩     | 초급    | [실습 시작](https://labex.io/ko/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|     4 | 🧩  액세스 모드 및 볼륨 모드 구성           | 초급    | [실습 시작](https://labex.io/ko/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|     5 | 🧩  Reclaim Policy 를 사용한 데이터 보존 | 초급    | [실습 시작](https://labex.io/ko/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|     6 | 🧩  PVC 바인딩 및 마운트 문제 해결         | 초급    | [실습 시작](https://labex.io/ko/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### 문제 해결 및 유지보수

|   인덱스 | 이름                                  | 난이도   | 연습                                                                                              |
|-------|-------------------------------------|-------|-------------------------------------------------------------------------------------------------|
|     1 | 🧩  클러스터 리소스 압박 진단                   | 초급    | [실습 시작](https://labex.io/ko/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|     2 | 🧩  Metrics 및 Top 을 이용한 Pod 모니터링     | 초급    | [실습 시작](https://labex.io/ko/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|     3 | 🧩  컨테이너 출력 스트림 관리                   | 초급    | [실습 시작](https://labex.io/ko/labs/manage-container-output-streams-663783?course=cka-prep)        |
|     4 | 🧩  이미지 풀 (Image Pull) 실패 디버깅        | 초급    | [실습 시작](https://labex.io/ko/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|     5 | 🧩  실패한 Init 컨테이너 진단                 | 초급    | [실습 시작](https://labex.io/ko/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|     6 | 🧩  충돌하는 정적 파드 (Static Pod) 매니페스트 복구 | 초급    | [실습 시작](https://labex.io/ko/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|     7 | 🧩  노드 안전하게 드레인 및 복구하기               | 초급    | [실습 시작](https://labex.io/ko/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|     8 | 🧩  메트릭 기반 스케일링 신호 복구                | 초급    | [실습 시작](https://labex.io/ko/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|     9 | 🧩  중단된 서비스 트래픽 복구                   | 초급    | [실습 시작](https://labex.io/ko/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [CKA 실전 모의고사 01](https://labex.io/ko/courses/cka-practice-exam-01)

[![CKA 실전 모의고사 01](https://course-cover.labex.io/cka-practice-exam-01.png?lang=ko)](https://labex.io/ko/courses/cka-practice-exam-01)

스토리지, 트러블슈팅, 워크로드 및 스케줄링, 클러스터 아키텍처, 서비스 및 네트워킹 등 CKA 의 핵심 영역을 다루는 20 개의 독립적인 쿠버네티스 관리 실습 도전 과제로 구성된 CKA 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/cka-practice-exam-01) · 실습: 20

#### 스토리지

|   인덱스 | 이름                                               | 난이도   | 연습                                                                                                                       |
|-------|--------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  PersistentVolumeClaim 을 사용하여 애플리케이션 데이터 마운트하기 | 초급    | [도전 시작](https://labex.io/ko/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|     2 | 🎯  아카이브 데이터를 위한 정적 PersistentVolume 바인딩          | 초급    | [도전 시작](https://labex.io/ko/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### 문제 해결

|   인덱스 | 이름                                    | 난이도   | 연습                                                                                                                  |
|-------|---------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  중단된 서비스의 트래픽 복구                    | 초급    | [도전 시작](https://labex.io/ko/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|     2 | 🎯  실패한 디플로이먼트 롤아웃 복구                  | 초급    | [도전 시작](https://labex.io/ko/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|     3 | 🎯  테인트가 설정된 노드에 Pending 상태인 파드 스케줄링하기 | 초급    | [도전 시작](https://labex.io/ko/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|     4 | 🎯  네임스페이스 간 NetworkPolicy 접근 권한 복구    | 초급    | [도전 시작](https://labex.io/ko/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|     5 | 🎯  CoreDNS 이름 확인 복구                   | 초급    | [도전 시작](https://labex.io/ko/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|     6 | 🎯  클러스터 리소스 압박 진단                     | 초급    | [도전 시작](https://labex.io/ko/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### 워크로드 및 스케줄링

|   인덱스 | 이름                                       | 난이도   | 연습                                                                                                                              |
|-------|------------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  제어된 배포 롤아웃 수행                         | 초급    | [도전 시작](https://labex.io/ko/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|     2 | 🎯  ConfigMap 과 Secret 을 사용한 애플리케이션 설정 구성 | 초급    | [도전 시작](https://labex.io/ko/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|     3 | 🎯  어피니티 및 리소스 제어를 통한 워크로드 배치             | 초급    | [도전 시작](https://labex.io/ko/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### 클러스터 아키텍처, 설치 및 구성

|   인덱스 | 이름                                    | 난이도   | 연습                                                                                                                   |
|-------|---------------------------------------|-------|----------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  RBAC 을 사용하여 네임스페이스 운영자 권한 부여       | 초급    | [도전 시작](https://labex.io/ko/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|     2 | 🎯  etcd 스냅샷 백업 생성                     | 초급    | [도전 시작](https://labex.io/ko/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|     3 | 🎯  노드 안전하게 드레인 및 복구하기                 | 초급    | [도전 시작](https://labex.io/ko/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|     4 | 🎯  Helm 과 Kustomize 를 사용한 클러스터 애드온 배포 | 초급    | [도전 시작](https://labex.io/ko/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|     5 | 🎯  사용자 정의 리소스 정의 및 사용                 | 초급    | [도전 시작](https://labex.io/ko/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### 서비스 및 네트워킹

|   인덱스 | 이름                                  | 난이도   | 연습                                                                                                                  |
|-------|-------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  서비스를 통한 애플리케이션 노출                | 초급    | [도전 시작](https://labex.io/ko/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|     2 | 🎯  Ingress 를 통한 HTTP 트래픽 라우팅        | 초급    | [도전 시작](https://labex.io/ko/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|     3 | 🎯  NetworkPolicy 를 사용한 네임스페이스 격리 강화 | 초급    | [도전 시작](https://labex.io/ko/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|     4 | 🎯  내부 DNS 별칭 구성                     | 초급    | [도전 시작](https://labex.io/ko/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [CKA 실전 모의고사 02](https://labex.io/ko/courses/cka-practice-exam-02)

[![CKA 실전 모의고사 02](https://course-cover.labex.io/cka-practice-exam-02.png?lang=ko)](https://labex.io/ko/courses/cka-practice-exam-02)

공식 CKA 시험 영역을 다양한 운영 시나리오로 구성한 20 개의 쿠버네티스 관리 도전 과제로 이루어진 두 번째 독립형 CKA 실전 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/cka-practice-exam-02) · 실습: 20

#### 스토리지

|   인덱스 | 이름                                     | 난이도   | 연습                                                                                                                  |
|-------|----------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  StorageClass 를 사용하여 애플리케이션 로그 프로비저닝 | 초급    | [도전 시작](https://labex.io/ko/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|     2 | 🎯  Retain 정책이 적용된 볼륨의 데이터 보존하기         | 초급    | [도전 시작](https://labex.io/ko/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### 문제 해결

|   인덱스 | 이름                            | 난이도   | 연습                                                                                                                   |
|-------|-------------------------------|-------|----------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  충돌하는 정적 파드 매니페스트 복구        | 초급    | [도전 시작](https://labex.io/ko/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|     2 | 🎯  손상된 kubelet 이미지 풀 경로 복구    | 초급    | [도전 시작](https://labex.io/ko/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|     3 | 🎯  메트릭 기반 스케일링 신호 복구          | 초급    | [도전 시작](https://labex.io/ko/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|     4 | 🎯  실패한 Init 컨테이너 시작 진단        | 초급    | [도전 시작](https://labex.io/ko/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|     5 | 🎯  유지보수 후 노드 스케줄링 복구          | 초급    | [도전 시작](https://labex.io/ko/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|     6 | 🎯  헤드리스 워크로드를 위한 서비스 디스커버리 복구 | 초급    | [도전 시작](https://labex.io/ko/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### 워크로드 및 스케줄링

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                                      |
|-------|------------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  Horizontal Pod Autoscaling 구성   | 초급    | [도전 시작](https://labex.io/ko/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|     2 | 🎯  PodDisruptionBudget 을 통한 가용성 보호 | 초급    | [도전 시작](https://labex.io/ko/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|     3 | 🎯  Admission 및 런타임 설정을 통한 Pod 제약   | 초급    | [도전 시작](https://labex.io/ko/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### 클러스터 아키텍처, 설치 및 구성

|   인덱스 | 이름                                            | 난이도   | 연습                                                                                                                   |
|-------|-----------------------------------------------|-------|----------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  읽기 전용 클러스터 진단 권한 위임                        | 초급    | [도전 시작](https://labex.io/ko/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|     2 | 🎯  kubeadm 인증서 검사 및 갱신                        | 초급    | [도전 시작](https://labex.io/ko/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|     3 | 🎯  계획된 업그레이드를 위한 노드 준비                        | 초급    | [도전 시작](https://labex.io/ko/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|     4 | 🎯  Kustomize 를 사용하여 Staged CSI Mock 드라이버 설치하기 | 초급    | [도전 시작](https://labex.io/ko/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|     5 | 🎯  운영자가 관리하는 커스텀 리소스 검증                       | 초급    | [도전 시작](https://labex.io/ko/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### 서비스 및 네트워킹

|   인덱스 | 이름                               | 난이도   | 연습                                                                                                             |
|-------|----------------------------------|-------|----------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  Gateway API 라우팅을 통한 API 게시    | 초급    | [도전 시작](https://labex.io/ko/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|     2 | 🎯  EndpointSlice 기반 서비스 액세스 복구   | 초급    | [도전 시작](https://labex.io/ko/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|     3 | 🎯  NetworkPolicy 를 이용한 Egress 제한 | 초급    | [도전 시작](https://labex.io/ko/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|     4 | 🎯  CoreDNS 조건부 포워딩 구성            | 초급    | [도전 시작](https://labex.io/ko/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

