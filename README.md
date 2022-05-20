# DAO-C-Block: Marketplace for carbon-credit NFTs Fractions from forestry projects


As Web3 and the blockchain bleed more and more into the mainstream, new acronyms get thrown around regularly with little explanation as to what they mean, including this one: DAO.    

Decentralized autonomous organizations (DAOs) are kind of like clubs for crypto enthusiasts, only they typically operate under a shared goal, give each member equal say in making decisions, and can potentially have more money than most clubs would ever know what to do with. 

Within C-Block Chainlink project, the DAO plays an indipensable role in creating a healthy environment for voting to different proposals including but not limited to lots proposols.

In this repository, we are introducing a DAO that will be formed by auditors who are responsible to create proposals and push them for voting.

# Usage / Implementation

There is one smart contract that is needed to be governed:
1. `Proposals.sol`

This contract allows auditors to create new proposals and push them for voting. 


You'll need [testnet Rinkeby](https://faucet.rinkeby.io/) and [testnet LINK](https://rinkeby.chain.link/) in the wallet associated with your private key. 

```
brownie run scripts/governance_standard/deploy_and_run_for_proposals.py --network rinkeby
```
