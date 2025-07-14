Project Summary: Blue-Green Deployment of Bank App using Jenkins + MicroK8s


🚀 Project Overview
This project demonstrates a CI/CD pipeline using Jenkins to deploy a Spring Boot-based
bankapp to MicroK8s using Blue-Green Deployment strategy. Unlike the previous
Python-based app, this project introduces:
● Java & Spring Boot application
● Maven as build tool
● Kaniko (alternative) vs Docker in Jenkins
● Proper MicroK8s ingress rules with hostname routing

🏗 Major Components & Tools Used
Component Purpose
Jenkins (Slave) CI/CD runner and Docker build/push steps
DockerHub Image registry
MicroK8s Lightweight Kubernetes for deployment
Maven Java build system (new to this project)
Spring Boot Java backend app framework
Ingress + NGINX Routes HTTP requests based on
hostname/path
SSH Agent Securely copy & apply K8s YAML to MicroK8s
