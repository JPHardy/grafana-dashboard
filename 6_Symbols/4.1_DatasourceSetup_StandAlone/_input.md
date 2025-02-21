```markdown
- 🚜 minikube delete
- 🚀 minikube start --memory=4096 --cpus=2 
- 📦 kubectl create namespace grafana-monitoring 
---------------------------optional----------------------------------------
- 📥 helm repo add bitnami https://charts.bitnami.com/bitnami  
- 🔄 helm repo update 
-------------------------------------------------------------------------
- 📂 cd /workspaces/grafana-dashboard/6_Symbols/4.1_DatasourceSetup_StandAlone
- 🧹 clear

- 📄 kubectl apply -f myconfig.yaml -n grafana-monitoring 

- 📄 kubectl apply -f configmap_dashboard_1.yaml -n grafana-monitoring
- 📄 kubectl apply -f configmap_dashboard_2.yaml -n grafana-monitoring

- 📄 kubectl apply -f grafana-datasource-provision.yaml -n grafana-monitoring
<!-- - 📄 kubectl apply -f grafana-datasource-provision1.yaml -n grafana-monitoring -->
<!-- - 📄 kubectl apply -f grafana-datasource-provision2.yaml -n grafana-monitoring -->

- 🔐 kubectl create secret generic grafana-datasource-secret --from-file=datasource-secret.yaml -n grafana-monitoring
- 🛠️ helm install grafana bitnami/grafana --namespace grafana-monitoring -f grafana-dashboard-deployment.yaml --dry-run --debug

- 🛠️ helm install grafana bitnami/grafana --namespace grafana-monitoring -f grafana-dashboard-deployment.yaml
- 🔌 kubectl port-forward -n grafana-monitoring svc/grafana 3000:3000  


oneliner > 
```bash
minikube start --memory=4096 --cpus=2 ;kubectl create namespace grafana-monitoring ; kubectl apply -f myconfig.yaml -n grafana-monitoring ;kubectl apply -f configmap_dashboard_1.yaml -n grafana-monitoring;kubectl apply -f configmap_dashboard_2.yaml -n grafana-monitoring;kubectl create secret generic grafana-datasource-secret --from-file=datasource-secret.yaml -n grafana-monitoring;helm install grafana bitnami/grafana --namespace grafana-monitoring -f grafana-dashboard-deployment.yaml;kubectl port-forward -n grafana-monitoring svc/grafana 3000:3000
```

---------------------------optional----------------------------------------
- 🔍 kubectl get secret grafana-datasource-secret -n grafana-monitoring
- 📂 provisioning/datasources >>> provision datasource is missing
- 📂 /workspaces/grafana-dashboard/6_Symbols/6_DashboardGrafanaIni/grafana-datasource-provision.yaml

- 🔄 helm upgrade grafana bitnami/grafana --namespace grafana-monitoring -f grafana-dashboard-deployment.yaml 
- 🚀 minikube start --memory=4096 --cpus=2 
- 📦 kubectl get pods -n grafana-monitoring
- 🔄 kubectl rollout restart deployment grafana -n grafana-monitoring 
- 🗑️ kubectl delete pod grafana-64fcf79d7c-t8xhd  -n grafana-monitoring

xxxxxxxxxxxxxxxxxxxxxxxxxxxdebuggingxxxxxxxxxxxxxxxxxxxxxxxxxxxx
- 📦 kubectl get pods -n grafana-monitoring
- 🖥️ kubectl exec -it grafana-66dc5cd4f-l2r8c -n grafana-monitoring -- /bin/bash
- ls /opt/bitnami/grafana/conf/provisioning/datasources
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
- 📜 kubectl logs grafana-5f8bc665d9-rthn9 -n grafana-monitoring
- 📜 kubectl logs grafana-64fcf79d7c-t8xhd  -n grafana-monitoring > mylog.md
- 📝 kubectl describe pod grafana-6fbbccf49f-zw9gl  -n grafana-monitoring
-------------------------------------------------------------------------
```
