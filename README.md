# DevOps Jenkins Pipeline

## Objective
Create a simple Jenkins CI/CD pipeline for a Python application.

## Architecture Diagram
This section summarizes the pipeline architecture and the main components involved.

| Component | Description |
|---|---|
| Source Repository | GitHub repository containing `app.py`, `Dockerfile`, `Jenkinsfile`, and `requirements.txt`. |
| Jenkins Server | Executes the pipeline and coordinates build, test, and deploy stages. |
| Docker | Builds the application image and packages the app for deployment. |
| Python Application | Minimal app that prints a message and is the deployment target of the pipeline. |

## Control Flow Diagram
This section summarizes the control flow of the Jenkins pipeline defined in `Jenkinsfile`.

| Stage | Description |
|---|---|
| Build | Runs the build step and prepares the application. |
| Test | Executes tests or verification steps. |
| Deploy | Deploys the application after successful build and test stages. |

## Tools Used
- Jenkins
- Docker
- GitHub
- Python

## Pipeline Stages
1. Build
2. Test
3. Deploy

## Files
- `app.py`
- `Dockerfile`
- `Jenkinsfile`
- `requirements.txt`

## Application Summary
- `app.py` is a minimal Python app that prints a simple message.
- `Jenkinsfile` defines a declarative pipeline with three stages: Build, Test, and Deploy.
- The pipeline is intentionally simple to demonstrate CI/CD flow in Jenkins.

## Pipeline Screenshots

| Screenshot | Description |
|---|---|
| ![Pipeline Screenshot 1](assets/pipeline-screenshot-1.png) | Jenkins pipeline execution view or job summary. |
| ![Pipeline Screenshot 2](assets/pipeline-screenshot-2.png) | Detailed stage status during the pipeline run. |
| ![Pipeline Screenshot 3](assets/pipeline-screenshot-3.png) | Final pipeline completion or deployment result. |

## Outcome
Learned how Jenkins automates CI/CD workflows by running sequential pipeline stages and deploying a Python application.