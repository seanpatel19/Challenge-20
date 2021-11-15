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

![account](https://github.com/seanpatel19/Challenge-19/blob/8ad3c96453d687a7f2252e33de8a133e56052dc0/Images/create%20account.png)

The starting balance added of 1 ether in wei

![account](https://github.com/seanpatel19/Challenge-19/blob/8ad3c96453d687a7f2252e33de8a133e56052dc0/Images/create%20account.png)


The second balance after 10 ether was added in wei

![account](https://github.com/seanpatel19/Challenge-19/blob/8ad3c96453d687a7f2252e33de8a133e56052dc0/Images/create%20account.png)


The final balance after 5 ether was added equaling 16 in total 

![account](https://github.com/seanpatel19/Challenge-19/blob/8ad3c96453d687a7f2252e33de8a133e56052dc0/Images/create%20account.png)

The full first transaction where accountOne  took out 5 ether

![account](https://github.com/seanpatel19/Challenge-19/blob/8ad3c96453d687a7f2252e33de8a133e56052dc0/Images/create%20account.png)


The lastToWithdraw function showing the second transaction eith a withdrawl of 10 Ether 

![account](https://github.com/seanpatel19/Challenge-19/blob/8ad3c96453d687a7f2252e33de8a133e56052dc0/Images/create%20account.png)




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
