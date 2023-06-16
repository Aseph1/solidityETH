# Creating a Token in Solidity

This is a representation of a straightforward Solidity-coded cryptocurrency contract. It is possible to issue and delete tokens (or currencies), and their circulation and value may be monitored in real-time. 

## Description

The Coin Contract is a smart contract written in Solidity that makes creating and burning tokens easier. It records token circulation and ownership. The contract provides built-in public variables for storing token-specific data like the Token Name, Token Abbreviation, and Total Supply. A mapping of addresses to balances may be used to track token ownership.

The contract contains a mint feature that adds money to the supply and transfers it to the balance of the "sender" address. On the other hand, the burn function reduces the total supply while also taking tokens away from the "sender" address's holdings. Conditionals are added to the burn function to ensure the "sender" address has a positive balance larger than or equal to the amount being burned.

## Getting Started

### Coding

1. Get starter code from the Metacrafters Solidity file. 
2. Make the necessary changes to the contract, such as revising the Token Name, Token Abbreviation, total supply, and values. 
3. Use a Solidity compiler or development environment of your choosing to compile the Solidity code. 
4. Use Remix to deploy the contract on the Ethereum network.

### Execution

With the mint function, tokens can be created by entering the required value (the number of tokens) and the address to which they should be sent. Using the burn function, where the owner's address and the token's value (in tokens) are arguments, is the second way to burn tokens. The function will deduct the specified amount from the supply and reduce the balance at the "sender" address's current address by the same amount.

## Help

If you have any problems or queries when working with Solidity, see the relevant documentation for your compiler or development environment. Support from online Solidity developer groups or forums is also available.

## Authors

Adrian Maglaque
ajmmaglaque@mymail.mapua.edu.ph

## License

The Adrian Maglaque License governs use of this work.
