# AVAXETH-Module-3-Project

MyToken is an ERC20-compliant token smart contract deployed on a local HardHat network. The contract allows the contract owner to mint tokens to a provided address and enables any user to burn and transfer tokens.

## Interact with the contract using Remix:

a. Go to https://remix.ethereum.org/.

b. Connect Remix to the local HardHat network by selecting the "HardHat" environment.

c. Create a new Solidity file and paste the MyToken contract code.

d. Deploy the contract from Remix by clicking the "Deploy & Run Transactions" tab.

## Minting Tokens:

As the contract owner, you can mint new tokens to a provided address.
In Remix, go to the "Deployed Contracts" section, find the MyToken contract, and expand it to see the functions.
Click on the "mint" function and provide the address and amount of tokens you want to mint.
Click the "transact" button to mint the tokens.
Burning Tokens:

## Any user can burn (destroy) their own tokens.
In Remix, go to the "Deployed Contracts" section, find the MyToken contract, and expand it to see the functions.
Click on the "burn" function and provide the amount of tokens you want to burn.
Click the "transact" button to burn the tokens from your address.
Transferring Tokens:

## Any user can transfer tokens to other addresses.
In Remix, go to the "Deployed Contracts" section, find the MyToken contract, and expand it to see the functions.
Click on the "transfer" function and provide the recipient's address and the amount of tokens you want to transfer.
Click the "transact" button to transfer the tokens.

## Contract Details
Name: MyToken

Symbol: MTK

Decimals: 18 (standard for most tokens)

Total Supply: Initial supply set during contract deployment

Minting Limit: No minting limit, only restricted by the contract owner's balance
