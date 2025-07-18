# Nextwork Web Project

A production-ready, Java-based web application built with Maven and designed for seamless deployment using AWS DevOps tooling. This project serves as a blueprint for WAR-based application packaging and deployment via AWS CodePipeline, CodeBuild, and CodeDeploy.

---

## Project Overview

The Nextwork Web Project is a structured Java Maven project that demonstrates the full CI/CD lifecycle on AWS. It emphasizes clean modular packaging, environment-based deployment flexibility, and automation of build and release processes using AWS-native services.

This project is ideal for:
- Learning how to set up Java-based CI/CD pipelines on AWS
- Demonstrating Maven + WAR workflows with deployment scripts
- Integrating infrastructure-as-code with software delivery

---

## Technology Stack

| Layer              | Technology                        |
|-------------------|------------------------------------|
| Language           | Java (Amazon Corretto 8)          |
| Build Tool         | Maven                             |
| Packaging          | WAR (Web Application Archive)     |
| Deployment         | AWS CodeDeploy + CodePipeline     |
| Build Automation   | AWS CodeBuild                     |
| Scripts/Automation | Bash                              |

---

## Repository Structure
pom.xml – Maven config

buildspec.yml – AWS build pipeline

appspec.yml – AWS deploy config

scripts/ – Start, stop, install scripts

Highlights
Production-ready CI/CD for Java apps

AWS-integrated DevOps setup

Clean WAR packaging and deployment flow
