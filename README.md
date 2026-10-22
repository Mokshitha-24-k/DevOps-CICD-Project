# Automated CI/CD Pipeline for Containerized Web Application with Monitoring

## 📌 Project Overview

This project demonstrates an end-to-end DevOps workflow for automating the build, deployment, and monitoring of a containerized web application. A **Netflix Clone** is used as the sample application to demonstrate Continuous Integration (CI), Continuous Deployment (CD), containerization, orchestration, and infrastructure monitoring.

The project integrates **Jenkins, Docker, Kubernetes, Prometheus, and Grafana** to streamline software delivery, reduce manual deployment effort, and improve application reliability, scalability, and observability.

## ⚙️ Project Workflow

The workflow begins when a developer pushes updated source code to the GitHub repository. Jenkins automates the CI/CD pipeline using the instructions defined in the `Jenkinsfile`.

1. **Source Code Management:** Jenkins retrieves the latest application source code from GitHub.
2. **Continuous Integration:** Jenkins executes the pipeline stages to build and prepare the application for deployment.
3. **Docker Image Creation:** Docker packages the application and its dependencies into a portable container image, ensuring consistent execution across environments.
4. **Automated Deployment:** Jenkins deploys the containerized application and replaces the previous version when a new deployment is performed.
5. **Container Orchestration:** Kubernetes manages application Pods, deployment updates, workload scheduling, and scaling. It also supports self-healing by recreating failed Pods according to the configured workload specifications.
6. **Metrics Collection:** Prometheus collects infrastructure and container metrics, including CPU utilization, memory consumption, network activity, and resource usage.
7. **Monitoring and Visualization:** Grafana uses Prometheus as a data source to display metrics through interactive dashboards, helping identify performance issues and monitor system health.

This automated workflow reduces repetitive manual tasks, improves deployment consistency, and provides visibility into application and infrastructure performance.

## 🛠️ Technologies Used

### 1. Jenkins
Jenkins automates the CI/CD pipeline by retrieving source code from GitHub and executing the stages defined in the `Jenkinsfile`. It coordinates application builds and deployment tasks to establish a repeatable software delivery process.

### 2. Docker
Docker containerizes the Netflix Clone application along with its required dependencies. Containerization improves portability, simplifies deployment, and reduces environment-related inconsistencies.

### 3. Kubernetes
Kubernetes orchestrates application containers by managing Pods, deployments, scheduling, scaling, and self-healing. It helps maintain application availability and simplifies container management.

### 4. Prometheus
Prometheus collects and stores time-series metrics from configured infrastructure and monitoring targets. These metrics help analyze resource utilization, monitor system health, and identify potential performance bottlenecks.

### 5. Grafana
Grafana visualizes Prometheus metrics through interactive dashboards, graphs, and gauges. It helps DevOps engineers monitor resource utilization, identify anomalies, and analyze performance trends.

### 6. Git and GitHub
Git provides version control for application source code and pipeline configuration, while GitHub hosts the repository and supports collaboration and source code management.

## 🔄 Workflow Summary

**Developer → GitHub → Jenkins → Docker Image → Container Deployment → Kubernetes → Prometheus → Grafana**

The developer pushes code to GitHub, Jenkins executes the CI/CD pipeline, Docker packages the application, and the deployment workflow runs the containerized application. Kubernetes manages the application workload, Prometheus collects configured metrics, and Grafana visualizes the collected data through monitoring dashboards.

##  Project Objectives

- Automate application build and deployment using Jenkins.
- Containerize a web application using Docker.
- Explore container orchestration with Kubernetes.
- Monitor infrastructure and container performance using Prometheus.
- Visualize metrics through Grafana dashboards.
- Reduce manual deployment effort and improve consistency.
- Develop practical experience with DevOps automation and monitoring.

##  Key Learning Outcomes

- CI/CD pipeline design and automation.
- Docker image creation and container management.
- Kubernetes deployment and orchestration concepts.
- Infrastructure monitoring and metrics visualization.
- Integration of DevOps tools into a unified workflow.
- Troubleshooting deployment and monitoring issues.

## 👩‍💻 Author

**Mokshitha**

GitHub: [Mokshitha-24-k](https://github.com/Mokshitha-24-k)
