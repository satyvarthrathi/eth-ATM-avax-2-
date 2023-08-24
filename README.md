# Ethereum ATM Smart Contract
The Ethereum ATM Smart Contract is a basic Solidity smart contract that simulates an Ethereum ATM, allowing users to deposit and withdraw ETH. This contract provides a simple way for users to manage their balances and perform deposit and withdrawal operations.

# Features
Deposit ETH: Users can deposit ETH into the contract.
Withdraw ETH: Users can withdraw ETH from their account balance.
Account Balance: Users can check their account balance.

## Usage

## Deposit ETH
Users can deposit ETH into the contract by sending ETH along with the deposit function call. The deposited amount will be added to the user's account balance.

### Withdraw ETH
Users can withdraw ETH from their account balance using the withdraw function. They need to specify the amount they want to withdraw.
pragma solidity ^0.8.4;

### Account Balance
Users can check their account balance using the getBalance function. This function returns the user's account balance stored in the contract.
