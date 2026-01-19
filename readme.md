# HELM Chart & Kubernetes Deployment for MERN Application

This project demonstrates the creation of Kubernetes deployment files and HELM charts for a MERN (MongoDB, Express.js, React.js, Node.js) stack application, along with Jenkins CI/CD pipeline automation.

## Project Overview

In this assignment, we are tasked with:
- Developing Kubernetes deployment files for both frontend and backend components
- Creating a HELM chart to streamline the deployment process
- Writing Jenkins Groovy code to automate the build and deployment process
- Ensuring seamless deployment, scalability, and efficient CI/CD pipeline

## Application Used

Instead of the originally suggested repositories, we have used **ShopNow** application.

**Forked Repository:** https://github.com/aryanm12/shopNow

![Project Overview](screenshots/image1.png)

---

## Kubernetes Deployment

### Backend Deployment

The backend component is deployed using Kubernetes deployment configurations that ensure:
- Scalability and high availability
- Proper resource allocation
- Service discovery and networking

![Backend Deployment 1](screenshots/image2.png)
![Backend Deployment 2](screenshots/image3.png)

### Frontend Deployment

The frontend React application is containerized and deployed with:
- Nginx reverse proxy configuration
- Static file serving optimization
- Load balancing capabilities

![Frontend Deployment 1](screenshots/image4.png)
![Frontend Deployment 2](screenshots/image5.png)

---

## Git Repository Management

Proper version control and repository management for the project:

![Git Repository](screenshots/image6.png)

---

## CI/CD Pipeline with Jenkins

Automated build and deployment pipeline using Jenkins with:
- Automated testing and building
- Docker image creation and pushing
- Kubernetes deployment automation
- Pipeline monitoring and notifications

![CI/CD Pipeline 1](screenshots/image7.png)
![CI/CD Pipeline 2](screenshots/image8.png)
![CI/CD Pipeline 3](screenshots/image9.png)
![CI/CD Pipeline 4](screenshots/image10.png)
![CI/CD Pipeline 5](screenshots/image11.png)
![CI/CD Pipeline 6](screenshots/image12.png)
![Final Pipeline Result](screenshots/image13.png)

---

## Technologies Used

- **Kubernetes**: Container orchestration platform
- **HELM**: Package manager for Kubernetes
- **Jenkins**: CI/CD automation server
- **Docker**: Containerization platform
- **MERN Stack**: MongoDB, Express.js, React.js, Node.js
- **Git**: Version control system

## Key Features

✅ **Kubernetes Deployments**: Scalable frontend and backend deployments  
✅ **HELM Charts**: Streamlined deployment and configuration management  
✅ **Jenkins Pipeline**: Automated CI/CD with Groovy scripting  
✅ **Docker Integration**: Containerized application components  
✅ **Service Discovery**: Kubernetes native networking  
✅ **Load Balancing**: High availability and traffic distribution  
✅ **Monitoring**: Pipeline and deployment monitoring  

## Project Architecture

```
ShopNow MERN Application
├── Frontend (React.js)
│   ├── Kubernetes Deployment
│   ├── Service Configuration
│   └── Ingress Rules
├── Backend (Node.js/Express)
│   ├── Kubernetes Deployment
│   ├── Service Configuration
│   └── Database Connection
├── HELM Chart
│   ├── Templates
│   ├── Values.yaml
│   └── Chart.yaml
└── Jenkins Pipeline
    ├── Build Stage
    ├── Test Stage
    ├── Docker Build & Push
    └── Kubernetes Deploy
```

## Deployment Process

1. **Code Commit**: Developer pushes code to Git repository
2. **Jenkins Trigger**: Webhook triggers Jenkins pipeline
3. **Build & Test**: Application is built and tested
4. **Docker Image**: Container images are created and pushed to registry
5. **HELM Deploy**: HELM chart deploys application to Kubernetes cluster
6. **Verification**: Deployment is verified and monitored

## Project Structure

```
free5/
├── HEM Project.docx        # Original project documentation
├── readme.md              # This documentation
└── screenshots/           # All project screenshots
    ├── image1.png        # Project overview
    ├── image2.png        # Backend deployment
    ├── image3.png        # Backend configuration
    ├── image4.png        # Frontend deployment
    ├── image5.png        # Frontend configuration
    ├── image6.png        # Git repository
    ├── image7.png        # CI/CD pipeline setup
    ├── image8.png        # Pipeline configuration
    ├── image9.png        # Build process
    ├── image10.png       # Deployment process
    ├── image11.png       # Pipeline monitoring
    ├── image12.png       # Final deployment
    └── image13.png       # Pipeline success
```

## Challenges and Solutions

- **Container Orchestration**: Implemented Kubernetes for scalable deployment
- **Configuration Management**: Used HELM charts for templated deployments
- **Automation**: Jenkins pipeline for consistent CI/CD process
- **Monitoring**: Integrated logging and monitoring for production readiness

This project demonstrates a complete DevOps workflow for MERN stack applications using modern container orchestration and automation tools.