# task-board-dev

Developer submissions for the Redbelly DAO Community Task Board.

**Tasks covered:** 1 (Sybil-Proof ERC-20), 2 (CAT Vault), 3 (Dividend Automation), 4 (Credential Expiry Monitor), 10 (Network Dashboard), 13 (Zero-to-Hero Onboarding Kit)

---

## Before You Submit

1. Read the full task specification in the [Expanded Task Specifications document](#)
2. Set up your environment using the [Testnet Setup Guide](../resources/testnet-guide/TESTNET_SETUP.md)
3. Start from the [Hardhat Starter](../resources/hardhat-starter/) and [EligibilitySDK Boilerplate](../resources/eligibility-sdk-boilerplate/)
4. Confirm the eligibility contract address with the Redbelly core team before deployment

## Submission Requirements

All developer submissions must include:

- Smart contract source code (Solidity ^0.8.20)
- Deployment scripts targeting Redbelly Testnet (Chain ID 153)
- Test suite with minimum 90% coverage
- Testnet deployment proof (contract address + transaction hash)
- Documentation matching the page requirements in the task spec

## How to Submit

1. Build your deliverable in your own public GitHub repository
2. Open a Pull Request in this repo using the **Developer Submission** template
3. A technical reviewer will be assigned within 48 hours
4. You have one revision opportunity if feedback is returned
5. Upon approval, payment is processed within 24 hours

## Review Criteria

Reviewers evaluate against the Quality Benchmarks and Failure Criteria defined in each task specification. A submission fails if:

- Contract allows actions by unverified wallets
- Test coverage is below 90%
- Deployment scripts do not work on the current testnet
- Documentation is missing or contains broken code
