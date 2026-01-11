# Adassa FinTech

## DeFi Arbitrage Engine Project

A research-grade DeFi arbitrage system combining off-chain JavaScript
price intelligence with on-chain atomic execution using Solidity.

⚠️ This project is for educational and engineering purposes.
Profitability is not guaranteed.

---

### Architecture Overview

- JavaScript Engine
  - Price discovery
  - Slippage simulation
  - Gas-aware profit calculation
  - Execution decision logic

- Solidity Smart Contract
  - Atomic arbitrage execution
  - Flash loan support
  - Profit enforcement
  - Safety guards

---

### Supported Protocols (Initial)
- Uniswap V2
- SushiSwap
- Aave (flash loans)

---

### Project Goals
- Correct arbitrage detection
- Safe atomic execution
- MEV-aware design
- Strong engineering practices

---

### Non-Goals
- Guaranteed profitability
- Production trading
- Capital deployment

---

### Repository Structure

- docs/ Architecture & research notes
- js-engine/ Off-chain arbitrage logic
- contracts/ Solidity smart contracts
- scripts/ Deployment & interaction
- test/ Solidity unit tests

### Disclaimer
This project interacts with DeFi protocols.
Use at your own risk. No financial advice.

## Development

- For Jekyll website, go to the project directory and issue the command `bundle exec jekyll serve`
