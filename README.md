# Crypto-Currency-Wallet

## Description
I created a web app that allows me to pay fintech professionals to do work and get paid for it, all in the same place. 

## What I did Exactly
* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their  work.

* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

* Review the transaction hash code associated with the validated blockchain transaction.


## Imports

# Imports
* import os
* import requests
* from dotenv import load_dotenv
* load_dotenv()
* from bip44 import Wallet
* from web3 import Account
* from web3 import middleware
* from web3.gas_strategies.time_based import medium_gas_price_strategy

## Proof of Transaction
![Screen Shot 2022-02-18 at 3 05 27 PM](https://user-images.githubusercontent.com/85980757/154756065-b52a45eb-a388-4841-9565-7efbb354e133.png)


![Screen Shot 2022-02-18 at 3 06 40 PM](https://user-images.githubusercontent.com/85980757/154756103-c53c11fe-e7a5-4abc-bac4-884b22200dd7.png)




