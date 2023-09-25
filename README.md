# Awesome Cairo <a href="https://github.com/sindresorhus/awesome"> <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"> </a> ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green.svg) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/auditless/awesome-cairo/blob/main/LICENSE)

A curated list of Cairo 1.0 code and resources.

"A Cairo Wikipedia" ~StarknetAfrica

## Contents

- [Awesome Cairo     ](#awesome-cairo-----)
  - [Contents](#contents)
  - [Libraries](#libraries)
  - [Misc](#misc)
  - [Projects](#projects)
  - [References](#references)
  - [Templates](#templates)
  - [Tools](#tools)
  - [Tutorials](#tutorials)
  - [Other Lists](#other-lists)
    - [Starknet](#starknet)
    - [Cairo 0.x](#cairo-0x)
  - [License](#license)

Other Starknet/Cairo related lists: [Other lists](#other-lists)

## Libraries

- [`cairo-contracts`](https://github.com/OpenZeppelin/cairo-contracts/tree/cairo-1) – OpenZeppelin's cairo1 development branch
- [`cairo_ml`](https://github.com/raphaelDkhn/cairo_ml) – Build neural network models in Cairo 1.0 to perform inference
- [`corelib`](https://github.com/starkware-libs/cairo/tree/main/corelib/src) - Built in Cairo 1.0 standard library
- [`alexandria`](https://github.com/keep-starknet-strange/alexandria) – Community maintained standard library for Cairo 1.0
- [`orion`](https://github.com/gizatechxyz/orion) - library for verifiable ML inference in Cairo 1.0
- [`neural-network-cairo`](https://github.com/franalgaba/neural-network-cairo) – Neural Network for MNIST in Cairo 1.0
- [`cubit`](https://github.com/influenceth/cubit) – A fixed point math library in 64.64 representation built for Cairo 1.0
- [`erc20.cairo`](https://github.com/starkware-libs/cairo/blob/main/crates/cairo-lang-starknet/test_data/erc20.cairo) – StarkWare's test ERC20 implementation
- [`erc721.cairo`](https://github.com/reddio-com/cairo/blob/main/token/ERC721/erc721.cairo) – An early ERC721 implementation
- [`suna`](https://github.com/auditless/suna) – Typesafe primitives for Cairo 1.0 with a focus on DeFi protocols
- [`arcade-accounts`](https://github.com/BibliothecaDAO/arcade-account) - Starknet Accounts with fine grain permissions for use in onchain games
- [`cairo1-bytes`](https://github.com/zkLinkProtocol/cairo1-bytes) - Solidity likely bytes by [zkLink](https://zk.link/) in Cairo 1.0. 

**[back to top](#contents)**

## Misc

- [Cairo 1.0 dashboard](https://starkscan.co/cairo-one) – Starkscan Cairo 1.0 dashboard

## Projects

- [`dojo`](https://github.com/dojoengine/dojo) – A full stack toolchain for developing onchain games in Cairo
- [`kakarot-ssj`](https://github.com/sayajin-labs/kakarot-ssj) – Kakarot ZK-EVM in Cairo 1.0
- [`starknet-commit-reveal`](https://github.com/gaetbout/starknet-commit-reveal) – Commit-reveal implementation
- [`Cairo1.0 by Examples`](https://github.com/CeliktepeMurat/Cairo1.0_by_Examples/tree/main) – Cairo 1.0 examples
- [`kass`](https://github.com/ruleslabs/kass) – L1 <-> L2 Starknet ERC1155 Bridge
- [`RockPaperScissors-Cairo`](https://github.com/Kalzak/RockPaperScissors-Cairo/tree/main) – Commit-reveal based Rock-Paper-Scissors
- [`InstaSwap`](https://github.com/BibliothecaDAO/InstaSwap) – Decentralized token swap protocol for ERC-1155 tokens on Starknet.
- [`rollyourown`](https://github.com/cartridge-gg/rollyourown) – On-chain adaptation of the original Drug Wars game
- [`shoshin-cairo1`](https://github.com/topology-gg/shoshin-cairo-1) – On-chain fighting game in Cairo 1
- [`bto-cairo-1`](https://github.com/topology-gg/bto-cairo-1) – Binary Tree Operations in Cairo 1
- [`2wrds_cntrcts`](https://github.com/greged93/2wrds_cntrcts) – 2wrds project
- [`Realms: Eternum`](https://github.com/BibliothecaDAO/eternum) – Realms Autonomous World built with [`dojo`](https://github.com/dojoengine/dojo) 
- [`Loot Survivor`](https://github.com/BibliothecaDAO/loot-survivor) - Roguelike single felt onchain game

**[back to top](#contents)**

## References

- [`starkware-libs/cairo/docs`](https://github.com/starkware-libs/cairo/tree/main/docs/reference) – Official Cairo 1.0 reference

**[back to top](#contents)**

## Templates

- [`auditless/cairo-template`](https://github.com/auditless/cairo-template) – A minimal template for building smart contracts with Cairo 1.0
- [`msaug/cairo1-template`](https://github.com/msaug/cairo1-template) – A template to get you started with Cairo 1
- [ArgentX Cairo template](https://github.com/argentlabs/starknet-build/tree/main/cairo1.0) – ArgentX Cairo template
- [`cairo1-mocha`](https://github.com/enitrat/cairo1-mocha) – This project aims to provide a simple way of testing your contracts using Mocha and StarknetJS

**[back to top](#contents)**

## Tools

- [`scarb`](https://docs.swmansion.com/scarb) – The project management tool for the Cairo language
- [`protostar`](https://docs.swmansion.com/protostar) – The Starknet smart contract development toolchain

**[back to top](#contents)**

## Tutorials

- [The Cairo Book](https://github.com/cairo-book/cairo-book.github.io) – The Cairo Programming Language Book
- [Getting Started with Cairo 1.0](https://www.argent.xyz/blog/getting-started-with-cairo-1.0/) – Learn everything you need to know about the new and improved Cairo
- [A First Look at Cairo 1.0](https://medium.com/nethermind-eth/a-first-look-at-cairo-1-0-a-safer-stronger-simpler-provable-programming-language-892ce4c07b38) – This blog post will take you through the new features added to Cairo and discuss how they will improve the language
- [`starklings-cairo1`](https://github.com/shramee/starklings-cairo1) – An interactive tutorial to get you up and running with Cairo and Starknet
- [`starklings-cairo1` solutions](https://github.com/Akashneelesh/starklings-cairo1) – Solutions to starklings exercises
- [Reading Sierra: Starknet's secret sauce for Cairo 1.0](https://medium.com/yagi-fi/reading-sierra-starknets-secret-sauce-for-cairo-1-0-5bc73409e43c) – A tutorial for reading Sierra
- [`HERDAO-cairo`](https://github.com/omarespejel/HERDAO-Cairo) - First smart contracts with Cairo and HER DAO
- [How to write ERC721 contracts with Cairo 1.0](https://blog.reddio.com/how-to-write-erc721-contracts-with-cairo-1/) – Guide to writing an ERC721 contract
- [Under the hood of Cairo 1.0: Exploring Sierra](https://medium.com/nethermind-eth/under-the-hood-of-cairo-1-0-exploring-sierra-7f32808421f5) – A deep-dive into the purpose of Sierra
- [`0to1CairoDemo`](https://github.com/NethermindEth/0to1CairoDemo) – Steps to upgrade from cairo 0 upgradeable contract to cairo 1 upgradeable contract
- [`deploy-cairo1-demo`](https://github.com/starknet-edu/deploy-cairo1-demo) – Official StarkWare tutorial for deploying a Cairo 1 contract
- [`starknet-accounts-cairo1`](https://github.com/FelixGibson/starknet-accounts-cairo1) – Starknet account abstraction workshop
- [`cairopractice`](https://cairopractice.com/) - Cairo 1.0 and Starknet blog
- [`Cairo1.0`](https://github.com/Starknet-Africa-Edu/Cairo1.0) – Mini Cairo 1.0 tutorial by Starknet Africa

**[back to top](#contents)**

## Other Lists

### Starknet

- [`awesome-starknet`](https://github.com/gakonst/awesome-starknet) A curated list of awesome Starknet resources, libraries, tools and more

### Cairo 0.x

- [`cairo-resources-list`](https://github.com/NewtonDAO/cairo-resources-list) A curated list of awesome Cairo resources, libraries, tools and more
- [`cairo-goldmine`](https://github.com/beautyisourbusiness/cairo-goldmine) A comprehensive, annotated list of repositories of the Starknet ecosystem
- [`newton`](https://www.newton.so) A series of Q&As and FAQs about StarkNet developer tools and Cairo 0.x

**[back to top](#contents)**

## License

[MIT](https://github.com/auditless/cairo-template/blob/main/LICENSE) © [Auditless Limited](https://www.auditless.com)
