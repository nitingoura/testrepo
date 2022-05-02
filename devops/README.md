# Devops ReadMe

### Step 1 - Pre-Request

1. Make sure you have Kubernetes cluster running and accessible from system where you going to run commands
    Test connection using command
    ```
    kubectl get all --all-namespaces 
    ```
2. I am using jenkins file to automate step. I am assuming we have up and running jenkins machine

### Step 2 - Deploy the NGINX Ingress Controller & Cert manager
use jenkins file from path - devops/jenkins/infra/Jenkinsfile

### Step 2 - Deploy an App Service
use jenkins file from path - devops/jenkins/app/Jenkinsfile