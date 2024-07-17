# AVAX-ADV-1
# ERC-20 Token and Vault Contracts

## Overview

This repository contains the code for an ERC-20 token and a Vault smart contract. The ERC-20 token contract allows for the creation and management of a fungible token on the Ethereum blockchain. The Vault contract enables secure storage and management of these tokens.

## Features

### ERC-20 Token
- **Token Creation**: Deploy a new ERC-20 token with a specified name, symbol, and initial supply.
- **Standard Functions**: Supports all standard ERC-20 functions (balanceOf, transfer, approve, transferFrom, etc.).
- **Events**: Emits Transfer and Approval events as per the ERC-20 standard.

### Vault
- **Token Storage**: Securely store ERC-20 tokens.
- **Deposit**: Users can deposit ERC-20 tokens into the Vault.
- **Withdraw**: Users can withdraw their tokens from the Vault.
- **Owner Management**: Only the owner can manage the Vault settings.

## Getting Started

### ERC-20 Token
- **Deploy the ERC-20 contract**: Deploy and configure the token parameters (name, symbol, initial supply).
- **Interact with the token**: Use the standard ERC-20 functions for transferring tokens, checking balances, and managing allowances.

### Vault
- **Deposit tokens**: Users can deposit tokens into the Vault using the `deposit` function.
- **Withdraw tokens**: Users can withdraw their deposited tokens using the `withdraw` function.

## License
This project is licensed under the MIT License.
