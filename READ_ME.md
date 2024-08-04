BankAccount Class Implementation-

This project implements a Bank class in JavaScript, simulating a basic banking system. The class includes functionalities such as deposit, withdrawal, transfer, and interest calculation. It also records all transactions for each account.

Features-

Deposit: Add funds to the account balance.

Withdraw: Remove funds from the account balance, with checks for sufficient funds.

Transfer: Transfer funds from one account to another, with transaction recording for both accounts.

Add Interest: Calculate and add interest to the account balance based on a specified rate.

Transaction Logging: Record all transactions, including the type, amount, date, and resulting balance.

Account Details: Retrieve and display account details, including the transaction log.

Class Methods-

deposit(amount):
Adds a specified amount to the account balance if the amount is positive.
Records the transaction with the type "Deposit".
Shows an alert if the amount is invalid.

withdraw(amount):
Withdraws a specified amount from the account balance if sufficient funds are available.
Records the transaction with the type "Withdraw".
Shows an alert if the amount is greater than the available balance or invalid.

transfer(amount, recipientAccountNumber):
Transfers a specified amount to another account.
Deducts the amount from the sender's account and adds it to the recipient's account.
Records the transaction with the type "Transfer".
Shows an alert if the transfer amount is invalid or exceeds the balance.

addInterest(rate):
Adds interest to the account balance based on the provided rate.
Records the transaction with the type "Interest".
Shows an alert if the rate is invalid.

Transactionhistory(type, amount):
Records a transaction with the specified type and amount, along with the current date and balance.

getAccountDetails():
Retrieves and displays account details, including the transaction history.
