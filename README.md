# ERC 20 Token

## Overview
MyToken is an ERC-20 token smart contract that provides a standard token implementation with the ability to mint and burn tokens. The contract uses the OpenZeppelin ERC20 and Ownable contracts to maintain security and compliance with industry standards.

## Contract Details
* Token Name: MyToken
* Token Symbol: MYT
* Compiler Version: Solidity ^0.8.0
* License: MIT

# Features
## Minting Tokens
* Description: Allows the contract owner to create new tokens and assign them to a specified address.
* Function Name: mint(address to, uint256 amount)
* Access Control: Only the contract owner can call this function.

## Transferring Tokens
* Description: Token can be transfered between addresses
* Function Name: transfer(address recipient, uint256 amount)
* Access Control: Any user can call this function to transfer their own tokens.

## Burning Tokens
* Description: Allows a user to destroy a specified amount of their own tokens.
* Function Name: burn(uint256 amount)
* Access Control: Any user can call this function to burn their own tokens.

## How to Deploy and Interact
### Deployment Steps
### Preparation:
* Ensure you are using Solidity compiler version ^0.8.0 in Remix IDE or any compatible environment.
* Import the contract file and compile it.
### Deploy the Contract:
* Deploy the contract using the appropriate deployment tool (e.g., Remix IDE).
* No initial parameters are needed for deployment.

## Interaction Steps
### Minting Tokens:
* The contract owner can use the mint function to mint new tokens.
* Provide the recipient's address and the amount of tokens to mint.
* Execute the function to mint the tokens.
### Transfer Tokens:
* Any user can use the transfer function to transfer their tokens.
* Provide the recipient's address and the amount of tokens to transfer.
* Execute the function to transfer the tokens.
### Burning Tokens:
Any user can use the burn function to burn their own tokens.
Specify the amount of tokens to burn.
Execute the function to burn the tokens.

## Important Notes
* Ownership: The deployer of the contract is the initial owner and has the ability to mint tokens. Only the owner can call the mint function.
* Security: The contract leverages OpenZeppelin's Ownable contract to manage ownership and access control.

## License
This project is licensed under the MIT License.

## Acknowledgments
The ERC20 and Ownable contracts from OpenZeppelin are used in this smart contract.
