# DevOps Capstone Project

## Project Name
DevOps Capstone Project - Accounts Microservice CI/CD Pipeline

## Description
This project is the final capstone of the IBM DevOps and Software Engineering course. It is a Flask-based Accounts REST API microservice with a complete CI/CD pipeline:

- **GitHub Actions**: runs flake8 linting and nose unit tests on every push and pull request.
- **Tekton Pipeline**: cleans the workspace, clones the repository, runs the tests, builds the image and deploys it.
- **OpenShift**: the application is deployed to an OpenShift cluster by the Tekton pipeline.

## Author
yPala
