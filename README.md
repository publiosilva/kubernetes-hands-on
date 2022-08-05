# Kubernetes Hands On

## Comands

### Create pod

```bash
kubectl run POD_NAME --image=POD_IMAGE_NAME
```

### List pods

```bash
kubectl get pods
```

Or

```bash
kubectl get pods --watch
```

Or

```bash
kubectl get pods -o wide
```

### Get pod details

```bash
kubectl describe pod POD_NAME
```

### Update pod

```bash
kubectl edit pod POD_NAME
```

### Delete pod

```bash
kubectl delete pod POD_NAME
```

To delete all:

```bash
kubectl delete pod --all
```

### Create resources declaratively

```bash
kubectl apply -f RESOURCES_DEFINITION_FILE
```

### Delete declaratively created resources

```bash
kubectl delete -f RESOURCES_DEFINITION_FILE
```

### Run a command in a pod

```bash
kubectl exec POD_NAME -- COMMAND
```

Example:

```bash
kubectl exec -it POD_NAME -- bash
```

### List services

```bash
kubectl get services
```

Or

```bash
kubectl get svc
```

### Delete service

```bash
kubectl delete scv SERVICE_NAME
```

To delete all:

```bash
kubectl delete scv --all
```

### List nodes

```bash
kubectl get nodes
```

Or

```bash
kubectl get nodes -o wide
```

### List config maps

```bash
kubectl get configmap
```

### List config map details

```bash
kubectl describe configmap CONFIGMAP_NAME
```

### Delete configmap

```bash
kubectl delete configmap CONFIGMAP_NAME
```

To delete all:

```bash
kubectl delete configmap --all
```
