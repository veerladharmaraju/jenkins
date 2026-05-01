# 🚀 CI/CD Pipeline using Jenkins on AWS EC2

## 📌 Project Overview

This project demonstrates a complete **CI/CD (Continuous Integration and Continuous Delivery)** pipeline using **Jenkins** deployed on an AWS EC2 instance.

Whenever code is pushed to GitHub, Jenkins automatically triggers a build process.

---

## 🛠️ Technologies Used

* Jenkins (Automation Server)
* AWS EC2 (Cloud Infrastructure)
* Git & GitHub (Version Control)
* Linux (Ubuntu)
* HTML (Sample Application)

---

## ⚙️ CI/CD Workflow

1. Developer pushes code to GitHub repository
2. GitHub webhook triggers Jenkins job
3. Jenkins pulls the latest code
4. Build process is executed automatically
5. Output is displayed in Jenkins console

---

## 🔗 Architecture

GitHub → Jenkins (EC2) → Build Execution

---

## 📂 Project Structure

```
cicd-demo/
│── index.html
│── README.md
```

---

## 🧪 Sample Output

```
Hello DevOps - Day 3 CI/CD
Build triggered from GitHub
```

---

## 🔔 Webhook Configuration

* Payload URL:

```
http://<your-ec2-public-ip>:8080/github-webhook/
```

* Content type: application/json

---

## ▶️ How to Run

1. Push code to GitHub repository
2. Jenkins automatically detects changes
3. Build is triggered
4. Check console output in Jenkins

---

## 📸 Screenshots

(Add your screenshots here)

* Jenkins Dashboard
* Build Console Output
* GitHub Webhook

---

## 🎯 Learning Outcome

* Understood CI/CD pipeline
* Integrated GitHub with Jenkins
* Automated build process
* Learned webhook triggering

---

## 👨‍💻 Author

Your Name
DevOps Learner 🚀
