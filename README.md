# Overview
The goal of this repository is to provide an alternative implementation of the beacon chain 
that was recently announced by the Ethereum Core dev team. As even the Ethereum Core dev team don't know how the finalized beacon chain
will be implemented, this is our contribution to the effort to transitioning Ethereum from a PoW blockchain to a PoS blockchain.

This is currently a work in progress and you can ask questions and contribute in our [gitter](https://gitter.im/chainsafe/lodestar-chain).

## What you need
You will need to go over the [specification](https://notes.ethereum.org/SCIg8AH5SA-O4C1G1LYZHQ?view#). You will also need to have a [basic understanding of sharding](https://github.com/ethereum/wiki/wiki/Sharding-FAQs). Note that that the specification is an ongoing document and will get outdated. The reference implementation by the Ethereum development team is written in Python and can be found [here](https://github.com/ethereum/beacon_chain).

In order to run the code in this repository, you will first need to run `npm install` to install all dependencies. Then, to run the tests, you will need to run `npm test`

## Contributors
If you would like to contribute, please submit an issue or talk to us on our [gitter](https://gitter.im/chainsafe/lodestar-chain).
