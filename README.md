# vpa-newbie

https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler

```bash
minikube start --kubernetes-version=v1.29.0

kustomize build . | kubectl apply -f -

helmfile sync
helmfile test

minikube service -n newbie goldilocks-dashboard --url
```
