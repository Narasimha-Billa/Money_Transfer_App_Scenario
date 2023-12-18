# Money Transfer Application Scenario

## Overview

This Python application simulates a basic money transfer scenario between two bank accounts using the `BankAccount` class. The application ensures secure and error-handled transactions, including features for deposit, withdrawal, and balance inquiry.

## Features

- **BankAccount Class:**
  - `__init__`: Initializes the account with an account number and sets the initial balance to 0.
  - `get_balance`: Returns the current balance of the account.
  - `withdraw`: Withdraws a specified amount from the account, raising a `ValueError` if there are insufficient funds.
  - `deposit`: Deposits a specified amount into the account.

- **Transaction Function:**
  - `transfer_amount`: Facilitates fund transfers between two accounts, handling insufficient fund scenarios gracefully.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/money-transfer-app.git
