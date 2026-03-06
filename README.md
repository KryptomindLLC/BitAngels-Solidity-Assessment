# Smart Contract Coding Task – ERC20 Token with ETH Dividends

This repository contains the solution for the Solidity coding challenge.

The contract implements a mintable ERC-20 token backed by ETH deposits, similar to Wrapped ETH. Users can mint tokens by depositing ETH and burn tokens to redeem the equivalent ETH amount.

In addition, the contract supports ETH dividend distribution to token holders proportional to their token balance relative to the total supply. Dividends are assigned to holder addresses and remain claimable even if tokens are later transferred or burned.

The implementation also maintains an internal list of token holders to enable efficient dividend assignment.

## Setup

Install dependencies:

```bash
npm install
```

Run tests:

```bash
npm run test
```

All provided Hardhat tests pass successfully.

## Loom Walkthrough

Loom video demonstrating the implementation and test execution:

Loom: https://www.loom.com/share/82165bf02c4244049281281e4595d4b2
