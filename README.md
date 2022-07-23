# Unit-21-Advanced-Solidity

## Martian Token Crowdsale

![image](https://user-images.githubusercontent.com/99091066/180624129-fad8426e-3b55-4f91-8564-40197b8a9aa9.png)

## Step 1: Create the KaseiCoin Token Contract



<img width="1436" alt="Screen Shot 2022-07-22 at 10 21 13 PM" src="https://user-images.githubusercontent.com/99091066/180624323-f966ea75-3d32-4278-b788-de4a286d58d3.png">


## Step 2: Create the KaseiCoin Crowdsale Contract


<img width="1433" alt="Screen Shot 2022-07-22 at 10 21 39 PM" src="https://user-images.githubusercontent.com/99091066/180624372-39321dad-949e-43c4-a132-4edbd1df34b5.png">


## Step 3: Create the KaseiCoin Deployer Contract


<img width="1434" alt="Screen Shot 2022-07-22 at 10 36 58 PM" src="https://user-images.githubusercontent.com/99091066/180624392-ab0e4142-967a-4c60-abb5-7210ec6b8d5e.png">


## Step 4: Deploy and Test the Crowdsale on a Local Blockchain

To test out the contracts, I used Metamask :

<img width="1253" alt="Screen Shot 2022-07-23 at 5 43 36 PM" src="https://user-images.githubusercontent.com/99091066/180624423-287df6d7-1e26-4d79-8f83-cb063457f610.png">

Using `KaseiCoinCrowdsaleDeployer`, i deployed the contract using the name `kasecoin`, symbol `kc`, and used the MetaMask address under the wallet section. Once i hit transact, the metamask notification above appeared, prompting me to confirm the transaction. 
Once confirmed, the contract appeared under the "deployed contract sectio".

Under the deployed contracts, the addresses for kasei crowdsale and kasei token are called. The address for kasei crowdsale was copied.

I then changed the contract to KaseiCoinCrowdsale and added the above address to "at address". This deployed the KaseiCoinCrowdsale contract.

The same process was done using the kasei token address and KaseiCoin contract. This deployed the KaseCoin contract as well.


<img width="1255" alt="Screen Shot 2022-07-23 at 5 47 00 PM" src="https://user-images.githubusercontent.com/99091066/180624822-c0bbef1a-eaae-4d70-bada-a22b601ca5ff.png">

Under the KaseiCoin contract, i inputted an initial supply of 250. 


### Testing the Crowdsale

I entered 114 Wei and pasted the metamask address under the `buytokens` button. 

<img width="1259" alt="Screen Shot 2022-07-23 at 5 47 54 PM" src="https://user-images.githubusercontent.com/99091066/180624855-5e40cec7-874b-4863-ac43-975c4cdd1e43.png">

This prompted metamask to confirm the transaction.


<img width="1261" alt="Screen Shot 2022-07-23 at 5 48 29 PM" src="https://user-images.githubusercontent.com/99091066/180624852-c18cb34e-056d-47e5-8514-cd8e7adf7869.png">

Once the transaction processed, i checked the balances under the KaseiCoin contract to ensure it was accurate.

<img width="1252" alt="Screen Shot 2022-07-23 at 5 49 15 PM" src="https://user-images.githubusercontent.com/99091066/180624862-2236b4c4-8418-4c90-b448-573cd7048600.png">










