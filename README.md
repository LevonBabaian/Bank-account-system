# Bank-account-system

This C program simulates a basic banking system allowing users to create accounts, log in, check balance, transfer money, and log out.

## Features

- **Create Account:**
  - Users can create a bank account by providing personal details, including name, address, date of birth, Aadhar number, phone number, username, and password.

- **Login:**
  - Existing users can log in using their username and password.

- **Check Balance:**
  - Users can check their account balance, and the system displays transaction history.

- **Transfer Money:**
  - Users can transfer money to other users by providing the recipient's username and the amount to be transferred.

- **Logout:**
  - Users can log out of their accounts.

## How to Compile and Run

1. Open a terminal window.
2. Navigate to the project directory.

```bash
gcc -o BankingSystem main.c
./BankingSystem
```

## Usage

1. **Create a Bank Account:**
   - Choose option 1 to create a bank account.
   - Enter personal details as prompted.

2. **Already a User? Sign In:**
   - Choose option 2 to log in.
   - Enter your username and password.

3. **Check Balance:**
   - After logging in, choose option 1 to check your balance.
   - The system will display your account details and transaction history.

4. **Transfer Money:**
   - After logging in, choose option 2 to transfer money.
   - Enter the recipient's username and the amount to be transferred.

5. **Log Out:**
   - After completing your transactions, choose option 3 to log out.

6. **Exit:**
   - Choose option 4 to exit the banking system.

## Example Usage

1. Create a Bank Account:
   ```
   WELCOME TO BANK ACCOUNT SYSTEM

   1.... CREATE A BANK ACCOUNT
   2.... ALREADY A USER? SIGN IN
   3.... EXIT

   ENTER YOUR CHOICE..1
   ```

2. Check Balance:
   ```
   WELCOME, John Doe
   ===============================
   HOME
   ******
   1....CHECK BALANCE
   2....TRANSFER MONEY
   3....LOG OUT

   ENTER YOUR CHOICE..1
   ```

3. Transfer Money:
   ```
   WELCOME, John Doe
   ===============================
   HOME
   ******
   1....CHECK BALANCE
   2....TRANSFER MONEY
   3....LOG OUT

   ENTER YOUR CHOICE..2
   ```

4. Log Out:
   ```
   Sign out successfully..
   Press any key to continue..
   ```
