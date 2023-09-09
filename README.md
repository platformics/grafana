# Grafana

The folder `grafana-stack`` represents the namespace used by argocd. This is the same namespace used by loki.

```bash
helm repo add grafana https://grafana.github.io/helm-charts
helm repo update
helm pull grafana/grafana --untar
```
