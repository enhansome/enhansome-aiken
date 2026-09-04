<p align="center">
    <img src=".github/awesome-aiken.png" alt="Awesome Aiken" width="480"/>
    <br/>
    <strong>An collection of (curated) awesome <a href="https://aiken-lang.org" alt="aiken-lang.org"/>Aiken</a> libraries, DApps, tutorials & other cool stuff.</strong>
</p>

***

> \[!TIP]
>
> Anything to contribute? [Make a pull request](https://github.com/aiken-lang/awesome-aiken/pulls) ⭐ 82 | 🐛 2 | 📅 2025-10-01 that adds your project to this list :heart:!

***

# Awesome Aiken with stars

* [Libraries](#Libraries)
* [Dapps](#Dapps)
* [Tutorials/Examples](#tutorialsexamples)
* [Videos](#Videos)

## Libraries

#### Infrastructure

* [aiken-lang/setup-aiken](https://github.com/aiken-lang/setup-aiken) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-23 - A GitHub action for installing and using Aiken in Github Workflows

#### Standard library & extras

* [aiken-lang/stdlib](https://github.com/aiken-lang/stdlib) ⭐ 58 | 🐛 6 | 🌐 Aiken | 📅 2026-06-10 - The official standard library
* [LogicalMechanism/assist](https://github.com/logicalmechanism/assist) ⭐ 18 | 🐛 0 | 🌐 Aiken | 📅 2026-01-24 - A collection of specialized Aiken functions.
* [Cardano-Fans/acca](https://github.com/Cardano-Fans/acca) ⭐ 11 | 🐛 3 | 🌐 Gleam | 📅 2026-02-11 - Extensions to the standard library
* [SundaeSwap-finance/aicone](https://github.com/SundaeSwap-finance/aicone) ⭐ 10 | 🐛 2 | 🌐 Aiken | 📅 2026-08-14 - Several reusable Aiken libraries
* [aiken-extra/\*](https://github.com/aiken-extra) - A collection of additional aiken functions to build tests and help debug.

#### Cryptography

* [ilap/bls](https://github.com/ilap/bls) ⭐ 4 | 🐛 0 | 🌐 Gleam | 📅 2026-03-21 - High-level BLS12-381 cryptographic functions

#### Data-structures

* [aiken-lang/merkle-patricia-forestry](https://github.com/aiken-lang/merkle-patricia-forestry) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-25 - For working with modified Merkle Patricia Tries (on-chain & off-chain): a persistent & authenticated data structure to map between arbitrary keys and values.
* [anastasia-labs/aiken-linked-list](https://github.com/Anastasia-Labs/aiken-linked-list) ⭐ 4 | 🐛 2 | 🌐 Makefile | 📅 2024-05-14 - For working with onchain distributed linked lists (on-chain): each node in the linked list is represented by a single UTxO (and thus concurrency scales with utilization, the larger the linked list, the lower the probability of experiencing UTxO contention).
* [anastasia-labs/aiken-trie](https://github.com/Anastasia-Labs/aiken-trie) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2024-04-09 - For working with distributed tries (on-chain & off-chain): each trie is fully-contained within a UTxO, and it supports managing multiple distributed tries with a single validator.

#### Testing

* [sidan-lab/vodka](https://github.com/sidan-lab/vodka) ⭐ 30 | 🐛 5 | 🌐 Gleam | 📅 2026-02-20 - Offer validation utils and similar to offchain code building experience framework for unit testing.
* [aiken-lang/fuzz](https://github.com/aiken-lang/fuzz) ⭐ 11 | 🐛 4 | 🌐 Aiken | 📅 2025-07-13 - For writing Fuzzers (a.k.a generators) for property-based testing in Aiken

## Dapps

#### DeFi

* [Sundae Swap V3](https://github.com/SundaeSwap-finance/sundae-contracts) ⭐ 23 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-01 - DEX
* [Minswap V2](https://github.com/minswap/minswap-dex-v2) ⭐ 14 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-23 - DEX
* [Minswap - Stableswap](https://github.com/minswap/minswap-stableswap) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2024-06-07 - DEX
* [Lenfi](https://github.com/lenfiLabs/lenfi-smart-contracts) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-01-21 - Lending and Borrowing
* [SundaeSwap Yield Farming v2](https://github.com/SundaeSwap-finance/sundae-yield-v2) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2025-03-10 - SundaeSwap Yield Farming v2 contracts
* [Levvy](https://levvy.fi/) - NFT based lending and borrowing
* [Danogo](https://danogo.io/) - Decentralized Bond Exchange
* [Mehen](https://mehen.io) - Fiat-backed stable coin

#### Marketplaces

* [Nebula](https://github.com/spacebudz/nebula/tree/main/contract/src/nebula) ⭐ 84 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-17 - A Cardano NFT marketplace contract including chain indexer and event listener for individual projects
* [Jpg Store](https://github.com/jpg-store/contracts-v3) ⭐ 17 | 🐛 2 | 🌐 TypeScript | 📅 2024-07-02 - NFT Marketplace

#### Smart Wallets

* [Seedelf](https://github.com/logical-mechanism/Seedelf-Wallet) ⭐ 14 | 🐛 1 | 🌐 Rust | 📅 2026-05-21 A Cardano Stealth Wallet

#### Governance

* [unLearn](https://github.com/Astodialo/unLearn) ⭐ 9 | 🐛 1 | 🌐 TypeScript | 📅 2024-12-22 - Modular governance framework

#### Games

* [Tetrano](https://tetrano.net) - Tetris style puzzle game on Cardano

#### Misc

* [Fortuna](https://github.com/cardano-miners/fortuna) ⭐ 53 | 🐛 2 | 🌐 TypeScript | 📅 2024-11-11 - A Smart Contract that mimics bitcoin proof of work
* [morbid](https://github.com/ariady-putra/morbid) ⚠️ Archived - A dead-man's switch contract
* [Projected NFT Whirlpool](https://github.com/dcSpark/projected-nft-whirlpool) ⭐ 10 | 🐛 6 | 🌐 TypeScript | 📅 2024-09-12 - A new protocol for the Paima Whirlpool vision to allow users from other ecosystems to naturally be able to use existing NFTs in games from other ecosystems while still maintaining custody
* [ENCOINS](https://github.com/encryptedcoins/encoins-core-aiken) ⭐ 2 | 🐛 0 | 📅 2023-09-06 - An NFT-based private transactions protocol

## Tutorials/Examples

* [MeshJS smart contracts collection](https://github.com/MeshJS/mesh/tree/main/packages/mesh-contract/src) ⭐ 271 | 🐛 82 | 🌐 TypeScript | 📅 2026-08-11 - A series of smart contracts  with full integration with MeshJS, offering code examples and explanations
* [Common Design Pattens](https://github.com/Anastasia-Labs/aiken-design-patterns) ⭐ 54 | 🐛 1 | 🌐 Aiken | 📅 2026-09-04 - A collection of tried and tested modules and functions for implementing common design patterns.
* [Cardano Capture The Flag](https://github.com/vacuumlabs/cardano-ctf) ⭐ 35 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-28 - A game where Cardano developers and enthusiasts can try to exploit purposely vulnerable smart contracts and learn about the most common security issues and how to prevent them.
* [Gift Card NextJS](https://github.com/adalicious/aiken-gift-card) ⭐ 8 | 🐛 3 | 🌐 TypeScript | 📅 2023-04-27 - A similar gift card example but with NextJS
* [Good Practices](https://github.com/francolq/aiken-good-practices) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-13
* [Logical Mechanism's Convert Expression](https://github.com/logicalmechanism/convert-expression) ⭐ 3 | 🐛 0 | 🌐 Mathematica | 📅 2023-10-12 - A novel variation of a Schnorr protocol
* [Cardano Recorded Mint](https://github.com/keyan-m/cardano-recorded-mint) ⭐ 3 | 🐛 1 | 📅 2026-01-06 - A proof-of-concept for a minting script with historical record of all mints, and on-chain guarantee of uniqueness.
* [Logical Mechanism's Distributed Representation](https://github.com/logicalmechanism/distributed_representation) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-07-11 - A model semi-liquid `mint-lock-stake` DAO
* [From Aiken to frontend deployment](https://meshjs.dev/guides/aiken) - A end-to-end guide from writing a Aiken smart contract, to creating transactions, to deploying a frontend to interact with it. See also [demo](https://aiken-next-ts-template.vercel.app/) and [repo](https://github.com/MeshJS/aiken-next-ts-template) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2023-10-19.
* [CIP 102 Reference Implementation](https://github.com/SamDelaney/CIP_102_Reference) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-22 - Official examples for implementing CIP-102 based royalties, made by the CIP's author.
* [Hello, World!](https://aiken-lang.org/example--hello-world) - Write and execute a smart contract on Cardano in 10 minutes
* [Vesting](https://aiken-lang.org/example--vesting/mesh) - Learn how to work with time
* [Gift Card](https://aiken-lang.org/example--gift-card) - Make gift cards using NFTs using Aiken and Deno fresh
* [Gimbalabs Aiken Essentials Module](https://plutuspbl.io/modules/303/slts) - Learn Aiken from scratch and develop your skills with hands-on exercises and mini-projects.

## Books

* [I can Aiken](https://book.io/book/i-can-aiken/) - A book for Aiken newcomers. Contact @johnnygreeney for a free book (x.com/cardanobook)

## Courses

* [Aiken - eUTxO smart contracts on Cardano](https://cardanofoundation.org/academy/course/aiken-eutxo-smart-contracts-cardano) - A 4-hour video course about Aiken, self-paced, on-demand and free. Created by the Cardano Academy

## Videos

* [NerdOut's Aiken edition](https://www.youtube.com/watch?v=9wbQ33uzwsc\&pp=ygUNQWlrZW4gY2FyZGFubw%3D%3D) - A high-level presentation of Aiken <sup> \~11 min</sup>
* [ReddSpark's beginner guide to Aiken](https://www.youtube.com/watch?v=-H5llvQdpRw\&pp=ygUPcmVkZHNwYXJrIGFpa2Vu) - A guided 'Hello, World!' tutorial for Windows users <sup> \~50 min</sup>
* [Hello, World! with Demeter](https://twitter.com/i/status/1652846950251732993) - The 'Hello, World!' tutorial but using `cardano-cli` instead of `Lucid` <sup> \~19min</sup>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
