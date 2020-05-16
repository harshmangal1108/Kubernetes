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
#above cmd will not create if already pod exist
#We can use apply cmd it will try to create pod again same and also will update if it there
$~kubectl apply -f podfile.yml
##check status
$~kubectl get pods
#-w for watching live
$~kubectl get pods -w
###checking IP of POD , Node where it scheduled
~>>kubectl get pods -o wide
## delete POD
$~kubectl delete pod podname
##rather than get pod we can use describe for detailed infomation
$~kubectl describe pods podname
```
