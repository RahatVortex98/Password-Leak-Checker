# Password Checker

This is a simple Flask application that checks if a password has been compromised by querying the Have I Been Pwned API. It provides a user-friendly interface for users to input their passwords and receive feedback on whether their passwords have been leaked in data breaches.

## Project Structure


## Requirements

- Python 3.x
- Flask
- Requests

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory:

   ```bash
   cd D:\Password_checker


Create a virtual environment (if not already created):

python -m venv .venv

For Windows:
.venv\Scripts\activate

Install the required packages:
pip install Flask requests

To run the application, execute the following command in the terminal:
python checkmypass.py


Once the application is running, open your web browser and navigate to:
http://127.0.0.1:5000/


How It Works
The user inputs a password into the form.
The password is hashed using SHA-1.
The first 5 characters of the hash are sent to the Have I Been Pwned API to check for leaks.
The application returns the number of times the password has been found in breaches, providing feedback on whether the password should be changed.



### Instructions to Create and Update the README

1. **Create a `README.md` File**:
   - If you haven't already, create a file named `README.md` in your project directory.

2. **Copy and Paste the Content**:
   - Copy the above Markdown content and paste it into the `README.md` file.

3. **Save the File**:
   - Save your changes.

Feel free to modify any section to better suit your project or add more information as needed!

