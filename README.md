# portal
The CUTM Result Portal is a web application designed to help students and administrators view and manage academic results efficiently. This repository contains the codebase for the portal, including frontend templates, backend logic, and database configurations.

Live Demo https://cutm-new-result-portal-2-0.onrender.com/

Features
Student Result Display: Students can view their academic results by entering their registration number and selecting the semester.
Admin Panel: Administrators can log in to access the admin panel, where they can manage student records, update results, and perform other administrative tasks.
Responsive Design: The portal is built using Bootstrap CSS, ensuring responsiveness across various devices and screen sizes.
Dynamic Content: Results are dynamically loaded and displayed based on user input, providing a seamless user experience.
Security: Authentication and authorization mechanisms are implemented to ensure that only authorized users can access sensitive functionalities.
Technologies Used
Backend
Flask: Python web framework used for building the backend of the application.
SQLite: SQL database engine used for storing and managing relational data.
MongoDB: NoSQL document-oriented database used for storing user input data.
dotenv: Python library for parsing environment variables from a .env file.
PyMongo: Python driver for working with MongoDB.
Datetime: Python module for working with dates and times.
Jinja: Templating engine for Python used for generating dynamic HTML content.
Frontend
HTML/CSS: Used for frontend structure and styling.
Bootstrap 5: Frontend framework for designing responsive and mobile-first web pages.
JavaScript: Programming language for adding interactivity to web pages.
Installation
Clone the repository: git clone https://github.com/minnukota381/CUTM-Result-Portal.git
Install dependencies: pip install -r requirements.txt
Run the application: python app.py
Access the portal in your web browser at http://localhost:5000
Usage
To access the student result portal, visit the homepage and enter your registration number and select the semester.
To log in as an admin, navigate to the admin login page and enter your credentials.
Once logged in, you can access the admin panel to manage student records, update results, etc.
