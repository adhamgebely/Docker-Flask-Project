# Dockerized Flask Demo 🐳

A simple project to demonstrate running a Flask web application inside a Docker container. The goal is to build a minimal Flask app, containerize it, and run it locally.

## 📂 Project Structure

Docker-Flask-Project/
 ├── hello.py
 ├── requirements.txt
 └── Dockerfile

## ⚙️ How to Run
### 1️⃣ Clone the Repository 
``` bash 
git clone https://github.com/adhamgebely/Docker-Flask-Project.git
cd Docker-Flask-Project
```
### 2️⃣ Build the Docker Image
``` bash
docker build -t flask-demo .
```
### 3️⃣ Run the Container
``` bash
docker run -d -p 5000:5000 flask-demo
```
### 4️⃣ Open the App 
In your browser, go to 👉 http://localhost:5000
![alt text](<Screenshot 2025-10-02 173909.png>)