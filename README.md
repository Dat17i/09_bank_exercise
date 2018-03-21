# Bank Exercise
## Exercise: from use cases to database.    
### From the information below you should now create a database that can  hold the information.

# _

## Description of the Scenario:
  
A customer opens a bank account in a bank.
After opening the account the customer can withdraw, deposit and check his balance at any time he wants. The bank charges a fee of 10kr. for every withdraw a customer makes. The Customer can not withdraw more money than is on the account including the fee. The bank also has an interest rate of 8.5%, which is used for calculating a certain amount of interest on the amount deposited by the customer.

## Use Cases

### Use Case Diagram

![](https://github.com/Dat17i/09_bank_exercise/blob/master/src/Screen%20Shot%202018-03-21%20at%2020.59.29.png)

### UC#1: Withdraw Money
**Actor: Customer**    

Customer requests to withdraw money from his account and specifies the amount. 
The bank puts on a fee of 10 kr. when a withdrawal is made, so the customer gets the requested amount, and the fee is subducted on the remaining balance of the account. 

### UC#2: Deposit Money
**Actor: Customer**   

The Customer requests to deposit money. The bank calculates the interest based on the interest rate and the amount just deposited, the interest and the amount is summed. The sum is then added to the account balance.

### UC#3: Check Balance
**Actor: Customer**    

Customer requests to see the balance of his account. 
The account number and name of the customer together with the balance is displayed.



  
