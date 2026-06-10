# CKA-Schulung Certification Prep Path

## Sprachen

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/de/learn/cka"><img width="128px" src="https://file.labex.io/path/D11aS1XBKGaa.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Pfad-Starten-whitesmoke?style=for-the-badge)](https://labex.io/de/learn/cka)

Bereiten Sie sich mit einem strukturierten, praxisorientierten Lernpfad auf die Prüfung Certified Kubernetes Administrator (CKA) vor. Der Fokus liegt auf Cluster-Administration, Installation und Konfiguration, Workloads und Scheduling, Services und Netzwerk, Speicher und Troubleshooting in Kubernetes, leistungsbasierten CKA-Aufgaben und realistischen Szenarien. CKA-Kurse, Labs und Übungsprüfungen werden schrittweise ergänzt.

**Kurse**: 3 · **Labs**: 88

## Kurse

### 1. [CKA-Vorbereitung](https://labex.io/de/courses/cka-prep)

Ein einsteigerfreundlicher CKA-Vorbereitungskurs mit 48 geführten Kubernetes-Administrations-Experimenten, die von der Cluster-Orientierung bis hin zu Workloads, Architektur, Netzwerk, Speicher, Fehlerbehebung und Wartung reichen.

[Kurs Starten](https://labex.io/de/courses/cka-prep) · Labs: 48

#### Cluster-Orientierung und Grundlagen der Administration

|   Index | Name                                                 | Schwierigkeit   | Übung                                                                                                           |
|---------|------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Untersuchung von kubeconfig und Kontexten         | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-kubeconfig-and-contexts-663781?course=cka-prep)                |
|       2 | 🧩  Nodes und Cluster-Version erkunden                | Anfänger        | [Labor Starten](https://labex.io/de/labs/explore-nodes-and-cluster-version-663773?course=cka-prep)              |
|       3 | 🧩  API-Ressourcen und Namespaces untersuchen         | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-api-resources-and-namespaces-663776?course=cka-prep)           |
|       4 | 🧩  Events und Objekt-Conditions lesen                | Anfänger        | [Labor Starten](https://labex.io/de/labs/read-events-and-object-conditions-663791?course=cka-prep)              |
|       5 | 🧩  Labels, Selektoren und Feldselektoren verwenden   | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-labels-selectors-and-field-selectors-663806?course=cka-prep)       |
|       6 | 🧩  Namespaces für administrative Workflows verwalten | Anfänger        | [Labor Starten](https://labex.io/de/labs/manage-namespaces-for-administrative-workflows-663784?course=cka-prep) |
|       7 | 🧩  Verwendung von Dry Run und Explain für Manifeste  | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-dry-run-and-explain-for-manifests-663805?course=cka-prep)          |

#### Workloads und Scheduling

