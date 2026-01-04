# Flipkart Clone – Dockerfile Practice Project 🐳

This project focuses on **Dockerfile creation and containerization** using a static Flipkart-style web application.  
It is built specifically for **Cloud / DevOps engineers** to practice Docker fundamentals.

---

## 🎯 Project Purpose

The main goal of this project is to:

- Practice writing a **Dockerfile**
- Build a **custom Docker image**
- Run a **containerized static web application**
- Understand Docker concepts used in real-world DevOps environments

Frontend code is used only as **sample content** for Docker practice.

---

## 🛠️ Technologies Used

- Docker
- Dockerfile
- Nginx (web server inside container)
- HTML / CSS / JavaScript (static files)
- Git & GitHub

---
## 📂 Project Structure

├── Dockerfile
├── index.html
├── login.html
├── signup.html
├── electronics.html
├── fashion.html
├── css/
├── js/
├── assets/
└── README.md

---

## 🐳 Dockerfile Explanation

The Dockerfile performs the following steps:

- Uses an official lightweight **Nginx base image**
- Copies static website files into the Nginx web directory
- Exposes port **80** for HTTP traffic
- Runs Nginx in the foreground to serve the application

This setup reflects how static websites are commonly deployed in containers.

---

##  Build & Run Using Docker

2️⃣ Build Docker Image
docker build -t flipkart-clone .

3️⃣ Run Docker Container
docker run -d -p 8080:80 flipkart-clone

4️⃣ Access the Application
Open your browser and visit:
http://localhost:8080

📦 Verify Running Container
docker ps

🎓 Key Docker Concepts Practiced

Dockerfile instructions (FROM, COPY, EXPOSE, CMD)
Image building and tagging
Container lifecycle management
Port mapping

Serving static content via Nginx container

👤 Author

Santhosh Kumar A
Cloud & DevOps Engineer (Fresher)
GitHub: https://github.com/SanthoshKumarDevops


