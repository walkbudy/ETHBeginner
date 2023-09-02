# Creating a Token

The program introduces a simple custom token called "MyTokens" built on the Ethereum blockchain using Solidity. It allows for the creation and destruction of tokens, keeping track of their total supply and individual balances. Overall, it provides a user-friendly and accessible framework for creating and managing custom tokens on the Ethereum platform, offering a reliable solution for token issuance and tracking.

## Description

name: A string representing the name of the token ("Supra").
abbr: A string representing the abbreviation of the token ("mk4").
total_amount: An unsigned integer representing the total supply or balance of tokens. This value will change as tokens are credited and debited.
account_balance: A mapping that associates Ethereum addresses with their corresponding token balances. Each address has an associated balance.
#Explanation

# Functions

credit_value: This function allows users to credit (add) tokens to their accounts. It takes an Ethereum address (add) and a value (val) as parameters. The value is added to both the total supply (total_amount) and the balance of the specified address. This is how tokens are created or added to user accounts.
debit_value: This function allows users to debit (subtract) tokens from their accounts. It takes an Ethereum address (add) and a value (val) as parameters. The value is subtracted from both the total supply (total_amount) and the balance of the specified address. This is how tokens are removed from user accounts.

## Getting Started

### Installing

Copy the code and paste in the remix ide

### Executing program

First, deploy the program.
After that, we can use the default address provided.
Paste the address in the credit_value the value 
Check the Balance.
Also, we can burn the token.
Add the address.
After adding the address the conditional statement will check whether the entered amount to debit is available in the account
or not if it is available then the token will burn.
Burn the token.
Check the balance.


## Authors
Shobhit Kumar
