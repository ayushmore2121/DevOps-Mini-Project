# DevOps-Mini-Project
# ☁️ CloudTask – Student Task Management System

## 📌 Project Overview

CloudTask is a web-based Student Task Management System developed using Python, Flask, HTML, and CSS. The application allows students to create, manage, and track their daily academic tasks.

The project is deployed on an Amazon Web Services (AWS) EC2 cloud server to demonstrate cloud hosting, application deployment, containerization, and DevOps practices.

## 🎯 Objectives

- Develop a simple and user-friendly web application.
- Deploy the application on an AWS EC2 instance.
- Understand cloud computing and server management.
- Use Docker to containerize the application.
- Use Git and GitHub for version control.
- Implement automated testing using GitHub Actions.
- Gain practical experience with DevOps tools and workflows.

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Backend programming |
| Flask | Web application framework |
| HTML | Web page structure |
| CSS | User interface design |
| SQLite | Task data storage |
| AWS EC2 | Cloud server hosting |
| Ubuntu Server | Server operating system |
| Docker | Application containerization |
| Git | Version control |
| GitHub | Source code repository |
| GitHub Actions | Automated testing and CI |

## ✨ Features

- Add new tasks.
- View all tasks.
- Mark tasks as completed.
- Delete existing tasks.
- Track pending and completed tasks.
- Access the application through a web browser.
- Deploy the application on an AWS EC2 server.

## 🏗️ System Architecture

```text
             Student / User
                    |
                    v
              Web Browser
                    |
                    v
                Internet
                    |
                    v
             AWS EC2 Instance
              (Ubuntu Server)
                    |
                    v
              Docker Container
                    |
                    v
              Flask Application
                    |
                    v
                SQLite DB
