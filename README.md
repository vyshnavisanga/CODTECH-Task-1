# CODTECH-Task-1
Name : Sanga Vyshnavi
Company : CODTECH IT SOLUTIONS
ID : CT08DS4706
Domain : CyberSecurity & Ethical Hacking
Duration : July to August 2024
Mentor : Neela Santhosh Kumar

OVERVIEW OF THE PROJECT :
This project aims to develop a tool to assess the strength of passwords entered by users. The tool will analyze factors such as length, complexity, and uniqueness to provide feedback on password strength.
Requirements :-
Python 3.x
re (regular expression) module for password complexity analysis
The password_strength_checker function takes a password as input and analyzes its strength based on three factors:
Length: The password should be at least 12 characters long.
Complexity: The password should contain at least one lowercase letter, one uppercase letter, one digit, and one special character.
Uniqueness: The password should not contain any repeating characters (simple implementation, can be improved).
The function returns a dictionary containing the analysis results, including a overall strength assessment (Weak, Medium, or Strong)
Advice :-
Use a sufficient work factor (e.g., iteration count) when generating passwords to slow down the password generation process, making it more resistant to brute-force attacks.
Consider using a more advanced password hashing algorithm like Argon2, PBKDF2, or Bcrypt.
Implement a password policy that enforces regular password changes and prohibits the reuse of previously used passwords.
Use a secure password storage mechanism, such as a Hardware Security Module (HSM) or a secure password manager.
