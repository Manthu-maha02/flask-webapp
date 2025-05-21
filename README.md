# Flask Web App Setup using GitHub Codespaces

## 🔧 Project Overview
This project demonstrates how to set up a simple Flask web application using GitHub Codespaces. It includes:
- Flask Framework
- Python Routing
- HTML Templates
- GitHub Codespace integration

---

## 📁 Folder Structure
```
project-root/
│
├── templates/
│   └── index.html
├── main.py
└── README.md
```

---

## 🚀 Getting Started

### 1. Set Up GitHub Codespace and creating a environment
- Open this repository in GitHub.
- Click **Code > Open with Codespaces** > **Create codespace on main**.
- GitHub will launch a cloud-based dev environment with pre-installed Python.
- open terminal and run
```bash
  python -m venv venv #create a virtual environment
  venv\Scripts\Activate #open the virtual environment
```

### 2. Install Requirements
In the termial run:

```bash
pip install -r requirements.txt
```

---

## Running the Flask App

### Option 1: Run directly
```bash
python main.py
```

### Option 2: Using Flask CLI

```bash
export FLASK_APP=main.py  # use set FLASK_APP=main.py on Windows
flask run
```

Your app will be available at:  
📍 `http://127.0.0.1:5000`

---
You can close the environment using
```
deactivate
```
