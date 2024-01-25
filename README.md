Web3.js, a library facilitating smart contract interactions, is crucial for managing ERC-20 tokens on Ethereum. In our project, Web3.js connects to a deployed ERC-20 token, allowing function calls from our application.

Main Variables:
![image](https://github.com/hvruu/blockchain-assign2/assets/122508256/b13a80c8-7539-4574-b3c5-db9252b844be)

Usage:
Install Dependencies:
npm install web3 npm install dotenv
Create .env File:
ETHEREUM_NETWORK=<your_ethereum_network> INFURA_API_KEY=<your_infura_api_key> SENDER_ADDRESS=<your_ethereum_wallet_address> SENDER_PRIVATE_KEY=<your_ethereum_wallet_private_key>
Compile your solidity code:
Take ABI of your contract and create JSON file.

Execution Script
![image](https://github.com/hvruu/blockchain-assign2/assets/122508256/6ab6cafc-1000-4214-bbc1-9fac72d74ae2)

Output
![image](https://github.com/hvruu/blockchain-assign2/assets/122508256/8cf681c5-0b98-44d9-a01b-02ea7f89ca0e)

Envision Web3.js as a conduit linking your wallet to smart contracts on blockchains like Ethereum. It comprises a toolkit enabling you to:
Execute Contract Functions: For instance, you can trigger functions like purchasing tokens, transferring them to others, or participating in contract-based voting.
Retrieve Data: Web3.js facilitates the extraction of stored data from smart contracts. This may encompass details such as the sender and recipient of token transactions, along with transaction amounts.
Initiate Token Transfers via Web3.js: This process resembles making a traditional payment, but with tokens rather than conventional currency.
Various functions, including latestTransferHumanReadable(), getTransactionSender(), getTransactionRetriever(), transfer(), balanceOf(), and others, contribute to these capabilities.
