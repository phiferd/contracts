# Testing Parity Smart Contracts

BEFORE TESTING: ensure your test environment is properly setup for Babel and its ES2015 modules

```
cd /path/to/parity/contracts
npm install [-g] --save-dev . 
```

This will install necessary dependencies, and configure Babel to transpile JavaScript according to ES2015 specs (e.g. needed for `import {} from ""` syntax).

## Test Suite Layout

## Running Coverage Tests with solidity-coverage

## Running Unit & Integration Tests with Truffle

Make sure that you are in the contracts' base directory, and that your node/babel/truffle environment is configured correctly.

Then run:
```
truffle test
```

This will run all JavaScript tests Truffle recognizes under the `test` directory.

## Running Integration Tests with Truffle

## Running Fuzz Tests with Solfuzz

## Running Security Tests with ManticoreEVM
