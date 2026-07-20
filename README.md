# Quopit Helm Chart Repository

Chart repository for [Quopit](https://github.com/quopit/quopit). The packaged
charts and the `index.yaml` live on the `gh-pages` branch and are served at
https://quopit.github.io/quopit-chart.

## Usage

```bash
helm repo add quopit-chart https://quopit.github.io/quopit-chart
helm repo update
helm install quopit quopit-chart/quopit
```

The chart source lives in the main repository at
[deploy/helm/quopit](https://github.com/quopit/quopit/tree/main/deploy/helm/quopit).
New versions are published automatically by the "Publish Helm Chart" workflow
on every tag push.
