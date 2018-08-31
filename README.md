# kube-apiserver

github addr [https://github.com/kubernets/kube-apiserver](https://github.com/kubernets/kube-apiserver)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/kube-apiserver/raw/master/get-kube-apiserver-image.sh

## Arch and Version

- [**amd64** v1.11.2](https://hub.docker.com/r/kubernets/kube-apiserver-amd64)

    > docker pull kubernets/kube-apiserver-amd64:v1.11.2

    > docker tag kubernets/kube-apiserver-amd64:v1.11.2 gcr.io/google-containers/kube-apiserver-amd64:v1.11.2 

    > docker rmi kubernets/kube-apiserver-amd64:v1.11.2
