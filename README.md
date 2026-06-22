# Flask URL Shortener with Azure CI/CD

## 📌 Project Overview

This project is a simple **URL Shortener Web Application** built using **Python Flask**. Users can enter a long URL and receive a shortened URL that redirects to the original website.

The project demonstrates **DevOps practices** by implementing a complete **CI/CD pipeline using GitHub Actions and Azure App Service**, enabling automatic deployment whenever changes are pushed to the GitHub repository.

---

## 🚀 Features

* Shorten long URLs into unique short links
* Redirect short URLs to original URLs
* Simple and responsive web interface
* Persistent URL storage using JSON
* Automated CI/CD deployment with GitHub Actions
* Hosted on Microsoft Azure App Service

---

## 🛠️ Technologies Used

| Technology        | Purpose             |
| ----------------- | ------------------- |
| Python            | Backend Development |
| Flask             | Web Framework       |
| HTML              | Frontend Structure  |
| CSS               | Styling             |
| GitHub Actions    | CI/CD Automation    |
| Azure App Service | Cloud Hosting       |
| JSON              | URL Storage         |

---

## 📂 Project Structure

```text
CodeAlpha_Devops_Task1/
│
├── .github/
│   └── workflows/
│       └── main_url-shortner.yml
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── images/
│   ├── Screenshot (1877).png
│   ├── Screenshot (1878).png
│   └── Screenshot (1879).png
│
├── app.py
├── urls.json
├── requirements.txt
├── startup.txt
└── README.md
```


## 🔄 CI/CD Pipeline Workflow

The project uses **GitHub Actions** for Continuous Integration and Continuous Deployment.

### Workflow Steps

1. Developer pushes code to GitHub.
2. GitHub Actions workflow is triggered.
3. Dependencies are installed.
4. Build process is validated.
5. Application artifact is generated.
6. Azure authentication is performed.
7. Application is automatically deployed to Azure App Service.

---

## ☁️ Azure Deployment

### Services Used

* Azure App Service
* GitHub Actions
* Azure Login Action
* Azure Web Apps Deploy Action

### Deployment Trigger

```yaml
on:
  push:
    branches:
      - main
```

Every push to the `main` branch automatically deploys the latest version of the application.

---

## 📸 Output Screenshots

### Home Page

Add screenshot:

```text
images/Screenshot (1877).png
```

### URL Generated

Add screenshot:

```text
images/Screenshot (1878).png
```

### Azure Deployment Success

Add screenshot:

```text
images/Screenshot (1879).png
```

---

## 📋 Requirements

```text
Flask
gunicorn
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Learning Outcomes

* Flask Web Application Development
* Azure App Service Deployment
* GitHub Actions Workflow Creation
* CI/CD Pipeline Automation
* Cloud-Based Application Hosting
* Version Control with Git & GitHub

---

## 👨‍💻 Author

**Maheesh Varma Ugge**

B.Tech CSE (AI & ML)
SR University

---

## 📜 Internship

This project was completed as part of the **CodeAlpha DevOps Internship Program**.

### Task 1: CI/CD Pipeline with Azure and GitHub Actions

Successfully implemented an end-to-end deployment pipeline that automatically builds and deploys a Flask application to Azure whenever code is pushed to GitHub.
