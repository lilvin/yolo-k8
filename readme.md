This is Yolo-client Ochestration using kubernetes.
Below are the steps followed.
1.	Install Minikube
2.	Start Minikube
3.	Verify Kubernetes Installation by running kubectl version
4.	Interacting with Minikube Cluster
5.	Launch the Minikube dashboard


6.	Deploying Applications: To deploy an application to your Minikube cluster, use the kubectl apply command to deploy and create services. Cd into client and run kubectl apply -f client-deployment.yaml –f client-service.yaml and then cd into backend and run kubectl apply -f deployment.yaml -f service.yaml -f configmap.yaml.
7.	Accessing Services
8.	Cleaning Up


The images used were containerized using docker.
1. lilianthiauru/yolo-client:1.0.0
2. lilianthiauru/yolo-backend:1.0.0
