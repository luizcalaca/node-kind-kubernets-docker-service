### Commands

```cmd
docker build -t luizcalaca/nodeapp .
docker run -d -p 3000:3000

docker login
docker push luizcalaca/nodeapp:latest

kind create cluster
kind get clusters
kind load docker-image luizcalaca/nodeapp

kubectl get pods
kubectl get nodes

kubectl apply -f deployment.yml
kubectl get deployment
kubectl apply -f service.yml
kubectl get services

kubectl get svc
kubectl describe svc nodeapp-service
kubectl cluster-info
```
