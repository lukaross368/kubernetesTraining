## Kubernetes Demo Project

### Project Overview

In order to start learning about kubernetes I followed a tutorial online to create this basic hello world kubernetes 
application with minikube, MongoDB and Mongo Express.

The Application runs inside Minikube which acts as a Single-Node local Kubernetes Cluster. 
We then have an external service attached to a Pod running a Mongo Express web app which talks to a internal Service 
attached to a pod running a MongoDB Container.

### Setup

- setup minikube and kubectl
- start minikube with `minikube start`
- run components with `kubectl apply -f <file_name>`
- connect the minikube cluster to the mongo-express-service
  - `minikube service mongo-express-service --url`
- view your locally running application