|   Index | Name                                                         | Schwierigkeit   | Übung                                                                                                            |
|---------|--------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Untersuchung des Verhaltens von Deployment und ReplicaSet | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-deployment-and-replicaset-behavior-663780?course=cka-prep)      |
|       2 | 🧩  Durchführung eines kontrollierten Deployment-Rollouts     | Anfänger        | [Labor Starten](https://labex.io/de/labs/perform-a-controlled-deployment-rollout-663786?course=cka-prep)         |
|       3 | 🧩  Rollback eines fehlerhaften Rollouts                      | Anfänger        | [Labor Starten](https://labex.io/de/labs/roll-back-a-broken-rollout-663798?course=cka-prep)                      |
|       4 | 🧩  Workloads mit ConfigMaps und Secrets konfigurieren        | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-workloads-with-configmaps-and-secrets-663763?course=cka-prep) |
|       5 | 🧩  Requests, Limits und Ressourcen-Nachweise festlegen       | Anfänger        | [Labor Starten](https://labex.io/de/labs/set-requests-limits-and-resource-evidence-663802?course=cka-prep)       |
|       6 | 🧩  Pods mit Node Selectors planen                            | Anfänger        | [Labor Starten](https://labex.io/de/labs/schedule-pods-with-node-selectors-663801?course=cka-prep)               |
|       7 | 🧩  Workloads mit Affinity-Regeln platzieren                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/place-workloads-with-affinity-rules-663787?course=cka-prep)             |
|       8 | 🧩  Taints und Tolerations verwenden                          | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-taints-and-tolerations-663807?course=cka-prep)                      |
|       9 | 🧩  Verfügbarkeit mit PodDisruptionBudgets schützen           | Anfänger        | [Labor Starten](https://labex.io/de/labs/protect-availability-with-poddisruptionbudgets-663789?course=cka-prep)  |

#### Cluster-Architektur, Installation und Konfiguration

|   Index | Name                                                    | Schwierigkeit   | Übung                                                                                                       |
|---------|---------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Untersuchung der Control-Plane-Komponenten           | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-control-plane-components-663779?course=cka-prep)           |
|       2 | 🧩  Erkundung der kubeadm-Konfigurationsartefakte        | Anfänger        | [Labor Starten](https://labex.io/de/labs/explore-kubeadm-configuration-artifacts-663772?course=cka-prep)    |
|       3 | 🧩  Zertifikate und Cluster-Vertrauen untersuchen        | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-certificates-and-cluster-trust-663777?course=cka-prep)     |
|       4 | 🧩  RBAC für Namespace-Operatoren gewähren               | Anfänger        | [Labor Starten](https://labex.io/de/labs/grant-namespace-operator-rbac-663775?course=cka-prep)              |
|       5 | 🧩  Delegierung von schreibgeschützten Cluster-Diagnosen | Anfänger        | [Labor Starten](https://labex.io/de/labs/delegate-read-only-cluster-diagnostics-663768?course=cka-prep)     |
|       6 | 🧩  Bereitstellung eines Addons mit Helm                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/deploy-an-addon-with-helm-663769?course=cka-prep)                  |
|       7 | 🧩  Anpassen von Cluster-Ressourcen mit Kustomize        | Anfänger        | [Labor Starten](https://labex.io/de/labs/customize-cluster-resources-with-kustomize-663765?course=cka-prep) |
|       8 | 🧩  Definieren und Verwenden einer Custom Resource       | Anfänger        | [Labor Starten](https://labex.io/de/labs/define-and-use-a-custom-resource-663767?course=cka-prep)           |
|       9 | 🧩  Untersuchung der CNI-, CSI- und CRI-Schnittstellen   | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-cni-csi-and-cri-interfaces-663778?course=cka-prep)         |

#### Services und Networking

|   Index | Name                                              | Schwierigkeit   | Übung                                                                                                     |
|---------|---------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Anwendungen mit Services bereitstellen         | Anfänger        | [Labor Starten](https://labex.io/de/labs/expose-applications-with-services-663774?course=cka-prep)        |
|       2 | 🧩  Zugriff auf EndpointSlice-Service reparieren   | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-endpointslice-service-access-663793?course=cka-prep)      |
|       3 | 🧩  Fehlerbehebung bei der Service-DNS-Auflösung   | Anfänger        | [Labor Starten](https://labex.io/de/labs/troubleshoot-service-dns-resolution-663804?course=cka-prep)      |
|       4 | 🧩  CoreDNS Conditional Forwarding konfigurieren   | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-coredns-conditional-forwarding-663762?course=cka-prep) |
|       5 | 🧩  Egress-Beschränkung mit NetworkPolicy          | Anfänger        | [Labor Starten](https://labex.io/de/labs/restrict-egress-with-networkpolicy-663797?course=cka-prep)       |
|       6 | 🧩  NetworkPolicy-Zugriff reparieren               | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-networkpolicy-access-663794?course=cka-prep)              |
|       7 | 🧩  HTTP-Traffic mit Ingress routen                | Anfänger        | [Labor Starten](https://labex.io/de/labs/route-http-traffic-with-ingress-663799?course=cka-prep)          |
|       8 | 🧩  Veröffentlichung einer API mit Gateway-Routing | Anfänger        | [Labor Starten](https://labex.io/de/labs/publish-an-api-with-gateway-routing-663790?course=cka-prep)      |

#### Storage

|   Index | Name                                                        | Schwierigkeit   | Übung                                                                                                            |
|---------|-------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  StorageClasses und dynamische Bereitstellung untersuchen | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-storageclasses-and-dynamic-provisioning-663782?course=cka-prep) |
|       2 | 🧩  Erstellen eines PVC für Anwendungsdaten                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/create-a-pvc-for-application-data-663764?course=cka-prep)               |
|       3 | 🧩  Ein statisches PersistentVolume binden                   | Anfänger        | [Labor Starten](https://labex.io/de/labs/bind-a-static-persistentvolume-663760?course=cka-prep)                  |
|       4 | 🧩  Zugriffsmodi und Volume-Modi konfigurieren               | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-access-modes-and-volume-modes-663761?course=cka-prep)         |
|       5 | 🧩  Daten mit Reclaim Policies bewahren                      | Anfänger        | [Labor Starten](https://labex.io/de/labs/preserve-data-with-reclaim-policies-663788?course=cka-prep)             |
|       6 | 🧩  Fehlerbehebung bei PVC-Bindung und Mounts                | Anfänger        | [Labor Starten](https://labex.io/de/labs/troubleshoot-pvc-binding-and-mounts-663803?course=cka-prep)             |

#### Fehlerbehebung und Wartung

|   Index | Name                                                             | Schwierigkeit   | Übung                                                                                                   |
|---------|------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Cluster-Ressourcenengpässe diagnostizieren                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-cluster-resource-pressure-663770?course=cka-prep)     |
|       2 | 🧩  Pods mit Metrics und Top überwachen                           | Anfänger        | [Labor Starten](https://labex.io/de/labs/monitor-pods-with-metrics-and-top-663785?course=cka-prep)      |
|       3 | 🧩  Container-Ausgabeströme verwalten                             | Anfänger        | [Labor Starten](https://labex.io/de/labs/manage-container-output-streams-663783?course=cka-prep)        |
|       4 | 🧩  Fehler bei Image-Pull-Vorgängen beheben                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/debug-image-pull-failures-663766?course=cka-prep)              |
|       5 | 🧩  Fehlerhafte Init-Container diagnostizieren                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-failed-init-containers-663771?course=cka-prep)        |
|       6 | 🧩  Wiederherstellung eines abstürzenden statischen Pod-Manifests | Anfänger        | [Labor Starten](https://labex.io/de/labs/restore-a-crashing-static-pod-manifest-663795?course=cka-prep) |
|       7 | 🧩  Einen Node sicher leeren und wiederherstellen                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/safely-drain-and-restore-a-node-663800?course=cka-prep)        |
|       8 | 🧩  Wiederherstellung von metrikbasierten Skalierungssignalen     | Anfänger        | [Labor Starten](https://labex.io/de/labs/recover-metrics-based-scaling-signals-663792?course=cka-prep)  |
|       9 | 🧩  Wiederherstellung von unterbrochenem Service-Traffic          | Anfänger        | [Labor Starten](https://labex.io/de/labs/restore-broken-service-traffic-663796?course=cka-prep)         |

### 2. [CKA-Übungsprüfung 01](https://labex.io/de/courses/cka-practice-exam-01)

Eine praxisorientierte CKA-Übungsprüfung mit 20 unabhängigen Kubernetes-Administrations-Herausforderungen, die die Bereiche Speicher, Fehlerbehebung, Workloads und Scheduling, Cluster-Architektur sowie Services und Networking abdecken.

[Kurs Starten](https://labex.io/de/courses/cka-practice-exam-01) · Labs: 20

#### Speicher

|   Index | Name                                                         | Schwierigkeit   | Übung                                                                                                                                |
|---------|--------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Anwendungsdaten mit einem PersistentVolumeClaim einbinden | Anfänger        | [Challenge Starten](https://labex.io/de/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=cka-practice-exam-01) |
|       2 | 🎯  Ein statisches PersistentVolume für Archivdaten einbinden | Anfänger        | [Challenge Starten](https://labex.io/de/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=cka-practice-exam-01)     |

#### Fehlerbehebung

|   Index | Name                                                                  | Schwierigkeit   | Übung                                                                                                                           |
|---------|-----------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Wiederherstellung des Datenverkehrs für einen fehlerhaften Service | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restore-traffic-to-a-broken-service-663022?course=cka-practice-exam-01)            |
|       2 | 🎯  Wiederherstellung eines fehlerhaften Deployment-Rollouts           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/recover-a-failing-deployment-rollout-663020?course=cka-practice-exam-01)           |
|       3 | 🎯  Planen von Pending Pods auf einem mit Taints versehenen Node       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/schedule-pending-pods-on-a-tainted-node-663026?course=cka-practice-exam-01)        |
|       4 | 🎯  Netzwerkzugriff zwischen Namespaces über NetworkPolicy reparieren  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/repair-networkpolicy-access-between-namespaces-663021?course=cka-practice-exam-01) |
|       5 | 🎯  CoreDNS Namensauflösung wiederherstellen                           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restore-coredns-name-resolution-663023?course=cka-practice-exam-01)                |
|       6 | 🎯  Diagnose von Cluster-Ressourcenengpässen                           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/diagnose-cluster-resource-pressure-663013?course=cka-practice-exam-01)             |

#### Workloads und Scheduling

|   Index | Name                                                                | Schwierigkeit   | Übung                                                                                                                                       |
|---------|---------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Durchführung eines kontrollierten Deployment-Rollouts            | Anfänger        | [Challenge Starten](https://labex.io/de/labs/perform-a-controlled-deployment-rollout-663018?course=cka-practice-exam-01)                    |
|       2 | 🎯  Anwendungseinstellungen mit ConfigMaps und Secrets konfigurieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/configure-application-settings-with-configmaps-and-secrets-663008?course=cka-practice-exam-01) |
|       3 | 🎯  Workloads mit Affinität und Ressourcenkontrollen platzieren      | Anfänger        | [Challenge Starten](https://labex.io/de/labs/place-workloads-with-affinity-and-resource-controls-663019?course=cka-practice-exam-01)        |

#### Cluster-Architektur, Installation und Konfiguration

|   Index | Name                                                           | Schwierigkeit   | Übung                                                                                                                            |
|---------|----------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Namespace-Operator-Berechtigungen mit RBAC erteilen         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/grant-namespace-operator-permissions-with-rbac-663016?course=cka-practice-exam-01)  |
|       2 | 🎯  Erstellen eines etcd-Snapshot-Backups                       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/create-an-etcd-snapshot-backup-663010?course=cka-practice-exam-01)                  |
|       3 | 🎯  Einen Node sicher leeren und wiederherstellen               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/safely-drain-and-restore-a-node-663025?course=cka-practice-exam-01)                 |
|       4 | 🎯  Bereitstellung eines Cluster-Add-ons mit Helm und Kustomize | Anfänger        | [Challenge Starten](https://labex.io/de/labs/deploy-a-cluster-add-on-with-helm-and-kustomize-663012?course=cka-practice-exam-01) |
|       5 | 🎯  Definieren und Verwenden einer Custom Resource              | Anfänger        | [Challenge Starten](https://labex.io/de/labs/define-and-use-a-custom-resource-663011?course=cka-practice-exam-01)                |

#### Services und Netzwerk

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                                           |
|---------|-----------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Anwendung mit Services bereitstellen             | Anfänger        | [Challenge Starten](https://labex.io/de/labs/expose-an-application-with-services-663015?course=cka-practice-exam-01)            |
|       2 | 🎯  HTTP-Traffic mit Ingress routen                  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/route-http-traffic-with-ingress-663024?course=cka-practice-exam-01)                |
|       3 | 🎯  Namespace-Isolierung mit NetworkPolicy erzwingen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/enforce-namespace-isolation-with-networkpolicy-663014?course=cka-practice-exam-01) |
|       4 | 🎯  Konfiguration eines internen DNS-Alias           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/configure-an-internal-dns-alias-663009?course=cka-practice-exam-01)                |

### 3. [CKA-Übungsprüfung 02](https://labex.io/de/courses/cka-practice-exam-02)

Eine zweite, unabhängige CKA-Übungsprüfung mit 20 Kubernetes-Administrations-Herausforderungen, die die offiziellen CKA-Themenbereiche anhand verschiedener operativer Szenarien abdeckt.

[Kurs Starten](https://labex.io/de/courses/cka-practice-exam-02) · Labs: 20

#### Speicher

|   Index | Name                                                                       | Schwierigkeit   | Übung                                                                                                                           |
|---------|----------------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Anwendungsprotokolle mit einer StorageClass bereitstellen               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/provision-application-logs-with-a-storageclass-663037?course=cka-practice-exam-02) |
|       2 | 🎯  Daten aus einem beibehaltenen Volume (Retained Volume) wiederherstellen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/preserve-released-data-from-a-retained-volume-663035?course=cka-practice-exam-02)  |

