# Kubernetes Deployment

## Kubernetes Cluster

The Kubernetes environment was verified after starting Minikube.

![Kubernetes Progress](../screenshots/15-kubernetes-progress.png)

## Application Deployment

NGINX was deployed as the application workload.

![NGINX Browser](../screenshots/16-nginx-browser.png)

## Deployment Approach

The application is managed through Kubernetes resources rather than manually running individual containers.

The basic deployment flow is:

Docker Image
↓
Kubernetes Deployment
↓
Pods
↓
Service
↓
Application Access
