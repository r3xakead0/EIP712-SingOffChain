# EIP-712 Signs Off-Chain

## Implement EIP-712 contract using OpenZeppelin contracts

### Step by step to create our project

01. Run the command `npm init`
02. Run the command `npm install --save-dev hardhat`
03. Run the command `npx hardhat`
04. Create an empty hardhat.config.js
05. Create a folder named contracts
06. Run the command `npm install @openzeppelin/contracts`
07. Create a file named EIP712MessageCounter.sol in contracts folder
08. Run the command `npx hardhat compile`
09. Create a folder named test
10. Run the command `npm install --save-dev @nomiclabs/hardhat-ethers chai ethers`
11. edit hardhat.config.js file and add `require("@nomiclabs/hardhat-ethers");`
14. Create a file named EIP712Counter.test.js in test folder
15. Run the command `npx hardhat test`

### How to run this code?

01. Clone or download the repository.
02. Run the command `npm install`.
03. To run the tests run the command `npx hardhat test`