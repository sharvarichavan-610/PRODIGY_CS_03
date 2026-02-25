🔐 Password Complexity Checker

🔗📖 Overview
In today’s digital world, password security plays a crucial role in protecting personal and organizational data. Weak passwords are one of the most common reasons for security breaches. The Password Complexity Checker is a command-line based application that evaluates the strength of a user-provided password using multiple security criteria and provides clear feedback to help users create strong and secure passwords.
This project was developed as part of an internship task with the objective of demonstrating problem-solving skills, understanding of password security principles, and basic programming proficiency.


🔗🎯 Project Objectives
To analyze password strength based on standard security rules
To guide users in creating secure passwords
To implement validation using logical conditions and regular expressions
To provide meaningful feedback and suggestions


🔗🚀 Features
Validates password length
Checks presence of:
Uppercase letters (A–Z)
Lowercase letters (a–z)
Numeric digits (0–9)
Special characters (!@#$%^&* etc.)
Assigns a strength score
Categorizes passwords as:
Weak
Moderate
Strong
Displays improvement suggestions for weak passwords
Simple and user-friendly command-line interface


🔗🛠️ Technologies Used
Programming Language: Python 3
Libraries:
re (Regular Expressions)
📂 Project Structure
Copy code

🔗password-complexity-checker/
│
├── password_checker.py     # Main Python program
├── README.md               # Project documentation
└── requirements.txt        # (Optional)

🔗🧪 How It Works
The program evaluates the password based on five key criteria:
Criteria
Description
Length
Minimum of 8 characters
Uppercase
At least one capital letter
Lowercase
At least one small letter
Numbers
At least one digit
Special Characters
At least one symbol
Each satisfied condition increases the password score. The final score determines the password strength.


🔗📊 Strength Evaluation Logic
Score
Strength
0 – 2
Weak
3 – 4
Moderate
5
Strong

🔗🔐 Password Security Guidelines
To ensure better security:
Avoid common words or names
Do not reuse passwords across platforms
Use a mix of characters
Change passwords periodically
Avoid storing passwords in plain text


🔗📌 Use Cases
Educational purposes
Internship and academic projects
Beginner cybersecurity demonstrations
Password validation tools
Command-line security utilities


🔗🔮 Future Enhancements
GUI-based interface
Web version using HTML, CSS, and JavaScript
Password breach check using APIs
Password strength meter visualization
Support for multiple languages


🔗🧠 Learning Outcomes
Understanding of password security principles
Practical use of regular expressions
Conditional logic implementation
Input validation techniques
Writing clean and structured Python code
