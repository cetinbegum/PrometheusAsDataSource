# Mevcut Pod Listesi
@cetinbegum ➜ /workspaces/PrometheusAsDataSource (main) $ kubectl get pods
NAME                                                 READY   STATUS    RESTARTS      AGE
grafana-54d9df94c8-64jqd                             1/1     Running   2 (20m ago)   6d21h
prometheus-alertmanager-0                            1/1     Running   2 (20m ago)   6d21h
prometheus-kube-state-metrics-75b5bb4bf8-nb777       1/1     Running   3 (19m ago)   6d21h
prometheus-prometheus-node-exporter-ssbkk            1/1     Running   2 (20m ago)   6d21h
prometheus-prometheus-pushgateway-84557d6c79-mg9bm   1/1     Running   2 (20m ago)   6d21h
prometheus-server-644d686bc6-tqk2x                   2/2     Running   4 (20m ago)   6d21h

# Namespace'lerde Bulunan Pod Listesi
@cetinbegum ➜ /workspaces/PrometheusAsDataSource (main) $ kubectl get pods -A
NAMESPACE     NAME                                                 READY   STATUS    RESTARTS      AGE
default       grafana-54d9df94c8-64jqd                             1/1     Running   2 (25m ago)   6d21h
default       prometheus-alertmanager-0                            1/1     Running   2 (25m ago)   6d21h
default       prometheus-kube-state-metrics-75b5bb4bf8-nb777       1/1     Running   3 (24m ago)   6d21h
default       prometheus-prometheus-node-exporter-ssbkk            1/1     Running   2 (25m ago)   6d21h
default       prometheus-prometheus-pushgateway-84557d6c79-mg9bm   1/1     Running   2 (25m ago)   6d21h
default       prometheus-server-644d686bc6-tqk2x                   2/2     Running   4 (25m ago)   6d21h
kube-system   coredns-6f6b679f8f-b8p5c                             1/1     Running   2 (25m ago)   6d22h
kube-system   etcd-minikube                                        1/1     Running   2 (25m ago)   6d22h
kube-system   kube-apiserver-minikube                              1/1     Running   2 (25m ago)   6d22h
kube-system   kube-controller-manager-minikube                     1/1     Running   2 (25m ago)   6d22h
kube-system   kube-proxy-s7kbr                                     1/1     Running   2 (25m ago)   6d22h
kube-system   kube-scheduler-minikube                              1/1     Running   2 (25m ago)   6d22h
kube-system   storage-provisioner                                  1/1     Running   4 (24m ago)   6d22h