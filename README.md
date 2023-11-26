# Fintech_Module_21_Homework_Advanced_Solidity

# KaseiKoin Cryptocurrency and Crowdsale

## Overview
This project involves the development of a new cryptocurrency named KaseiKoin (KAI) as part of an initiative for a monetary system on Mars. KaseiKoin is an ERC-20 token built on the Ethereum blockchain. The project also includes the setup of a crowdsale for KaseiKoin, enabling contributors to exchange Ether for KaseiKoin tokens.

## Objectives
- Develop an ERC-20 token named KaseiKoin.
- Implement a crowdsale for KaseiKoin using smart contracts.
- Ensure the token and crowdsale contracts are compliant with Ethereum standards and secure.

## Implementation Details

### KaseiKoin Token Contract
- ERC-20 compliant token contract.
- Utilizes OpenZeppelin contracts for standard token functionalities (`ERC20`, `ERC20Detailed`, and `ERC20Mintable`).
- Initial supply is minted to the contract deployer's address.

### KaseiKoin Crowdsale Contract
- A contract to manage the crowdsale of KaseiKoin.
- Inherits from OpenZeppelin's `Crowdsale` and `MintedCrowdsale` contracts.
- Allows users to send Ether to the contract and receive KaseiKoin tokens in return.

![Deployed KaseiKoin Contract](https://github.com/darcy5d/Fintech_Module_21_Homework_Advanced_Solidity/blob/main/screenshots/step_1-1_contract-compilation.png?raw=true)

![Deployed Developer](https://github.com/darcy5d/Fintech_Module_21_Homework_Advanced_Solidity/blob/main/screenshots/step_2-1_contract-compilation-KaseiKoinCrowdsale.png?raw=true)

![Deployed Contracts](https://github.com/darcy5d/Fintech_Module_21_Homework_Advanced_Solidity/blob/main/screenshots/step_3-1_contract-compilation-KaseiKoinCrowdsaleDeveloper.png?raw=true)

### Deployment and Testing
- Contracts were deployed and tested on a local Ganache blockchain.
- MetaMask was used to interact with the contracts for testing purposes.
- Various scenarios, including token purchasing and rate verification, were attempted.  Unfortunately this was not successfully completed

## Challenges and eventual Failure to transact on smart contract
- Understanding the intricacies of ERC-20 token standard and crowdsale mechanism.
- Gained experience in smart contract development using Solidity.
- Learned debugging and testing smart contracts using Remix, Ganache, and MetaMask.
- Eventually failed in transacting on the contract (see below GIF)

![Failed Transactions](https://github.com/darcy5d/Fintech_Module_21_Homework_Advanced_Solidity/blob/main/screenshots/step_4-4_fail.gif?raw=true)
