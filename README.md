# Collateral and Insurance Protocol Contract

This is Solidity-based smart contracts in this project. The contracts enable users to purchase insurance and collateral for crypto-backed loans.

## Table of Contents

- [Collateral and Insurance Protocol Contract](#collateral-and-insurance-protocol-contract)
  - [Table of Contents](#table-of-contents)
  - [Overview-Description](#overview-description)
  - [Deploying and Verifying the Contracts on Sepolia testnet](#deploying-and-verifying-the-contracts-on-sepolia-testnet)
  - [Verified Contract Addresses](#verified-contract-addresses)
  - [Authors](#authors)
  - [License](#license)

## Overview-Description

The project includes a `factory contract model`, which allows users to create either `insurance contracts` or `collateral protection contracts`.
The factory contract can deploy instances of either a child contract based on user preference.

The insurance contract allows users to pay their premiums either `monthly` or `annually`.
The `collateral management contract`, on the other hand, monitors the value of the user's collateral.
If the collateral value drops below 20, the contract liquidates the collateral. Users can also repay their loans to retrieve their collateral.


## Verified Contract Addresses

- Insurance Contract:
  https://sepolia.etherscan.io/address/0xEE331e548BCDe62053FB2A7969f6302E32984bB7

- Collateral Contract:
  https://sepolia.etherscan.io/address/0x73AbAb5B8e4F1db9b51574239B35E6b1737dB969

- Factory Contract:
  https://sepolia.etherscan.io/address/0x8f0cf5Cec04325080aC1BC602347ad92945e3Ace

## Authors

Isaac
[@metacraftersio](https://twitter.com/0xkyng)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
