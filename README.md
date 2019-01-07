# Theo

## Deploying from local checkout

```
git clone https://github.com/theoapp/theo-charts.git
cd theo-charts/theo
helm dep update
helm upgrade --install --namespace theo theo .
```

## Undeploying

```
helm delete --purge theo
```

