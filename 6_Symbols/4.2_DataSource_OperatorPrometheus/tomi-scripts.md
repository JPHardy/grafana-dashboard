# Tomi implementation Gpt Generated
- minikube delete
- minikube start
- helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
- helm repo update
- kubectl create namespace grafana-monitoring 

- helm repo add grafana https://grafana.github.io/helm-charts
- helm repo update
- helm install grafana-operator grafana/grafana-operator -n grafana-monitoring 
# prometheus stak depends on the grafana-operator CRD
- helm install prometheus-operator prometheus-community/kube-prometheus-stack -n grafana-monitoring
# in the back ground it installs the grafana service
# GrafanaOperator should be used to deploy datasource > this is controlled by the operator based
- kubectl get pods -n grafana-monitoring
- kubectl get all -n grafana-monitoring


- kubectl apply -f /workspaces/grafana-dashboard/6_Symbols/4_DatasourceSetup/tomi-datasource.yaml -n grafana-grafanamonitoring

