---
id: chainlink
title: On Chainlink
sidebar_label: On Chainlink
layout: post
tags: [crypto, blockchain]
---

Chainlink is one of those fundamental projects that I can't just stop talking about. This post will be an ongoing proof of that. People tend to like my communication style, which is why I'll keep posting. Below you can see some of the Tweetstorms I produced to describe this amazing technology:

- [What is Chainlink?](https://twitter.com/dmitrydao/status/1353850962734166016)
- [Chainlink and NFTs](https://twitter.com/dmitrydao/status/1349765189072248837)
- [Proof of Reserve](https://twitter.com/dmitrydao/status/1351879347641180160)
- [Secure Oracle Notification System](https://twitter.com/dmitrydao/status/1358093120227966976)
- [Chainlink Node Installation](https://twitter.com/dmitrydao/status/1354199414114578439)
- [Premium Quality Data](https://twitter.com/dmitrydao/status/1364618401616957440)

<!--truncate-->

## What is Chainlink?

Chainlink represents an ecosystem of numerous decentralized oracle networks. This implies that it’s not just an oracle and it’s not even a network of oracles. It’s a lot bigger than that.

Each oracle is simply a service that responds to whatever real-life event based on a certain trigger or a direct request: booking confirmation, car purchase, FX rate change, rental signature. Essentially, it’s an IFTTT for the blockchain world.

See, smart contracts can’t communicate to Web APIs, payments systems, cloud providers, etc. APIs break, databases get deleted, infra for other blockchains become unstable. That’s why nodes will never include this unpredictable behavior in their validation process.

You could create your own oracle or use a centralized one. But that kind of breaks the whole point of decentralization and you waste a lot of resources in the process.

Next. Each event (e.g. weather data change) on a Chainlink network is processed by multiple oracles within the same type of an oracle network:
- Decentralized Price Feeds
- A Verifiable Random Function (VRF)
- External Adapters
- Other

Price Feeds are pre-built and return a price for a requested asset pair (e.g. ETH/USD). VRF helps generate random numbers on-chain in a secure and provably-fair way. External Adapters are useful for custom data manipulation, such as computation, authentication, etc.

These different types of oracle networks form an entire ecosystem or a set of decentralized oracle networks.  The best part is that they run in parallel without interfering with each other. Let’s just say they are independent and awesome.

## Chainlink and NFTs

NFT is big. NFT + Chainlink is much bigger. Here’s my outlook on why this is a perfect combination of two awesome technologies.

A smart contract that receives the recent player, team or tournament stats from a Chainlink oracle could offer the most accurate real-time NFT minting and burning in the world.

A Chainlink oracle that monitors ETH fees could notify and predict the best time slots to mint NFT tokens. Marketplaces could create an alternative to a mempool and automatically mint tokens based on the fee an artist is willing to pay for an issuance.

Chainlink VRF opens a chance to mint assets that don’t have prearranged features or properties. Typically this generates more interest and engagement within the gaming industry but look at what happened to CryptoKitties.

A Chainlink oracle could trigger immediate shipping of a physical painting from an artist’s stock (e.g. DHL) to a new owner of the digital NFT. The address should be revealed between a buyer and seller only though. And this can’t be on-chain, too risky.

An oracle that retrieves social engagement of any fanbase (music, movies, sports, etc.) could generate enough information to create NFTs of the most active fans. This will skyrocket the engagement of communities, especially if these NFTs are tradable on global markets.

NFT that represents a physical object with an expiry date can be automatically burned after the Chainlink oracle sends this data to the corresponding smart contract.

Properties, land, commodities, and any financial asset class could be represented as an NFT and retrieve the corresponding properties, such as location, size, market rate, solvency, valuations, etc. from the Chainlink oracle.

## Proof of Reserve

I believe stablecoins, collateral and money reserve audits and checks could become gigantic use cases for Chainlink.

Typically stablecoin issuers do quarterly semi-annual and/or annual audits because it’s expensive and reveals the truth behind assets. Some of them don’t do audits at all or can only provide partial data, which is not transparent and accurate enough.

An oracle could pull the data from bank accounts and various resources to verify that a marketcap of whatever stablecoin is backed by a list of real assets, debt, collateral, or whatever form of value that is acceptable in both the traditional and crypto financial industry.

This allows hourly and daily audits for stablecoin issuers, which removes potential market manipulations due to some rumors of involved parties.

The same approach could be applied across every niche within the crypto industry that requires proof of asset issuance, ownership, availability, etc.

Here’s a few potential mind-blowing things:
⁃ proof of funds on hot and cold wallets of an A exchange
⁃ asset allocation of a B fund, company, investor
⁃ solvency of a C person, firm, entity
⁃ instant proof of ownership of a D entity, equity, stock, license, etc.

## Secure Oracle Notification System

Recently I was exposed to an interesting use case of a decentralized network of oracles like Chainlink.

The idea relies on having an oracle network that looks for various types of attacks and exploits on exchanges, wallets, DeFi protocols, and other products that secure funds for their users.

These include DDoS, Sybil, and Phishing attacks, transaction malleability, flash loans, and oracle attacks, exotic vulnerabilities in smart contracts, etc. 

Not all but most of them are possible for scheduled monitoring, which could create a Secure Oracle Notification System.

Here are some examples of how that might work:
- When a hack happens, oracles could send a notification to all exchanges to block compromised addresses.
- Each exchange could subscribe to a preferred group of attacks that Chainlink nodes will check during the day.
- Lending protocols may collect data from oracles after each flash loan happens to identify malicious patterns.
- Oracles could verify that exchanges don't manipulate users' funds when they go into maintenance mode or completely offline because of overload.

## Premium Quality Data

Top 5 ways how Chainlink provides premium quality data for their users:

1. Chainlink nodes consume price data from multiple data aggregators (e.g. Amberdata, Brave New Coin, etc.) that maintain volume-adjusted market coverage across all trading environments. To achieve the highest quality nodes rely on data from several aggregators, not just one.

2. For serving APIs and data feeds from sources with advanced security measures (API keys, credentials, passwords) Chainlink nodes use highly customizable external adapters. These can be built by any developer and applied to any node.

3. Market data aggregators and providers (e.g. Coingecko) can operate their own node and sell their data directly to smart contracts. Gradually this will increase the trust for the overall network because it removes the need for external actors to route the data on-chain.

4. Service Agreements between nodes and requesting smart contracts will allow having pre-defined parameters to be compliant with. The node will be paid only when the response matches with the agreed terms and conditions (data quality, the latency of response, etc.)

5. Clients that consume data from Chainlink can configure which nodes they want to request the data from based on immutable historic performance records, such as reputation frameworks and node marketplaces.

I'm sure there are more important use cases than the above. Just sharing what came into my mind first.