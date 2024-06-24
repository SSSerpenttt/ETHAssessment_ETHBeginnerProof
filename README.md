# Project: Create a Token

This Solidity program is a simple Solidity Contract activity where we create a simple token.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract creates a token with specific details (Token Name, Token Abbrv., Total Supply). Moreover, the contract allows us to perform the following:
- Mint a token
- Check the token balance of an address
- Burn tokens for an address

## Getting Started

### Executing program

To run this program, it is recommended to use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol). Copy and paste the [project code](https://github.com/SSSerpenttt/ETHAssessment_ETHBeginnerProof/blob/main/ETHProject_ETHBeginnerProof.sol) into the file you just created.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile MyToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, expand the drop down bar of your deployed contract. You can interact with it through the following:
- Mint Function: Input an ethereum address (do not use a real address, use a dummy address) and the amount of tokens to mint.
- Balances: Input an ethereum address (use dummy address) to check its balance.
- Burn: Input and ethereum address (dummy address) and the amount of tokens to burn. If the address provided does not contain any tokens or the input is more than the balance of the address, nothing will be burned.

## Authors

Franz


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/SSSerpenttt/ETHAssessment_ETHBeginnerProof/blob/main/LICENSE) file for details
