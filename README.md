# Solana Web3
A TypeScript library for interacting with the Solana blockchain.

## What is it?
Solana Web3 is a library that provides a simple and intuitive way to interact with the Solana blockchain. It allows you to send transactions, query account balances, and more.

## Installation
To install Solana Web3, run the following command:
```bash
npm install
```
or
```bash
yarn install
```
## Running
To run the library, simply import it into your TypeScript project:
```typescript
import { Connection, PublicKey } from './src';
```
## Example
Here's a quick example of how to use Solana Web3 to query an account balance:
```typescript
import { Connection, PublicKey } from './src';

const connection = new Connection('https://api.devnet.solana.com');
const publicKey = new PublicKey(' votre-public-key-ici');

connection.getBalance(publicKey).then((balance) => {
  console.log(`Balance: ${balance}`);
});
```
Replace 'votre-public-key-ici' with a real public key.

## Contributing
Contributions are welcome! If you'd like to contribute to Solana Web3, please fork this repository and submit a pull request.