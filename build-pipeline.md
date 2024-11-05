# DevOps Assigment 2 - GitHub Actions & DockerHub

## Description of Workflow

Checkout Code: Retrieves the latest code from the repository.

Set Up JDK: Installs the Java Development Kit for building the application.

Compile Application: Uses Maven to clean and package the Java application into a JAR.

Build Docker Image: Creates a Docker image from the application JAR.

Log in to DockerHub: Authenticates using the DockerHub Personal Access Token stored as a secret.

Push Docker Image: Pushes the built Docker image to the specified DockerHub repository.

## Link to DockerHub Repository
[DockerHub - `YOURLASTNAME-WOPro-Service`](place link here)

## Link to GitHub Actions Run Results Summary
[Link to **working** workflow run results](sampleURL:https://github.com/WSU-kduncan/s24cicd-pattonsgirl/actions/runs/8726150186/job/23941797523)
