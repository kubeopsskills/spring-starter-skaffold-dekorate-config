# Spring Starter Project with Skaffold + Dekorate Config

This is a config for `Spring Starter Project with Skaffold + Dekorate`.

## Project Structure
```
|____rbac
| |____microservice.yaml
| |____ghcr-cred.yaml
|____config
| |____helloworld-demo.yaml
| |____kustomization.yaml
|____README.md
```

- `microservice.yaml` is Spring microservice RBAC config file
- `ghcr-cred.yaml` is container registry Kubernetes image pull secret
- `helloworld-demo.yaml` is Spring microservice application config
- `kustomization.yaml` is config map generator from the Spring microservice application config