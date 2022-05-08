# JointSavings

## To run the program: 

Source code: joint_saving.sol

run this code in the Remix IDE

The program will create a Solidity smart contract to accept two user addresses and provide the features (deposit and withdraw funds) as an joint savings account.
<br/>
<br/>
## To test the program:

### 1. set accounts
get the addresses from JavaScriptVM (London) for account1 and account2
<br/>
<br/>
account1 address: 0x5B38Da6a701c568545dCfcB03FcB875f56beddC4
<br/>
account2 address: 0xAb8483F64d9C6d1EcF9b849Ae677dD3315835cb2
<br/>
<br/>
![alt=""](Execution_Results/Beginning_balances.png)

enter the addresses of account1 and account2 in the setAccounts

![alt=""](Execution_Results/setAccounts.png)
<br/>
<br/>
### 2. deposit funds

use the deposit fuction to deposit 1, 10, 5 ethers from account1
![alt=""](Execution_Results/deposit_1_ether.png)
![alt=""](Execution_Results/deposit_10_ether.png)
![alt=""](Execution_Results/deposit_5_ether.png)
<br/>
Here is the contract balance after the deposits.
<br/>
![alt=""](Execution_Results/balance_after_deposits.png)
<br/>
<br/>
### 3. withdraw funds
withdraw 5 ether into account1
<br/>
![alt=""](Execution_Results/withdraw_5_ether.png)
<br/>
Here is the information of contract balance, lastToWithdraw, and lastWithdrawAmount aftere the withdraw.
<br/>
![alt=""](Execution_Results/balance_after_withdraw_5ETH.png)
<br/>
<br/>
withdraw 10 ether into account2
<br/>
![alt=""](Execution_Results/withdraw_10_ether.png)
<br/>
Here is the information of contract balance, lastToWithdraw, and lastWithdrawAmount aftere the withdraw.
<br/>
![alt=""](Execution_Results/balance_after_withdraw_10ETH.png)
<br/>
<br/>
The ending balances of account1 and account2
<br/>
![alt=""](Execution_Results/ending_balances.png)
