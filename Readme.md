Kubernetes tutorial


## checking number of pods in a system

`
kubectl get pods `

## Describing a pod


`
kubectl describe pod pod-name
`
## Editing a pod

`
kubectl edit pod pod-name -o yaml
`

## Deleting a pod

`
kubectl delete pod pod-name
`

## Applying changes for a deployment

`
kubectl apply -f definition.yml
`

## Creating a pod using the imperative way

`
kubectl run nginx --image=nginx --restart=Neve
`

## Running the command with argument
`kubectl run webapp-green --image=kodekloud/webapp-color -- --color green 
`

## Create config map the imperative way 

` 
kubectl create configmap app-config --from-literal=VALUE_NAME=value
kubectl create configmap app-config --from-file=app_config.properties 
`