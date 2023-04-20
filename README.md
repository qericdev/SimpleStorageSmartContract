# SimpleStorage Contract

The `SimpleStorage` contract is a basic Solidity smart contract that allows storing and retrieving a number on the Ethereum blockchain.

## Features

- Initialize the contract with a custom number
- Get the current number
- Set a new number

## Contract

The contract is written using Solidity version 0.8.12.

### State Variables

- `number`: A private uint256 variable that stores the current number.

### Constructor

- `constructor(uint256 _number)`: Initializes the contract with a custom number.

### Functions

- `getNumber()`: A public view function that returns the current number.
- `setNumber(uint256 _number)`: A public function that sets a new number.

## Usage

1. Deploy the contract with an initial number.
2. Call `getNumber()` to retrieve the current number.
3. Call `setNumber()` with a new number to update the stored number.

## License

This contract is licensed under the MIT License.