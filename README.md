Repo to learn containerization on Docker and Kubernetes platform.

Concepts touched:
1. Minikube, Kubectl and Kubeshark installation
2. Kubernetes architecture, components and characteristics
3. Deploying an application on Pods
4. Replica sets
5. Deployment kind
6. Services (Cluster IP mode, Node port mode and Load balancer mode)
7. Use of Kubeshark

Summary of commands executed
minikube start
minikube status
minikube stop
rm .Dockerfile.swp 
vim Dockerfile
docker build -t python-app:v1 .
docker images
docker inspect python-app:v1
kubectl create -f deployment.yml 
kubectl apply -f deployment.yml 
kubectl get deploy
kubectl get pods
kubectl get pods -o wide
vim deployment.yml 
cat deployment.yml 
kubectl delete -f deployment.yml
kubectl delete pods python-app-8d579c6b-rjdf5
docker push deepsuthar/python-app:v1
kubectl get svc
minikube stop
ks tap
ks proxy
