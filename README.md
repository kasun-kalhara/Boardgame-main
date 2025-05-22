# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)


🚀 Ultimate CI/CD DevOps Pipeline Project

This is a real-time, corporate-grade DevOps project built completely from scratch. It demonstrates how to design, implement, and deploy a production-ready CI/CD pipeline using the best practices and industry tools on AWS.



📌 Objective

      Build a complete CI/CD infrastructure using:
      Jenkins
      SonarQube
      Nexus Repository
      Docker
      Kubernetes
      Trivy
      Prometheus + Grafana
      GitHub 
      Email Notifications

🏗️ Project Architecture

![alt text](<Screenshot 2025-05-22 081652.png>)


🧪 Step-by-Step: How to Build This Project
🔹 Phase 1: Infrastructure Setup (on AWS)

1.Create VPC (or use default)

    Isolate your resources in a private network.

2.Launch EC2 Instances:

    3 VMs for Kubernetes: 1 Master + 2 Workers
    1 VM for Jenkins
    1 VM for SonarQube
    1 VM for Nexus
    Use Ubuntu 20.04 AMIs

3.Configure Security Groups:

    Open necessary ports (22, 80, 443, 8080, 9000, 8081, 3000–32767, etc.)

4.Install Required Tools:

    Docker
    Jenkins
    SonarQube (Docker container)
    Nexus Repository (Docker container)

5.Install Kubernetes:

    Use kubeadm to initialize the cluster on the master
    Join worker nodes using kubeadm join command

🔹 Phase 2: Git & Source Code Setup

      Create Private GitHub Repository
      Push Java Maven Project Source Code
      Install Git on Jenkins Server
      Generate GitHub Personal Access Token
      Add Git credentials to Jenkins


🔹 Phase 3: Jenkins CI/CD Pipeline

Jenkins Configuration:

Install Plugins:

    Maven Integration
    SonarQube Scanner
    Docker Pipeline
    Kubernetes CLI
    Email Extension
    Config File Provider

Configure Tools:

    JDK 17
    Maven
    Docker
    Sonar Scanner


🔹 Phase 4: Monitoring & Alerting

      Node Exporter (for Jenkins & servers)
      Blackbox Exporter (for app endpoint checks)
      prometheus Configuration
            Scrape configs for exporters
      Grafana Dashboards
            Visualize CPU, memory, disk usage, HTTP uptime



