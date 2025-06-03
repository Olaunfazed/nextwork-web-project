# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction

This project introduces the creation and deployment of a Java-based web application using AWS cloud services and CI/CD tools.

The deployment pipeline I'm building for this Java web app automates the software release process, making development more efficient and reliable.

<br>

## Technologies

Here’s what I’m using in this project:

- **Amazon EC2**: I'm developing the web application directly on EC2 virtual servers, allowing cloud-based development and testing.
- **VS Code**: Using the Remote - SSH extension, I connect my IDE directly to my EC2 instance for seamless file editing and management.
- **GitHub**: My web app source code is version-controlled and stored here in this repository.
- **[COMING SOON] AWS CodeArtifact**: This service will store artifacts and dependencies, improving build reliability and speed.
- **[COMING SOON] AWS CodeBuild**: This will handle the build process — compiling, testing, and packaging the app automatically.
- **[COMING SOON] AWS CodeDeploy**: Will automate the deployment of the built application across one or more EC2 instances.
- **[COMING SOON] AWS CodePipeline**: This will tie everything together, from code commit to deployment, providing an automated DevOps workflow.

<br>

## Setup

To get this project running locally or replicate the setup:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/peterafolabi/nextwork-web-project.git
    ```

2. **Navigate into the project folder:**
    ```bash
    cd nextwork-web-project
    ```

3. **Install the dependencies:**
    ```bash
    mvn install
    ```

> ⚠️ **Tip**: Make sure Java and Maven are installed and properly configured in your environment before running the project.

<br>

## Contact

For feedback, questions, or collaboration, feel free to reach out:

**Peter Afolabi**  
📧 [oluwaibkay@gmail.com](mailto:oluwaibkay@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/peterafolabi)

<br>

## Conclusion

Thank you for exploring this project! I'm excited to keep building this CI/CD pipeline and applying DevOps practices in real-world deployments.

A special thanks to **[NextWork](https://learn.nextwork.org/app)** for their step-by-step guide and support.  
[You can start this DevOps series yourself by clicking here.](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)

