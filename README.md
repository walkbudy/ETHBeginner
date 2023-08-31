Creating a Token
Program introduces a simple custom token called "MyTokens" built on the Ethereum blockchain using Solidity. It allows for the creation and destruction of tokens, keeping track of their total supply and individual balances. With the ability to mint new tokens and burn existing ones, the program ensures that token holders have enough balance before performing any burning actions. By adhering to the MIT license, this contract can be freely used and distributed. Overall, it provides a user-friendly and accessible framework for creating and managing custom tokens on the Ethereum platform, offering a reliable solution for token issuance and tracking.

Description
name: A string representing the name of the token ("Supra"). abbr: A string representing the abbreviation of the token ("mk4"). total_amount: An unsigned integer representing the total supply or balance of tokens. This value will change as tokens are credited and debited. account_balance: A mapping that associates Ethereum addresses with their corresponding token balances. Each address has an associated balance. #Explanation

Functions:

The credit_value function increments both the total_amount and the balance of a specific address in the account_balance mapping when tokens are credited.The debit_value function first checks if either the total_amount or the account balance for the specified address is insufficient. If either condition is true, the code within the if block will be executed. You can add appropriate handling for the insufficient balance scenario here.If both conditions are false (meaning there are sufficient tokens both in the total_amount and in the account balance), the code within the else block is executed. The specified amount is then deducted from both the total_amount and the account balance.

Getting Started
Installing
Copy the code and paste in remix ide

Executing program
First deploy the program. After that we can use the deafult address provided. Paste the address in the credit_value add the value Check the Balance. Also we can burn the token via burn. Add the address. Burn the token. Check the balance.

Authors
Shobhit Kumar
