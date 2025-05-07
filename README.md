# 🚀 Dockerized Django App by Simran

This project is a basic Django application that has been dockerized and deployed on an AWS EC2 instance. It is part of my hands-on DevOps learning journey using [Abhishek Veermalla's DevOps Zero to Hero](https://www.youtube.com/playlist?list=PLdpzxOOAlwvIKMhk8WhzN1pYoJ1YU8Csa) YouTube series.

---

## 🔍 Agenda

- Learn DevOps through real-world projects
- Understand containerization with Docker
- Deploy live applications on cloud environments (AWS)

---

## 📦 Tech Stack

- Django (Python)
- Docker
- AWS EC2
- Docker Hub

---

## 🛠️ Steps to Run the App

1. **Build the Docker Image**

```bash
docker build -t simrangagrawal/python-web-app .
```

2. **Run the Docker Container**

```bash
docker run -d -p 8000:8000 simrangagrawal/python-web-app
```

3. Visit in your browser: `http://<EC2_PUBLIC_IP>:8000/demo/`

---

## 🌐 Live Preview

**[Click to View](http://52.66.235.252:8000/demo/)**  
⚠️ Note: Instance should be running to access

---

## 🐳 Docker Hub

[Docker Hub Image](https://hub.docker.com/r/simranagrawal/python-web-app)


---

## 📝 Credits

Base app structure referenced from [Abhishek Veermalla's GitHub](https://github.com/abhishekveermalla).  
Customized, Dockerized, and Deployed by [Simran Agrawal](https://github.com/simranGagrawal).

---

💡 *Learning in public, one container at a time.*
