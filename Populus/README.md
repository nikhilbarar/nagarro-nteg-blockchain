# nagarro-nteg-blockchain Populus

Populus is a smart contract development framework for the Ethereum blockchain.

Documentation: http://populus.readthedocs.org/en/latest/
Development: https://github.com/pipermerriam/populus

This tooling is in the very early days of development.
Features
Compilation (currently Solidity only)
Deployment (to any JSON RPC server)
Testing (using pytest)

What makes Populus special?
The most compelling reason for you to use this framework is the simplicity of writing tests. Testing is done using the pytest testing framework. Populus provides testing fixtures to allow easy interaction with your contracts. Tests can be written against an ephemeral test chain backed by the eth-testrpc JSON RPC server, or by your own JSON-RPC server.

Populus also handles compilation and deployment of your contracts, though the controls for this are currently very limited.