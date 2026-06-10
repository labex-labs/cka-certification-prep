# Обучение CKA Certification Prep Path

## Языки

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ru/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Начать-Путь-whitesmoke?style=for-the-badge)](https://labex.io/ru/learn/cka)

Готовьтесь к экзамену Certified Kubernetes Administrator (CKA) по структурированной практической программе. Акцент на администрирование кластера, установка и настройка, рабочие нагрузки и планирование, сервисы и сеть, хранилище и устранение неполадок в Kubernetes, практических заданиях в стиле CKA и сценариях из практики. Курсы CKA, лаборатории и пробные экзамены будут добавляться постепенно.

**Курсы**: 3 · **Лаборатории**: 88

## Курсы

### 1. [Подготовка к CKA](https://labex.io/ru/courses/cka-prep)

[![Подготовка к CKA](https://course-cover.labex.io/cka-prep.png?lang=ru)](https://labex.io/ru/courses/cka-prep)

Курс по подготовке к CKA для начинающих, включающий 48 практических лабораторных работ по Kubernetes. Программа охватывает всё: от основ кластера до управления рабочими нагрузками, архитектуры, сетевого взаимодействия, хранилищ, устранения неполадок и обслуживания.

[Начать Курс](https://labex.io/ru/courses/cka-prep) · Лаборатории: 48

#### Знакомство с кластером и основы администрирования

|   Индекс | Название                                                                 | Сложность   | Практика                                                                                                             |
|----------|--------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Изучение kubeconfig и контекстов                                      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|        2 | 🧩  Изучение узлов и версии кластера                                      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|        3 | 🧩  Изучение ресурсов API и пространств имен                              | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|        4 | 🧩  Чтение событий и условий объектов                                     | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|        5 | 🧩  Использование меток (Labels), селекторов и селекторов полей           | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|        6 | 🧩  Управление пространствами имен для административных рабочих процессов | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|        7 | 🧩  Использование Dry Run и Explain для манифестов                        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### Рабочие нагрузки и планирование

|   Индекс | Название                                                          | Сложность   | Практика                                                                                                              |
|----------|-------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Изучение поведения Deployment и ReplicaSet                     | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|        2 | 🧩  Выполнение контролируемого развертывания (Rollout)             | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|        3 | 🧩  Откат неудачного развертывания                                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|        4 | 🧩  Настройка рабочих нагрузок с помощью ConfigMaps и Secrets      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|        5 | 🧩  Настройка запросов, лимитов и проверка ресурсов                | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|        6 | 🧩  Планирование подов с помощью селекторов узлов (Node Selectors) | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|        7 | 🧩  Размещение рабочих нагрузок с помощью правил аффинити          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|        8 | 🧩  Использование Taints и Tolerations                             | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|        9 | 🧩  Обеспечение доступности с помощью PodDisruptionBudgets         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### Архитектура, установка и настройка кластера

|   Индекс | Название                                                               | Сложность   | Практика                                                                                                         |
|----------|------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Инспекция компонентов Control Plane                                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|        2 | 🧩  Изучение конфигурационных артефактов kubeadm                        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|        3 | 🧩  Проверка сертификатов и доверия в кластере                          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|        4 | 🧩  Предоставление прав RBAC оператору пространства имен                | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|        5 | 🧩  Делегирование прав на диагностику кластера в режиме «только чтение» | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|        6 | 🧩  Развертывание дополнения с помощью Helm                             | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|        7 | 🧩  Настройка ресурсов кластера с помощью Kustomize                     | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|        8 | 🧩  Определение и использование пользовательского ресурса               | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|        9 | 🧩  Изучение интерфейсов CNI, CSI и CRI                                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### Сервисы и сетевое взаимодействие

|   Индекс | Название                                                           | Сложность   | Практика                                                                                                       |
|----------|--------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Публикация приложений с помощью сервисов (Services)             | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/expose-applications-with-services-663774?course=cka-prep)        |
|        2 | 🧩  Восстановление доступа к Service через EndpointSlice            | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|        3 | 🧩  Устранение неполадок DNS-разрешения сервисов                    | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|        4 | 🧩  Настройка условной пересылки (Conditional Forwarding) в CoreDNS | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|        5 | 🧩  Ограничение исходящего трафика (Egress) с помощью NetworkPolicy | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|        6 | 🧩  Исправление доступа NetworkPolicy                               | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|        7 | 🧩  Маршрутизация HTTP-трафика с помощью Ingress                    | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|        8 | 🧩  Публикация API с использованием Gateway Routing                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### Хранилище

|   Индекс | Название                                                                           | Сложность   | Практика                                                                                                              |
|----------|------------------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Изучение StorageClasses и динамического выделения ресурсов                      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|        2 | 🧩  Создание PVC для данных приложения                                              | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|        3 | 🧩  Привязка статического PersistentVolume                                          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|        4 | 🧩  Настройка режимов доступа и режимов томов                                       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|        5 | 🧩  Сохранение данных с помощью политик повторного использования (Reclaim Policies) | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|        6 | 🧩  Устранение неполадок при привязке и монтировании PVC                            | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### Устранение неполадок и обслуживание

|   Индекс | Название                                                    | Сложность   | Практика                                                                                                     |
|----------|-------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Диагностика нехватки ресурсов кластера                   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|        2 | 🧩  Мониторинг подов с помощью Metrics и Top                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|        3 | 🧩  Управление потоками вывода контейнеров                   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/manage-container-output-streams-663783?course=cka-prep)        |
|        4 | 🧩  Отладка ошибок при извлечении образов                    | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|        5 | 🧩  Диагностика сбоев init-контейнеров                       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|        6 | 🧩  Восстановление манифеста аварийного статического пода    | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|        7 | 🧩  Безопасное освобождение и восстановление узла            | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|        8 | 🧩  Восстановление сигналов масштабирования на основе метрик | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|        9 | 🧩  Восстановление нарушенного трафика сервиса               | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [Практический экзамен CKA 01](https://labex.io/ru/courses/cka-practice-exam-01)

[![Практический экзамен CKA 01](https://course-cover.labex.io/cka-practice-exam-01.png?lang=ru)](https://labex.io/ru/courses/cka-practice-exam-01)

Практический экзамен CKA с 20 независимыми задачами по администрированию Kubernetes, охватывающими хранилища, устранение неполадок, рабочие нагрузки и планирование, архитектуру кластера, а также сервисы и сети.

[Начать Курс](https://labex.io/ru/courses/cka-practice-exam-01) · Лаборатории: 20

#### Хранилище

|   Индекс | Название                                                         | Сложность   | Практика                                                                                                                            |
|----------|------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Подключение данных приложения с помощью PersistentVolumeClaim | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|        2 | 🎯  Привязка статического PersistentVolume для архивных данных    | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### Устранение неполадок

|   Индекс | Название                                                                  | Сложность   | Практика                                                                                                                       |
|----------|---------------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление трафика к неисправному сервису                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|        2 | 🎯  Восстановление зависшего развертывания (Deployment)                    | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|        3 | 🎯  Планирование ожидающих (Pending) подов на узле с ограничениями (Taint) | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|        4 | 🎯  Исправление доступа NetworkPolicy между пространствами имен            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|        5 | 🎯  Восстановление разрешения имен CoreDNS                                 | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|        6 | 🎯  Диагностика нагрузки на ресурсы кластера                               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### Рабочие нагрузки и планирование

|   Индекс | Название                                                                     | Сложность   | Практика                                                                                                                                   |
|----------|------------------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Выполнение контролируемого развертывания (Rollout)                        | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|        2 | 🎯  Настройка параметров приложения с помощью ConfigMap и Secret              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|        3 | 🎯  Размещение рабочих нагрузок с использованием аффинити и контроля ресурсов | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### Архитектура кластера, установка и настройка

|   Индекс | Название                                                          | Сложность   | Практика                                                                                                                        |
|----------|-------------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Предоставление прав оператора пространства имен с помощью RBAC | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|        2 | 🎯  Создание резервной копии etcd (snapshot)                       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|        3 | 🎯  Безопасное освобождение и восстановление узла                  | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|        4 | 🎯  Развертывание дополнения кластера с помощью Helm и Kustomize   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|        5 | 🎯  Определение и использование пользовательского ресурса          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### Сервисы и сетевое взаимодействие

|   Индекс | Название                                                             | Сложность   | Практика                                                                                                                       |
|----------|----------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Публикация приложения с помощью сервисов                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|        2 | 🎯  Маршрутизация HTTP-трафика с помощью Ingress                      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|        3 | 🎯  Принудительная изоляция пространства имен с помощью NetworkPolicy | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|        4 | 🎯  Настройка внутреннего DNS-алиаса                                  | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [Практический экзамен CKA 02](https://labex.io/ru/courses/cka-practice-exam-02)

[![Практический экзамен CKA 02](https://course-cover.labex.io/cka-practice-exam-02.png?lang=ru)](https://labex.io/ru/courses/cka-practice-exam-02)

Второй независимый практический экзамен в стиле CKA, включающий 20 задач по администрированию Kubernetes, охватывающих все ключевые области CKA через различные операционные сценарии.

[Начать Курс](https://labex.io/ru/courses/cka-practice-exam-02) · Лаборатории: 20

#### Хранилище

|   Индекс | Название                                                  | Сложность   | Практика                                                                                                                       |
|----------|-----------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Предоставление логов приложения с помощью StorageClass | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|        2 | 🎯  Сохранение данных из тома с политикой Retain           | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### Устранение неполадок

|   Индекс | Название                                                             | Сложность   | Практика                                                                                                                        |
|----------|----------------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление манифеста аварийного статического пода             | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|        2 | 🎯  Исправление ошибки пути извлечения образа kubelet                 | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|        3 | 🎯  Восстановление сигналов масштабирования на основе метрик          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|        4 | 🎯  Диагностика сбоя запуска Init-контейнера                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|        5 | 🎯  Восстановление планирования узлов после технического обслуживания | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|        6 | 🎯  Восстановление обнаружения сервисов для headless-нагрузок         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### Рабочие нагрузки и планирование

|   Индекс | Название                                                             | Сложность   | Практика                                                                                                                           |
|----------|----------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Настройка горизонтального автомасштабирования подов (HPA)         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|        2 | 🎯  Обеспечение доступности с помощью PodDisruptionBudget             | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|        3 | 🎯  Ограничение подов с помощью Admission и настроек среды выполнения | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### Архитектура кластера, установка и настройка

|   Индекс | Название                                                               | Сложность   | Практика                                                                                                                        |
|----------|------------------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Делегирование прав на диагностику кластера в режиме «только чтение» | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|        2 | 🎯  Проверка и обновление сертификатов kubeadm                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|        3 | 🎯  Подготовка узла к плановому обновлению                              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|        4 | 🎯  Установка промежуточного драйвера CSI Mock с помощью Kustomize      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|        5 | 🎯  Проверка пользовательского ресурса, управляемого оператором         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### Сервисы и сетевое взаимодействие

|   Индекс | Название                                                    | Сложность   | Практика                                                                                                                  |
|----------|-------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Публикация API с помощью маршрутизации Gateway API       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|        2 | 🎯  Восстановление доступа к сервису на основе EndpointSlice | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|        3 | 🎯  Ограничение исходящего трафика с помощью NetworkPolicy   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|        4 | 🎯  Настройка условной пересылки CoreDNS                     | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

