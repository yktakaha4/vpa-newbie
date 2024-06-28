# vpa-newbie

https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler

```bash
minikube start --kubernetes-version=v1.29.0

helmfile sync
helmfile test

kubectl apply -f examples/hamster.yaml
```
