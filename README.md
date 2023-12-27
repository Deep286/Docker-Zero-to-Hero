Repo to learn containerization on Docker and Kubernetes platform.

Concepts touched:
1. Minikube, Kubectl and Kubeshark installation
2. Kubernetes architecture, components and characteristics
3. Deploying an application on Pods
4. Replica sets
5. Deployment kind
6. Services (Cluster IP mode, Node port mode and Load balancer mode)
7. Use of Kubeshark
8. Trouble shooting

Summary of commands executed
1. minikube start
2. minikube status
3. minikube stop
4. rm .Dockerfile.swp
5. vim Dockerfile
6. docker build -t python-app:v1 .
7. docker images
8. docker inspect python-app:v1
9. kubectl create -f deployment.yml
10. kubectl apply -f deployment.yml
11. kubectl get deploy
12. kubectl get pods
13. kubectl get pods -o wide
14. vim deployment.yml
15. cat deployment.yml
16. kubectl delete -f deployment.yml
17. kubectl delete pods python-app-8d579c6b-rjdf5
18. docker push deepsuthar/python-app:v1
19. kubectl get svc
20. minikube stop
21. ks tap
22. ks proxy

Thanks !!
