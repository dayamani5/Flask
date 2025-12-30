Flask Web Application

This is a basic Flask web application that demonstrates core Flask concepts such as routing, templates, sessions, cookies, file upload, flash messages, and error handling.

Features

Home page

Dynamic route with URL parameters

Login and Logout using sessions

Dashboard page

Flash messages for user feedback

Set and get cookies

File upload functionality

Custom 404 error page

Technologies Used

Python

Flask

HTML (Templates)

Werkzeug

OS module

Project Structure
flask/
│
├── app.py
├── uploads/
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── dashboard.html
│   ├── upload.html
│   └── 404.html
│
└── README.md

Setup and Installation

Clone the repository

git clone <your-repo-url>
cd flask


Create a virtual environment (optional but recommended)

python -m venv venv
venv\Scripts\activate


Install Flask

pip install flask


Run the application

python app.py


Open in browser

http://127.0.0.1:5000/

Routes Explanation

/ → Home page

/hello/<name> → Displays greeting message

/login → Login page

/dashboard → Dashboard after login

/logout → Logout user

/set-cookie → Sets a cookie

/get-cookie → Reads cookie value

/upload → File upload page

File Upload

Uploaded files are stored in the uploads/ folder

File names are secured using secure_filename()

Session and Cookies

Sessions are used to store logged-in user information

Cookies are used to store course information

Error Handling

Custom 404 Page Not Found error handler is implemented

Notes

Make sure the uploads folder exists (it is created automatically if not present)

Debug mode is enabled for development

Author

Dayamani
B.Tech CSE (AI & ML)
Flask Beginner Project
