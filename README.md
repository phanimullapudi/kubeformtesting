### Installing kubeform Operator

```
$ helm repo add appscode https://charts.appscode.com/stable/
$ helm repo update
$ helm search appscode/kubeform
NAME                CHART VERSION  APP VERSION  DESCRIPTION
appscode/kubeform   v0.1.0         v0.1.0       Kubeform by AppsCode - Build Cloud Infrastructure from Kubernetes

$ helm install appscode/kubeform --name kfc --version v0.1.0 --namespace kube-system
```

### Reference Links

https://kubeform.com/docs/v0.1.0/setup/install/
