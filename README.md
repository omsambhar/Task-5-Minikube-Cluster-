# Task 5: Kubernetes Cluster with Minikube

This repo contains files and screenshots for deploying a Node.js app using Kubernetes locally with Minikube.

## Files
- `deployment.yaml`: Defines the Node.js app deployment.
- `service.yaml`: Exposes the app using a NodePort service.

## Steps Performed
1. Started Minikube using `minikube start`
2. Applied deployment and service YAMLs using `kubectl apply -f`
3. Verified pods and services using `kubectl get pods` and `kubectl get svc`
4. Scaled the deployment to 3 replicas
5. Collected logs using `kubectl describe`

## Screenshots
Included sample screenshots of the commands and their outputs.