#### Fehlerbehebung

|   Index | Name                                                              | Schwierigkeit   | Übung                                                                                                                            |
|---------|-------------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Ein abstürzendes statisches Pod-Manifest wiederherstellen      | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restore-a-crashing-static-pod-manifest-663043?course=cka-practice-exam-02)          |
|       2 | 🎯  Reparatur eines fehlerhaften Image-Pull-Pfads im Kubelet       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/repair-a-broken-kubelet-image-pull-path-663040?course=cka-practice-exam-02)         |
|       3 | 🎯  Wiederherstellung von metrikbasierten Skalierungssignalen      | Anfänger        | [Challenge Starten](https://labex.io/de/labs/recover-metrics-based-scaling-signals-663039?course=cka-practice-exam-02)           |
|       4 | 🎯  Fehlgeschlagenen Init-Container-Start diagnostizieren          | Anfänger        | [Challenge Starten](https://labex.io/de/labs/diagnose-failed-init-container-startup-663031?course=cka-practice-exam-02)          |
|       5 | 🎯  Wiederherstellung der Node-Planung nach Wartungsabweichungen   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restore-node-scheduling-after-maintenance-drift-663044?course=cka-practice-exam-02) |
|       6 | 🎯  Wiederherstellung der Service-Discovery für Headless-Workloads | Anfänger        | [Challenge Starten](https://labex.io/de/labs/repair-service-discovery-for-headless-workloads-663042?course=cka-practice-exam-02) |

#### Workloads und Scheduling

|   Index | Name                                                          | Schwierigkeit   | Übung                                                                                                                               |
|---------|---------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Horizontal Pod Autoscaling konfigurieren                   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/configure-horizontal-pod-autoscaling-663028?course=cka-practice-exam-02)               |
|       2 | 🎯  Verfügbarkeit mit einem PodDisruptionBudget schützen       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/protect-availability-with-a-poddisruptionbudget-663036?course=cka-practice-exam-02)    |
|       3 | 🎯  Pods mit Admission- und Runtime-Einstellungen einschränken | Anfänger        | [Challenge Starten](https://labex.io/de/labs/constrain-pods-with-admission-and-runtime-settings-663029?course=cka-practice-exam-02) |

#### Cluster-Architektur, Installation und Konfiguration

|   Index | Name                                                        | Schwierigkeit   | Übung                                                                                                                            |
|---------|-------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Delegierung von schreibgeschützten Cluster-Diagnosen     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/delegate-read-only-cluster-diagnostics-663030?course=cka-practice-exam-02)          |
|       2 | 🎯  kubeadm-Zertifikate prüfen und erneuern                  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/inspect-and-renew-kubeadm-certificates-663032?course=cka-practice-exam-02)          |
|       3 | 🎯  Vorbereitung eines Nodes für ein geplantes Upgrade       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/prepare-a-node-for-planned-upgrade-663034?course=cka-practice-exam-02)              |
|       4 | 🎯  Installieren eines Staged CSI Mock Drivers mit Kustomize | Anfänger        | [Challenge Starten](https://labex.io/de/labs/install-a-staged-csi-mock-driver-with-kustomize-663033?course=cka-practice-exam-02) |
|       5 | 🎯  Validierung einer Operator-verwalteten Custom Resource   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/validate-an-operator-managed-custom-resource-663046?course=cka-practice-exam-02)    |

