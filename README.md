# Awsome-Kubernetes

# Kubectl Context and Configuration

See Authenticating Across Clusters with kubeconfig documentation for detailed config file information.
kubectl config view # Show Merged kubeconfig settings.

```
kubectl config view # Show Merged kubeconfig settings.
```

# add a new user to your kubeconf 
```
kubectl config set-credentials kubeuser/foo.kubernetes.com --username=kubeuser --password=kubepassword
```

# Apply

 It creates and updates resources in a cluster through running kubectl apply
 
 ```
 kubectl apply -f example.yaml           # create resource(s)
```
 
