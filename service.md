##### Creating service and working
##### Service is used in Accessing our app
```bash
1209	 vim pod1.yml 
1210	 kubectl apply -f pod1.yml 
1211	 kubectl get po -w
1212	 kubectl get  po --show-labels 
1213	 vim pod_service.yml
1214	 kubectl create -f pod_service.yml 
1215	 kubectl get po
1216	 kubectl get service
1217	 kubectl get services 
1218	 kubectl get service
1219	 vim pod_service.yml
1220	 kubectl apply -f pod_service.yml 
1221	 kubectl get service
1222	 vim pod_service.yml
1223	 kubectl apply -f pod_service.yml 
1224	 kubectl get service
1225	 docker ps
1226	 docker inspect minikube
1227	 kubectl get service
```