#### Services und Netzwerk

|   Index | Name                                                              | Schwierigkeit   | Übung                                                                                                                      |
|---------|-------------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Veröffentlichung einer API mit Gateway API Routing             | Anfänger        | [Challenge Starten](https://labex.io/de/labs/publish-an-api-with-gateway-api-routing-663038?course=cka-practice-exam-02)   |
|       2 | 🎯  Wiederherstellung des EndpointSlice-basierten Service-Zugriffs | Anfänger        | [Challenge Starten](https://labex.io/de/labs/repair-endpointslice-based-service-access-663041?course=cka-practice-exam-02) |
|       3 | 🎯  Egress-Beschränkung mit NetworkPolicy                          | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restrict-egress-with-networkpolicy-663045?course=cka-practice-exam-02)        |
|       4 | 🎯  CoreDNS bedingte Weiterleitung konfigurieren                   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/configure-coredns-conditional-forwarding-663027?course=cka-practice-exam-02)  |

## Über LabEx

[LabEx](https://labex.io) ist eine interaktive, praktische Lernplattform für Programmierung und Technologie. Sie kombiniert Labore, KI-Unterstützung und virtuelle Maschinen für eine videofreie, praktische Lernerfahrung. Mit einem strikten 'Learning by Doing'-Ansatz, interaktiven Online-Umgebungen im Browser mit automatisierten Schritt-für-Schritt-Überprüfungen, strukturierter Inhaltsorganisation mit dem Skill-Tree-basierten System, und einer wachsenden Lernressource von 30 Skill Trees und über 6.000 Laboren, [LabEx](https://labex.io) bietet umfassende praktische Bildung. Die Plattform umfasst den Lernassistenten Labby, aufgebaut auf den neuesten KI-Modellen, der eine konversationelle Lernerfahrung bietet.

