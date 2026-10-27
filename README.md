# CI/CD Pipeline Automation Using Jenkins, Maven & Tomcat

##  Project Overview

This project demonstrates the automation of application build and deployment using Jenkins, Maven, and Apache Tomcat on AWS EC2 instances.

A GitHub webhook triggers Jenkins when code changes are pushed to the repository. Jenkins uses Maven to build the Taxi/Cab Booking application into a WAR file and deploys it to an Apache Tomcat server.

##  Technologies Used

* **AWS EC2** – Hosts Jenkins and Tomcat servers.
* **Git & GitHub** – Source code management.
* **GitHub Webhooks** – Automatically trigger Jenkins builds when configured repository events occur.
* **Jenkins** – Automates the CI/CD pipeline.
* **Apache Maven** – Builds the application and packages it into a WAR file.
* **Apache Tomcat** – Hosts the deployed web application.
* **Java** – Application development and build environment.

##  Architecture

   text
Developer
    |
    v
GitHub Repository
    |
    | GitHub Webhook
    v
Jenkins Server (AWS EC2)
    |
    | Maven Build
    v
WAR File
    |
    | Automated Deployment
    v
Tomcat Server (AWS EC2)
    |
    v
Taxi/Cab Booking Web Application


##  CI/CD Workflow

1. **Code Management:** Application source code is stored in GitHub.
2. **Webhook Integration:** A GitHub webhook triggers Jenkins when the configured repository event occurs.
3. **Build Automation:** Jenkins retrieves the source code and executes the Maven build.
4. **WAR Packaging:** Maven compiles the application and packages it into a WAR file.
5. **Automated Deployment:** Jenkins deploys the WAR file to the Tomcat server.
6. **Application Access:** Users access the deployed Taxi/Cab Booking application through a web browser.

##  Key Learning Outcomes

* Configured a Jenkins job for automated application builds.
* Integrated GitHub with Jenkins using webhooks.
* Used Maven to build and package a Java web application.
* Automated WAR file deployment to Apache Tomcat.
* Practiced deploying and managing application components on AWS EC2.
