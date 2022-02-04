# Awesome Substrate [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> An awesome list is a list of awesome things curated by the Substrate community.

Substrate is a framework for building upgradable, modular and efficient
blockchains. Substrate is an open-source library of [Rust](https://www.rust-lang.org/) code that is
maintained by [Parity Technologies](https://www.parity.io/). Source code available on
[GitHub](https://github.com/paritytech/substrate).

## Contents

- [Resources](#resources)
- [Support](#support)
- [Social](#social)
- [Events](#events)
- [Blogs](#blogs)
- [Videos](#videos)
- [Templates](#templates)
- [FRAME Pallets](#frame-pallets)
- [Framework Extensions](#framework-extensions)
- [Client Libraries](#client-libraries)
- [Mobile](#mobile)
- [Tools](#tools)
- [Products and Services](#products-and-services)
- [Alternative Implementations](#alternative-implementations)
- [SCALE Codec](#scale-codec)

## Resources

- [Official Homepage](https://substrate.io/) - Vision, ecosystem, opportunities, and much more.
  - [Docs](https://docs.substrate.io/) - Developer documentation.
  - [Tutorials](https://docs.substrate.io/tutorials) - Guided exercises to get you started.
  - [How-to guides](https://docs.substrate.io/how-to-guides) - Workflows outlined to achieve a
    specific goal.
  - [Reference Docs](https://docs.substrate.io/rustdocs) - Versioned API documentation.
- [Developer Hub GitHub](https://github.com/substrate-developer-hub/) - Developer Hub repositories.
- [Ecosystem Projects](https://substrate.io/ecosystem/projects/) - Projects and teams building with
  Substrate.
- Technical Papers
  - [Polkadot Lightpaper](https://polkadot.network/Polkadot-lightpaper.pdf)
  - [Polkadot: Vision for a heterogeneous multi-chain framework](https://github.com/polkadot-io/polkadotpaper/raw/master/PolkaDotPaper.pdf)
  - [Overview of Polkadot and its Design Considerations](https://arxiv.org/abs/2005.13456.pdf)
    - [Chinese Translation](https://github.com/AmadeusGB/Overview-of-Polkadot) (by community)

- [DotJobs](https://dotjobs.net/) - A job board for the Substrate and Polkadot ecosystem projects,
  maintained by [Stateless.Money](https://stateless.money/).
- [Polkadot Stack](https://github.com/w3f/Grants-Program/blob/master/docs/polkadot_stack.md) - An
  `awesome list` maintained by our friends at [Web3 Foundation](https://web3.foundation/).

## Support

- [Stack Overflow](https://stackoverflow.com/questions/tagged/substrate) - Tagged with "Substrate"
  is best for all technical questions.
- [`subport`](https://github.com/paritytech/subport/issues) - Support repository to discuss use.
- [Builders Program](https://substrate.io/ecosystem/substrate-builders-program/) - White-glove
  solutions and dedicated support team for visionary teams using Substrate.
- [Web3 Foundation Grants](https://web3.foundation/grants) - Funding for ecosystem development.

## Social

- [Technical Chat](https://matrix.to/#/#substrate-technical:matrix.org) - Ask questions &
  chat with other Substrate developers.
- [Twitter](https://twitter.com/substrate_io) - Follow us to stay up-to-date.
- [Reddit](https://www.reddit.com/r/substrate/) - Official subreddit.

## Events

- [Sub0 Developer Conference](https://sub0.parity.io/) - Semiannual, online and in-person for all
  things Substrate.
- [Substrate Seminar](https://substrate.io/ecosystem/resources/seminar/) - Bi-weekly
  collaborative learning sessions.

## Blogs

- [Official](https://www.parity.io/blog/tag/parity-substrate) - Published by Parity.
- [DotLeap](https://dotleap.com/) - Polkadot and Substrate Community blog and newsletter.

## Videos

- [Parity YouTube](https://www.youtube.com/c/paritytech)
  - [Substrate Seminar (YouTube Archive)](https://www.youtube.com/playlist?list=PLp0_ueXY_enXRfoaW7sTudeQH10yDvFOS)
  - [Sub0 Conference Oct. 2020](https://www.youtube.com/playlist?list=PLp0_ueXY_enUZk1RuEAU9ly5h0wy5FuLs)
  - [Sub0 Conference Dec. 2019](https://www.youtube.com/playlist?list=PLp0_ueXY_enWZ4UZE7rM0hdT8Z_ZTjU5V)
  - [Sub0 Conference Apr. 2019](https://www.youtube.com/playlist?list=PLp0_ueXY_enWqrfP_vR4PLhzQj76fLT8y)
- [New Seminar Crowdcast]( https://www.crowdcast.io/e/substrate-seminar-2/) - Upcoming events and
  latest recordings.
- [Old Seminar Crowdcast]( https://www.crowdcast.io/e/substrate-seminar/) - Archive only.
- [Substrate: A Rustic Vision for Polkadot by Gavin Wood at Web3 Summit 2018](https://www.youtube.com/watch?v=0IoUZdDi5Is)
- [Polkadot Network Technical Explainers](https://www.youtube.com/playlist?list=PLOyWqupZ-WGuAuS00rK-pebTMAOxW41W8)

## Templates

- [Base](https://github.com/substrate-developer-hub/substrate-node-template) - Minimal FRAME-based
  node, ready for hacking. 
- [Parachain](https://github.com/substrate-developer-hub/substrate-parachain-template) - Cumulus
  enabled Substrate node, ready for hacking.   
- [Frontier](https://github.com/substrate-developer-hub/frontier-node-template/) - Fronter enabled
  EVM and Ethereum RPC compatible Substrate node, ready for hacking. 
- [Front-End](https://github.com/substrate-developer-hub/substrate-front-end-template) - Polkadot-JS
  API and [React](https://reactjs.org/) app to build front-ends for Substrate-based chains. 
- [`substrate-stencil`](https://github.com/kaichaosun/substrate-stencil) - A template for a
  Substrate node that includes staking and governance capabilities.

## FRAME Pallets

- [Included in Substrate](https://github.com/paritytech/substrate/tree/master/frame) - Officially
  supported.
- [Open Runtime Module Library (ORML)](https://github.com/open-web3-stack/open-runtime-module-library) - Community
  maintained collection of Substrate runtime modules. 
- [Sunshine Bounty](https://github.com/sunshine-protocol/sunshine-bounty/tree/master/pallets) - Distributed
  autonomous organization (DAO) for administering a bounty program.
- [Sunshine Identity](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/identity/pallet) - Keybase-inspired
  identity management.
- [Sunshine Faucet](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/faucet/pallet) - Dispense
  resources for a development chain.
- [Commodities](https://github.com/danforbes/pallet-nft) - Defines and implements a non-fungible
  token interface.
- [Chainlink Feed Pallet](https://github.com/smartcontractkit/chainlink-polkadot) - Chainlink feed
  pallet and example node showing how to integrate to Substrate chains.

## Framework Extensions

- [FRAME](https://docs.substrate.io/v3/runtime/frame/) - A system for building Substrate runtimes.
- [ink!](https://github.com/paritytech/ink) - Rust smart contract language for Substrate chains.
- [Cumulus](https://github.com/paritytech/cumulus) - A set of tools for writing Substrate-based
  Polkadot parachains.
- [Bridges](https://github.com/paritytech/parity-bridges-common) - A collection of tools for
  cross-chain communication.
- [Frontier](https://github.com/paritytech/frontier) - End-to-end Ethereum emulation for Substrate
  chains.
- [Polkadot-JS](https://polkadot.js.org/) - Rich JavaScript API framework for front-end development.
- [IntegriTEE](https://book.integritee.network/) - Trusted off-chain execution framework that uses
  [Intel SGX](https://en.wikipedia.org/wiki/Software_Guard_Extensions) trusted execution
  environments.

## Client Libraries

- [`subxt`](https://github.com/paritytech/substrate-subxt) - Official Rust client.
- [Substrate API Client](https://github.com/scs/substrate-api-client) - Rust client maintained by
  [Supercomputing Systems AG](https://www.scs.ch/).
- [Polkadot-JS API](https://github.com/polkadot-js/api/) - Semi-official JavaScript library for
  Substrate-based chains.
- [Python Substrate Interface](https://github.com/polkascan/py-substrate-interface) - Maintained by
  [Polkascan Foundation](https://polkascan.org/).
- [Go Substrate RPC Client](https://github.com/centrifuge/go-substrate-rpc-client/) - Maintained by
  [Centrifuge](https://centrifuge.io/). 
- [Substrate C++ API](https://github.com/usetech-llc/polkadot_api_cpp) - Maintained by
  [Usetech](https://usetech.com/blockchain/).
- [Substrate .Net API](https://github.com/usetech-llc/polkadot_api_dotnet) - Maintained by
  Usetech.
- [Substrate .NET Standard API](https://github.com/dotmog/SubstrateNetApi) - Used in
  [nuget](https://www.nuget.org/packages/SubstrateNetApi/), and
  [Unity 3D integration example](https://github.com/darkfriend77/Unity3DExample) - Maintained by
  [DOTMog](https://dotmog.com/).
- [Kotlin Substrate Client](https://github.com/NodleCode/substrate-client-kotlin) - Maintained by 
  [Nodle.io](https://github.com/NodleCode)
- [`sube`](https://github.com/virto-network/sube) - Lightweight Rust client library and CLI with support for type information.
- [Subscan Go Utilities](https://github.com/itering/subscan-essentials) - SS58 and more, developed by Subscan.


## Mobile

- [React-Native-Substrate-Sign](https://github.com/paritytech/react-native-substrate-sign) - Rust
  library for React Native.
- [Polkadot-Dart](https://github.com/Pocket4D/Polkadot-Dart) - Dart Substrate API.
- [PolkaWallet SDK](https://github.com/polkawallet-io/sdk) - Flutter SDK for Substrate-based App.
- [Fearless Utils iOS](https://github.com/soramitsu/fearless-utils-iOS) - iOS Substrate tools.
- [Fearless Utils Android](https://github.com/soramitsu/fearless-utils-Android) - Android Substrate tools.

## Tools

- [Polkadot-JS Apps UI](https://polkadot.js.org/apps/) - Semi-official block explorer & front-end
  for Substrate-based chains.
- [Polkadot-JS Extension](https://github.com/polkadot-js/extension) - Browser extension for
  interacting with Substrate-based chains.
- [Polkadot Tool Index](https://wiki.polkadot.network/docs/build-tools-index) - List of tools
  available for your development with Polkadot and any Substrate chain including Block Explorers,
  Wallets, Network Monitoring & Reporting, Clients, Benchmarking, Fuzzing, Forking, SCALE Codec, CLI
  Tools and much more.
- [Sidecar](https://github.com/paritytech/substrate-api-sidecar) - REST service that runs alongside
  Substrate nodes.
- [Archive](https://github.com/paritytech/substrate-archive) - Indexing engine for Substrate chains.
- [TxWrapper](https://github.com/paritytech/txwrapper) - Helpful library for offline transaction
  creation.
- [Substate](https://github.com/arrudagates/substate) - 100% no-std/wasm compatible Substrate
  storage key generator library for Rust.
- [Subkey](https://substrate.dev/docs/en/knowledgebase/integrate/subkey) - Command line utility for
  working with cryptographic keys.
- [Polkascan](https://polkascan.io/) - Multi-chain block explorer maintained by Polkascan
  Foundation.
- [VSCode Substrate](https://marketplace.visualstudio.com/items?itemName=paritytech.vscode-substrate) - Plugin
  for Visual Studio Code.
- [Parity Signer](https://www.parity.io/signer/) - Upcycle an unused mobile phone into an air-gapped
  hardware wallet.
- [Fork Off Substrate](https://github.com/maxsam4/fork-off-substrate) - Script to help bootstrap a
  new chain with the state of a running chain.
- [Substrate debug-kit](https://github.com/paritytech/substrate-debug-kit) - A collection of tools
  and libraries for debugging Substrate-based chains, including
  [`offline-election`](https://github.com/paritytech/substrate-debug-kit/tree/master/offline-election),
  which is a tool that is used to predict nominated proof-of-stake elections.
- [`sup`](https://github.com/clearloop/sup) - Command line tool for generating or upgrading a
  Substrate node.
- [Substrate Dev Hub Utils](https://github.com/danforbes/substrate-devhub-utils) - _Unofficial_
  utilities for working with official Substrate Developer Hub resources.
- [Subscan](https://www.subscan.io/) - Multi-network explorer for Substrate-based chains.
- [Substrate Docker Builders](https://github.com/ETeissonniere/substrate-nodeops) - A set of
  Dockerfiles and GitHub Actions to auto-build and push a Docker image for Substrate-based chains.
- [Halva](https://github.com/halva-suite/halva) - A toolchain for improving the experience of
  developing on Substrate.
- [`offchain::ipfs`](https://rs-ipfs.github.io/offchain-ipfs-manual/) - Substrate infused with
  [IPFS](https://ipfs.io/).
- [Gantree Library](https://github.com/gantree-io/gantree-lib-nodejs) - A suite of technologies for
  managing Substrate-powered parachain networks via rapid spin-up & tear-down.
- [Redspot](https://github.com/patractlabs/redspot) - A
  [Truffle](https://www.trufflesuite.com/truffle)-like toolkit for smart contracts for the FRAME
  Contracts pallet.
- [Proxy Hot Wallet Demo](https://github.com/emostov/proxy-hot-wallet) - A demonstration of a
  secure, convenient, and flexible hot wallet architecture built on Substrate primitives.
- [Substrate Faucet Bot](https://github.com/starkleytech/substrate-faucet) - Python-based faucet for
  development purposes.
- [Hydra](https://github.com/Joystream/hydra) - A GraphQL framework for Substrate nodes.
- [Substrate Graph](https://github.com/playzero/substrate-graph) - GraphQL indexer for
  Substrate-based chains.
- [SubQuery](https://subquery.network) - A GraphQL indexer and query service that allows users to
  easily create indexed data sources and host them online for free.
- [Megaclite](https://github.com/patractlabs/megaclite) - Zero-knowledge tools for the Polkadot
  ecosystem.
- [Europa](https://github.com/patractlabs/europa) - A sandbox for the Substrate runtime execution
  environment.
- [Jupiter](https://github.com/patractlabs/jupiter) - Testnet for smart contracts written for the
  FRAME Contracts pallet.
- [Staking Rewards Collector](https://github.com/w3f/staking-rewards-collector) - A script to parse
  and output staking rewards for a given Kusama or Polkadot address and cross-reference them
  with daily price data.
- [`polkadot-scripts`](https://github.com/paritytech/polkadot-scripts) - A collection of scripts Parity uses to diagnose Polkadot/Kusama.
- [`polkadot-launch`](https://github.com/shawntabrizi/polkadot-launch) - Simple CLI tool to launch a
  local Polkadot test network.
- [`polkadot-starship`](https://github.com/koute/polkadot-starship) - Another tool to launch a local
  Polkadot test network, with emphasis on the ability to run big testnets.
- [`substrate-js-utils`](https://github.com/shawntabrizi/substrate-js-utilities) - A
  set of useful JavaScript utilities for Substrate that uses the Polkadot{JS} API. Also
  [deployed as a website](https://www.shawntabrizi.com/substrate-js-utilities/).
- [`substrate-graph-benchmarks`](https://github.com/shawntabrizi/substrate-graph-benchmarks) - Graph
  the benchmark output of FRAME pallets.
- [`substrate-balance-calculator`](https://github.com/shawntabrizi/substrate-balance-calculator) - Breakdown
  the balances of your Substrate account.
- [`substrate-balance-graph`](https://github.com/shawntabrizi/substrate-balance-graph) - Create a
  graph of the token balance over time of a Substrate address.
- [`polkadot-js-bundle`](https://github.com/shawntabrizi/polkadot-js-bundle) - A standalone JS
  bundle that contains Polkadot{JS} libraries.
- [`substrate-society`](https://github.com/shawntabrizi/substrate-society) - A basic front-end for
  the FRAME Society pallet.
- [Aleph.im](https://aleph.im) - Scalable, decentralized database, file storage, and computation
  services for Substrate chains and more.
- [`subsee`](https://github.com/ascjones/subsee) - CLI to inspect metadata of a Substrate node as
  JSON.
- [`polkadot-runtime-prom-exporter`](https://github.com/paritytech/polkadot-runtime-prom-exporter/) - A
  [Prometheus](https://prometheus.io/) exporter for Polkadot runtime metrics (modifiable for Substrate use).
- [`subwasm`](https://github.com/chevdor/subwasm) - CLI to inspect a runtime WASM blob offline. It
  shows information, metadata and can compare runtimes. It can also help you fetch a runtime
  directly from a node.
- [`srtool`](https://github.com/paritytech/srtool) - Docker image to deterministically build a runtime.
- [`srtool-cli`](https://github.com/chevdor/srtool-cli) - CLI frontend for the `srtool` Docker image.
- [`srtool-actions`](https://github.com/chevdor/srtool-actions) - GitHub actions to easily use the
  `srtool` Docker image to build your own runtime.
- [SS58 Transform](https://polkadot.subscan.io/tools/ss58_transform) - Display key's addressees with all SS58 prefixes.

## Products and Services

- [OnFinality](https://onfinality.io) - Free and paid services to shared Substrate based
  nodes.

## Alternative Implementations

- [Gossamer](https://github.com/ChainSafe/gossamer) - A Polkadot client implemented in Go; from
  [ChainSafe](https://chainsafe.io/).
- [Kagome](https://kagome.readthedocs.io/en/latest/) - A C++17 implementation of the Polkadot client;
  from [Soramitsu](http://www.soramitsu.co.jp/).
- [LimeChain AssemblyScript Runtime](https://github.com/LimeChain/as-substrate-runtime) - An
  account-based Substrate proof-of-concept runtime written in AssemblyScript; from
  [LimeChain](https://limechain.tech/).

## SCALE Codec

- [Codec Definition](https://docs.substrate.io/v3/advanced/scale-codec/) - Official
  codec documentation.
- [Parity SCALE Codec](https://github.com/paritytech/parity-scale-codec) - Reference implementation
  written in Rust.
- [AssemblyScript](https://github.com/LimeChain/as-scale-codec) - Maintained by LimeChain.
- [TypeScript](https://github.com/polkadot-js/api/tree/master/packages/types) - Maintained by
  Polkadot-JS.
- [Go](https://github.com/itering/scale.go) - Maintained by [Itering](https://www.itering.com/).
- [C](https://github.com/MatthewDarnell/cScale) - Maintained by Matthew Darnell.
- [C++](https://github.com/soramitsu/kagome/tree/master/core/scale) - Maintained by Soramitsu.
- [Haskell](https://github.com/airalab/hs-web3/tree/master/src/Codec) - Maintained by
  [Robonomics Network](https://robonomics.network/).
- [Java](https://github.com/emeraldpay/polkaj/tree/master/polkaj-scale) - Maintained by
  [Emerald](https://emerald.cash/).
- [Ruby](https://github.com/itering/scale.rb) - Maintained by Itering.
- [Python](https://github.com/polkascan/py-scale-codec) - Maintained by Polkascan Foundation.
- [Scales](https://github.com/virto-network/scales) - Serializing SCALE using type information from a type registry.
