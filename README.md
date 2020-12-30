# kubernetes-taty

folder backend
docker build -t backend-k8s:v1 .
kubectl apply -f backend.yaml 

cambiar la ip del back
folder fronted
docker build -t frontend-k8s:v1 .
kubectl apply -f fronted.yaml 