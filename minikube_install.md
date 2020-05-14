### Minikube Installation in Linux
### We can assume **minikube** as automatic ***Kubernetes*** installer
```bash
833  curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  835  mv minikube /usr/bin/
  836  sudo mv minikube /usr/bin/
  839  minikube start --driver=docker
  980  minikube start --driver=docker
 1004  which minikube
 1006  cd /usr/bin/minikube
 1009  minikube start --driver=docker
 1010  docker exec -it minikube bash
 1014  history | grep minikube
 1015  docker stats minikube
 ```
