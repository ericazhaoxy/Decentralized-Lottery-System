# Decentralized Lottery System - Sepolia

## A decentralized lottery smart contract (Solidity) with tests and Sepolia deployment.

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

## Quickstart

### Install

```bash
npm install
```

## Compile

npx hardhat compile

## Test

npx hardhat test

## Deployment (Sepolia)

1. Create .env from .env.example
2. Configure RPC + private key
3. Deploy: npx hardhat run scripts/deploy.js --network sepolia

## Docs

- docs/design.md — architecture + state machine
- docs/threat-model.md — attack surface + mitigations

Roadmap

- MVP Lottery contract
- Full unit tests + coverage
- Sepolia deployment + Etherscan verification
- Chainlink VRF integration
- Minimal frontend demo

License
MIT
