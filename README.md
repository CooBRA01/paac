## Overview

This is a basic website built using ReactJS that has been designed to be used for Continuous Integration and Deployment (CI/CD). The website is deployed on EC2, and the pipeline is managed using Jenkins. Ansible is used to pull the Docker image and run the container, and SonarQube is used for code quality analysis.

## Requirements

To use this app, you'll need to have the following:

- ReactJS
- EC2 instance
- Jenkins
- Ansible
- Docker
- SonarQube

## Installation

To install the app, follow these steps:

1. Clone the repository to your local machine
2. Install the required dependencies
3. Configure Jenkins to manage the pipeline
4. Configure Ansible to  pull the Docker image and run the container
5. Run SonarQube to perform code quality analysis

## Usage

To use the app, follow these steps:

1. Make changes to the website code in your local repository
2. Push the changes to the remote repository
3. Jenkins will automatically pick up the changes and run the pipeline
4. Ansible will pull the Docker image and run the container on the EC2 instance
5. SonarQube will perform code quality analysis and provide feedback

## Conclusion

This app provides a basic website built using ReactJS that can be used for CI/CD. It is deployed on EC2 and managed using Jenkins, with Ansible used to pull the Docker image and run the container. SonarQube is used for code quality analysis.
