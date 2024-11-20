# Mini-Project-1
This repository contains a simple banking system implemented in Java. The system includes classes for managing customers and their bank accounts, along with a command-line interface for user interaction.

## Description

### Classes

#### Customer
- **Fields**:
    - `String customerName`
    - `String customerAddress`
    - `BankAccount bankAccount`

- **Constructors**:
    - `public Customer(String customerName, String customerAddress)`

- **Methods**:
    - Method to create a new `BankAccount` for the customer.
    - Method to get the `BankAccount` of the customer.

#### BankAccount
- **Fields**:
    - `String bankAccountName`
    - `int bankAccountId`
    - `double balance`

- **Constructors**:
    - `public BankAccount(String name, double balance)`

- **Methods**:
    - Method to deposit money into the `BankAccount`.
    - Method to withdraw money from the `BankAccount`.
    - Method to get the current balance.
    - Method to get the ID number of the `BankAccount`.

#### BankAccountCLI
- The main class that contains the entry point of the application.
- Responsible for user interaction and testing the functionality of the `Customer` and `BankAccount` classes.
- Includes user input validation where necessary.

## Getting Started

1. **Create the `Customer` and `BankAccount` classes**: Implement the fields, constructors, and methods as specified above.
2. **Create the `BankAccountCLI` class**: This class should contain the `main` method to test your classes and facilitate user interaction.
3. **Implement user interaction**: Extend the `main` method in `BankAccountCLI` to support user inputs for creating customers, managing bank accounts, depositing, and withdrawing funds.
4. **Input validation**: Ensure that user inputs are validated where necessary (e.g., checking for valid amounts for deposits and withdrawals).

## Example Usage

The following is a simple example of how the command-line interface might work:

```
Welcome to the Bank Account System!
1. Create a new customer
2. Deposit money
3. Withdraw money
4. Check balance
5. Exit
Enter your choice: 
```

*Follow the prompts to interact with the banking system.*

## Notes

- Ensure that you have the necessary Java environment set up to compile and run the program.
- Extend the functionality as needed to meet any additional requirements.

Happy coding! 🎉