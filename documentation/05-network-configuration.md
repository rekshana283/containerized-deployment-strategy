# Network Configuration

## Kubernetes Service

A Kubernetes Service provides stable network access to the application pods.

![Kubernetes Service Details](../screenshots/19-kubernetes-service-details.png)

## Ingress

Ingress provides an application-level entry point and routing mechanism.

![Kubernetes Ingress](../screenshots/23-kubernetes-ingress.png)

## Network Flow

User
↓
Ingress
↓
Service
↓
Application Pods

## Benefits

- Stable service endpoint
- Application routing
- Separation between external access and pods
- Easier traffic management
