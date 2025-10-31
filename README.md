# Smart Course Selector

A Django web application that helps students choose the most suitable course or specialization based on their interests, strengths, and previous academic performance.

---

## Overview

This project was developed during my **second year** of the BSc (Hons) Computer Science degree.  
The idea was to design a simple recommendation system that could assist students when deciding what course or path to take next.

The system collects a few details about the user — such as interests, subject preferences, and academic background — and then generates ranked course suggestions using a basic scoring model.

---

## Features

- 🧭 Interactive web interface for students to enter their details  
- 🧮 Simple scoring algorithm to rank courses  
- 💾 SQLite database for storing course data and user inputs  
- ⚙️ Admin dashboard to manage course information  
- 📱 Responsive layout (works on desktop and mobile)

---

## Tech Stack

- **Language:** Python  
- **Framework:** Django  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, a bit of JavaScript  
- **Tools:** Git, GitHub, VS Code

---

## Getting Started

If you want to run the project locally:

```bash
# 1. Clone the repo
git clone https://github.com/MurtazaAliCS/Smart_Course_Selector.git
cd Smart_Course_Selector

# 2. Set up a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate    # on Windows
# or source venv/bin/activate  # on macOS/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver
