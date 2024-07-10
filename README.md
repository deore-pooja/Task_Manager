# Task_Manager

# Overview
The Task Manager is a simple Python-based application that allows users to sign up, log in, and manage their tasks. It securely stores user information and task details in text files.

# Features
User Signup: Users can create a new account by providing a username and password.
User Information: Collects additional user information such as name, address, and age.
User Login: Users can log in using their username and password.
Task Management: Users can add and view their tasks (functionality to be inferred from the script).

# Requirements
Python 3.x

# Installation
Clone the repository or download the Task_Manager.py file.
Ensure you have Python 3.x installed on your machine.

# Usage
Run the script using Python:

sh
python Task_Manager.py


# Follow the on-screen prompts to:

Sign up: Enter your username and password.

Provide additional user information: Name, address, and age.

Log in: Enter your username and password to access your tasks.

# Code Overview

# Functions

signup(): Prompts the user to enter a username and password and calls user_information() to collect additional information.

user_information(username, password): Collects additional user information and saves it to a text file named <username> task.txt.

login(): Prompts the user to enter their username and password to log in.


# File Handling

User information is stored in text files named <username> task.txt.

The user's password, name, address, and age are written to the file.
