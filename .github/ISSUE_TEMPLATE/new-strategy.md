---
name: New Strategy
about: Submitting a new strategy for review
title: ''
labels: ''
assignees: ''

---

# Strategy Review

### Description
Plaintext logic. Can be a link to README or other doc.

### Code Link 
Commit / Hash / Repo should be known from this.

## Due Diligence Document  (Link, but could also just be a .md file in repo)
This document evaluates the protocols that are interacted with as strategy positions.

## Deployed Contract (If present)

## Review By
* Ongoing: 
* Completed:

## Review by Security Board
* Not started / ongoing / completed

## Test Checks (screen shot of all test passing)

## Check Contract Delegation Tool (Only after wireup, before Beta)
https://github.com/Badger-Finance/badger-vaults-mix-v1.5/blob/main/scripts/7_single_vault_proxy_check.py


## Launch Checklist
- [ ] Strategy development - Strategist
- [ ] Strategy fork testing - Strategist/QA Pod
- [ ] Strategy review - Solidity Pod/QA pod
- [ ] Contracts deployment and initialization - Strategist/QA Pod
- [ ] Addition of vault to the Badger Registry - Strategist/QA Pod
- [ ] Wire-up of contracts to the UI (On-chain with RegistryV2) - UI/API pod
- [ ] Guestlist deployment and setup (If guarded launch) - Strategist/QA Pod
- [ ] Test deposit through the UI - Strategist/QA Pod
- [ ] Production tests of operational functions (Earn, Harvest, Tend) - Strategist/QA Pod
- [ ] Add vault/strategy addresses to the keeper bot - Emissions Pod
- [ ] Test a rewards claim (If new reward token is emitted) - Strategist/QA Pod
- [ ] APY and balance on UI verification - Strategist/QA Pod
- [ ] User Guide and Strategy diagram - Comms pod
- [ ] Contract addresses additions to Docs - Comms/QA pod
- [ ] Contracts delegation - Strategist/QA Pod
- [ ] Contracts' Production parameters and delegation verification - Solidity/QA pod
- [ ] Production launch - UI/API Pod
- [ ] Announcements - Comms pod
