## Find the current version

```
$ minikube version
minikube version: v1.7.1
```

## Check if there are newer versions available

```
$ minikube update-check
CurrentVersion: v1.7.1
LatestVersion: v1.7.2
```

## Update to the latest version

```
 curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
   && sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

## Check the new Minikube version

```
$ minikube version
minikube version: v1.33.1
commit: 5883c09216182566a63dff4c326a6fc9ed2982ff


