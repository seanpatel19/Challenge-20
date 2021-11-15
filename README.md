# Challenge-20

## Smart Contracts

We are fintech engineers for a fintech startup. The team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting 

joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses.

To accomplish this we need to do the following:

Step 1: Create a Joint Savings Account Contract in Solidity

Step 2: Compile and Deploy Your Contract in the JavaScript VM

step 3: Interact with Your Deployed Smart Contract


---



## Creating The Smart Contract 

We first had to define the contract, please see the following for the variables defined in contract jointsavings

![accounts](https://github.com/seanpatel19/Challenge-20/blob/5ed4b0063ddc4c4d09c06a6d302763aae16e2afe/Images/accounts.jpg)

We then needed to create a withdrawl function, making sure that the addresses matched either accountOne or accountTwo, and there were enough funds for the transaction. 

![require and if statements](https://github.com/seanpatel19/Challenge-20/blob/5ed4b0063ddc4c4d09c06a6d302763aae16e2afe/Images/require%20and%20if%20functions.jpg)

We also added functionality to check the balance of the contract 

![contract balance](https://github.com/seanpatel19/Challenge-20/blob/5ed4b0063ddc4c4d09c06a6d302763aae16e2afe/Images/contract%20balance.jpg)

And to update the values of each account 

![account update](https://github.com/seanpatel19/Challenge-20/blob/5ed4b0063ddc4c4d09c06a6d302763aae16e2afe/Images/account%20update.jpg)


## Testing the Smart Contract   

Here is the contract as deployed 

![deploy](https://github.com/seanpatel19/Challenge-20/blob/c6ce43df199f63c5a2532e1164bb0f15d3d90226/Execution_Results/deployment.jpg)

The starting balance added of 1 ether in wei

![first balance](https://github.com/seanpatel19/Challenge-20/blob/c6ce43df199f63c5a2532e1164bb0f15d3d90226/Execution_Results/first%20balance.jpg)


The second balance after 10 ether was added in wei

![second balance](https://github.com/seanpatel19/Challenge-20/blob/c6ce43df199f63c5a2532e1164bb0f15d3d90226/Execution_Results/second%20balance.jpg)


The final balance after 5 ether was added equaling 16 ETH in total 

![final balance](https://github.com/seanpatel19/Challenge-20/blob/c6ce43df199f63c5a2532e1164bb0f15d3d90226/Execution_Results/final%20balance.jpg)

The full first transaction where accountOne  took out 5 ether

![first transaction](https://github.com/seanpatel19/Challenge-20/blob/c6ce43df199f63c5a2532e1164bb0f15d3d90226/Execution_Results/user%201%205%20ether.jpg)


The lastToWithdraw function showing the second transaction eith a withdrawl of 10 Ether 

![second transaction ](https://github.com/seanpatel19/Challenge-20/blob/c6ce43df199f63c5a2532e1164bb0f15d3d90226/Execution_Results/second%20balance.jpg)

Another view showing more detail 

![in console](https://github.com/seanpatel19/Challenge-20/blob/9dea41fedc31d59a5d9d86f9d22fc487e76bc0da/Execution_Results/secondtransfull.jpg)

## Bonus 

The following are some screen shots to show that the error messages work, when the wrong account information  is provided and when there is not enough to complete the transaction

![account](https://github.com/seanpatel19/Challenge-20/blob/9dea41fedc31d59a5d9d86f9d22fc487e76bc0da/Images/error%20working%20.jpg)

![account](https://github.com/seanpatel19/Challenge-20/blob/9dea41fedc31d59a5d9d86f9d22fc487e76bc0da/Images/error%20working%202.jpg)



---

## Technologies
This application is written in Solidity 5

It also uses the built in services of Remix IDE such as compile and deploy 



---








## Usage

To use the data simply clone the repository. All code written in Solidity. To deploy open up the .sol file in Remix IDE, or any other IDE that has similar functionality   

```
---

## Contributors

Sean Patel (myself) seanpatel076@gmail.com
---

## License

License is public anyone can use or make changes to this application
