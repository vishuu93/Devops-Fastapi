# 🚀 FastAPI Backend with Automated Testing & CI/CD

Welcome to the **FastAPI Backend Automation Project**! This project sets up a lightweight FastAPI server with automated API testing using `pytest` and `requests`, seamlessly integrated with GitHub Actions for continuous testing. 💡

## 📌 Features
✅ FastAPI server with basic mathematical operations (Add, Subtract, Multiply)  
✅ Automated API testing using `pytest` & `requests`  
✅ Continuous Integration (CI) with GitHub Actions  
✅ Easy setup and execution in **VS Code on Windows**  
✅ Scalable foundation for real-world API development 🔥  

---

## 📦 Setup & Installation
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/vishuu93/Devops-Fastapi.git
 cd Devops-Fastapi
```

### 2️⃣ Set Up a Virtual Environment (Windows)
```sh
 python -m venv venv
 venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```sh
 pip install fastapi uvicorn pytest requests
```

---

## 🚀 Running the FastAPI Server
Start the FastAPI server by running:
```sh
 python apiserver.py
```
The server will be available at: **http://localhost:8000** 🔗

### Test Endpoints:
- ➕ `GET /add/2/2` → `{ "result": 4 }`
- ➖ `GET /subtract/5/3` → `{ "result": 2 }`
- ✖ `GET /multiply/2/3` → `{ "result": 6 }`

You can also test these endpoints interactively using the **Swagger UI** at:  
📌 **http://localhost:8000/docs**  

---

## 🧪 Running Automated Tests
### 1️⃣ Run Basic Tests
```sh
 python testAutomation.py
```

### 2️⃣ Run Tests with Pytest
```sh
 pytest testAutomationPytest.py
```

---

## 🤖 GitHub Actions CI/CD Integration
Automated tests run **on every push and pull request** in the `main` branch! ✅  

### 📂 Workflow File: `.github/workflows/test.yml`
- 🚀 Installs dependencies
- 🛠️ Starts the FastAPI server
- 📊 Runs tests with `pytest`

### 🔍 View CI/CD Pipeline:
Check your **GitHub Actions** tab to see real-time test results! 🎯  

---

## 🔥 Expanding the Project
🚀 Want to make it even more powerful? Try adding:
- **Database integration** (PostgreSQL, MongoDB)
- **Authentication & authorization** (JWT, OAuth2)
- **Performance testing** (`locust.io`, `pytest-benchmark`)
- **Logging & monitoring** (ELK Stack, CloudWatch)

---

Happy Coding! 🚀🎯
