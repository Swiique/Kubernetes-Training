# Kubernetes-Training


### Launch
```bash
kubectl apply -f pod.yml
```

### Get informations
```bash
kubectl get pod
```
Or
```bash
kubectl describe pod simple-webapp-color
```

### Port-forward
```bash
kubectl port-forward simple-webapp-color 8080:8080 --address 0.0.0.0
```
