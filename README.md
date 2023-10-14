******************************************************************************************************************************************************************************************************************************************************************************
>>>>>Deatils for "Username-Password Project using python":

This Python project demonstrates the use of various fundamental programming concepts such as variables, conditional statements (if-else), loops (while), break statements, methods, and functions to create a simple username and password validation system. The project simulates a basic login system with multiple validation checks.

Project Overview

The project includes the following components:

- A list of valid email domains to check if the entered username is valid.
- A function `requestUsername` to allow the user to input their username up to 5 times, locking the account after unsuccessful attempts.
- A function `requestPassword` to allow the user to input their password up to 5 times, locking the account after unsuccessful attempts.
- The main code to initiate the program and prompt the user for their username and password.

Valid Email Domains

The project begins by defining a list of 100 valid email domains. You can add more domains to the list as needed.

valid_domains = (
    # List of valid email domains (add more if needed)
    "gmail.com",
    "yahoo.com",
    "hotmail.com",
    # ...
)

Usage

To run the program, execute the Python script. It will display a welcome message and prompt you to enter your username and password.

- If the username is not valid (doesn't end with a valid domain), the program will allow you to re-enter the username up to 5 times.
- If the password is not valid (less than 8 characters or more than 16 characters), the program will allow you to re-enter the password up to 5 times.
- If both the username and password are valid, you will receive a "Welcome to SBI" message.

Account Locking

If the user exceeds the maximum number of attempts (5) for either the username or password, the account will be locked, and a message to contact the administrator for unlocking will be displayed.

Contributing

Contributions to this project are welcome. If you have any improvements or feature suggestions, please feel free to submit a pull request.


Thank you for using the Username-Password Project using Python. Enjoy exploring and learning from this basic Python project!
******************************************************************************************************************************************************************************************************************************************************************************
