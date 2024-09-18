The ATM class simulates the functionality of an Automated Teller Machine (ATM). It allows users to create and manage their ATM pin, check their balance, and withdraw funds. This class provides a simple command-line interface to interact with these features.

Features
Create Pin: Allows the user to set a new PIN and initial balance.
Change Pin: Enables the user to update their existing PIN after verifying the old PIN.
Check Balance: Provides the user with the current account balance upon entering the correct PIN.
Withdraw Funds: Allows the user to withdraw money from their account, checking for sufficient balance and verifying the PIN before processing the withdrawal.
Exit: Terminates the ATM session.
Methods
__init__(self): Initializes the ATM instance with an empty PIN and a balance of 0. Automatically calls the menu method to start the ATM interface.
menu(self): Displays the main menu and prompts the user to select an option. Calls corresponding methods based on user input.
create_pin(self): Prompts the user to set a new PIN and an initial balance. Updates the object's PIN and balance.
change_pin(self): Allows the user to change their PIN after providing the correct current PIN.
check_balance(self): Displays the current balance if the user provides the correct PIN.
withdraw(self): Allows the user to withdraw funds if the correct PIN is provided and the balance is sufficient.
