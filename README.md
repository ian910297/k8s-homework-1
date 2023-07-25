# k8s-homework-1

## Cmd
```shell
# launch minikube
minikube start
minikube dashboard

# create pod
kubectl apply -f <yaml>  

# get into pod
kubectl exec -it curl-pod -n default -- sh

# get pod info
kubectl get pods

# delete pod
kubectl delete pod <pod name> --force  

# Note
# No restart flow in k8s
# delete, then apply again

# show the stdout of the pod
kubectl logs pod <pod name>  

# show the local namespace info
kubectl cluster-info
```

## TODO
1. get the API token  
2. put it all into yaml  
