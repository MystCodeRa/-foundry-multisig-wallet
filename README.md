# -foundry-multisig-wallet Multi-Signature Ethereum Wallet

SecureWallet is a secure and transparent multi-signature Ethereum wallet that allows transactions to be executed only after approval by multiple administrators. The project is written in Solidity  and developed using the [foundry](https://book.getfoundry.sh/) framework with full test covarage.

## Project Purpose 
IN Decentralized and collaborative environments, having a single person in control of a wallet poses security and governance risks. This project solves that by requiring multiple approvals for any critical transaction to be executed ideal for DAOs, team-managed treasuries, or high-value operations.

## Features 
- Define multiple administrators
- Admin can propose transactions(ETH transfers or contract calls).
- Other admins vote to approve the transaction.
- Once the minimum  number of approvals is automatically executed.
- Transactions are imnutable and cant't be executed more than once.
- Ether can be sent to the wallet from outside.



