# Kubernetes Workshop: Deploying a WordPress Application

# Prerequisites:
A running Minikube cluster.
kubectl command-line tool installed.
Docker installed (for building custom images).
Basic knowledge of Kubernetes concepts (Pods, Services, Deployments).

# Installations:
1. Minikube
To install Minikube, follow the official Minikube installation guide.
2. kubectl
Install kubectl by following the official kubectl installation guide.
3. Docker (if needed)
Install Docker by following the official Docker installation guide.
4. Helm (optional for package management)
If you are using Helm for managing Kubernetes applications, install it by following the official Helm installation guide.
5. NGINX Ingress Controller
To manage ingress resources, install the NGINX Ingress Controller
6. Persistent Volume and Persistent Volume Claim
Define a PersistentVolume and PersistentVolumeClaim in YAML to ensure data persistence for the MySQL database.
7. Prometheus and Grafana (optional)
To monitor your Kubernetes cluster:
Follow the kube-prometheus-stack installation instructions.
