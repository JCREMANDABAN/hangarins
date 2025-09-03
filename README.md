# ✨ HANGARIN – Task & To-Do Manager

Welcome to **Hangarin**, a simple and effective web app designed to help you stay organized and focused. 🧠📋

---

## 📝 What is Hangarin?

**Hangarin** is a minimal yet powerful task management application built with **Django**. It allows users to:

✅ Manage their daily to-dos  
✅ Set task priorities  
✅ Add personal notes  
✅ Categorize tasks  
✅ Break big goals into manageable subtasks

---

## 🚀 Features

Here’s what Hangarin offers:

- 🔥 **Priority Section** – Manage urgency: High, Medium, Low, Critical, Optional  
- 📂 **Category Section** – Group tasks: Work, School, Personal, Finance, Projects  
- ✅ **Task Section** – Title, description, deadlines, and status tracking  
- 🗒️ **Note Section** – Add detailed notes to your tasks  
- 🧩 **SubTask Section** – Break down large tasks into smaller chunks  

---

## ⚙️ Tech Stack

- 🐍 Python 3
- 🌐 Django Framework
- 🎲 Faker (for dummy data generation)
- 🛠️ Django Admin for management
- ☁️ PythonAnywhere for deployment

---

## 📦 Installation

Clone the repository and set up the project locally:

```bash
git clone https://github.com/your-username/hangarin.git
cd hangarin_project
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
