# k8s-homework-1

* Step 1
Start an one node cluster at localhost
```shell
minikube start
```

* Step 2
Create Pod `curl-pod`
```shell
kubectl apply -f get_pod_with_serviceaccount.yaml
```

* Step 3
View the `curl-pod` output
```shell
kubectl logs curl-pod
```

* Step 4
Delete `curl-pod`
```shell
kubectl delete pod curl-pod --force
```
