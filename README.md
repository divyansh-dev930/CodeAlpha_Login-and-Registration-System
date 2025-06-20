🔐 Login and Registration System (C++)
Objective: A simple console-based user authentication program in C++.

Functionality:

Users can register by creating a username and password.

Login feature checks credentials against stored data.

Data Storage: User credentials are saved in individual .txt files using the format:

<username>.txt → stores username and password
Validation:

Prevents duplicate registration using existing usernames.

Verifies login credentials before granting access.

Tech Used: fstream for file handling, string operations, and basic console input/output.

Here's a look of how the code works - 

1. Register
2. Login
Choose an option: 1
Enter username: raja
Enter password: 2345
Registration successfull!

1. Register
2. Login
Choose an option: 2
Enter username: raja
Enter password: 2345
Login successfull! Welcome, raja!
