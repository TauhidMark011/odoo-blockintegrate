### AVAX Odoo module to interact with accounts and smart contracts

A minimal odoo module to interact with the Avalanche blockchain.

### Goal
the smart contracts development and integration with Odoo. Of course, there are many alternatives to achieve this,a blockchain compatible with the Ethereum virtual machine to run Solidity code faster.


### Avax

Avalanche ([AVAX](https://www.avax.network/)) is an Ethereum compatible 3rd generation blockchain.

### Odoo

Odoo module to interact with smart contracts in Avax.

The architecture of this module is oriented to test the Avax integration only.

This Odoo module uses [Web3.py](https://web3py.readthedocs.io/en/stable/#). Web3.py is a python library for interacting with Ethereum, and it works perfectly with Avax too.

It has the Avax connector implementation, accounts, and smart contract functionality with certain limitations.


I packed this inside a docker-compose.

#### basic steps:

- Initialize the docker container
- Create a new odoo database
- Search and install the Avax module
- Create an Avax account from odoo
- Don't forget to fund your account with the faucet
- Create a smart contract, paste de solidity content in the solidity field
- Compile and deploy the smart contract
- Test the smart contract functionally. You need funds to write, to pay the gas of the transactions, but not for reading.

