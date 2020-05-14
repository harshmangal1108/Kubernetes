#### ***Kubectl*** is kind of client side CLI for using Kubernetes.
##### Insatllation and Setup
```bash
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
mv kubectl /usr/bin/
chmod +x /usr/bin/kubectl
```
##### Using it
```bash
#To check version
$~kubectl version
#To Check Number of Nodes
$~kubectl get node
```
##### Check that kubectl is correctly installed and configured by running the kubectl cluster-info command:
```bash
kubectl cluster-info
```
##### Running a POD
```bash
$~kubectl create -f podfile.yml
##check status
$~kubectl get pods
```
