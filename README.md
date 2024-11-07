Simple Banking System

This Python script implements a basic banking system with functionalities to manage user accounts, check balance, deposit, and withdraw money. 
The system uses a dictionary (key_pass) to store user accounts and their passwords.
It allows users to log in with their username and password, and once logged in, they can:

1:Check Balance: Display the current balance of the user's account.
2:Deposit: Add money to the account after validating that the deposit amount is positive.
3:Withdraw: Subtract money from the account, ensuring sufficient funds are available.

Features:

1:Login System: Users have three attempts to log in with the correct credentials. After three failed attempts, they are locked out.
2:Account Creation: If the user doesn't have an account, they can create one by entering a unique username and a password.
3:User Prompts: The script guides users through available options (balance check, deposit, withdraw) and handles incorrect inputs.

Usage:

1:If the user has an account, they will be prompted to log in using their username and password.
2:If the login is successful, they can choose to:
* Check their balance.
* Deposit money.
* Withdraw money.

If the user does not have an account, they can create a new one.
The program terminates when the user chooses the "Exit" option.
This code is ideal for educational purposes and can be further expanded to include additional banking functionalities, secure password management, and error handling mechanisms.

