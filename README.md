# kubernetes-testing-pod
Docker image to setup a useful testing pod in Kubernetes  

# Build from Dockerfile
```
Get-Content Dockerfile | docker build -
```

# Tag image 
```
docker tag e461f36bd216 bojewell/kubepod
```

# Push docker image to docker hub

```
docker image push bojewell/kubepod
```