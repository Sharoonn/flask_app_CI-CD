# Flask CI/CD Demo with Docker 🐳🚀

This project is a simple **Flask Hello World application** containerized using **Docker** and automatically built & pushed to **Docker Hub** using **GitHub Actions (CI/CD)**.

It demonstrates how modern DevOps practices work together:

- Application code (Flask)
- Containerization (Docker)
- Automation (GitHub Actions)

---

## 🔧 Tech Stack

- **Python 3**
- **Flask**
- **Docker**
- **GitHub Actions (CI/CD)**
- **Docker Hub**

---

## 📁 Project Structure

```
My_Flask_App/
│
├── app.py                 # Flask application
├── requirements.txt       # Python dependencies
├── Dockerfile              # Docker image instructions
├── .github/
│   └── workflows/
│       └── ci-cd.yml      # GitHub Actions pipeline
└── README.md
```

---

## 🚀 How the CI/CD Pipeline Works

1. Code is pushed to GitHub
2. GitHub Actions workflow is triggered
3. Docker image is built automatically
4. Image is pushed to Docker Hub
5. Image is ready to run anywhere

---

## 🐳 Run the Application Locally (Docker)

### Pull the image from Docker Hub

```bash
docker pull sharoon748/flask-ci-cd-demo
```

### Run the container

```bash
docker run -p 5000:5000 sharoon748/flask-ci-cd-demo
```

### Open in browser

```
http://localhost:5000
```

You should see:

```
Hello World!
```

---

## 📦 Build & Run Locally (Without CI/CD)

```bash
docker build -t flask-ci-cd-demo .
docker run -p 5000:5000 flask-ci-cd-demo
```

---

## 🎯 What This Project Demonstrates

- Dockerizing a Flask application
- Writing a Dockerfile
- Using GitHub Actions for CI/CD
- Automatically pushing images to Docker Hub
- Basic DevOps workflow

---

## 🔮 Future Improvements

- Add automated tests
- Add Docker Compose
- Deploy to cloud (AWS / DigitalOcean)
- Use a production WSGI server (Gunicorn)
- Add environment variables

---

## 👤 Author

**Sharoon**  
IT Support Engineer | DevOps & Software Engineering Learner

---

⭐ If you like this project, give it a star on GitHub!
