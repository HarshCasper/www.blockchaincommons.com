---
cover: false
hide_description: true
permalink: /projects.html
---

Blockchain Commons is working on a large variety of projects all intended to improve the entirety of the community who is using blockchain technology and developing it.

<hr>

## Gordian Reference Projects

_Reference projects demonstrate the self-sovereign approach of the Gordian principles, highlighting Independence, Privacy, Resilience, and Openness._

### The Core Gordian System (web + iOS)

**Repo:** [Gordian](https://github.com/BlockchainCommons/Gordian)<br>
**Status:** Varied

The Gordian system is a suite of powerful open-source tools that demonstrate a self-sovereign solution for Bitcoin embodied in the Gordian principles. It does so by using [Torgap](https://github.com/BlockchainCommons/torgap) and [QuickConnect API](https://github.com/BlockchainCommons/Gordian/blob/master/Docs/Quick-Connect-API.md) technology to link a protected [GordianServer-MacOS](https://github.com/BlockchainCommons/GordianServer-macOS) (or the alternative [Bitcoin Standup Linux Scripts](https://github.com/BlockchainCommons/Bitcoin-StandUp-Scripts)) with a mobile [GordianWallet-iOS](https://github.com/BlockchainCommons/GordianWallet-iOS) so that you access full-node capabilities from a mobile device. (It's meant to cut through a traditionally knotty problem in Bitcoin development.) 

### Gordian CoSigner (Android, iOS, MacOS)

**Repo:** [CoSigner iOS](https://github.com/BlockchainCommons/GordianCosigner-iOS), [CoSigner Android](https://github.com/BlockchainCommons/GordianSigner-Android), or [CoSigner macOS](https://github.com/BlockchainCommons/GordianSigner-macOS)<br>
**Status:* Varied

Gordian CoSigner is an offline signing tool that transmit PSBTs through QR Codes across an Airgap that improves seed security.

### Gordian QR Tool (iOS)

**Repo:** [QR Tool](https://github.com/BlockchainCommons/GordianQRTool-iOS)<br>
**Status:* Testflight Release

QR Tool is an airgapped vault for containing secure QRs such as 2FAs, Bitcoin addresses, and URs.

### Gordian Seed Tool (iOS)

**Repo:** [Seed Tool](https://github.com/BlockchainCommons/GordianSeedTool-iOS)<br>
**Status:* Testflight Release

Seed Tool is a cryptographic seed manager for iOS that acts as a secure, airgapped vault.

### LetheKit (kit)

<a href="images/projects/lethekit.jpg"><img src="images/projects/lethekit.jpg" align="right" border="1" width="200"></a>
**Repo:** [lethekit](https://github.com/BlockchainCommons/lethekit)<br>
**Status:** Late Alpha<br>
**Blog:** 10/28/20: [Blockchain Commons Releases Feature-complete LetheKit](https://www.blockchaincommons.com/projects/Releasing-LetheKit/)

LetheKit is a do-it-youself platform for performing various sensitive cryptographic operations on an offline airgapped device. It uses no WiFi or Bluetooth which could leak information and contains no local storage, and when the device is turned off it forgets any sensitive data stored in RAM. Thus the name Lethe (lee-thee), from the mythological river of forgetfulness and oblivion.

### Spotbit (web)

**Repo:** [spotbit](https://github.com/BlockchainCommons/spotbit)<br>
**Status:** Late Alpha

Spotbit is a portable Flask API for Bitcoin price data and candles. It can either be used as a repository of historical data that allows for more frequent API requests, or as a simple wrapper around exchange APIs that permits the user to collect information over Tor. It can aggregate data from over 100 exchanges and serve them from a single URL or using Tor as an onion hidden service. It's extremely flexible: the user can decide which base currencies to use (USDT, USD, EUR etc), which exchanges to keep data for, and how much data to keep.

<hr>

## Educational Projects

_Educational projects consist of books, tutorials, or courses, intended to teach the usage of blockchains to programmers and end users alike._

### Learning Bitcoin from the Command Line

<a href="images/projects/lbtc.png"><img src="images/projects/lbtc.png" align="right" border="1" width="500"></a>
**Repo:** [Learning-Bitcoin-from-the-Command-Line](https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line)<br>
**Status:** v2.0 Complete (2020-10-20)<br>
**Blog:** 10/30/20: [Learning Bitcoin Upgrades to v2](https://www.blockchaincommons.com/projects/Learning-Bitcoin-Upgrades-to-v2/)

This is a complete nineteen-chapter course intended to teach system administrators, developers, and engineers who are already acquainted with the UNIX command line interface how to work with Bitcoin. It uses this methodology to teach the fundamentals of Bitcoin, from RPC communications to how transactions work and how scripts work. The majority of the course is focused on `bitcoin-cli`, but there's also information on scripting, on programming with the RPC interface, and on using other command-line programs, beginning with `lightning-cli`. 

### #SmartCustody

<a href="images/projects/sc.png"><img src="images/projects/sc.jpg" align="right" border="1" width="200"></a>  
**PDF:** [#SC v1.01](https://bit.ly/SmartCustodyBookV101)<br>
**Book Site:** [WWW Site](https://www.smartcustody.com/)
**Repo:** [SmartCustodyBook](https://github.com/BlockchainCommons/SmartCustodyBook)<br>
**Status:** v1.01 Complete (2019-09-16)<br>
**Future:** [Outline for v2.0](https://github.com/BlockchainCommons/SmartCustodyBook/blob/master/TODO.md)<br>
**Blog:** 1/4/19: [First #SmartCustody Workshop: Simple Cold Storage & Self-Custody](https://www.blockchaincommons.com/projects/First-SmartCustody-Workshop-Simple-Cold-Storage-and-Self-Custody/)

_The Use of Advanced Cryptographic Tools to Improve the Care, Maintenance, Control, and Protection of Digital Assets._ This five-chapter (186-page) book is intended to make you rethink the security of your digital assets. It puts together a risk-modeling system with two additional building blocks: a cold-storage scenario for managing self-custody; and an extensively detailed list of potential adversaries. By working through the book, you can determine which adversaries are actually the most dangerous to your assets, and adjust your own self-custody scenario to accomodate them. Additional chapters talk about fiduciary duties with regard to digital assets. 

A v2.0 of this book is in the planning stage, to improve the accessibility of the course, to support additional hardware tools, and to introduce multi-signature scenarios. Our [multisig design article](https://github.com/BlockchainCommons/Gordian/blob/master/Docs/Multisig.md) is our first content for that update.

<hr>

## Developer Projects

_Developer projects create resources for use by engineers and programmers, including libraries and CLIs._

### C Libraries

**Repos:** [bc-crypto-base](https://github.com/BlockchainCommons/bc-crypto-base), [bc-shamir](https://github.com/blockchainCommons/bc-shamir/), [bc-sskr](https://github.com/BlockchainCommons/bc-sskr), [bc-bip39](https://github.com/BlockchainCommons/bc-bip39), and [bc-ur](https://github.com/BlockchainCommons/bc-ur)<br>
**Status:** Feature-complete beta

Blockchain Commons offers a variety of C-language cryptographic libraries focuses largely on wallet design, which can be used in your own projects. The currently libraries include 
reference implementations of [BIP39](https://github.com/BlockchainCommons/bc-bip39), [Shamir Secret Sharing](https://github.com/blockchainCommons/bc-shamir/), [Shamir Secret Key Recovery](https://github.com/BlockchainCommons/bc-sskr), and [Uniform Resources](https://github.com/BlockchainCommons/bc-ur). The usage of these libraries is also demonstrated in [the keytool app](https://github.com/blockchainCommons/keytool-cli) and the [seedtool app](https://github.com/blockchainCommons/seedtool-cli).

### Bytewords-CLI

**Repo:** [bytewords-cli](https://github.com/BlockchainCommons/bytewords-cli)
**Status:** Feature-complete beta

Bytewords is a command-line tool that can be used to translate to and from various [Bytewords](https://github.com/BlockchainCommons/Research/blob/master/papers/bcr-2020-012-bytewords.md) formats, exercising the [Bytewords library](https://github.com/blockchaincommons/bc-bytewords).

### Keytool-CLI

<a href="images/projects/keytool.png"><img src="images/projects/keytool.png" align="right" border="1" width="500"></a>
**Repo:** [keytool-cli](https://github.com/BlockchainCommons/keytool-cli)<br>
**Status:** Feature-complete beta

keytool is a command-line tool that implements a data flow graph for deriving cryptocurrency keys and addresses. Any of the nodes in the graph can be assigned and any set of nodes can be derived as long as their dependencies are met. It also acts as a showcase for Blockchain Commons' C libraries, such as our reference implementations of [BIP39](https://github.com/BlockchainCommons/bc-bip39), [Shamir Secret Sharing](https://github.com/blockchainCommons/bc-shamir/), [Shamir Secret Key Recovery](https://github.com/BlockchainCommons/bc-sskr), and [Uniform Resources](https://github.com/BlockchainCommons/bc-ur).

### LifeHashTool-CLI

**Repo:** [LifeHashTool](https://github.com/BlockchainCommons/LifeHashTool)
**Status:** Late Alpha

LifeHashTool can be used to generate lifehashes from the command line, based on the [LifeHash format](https://github.com/BlockchainCommons/LifeHash).

### Seedtool-CLI

**Repo:** [seedtool-cli](https://github.com/BlockchainCommons/seedtool-cli)<br>
**Status:** Feature-complete beta

seedtool is a command-line tool for creating and transforming cryptographic seeds of the sort commonly used by blockchain applications. It exercises the various cryptographic C libraries created by Blockchain Commons, such as our reference implementations of [BIP39](https://github.com/BlockchainCommons/bc-bip39), [Shamir Secret Sharing](https://github.com/blockchainCommons/bc-shamir/), [Shamir Secret Key Recovery](https://github.com/BlockchainCommons/bc-sskr), and [Uniform Resources](https://github.com/BlockchainCommons/bc-ur).

<hr>

## Open Infrastructure Projects

_Open infrastructure projects create resources that can be used by the entire internet community._

### Spotbit Server

**Onion Address:** h6zwwkcivy2hjys6xpinlnz2f74dsmvltzsd4xb42vinhlcaoe7fdeqd.onion<br>
**Related Repo:** [spotbit](https://github.com/BlockchainCommons/spotbit)

A instance of Blockchain Commons' Spotbit Bitcoin price-aggregation server, available for public usage.

### Testnet Public Node

**Testnet Node:**<br>
**Related Repo:** [GordianWallet-iOS](https://github.com/BlockchainCommons/GordianWallet-iOS)

Blockchain Commons maintains a public Bitcoin testnet node, primarily for use as an optional server for use with GordianWallet.

### Tor Exit Node

**Tor Node:**<br> [644074F47257F9A906F9AA5C6B8926C1540A1DA8](https://metrics.torproject.org/rs.html#details/644074F47257F9A906F9AA5C6B8926C1540A1DA8)

Blockchain Commons supports the open infrastructure of Tor by running its own exit node.

<center>
<img align="center" src="https://raw.githubusercontent.com/BlockchainCommons/www.blockchaincommons.com/master/images/tor-graph.png" width="100%">
  </center>
