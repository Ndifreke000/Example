# Advanced Smart Contract Project

## Overview

This project contains an advanced smart contract written in Solidity that demonstrates the usage of `require()`, `assert()`, and `revert()` statements. The contract includes an ownership mechanism, deposit and withdrawal functionalities, and a complex operation that requires specific conditions to be met.

## Smart Contract Details

- **Contract Name**: AdvancedSmartContract
- **Functions**:
  - `constructor()`: Initializes the contract and sets the deployer as the owner.
  - `deposit()`: Allows users to deposit funds into the contract.
  - `withdraw(uint256 amount)`: Allows the owner to withdraw funds from the contract, demonstrating `require()`, `assert()`, and `revert()` statements.
  - `complexOperation(uint256 x, uint256 y)`: Demonstrates complex operations with conditions using `require()`, `assert()`, and `revert()`.

## Installation

Ensure you have a compatible Ethereum development environment set up.

```bash
npm install -g truffle
