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

![image](https://user-images.githubusercontent.com/58024415/234222428-0417d76c-2fa3-4429-b1f0-51c5aef587f2.png)
