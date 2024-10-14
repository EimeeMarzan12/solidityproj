# Project Title

A simple token smart contract that allows minting and burning of tokens on the Ethereum blockchain.

## Description

This project implements a basic Ethereum token contract with functionalities to mint new tokens and burn existing tokens. The contract tracks the total token supply and each user's balance using public variables and mappings. The mint function allows increasing the total supply and assigning tokens to a specified address, while the burn function reduces the supply by burning tokens from a user's balance, provided they have enough tokens. It is designed for educational purposes, demonstrating how simple tokenomics can be implemented using Solidity.

## Getting Started

### Installing

* Download or clone the project repository to your local machine.
* Install Solidity development tools like Remix or Hardhat for compiling and deploying the contract.
* Deploy the contract on a testnet or a local Ethereum development environment.

### Executing program

* Open Remix IDE (or another Solidity-compatible environment).
* Paste the contract code into the editor.
* Compile the contract:
```
pragma solidity 0.8.18;
```

* Deploy the contract on the Ethereum testnet or remix Ethereum IDE website
* Once deployed, use the functions to mint or burn tokens
* Test the mint function with entering default account address and a sample value such as 1000
* Check the totalSupply and balances if it is equal to what you inputted in the mint function
* Do the same with the burn function with the default account address and a sample value such as 500
* Check the totalSupply and balances if it is equal to what you inputted in the burn function if it was subtracted
* Try to test the burn function if it will exceed the amount of tokens to subtract that what is stored
  


## Help

Any advise for common problems or issues.
*Make sure the Ethereum address used in mint/burn is valid and holds enough tokens before burning.

## Authors
Eimee Suzanne Marzan


Contributors names and contact info

@EimeeMarzan12


## License

This project is licensed under the MIT License.
