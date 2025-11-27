# 🎧 Simple Music Player – Solidity Smart Contract

A beginner-friendly Solidity smart contract that acts as a simple, gas-optimized on-chain music playlist.  
This project is perfect for anyone learning blockchain, smart contracts, events, and storage in Ethereum.

---

## 📌 Project Description

The **Simple Music Player** is a lightweight Solidity contract that stores songs on the blockchain.  
Users can add songs, view them, and “play” a song — which triggers an event.  
The design is intentionally simple so beginners can understand how smart contracts work without complexity.

---

## 🚀 What It Does

- Stores songs using a `Song` struct  
- Allows users to add new songs  
- Retrieves song details by index  
- Emits an event when a song is played  
- Tracks the last played song  

This contract is ideal for experimenting with **structs**, **mappings**, **events**, and **basic DApp logic**.

---

## ⭐ Features

### 🎵 Add Songs  
Add a new song by providing the title and artist.

### 📚 View Songs  
Read any song stored on the blockchain with just its index.

### ▶️ Play Songs  
Simulates playing a song using:
- an event (`SongPlayed`)
- the `lastPlayed` state update

### ⚡ Gas-Efficient  
Uses:
- `mapping` instead of dynamic array  
- `calldata` parameters  
- no default songs in constructor  

This keeps deployment and execution costs low.

---

## 📝 Smart Contract Code

```solidity
//paste your code
