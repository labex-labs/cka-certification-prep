# Formation CKA Certification Prep Path

## Langues

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/fr/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Commencer-le-Parcours-whitesmoke?style=for-the-badge)](https://labex.io/fr/learn/cka)

Préparez-vous à l'examen Certified Kubernetes Administrator (CKA) grâce à un parcours structuré et orienté pratique. Ce plan met l'accent sur administration de cluster, installation et configuration, charges de travail et planification, services et réseau, stockage et dépannage dans Kubernetes, les tâches en mode performance au style CKA et des scénarios réalistes. Des cours CKA, des labs et des examens blancs seront ajoutés progressivement.

**Cours**: 3 · **Labs**: 88

## Cours

### 1. [Préparation CKA](https://labex.io/fr/courses/cka-prep)

[![Préparation CKA](https://course-cover.labex.io/cka-prep.png?lang=fr)](https://labex.io/fr/courses/cka-prep)

Un cours de préparation au CKA adapté aux débutants, comprenant 48 travaux pratiques guidés sur l'administration de Kubernetes, allant de la découverte du cluster aux charges de travail, en passant par l'architecture, le réseau, le stockage, le dépannage et la maintenance.

[Commencer le Cours](https://labex.io/fr/courses/cka-prep) · Labs: 48

#### Orientation du cluster et bases de l'administration

|   Index | Nom                                                                  | Difficulté   | Pratique                                                                                                           |
|---------|----------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Inspection de kubeconfig et des contextes                         | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|       2 | 🧩  Explorer les nœuds et la version du cluster                       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|       3 | 🧩  Inspection des ressources API et des espaces de noms              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|       4 | 🧩  Lire les événements et les conditions des objets                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|       5 | 🧩  Utiliser des labels, des sélecteurs et des sélecteurs de champs   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|       6 | 🧩  Gérer les espaces de noms pour les flux de travail administratifs | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|       7 | 🧩  Utiliser le Dry Run et Explain pour les manifestes                | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### Charges de travail et planification

|   Index | Nom                                                                     | Difficulté   | Pratique                                                                                                            |
|---------|-------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Inspecter le comportement des Deployment et ReplicaSet               | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|       2 | 🧩  Effectuer un déploiement contrôlé                                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|       3 | 🧩  Annuler un déploiement défectueux                                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|       4 | 🧩  Configurer des charges de travail avec des ConfigMaps et des Secrets | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|       5 | 🧩  Définir les requêtes, les limites et les preuves de ressources       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|       6 | 🧩  Planification de Pods avec des sélecteurs de nœuds (Node Selectors)  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|       7 | 🧩  Placer des charges de travail avec des règles d'affinité             | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|       8 | 🧩  Utiliser les Taints et Tolerations                                   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|       9 | 🧩  Protéger la disponibilité avec les PodDisruptionBudgets              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### Architecture, installation et configuration du cluster

|   Index | Nom                                                         | Difficulté   | Pratique                                                                                                       |
|---------|-------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Inspection des composants du plan de contrôle            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|       2 | 🧩  Explorer les artefacts de configuration de kubeadm       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|       3 | 🧩  Inspection des certificats et de la confiance du cluster | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|       4 | 🧩  Accorder des permissions RBAC d'opérateur de namespace   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|       5 | 🧩  Délégation de diagnostics de cluster en lecture seule    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|       6 | 🧩  Déployer un addon avec Helm                              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|       7 | 🧩  Personnaliser les ressources du cluster avec Kustomize   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|       8 | 🧩  Définir et utiliser une ressource personnalisée          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|       9 | 🧩  Inspecter les interfaces CNI, CSI et CRI                 | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### Services et mise en réseau

|   Index | Nom                                                          | Difficulté   | Pratique                                                                                                     |
|---------|--------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Exposer des applications avec des Services                | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/expose-applications-with-services-663774?course=cka-prep)        |
|       2 | 🧩  Réparer l'accès au Service via EndpointSlice              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|       3 | 🧩  Dépannage de la résolution DNS des services               | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|       4 | 🧩  Configurer le transfert conditionnel CoreDNS              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|       5 | 🧩  Restreindre le trafic sortant (egress) avec NetworkPolicy | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|       6 | 🧩  Réparer l'accès via NetworkPolicy                         | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|       7 | 🧩  Routage du trafic HTTP avec Ingress                       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|       8 | 🧩  Publier une API avec le routage Gateway                   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### Stockage

|   Index | Nom                                                                             | Difficulté   | Pratique                                                                                                            |
|---------|---------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Inspecter les StorageClasses et le provisionnement dynamique                 | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|       2 | 🧩  Créer un PVC pour les données d'application                                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|       3 | 🧩  Lier un PersistentVolume statique                                            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|       4 | 🧩  Configurer les modes d'accès et les modes de volume                          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|       5 | 🧩  Préserver les données avec les politiques de récupération (Reclaim Policies) | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|       6 | 🧩  Dépannage des liaisons et montages de PVC                                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### Dépannage et maintenance

|   Index | Nom                                                                           | Difficulté   | Pratique                                                                                                   |
|---------|-------------------------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Diagnostiquer la pression sur les ressources du cluster                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|       2 | 🧩  Surveiller les Pods avec Metrics et Top                                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|       3 | 🧩  Gérer les flux de sortie des conteneurs                                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/manage-container-output-streams-663783?course=cka-prep)        |
|       4 | 🧩  Déboguer les échecs de récupération d'image                                | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|       5 | 🧩  Diagnostiquer les échecs des conteneurs d'initialisation (Init Containers) | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|       6 | 🧩  Restaurer un manifeste de Pod statique en échec                            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|       7 | 🧩  Drainer et restaurer un nœud en toute sécurité                             | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|       8 | 🧩  Récupérer les signaux de mise à l'échelle basés sur les métriques          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|       9 | 🧩  Restaurer le trafic d'un service défaillant                                | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [Examen blanc CKA 01](https://labex.io/fr/courses/cka-practice-exam-01)

[![Examen blanc CKA 01](https://course-cover.labex.io/cka-practice-exam-01.png?lang=fr)](https://labex.io/fr/courses/cka-practice-exam-01)

Un examen blanc pratique pour la certification CKA composé de 20 défis d'administration Kubernetes indépendants, couvrant le stockage, le dépannage, les charges de travail et la planification, l'architecture de cluster, ainsi que les services et la mise en réseau.

[Commencer le Cours](https://labex.io/fr/courses/cka-practice-exam-01) · Labs: 20

#### Stockage

|   Index | Nom                                                               | Difficulté   | Pratique                                                                                                                             |
|---------|-------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Monter des données d'application avec un PersistentVolumeClaim | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|       2 | 🎯  Lier un PersistentVolume statique pour des données d'archive   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### Dépannage

|   Index | Nom                                                        | Difficulté   | Pratique                                                                                                                        |
|---------|------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Rétablir le trafic vers un service défaillant           | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|       2 | 🎯  Récupérer un déploiement Kubernetes bloqué              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|       3 | 🎯  Planifier des Pods en attente sur un nœud avec taint    | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|       4 | 🎯  Réparer l'accès NetworkPolicy entre les espaces de noms | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|       5 | 🎯  Restaurer la résolution de noms CoreDNS                 | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|       6 | 🎯  Diagnostiquer la pression sur les ressources du cluster | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### Charges de travail et planification

|   Index | Nom                                                                             | Difficulté   | Pratique                                                                                                                                    |
|---------|---------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Effectuer un déploiement contrôlé                                            | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|       2 | 🎯  Configurer les paramètres d'application avec des ConfigMaps et des Secrets   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|       3 | 🎯  Placer des charges de travail avec l'affinité et les contrôles de ressources | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### Architecture, installation et configuration du cluster

|   Index | Nom                                                                    | Difficulté   | Pratique                                                                                                                         |
|---------|------------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Accorder des permissions d'opérateur de namespace avec RBAC         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|       2 | 🎯  Créer une sauvegarde instantanée (snapshot) d'etcd                  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|       3 | 🎯  Drainer et restaurer un nœud en toute sécurité                      | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|       4 | 🎯  Déployer un module complémentaire de cluster avec Helm et Kustomize | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|       5 | 🎯  Définir et utiliser une ressource personnalisée                     | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### Services et mise en réseau

|   Index | Nom                                                             | Difficulté   | Pratique                                                                                                                        |
|---------|-----------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Exposer une application avec des Services                    | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|       2 | 🎯  Routage du trafic HTTP avec Ingress                          | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|       3 | 🎯  Appliquer l'isolation des espaces de noms avec NetworkPolicy | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|       4 | 🎯  Configurer un alias DNS interne                              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [Examen blanc CKA 02](https://labex.io/fr/courses/cka-practice-exam-02)

[![Examen blanc CKA 02](https://course-cover.labex.io/cka-practice-exam-02.png?lang=fr)](https://labex.io/fr/courses/cka-practice-exam-02)

Un second examen blanc indépendant de type CKA, composé de 20 défis d'administration Kubernetes couvrant les domaines officiels de la certification CKA à travers divers scénarios opérationnels.

[Commencer le Cours](https://labex.io/fr/courses/cka-practice-exam-02) · Labs: 20

#### Stockage

|   Index | Nom                                                              | Difficulté   | Pratique                                                                                                                        |
|---------|------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Provisionner des journaux d'application avec une StorageClass | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|       2 | 🎯  Préserver les données libérées d'un volume conservé           | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### Dépannage

|   Index | Nom                                                                                    | Difficulté   | Pratique                                                                                                                         |
|---------|----------------------------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Restaurer un manifeste de Pod statique en échec                                     | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|       2 | 🎯  Réparer un chemin de tirage d'image kubelet défectueux                              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|       3 | 🎯  Récupérer les signaux de mise à l'échelle basés sur les métriques                   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|       4 | 🎯  Diagnostiquer l'échec de démarrage d'un conteneur d'initialisation (Init Container) | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|       5 | 🎯  Restaurer la planification des nœuds après une dérive de maintenance                | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|       6 | 🎯  Réparer la découverte de service pour les charges de travail headless               | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### Charges de travail et planification

|   Index | Nom                                                                    | Difficulté   | Pratique                                                                                                                            |
|---------|------------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Configurer l'autoscaling horizontal des pods (HPA)                  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|       2 | 🎯  Protéger la disponibilité avec un PodDisruptionBudget               | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|       3 | 🎯  Restreindre les Pods avec des paramètres d'admission et d'exécution | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### Architecture, installation et configuration du cluster

|   Index | Nom                                                           | Difficulté   | Pratique                                                                                                                         |
|---------|---------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Délégation de diagnostics de cluster en lecture seule      | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|       2 | 🎯  Inspecter et renouveler les certificats kubeadm            | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|       3 | 🎯  Préparer un nœud pour une mise à niveau planifiée          | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|       4 | 🎯  Installer un pilote CSI fictif par étapes avec Kustomize   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|       5 | 🎯  Valider une ressource personnalisée gérée par un opérateur | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### Services et mise en réseau

|   Index | Nom                                                  | Difficulté   | Pratique                                                                                                                   |
|---------|------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Publier une API avec le routage Gateway API       | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|       2 | 🎯  Réparer l'accès au Service basé sur EndpointSlice | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|       3 | 🎯  Restreindre le trafic sortant avec NetworkPolicy  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|       4 | 🎯  Configurer le transfert conditionnel CoreDNS      | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## À propos de LabEx

[LabEx](https://labex.io) est une plateforme d'apprentissage interactive et pratique dédiée au codage et à la technologie. Elle combine des laboratoires, une assistance IA et des machines virtuelles pour offrir une expérience d'apprentissage pratique sans vidéo. Avec une approche stricte 'Apprendre en Faisant', des environnements en ligne interactifs dans le navigateur avec des vérifications automatisées étape par étape, une organisation structurée du contenu avec le système basé sur l'Arbre de Compétences, et une ressource d'apprentissage croissante de 30 Arbres de Compétences et plus de 6 000 Laboratoires, [LabEx](https://labex.io) offre une éducation pratique complète. La plateforme comprend l'assistant d'apprentissage Labby, construit sur les derniers modèles d'IA, offrant une expérience d'apprentissage conversationnelle.

