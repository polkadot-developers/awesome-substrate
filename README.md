![Substrate Logo](substrate_logo_dark.png)

# Awesome Substrate

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> Awesome lists are curated lists of awesome projects and resources concerning a topic, a
> programming language, a technology, etc.

-[Developer Resources: Awesome Lists](https://codeburst.io/developer-resources-awesome-lists-2c85b45a0216)

This is the official **Awesome List** for [Substrate](https://substrate.io/); it is maintained by
the [Substrate Developer Hub](https://substrate.dev/) team.

## What is Substrate?

Substrate is a framework for building upgradable, modular and efficient blockchains. Substrate is an
[open-source](https://github.com/paritytech/substrate) library of [Rust](https://www.rust-lang.org/)
code that is maintained by [Parity Technologies](https://www.parity.io/).

## Table of Contents

- [Official Resources](#official-resources)
- [Recordings](#recordings)
- [Workshops & Demos](#workshops--demos)
- [Community Resources](#community-resources)
- [Frameworks](#frameworks)
- [Templates](#templates)
- [Pallets](#pallets)
- [Client Libraries](#client-libraries)
- [Ecosystem Tools](#ecosystem-tools)

## Official Resources

- [substrate.io](https://substrate.io/) - Product page
- [Developer Hub](https://substrate.dev/) - Developer portal
  - [Tutorials](https://substrate.dev/tutorials) - Guided exercises to get you started
  - [Knowledge Base](https://substrate.dev/knowledgebase) - In-depth documentation related to
    Substrate development
  - [Recipes](https://substrate.dev/recipes) - Working code examples that solve common problems
  - [Reference Docs](https://substrate.dev/rustdocs) - Rustdoc API documentation
- [Seminar](https://substrate.dev/seminar) - Collaborative learning on
  [Crowdcast](https://www.crowdcast.io/e/substrate-seminar)
- [Technical Chat](https://app.element.io/#/room/!HzySYSaIhtyWrwiwEV:matrix.org) - Ask questions &
  chat with other Substrate developers
- [Builders Program](https://www.substrate.io/builders-program) - white-glove support for visionary
  teams
- [Web3 Foundation Grants](https://web3.foundation/grants) - funding for ecosystem development
- [Users](https://www.substrate.io/substrate-users) - Teams building with Substrate
- [GitHub](https://github.com/paritytech/substrate) - Substrate source code
- [Developer Hub GitHub](https://github.com/substrate-developer-hub/) - Developer Hub repositories
- [Polkadot GitHub](https://github.com/paritytech/polkadot) - Substrate monorepo for multiple
  Parity-sponsored chains
- [Parity Blog](https://www.parity.io/blog/) - Read about updates in the Substrate ecosystem
- [Twitter](https://twitter.com/substrate_io) - Follow us to stay up-to-date

## Recordings

- [Introduction to Substrate](https://www.crowdcast.io/e/ocimgwg2)
- [Parachains, Cumulus & the Rococo Test Network](https://www.crowdcast.io/e/zpnjlj0r)
- [Enterprise Demo](https://www.crowdcast.io/e/substrate-seminar/6)
- [Bridges & Cross-Chain Interoperability](https://www.crowdcast.io/e/substrate-seminar/12)
- [Archive Indexing Engine](https://www.crowdcast.io/e/substrate-seminar/15)
- [Ethereum Apps on Substrate Chains](https://www.crowdcast.io/e/ethereum-apps-moonbeam)

## Workshops & Demos

- [UTXO Workshop](https://github.com/substrate-developer-hub/utxo-workshop) - Use Substrate to
  implement a Bitcoin-like chain
- [Cumulus Wokshop](https://substrate.dev/cumulus-workshop/#/) - Build a parachain with Cumulus
- [Enterprise Sample](https://github.com/substrate-developer-hub/substrate-enterprise-sample) - A
  fully-featured sample that uses a supply chain use case to demonstrate Substrate's rich set of
  capabilities

## Community Resources

- [DotLeap](https://dotleap.com/) - Community content and newsletter
- [Stack Overflow](https://stackoverflow.com/questions/tagged/substrate) - Questions tagged
  `substrate`
- [Reddit](https://www.reddit.com/r/substrate/) - Official subreddit
- [Polkadot Stack](https://github.com/w3f/General-Grants-Program/blob/master/grants/polkadot_stack.md) -
  Another awesome list maintained by our friends at [Web3 Foundation](https://web3.foundation/)
- [Subsocial](https://subsocial.network/) - Decentralized social network for Polkadot / Kusama ecosystem. Built on Substrate + IPFS.

## Frameworks

- [FRAME](https://substrate.dev/docs/en/knowledgebase/runtime/frame) - An idiomatic system for
  building Substrate runtimes
- [ink!](https://github.com/paritytech/ink) - Smart contract language for Substrate chains
- [Cumulus](https://github.com/paritytech/cumulus) - Simplified Polkadot-compatible parachains
- [Bridges](https://github.com/paritytech/parity-bridges-common) - A collection of tools for
  cross-chain communication
- [Frontier](https://github.com/paritytech/frontier) - End-to-end Ethereum emulation for Substrate
  chains
- [Polkadot-JS](https://polkadot.js.org/) - Rich framework for front-end development
- [SubstraTEE](https://www.substratee.com) - Trusted off-chain execution framework that uses
  [Intel SGX](https://en.wikipedia.org/wiki/Software_Guard_Extensions) trusted execution
  environments

## Templates

- [Node](https://github.com/substrate-developer-hub/substrate-node-template) - A fresh
  [FRAME](https://substrate.dev/docs/en/knowledgebase/runtime/frame)-based node, ready for hacking
- [Pallet](https://github.com/substrate-developer-hub/substrate-pallet-template) - Easily create
  pluggable blockchain capabilities
- [Parachain](https://github.com/substrate-developer-hub/substrate-parachain-template) - A new
  [Cumulus](https://github.com/paritytech/cumulus)-based Substrate node, ready for hacking
- [Front-End](https://github.com/substrate-developer-hub/substrate-front-end-template) - Use the
  [Polkadot-JS API](https://github.com/polkadot-js/api/) and [React](https://reactjs.org/) to build
  front-ends for Substrate-based chains

## Pallets

- [Open Runtime Module Library (ORML)](https://github.com/open-web3-stack/open-runtime-module-library) -
  Community maintained collection of Substrate runtime modules
- [Sunshine Bounty](https://github.com/sunshine-protocol/sunshine-bounty/tree/master/pallets) -
  Distributed autonomous organization (DAO) for administering a bounty program
- [Sunshine Identity](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/identity/pallet) -
  Keybase-inspired identity management
- [Sunshine Faucet](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/faucet/pallet) -
  Dispense resources for a development chain
- [Commodities](https://github.com/danforbes/pallet-nft) - Defines and implements a non-fungible
  token interface

## Client Libraries

- [`subxt`](https://github.com/paritytech/substrate-subxt) - Official Rust client
- [Substrate API Client](https://github.com/scs/substrate-api-client) - Rust client maintained by
  [Supercomputing Systems AG](https://www.scs.ch/)
- [Polkadot-JS API](https://github.com/polkadot-js/api/) - Semi-official Javascript library for
  Substrate-based chains
- [Python Substrate Interface](https://github.com/polkascan/py-substrate-interface) - Maintained by
  [Polkascan Foundation](https://polkascan.org/)
- [Go Substrate RPC Client](https://github.com/centrifuge/go-substrate-rpc-client/) - Maintained by
  [Centrifuge](https://centrifuge.io/)
- [Substrate C++ API](https://github.com/usetech-llc/polkadot_api_cpp) - Maintained by
  [Usetech](https://usetech.com/blockchain/)
- [Substrate .Net API](https://github.com/usetech-llc/polkadot_api_dotnet) - Maintained by
  [Usetech](https://usetech.com/blockchain/)

## Ecosystem Tools

- [Polkadot-JS Apps UI](https://polkadot.js.org/apps/) - Semi-official block explorer & front-end
  for Substrate-based chains
- [Polkadot-JS Extension](https://github.com/polkadot-js/extension) - Browser extension for
  interacting with Substrate-based chains
- [Sidecar](https://github.com/paritytech/substrate-api-sidecar) - REST service that runs alongside
  Substrate nodes
- [Archive](https://github.com/paritytech/substrate-archive) - Indexing engine for Substrate chains
- [TxWrapper](https://github.com/paritytech/txwrapper) - Helpful library for offline transaction
  creation
- [Subkey](https://substrate.dev/docs/en/knowledgebase/integrate/subkey) - Command line utility for
  working with cryptographic keys
- [Polkascan](https://polkascan.io/) - Multi-chain block explorer maintained by
  [Polkascan Foundation](https://polkascan.org/)
- [VSCode Substrate](https://marketplace.visualstudio.com/items?itemName=paritytech.vscode-substrate) -
  Official plugin for Visual Studio Code
- [Parity Signer](https://www.parity.io/signer/) - Upcycle an unused mobile phone into an air-gapped
  hardware wallet
- [Fork Off Substrate](https://github.com/maxsam4/fork-off-substrate) - Script to help bootstrap a
  new chain with the state of a running chain
- [Substrate debug-kit](https://github.com/paritytech/substrate-debug-kit) - A collection of tools
  and libraries for debugging Substrate-based chains, including  
  [`offline-election`](https://github.com/paritytech/substrate-debug-kit/tree/master/offline-election), 
  which is a tool that is used to predict nominated proof-of-stake elections. 
