**MyToken Contract**
This contract is a simple implementation of a token with the following features:
- Public variables to store the token name, abbreviation, and total supply.
- A mapping of addresses to balances.
- A mint function to create new tokens and assign them to a specified address.
- A burn function to destroy existing tokens and decrease the total supply and the balance of the sender.

**Usage**
**Minting Tokens**
To mint new tokens, call the mint function with the following parameters:

- _to: the address to receive the new tokens.
- _value: the number of tokens to mint.
Before minting new tokens, the contract checks if the sender has enough balance to cover the cost of the new tokens.

**Burning Tokens**
To burn existing tokens, call the burn function with the following parameters:
- _from: the address to burn the tokens from.
- _value: the number of tokens to burn.
Before burning tokens, the contract checks if the sender has enough balance to cover the number of tokens to be burned.

**Compilation**
This contract can be compiled with the Solidity compiler version 0.8.18 or higher.

**License**
This contract is released under the MIT License. See LICENSE for details.
