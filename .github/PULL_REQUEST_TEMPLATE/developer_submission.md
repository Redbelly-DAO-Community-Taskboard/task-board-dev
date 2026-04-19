## Developer Task Submission

### Task Details

- **Task ID:** (e.g., TASK-01)
- **Task Title:** (e.g., Sybil-Proof ERC-20)
- **Your Discord Handle:** (@username)
- **Your Wallet Address (for payment):** (0x...)

---

### Deliverables Checklist

**Smart Contracts**
- [ ] Contract source code is in `/contracts/`
- [ ] Contract compiles without warnings on Solidity ^0.8.20
- [ ] OpenZeppelin imports are from v5.x
- [ ] `EligibilityGated` base contract (or equivalent) correctly integrated
- [ ] All functions that should be gated are gated
- [ ] Error messages are descriptive and KYC-specific (not generic "transaction reverted")

**Deployment**
- [ ] Deployment script is in `/scripts/`
- [ ] `.env.example` provided (no real private keys committed)
- [ ] Contract successfully deployed to Redbelly Testnet (Chain ID 153)
- [ ] **Testnet contract address:** `0x...`
- [ ] **Deployment transaction hash:** `0x...`
- [ ] Contract verified on block explorer (if supported)

**Tests**
- [ ] Test suite is in `/test/`
- [ ] Tests run with `npx hardhat test`
- [ ] Test coverage is 90% or above
- [ ] **Coverage report screenshot or output:** (paste or attach)
- [ ] Verified users can perform allowed actions
- [ ] Unverified users are correctly blocked
- [ ] Edge cases covered (see task spec for specific requirements)

**Frontend (if required by task)**
- [ ] React component(s) in `/frontend/` or linked repo
- [ ] SDK widget renders correctly
- [ ] Eligibility status displayed in real-time

**Documentation**
- [ ] Integration guide included (see task spec for required page count)
- [ ] Deployment steps documented
- [ ] Troubleshooting section included
- [ ] All code snippets in docs are tested and functional

---

### Proof of Work

**Testnet demonstration:** (describe or link to a screen recording showing the contract working as expected)

**Quality benchmark confirmation:** (describe how your submission meets each quality benchmark from the task spec)

---

### Notes for Reviewer

(Anything the reviewer should know: design decisions made, known limitations, trade-offs chosen)

---

### Reviewer Use Only

- [ ] All deliverables present
- [ ] Quality benchmarks met
- [ ] Failure criteria not triggered
- [ ] Approved for payment
- [ ] Revision requested (see comments)
