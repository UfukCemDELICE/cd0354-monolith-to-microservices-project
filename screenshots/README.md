# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed - Done
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook) - Done
* Travis CI showing a successful build and deploy job - Done

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods - Done
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services - Done
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa - Done
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
