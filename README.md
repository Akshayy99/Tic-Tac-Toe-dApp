# Tic Tac Toe in Blockchain

## Prerequisites

> truffle
> ganache / gananche-cli 
> solc
> web3

## Installation

- Clone this repo
- On the terminal, run the following command:
```bash
npm -g install truffle ganache-cli solc web3
```

## To run tests

- Compile using 
```bash 
truffle compile
``` 
It should download the required solc version automatically 
- Start the ganache network 
```bash
ganache-cli -p 7545 -e 100 -i 5777
```
- Deploy using 
```bash
truffle deploy
```
- Run tests using 
```bash
truffle test
```
