# Degen Gaming Token (DEGEN) README

## Introduction

Welcome to the Degen Gaming Token (DEGEN) repository! This repository contains the Solidity smart contract code for the DEGEN token, an ERC-20 compatible token designed for gaming purposes on the Avalanche Fuji Test Network. DEGEN tokens can be used for various in-game activities, rewards, and transactions within the gaming ecosystem.

This README file provides an overview of the DEGEN token contract and includes instructions on how to deploy the contract to the Avalanche Fuji Test Network using Remix Injector and how to interact with it using Remix.

## Contract Details

The `DegenToken.sol` file contains the source code for the DEGEN token contract. Here are the key details of the contract:

- Token Name: Degen Gaming Token
- Token Symbol: DEGEN
- Decimals: 18
- Total Supply: 0 (initially)

The contract includes standard ERC-20 functions such as `balanceOf`, `transfer`, `approve`, and `transferFrom`. It also includes additional functionalities for minting and burning tokens.

The contract owner has special privileges and is the only address allowed to mint new tokens. Other addresses can interact with the contract by transferring tokens, approving token transfers on their behalf, and burning their own tokens.

## Deployment on Avalanche Fuji Test Network using Remix Injector

To deploy the DEGEN token contract to the Avalanche Fuji Test Network using Remix Injector, follow these steps:

1. Open the [Remix](https://remix.ethereum.org/) online IDE in your browser.

2. Create a new file named `DegenToken.sol` and copy the contents of the `DegenToken.sol` file from this repository into it.

3. Select the Solidity compiler version `0.8.0` or a compatible version.

4. Compile the contract by clicking the "Compile" button.

5. Switch to the "Deploy & Run Transactions" tab.

6. In the "Environment" dropdown, select "Injected Web3" to connect Remix to your MetaMask wallet.

7. Make sure your MetaMask wallet is connected to the Avalanche Fuji Test Network.

8. Click the "Deploy" button next to the `DegenToken` contract.

9. Confirm the deployment transaction in MetaMask.

10. Wait for the deployment transaction to be confirmed on the Avalanche network.

11. Once the contract is deployed, you will see the contract address in the Remix console. Make note of this address for future interactions.

## Interacting with the Contract using Remix

After deploying the DEGEN token contract to the Avalanche Fuji Test Network, you can interact with the contract using Remix. Here are the steps to get started:

1. Open the [Remix](https://remix.ethereum.org/) online IDE in your browser.

2. In the "File Explorer" section, locate the `DegenToken.sol` file and open it.

3. In the "Deployed Contracts" section, click on the contract named `DegenToken`.

4. In the "At Address" input field, enter the contract address obtained during deployment.

5. Click the "At Address" button to load the contract instance.

6. You can now interact with the DEGEN token contract through the provided functions.

   - Use the `balanceOf` function to check the token balance of a specific address.
   - Use the `transfer` function to send DEGEN tokens from your address to another address.
   - Use the `approve` function to allow another address to spend a specific amount of DEGEN tokens on your behalf.
   - Use the `transferFrom` function to transfer DEGEN tokens on behalf of another address.
   - Use the `mint` function (accessible only to the contract owner) to mint new DE

GEN tokens.
   - Use the `burn` function to burn a specific amount of your DEGEN tokens.

7. Set the required parameters for each function and click the corresponding button to execute the transaction.

8. Confirm the transaction details and sign the transaction in MetaMask.

9. Wait for the transaction to be confirmed on the Avalanche network.

10. You can view the transaction status and emitted events in the Remix console.

## Authors

RIDAM ADITYA SINHA

https://www.linkedin.com/in/ridam-sinha-188133210/

ridamsinha20@gmail.com

## License

The Degen Gaming Token contract is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for more information.

## Disclaimer

Please note that this contract and the associated README file are provided for informational purposes only. Deploying and interacting with smart contracts involves risks, and it is your responsibility to review and understand the code before proceeding. Make sure to exercise caution and perform appropriate testing before deploying any smart contract on a live network.

If you have any questions or need further assistance, please feel free to reach out to the Degen Gaming Token development team.
