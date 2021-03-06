# Tools

Here we provide a list of tools available for your development needs. They
are sorted by programming language. Right now, the Rust ecosystem is the most
mature and it's possible to get started by building on Substrate today. As the
ecosystems surrounding other programming languages expand, the sections below
will be filled out.

## Block Explorers

 - [Polka.io](https://polka.io) - Blockchain explorer for Polkadot.
 - [PolkadotJS Apps Explorer](https://polkadot.js.org/apps/#/explorer) - Polkadot dashboard block explorer. Currently connects to the Alexander testnet by default, but can be configured to connect to other remote or local endpoints.
 - [Polkascan](https://polkascan.io/) - Blockchain explorer for Polkadot. **Currently down.**

## Wallets

 - [Polkawallet](https://polkawallet.io/) - A mobile wallet for Polkadot on both iOs and Android. Currently in development but a Beta version is available for download. Follow development on [GitHub](https://github.com/polkawallet-io/polkawallet-RN).
 - [SpeckleOS](https://www.speckleos.io/) - Browser extension wallet. In development - follow progress on [GitHub](https://github.com/SpeckleOS/speckle-browser-extension).
 - [ImageWallet](https://www.reddit.com/r/dot/comments/ah3py1/introducing_alpha_version_of_httpsimagewalletio/) - Cross-chain wallet with visuals. **In development with planned support for Polkadot and all Substrate chains.**

## Rust

### Clients

- [Polkadot](https://github.com/paritytech/polkadot) - Rust implementation of the Polkadot Runtime Environment.

### Tools

- [Substrate](https://github.com/paritytech/substrate) - Blockchain development platform written in Rust. Polkadot is being built on top of Substrate.
- [Substrate Development Hub](https://docs.substrate.dev) - Comprehensive documentation and tutorials for building a blockchain using Substrate.

## C++

- [Kagome](https://github.com/soramitsu/kagome) - A C++ Polkadot client developed by [Soramitsu](https://github.com/soramitsu).

## Go

- [Gossamer](https://github.com/ChainSafe/gossamer) - A Go implementation of the Polkadot Runtime Environment.
- [Golkadot](https://github.com/opennetsys/golkadot) - A Go implementation of Polkadot Substrate.

## JS

### Client

- [PolkadotJS client](https://github.com/polkadot-js/client) - Alternative client for JavaScript enthusiasts.

Documentation on the [Polkadot-JS](https://polkadot.js.org) is a good starting point for diving deeper.

Once you've configured and started to run a local node, you can interact with it through the generic polkadot [explorer](https://polkadot.js.org/apps/#/explorer).

### Libraries

 - [@polkadot/keyring](https://polkadot.js.org/common/keyring/) To create / load accounts in JavaScript, helpful for creating wallets or any application which will require the user to write to chain. [Examples](https://polkadot.js.org/common/examples/keyring/)
 - [@polkadot/util](https://polkadot.js.org/common/util/) Useful utility functions like checking if a string is hex encoded. **!Needs documentation**
 - [@polkadot/util-crypto](https://polkadot.js.org/common/util-crypto/) Crypto utilities that will come into handy while developing with Polkadot. **!Needs documentation**
 - [oo7-polkadot](https://github.com/polkadot-js/oo7-polkadot) A bonds library for Polkadot. **!Needs documentation**

### CLI Tools

 - [@polkadot/api-cli](https://github.com/polkadot-js/tools/tree/master/packages/api-cli) Simple commandline interface for the polkadot API. **!Needs documentation**
 - [@polkadot/monitor-rpc](https://github.com/polkadot-js/tools/tree/master/packages/monitor-rpc) Simple RPC monitor for Polkadot. **!Needs documentation**
