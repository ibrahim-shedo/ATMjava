# Java ATM Program

This is a simple ATM (Automated Teller Machine) simulation written in Java. The program allows users to interact with their bank accounts by performing basic operations such as balance inquiry, deposit, and withdrawal.

## Features
- **User Authentication**: Users must enter their account number and PIN to access their account.
- **Balance Inquiry**: Users can check their current account balance.
- **Deposit**: Users can deposit money into their account.
- **Withdrawal**: Users can withdraw money from their account (if sufficient funds are available).
- **PIN Validation**: Basic authentication based on account number and PIN.

## Project Structure
The project contains the following main files:
- `Account.java`: Represents a user's bank account, including details such as the account number, PIN, and balance. It also includes methods for depositing and withdrawing funds.
- `ATM.java`: The main class that interacts with the user, processes transactions, and handles authentication.

## Prerequisites
To run this program, you need to have the following installed:
- Java Development Kit (JDK) 8 or higher
- A text editor or Integrated Development Environment (IDE) like IntelliJ IDEA, Eclipse, or VS Code

## How to Run
1. **Clone the repository or download the source code**.
2. **Compile the program** using the terminal or your IDE:
   ```bash
   javac *.java
Run the ATM program:
bash
Copy code
java ATM
Usage
When prompted, enter your account number and PIN to log in.
After successful authentication, choose from the following menu options:
Check balance
Deposit money
Withdraw money
Exit the program
Follow the on-screen instructions for each operation.
The program will exit when you choose the "Exit" option.
Future Enhancements
This is a basic ATM simulation. Possible future improvements include:

Storing multiple accounts and allowing users to switch between them.
Adding a more secure PIN storage method (e.g., hashing).
Including additional banking features such as money transfers, account creation, and PIN change.
Implementing a graphical user interface (GUI) for better user experience.
License
This project is open-source and free to use. Feel free to contribute or modify it as per your needs.
