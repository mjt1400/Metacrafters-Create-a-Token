# CREATE A TOKEN PROJECT USING SOLIDITY
This is a Solidity smart contract project that defines a token called "DOGGY" with the symbol "DY". The token is built on the Ethereum blockchain using the ERC20 token standard. The contract has two functions, "mint" and "burn", which can be used to create or destroy tokens, respectively.

## DESCRIPTION
The "mint" function takes two parameters, "_address" and "_value", and adds "_value" tokens to the "_address" account. The "totalSupply" variable is also increased by "_value".

The "burn" function takes two parameters, "_address" and "_value", and removes "_value" tokens from the "_address" account, as long as the account has a sufficient balance. The "totalSupply" variable is also decreased by "_value".

The contract includes the "SPDX-License-Identifier" statement, which is a standardized way of indicating the license under which the contract is released. In this case, the license is the MIT license.

## Getting Started

### Installation

Download the file and import it to your preferred IDE. I recommend using Remix, an Ethereum IDE.

### Executing the Program

After you downlod the file, run the compiler then deploy the contract in order to mint, burn and monitor token supply.
