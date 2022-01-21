# Kubernetes Skills
1. What is pod?
Pods are the smallest, most basic deployable objects in Kubernetes. A Pod represents a single instance of a running process in your cluster.  
Pods contain one or more containers, such as Docker containers. When a Pod runs multiple containers, the containers are managed as a single entity and share the Pod's resources.

2. How can save important secrets in Kubernetes?
* Vault 
* encrypted data in etcd

3. How deployments works?
Deployment creates replicaset and replicaset creates pods. It's try to run pods based of desired state that to define.


