# Configuration Management

## ConfigMap and Secret

ConfigMap and Secret resources were used to separate configuration data from the application deployment.

![ConfigMap and Secret Resources](../screenshots/21-kubernetes-config-map-secret-resources.png)

## ConfigMap

ConfigMap is intended for non-sensitive configuration values.

## Secret

Secret is intended for sensitive configuration data.

## Benefits

- Separation of configuration from application code
- Easier configuration updates
- Better handling of sensitive values
- Reusable deployment configuration
