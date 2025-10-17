🏋️‍♀️ Fitness Guide — Full-Stack Flask Web Application

Fitness Guide is a modern, interactive fitness and wellness web application built with Flask (Python), HTML, CSS, JavaScript, and SQLite.
It helps users stay motivated and maintain a healthy lifestyle through personalized dashboards, workout plans, diet tracking, and motivational content.

🚀 Key Features

🔐 User Authentication – Secure login with username and password

🏠 Personalized Dashboard – Displays motivational quotes and navigation links

🧘 Workout Page – Yoga, Strength, and Cardio categories with videos and guides

🥗 Weekly Diet Plan – Healthy meal suggestions with visuals and nutrition tips

✅ Habit Tracker – Add, edit, and track daily habits for progress consistency

💬 Motivational Thoughts – Inspiring quotes to boost positivity and focus

🛠️ Tech Stack

Frontend: HTML5, CSS3, JavaScript

Backend: Python (Flask Framework)

Database: SQLite

Styling: Custom CSS with a fitness-inspired theme

📂 Project Structure
fitness_guide/
│── app.py                 # Main Flask application  
│── fitness_guide.db       # SQLite database file  
│── static/                # CSS, images, and assets  
│── templates/             # HTML templates for all pages  
│── README.md              # Project documentation  

⚙️ How to Run the Project

Follow these steps to set up and run the project locally:

1. Clone the Repository
git clone https://github.com/<your-username>/fitness_guide.git
cd fitness_guide

2. Set Up a Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate     # On Windows  
# OR  
source venv/bin/activate  # On macOS/Linux

3. Install Dependencies
pip install flask bcrypt

4. Run the Application
python app.py


or

flask run

5. Open in Browser

Go to:
👉 http://127.0.0.1:5000

🧠 Notes

Default login credentials (if applicable):

Username: Shubhashree Bhosale

Password: fitness

The SQLite database (fitness_guide.db) is automatically created when the app runs for the first time.

You can customize motivational quotes, images, and habit categories inside the /templates and /static folders.

💡 Overview

This project demonstrates a complete full-stack fitness application featuring authentication, database interaction, and responsive design.
It’s ideal for portfolio showcases, academic projects, and learning Flask-based web development.
