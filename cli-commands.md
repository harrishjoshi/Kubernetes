### Create minikube cluster
```
minikube start
```
```
minikube status
```
```
kubectl version
```
```
kubectl get nodes
```
### Delete cluster and restart in debug mode
```
minikube delete
```
```
minikube start --v=7 --alsologtostderr 
```
### kubectl commands
```
kubectl get nodes
```
```
kubectl get pod
```
```
kubectl get services
```
```
kubectl create deployment nginx-deployment --image=nginx
```
```
kubectl get deployment
```
```
kubectl get replicaset
```
```
kubectl edit deployment nginx-deployment
```
```
kubectl apply -f nginx-deployment.yaml
```
```
kubectl delete -f nginx-deployment.yaml
```
# Debugging
```
kubectl logs {pod-name} -f
```
```
kubectl exec -it {pod-name} -- bin/bash
```
