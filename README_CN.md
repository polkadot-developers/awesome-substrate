# Substrate综述

这里实时更新了Substrate相关的新闻、活动、学习资料。

[Substrate](https://github.com/paritytech/substrate)是一个开源的区块链构建框架，可以在短时间内建立完整、可配置的区块链。另外一个可选功能是，可以将构建的区块链部署到[Polkadot](https://github.com/paritytech/polkadot)网络中，这一网络拥有共享安全等其它优势。更多内容参考[这里](https://www.parity.io/a-brief-summary-of-everything-substrate-polkadot/)。

使用Substrate，你可以获得下面这些开箱即用的功能，还可以自定义这些功能：

* 一条PoS的区块链
* 可升级的运行环境
* 插件式的共识 (PoS, PoW, PoA)
* 区块生产和同步
* 高效存储
* 高效状态机
* P2P网络层
* 内置的基本加密工具
* 支持轻客户端
* [工具集]((https://substrate.dev/rustdocs/v1.0/substrate_service/index.html?search=srml))，用来修改运行环境的逻辑，例如管理存储、账户、权益、资产、共识算法等等
* UI工具

## 内容列表

- [内容列表](#内容列表)
- [本月事件](#本月事件)
  - [公告](#公告)
  - [活动](#活动)
- [官方文档](#官方文档)
- [社交频道](#社交频道)
- [开发指南](#开发指南)
- [重要分享](#重要分享)
  - [Parity介绍](#parity介绍)
  - [Web3 介绍](#web3-介绍)
  - [Substrate和Polkadot](#substrate和polkadot)
  - [核心开发者演讲](#核心开发者演讲)
- [重要文章](#重要文章)
- [项目](#项目)
- [合作](#合作)
- [研究](#研究)
- [时间线](#时间线)
- [安全](#安全)
- [评论](#评论)
- [附录](#附录)
  - [历史资料](#历史资料)
  - [精选图表](#精选图表)

## 本月事件
### 公告
- **正在招聘**: Rust开发工程师，运行环境工程师，发布经理，具体职位信息请看[这里]((https://www.parity.io/jobs/))。
- [4月26]: [Ink](https://github.com/paritytech/ink/)初始版本发布: 基于Substrate的智能合约DSL可以进行试验了。
- [4月9]: Parity Fether: 以太坊桌面钱包[上线]((https://medium.com/paritytech/parity-fether-is-on-ethereum-mainnet-105ed0c7b491))！

### 活动
Substrate相关的分享活动：
- [4月29]: Oslo Blockchain Day
- [5月6-8]: Re:publica in Berlin ft. Jutta Steiner. [链接](https://re-publica.com/en)
- [5月9-10]: The next web in Amsterdam. [链接](https://thenextweb.com/conference/)
- [5月10-11]: Ethereal Summit in NYC. [链接]( https://etherealsummit.com/events/ethereal-ny/)
- [5月13-15]: Coindesk Consensus in NYC. [链接](https://www.coindesk.com/events/consensus-2019)
- [5月13-15]: Webit Festival in Bulgaria. [链接](https://www.webit.org/festival/2019/index.php)
- [5月17-19]: Eth New York, Eth Global Hackathon. [链接](https://twitter.com/ethnewyork)
- [5月23-24]: Malta AI & Blockchain Summit in Malta. [链接](https://maltablockchainsummit.com/)
- [5月31]: Crypto Chicks in Toronto. [链接](https://www.toronto.cryptochicks.ca/)

加入[Meetup 群组](https://www.meetup.com/parity/events/) 获取更多活动。

**推荐：Web3Summit购票[入口](https://web3summit.com/)，时间：8月19-21，地点：柏林。**

## 官方文档

- [Substrate 参考文档](https://substrate.dev/rustdocs/): 官方Substrate参考文档
- [Substrate Wiki](https://substrate.dev/docs/): 指南、实例和深入解释
- [Polkadot Wiki](https://wiki.polkadot.network/en/latest/): 指南、实例和深入解释
- [Research Wiki](https://research.web3.foundation/en/latest/): 早期研究，未来的技术路线
- [UI Wiki](https://polkadot.js.org/api/): Polkadot和Substrate的JS API文档

## 社交频道
- [Twitter](https://twitter.com/ParityTech): 最新的公告
- [Riot](https://riot.im/app/#/room/#watercooler:matrix.parity.io): 与核心开发讨论技术问题
- [Blog](https://www.parity.io/tag/parity-substrate/): 技术决定和公司文化
- [Stack Overflow](https://stackoverflow.com/questions/tagged/substrate): 常见问题和解决方案 `#substrate`
- [Substrate Reddit](https://www.reddit.com/r/substrate/): Substrate社区论坛
- [Polkadot Reddit](https://www.reddit.com/r/dot/): Polkadot社区论坛
- [PolkaWorld](https://polkaworld.org/): Polkadot中国社区

## 开发指南
- [构建自定义的Substrate运行环境](https://substrate.dev/docs/en/tutorials/creating-your-first-substrate-chain): 作者[@gavofyork](https://github.com/gavofyork)，抛硬币游戏DAppChain。
- [构建加密猫区块链](https://substrate.dev/substrate-collectables-workshop/#/): 作者[@shawntabrizi](https://github.com/shawntabrizi)，基于Substrate的加密猫DAppChain 
- [构建TCR链](https://substrate.dev/docs/en/tutorials/tcr/): 作者[@Gautamdhameja](https://github.com/gautamdhameja)，基于Substrate的通证背书清单
- [构建UTXO链](https://github.com/substrate-developer-hub/utxo-workshop): 作者[@Dmitriy K](https://github.com/0x7CFE) 基于Substrate的UTXO链
- **[新!]**** [使用Ink开发智能合约](https://substrate.dev/substrate-contracts-workshop/#/): 一个用Substrate编写智能合约的DSL。

## 重要分享
### Parity介绍
来源于[@folsen](https://github.com/folsen)和[@amarRSingh](https://github.com/AmarRSingh)
- [ZeroKnowledgeFM 58: Kicking off 2019 with Jutta Steiner](https://www.zeroknowledge.fm/58)
- [ZeroKnowledgeFM 46: Gavin Wood on Polkadot, Sharding and Substrate](https://www.zeroknowledge.fm/46)
- [ZeroKnowledgeFM 12: How to become a blockchain developer? We ask Gavin Wood](https://www.zeroknowledge.fm/12)
- [ZeroKnowledgeFM 5: A fireside chat with a couple Parity peeps](https://www.zeroknowledge.fm/5)

### Web3 介绍
- [Web3 Foundation and Polkadot](https://www.youtube.com/watch?v=IiNcAoiPb8k) by Gavin Wood
- [The Next Evolution of the Internet](https://www.youtube.com/watch?v=ouMK-Q9S7cc) by Gavin Wood
- [History of Web3](https://www.youtube.com/watch?v=JAyw7FWXncE) by Ryan Zurrer at Polkadot Seoul, December 2018
- [Introducing Polkadot](https://www.youtube.com/watch?v=lIghiCmHz0U) by Gavin Wood at London Ethereum Meetup, July 2017

### Substrate和Polkadot
- [Motivating Polkadot](https://www.youtube.com/watch?v=O363z8UQYLE) by Bjorn Wagner, Fred Harrysson, August 2018
- [Polkadot and Parity Substrate](https://www.youtube.com/watch?v=PoHa2p5XzUs) by Bjorn Wagner, Robert Habermeier at Polkadot SF, December 2018
- [A Case for Substrate and Polkadot](https://www.youtube.com/watch?v=jyieXzflPAk) by Fabian Gompf, October 2018

### 核心开发者演讲

- [Upcoming Polkadot Developments](https://youtu.be/Opj_5ORbyXA?t=21972) by Gavin Wood at the M1 Conference, February 2019
- [Building DApps with Substrate](https://www.youtube.com/watch?v=Bamo8xjPzVc) by Benjamin Kampmann, February 2019
- [Polkadot for Developers: Status, Roadmap and Tools](https://www.youtube.com/watch?v=XbJ1ESl_Dhw) by Robert Habermeier at Polkadot Seoul, December 2018
- [Implications of Interoperability](https://www.youtube.com/watch?v=TBeGIGvC6r8) by Robert Habermeier at Web3 Summit, October 2018
- [Parity Substrate: the foundation for blockchain innovators](https://www.youtube.com/watch?v=q1zLHO7Lkuk) by Robert Habermeier, May 2018
- [How Polkadot works](https://www.youtube.com/watch?v=WXq8AnGbPkE) by Robert Habermeier, July 2018
- [Light Clients: What is a blockchain node?](https://www.youtube.com/watch?v=0vzrfCruvK8) by Thibaut Sardan, November 2018
- [Light Clients: Why light clients are the future](https://www.youtube.com/watch?v=rowrrffglSI) by Thibaut Sardan, October 2018
- [Light Clients: `Light.js`: building DApps on top of a light client](https://www.youtube.com/watch?v=Hxzzj3lJKlw) by Amaury Martiny, October 2018
- [Parachains vs Smart Contracts](https://www.youtube.com/watch?v=LRAqF-8samI) by Adrian Brink at Polkadot Seoul, December 2018
- [Parachains vs Smart Contracts Panel](https://www.youtube.com/watch?v=xpjJPuQvSu4) with Alistair Stewart, Adrian Brink and Andrew Jones at Polkadot Seoul, December 2018
- [Libp2p: A Modular, P2P Networking Stack](https://www.youtube.com/watch?v=xqVmEzsin3Y) by Mike Goelzer at Web3 Summit, October 2018
- [WebAssembly: WASM for Web 3.0 Panel](https://www.youtube.com/watch?v=H-Wz4lL3LMc) by Alex Beregszaszi, Peter Czaban, Sergei Shulepov &amp; Lane Rettig at Web3 Summit, October 2018
- [WebAssembly: Rust Cologne, WASM in the wild](https://www.youtube.com/watch?v=ULQRGXziF3s) by Benjamin Kampmann at Rust Cologne, November 2018
- [Consensus: ZeroKnowledgeFM 15 - Chatting about Consensus Algorithms with Robert Habermeier](https://www.zeroknowledge.fm/15)
- [Consensus and Finality](https://www.youtube.com/watch?v=o1eKVi5ymSY) by Alistair Stewart at Polkadot Seoul, December 2018
- [Governance: Web3 Summit Governance Panel](https://www.youtube.com/watch?v=eO3fG_1YrE4)
- [Governance: ZeroKnowledgeFM 52: Vlad and Gavin debate blockchain governance](https://www.zeroknowledge.fm/52)
- [Governance: Epicenter #259 Gavin Wood: Substrate, Polkadot and the Case for On-Chain Governance](https://www.youtube.com/watch?v=eP4mT19S_jg)

## 重要文章
- [What is Substrate](https://www.parity.io/what-is-substrate/)
- [Substrate in a nutshell](https://www.parity.io/substrate-in-a-nutshell/)
- [Never fork again](https://medium.com/polkadot-network/never-fork-again-438c5e985cd8)
- [Substrate has arrived](https://www.parity.io/substrate-has-arrived/)
- [A brief summary of everything Substrate and Polkadot](https://www.parity.io/a-brief-summary-of-everything-substrate-polkadot/)
- [Everything you Need to Know to Prepare for Polkadot](https://medium.com/polkadot-network/everything-you-need-to-know-to-prepare-for-polkadot-32d08b929735?sk=d81a3cebd61fb9b8aaf29a564fe0d303)

## 中文资料

- [Substrate 基础介绍](https://www.slideshare.net/casperLTH/substrate-134676336/1)
- [Polkadot 简介](https://www.slideshare.net/casperLTH/polkadot/1)
- [Substrate高阶概览和在ChainX系统中的应用（视频分享）](https://mp.weixin.qq.com/s/AjQ10yk-VsmS-HdREgjBTQ)
- [Substrate 设计总览](https://zhuanlan.zhihu.com/p/56383616)

## 项目

使用Substrate构建的项目展示：
- IPFS浏览器. [代码](https://github.com/Polygos/substrate-node-ipfsbrowser)
- Substrate多重签名. [代码](https://github.com/mixbytes/substrate-module-multisig)
- Merkle tree模块. [代码](https://github.com/filiplazovic/substrate-merkle-tree)
- 使用Substrate实现停车场车位登记. [代码](https://github.com/yjkimjunior/ParkingSpaceSubstrate)
- 使用Substrate构建出售苹果的线上商店. [代码](https://github.com/osuketh/apple-store-substrate)
- ChainLink - 正在开发预言机 ([公告](https://medium.com/web3foundation/web3-foundation-and-chainlink-announce-collaboration-df55ed462a3a))
- DataHighway - 分散式物聯網漫遊，挖掘（鎖定，信令），鏈間數據市場, DAO ([网站](https://www.datahighway.com), [文件和技術報告](https://dev.datahighway.com), [Github 代码](https://github.com/DataHighway-DHX))
- 0x protocol - 去中心化的交易所 ([Tweet](https://twitter.com/recmo/status/1081637877027549190?s=09))
- Aragon - 永不离线的组织，DAOs ([演讲](https://twitter.com/rzurrer/status/1090201496753504259))
- AdEx - 正在实现他们的TCR ([公告](https://medium.com/web3foundation/adex-announces-substrate-implementation-3fdeed8bf494))
- ChainX - 正在开发比特币和以太坊的桥接网络 ([公告](https://medium.com/web3foundation/web3-foundation-and-chainx-announce-collaboration-6c70564d7272))
- Ocean Protocol - 建立数据共享的生态系统 ([演讲](https://blog.oceanprotocol.com/decentralized-web-summit-2018-highlights-a6376edefb01))
- Energy Web Foundation - 正在构建一个能源网络 ([公告](https://www.parity.io/private-transactions-webassembly-and-permissioning-new-features-energy-web-foundation-blockchain-for-energy/))
- iExec - 去中心化的云计算 ([公告](https://medium.com/iex-ec/dev-letter-24-sidechain-approach-7cab5de2e54a))
- Edgeware - 正在构建基于WASM的智能合约平台 ([网站](https://edgewa.re/))
- ZeroChain - 基于Substrate开发的zK-SNARKs链 ([公告](https://medium.com/layerx/announcing-zerochain-5b08e158355d))
- Robonomics - 信息实体系统集成 ([Twitter](https://twitter.com/AIRA_Robonomics/status/1079001376452210689))
- MXC - IoT 协议 ([网站](https://www.mxc.org))
- Katal Chain - 金融合约 ([网站](https://katalchain.com/))
- Joystream - 用户治理的视频平台 ([公告](https://blog.joystream.org/sparta/))
- Asure Network - 社交安全网络 ([网站](https://www.asure.network/))
- Kilt Protocol - 身份信任市场 ([网站](https://kiltprotocol.com/))
- PACTCare - 基于Substrate开发的元数据区块链Starlog ([GitHub](https://github.com/PACTCare/Starlog))
- Blink Network - 快速支付 ([网站](https://blink.network/))
- Akropolis - 全球养老基础设施 ([公告](https://medium.com/akropolis/hello-world-ae16b654ba71))
- LayerX - zk-SNARKs 链 ([announcement](https://medium.com/layerx/announcing-zerochain-5b08e158355d))
- Plasm - Plasm 是Substrate的一个运行时模块，可以方便开发者添加Plasma功能到自己的Substrate链中 ([代码](https://github.com/stakedtechnologies/Plasm))
- Speckle OS - 通用的身份和账户管理平行链 ([公告](https://medium.com/polkadot-network/dots-and-speckle-paving-the-way-forward-for-the-new-web-691beed50f1a))
- Evolution Land - 基于区块链的虚拟经营游戏 ([Github](https://github.com/evolutionlandorg/darwinia-appchain))
- Substrate Dex - 一个基于substrate的Dex ([Github](https://github.com/alexxuyang/substrate-dex))

[来源](https://forum.web3.foundation/t/teams-building-on-polkadot/67)

## 合作
- 与Longhash合作建立Polkadot孵化器 [链接](https://longhash.com.sg/program)

## 研究
- [Polkadot Lightpaper](https://polkadot.network/Polkadot-lightpaper.pdf)

## 时间线
### Substrate
![](https://i.imgur.com/tYt3luX.png)

**As of 8 Feb 2019*

### Polkadot
![](https://i.imgur.com/Ga30C1g.png)

**As of 1 Dec 2018
## 安全
## 评论
## 附录
### 历史资料

### 精选图表

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

