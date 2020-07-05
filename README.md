# Cheat Sheet

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
 # Viewing, Finding Resources
 
 ```
kubectl apply -f ./my-manifest.yaml            # create resource(s)
kubectl apply -f ./my1.yaml -f ./my2.yaml      # create from multiple files
kubectl apply -f ./dir                         # create resource(s) in all manifest files in dir
kubectl apply -f https://git.io/vPieo          # create resource(s) from url
kubectl create deployment nginx --image=nginx  # start a single instance of nginx
kubectl explain pods                           # get the documentation for pod manifests 
```
 

