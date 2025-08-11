# Decentralized Marketplace

## Overview
A blockchain-based marketplace smart contract where:
- Sellers can list items for sale with a price.
- Buyers can purchase items directly on-chain.
- Transactions are transparent and trustless.

## Features
- List item with name and price.
- Purchase item with exact payment.
- Prevent sellers from buying their own items.
- Emit events for marketplace actions.

## How to Deploy & Test
1. Copy the code into [Remix IDE](https://remix.ethereum.org/).
2. Compile using Solidity `0.8.x`.
3. Deploy the contract on the Remix VM or testnet.
4. Use `listItem()` to create a new product.
5. Call `purchaseItem()` with the correct payment.

## License
This project is licensed under the MIT License.
