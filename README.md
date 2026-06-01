# DevOps Jenkins Pipeline

## Objective
Create a simple Jenkins CI/CD pipeline for a Python application.

## Architecture Diagram
![Architecture Diagram](assets/architecture-diagram.png)

This architecture diagram shows the end-to-end flow of the Jenkins pipeline, the source repository, the build/test/deploy stages, and the simple Python app that is being deployed.

## Control Flow Diagram
![Control Flow Diagram](assets/controlflow-diagram.png)

This control flow diagram visualizes how the Jenkinsfile executes the pipeline stages in order: Build, Test, and Deploy. It maps directly to the sequential stage structure in `Jenkinsfile`.

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