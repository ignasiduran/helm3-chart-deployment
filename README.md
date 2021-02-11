# Helm 3 charts

Helm charts repository

## Helm 3 version

```
# helm3 version --short
v3.4.0+g7090a89
```

## Deploy from local

```
helm3 upgrade <deployment_name> deployment-chart -f <values>.yaml --install --namespace <namespace_name>
```