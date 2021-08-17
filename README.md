# badger-strategies

This repo is used to coordinate the development, deployment and verification of Strategies by Badger DAO

## Steps

Typically the strat will go through:

- Initial Review, where we will ask for revisions
- For each revision, make sure to tag a release
- Deployment, we will have you deploy the strat so it can be run, make sure to add the strategy to the registry under your address
- Review Board: The review board will review the code as well for any security risks
- Release: The strategy is live and the issue is closed, make sure to publish all addresses related to the strat and to verify all contracts

## How to Add a new strategy for review

Create a new issue, with the name of the strategy, and the network it targets

Create a Release in your Strategy Repository

Link to that release in the Strategy Issue

If you're working with a new protocol, make a DD document and attach that as well, ideally reach out earlier with DD before writing code.

### What to do while you wait for review
- Make a release for your Strategy, tag it and then link that in the issue (no generic URL)
- Deploy your Strategy with development settings and have it run (ask FE to add it to test environment)
- Deposit some funds in the Strategy and Harvest it


## How to Review a Strategy
- Run all tests, take a screenshot and post it on the review
- Ask questions if you don't understand what the strategy is doing
- If you understand the strat, write a simple summary of what you think the strat does in the review as a sanity check so others can confirm or tell you that your interpretation is wrong
- Run security checks (Slither)
- Do a sanity check on all methods
- Check that tests and infra have not been compromised
- Say LGTM

## Before it can be promoted (on the Registry)
- Use the Production Controller
- Have an Harvest via ACL
- Run Emissions and BadgerTree via RewardsLogger
- Run script to check config by comparing it to the BadgerRegistry
- Frontend can deposit, withdraw, etc..
- APY Math is correct
- Review Board Security Check
