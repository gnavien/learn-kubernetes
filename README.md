# learn-kubernetes

Advantages of POD Over Container
1. POD is a logical group of containers, meaning a POD can have one or more containers inside that.
2. Dealing with network is advantage
3. Dealing with storage is an advantage
4. Inbuilt DNS server

Network In POD Vs Container

In Microservices world, all softwares are small pieces, they will run individually and connect over the network. While small pieces, software development can go even smaller pieces where couple of pieces together work as one container as once microservice. Each such nano piece will be a container.



# We will use AWS EKS cluster for our project Master node will be managed by AWS and you will have EC2 instances running containers and for storage there will be EBS/EFS and networking we will have LB (load balancer) and SG (Security Group)

# We will use AWS EKS, but to start with we will use kubernetes Minikube and later on we will move to AWS EKS.

In Minikube we have Master + Node (One Server)

