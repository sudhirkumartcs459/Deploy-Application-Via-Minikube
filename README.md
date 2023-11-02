Deploy the Application using the Local Minikube Kubernetes Cluster, there are some prerequisites are given below. 


1.Install [Kubectl](https://kubernetes.io/docs/tasks/tools/) tool that is used to manage the manage the Kubernetes cluster via CLI 

Note - Kubectl is the Command line Interface that is used to manage the Kubernetes cluster

Once you have Install the Kubectl tool on your machine you can verify it by using the command # kubectl verison 

 2.Now proceed to install the local [Minikube](https://minikube.sigs.k8s.io/docs/start/) kuburnetes cluster.

After Installation of the Minikube you can procced to verify the Minikube using the command # minikube 

After Installation of the Minikube we are going to create the Kubernetes cluster using the Minikube Instructions are given below:


# minikube start --memory=2200 --driver=docker             Note- Docker should be present in the system 






