# helm
helm Chart examples and tutorial resoruces
nginx-chart
├── Chart.yaml
├── charts
├── templates
│   ├── configmap.yaml
│   ├── deployment.yaml
│   └── service.yaml
└── values.yaml

helm lint .

helm lint /path/to/nginx-chart


helm template .


helm install --dry-run my-release nginx-chart

helm install frontend nginx-chart

helm list

kubectl get deployment
kubectl get services
kubectl get configmap
kubectl get pods


helm install frontend nginx-chart --values env/prod-values.yaml

<!--Helm Upgrade & Rollback
helm upgrade frontend nginx-chart
helm rollback frontend
helm uninstall frontend
helm diff revision nginx-chart 1 2 -->
