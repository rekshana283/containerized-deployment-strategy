# Backup and Restore Strategy

## Backup Strategy

Kubernetes deployment configuration should be maintained in version control.

The following resources should be backed up:

- Deployment manifests
- Service configuration
- ConfigMap configuration
- Secret configuration
- Ingress configuration
- Namespace configuration
- Container image information

## Version Control

The Kubernetes manifests are stored in the repository so that the deployment configuration can be recreated when required.

## Restore Strategy

A new Kubernetes environment can be restored by applying the saved manifests.

Example:

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f configmap.yaml
kubectl apply -f secret.yaml
kubectl apply -f ingress.yaml
