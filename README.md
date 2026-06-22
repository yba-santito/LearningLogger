# LearningLogger

A digital note-taking web application for logging topics you're learning about and reflecting on key insights.

## Overview

LearningLogger is a web application built with Django that helps users track their learning journey. It provides a clean, minimal interface for creating journal entries about new topics, making it easy to revisit and reflect on what you've learned over time.

## Features

- **User Authentication** – Secure login and registration system
- **Topic Journaling** – Add and manage learning topics
- **Reflection Entries** – Write and save insights for each topic
- **Clean UI** – Minimalistic design powered by Bootstrap
- **Persistent Storage** – SQLite database for reliable data storage

## Tech Stack

| Component    | Technology                         |
|--------------|------------------------------------|
| **Backend**  | Python, Django                     |
| **Frontend** | HTML, Bootstrap                    |
| **Database** | SQLite (default)                   |
| **Environment** | Python 3.x                      |

## Project Structure
LearningLogger/
├── learnin_log/ # Django project settings
│ └── settings.py # Project configuration
├── learnin_logs/ # Main app for learning topics and entries
├── users/ # User authentication app
├── db.sqlite3 # SQLite database file
├── manage.py # Django management script
├── requirements.txt # Python dependencies
└── README.md # Project documentation



## Getting Started

### Prerequisites

- Python 3.x installed on your system
- pip (Python package manager)

### 1. Clone the Repository

```bash
git clone https://github.com/yba-santito/LearningLogger.git
cd LearningLogger
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
python manage.py migrate
```
### 5. Start the Development Server
```bash
python manage.py runserver
```
The application will be available at http://127.0.0.1:8000/.

### 6. Create a Superuser (Optional)
To access the admin panel at /admin, create an admin account:

```bash

python manage.py createsuperuser

```
### Usage
Register a new account or log in with existing credentials

Add topics you're currently learning about

Write entries for each topic to capture insights and reflections

Review your learning history anytime

### Future Improvements
Search and filter functionality for topics and entries

Rich text editing for entries

Tagging system for better organization

Public/private toggle for entries

Export journal as PDF or Markdown

### License
This project is open source and available under the MIT License.

### Acknowledgements
Built with the Django framework and Bootstrap for a clean, responsive user interface.
