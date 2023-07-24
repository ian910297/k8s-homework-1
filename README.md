# k8s-homework-1

## Cmd
```shell
# launch minikube
minikube start
minikube dashboard

# create pod
kubectl apply -f <yaml>  

# delete pod
kubectl delete pod <pod name> --force  

# show the stdout of the pod
kubectl logs pod <pod name>  

# show the local namespace info
kubectl cluster-info
```

## TODO
1. get the API token  
2. put it all into yaml  
