# kong-ingress-controller-springboothello

## Setup Kong

```bash
kubectl apply -f kong.yaml
```

## Check Service of kong

```bash
kubectl get svc -n kong
```

## Deploy springboot application

```bash
kubectl apply -f springboot/deployment.yaml
kubectl apply -f springboot/service.yaml
kubectl apply -f springboot/ingress.yaml
```

## Check ingress url in UI
