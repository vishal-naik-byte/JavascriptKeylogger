# Project: JavaScript Keylogger

## Overview

JavaScript Keylogger is a project aimed at demonstrating how keylogging can be done through JavaScript and integrated with a server-side application using Python and Flask. This project is designed for educational purposes to illustrate the security risks associated with malicious scripts and how to detect and prevent them.

## Requirements

To run this project, you will need:

**Python 3.12**: The latest version of Python. Download it from Python.org.

**Flask**: A lightweight WSGI web application framework for Python. Install it using pip install Flask.

**Code Editor**: Any code editor, such as Visual Studio Code, Sublime Text, or Atom.

Download Visual Studio Code.

**WAMP or XAMPP Server**: A local server environment that can be used for testing purposes. Download WAMP or XAMPP.

## Installation

1. **Clone the Repository**:
git clone https://github.com/YourUsername/Project_JavascriptKeylogger.git
cd Project_JavascriptKeylogger

2. **Set Up Python Environment**:Ensure you have Python 3.12 installed. Set up a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # For Unix or MacOS
venv\Scripts\activate     # For Windows

3. **Install Flask**:Install Flask and any other necessary Python packages:

pip install Flask

4. **Set Up the Server**:Install and configure WAMP or XAMPP server on your local machine. This will be used to host the JavaScript keylogger and communicate with the Python Flask application.

5. **Run the Flask Application**:Start the Flask server:
python app.py

6. **Open in Browser**:Open your web browser and go to http://localhost:5000 to see the keylogger in action.

## Usage

This project demonstrates:

How JavaScript can be used to capture keystrokes.

How to send the captured data to a server-side Python application using Flask.

How to analyze and understand keylogger behavior to enhance security awareness.

**Note**: This keylogger is meant for educational purposes only. It is illegal to use a keylogger on any system without the owner's explicit permission.

## Contributing

Feel free to contribute to this project by submitting pull requests or suggesting new features and improvements.
