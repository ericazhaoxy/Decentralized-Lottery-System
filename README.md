# Decentralized-Lottery-System

## A decentralized lottery smart contract (Solidity) with tests and Sepolia deployment.

# Decentralized Lottery System (Sepolia)

A production-minded decentralized lottery (raffle) smart contract project designed with security, testing, and deployability in mind. Built for Ethereum Sepolia testnet.

## Highlights

- State machine design (OPEN → CALCULATING → OPEN)
- Clear events for indexing/analytics
- Comprehensive tests (unit + edge cases)
- Deployment scripts + reproducible setup
- Documentation: design + threat model

## Tech Stack

- Solidity
- Hardhat + Ethers.js
- (Planned) Chainlink VRF for verifiable randomness
- GitHub Actions CI

## Project Structure

- contracts/ # Solidity contracts
- test/ # automated tests
- scripts/ # deploy scripts
- docs/ # design docs, threat model, runbook
