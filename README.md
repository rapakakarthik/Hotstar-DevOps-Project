### Prerequisites

- AWS account setup
- Basic knowledge of AWS services
- Understanding of DevSecOps principles
- Familiarity with Docker, Jenkins, Java, SonarQube, AWS CLI, Kubectl, and Terraform,Docker Scout

### Step-by-Step Deployment Process
### Step 1: Setting up AWS EC2 Instance

- Creating an EC2 instance with Ubuntu AMI, t2.large, and 30 GB storage
- Assigning an IAM role with Admin access for learning purposes

### Step 2: Installation of Required Tools on the Instance

- Writing a script to automate the installation of:
- Docker
- Jenkins
- Java
- SonarQube container
- AWS CLI
- Kubectl
- Terraform

### Step 3: Jenkins Job Configuration

- Creating Jenkins jobs for:
- Creating an EKS cluster
- Deploying the Hotstar clone application
- Configuring the Jenkins job stages:
- Sending files to SonarQube for static code analysis
- Running npm install
- Implementing OWASP for security checks
- Installing and running Docker Scout for container security
- Scanning files and Docker images with Docker Scout
- Building and pushing Docker images
- Deploying the application to the EKS cluster

### Step 4: Clean-Up Process

- Removing the EKS cluster
- Deleting the IAM role
- Terminating the Ubuntu instance
