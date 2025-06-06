# 📝 TaskVault

**TaskVault** is a minimal and elegant task management web application built using Python and Flask. It allows users to add, complete, and delete tasks in a simple and intuitive interface.

---

## 🚀 Features

* Add new tasks
* Mark tasks as completed
* Delete tasks
* Tasks sorted by creation time (newest first)
* Simple and responsive UI

---

## 💠 Tech Stack

* **Backend:** Flask (Python), Flask-SQLAlchemy (ORM)
* **Frontend:** HTML, CSS (with Jinja2 templates)
* **Database:** SQLite (local)

---

## 📁 Project Structure

```
taskvault/
├── app.py               # Main Flask app
├── models.py            # SQLAlchemy model for Task
├── requirements.txt     # Python dependencies
├── templates/           # HTML templates
│   ├── base.html
│   └── index.html
├── static/              # CSS files
│   └── style.css
├── database.db          # Auto-created SQLite database
└── .gitignore           # Git ignored files



## ✅ Setup Instructions

### 1. Clone the repository


git clone https://github.com/your-username/taskvault.git
cd taskvault
```

### 2. Create and activate a virtual environment


# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
pip install -r requirements.txt



### 4. Run the Flask app
python app.py


Then open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🧐 Future Improvements

* User authentication (Flask-Login)
* Task categories and tags
* REST API version
* Deployment on Render / Railway / Heroku

