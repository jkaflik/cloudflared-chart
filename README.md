# Using the chart

```
helm repo add kylesferrazza https://charts.kylesferrazza.com
helm show values kylesferrazza/cloudflared > values.yaml
# edit values.yaml
helm install kylesferrazza/cloudflared -f values.yaml
```
