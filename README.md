## Ethereum Smart Contracts

&nbsp;

Just a few links I found useful to start with smart contracts in ethereum. 
    
 &nbsp;


### Basics

- [Introduction to Ethereum](https://ethereum.org/en/developers/docs/intro-to-ethereum/)
- [Ethereum networks](https://ethereum.org/en/developers/docs/networks/)
- [Accounts](https://ethereum.org/en/developers/docs/accounts/)
- [Transactions](https://ethereum.org/en/developers/docs/transactions/)
- [Ethereum Virtual Machine](https://ethereum.org/en/developers/docs/evm/)
- [Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
- [Anatomy of smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/anatomy/)
- [Gas and fees](https://ethereum.org/en/developers/docs/gas/)
- [Compiling smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/compiling/)

&nbsp;

### Tools needed


* **[Alchemy](https://alchemyapi.io/eth)**: A development platform and API that allows to make requests to the Ethereum blockchain without having to run a node
* **[Metamask](https://metamask.io/)**: an ethereum wallet that is also a browser plugin that let me use the Ethereum Mainnet to use dApps. It also allows me to use other networks to test without spending real gas in the Mainnet
* **Hardhat/Truffle**: development environment to debug, compile, deploy, etc. (see IDEs section)
* **Editor**: could be vsCode

&nbsp;

### IDEs (can choose one of the next list)

- [Hardhat documentation on deploying your contracts](https://hardhat.org/guides/deploying.html)
- [Truffle documentation on networks and app deployment](https://www.trufflesuite.com/docs/truffle/advanced/networks-and-app-deployment)

&nbsp;

### First Tutorial to understand the different pieces

- [Hello World Smart Contract for Beginners](https://ethereum.org/en/developers/tutorials/hello-world-smart-contract/)

&nbsp;

### Tokens
This project has examples of smart contracts creating tokens using the standar ERC20. This standard allows developers to create tokens in the same way, following a pre defined list of functions, making it easier to treat different tokens in the same way within the network. To know more about this standard read:
- [ERC-20 Token Standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)
- Explanation of the different functions in the standard, recommend reading this! [Understand the ERC-20 Token Smart Contract](https://ethereum.org/en/developers/tutorials/understand-the-erc-20-token-smart-contract/)
#### Examples
- This example contains an ERC20 token created from scratch. The smart contract also contains the interfaces defined in the ERC20 standard and the contract implementing those interfaces. [Example](https://github.com/nelsongallardo/eth-smart-contracts-beginner-guide/blob/main/examples/TokenWithInterfaces.sol)
- This example imports a library that contains the interfaces, making it easier to create the token without having to write the interfaces from scratch. [Example](https://github.com/nelsongallardo/eth-smart-contracts-beginner-guide/blob/main/examples/TokenWithLibrary.sol) - Also, heres's a guide of how to use the library: [Create ERC20 token](https://ethereum.org/en/developers/tutorials/create-and-deploy-a-defi-app/#create-the-erc20-token) 

### Further reading
- [Ethereum Gas Explained](https://defiprime.com/gas)
- [Web2 vs Web3](https://ethereum.org/en/developers/docs/web2-vs-web3/)
- [Nodes and Clients](https://ethereum.org/en/developers/docs/nodes-and-clients/)
- [Nodes as a service](https://ethereum.org/en/developers/docs/nodes-and-clients/nodes-as-a-service/)
- [Consensus mechanisms](https://ethereum.org/en/developers/docs/consensus-mechanisms/)
- [Proof of Work vs Proof of Stake: Basic Mining Guide](https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/)
- [Oracles](https://ethereum.org/en/developers/docs/oracles/)
- [Solidity documentation](https://docs.soliditylang.org/en/latest/introduction-to-smart-contracts.html)
- [What are ABIs?](https://docs.alchemy.com/alchemy/guides/eth_getlogs#what-are-ab-is)
