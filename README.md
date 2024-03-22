Password Checker
This script checks the security of your passwords by querying the Pwned Passwords API. It determines whether your passwords have been exposed in data breaches.

Installation
Clone Repository:

bash
Copy code
git clone https://github.com/Hanadali818/PasswordChecker.git
Install Dependencies:

Copy code
pip install requests
Usage
To use the script, follow these steps:

Open your terminal or command prompt.
Navigate to the directory where the script is located.
Run the script using the following command:
php
Copy code
python password_checker.py <password1> <password2> ...
Replace <password1>, <password2>, etc. with the passwords you want to check.

How It Works
The script computes the SHA-1 hash of each password and sends the first 5 characters of the hash to the Pwned Passwords API. The API returns a list of password hashes that match the provided prefix. The script then compares the full hash of each password against the response to determine if it has been compromised.

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

License
This project is licensed under the MIT License.

Credits
Troy Hunt, creator of the Pwned Passwords service
requests, HTTP library for Python
Contact
For any questions or inquiries, please contact Hanadali818@gmail.com.

Thank you for using the Password Checker! Stay safe online.





