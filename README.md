# ATM Program

## Overview

This is a simple ATM (Automated Teller Machine) program implemented in Python. The program includes functionality for both users and administrators. Users can create accounts, deposit, withdraw, check balances, and change passwords. Administrators can check the total balance, deposit cash, and withdraw cash.

## Features

### User Functionality
- Create a new account
- Deposit cash with denomination validation
- Withdraw cash with denomination validation
- Check account balance
- Change account password

### Admin Functionality
- Check total balance
- Deposit cash to the admin account with denomination validation
- Withdraw cash from the admin account with denomination validation

## File Structure

- `atm.py`: Main Python script containing the classes for User and Admin, as well as the main program logic.
- `README.md`: This file, providing information about the ATM program.

## How to Run

1. Run the `atm.py` script.
2. Choose between User and Admin options in the main menu.
3. Follow the on-screen instructions for the selected role.

## Dependencies

No external libraries or frameworks are used. The program relies on native Python functionality.

## Important Notes

- Users must maintain a minimum balance of 5000.
- Admins must maintain a minimum balance of 75000.

## Author

NOBODY1819

## License

This project is open-source and available under the [MIT License](LICENSE).
