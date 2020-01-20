# Ingress Traefik

## Instalacja Ingress

```bash
helm install stable/traefik --name traefik --set dashboard.enabled=true,rbac.enabled=true  --namespace kube-system
```

## Test

```bash
kubectl get svc traefik --namespace kube-system -w
```

## Midleware

```bash
kubectl apply -f https://raw.githubusercontent.com/vranystepan/traefik2-dok8s-example-01/master/kubernetes/traefik/traefik-prereqs.yaml
```