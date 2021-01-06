# Kubernetes Learning


### Order to have a Entire Cluster K8s

config-map > svc > pvc > deployment/stateful-set

### ConfigMap

Set all the environment variables for a application.

### Service (SVC)

Used to load balancer the application.

### PersistentVolumeClaim

Create a resource to your pv, if you don't have any sc (StorageClass) it will use the default one.

### Deployments/StatefulSet

Good to have many pods (Applications)

#### Utils

#### Liveness Probe

It's used to see if the application is working correctly

#### Readiness Probe

It's used to see if the application is ready to receive requests