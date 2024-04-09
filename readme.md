# README

## Note

1. Cannoot access services via NodePort on MacOS with Docker driver
    - [issue](https://github.com/kubernetes/minikube/issues/11193)
    - Sol: `minikube service hello-minikube1 --url` 用 tunnel 連線 minikube service
