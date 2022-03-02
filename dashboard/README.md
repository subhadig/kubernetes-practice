Create a Kubernetes Ingress for the kuberenetes-dashboard service.

# Steps

```
minikube addons enable ingress

kubectl apply -f dashboard-ingress.yaml
```
