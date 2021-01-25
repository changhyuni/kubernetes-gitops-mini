# GitOps-CI/CD Kubernetes and Monitoring

### Overview
* Jenkins -> Docker build -> ECR Push
* Helm Chart -> ArgoCD


* [GITOPS Repo](https://github.com/changhyuni/kubernetes-manifest)
* [Jenkinsfile Repo](https://github.com/changhyuni/jenkins-ecr)
* [SOURCE Repo](https://github.com/changhyuni/django-file-server)
* [Terraform](https://github.com/changhyuni/kubernetes-gitops-terraform/tree/main/terraform)


### Architecture
![ex_screenshot](./gitops.png)

### AWS EKS Config
AWS EKS Managed(Spot Instance) / Node Termination Handler / Cluster-Autoscaler

### Objects
* Nginx-Ingress-Controller, Metric-Server, Node Termination Handler, Cluster-AutoScaler
* Prometheus, Grafana
* Jenkins, ArgoCD, ArgoCD Rollouts
