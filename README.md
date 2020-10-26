# Kubernetes

## TL;DR

## Intro

## `kubectl`

### Imperative

#### Create objects

```shell
kubectl run --image=nginx nginx
```

```shell
kubectl create deployments.apps --image=nginx nginx
```

```shell
kubectl expose deployments.apps nginx
```

```shell
kubectl create -f manifest.yaml
```

#### Update objects

```shell
kubectl edit deployments.apps nginx
```

```shell
kubectl set image deployments.apps nginx nginx=nginx:1.19
```

```shell
kubectl replace -f manifest.yaml
```

#### Delete objects

```shell
kubectl delete -f manifest.yaml
```

### Declarative

```shell
kubectl apply -f manifest.yaml
```

## Architecture

## Networking

## Controllers

## Namespaces

## DNS

## Ingress

## Persistance
