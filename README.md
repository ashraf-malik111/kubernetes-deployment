# Kubernetes Deployment Project

This project demonstrates application deployment on Kubernetes using Deployments, Services, and Ingress resources.

## Technologies Used

* Kubernetes
* Docker
* YAML
* NGINX

## Project Components

### Deployment

* Manages application pods.
* Ensures desired number of replicas are running.

### Service

* Exposes application pods within or outside the cluster.
* Provides load balancing across pods.

### Ingress

* Manages external HTTP/HTTPS access.
* Routes traffic to Kubernetes services.

## Files Included

* deployment.yaml
* service.yaml
* ingress.yaml

## Deployment Commands

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

kubectl apply -f ingress.yaml

## Benefits

* High Availability
* Scalability
* Load Balancing
* Simplified Application Management

## Author

Ashraf
Senior DevOps Engineer
AWS | Jenkins | Terraform | Docker | Kubernetes
