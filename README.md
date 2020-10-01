# slowtom-chart
Helm 2 Charts for <a href="https://hub.docker.com/r/hqasem/slow-tomcat" target="_blank">Slow Tomcat</a>

### Helm2 Install
```
helm install https://github.com/h-q/slowtom/raw/master/docs/slowtom.tgz --name slowtom \
     -f https://raw.githubusercontent.com/h-q/slowtom/master/docs/slowtom/environments/initial.yaml
```

### Helm2 Upgrade
```
helm upgrade --debug --dry-run slowtom https://github.com/h-q/slowtom/raw/master/docs/slowtom.tgz \
     -f https://raw.githubusercontent.com/h-q/slowtom/master/docs/slowtom/environments/upgrade.yaml
```

### Helm2 Delete
```
helm del slowtom --purge
```
