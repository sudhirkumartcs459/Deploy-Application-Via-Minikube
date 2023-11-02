Deploy the Application using the Local Minikube Kubernetes Cluster, there are some prerequisites are given below. 


1.Install [Kubectl](https://kubernetes.io/docs/tasks/tools/) tool that is used to manage the manage the Kubernetes cluster via CLI 

Note - Kubectl is the Command line Interface that is used to manage the Kubernetes cluster

Once you have Install the Kubectl tool on your machine you can verify it by using the command # kubectl verison 

 2.Now proceed to install the local [Minikube](https://minikube.sigs.k8s.io/docs/start/) kuburnetes cluster.

After Installation of the Minikube you can procced to verify the Minikube using the command # minikube 

After Installation of the Minikube we are going to create the Kubernetes cluster using the Minikube Instructions are given below:


# minikube start --memory=2200 --driver=docker             Note- Docker should be present in the system 


Now after installation of the Minikube on the system we can verify the Minikube control plane # minikube get nodes 
                                                                                              

After Installation Minikube Node, we have to install the Minikube Pod on the system follow the [link](https://kubernetes.io/docs/concepts/workloads/pods/)

create the application using the command and it will created as per code in the Pod YAML Configuration file # kubectl create -f pod.yml


Now you can verify the Kubernetes pod using the command line # kubectl get pods


How to get the complete detail of the Pod using the command # kubectl get pods -o wide 


How to take SSH of the Minikube # minikube ssh 


And now you can verify the application# curl $ IP of the Pod 


