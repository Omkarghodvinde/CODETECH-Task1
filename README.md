*Name:* OMKAR BALKRUSHNA GHODVINDE 

*Company:* CODETECH IT SOLUTIONS 

*ID:* CT12DS1851

*Domain:* CYBER SECURITY AND ETHICAL HACKING 

*Duration:* JULY to SEPTEMBER 2024

*Mentor:* MUZAMMIL AHMED




**OVERVIEW OF THE PROJECT :-**



*Project:* Password Strength Verifier

*Objective:* Create a function that evaluates the strength of a password and provides feedback on how to improve it.

*Functionalities:*

1. *Minimum Length:* Checks if the password has at least 8 characters.
2. *Character Diversity:* Checks if the password includes:
    - At least one lowercase letter.
    - At least one uppercase letter.
    - At least one digit.
    - At least one special character (@#$%^&+=).
3. *Common Patterns:* Checks if the password contains common and easily guessable patterns (such as "123456", "password", etc.).

*Code:*

- The `check_password_strength` function takes a password as input and returns a message indicating whether the password is strong or not.
- Uses regular expressions (re) to search for patterns in the password.
- Checks each requirement and returns a specific message if not met.
- If the password meets all requirements, returns "Password is strong.".

*Test:*

- A test password ("MyPassword123!") is provided and the `check_password_strength` function is called.
- The result is printed, indicating whether the password is strong or not.

*Summary:*

This project creates a useful tool for evaluating password strength and providing feedback to improve security. The `check_password_strength` function checks various aspects of the password and returns specific messages to help users create stronger passwords.
