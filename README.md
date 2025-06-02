## Build a Kubernetes Cluster Locally with Minikube

## Objective:
####  Deploy and manage an app using Kubernetes on an EC2 instance Minikube cluster.
## Tools Used
- Minikube
- kubectl
- Docker
  
### Launched the EC2 server with the t3 small instance type for minikube purpose <br>
#### Installed Docker on the server <br>
#### Installed Minikube on the server <br>
#### Installed Kubectl on the server <br>

### Created a deployment.yml and service.yml for sample Application
#### deploying the kubernetes application <br>
### kubectl apply -f . <br>
### kubectl get pods <br>
### kubectl get nodes <br>

![](https://github.com/deepakbehera11/kubernetes-cluster-locally-with-minikube/blob/ae1b04b9e6b7d9cad64011a1f343462440a07d50/assets/Screenshot-01.png)

### Updating the replicas <br>

![](https://github.com/deepakbehera11/kubernetes-cluster-locally-with-minikube/blob/ae1b04b9e6b7d9cad64011a1f343462440a07d50/assets/Screenshot-02.png)

### kubectl describe for logs <br> 

![](https://github.com/deepakbehera11/kubernetes-cluster-locally-with-minikube/blob/ae1b04b9e6b7d9cad64011a1f343462440a07d50/assets/Screenshot-03.png)

### kubectl describe node <br>

![](https://github.com/deepakbehera11/kubernetes-cluster-locally-with-minikube/blob/ae1b04b9e6b7d9cad64011a1f343462440a07d50/assets/Screenshot-04.png)
