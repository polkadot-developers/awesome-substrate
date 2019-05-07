# Overview of Substrate

This is an up-to-date cheatsheet of news, events, and onboarding materials for Substrate.

[Substrate](https://github.com/paritytech/substrate) is an open-source framework that lets you build entire, configurable blockchains in minimal time. Optionally, you can then deploy your blockchain to the [Polkadot](https://github.com/paritytech/polkadot) network, which has pooled security and other advantages. See a detailed summary [here](https://www.parity.io/a-brief-summary-of-everything-substrate-polkadot/).

*With Substrate, you get the following customizable functionalities out-of-the-box: A default PoS blockchain, upgradable runtimes, pluggable consensus (PoS, PoW, PoA), block production, synchronization, P2P networking layer, built in crypto primitives, light client support, and an entire suite of ready-to-use [libraries](https://crates.parity.io/srml_staking/index.html?search=srml), i.e. to manage storage, accounts, staking, a treasury, consensus and more.*

## Table of Contents
* [Happening this Month](#Happening-this-Month)
    * [Announcements](#Announcements)
    * [Events](#Events)
* [Official Wikis](#Official-Wikis)
* [Official Channels](#Social-Channels)
* [Tutorials](#Tutorials)
* [Key Talks](#Key-talks)
* [Key Articles](#Key-Articles)
* [Projects](#Projects)
* [Partnerships](#Partnerships)
* [Research](#Research)
* [Timeline](#Timeline)
* [Security](#Security)
* [Critiques](#Critiques)
* [Appendix](#Appendix)
    * [Historical](#Historical)
    * [Helpful Diagrams](#Helpful-Diagrams)

## Happening this Month
### Announcements
- Now hiring: Rust developers, runtime engineers, and release managers [here!](https://www.parity.io/jobs/)
- [26 Apr]: Initial version of [Ink](https://github.com/paritytech/ink/): Substrate's smart contract DSL is ready for experimentation.
- [9 Apr]: Parity Fether: Ethereum desktop wallet [is live](https://medium.com/paritytech/parity-fether-is-on-ethereum-mainnet-105ed0c7b491)!

### Events
Substrate talks near you:
- [Apr 29]: Oslo Blockchain Day
- [May 6-8]: Re:publica in Berlin ft. Jutta Steiner. [Link](https://re-publica.com/en)
- [May 9 -10]: The next web in Amsterdam. [Link](https://thenextweb.com/conference/)
- [May 10-11]: Ethereal Summit in NYC. [Link]( https://etherealsummit.com/events/ethereal-ny/)
- [May 13-15]: Coindesk Consensus in NYC. [Link](https://www.coindesk.com/events/consensus-2019)
- [May 13-15]: Webit Festival in Bulgaria. [Link](https://www.webit.org/festival/2019/index.php)
- [May 17-19]: Eth New York, Eth Global Hackathon. [Link](https://twitter.com/ethnewyork)
- [May 23-24]: Malta AI & Blockchain Summit in Malta. [Link](https://maltablockchainsummit.com/)
- [May 31]: Crypto Chicks in Toronto. [Link](https://www.toronto.cryptochicks.ca/)
Join the [Meetup Group](https://www.meetup.com/parity/events/) for more events.

**Featured: Web3Summit tickets [are here](https://web3summit.com/). Coming Aug 19-21 '19.**

## Official Wikis
- [Substrate Documentation](https://crates.parity.io/): Official reference docs for Substrate in Rust
- [Substrate Wiki](https://docs.substrate.dev/docs): Tutorials, samples, and in-depth explanations
- [Polkadot Wiki](https://wiki.polkadot.network/en/latest/): Tutorials, samples, and in-depth explanations
- [Research Wiki](https://research.web3.foundation/en/latest/): Early research, what's coming down the road
- [UI Wiki](https://polkadot.js.org/api/): JS API for Polkadot and Substrate

## Social Channels
- [Twitter](https://twitter.com/ParityTech): latest announcements
- [Riot](https://riot.im/app/#/room/#watercooler:matrix.parity.io): discussion with core devs
- [Blog](https://www.parity.io/tag/parity-substrate/): technical decisions and company culture
- [Stack Overflow](https://stackoverflow.com/questions/tagged/substrate): Q&A support for `#substrate`
- [Substrate Reddit](https://www.reddit.com/r/substrate/): Substrate community forum
- [Polkadot Reddit](https://www.reddit.com/r/dot/): Polkadot community forum

## Tutorials
- [Build a Custom Substrate Runtime](https://docs.substrate.dev/docs/creating-a-custom-substrate-chain): A coin-flip game DAppChain with [@gavofyork](https://github.com/gavofyork)
- [Build Substrate Kitties](https://shawntabrizi.github.io/substrate-collectables-workshop/#/): A cryptokitty DAppChain on Substrate by [@shawntabrizi](https://github.com/shawntabrizi)
- [Build a TCR Chain](https://docs.substrate.dev/docs/building-a-token-curated-registry-dappchain-using-substrate): A token curated registry DAppChain on Substrate by [@Gautamdhameja](https://github.com/gautamdhameja)
- [Build a UTXO Chain](https://github.com/nczhu/utxo-workshop): A utxo chain on Substrate by [@Dmitriy K.](https://github.com/0x7CFE)
- **[New!]**** [Write Smart Contracts in Ink](http://tiny.cc/ink-workshop): A new, domain specific language around writing smart contracts in Substrate.

## Key talks
### Intro to Parity
Sourced from [@folsen](https://github.com/folsen) and [@amarRSingh](https://github.com/AmarRSingh)
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
* [Staking on Polkadot](https://www.youtube.com/watch?v=4Wz6FHqaTLk&feature=youtu.be&t=1) by Gav Wood in Hong Kong Apr 2019
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

## Key Articles
- [What is Substrate](https://www.parity.io/what-is-substrate/)
- [Substrate in a nutshell](https://www.parity.io/substrate-in-a-nutshell/)
- [Never fork again](https://medium.com/polkadot-network/never-fork-again-438c5e985cd8)
- [Substrate has arrived](https://www.parity.io/substrate-has-arrived/)
- [A brief summary of everything Substrate and Polkadot](https://www.parity.io/a-brief-summary-of-everything-substrate-polkadot/)
- [Everything you Need to Know to Prepare for Polkadot](https://medium.com/polkadot-network/everything-you-need-to-know-to-prepare-for-polkadot-32d08b929735?sk=d81a3cebd61fb9b8aaf29a564fe0d303)

## Projects
Showcasing projects built on Substrate
- UTXO: UTXO chain built on substrate by @0x7CFE [Repo](https://github.com/0x7CFE/substrate-node-template/tree/utxo)
- AdEx: Payment channels using Substrate. [Video](https://www.youtube.com/watch?v=1CeI6Oa1BnU). [Repo](https://github.com/AdExNetwork/adex-protocol-substrate).
- AIRA Robonomics: modules for integrating with ROS. [Repo](https://github.com/airalab/substrate-node-robonomics)
- Zerochain privacy-focused runtime module.
    - [Zero-chain Repo](https://github.com/LayerXcom/zero-chain)
    - [Bellman-substrate (zksnarks on substrate) Repo](https://github.com/LayerXcom/bellman-substrate)
- Starlog: IPFS metadata on substrate. [Repo](https://github.com/PACTCare/Starlog)
- Joystream: a user governed video platform. [Repo]( https://github.com/Joystream/substrate-runtime-joystream)
- Edgeware: linking identities [Repo](https://github.com/hicommonwealth/edge-identity)
- Substrate multisig. [Repo](https://github.com/mixbytes/substrate-module-multisig)
- Merkle tree module. [Repo](https://github.com/filiplazovic/substrate-merkle-tree)
- Parking spaces registry using Substrate. [Repo](https://github.com/yjkimjunior/ParkingSpaceSubstrate)
- ChainX: cross-chain asset management platform on Substrate [Repo](https://github.com/chainx-org/ChainX)
- An "Apple Store": sells apples using Substrate. [Repo](https://github.com/osuketh/apple-store-substrate)

## Partnerships
- Partnering with Longhash on a Polkadot incubator [program](https://longhash.com.sg/program)

## Research
- [Polkadot Lightpaper](https://polkadot.network/Polkadot-lightpaper.pdf)

## Timeline
### Substrate
![](https://i.imgur.com/tYt3luX.png)

**As of 8 Feb 2019*

### Polkadot
![](https://i.imgur.com/Ga30C1g.png)

**As of 1 Dec 2018
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

