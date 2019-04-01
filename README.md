# Oveview of Substrate

This is an up-to-date cheatsheet of news, events, and onboarding materials for Substrate.

[Substrate](https://github.com/paritytech/substrate) is an open-source framework that lets you build entire, configurable blockchains in minimal time. Optionally, you can then deploy your blockchain to the [Polkadot](https://github.com/paritytech/polkadot) network, which has pooled security and other advantages. See a detailed summary [here](https://www.parity.io/a-brief-summary-of-everything-substrate-polkadot/).

With Substrate, you get the following *customizable* functionalities out-of-the-box:
* A default PoS blockchain
* Upgradable runtimes
* Pluggable consensus (PoS, PoW, PoA)
* Block production, synchronization
* Efficient storage
* Efficient state machine
* P2P networking layer
* Built in crypto primitives
* Light client support
* Suite of [libraries](https://crates.parity.io/srml_staking/index.html?search=srml) to modify runtime logic, i.e. manage storage, accounts, staking, a treasury, consensus and more
* UI kits

## Table of Contents
* [Happening this Month](#Happening-this-Month)
    * [Announcements](@Announcements)
    * [Events](#Events)
* [Official Wikis](#Official-Wikis)
* [Official Channels](#Social-Channels)
* [Timeline](#Timeline)
* [Tutorials](#Tutorials)
* [Key Talks](#Key-talks)
* [Articles](#Articles)
* [Projects](#Projects)
* [Research](#Research)
* [Security](#Security)
* [Critiques](#Critiques)
* [Appendix](#Appendix)
    * [Historical](#Historical)
    * [Helpful Diagrams](#Helpful-Diagrams)

## Happening this Month
### Announcements
- [Coming soon] Stable release of Substrate V1. [Follow the Repo](https://github.com/paritytech/substrate)
- [Mar 29]: 10 more validators slots open on Alexander testnet. Ping [Riot](https://riot.im/app/#/room/#watercooler:matrix.parity.io) to start.

### Events
- [Apr 1]: Wrocław blockchain [meetup](https://www.meetup.com/Wroclaw-Blockchain-Meetup/)
- [Apr 3] Seoul [DOT Day](http://bit.ly/dot-day-seoul)
- [Apr 4] Buenos Aires [meetup](https://www.meetup.com/meetup-group-PoZjboSq/events/259876801/)
- [Apr 9]: Tokyo [Dot day](https://cryptoage.connpass.com/event/125207/)
- [Apr 24 - 25]: Sub0 2-day Substrate workshop in Berlin. [Apply to attend here.](https://docs.google.com/forms/d/1k97NJLdBCLjfhlxSvntibBYT15DsLSz42c9exgIzGLE)

Join the [Meetup Group](https://www.meetup.com/parity/events/) and [subscribe to Parity's newsletter](https://www.parity.io/newsletter/) for more events.

## Official Wikis
- [Substrate Documentation](https://crates.parity.io/): Official reference docs for Substrate in Rust
- [Substrate Wiki](https://docs.substrate.dev/docs): Tutorials, samples, and in-depth explanations
- [Polkadot Wiki](https://wiki.polkadot.network/en/latest/): Tutorials, samples, and in-depth explanations

## Social Channels
- [Twitter](https://twitter.com/ParityTech): latest announcements
- [Riot](https://riot.im/app/#/room/#watercooler:matrix.parity.io): live discussion with core devs
- [Blog](https://www.parity.io/tag/parity-substrate/): technical decisions and company culture
- [Stack Overflow](https://stackoverflow.com/questions/tagged/substrate): Q&A support for `#substrate`
- [Reddit](https://www.reddit.com/r/dot/): Polkadot community forum
- [Reddit](https://www.reddit.com/r/substrate/): Substrate community forum


## Timeline
### Substrate
![](https://i.imgur.com/tYt3luX.png)

**As of 8 Feb 2019*

### Polkadot
![](https://i.imgur.com/Ga30C1g.png)

**As of 1 Dec 2018


## Tutorials
- [Custom Runtime](https://docs.substrate.dev/docs/creating-a-custom-substrate-chain): Build a coin-flip game DAppChain with [@gavofyork](https://github.com/gavofyork)
- [Substrate Kitties](https://shawntabrizi.github.io/substrate-collectables-workshop/#/): build a cryptokitty DAppChain on Substrate by [@shawntabrizi](https://github.com/shawntabrizi)
- [TCR](https://docs.substrate.dev/docs/building-a-token-curated-registry-dappchain-using-substrate): Build a token curated registry DAppChain on Substrate by [@Gautamdhameja](https://github.com/gautamdhameja)
- [Video](https://www.youtube.com/watch?v=26ucTSSaqog) : Substrate workshop by @Gavin and @SergeiShulepov at Dotcon-0, November 2018

*Non-DAppChain tutorials coming soon*


## Key talks
### Intro to Parity
Sourced from [@folsen](https://github.com/folsen)
* [ZeroKnowledgeFM 58: Kicking off 2019 with Jutta Steiner](https://www.zeroknowledge.fm/58)
* [ZeroKnowledgeFM 46: Gavin Wood on Polkadot, Sharding and Substrate](https://www.zeroknowledge.fm/46)
* [ZeroKnowledgeFM 12: How to become a blockchain developer? We ask Gavin Wood](https://www.zeroknowledge.fm/12)
* [ZeroKnowledgeFM 5: A fireside chat with a couple Parity peeps](https://www.zeroknowledge.fm/5)

### Intro to Web3
* [Web3 Foundation and Polkadot](https://www.youtube.com/watch?v=IiNcAoiPb8k) by Gavin Wood
* [The Next Evolution of the Internet](https://www.youtube.com/watch?v=ouMK-Q9S7cc) by Gavin Wood
* [History of Web3](https://www.youtube.com/watch?v=JAyw7FWXncE) by Ryan Zurrer at Polkadot Seoul, December 2018
* [Introducing Polkadot](https://www.youtube.com/watch?v=lIghiCmHz0U) by Gavin Wood at London Ethereum Meetup, July 2017

### Substrate and Polkadot
* [Motivating Polkadot](https://www.youtube.com/watch?v=O363z8UQYLE) by Bjorn Wagner, Fred Harrysson, August 2018
* [Polkadot and Parity Substrate](https://www.youtube.com/watch?v=PoHa2p5XzUs) by Bjorn Wagner, Robert Habermeier at Polkadot SF, December 2018
* [A Case for Substrate and Polkadot](https://www.youtube.com/watch?v=jyieXzflPAk) by Fabian Gompf, October 2018

### Key Developers Talks

* [Upcoming Polkadot Developments](https://youtu.be/Opj_5ORbyXA?t=21972) by Gavin Wood at the M1 Conference, February 2019
* [Building DApps with Substrate](https://www.youtube.com/watch?v=Bamo8xjPzVc) by Benjamin Kampmann, February 2019
* [Polkadot for Developers: Status, Roadmap and Tools](https://www.youtube.com/watch?v=XbJ1ESl_Dhw) by Robert Habermeier at Polkadot Seoul, December 2018
* [Implications of Interoperability](https://www.youtube.com/watch?v=TBeGIGvC6r8) by Robert Habermeier at Web3 Summit, October 2018
* [Parity Substrate: the foundation for blockchain innovators](https://www.youtube.com/watch?v=q1zLHO7Lkuk) by Robert Habermeier, May 2018
* [How Polkadot works](https://www.youtube.com/watch?v=WXq8AnGbPkE) by Robert Habermeier, July 2018
* [Light Clients: What is a blockchain node?](https://www.youtube.com/watch?v=0vzrfCruvK8) by Thibaut Sardan, November 2018
* [Light Clients: Why light clients are the future](https://www.youtube.com/watch?v=rowrrffglSI) by Thibaut Sardan, October 2018
* [Light Clients: `Light.js`: building DApps on top of a light client](https://www.youtube.com/watch?v=Hxzzj3lJKlw) by Amaury Martiny, October 2018
* [Parachains vs Smart Contracts](https://www.youtube.com/watch?v=LRAqF-8samI) by Adrian Brink at Polkadot Seoul, December 2018
* [Parachains vs Smart Contracts Panel](https://www.youtube.com/watch?v=xpjJPuQvSu4) with Alistair Stewart, Adrian Brink and Andrew Jones at Polkadot Seoul, December 2018
* [Libp2p: A Modular, P2P Networking Stack](https://www.youtube.com/watch?v=xqVmEzsin3Y) by Mike Goelzer at Web3 Summit, October 2018
* [WebAssembly: WASM for Web 3.0 Panel](https://www.youtube.com/watch?v=H-Wz4lL3LMc) by Alex Beregszaszi, Peter Czaban, Sergei Shulepov &amp; Lane Rettig at Web3 Summit, October 2018
* [WebAssembly: Rust Cologne, WASM in the wild](https://www.youtube.com/watch?v=ULQRGXziF3s) by Benjamin Kampmann at Rust Cologne, November 2018
* [Consensus: ZeroKnowledgeFM 15 - Chatting about Consensus Algorithms with Robert Habermeier](https://www.zeroknowledge.fm/15)
* [Consensus and Finality](https://www.youtube.com/watch?v=o1eKVi5ymSY) by Alistair Stewart at Polkadot Seoul, December 2018
* [Governance: Web3 Summit Governance Panel](https://www.youtube.com/watch?v=eO3fG_1YrE4)
* [Governance: ZeroKnowledgeFM 52: Vlad and Gavin debate blockchain governance](https://www.zeroknowledge.fm/52)
* [Governance: Epicenter #259 Gavin Wood: Substrate, Polkadot and the Case for On-Chain Governance](https://www.youtube.com/watch?v=eP4mT19S_jg)

## Articles
- [What is Substrate](https://www.parity.io/what-is-substrate/)
- [Substrate in a nutshell](https://www.parity.io/substrate-in-a-nutshell/)
- [Never fork again](https://medium.com/polkadot-network/never-fork-again-438c5e985cd8)
- [Substrate has arrived](https://www.parity.io/substrate-has-arrived/)
- [A brief summary of everything Substrate and Polkadot](https://www.parity.io/a-brief-summary-of-everything-substrate-polkadot/)

## Projects
Showcasing projects built on Substrate
- AdEx: Payment channels using Substrate. [Video](https://www.youtube.com/watch?v=1CeI6Oa1BnU). [Repo](https://github.com/AdExNetwork/adex-protocol-substrate).
- AIRA Robonomics: modules for integrating with ROS. [Repo](https://github.com/airalab/substrate-node-robonomics)
- Zerochain privacy-focused runtime module.
    - [Zero-chain Repo](https://github.com/LayerXcom/zero-chain)
    - [Bellman-substrate (zksnarks on substrate) Repo](https://github.com/LayerXcom/bellman-substrate)
- Starlog: IPFS metadata on substrate. [Repo](https://github.com/PACTCare/Starlog)
- Joystream: a user governed video platform. [Repo](https://github.com/osuketh/apple-store-substrate)
- IPFS browser. [Repo](https://github.com/Polygos/substrate-node-ipfsbrowser)
- Edgeware: linking identities [Repo](https://github.com/hicommonwealth/edge-identity)
- Substrate multisig. [Repo](https://github.com/mixbytes/substrate-module-multisig)
- Merkle tree module. [Repo](https://github.com/filiplazovic/substrate-merkle-tree)
- Parking spaces registry using Substrate. [Repo](https://github.com/yjkimjunior/ParkingSpaceSubstrate)
- Chainx: social network on Substrate [Repo](https://github.com/chainx-org/ChainX)
- An "Apple Store": sells apples using Substrate. [Repo](https://github.com/osuketh/apple-store-substrate)

## Research
- [Polkadot Lightpaper](https://polkadot.network/Polkadot-lightpaper.pdf)
## Security
## Critiques
## Appendix
### Historical

### Helpful Diagrams

#### Substrate
SRML is composable
![](https://i.imgur.com/KXkgK45.png)

Substrate parallelises transactions:
![](https://i.imgur.com/8qDB5dU.png)

You can hack at various layers of Substrate:
![](https://i.imgur.com/S7m81Ol.png)

#### Polkadot
Polkadot is composable
![](https://i.imgur.com/aMgVQ0n.png)

Polkadot chains
![](https://i.imgur.com/a8syKgB.png)

Relay chain vs Parachain
![](https://i.imgur.com/nb0GjXO.png)


How PoS staking affects finality:
![](https://i.imgur.com/5duXkQQ.png)

Polkadot pools security:
![](https://i.imgur.com/yxPeBdq.png)

Difference btw Polkadot parachains vs Substrate chains:
![](https://i.imgur.com/Wo7xci9.png)

Relaychain, parachains, bridgechains
![](https://i.imgur.com/fC96E9J.png)

Solo chains, bridge chains, parachains
![](https://i.imgur.com/o3w406Z.png)

Transaction flow:
![](https://i.imgur.com/fLCqnxw.png)

