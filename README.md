# Bank Management System (Object-Oriented Programming)

## Overview
This project implements a Bank Management System using Object-Oriented Programming. It offers functionality for two types of users: Admin and Normal User.

## User Types
### Normal User
Normal users have the following capabilities:

1. **Account Creation**: Create Current and Savings accounts with personal information (name, email, and address). A unique ID is auto-generated for every user.

2. **Account Operations**: 
   - Check account balance.
   - Withdraw and deposit funds.
   - Transfer money to another user's account within the bank.
   - Apply for a maximum of 2 loans.

3. **Bank Solvency**: Users cannot withdraw funds if the bank is declared bankrupt.

### Admin
Administrators have the following privileges:

1. **User Management**:
   - View all user accounts.
   - Delete user accounts.

2. **Bank Statistics**:
   - Check the total balance of the bank.
   - View the total loan amount disbursed.

3. **Bank Management**:
   - Enable or disable the loan feature.
   - Declare the bank as bankrupt.

