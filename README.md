🥗 Food Intelligence – Advanced Nutrition Dashboard
📌 Overview

Food Intelligence is an advanced, interactive nutrition dashboard built using pure HTML, CSS, and JavaScript.

It helps users analyze their body metrics and generate personalized nutrition insights in real time.

This project demonstrates:

Frontend logic design

Interactive UI engineering

User input validation

Dynamic calculations

Responsive dashboard layout

Clean UI/UX principles

It runs entirely in the browser — no backend or installation required.

🎯 Purpose of This Project

The goal of this dashboard is to:

Provide quick health insights

Calculate BMI

Estimate calorie requirements

Suggest protein intake

Recommend water consumption

Generate goal-based meal suggestions

Demonstrate interactive frontend development

This project is designed as a foundational step toward building a larger AI-powered nutrition platform.

🧠 Core Functionalities
1️⃣ Editable User Profile

Users can input:

Name

Weight

Height

Goal (Maintain / Lose / Gain)

The dashboard dynamically updates the welcome message and calculations.

2️⃣ BMI Calculator

BMI is calculated using:

BMI = weight (kg) / (height in meters)^2


The result updates instantly after clicking Calculate.

3️⃣ Calorie Estimation Engine

Daily calorie needs are estimated using a simplified formula:

Base Calories = Weight × 30


Then adjusted by goal:

Lose Weight → -300 kcal

Maintain → Base

Gain Weight → +300 kcal

4️⃣ Protein Recommendation

Protein intake is calculated as:

Protein = Weight × 1.2 grams


This supports muscle maintenance and growth.

5️⃣ Water Intake Calculator

Water intake is calculated as:

Water = Weight × 0.035 liters


Includes:

+250ml interactive button

Reset functionality

Animated progress bar

6️⃣ Goal-Based Meal Plan Generator

Based on selected goal:

Maintain

Oats & Fruits

Roti + Dal + Sabzi

Light Rice & Veggies

Lose Weight

Boiled Eggs & Fruits

Grilled Vegetables + Salad

Soup & Lean Protein

Gain Weight

Paneer & Nuts

Rice + Dal + Sabzi

Milk + Banana Shake

The meal plan updates dynamically.

🎨 UI & Design Features

Dark premium gradient background

Glassmorphism card design

Soft shadows

Animated progress bars

Responsive CSS grid layout

Smooth hover transitions

Modern typography

The layout adapts to desktop and mobile screens.

🛠 Technologies Used

HTML5

CSS3

Vanilla JavaScript

No frameworks
No build tools
No dependencies
No installation required

🚀 How To Run

Clone the repository:

git clone https://github.com/yourusername/food-intelligence-dashboard.git


Open the project folder.

Double-click:

index.html


The dashboard runs immediately in your browser.

🌍 Deployment

This project can be deployed easily using:

GitHub Pages

Netlify

Vercel

Any static hosting service

No server setup required.

📁 Project Structure
Food-Intelligence/
│
├── index.html
└── README.md


Simple and lightweight.

🔐 Limitations

Does not store user data

No backend integration

Uses simplified nutrition formulas

No database

No authentication system

This version focuses on frontend logic and UI.

🔮 Future Roadmap

Planned improvements:

Macro distribution charts (Pie / Bar graphs)

Weekly tracking dashboard

Local storage for saving user data

Export nutrition report as PDF

Multiple profile support

AI-based food recommendation system

Mobile-first UI redesign

Backend integration with real nutrition database

💡 Learning Outcomes

Through this project, the following skills are demonstrated:

DOM manipulation

Event handling

Dynamic UI updates

Progress bar animation

Responsive layout design

User experience structuring

Clean code organization

📌 Version

Current Version: 1.0

👨‍💻 Author

Developed as a practical frontend project for building interactive web dashboards and exploring nutrition analytics concepts.

📄 License

This project is open-source and available for educational and learning purposes.
