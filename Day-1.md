Smart Contracts in Rust and connecting the backend and frontend using Javascript.
Blockchain Demo: https://andersbrownworth.com/blockchain/
Books: [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook)

Course Content:

-> Blockchain
-> Solana

## 1. Blockchain

### 1.1 What is Blockchain?

Blockchain is a **decentralized, distributive and immutable ledger.**

- **Centralized Network** - All the data is present in one server.

![[Pasted image 20230707014254.png]]

- **Decentralized Network:** data is distributed among the various peers.

![[Pasted image 20230707014454.png]]

![[Pasted image 20230707014905.png]]

Hash - is like the ID of the block.

![[Pasted image 20230707015400.png]]

Always the block hash starts with '0000', otherwise it will be invalid. Nonce is what ensures that this criteria is met.

### 1.2 Hashing Algorithm

[[/assets/Pasted image 20230707015036.png]]

It generates the digital fingerprint of any data. Nonce relates to block and consensus relates to blockchain. Consensus is how the blockchain is considered valid and nonce is for the block itself. Hash for each block takes data + previous block hash as data, so if one hash/data in the middle of the chain is changed every block following it has to be changed. thats how we maintain security.

**51% attack:**

Truth in blockchain = what majority says. 
If someone needs to actually 'truly' own a blockchain and change entire history. 

Step one: become trillionaire and own tons and tons of machines. 
Step 2: own 51% of the machines on the network and just say that they have consensus of the fake data that you want. 

This is called as 51% attack.

### 1.3 Immutable ledger

Once a data is stored on blockchain, it cannot be modified. 

### 1.4 P2P Networking

### 1.5 Mining

### 1.6 Consensus

Consensus protocol is how every node agrees on the working of a blockchain Eg, proof of work consensus mein sab nodes agree on the fact that a block will be validated only if a miner cryptographically verifies it that its true In proof of stake, nodes agree that only validatiors who have staked an amount can validate or verify a transaction.

![[Pasted image 20230707021911.png]]

Whenever a block has to be added in a blockchain, some complex mathematical computations have to be performed. All the peers simultaneously run a program, if the block is valid it will be added and the miner will be rewarded. 

![[Pasted image 20230707022046.png]]

### 1.7 Public Keys


## 2. Solana

Docs: https://docs.solana.com/

### 2.1 Introduction

- Before Solana -  we had Bitcoin by Satoshi Nakamoto. Ethereum and Blockchain by Vitaly Buterin, but it was slow, which allowed for web apps over blockchain.
- Solana solved the problems of speed and lesser transaction fees. 

### 2.2 Client Side Programming (JS)

### 2.3 NFT (Non-fungible Token)

### 2.4 Rust Programming Language

### 2.5 Program (Smart Contacts)

### 2.6 Program Derived Address

### 2.7 Decentralized Finance


