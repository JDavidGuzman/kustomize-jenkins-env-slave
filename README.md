# Kubernetes RBAC

This project contains a Kustomize configuration to deploy development, qa, and production environments on a Kubernetes Cluster. Besides that, it contains an RBAC model that allows a Jenkins slave, using the integration Kubernetes plugin on Jenkins, to deploy kubernetes deployments exposed through ingresses.

## Notes

This project requires adding a Kubernetes configuration file in order to deploy it as a secret on jenkins namespace to allowing jenkins slave to communicate with Kubernetes apiserver.