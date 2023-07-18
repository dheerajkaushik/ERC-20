# Degen Gaming Token  (DEGEN) README

## Introduction

This repository contains the Solidity smart contract code for the DEGEN token, an ERC-20 token designed for gaming purposes. DEGEN tokens can be used for various in-game activities.

## Contract Details

The `DegenToken.sol` file contains the source code for the DEGEN token contract. Here are the key details of the contract:

- Token Name: Degen
- Token Symbol: DGN

# Functionality:
-Minting new tokens: The platform should be able to create new tokens and distribute them to players as rewards. Only the owner can mint tokens.
-Transferring tokens: Players should be able to transfer their tokens to others.
-Redeeming tokens: Players should be able to redeem their tokens for items in the in-game store.
-Checking token balance: Players should be able to check their token balance at any time.
-Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.
-updatename: update the name of token.
-updatesymbol: updatee the symbol of token.

The contract owner has special privileges and is the only address allowed to mint new tokens. Other addresses can interact with the contract by transferring tokens, approving token transfers on their behalf, and burning their own tokens.

## Deployment on Avalanche Fuji Test Network:-

To deploy the DEGEN token contract to the Avalanche Fuji Test Network using Remix Injector, follow these steps:

1. Open the [Remix](https://remix.ethereum.org/) online IDE in your browser.

2. Create a new file named `DegenToken.sol` and copy the contents of the `DegenToken.sol` file from this repository into it.

3. Select the Solidity compiler version `0.8.0` or a compatible version.

4. Compile the contract by clicking the "Compile" button.

5. Switch to the "Deploy" tab.

6. In the "Environment" dropdown, select "Injected Web3" to connect Remix to your MetaMask wallet.

7. Make sure your MetaMask wallet is connected to the Avalanche Fuji Test Network.

8. Click the "Deploy" button next to the `DegenToken` contract.

9. Confirm the deployment transaction in MetaMask.

10. Wait for the deployment transaction to be confirmed on the Avalanche network.

11. Once the contract is deployed.


   - Use the `balanceOf` function to check the token balance of a specific address.
   - Use the `transfer` function to send DEGEN tokens from your address to another address.
   - Use the `mint` function (accessible only to the contract owner).
   - Use the `burn` function to burn a specific amount of your DEGEN tokens.
   - -Use the `reedem` function to reedem in game token.

8. Confirm the transaction details and sign the transaction in MetaMask.

9. Wait for the transaction to be confirmed on the Avalanche network.

10. You can view the transaction status and emitted events in the Remix console.

## Authors

Dheeraj Kaushik

dkher4@gmail.com



## Disclaimer

Please note that this contract and the associated README file are provided for informational purposes only. Deploying and interacting with smart contracts involves risks, and it is your responsibility to review and understand the code before proceeding. Make sure to exercise caution and perform appropriate testing before deploying any smart contract on a live network.

If you have any questions or need further assistance, please feel free to reach out to the Degen Gaming Token development team.
