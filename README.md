🧑‍💻 Chandra Mouli S T – Developer Portfolio

This repository contains my personal portfolio website developed using Django, HTML5, CSS3, and JavaScript.
It highlights my projects, skills, and experience as a software engineer specializing in Python, web development, and intelligent systems.

🚀 Features

🎨 Responsive Design – Works smoothly across devices (mobile, tablet, desktop).

⚡ Dynamic Sections – Projects, Skills, About Me, and Contact Form integrated with Django templates.

🌗 Light/Dark Mode toggle for user-friendly accessibility.

🔍 Project Filtering & Search – View projects by tags (Web, UI, JS).

📬 Contact Form Layout – Ready to integrate with backend email handling or APIs.

🧱 Clean Code Structure – Organized static files and templates for easy modification.

🛠️ Tech Stack

Frontend: HTML5, CSS3, JavaScript (ES6)

Backend: Python

Web Framework: Django

Tools: VS Code, Git, Python 3.12

Version Control: Git & GitHub

🌟 Future Enhancements

🧠 AI-Powered Chatbot Integration – Add a portfolio assistant to guide visitors interactively.

💼 Admin Panel Customization – Manage projects, blogs, and contact messages directly from the backend.

🧩 Blog Section – Share insights, tutorials, and updates related to software development and AI.

☁️ Cloud Deployment – Host on AWS, Render, or Vercel for enhanced performance and uptime.

🔐 Secure Contact Form – Integrate email functionality with CAPTCHA and spam protection.

📱 Progressive Web App (PWA) – Enable installation of the portfolio as a mobile app.

🌍 Multilingual Support – Add internationalization (i18n) for global accessibility.


🧩 Development Process

Here’s the complete process followed to design and build this portfolio:

1️⃣ Project Setup

Installed Python 3.12 and Django framework using

#pip install django


Created a new Django project:

#django-admin startproject portfolio


Added a new Django app for portfolio sections:

#python manage.py startapp main

2️⃣ Project Configuration

Add import os in Setting.py @top

Registered the app (main) in settings.py under INSTALLED_APPS.
#INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app' -->Here 
]

Configured STATICFILES_DIRS and TEMPLATES directories for easy access to HTML and CSS files.
#STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'app', 'static'),
]

Set up the project’s urls.py and included app-level URLs for modular navigation.
from django.contrib import admin
from django.urls import path
from app import views -->Import and include sub apps/views here.

urlpatterns = [
    path('admin/', admin.site.urls),
    #add views router along with function names here 
]

3️⃣ Template & Static File Integration

Created reusable templates ( index.html).
#optional -->you can create it as Multi Html pages like(Home.html,Project.html ..ect)
Linked static files using Django’s {% load static %} tag.

Integrated CSS3 for responsive design and JavaScript for interactivity.

4️⃣ Portfolio Sections

Home Page: Added a professional introduction with name, title, and dynamic background.

About Me: Highlighted education, role at AdminDroid, and technology expertise.

Projects: Displayed Django, Python, and AI-based works (e.g., Healthcare Chatbot, Doctor Recommendation System).

Skills: Represented technical strengths in Python, Django , Sql and Web Development.

Contact Form: Designed an interactive layout with placeholders for email backend integration.

5️⃣ Frontend Enhancements

Implemented light/dark mode toggle using JavaScript and CSS variables.

Added hover animations and smooth transitions for UI elements.

Optimized layout with Flexbox and Grid for responsive alignment.

6️⃣ Version Control

Initialized a local Git repository:

git init
git add .
git commit -m "Initial portfolio setup"


Pushed the project to GitHub for version tracking and showcasing.

7️⃣ Testing & Optimization

Tested across devices (mobile, tablet, desktop) for full responsiveness.

Validated all HTML and CSS using W3C validators.

Minified assets and improved page load performance.

8️⃣ Deployment (Upcoming)

Preparing deployment using Render or Vercel with Django backend.

Future plan to integrate domain name and SSL for production-level hosting.

🏁 Outcome

This portfolio demonstrates:

Strong command of Django and frontend technologies

Ability to build end-to-end responsive web applications

A clear presentation of skills, certifications, and projects

🎓 Certifications

🏅 Pega Certified Senior System Architect (CSSA) – Completed in August 2024

📫 Author Information

👤 Name: Chandra Mouli S T

   College:M Kumarasamy College of Engineering
   
   Deparment:B.Tech Information Technology
   
💼 Role: Python FullStack Developer Trainee (Present) 
          System Architect conducte by Talentsprint ( March - August 2024)

📧 Email: mouligavaaskar@gmail.com

🔗 LinkedIn: linkedin.com/in/chandramouli-st




