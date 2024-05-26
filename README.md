MyToken Smart Contract
This is a simple smart contract for a token called "medusa" with the abbreviation "md". The contract is written in Solidity, a statically-typed programming language designed for developing smart contracts that run on the Ethereum Virtual Machine (EVM).

Requirements
-The contract has public variables that store the details about the token: Token Name, Token Abbreviation, and Total Supply.
-The contract has a mapping of addresses to balances (address => uint).
-The contract has a mint function that takes an address and a value as parameters. This function increases the total supply by that number and increases the balance of the "sender" address by that amount.
-The contract has a burn function that works the opposite of the mint function. It takes an address and a value as parameters, then deducts the value from the total supply and from the balance of the "sender".
-The burn function has conditionals to make sure the balance of the "sender" is greater than or equal to the amount that is supposed to be burned.

Contract Details
-Token Name: medusa
-Token Abbreviation: md
-Total Supply: Initially set to 0, but can be increased using the mint function.

Functions
mint
-This function takes an address and a value as parameters. It increases the total supply by the value and increases the balance of the "sender" address by that amount.

burn
-This function takes an address and a value as parameters. It checks if the balance of the "sender" is greater than or equal to the value. If true, it decreases the total supply by the value and decreases the balance of the "sender" address by that amount.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
