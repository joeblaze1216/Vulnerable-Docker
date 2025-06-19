
🛡️ Application Security Portfolio: Full CI/CD Pipeline with SAST, SCA, Container Image Scan, and DAST for OWASP NodeGoat

 ![image](https://github.com/user-attachments/assets/9e198b6f-7da2-4fa9-8403-7e3c0fc08993)


🔍 Seeking opportunities in Application Security / Product Security Engineering

👋 Hello, I'm Johnny Antony Puthur

This repository showcases my complete security-focused CI/CD pipeline implementation for OWASP NodeGoat using GitHub Actions and Kubernetes (AKS). The pipeline integrates SAST, SCA, image scanning, deployment automation, and DAST scanning for complete DevSecOps coverage.

🏗️ Pipeline Overview

| Stage                         | Tool             | Description                                               |
|------------------------------|-------------------|-----------------------------------------------------------|
| Static Application Security  | SonarQube         | Scans code for vulnerabilities and code quality issues    |
| Software Composition Analysis| Snyk              | Detects vulnerable dependencies in the code               |
| Build & Push Image           | Docker            | Builds and pushes tagged Docker image to Docker Hub       |
| Container Image Scanning     | Trivy             | Analyzes Docker image for vulnerabilities                 |
| YAML Version Update & Deploy | GitHub + sed      | Automatically updates version and deploys to Kubernetes   |
| Dynamic App Security Testing | OWASP ZAP         | Runs automated baseline DAST scan post-deployment         |

⚙️ Tools & Technologies

- Kubernetes (AKS)
- GitHub Actions
- SonarQube
- Snyk
- Trivy
- OWASP ZAP
- DockerHub
- YAML, Bash, Git

🚀 CI/CD Workflow Diagram

    +-------------+       +-----------+       +----------------+
    | GitHub Repo |-----> | GitHub CI |-----> | Docker Hub     |
    +-------------+       +-----------+       +--------+-------+
                                                        |
                                                +-------v---------+
                                                | Trivy Scan      |
                                                +-------+---------+
                                                        |
                                                +-------v---------+
                                                | AKS Deployment  |
                                                +-------+---------+
                                                        |
                                                +-------v---------+
                                                | OWASP ZAP DAST  |
                                                +-----------------+

📸 GitHub Actions Pipeline Steps

1. ✅ **SonarQube SAST Scan**
 

2. ✅ **Snyk SCA Scan**
 

3. ✅ **Docker Build & Push**
 

4. ✅ **Trivy Image Scan**
 

5. ✅ **Kubernetes Deploy & YAML Update**
  

6. ✅ **OWASP ZAP DAST Scan**
 

   ![image](https://github.com/user-attachments/assets/392bee6f-ee35-4238-b46b-b4d3bb98d765)


🧾 Sample Jira Report

Issues from SonarQube, Snyk, or ZAP are tracked and managed using Jira for vulnerability management.

![image](https://github.com/user-attachments/assets/aff2374e-0cc9-4d27-997e-8ead7c2b3559)


📢 I'm Looking For

Application Security Engineer or Product Security Engineer roles where I can:

- Integrate secure practices in CI/CD pipelines
- Automate vulnerability management across SDLC
- Implement SAST, SCA, DAST, container scanning
- Secure Kubernetes workloads

📬 Connect with me on [LinkedIn](https://www.linkedin.com/in/puthurjohnny/) or contact me via GitHub.

 
