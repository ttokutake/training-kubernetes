# Docs

- https://kubernetes.io/docs/tutorials/stateless-application/hello-minikube/

# How to create cluster

1. `$ docker build -t hello-node:v1 hellonode`
2. `$ kubectl run hello-node --image=hello-node:v1 --port=8080`
3. `$ kubectl get deployments`
4. `$ kubectl get pods`
5. `$ kubectl get events`
6. `$ kubectl config view`
7. `$ kubectl expose deployment hello-node --type=LoadBalancer`
8. `$ kubectl get services`
9. `$ curl localhost:8080`
10. `$ kubectl logs <POD-NAME>`
