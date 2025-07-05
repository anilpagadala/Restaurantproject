# 🍽️ Restaurant Website

A responsive restaurant website built with **Django** and **Bootstrap**.  
It features core pages like Home, About, Menu, Book a Table, and Feedback, providing a smooth user experience and clean UI.

---

## 🔧 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default)

---

## 🚀 Features

- 🏠 **Home Page** – Welcome section with responsive layout.
- 📖 **About Page** – Brief info about the restaurant.
- 🍽️ **Menu Page** – Displays list of food and drinks.
- 📅 **Book Table Page** – Users can reserve tables online.
- 💬 **Feedback Section** – Form to collect visitor feedback.
- 📱 **Responsive Design** – Mobile-friendly and modern UI.

---

## 📂 Folder Structure
```text
Resturant/
├── .venv/
├── manage.py
├── db.sqlite3
├── requirements.txt
├── Media/
├── Static/
├── Template/
├── Base_App/
├── Resturant_Project/
├── .gitignore
└── README.md

```
---

## ⚙️ Getting Started

Follow the steps below to run the project locally.

## Clone the repository

```bash
git clone https://github.com/anilpagadala/Resturantproject.git
cd Restaurantproject
```
## Create a virtual environment
```bash
python -m venv .venv
```
## Activate the environment
### Windows:
```bash
.venv\Scripts\activate
```

### Linux/macOS:
```bash
source .venv/bin/activate
```

## Install dependencies
```bash
pip install -r requirements.txt
```

## Apply migrations
```bash
python manage.py migrate
```
## Run the development server
```bash
python manage.py runserver
```
## Open in browser
```bash
http://127.0.0.1:8000/
```
