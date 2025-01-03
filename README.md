# Minidlna

Usage:

```bash
helm repo add linuxoid69 https://linuxoid69.github.io/helm-charts
helm repo update
helm upgrade --install -n media minidlna -f minidlna-values.yaml linuxoid69/minidlna --version 0.1.0

kubectl -n media rollout restart deployment minidlna
```
