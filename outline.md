In this book we will cover the basics of Kubernetes, and help you getting your Linux containers scheduled in Kubernetes. We will cover the most used concepts from writting Dockerfiles, deploying Pods to accessing them from outside the cluster.
# [About the book and auther](about.md)
# [1.0 What is a Linux container](chapter01.md)
# [2.0 What is Kubernetes](chapter02.md)
## 2.1 A history of Kubernetes
## 2.2 Why we need Kubernetes
## 2.3 The components of Kubernetes
### 2.3.1 Api-Server
### 2.3.2 Scheduler
### 2.3.3 Kubelet
### 2.3.4 Kube-Proxy
# [3.0 Kubnernetes objects](chapter03.md)
## 3.1 Pods
## 3.2. Deployments
## 3.3. Services
## 3.4 Ingress
## 3.5 PetSets
## 3.6 ConfigMaps
## 3.7 Secrets
## 3.8 PersistantVolumes / Claims
# [4.0 Doing by example - Jira and mySQL](chapter04.md)
## 4.1 Prerequisites
## 4.2 Preparing the Linux container image
## 4.3 Declaring ConfigMaps
## 4.4 Declaring Jira as a PetSets
## 4.5 Creating a Jira service
## 4.6 Creating an Ingress objects
## 4.7 Deploying a mySQL database
## 4.8 Deploying our Jira PetSet
## 4.9 Accessing Jira from the outside
### 4.9.1 Using Traefik as a Load Balancer
### 4.9.2 Setting up DNS
### 4.9.3 Accessing Jira
# [5.0 Summerize and ending](chapter05.md)
