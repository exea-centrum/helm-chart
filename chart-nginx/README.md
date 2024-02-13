# helm

<li> helm Chart examples and tutorial resoruces </li>
<li> nginx-chart  </li>
<li> ├── Chart.yaml  </li>
<li> ├── charts  </li>
<li> ├── templates  </li>
<li> │   ├── configmap.yaml  </li>
<li> │   ├── deployment.yaml  </li>
<li> │   └── service.yaml  </li>
<li> └── values.yaml  </li>
<li>  </li>

# helm lint .

<li> helm lint /path/to/nginx-chart </li>
<li> helm template . </li>
<li> helm install --dry-run my-release nginx-chart </li>
<li> helm install frontend nginx-chart</li>
<li> helm list </li>
<li> helm install frontend nginx-chart --values env/prod-values.yaml </li>

# $ Helm Upgrade & Rollback
<li> helm upgrade frontend nginx-chart </li>
<li> helm rollback frontend </li>
<li> helm uninstall frontend </li>
<li> helm diff revision nginx-chart 1 2 </li>

