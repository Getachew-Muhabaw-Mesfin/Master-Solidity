   Variables and types

There are 3 types of variables in Solidity

1. Local

Declared inside a function and are not stored on blockchain

2. State

Declared outside a function to maintain the state of the smart contract

Stored on the blockchain

3. Global

Provide information about the blockchain. They are injected by the Ethereum Virtual Machine during runtime.

Includes things like transaction sender, block timestamp, block hash, etc.

Examples of global variables

The scope of variables is defined by where they are declared, not their value. Setting a local variable's value to a global variable does not make it a global variable, as it is still only accessible within it's scope.v