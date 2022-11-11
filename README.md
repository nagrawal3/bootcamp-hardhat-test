# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```


## Lab portion

### Lab 1:
- Write a smart contract for issuing an ERC20 token.
- Restrict minting of token by either owner or approved wallet
- Only allow transfer of token between whitelisted wallet address
- ERC20 token should be Pausable
- Write test to validate functionality of contract.
  - Test should validate only authorize wallet can mint
  - Test should validate Pause functionality of token
- Deploy ERC20 token on Mumbai network

### Lab 2:
- Research when it is good to use upgradeable contract strategy vs migrate contract strategy
- On contract created in previous task, look ways to convert the contract to upgradeable contract (Psuedo code is fine). Research how upgradeable contracts are different than regular contracts.

