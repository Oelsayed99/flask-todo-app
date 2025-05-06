# 📝 Flask To-Do App

A **simple yet functional To-Do list web app** built using **Python Flask** and **SQLite**, designed to help you manage daily tasks. This project demonstrates the basic CRUD (Create, Read, Update, Delete) operations using a lightweight tech stack — perfect for beginners exploring Flask and backend development.

🌐 **Live Demo:**  
[https://flaskcrudapptodolist-a663f04498c2.herokuapp.com/](https://flaskcrudapptodolist-a663f04498c2.herokuapp.com/)

---

## 🚀 Features

- ✅ Add tasks
- ✏️ Update existing tasks
- ❌ Delete tasks
- 📆 View when a task was added
- 🗃️ All data is stored in a local SQLite database
- ☁️ Deployed on Heroku

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Database:** SQLite  
- **Frontend:** HTML, CSS (basic styling)  
- **Deployment:** Heroku  

---

## 📂 Project Structure

flask-todo-app/
│
├── static/ # CSS and static files
├── templates/ # HTML templates (Jinja2)
│ ├── base.html
│ └── index.html
│ └── update.html
│
├── app.py # Main Flask app
├── requirements.txt # Python dependencies
├── Procfile # For Heroku deployment
└── README.md # This file

## 🚀 Getting Started Locally

```bash
# Clone the repository
git clone https://github.com/your-username/Flask/flask-todo-app.git
cd flask-todo-app

# Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows use: .env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```
Open your browser at http://127.0.0.1:5000 to view the app.

📄 License
This project is open-source and free to use.

Let me know if you'd like a version with screenshots, GitHub badges, or setup instructions for Heroku too.
