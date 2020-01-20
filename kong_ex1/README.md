
[https://github.com/Kong/kubernetes-ingress-controller/blob/master/docs/guides/getting-started.md]

```bash
helm install kong stable/kong --set ingressController.enabled=true --namespace kube-system
```

```
helm install kong stable/kong --set ingressController.enabled=true --set admin.type=LoadBalancer --set proxy.type=LoadBalancer --namespace kube-system
```

```
helm install kong stable/kong --set ingressController.enabled=true --set admin.type=LoadBalancer --set proxy.type=LoadBalancer --set postgresql.enabled=true --namespace kube-system
```