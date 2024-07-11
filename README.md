# CI-CD-Pipeline-Implementation-using-Jenkins....


Provisioning the Environment:

Launched an AWS EC2 instance (t3.medium) for scalability and reliability.
Tool Installation:
Installed Jenkins for continuous integration.
Set up Git for effective version control.
Deployed Docker for containerized application management.
Configured SonarQube as a Docker container for continuous code quality checks.
Installed Maven for project build and dependency management.
Configuring Jenkins:
Installed essential plugins including SonarQube, Maven Integration, Eclipse JDK tools, etc.
Configured Jenkins tools ensuring proper paths and settings.
Integrating SonarQube:
Deployed SonarQube as a Docker container, secured with a generated token.
Integrated SonarQube token securely in Jenkins for automated code quality analysis.
Configured SonarQube server details in Jenkins for seamless integration.
Managing Application Builds:
Managed project artifacts with Maven, ensuring efficient build and dependency management.
Automated JAR file inclusion in build processes, maintaining version control.

 Continuous Deployment with Docker:

Enhanced pipeline to include continuous deployment using Docker.
Automated Docker image builds and deployments, ensuring rapid and reliable application updates.
Pushed Docker images to Docker Hub for accessible distribution and version management.
