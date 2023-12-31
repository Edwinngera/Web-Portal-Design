# Flask Web Portal
The Flask Web Portal is a simple web application that allows users to register, log in, and manage their profiles. It is built using the Flask web framework and uses Flask-WTF for form handling and MySQL for data storage.

## Features
User registration: Users can create an account by providing a unique username and password.
User login: Registered users can log in to access their profiles.
Profile management: Logged-in users can update their profile information, including changing their password.
Logout: Users can log out from their accounts to securely end their session.

## Prerequisites
Before running the application, ensure you have the following installed:

## Python (3.6 or higher)
pip (Python package manager)
MySQL server (make sure you have the necessary database and user credentials)
# Installation
Clone the repository:
git clone https://github.com/your-username/flask-web-portal.git
cd flask-web-portal
# Install the required packages:
pip install -r requirements.txt
## Set up the database:
Create a MySQL database for the web portal and a table to store user information. Use the provided SQL code in the project's root directory to create the table.
Update the MySQL configuration in App.py to match your MySQL host, username, password, and database.
Usage
To run the Flask web application, execute the following command in your terminal:
python App.py
The application will start running on http://127.0.0.1:5000/. Open this URL in your web browser to access the home page