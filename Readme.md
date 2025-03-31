# Helm Charts

# Using the Helm charts

1. Add the repo to the Helm repos

```sh
helm repo add cloudutsukpilot https://cloudutsukpilot.github.io/helm-charts/
```

2. Confirm if the repo was added

```sh
helm repo list
```

3. Search for the helm chart

```sh
helm search repo nginx
```

4. Install the helm chart

```sh
helm install local-ngnix cloudutsukpilot/nginx
````

5. Verify the installation

```sh
kubectl get deployments,svc,pods,rs
```
