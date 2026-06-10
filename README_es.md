# Formación CKA Certification Prep Path

## Idiomas

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/es/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Iniciar-Ruta-whitesmoke?style=for-the-badge)](https://labex.io/es/learn/cka)

Prepárate para el examen Certified Kubernetes Administrator (CKA) con una ruta de aprendizaje estructurada y práctica. Este plan se centra en administración de clústeres, instalación y configuración, cargas de trabajo y programación, servicios y redes, almacenamiento y resolución de problemas en Kubernetes, tareas basadas en rendimiento al estilo CKA y escenarios reales. Los cursos CKA, laboratorios y exámenes simulados se irán incorporando para reforzar habilidades alineadas con los objetivos CKA.

**Cursos**: 3 · **Laboratorios**: 88

## Cursos

### 1. [Preparación para CKA](https://labex.io/es/courses/cka-prep)

[![Preparación para CKA](https://course-cover.labex.io/cka-prep.png?lang=es)](https://labex.io/es/courses/cka-prep)

Un curso de preparación para CKA ideal para principiantes, que incluye 48 experimentos guiados de administración de Kubernetes, organizados desde la orientación del clúster hasta cargas de trabajo, arquitectura, redes, almacenamiento, resolución de problemas y mantenimiento.

[Iniciar Curso](https://labex.io/es/courses/cka-prep) · Laboratorios: 48

#### Orientación del clúster y fundamentos de administración

|   Índice | Nombre                                                             | Dificultad   | Práctica                                                                                                              |
|----------|--------------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Inspeccionar kubeconfig y contextos                             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|        2 | 🧩  Explorar nodos y la versión del clúster                         | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|        3 | 🧩  Inspeccionar recursos de API y espacios de nombres (Namespaces) | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|        4 | 🧩  Leer eventos y condiciones de objetos                           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|        5 | 🧩  Uso de etiquetas, selectores y selectores de campo              | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|        6 | 🧩  Gestión de Namespaces para flujos de trabajo administrativos    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|        7 | 🧩  Uso de Dry Run y Explain para manifiestos                       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### Cargas de trabajo y programación

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                               |
|----------|----------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Inspeccionar el comportamiento de Deployments y ReplicaSets | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|        2 | 🧩  Realizar un despliegue controlado (Rollout)                 | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|        3 | 🧩  Revertir un despliegue fallido                              | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|        4 | 🧩  Configurar cargas de trabajo con ConfigMaps y Secrets       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|        5 | 🧩  Configurar solicitudes, límites y evidencia de recursos     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|        6 | 🧩  Programación de Pods con selectores de nodo (nodeSelector)  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|        7 | 🧩  Ubicar cargas de trabajo con reglas de afinidad             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|        8 | 🧩  Uso de Taints y Tolerations                                 | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|        9 | 🧩  Proteger la disponibilidad con PodDisruptionBudgets         | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### Arquitectura, instalación y configuración del clúster

|   Índice | Nombre                                                   | Dificultad   | Práctica                                                                                                          |
|----------|----------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Inspeccionar los componentes del plano de control     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|        2 | 🧩  Explorar los artefactos de configuración de kubeadm   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|        3 | 🧩  Inspeccionar certificados y la confianza del clúster  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|        4 | 🧩  Conceder RBAC de operador de espacio de nombres       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|        5 | 🧩  Delegar diagnósticos de clúster de solo lectura       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|        6 | 🧩  Implementar un complemento con Helm                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|        7 | 🧩  Personalización de recursos del clúster con Kustomize | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|        8 | 🧩  Definir y utilizar un recurso personalizado           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|        9 | 🧩  Inspeccionar las interfaces CNI, CSI y CRI            | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### Servicios y redes

|   Índice | Nombre                                                  | Dificultad   | Práctica                                                                                                        |
|----------|---------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Exponer aplicaciones con Services                    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/expose-applications-with-services-663774?course=cka-prep)        |
|        2 | 🧩  Reparar el acceso al Service mediante EndpointSlice  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|        3 | 🧩  Solución de problemas de resolución DNS de servicios | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|        4 | 🧩  Configurar el reenvío condicional de CoreDNS         | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|        5 | 🧩  Restringir la salida (egress) con NetworkPolicy      | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|        6 | 🧩  Reparar el acceso de NetworkPolicy                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|        7 | 🧩  Enrutar tráfico HTTP con Ingress                     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|        8 | 🧩  Publicar una API con Gateway Routing                 | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### Almacenamiento

|   Índice | Nombre                                                      | Dificultad   | Práctica                                                                                                               |
|----------|-------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Inspeccionar StorageClasses y aprovisionamiento dinámico | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|        2 | 🧩  Crear un PVC para datos de aplicación                    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|        3 | 🧩  Vincular un PersistentVolume estático                    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|        4 | 🧩  Configurar modos de acceso y modos de volumen            | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|        5 | 🧩  Preservar datos con políticas de reclamación             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|        6 | 🧩  Solución de problemas de vinculación y montaje de PVC    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### Solución de problemas y mantenimiento

|   Índice | Nombre                                                  | Dificultad   | Práctica                                                                                                      |
|----------|---------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Diagnosticar la presión de recursos en el clúster    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|        2 | 🧩  Monitoreo de Pods con Metrics y Top                  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|        3 | 🧩  Gestionar flujos de salida de contenedores           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/manage-container-output-streams-663783?course=cka-prep)        |
|        4 | 🧩  Depurar fallos de extracción de imágenes             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|        5 | 🧩  Diagnosticar contenedores de inicialización fallidos | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|        6 | 🧩  Restaurar un manifiesto de Pod estático que falla    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|        7 | 🧩  Drenar y restaurar un nodo de forma segura           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|        8 | 🧩  Recuperar señales de escalado basadas en métricas    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|        9 | 🧩  Restaurar el tráfico de un servicio averiado         | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [Examen de práctica CKA 01](https://labex.io/es/courses/cka-practice-exam-01)

[![Examen de práctica CKA 01](https://course-cover.labex.io/cka-practice-exam-01.png?lang=es)](https://labex.io/es/courses/cka-practice-exam-01)

Un examen de práctica práctico de CKA con 20 desafíos independientes de administración de Kubernetes que cubren almacenamiento, resolución de problemas, cargas de trabajo y programación, arquitectura de clústeres, y servicios y redes.

[Iniciar Curso](https://labex.io/es/courses/cka-practice-exam-01) · Laboratorios: 20

#### Almacenamiento

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                                           |
|----------|----------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Montar datos de aplicación con un PersistentVolumeClaim     | Principiante | [Iniciar Desafío](https://labex.io/es/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|        2 | 🎯  Vincular un PersistentVolume estático para datos de archivo | Principiante | [Iniciar Desafío](https://labex.io/es/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### Resolución de problemas

|   Índice | Nombre                                                          | Dificultad   | Práctica                                                                                                                      |
|----------|-----------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Restaurar el tráfico a un servicio averiado                  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|        2 | 🎯  Recuperar un despliegue (Deployment) fallido                 | Principiante | [Iniciar Desafío](https://labex.io/es/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|        3 | 🎯  Programar Pods pendientes en un nodo con Taint               | Principiante | [Iniciar Desafío](https://labex.io/es/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|        4 | 🎯  Reparar el acceso de NetworkPolicy entre espacios de nombres | Principiante | [Iniciar Desafío](https://labex.io/es/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|        5 | 🎯  Restaurar la resolución de nombres de CoreDNS                | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|        6 | 🎯  Diagnosticar la presión de recursos del clúster              | Principiante | [Iniciar Desafío](https://labex.io/es/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### Cargas de trabajo y programación

|   Índice | Nombre                                                                  | Dificultad   | Práctica                                                                                                                                  |
|----------|-------------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Realizar un despliegue controlado                                    | Principiante | [Iniciar Desafío](https://labex.io/es/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|        2 | 🎯  Configurar los ajustes de la aplicación con ConfigMaps y Secrets     | Principiante | [Iniciar Desafío](https://labex.io/es/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|        3 | 🎯  Asignación de cargas de trabajo con afinidad y controles de recursos | Principiante | [Iniciar Desafío](https://labex.io/es/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### Arquitectura, instalación y configuración del clúster

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                                       |
|----------|----------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Otorgar permisos de operador de espacio de nombres con RBAC | Principiante | [Iniciar Desafío](https://labex.io/es/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|        2 | 🎯  Crear una copia de seguridad (snapshot) de etcd             | Principiante | [Iniciar Desafío](https://labex.io/es/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|        3 | 🎯  Drenar y restaurar un nodo de forma segura                  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|        4 | 🎯  Implementar un complemento de clúster con Helm y Kustomize  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|        5 | 🎯  Definir y utilizar un recurso personalizado                 | Principiante | [Iniciar Desafío](https://labex.io/es/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### Servicios y redes

|   Índice | Nombre                                                | Dificultad   | Práctica                                                                                                                      |
|----------|-------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Exponer una aplicación con Services                | Principiante | [Iniciar Desafío](https://labex.io/es/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|        2 | 🎯  Enrutar tráfico HTTP con Ingress                   | Principiante | [Iniciar Desafío](https://labex.io/es/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|        3 | 🎯  Aplicar aislamiento de Namespace con NetworkPolicy | Principiante | [Iniciar Desafío](https://labex.io/es/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|        4 | 🎯  Configurar un alias DNS interno                    | Principiante | [Iniciar Desafío](https://labex.io/es/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [Examen de práctica CKA 02](https://labex.io/es/courses/cka-practice-exam-02)

[![Examen de práctica CKA 02](https://course-cover.labex.io/cka-practice-exam-02.png?lang=es)](https://labex.io/es/courses/cka-practice-exam-02)

Un segundo examen de práctica independiente al estilo CKA, que incluye 20 desafíos de administración de Kubernetes que cubren los dominios públicos de CKA a través de diversos escenarios operativos.

[Iniciar Curso](https://labex.io/es/courses/cka-practice-exam-02) · Laboratorios: 20

#### Almacenamiento

|   Índice | Nombre                                                      | Dificultad   | Práctica                                                                                                                      |
|----------|-------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Provisión de registros de aplicación con un StorageClass | Principiante | [Iniciar Desafío](https://labex.io/es/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|        2 | 🎯  Preservar datos liberados de un volumen retenido         | Principiante | [Iniciar Desafío](https://labex.io/es/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### Resolución de problemas

|   Índice | Nombre                                                                                | Dificultad   | Práctica                                                                                                                       |
|----------|---------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Restaurar un manifiesto de Pod estático que falla                                  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|        2 | 🎯  Reparar una ruta de extracción de imagen de kubelet rota                           | Principiante | [Iniciar Desafío](https://labex.io/es/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|        3 | 🎯  Recuperar señales de escalado basadas en métricas                                  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|        4 | 🎯  Diagnosticar el inicio fallido de un contenedor de inicialización (Init Container) | Principiante | [Iniciar Desafío](https://labex.io/es/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|        5 | 🎯  Restaurar la programación de nodos tras el mantenimiento                           | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|        6 | 🎯  Reparar el descubrimiento de servicios para cargas de trabajo headless             | Principiante | [Iniciar Desafío](https://labex.io/es/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### Cargas de trabajo y programación

|   Índice | Nombre                                                                   | Dificultad   | Práctica                                                                                                                          |
|----------|--------------------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Configurar el escalado automático horizontal de pods (HPA)            | Principiante | [Iniciar Desafío](https://labex.io/es/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|        2 | 🎯  Proteger la disponibilidad con un PodDisruptionBudget                 | Principiante | [Iniciar Desafío](https://labex.io/es/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|        3 | 🎯  Restringir Pods con configuraciones de admisión y tiempo de ejecución | Principiante | [Iniciar Desafío](https://labex.io/es/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### Arquitectura, instalación y configuración del clúster

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                                       |
|----------|----------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Delegar diagnósticos de clúster de solo lectura             | Principiante | [Iniciar Desafío](https://labex.io/es/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|        2 | 🎯  Inspeccionar y renovar certificados de kubeadm              | Principiante | [Iniciar Desafío](https://labex.io/es/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|        3 | 🎯  Preparar un nodo para una actualización planificada         | Principiante | [Iniciar Desafío](https://labex.io/es/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|        4 | 🎯  Instalar un controlador CSI Mock preparado con Kustomize    | Principiante | [Iniciar Desafío](https://labex.io/es/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|        5 | 🎯  Validar un recurso personalizado gestionado por un operador | Principiante | [Iniciar Desafío](https://labex.io/es/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### Servicios y redes

|   Índice | Nombre                                                        | Dificultad   | Práctica                                                                                                                 |
|----------|---------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Publicar una API con el enrutamiento de Gateway API        | Principiante | [Iniciar Desafío](https://labex.io/es/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|        2 | 🎯  Reparar el acceso al servicio basado en EndpointSlice      | Principiante | [Iniciar Desafío](https://labex.io/es/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|        3 | 🎯  Restringir el tráfico de salida (egress) con NetworkPolicy | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|        4 | 🎯  Configurar el reenvío condicional de CoreDNS               | Principiante | [Iniciar Desafío](https://labex.io/es/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## Acerca de LabEx

[LabEx](https://labex.io) es una plataforma de aprendizaje interactiva y práctica dedicada a la programación y la tecnología. Combina laboratorios, asistencia de IA y máquinas virtuales para proporcionar una experiencia de aprendizaje práctica sin videos. Con un enfoque estricto de 'Aprender Haciendo', entornos en línea interactivos dentro del navegador con verificaciones paso a paso automatizadas, organización de contenido estructurada con el sistema basado en Árbol de Habilidades, y un recurso de aprendizaje en crecimiento de 30 Árboles de Habilidades y más de 6,000 Laboratorios, LabEx ofrece educación práctica integral. La plataforma incluye al asistente de aprendizaje Labby, construido sobre los últimos modelos de IA, que proporciona una experiencia de aprendizaje conversacional.

