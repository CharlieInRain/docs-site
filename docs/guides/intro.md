# Introduction


## Intro

[BNB Beacon Chain](https://www.bnbchain.world) is a blockchain developed by [Binance](https://www.binance.com) and its community that implements a vision of a decentralized exchange (DEX) for digital assets.

At the heart of BNB Beacon Chain is a highly performant [matching engine](./concepts/matching-engine.md) built on [distributed consensus](./concepts/architecture.md) that aims to replicate the <1 second trading efficiency of current centralized exchanges.

BNB Beacon Chain transactions burns BNB (the native token of the Binance ecosystem), according to a fee schedule.

BNB Beacon Chain also includes efforts to implement [listing assets from other chains](../atomic-swap.md), and cryptographic primitives such as [threshold signatures](./concepts/threshold-signature-scheme.md).

## Functionality

BNB Beacon Chain has the basic features of most blockchains:

- Sending and receiving BNB and digital assets
- Issuing new digital assets (we have a standard called BEP-2)
- Mint/burn, freeze/unfreeze, lock/unlock of digital assets

It has DEX and trading-specific functionality:

- Propose exchange listing for trading pairs
- Creating maker/taker orders for traders
- Listing assets from other chains using atomic swaps (BEP-3)

BNB Beacon Chain also implements new features, such as

- Threshold Signatures (an alternative to multisig)
- Smart Contracts sidechain (in-progress)

## Participate

There are different ways to participate in the network, from light nodes to full validators.

BNB Beacon Chain follows a philosophy of progressive decentralization. We envision a future where organizations and individuals can run validator nodes, and BNB can be staked to join governance.
