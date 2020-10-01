# slowtom-chart
Helm 2 Charts for <a href="https://hub.docker.com/r/hqasem/slow-tomcat" target="_blank">Slow Tomcat</a>

### Helm2 Install
```
helm install --debug --dry-run helm-chart/slowtom --name slowtom -f helm-chart/slowtom/environments/initial.yaml
```

### Helm2 Upgrade
```
helm upgrade --debug --dry-run slowtom helm-chart/slowtom -f helm-chart/slowtom/environments/upgrade.yaml
```

### Helm2 Delete
```
helm del slowtom --purge
```
