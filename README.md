# Savings and CD Account Interest Calculator

## Overview

This Python script calculates the interest earned on both a Savings account and a Certificate of Deposit (CD) account over a specified number of months. Users can input their account balances, interest rates, and the duration in months to see the total interest earned and the updated account balances.

## Features

- **Savings Account Interest Calculation**: Calculates the interest earned on a savings account balance over a given period.
- **CD Account Interest Calculation**: Computes the interest earned on a CD account balance for a specified term.
- **User Input**: Prompts users to enter account details such as balance, interest rate, and duration.
- **Output Display**: Shows the interest earned and the updated balance for each account type.

## Requirements

- Python 3.x
- The script assumes the existence of two external functions:
  - `create_savings_account` from a module named `savings_account`
  - `create_cd_account` from a module named `cd_account`

## Installation

No additional installation is required except for ensuring Python 3.x is installed on your system.

## Usage

1. Clone or download this repository to your local machine.
2. Ensure that the `savings_account.py` and `cd_account.py` modules are in the same directory as this script.
3. Run the script using Python:

   ```bash
   python main.py
## Usage

Follow the on-screen prompts to enter your savings and CD account details.

## Input Format

- **Savings Account and CD Account Balance**: Enter the initial balance in your account (numeric value).
- **Interest Rate**: Input the annual interest rate as a percentage (e.g., enter `5` for 5%).
- **Number of Months**: Specify the duration for which you want to calculate the interest (in months).

## Output

The script will display the following for each account type:

- **Interest Earned**: The total interest earned over the specified period.
- **Updated Balance**: The new account balance after adding the earned interest.



