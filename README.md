# Kubernetes

## Steps to set up Kubernetes
1. Enable kubernetes from docker app settings
2. `kubectl get svc` - gets a cluster IP
3. `kubectl` - provides information and commands available on kubernetes cluster manager 

`kubectl delete deploy <name of file>` - to delete deployed file
`kubectl create -f <name of yml file>` - creates deployment 
`kubectl get deploy` - shows deployments
`kubectl get pods` - shows pods running
`kubectl get svc` - shorthand for get service
`kubectl delete pod <name of pod>` - deletes the pod you have selected 

- With the loadbalancer although a pod was deleted the app was running whilst another pod was being created
