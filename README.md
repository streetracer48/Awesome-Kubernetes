# Awsome-Kubernetes

# Kubectl Context and Configuration

See Authenticating Across Clusters with kubeconfig documentation for detailed config file information.
kubectl config view # Show Merged kubeconfig settings.


```
kubectl config view # Show Merged kubeconfig settings.
```

# add a new user to your kubeconf that supports basic auth
```
kubectl config set-credentials kubeuser/foo.kubernetes.com --username=kubeuser --password=kubepassword
```
