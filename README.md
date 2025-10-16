# Welcome to your Diabecare project

## Project info

**URL**: https://preview--diabecare.lovable.app/

🧠 Overview

Developed a web application to help diabetic users:

Track daily glucose levels

Calculate insulin doses automatically

View weekly glucose trends through charts and analysis

⚙️ Tech Stack

Frontend: React.js, HTML, CSS, JavaScript

Database: SQL – for storing user readings, insulin doses, and historical data

Backend Analytics: Python – for weekly chart generation and insulin dose calculation logic

🔄 System Workflow

User enters glucose readings and meal data in the React interface.

Data is stored securely in the SQL database.

A Python module processes the data:

Calculates insulin dose

Generates weekly trend analysis

Results are sent back to the React frontend via API endpoints.

React dynamically displays results and visual charts for user insights.

🎨 Frontend Design

Built a clean, responsive, and user-friendly UI optimized for both desktop and mobile.

Used reusable React components for input forms, dashboards, and chart sections.

Implemented state management to handle dynamic data and real-time chart updates.

🔧 Challenges & Solutions
Challenge	Solution
Integrating Python analytics with React frontend	Created REST APIs to connect both systems for smooth data communication
Weekly charts not updating dynamically	Implemented React state re-fetching logic to auto-refresh charts after each entry
SQL query handling and data inconsistencies	Added validation checks and robust error handling in Python and SQL
Maintaining responsive design	Used CSS Flexbox and media queries for adaptive layouts
🚀 Learning & Impact

Combined frontend, backend, and analytics layers into one complete system.

Strengthened skills in React state management, Python integration, and SQL operations.

Learned to build modular APIs and handle cross-technology communication effectively.

Future improvements could include user authentication, scheduling reminders, and cloud deployment.

