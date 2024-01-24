# Cheatset Kubernetes

This is a cheat sheet for Kubernetes.

## Kubectl Commands

### Get Information about Resources

```
kubectl get pods/services/deployments
```

### Describe Resources

```
kubectl describe pods/services/deployments
```

## Apply Configuration from a File:

```
kubectl apply -f file.yaml
```

### Delete Resources

```
kubectl delete pods/services/deployments
```

## Scaling

### Scale Deployment

```
kubectl scale deployment deployment-name --replicas=10
``
```

## Network and Services

### Expose Deployment

```
kubectl expose deployment deployment_name --type=LoadBalancer --port=80

```

### Port Forwarding

```
kubectl port-forward pod_name 8080:80
```

## Trouble-shooting

### Get Cluster Events

```
kubectl get events
```

### Access Pod Shell

```
kubectl exec -it pod_name -- /bin/bash

```
