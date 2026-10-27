# CI/CD Pipeline Automation Using Jenkins, Maven & Tomcat

## Project Overview

This project automates the build and deployment of a Java web application using GitHub, Jenkins, Maven, and Apache Tomcat on AWS EC2.

When code changes are pushed to GitHub, a webhook triggers Jenkins to start the pipeline. Maven builds the application and packages it into a WAR file, which Jenkins deploys to the Tomcat server.

## Technologies Used

* AWS EC2
* Linux
* Git and GitHub
* Jenkins
* Maven
* Apache Tomcat
* GitHub Webhooks

## Architecture

Developer → GitHub → Webhook → Jenkins → Maven Build → WAR File → Apache Tomcat → Web Application

## Project Workflow

1. Push application code to GitHub.
2. GitHub webhook triggers Jenkins.
3. Jenkins runs the configured build process.
4. Maven packages the application into a WAR file.
5. Jenkins deploys the WAR file to the Tomcat server.
6. Access the deployed application through the Tomcat server's configured address.

## Learning Outcomes

* Configuring Jenkins on AWS EC2.
* Integrating GitHub with Jenkins using webhooks.
* Building Java applications using Maven.
* Deploying WAR files to Apache Tomcat.
* Automating application deployment.
