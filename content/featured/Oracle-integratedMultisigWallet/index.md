---
date: '2'
title: 'Oracle-integrated Multisig Wallet'
cover: './demo.png'
github: 'https://github.com/vivinvinh212/Multisig-wallet/blob/main/README.md'
external: 'http://maasify.surge.sh/'
tech:
- React
- Hardhat
- Solidity
- OpenZeppelin
---

A React/Hardhat-based multisig factory web3 dapp allowing users to create multisig wallets with off-chain signatures to save gas, pre-compute multisig wallet addresses for fund deposits, add or remove signers/owners. This multisig wallet also integrates an oracle supporting the addition of signers when a certain threshold on ETH/BTC reserves/ETH price is reached (low/high), providing owners an life-saving method to escape funds when losing the private key of the wallet.