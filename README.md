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

## Update to latest version

```
 curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
   && sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

## Check new minikube version

```
$ minikube version
minikube version: v1.7.2
commit: 50d543b5fcb


