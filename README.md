# 🛍️ Shop♡Ease: AI-Powered E-Commerce Platform

Welcome to the **Shop♡Ease** master repository. This project is a full-stack e-commerce solution that leverages Machine Learning to provide intelligent fashion recommendations based on H&M dataset insights.

---
website: https://hm-shop-hh7w.onrender.com/  ; open until : 28/2/2026

## 👥 About the Authors

We are a team of Engineering Students from the **National School of Applied Sciences (ENSA), Fès**, specializing in Software Engineering and Artificial Intelligence. This project is the culmination of our collaborative efforts to bridge the gap between modern E-commerce and Machine Learning.

| Name |
| --- | 
| **Malak Bensaid** | 
| **Hajar Slimani** | 
| **Douaa Berrahmo** |
| **Hachem Squalli ElHoussaini** |

### 🎓 Academic Context

* **Institution:** ENSA Fès (École Nationale des Sciences Appliquées)
* **Year:** 2026
* **Project:** ShopEase Intelligent E-commerce Solution
---

https://github.com/user-attachments/assets/6f0b8d24-96aa-498d-90a1-ae217700d6d6

---

## 🏗️ Project Structure

This repository uses **Git Submodules** to manage the two main components:

* **`/frontend`**: [Angular 17 Application](https://www.google.com/search?q=https://github.com/your-username/Front-End-ML-e-commerce) - The user interface and shopping experience.
* **`/backend`**: [FastAPI AI Engine](https://www.google.com/search?q=https://github.com/your-username/H-M-Backend-Recommendation-System-Model) - The REST API, Database, and Recommendation Model.

---

## 🚀 Getting Started (For Team Members)

Since this project uses submodules, a standard `git clone` will leave the folders empty. Use these commands:

### 1. Cloning the Project

```bash
git clone --recursive https://github.com/your-username/ShopEase-FullStack.git
cd ShopEase-FullStack

```

### 2. Running the Backend (AI & API)

```bash
cd backend
# Follow the README inside /backend to setup your .env and venv
python main.py

```

### 3. Running the Frontend (UI)

```bash
cd frontend
# Follow the README inside /frontend to install npm packages
ng serve

```

---

## 📋 Integration Details

| Feature | Implementation |
| --- | --- |
| **API URL** | Frontend calls `http://127.0.0.1:8000/api` |
| **AI Logic** | Euclidean Distance on `model_vectors.pkl` |
| **Images** | Served statically by FastAPI from `db/hm_lean_project` |
| **Authentication** | JWT Bearer Tokens stored in LocalStorage |

---

### 🛠 Maintenance Commands

* **To pull latest changes for all parts:**
`git submodule update --remote --merge`
* **To commit a change in a submodule:**
You must commit inside the specific folder (`frontend` or `backend`) **first**, push it, then commit the change in this parent folder.


