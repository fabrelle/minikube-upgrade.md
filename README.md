# minikube-upgrade.md
How to upgrade Minikube to the latest version in Linux.

Find the current version
$ minikube version
minikube version: v1.33.1

Update to latest version
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
   && sudo install minikube-linux-amd64 /usr/local/bin/minikube


Check the new Minikube version
minikube version


