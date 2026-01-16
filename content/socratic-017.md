+++
title = "Socratic Seminar 17"
date = 2026-01-15
+++

Housekeeping
------------

- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers December 8th to January 15th.

News
----
- [Clarity Act (H.R. 3633)](https://x.com/Jestopher_BTC/status/2011247476095984031)
- [A Mathematical Theory of Payment Channel Networks](https://x.com/renepickhardt/status/2009598480306901363)
- [Lightning Year in Review Stats](https://x.com/ambosstech/status/2007135311558857177)
- [Stablecoins: Evolution, not a Revolution](https://bitcoinmagazine.com/markets/stablecoins-evolution-not-a-revolution)
- [Distributed Charge Public Testing](http://andyschroder.com/DistributedCharge/news/2025-12-19-PublicTesting)
- [Time2Build 2025 Winners: Breez Awards Bitcoin Prizes for Lightning Integrations in BTCPay Server, Primal, and More](https://bitcoinmagazine.com/business/time2build-2025-winners-breez-awards-bitcoin-prizes-for-lightning-integrations-in-btcpay-server-primal-and-more)
- [BitGo Adds Support for Lightning Network from Custody](https://www.bitgo.com/resources/blog/bitgo-adds-support-for-lightning-network-from-custody)
- [Tether Leads $8M Strategic Investment in Speed to Advance Lightning-Native, Stablecoin-Powered Payments](https://tether.io/news/tether-leads-8m-strategic-investment-in-speed-to-advance-lightning-native-stablecoin-powered-payments)
- [LQWD Delivers Record Bitcoin Lightning Network Volumes as Transaction Activity Accelerates](https://lqwdtech.com/2025/lqwd-delivers-record-bitcoin-lightning-network-volumes-as-transaction-activity-accelerates)
- [REEZ.io Upgrades Bitcoin Payments With Lightning Network Integration](https://markets.businessinsider.com/news/stocks/reez-io-upgrades-bitcoin-payments-with-lightning-network-integration-1035712305)
- [Travel Retail Norway starts accepting Bitcoin at Oslo Airport via Lightning Network](https://cryptobriefing.com/bitcoin-lightning-payments-oslo-airport)
- [Bitcoin Capacity on Lightning hits an All Time High — 5,637 BTC!](https://xcancel.com/ambosstech/status/2001062647438172363)


Delving Bitcoin
----
- [Ark as a Channel Factory: Compressed Liquidity Management for Improved Payment Feasibility](https://delvingbitcoin.org/t/ark-as-a-channel-factory-compressed-liquidity-management-for-improved-payment-feasibility/2179)

Releases
--------
- [CLN v25.12.1 Boltz's Seamless Upgrade Experience II](https://github.com/ElementsProject/lightning/releases/tag/v25.12.1)
- [ZEUS v0.12.0](https://blog.zeusln.com/new-release-zeus-v0-12-0)

bLIPs & BOLTs
-------------
- [Lightning Specification Meeting 2026/01/12](https://github.com/lightning/bolts/issues/1311)
- [Lightning Specification Meeting 2025/12/15](https://github.com/lightning/bolts/issues/1300)
- [bolt12: Add test vector for missing offer_amount with offer_currency](https://github.com/lightning/bolts/pull/1279)
- [bolt11: Clarify that n is not mandatory](https://github.com/lightning/bolts/pull/1305)
- [bLIP-51: Specify invalid token error code](https://github.com/lightning/blips/pull/68)
- [Update bLIP-51 to add BOLT-12 support](https://github.com/lightning/blips/pull/59)

Noteworthy PRs
--------------
### [Core Lightning](https://github.com/ElementsProject/lightning)
- [doc: Update docs to reflect new hsm secret format](https://github.com/ElementsProject/lightning/pull/8838)
- [Askrene: fix infinite cost assertion](https://github.com/ElementsProject/lightning/pull/8832)
- [Modern node hsm_secret fixes](https://github.com/ElementsProject/lightning/pull/8831)
- [recovery for modern nodes](https://github.com/ElementsProject/lightning/pull/8830)
- [xpay: payment description](https://github.com/ElementsProject/lightning/pull/8784)
- [lightningd: add description field to offer related responces](https://github.com/ElementsProject/lightning/pull/8782)
- [lightningd: fix segfault when parse_filter fails](https://github.com/ElementsProject/lightning/pull/8780)
- [Fix gossipd node announcement ordering](https://github.com/ElementsProject/lightning/pull/8769)
- [Refactor LSPS plugin into proto/core/cln_adapters layers](https://github.com/ElementsProject/lightning/pull/8768)
- [lightningd: fix db constraint error when fixing up old blocks.](https://github.com/ElementsProject/lightning/pull/8767)

### [eclair](https://github.com/ACINQ/eclair)
- [Rework channel lifecyle events](https://github.com/ACINQ/eclair/pull/3237)
- [Stop storing channel errors in `AuditDb`](https://github.com/ACINQ/eclair/pull/3236)
- [Dont rebroadcast announcements for spent channels](https://github.com/ACINQ/eclair/pull/3235)
- [Add `maxCltvExpiryDelta` parameter to `findRoute*` APIs](https://github.com/ACINQ/eclair/pull/3234)
- [Use fallback feerates on testnets](https://github.com/ACINQ/eclair/pull/3233)
- [Validate Bolt 11 fallback addresses](https://github.com/ACINQ/eclair/pull/3232)
- [Improvements and fixes for #3217 ](https://github.com/ACINQ/eclair/pull/3229)
- [fixup! Add API methods to spend funds sent to taproot channel addresses (#3220)](https://github.com/ACINQ/eclair/pull/3228)
- [Allow remote `dust_limit_satoshis` up to 5000 sats](https://github.com/ACINQ/eclair/pull/3227)
- [Dont scan the blockchain for spent external channels](https://github.com/ACINQ/eclair/pull/3226)
- [Identify failing node](https://github.com/ACINQ/eclair/pull/3224)
- [Unwatch previous funding tx after splice ](https://github.com/ACINQ/eclair/pull/3218)
- [Accountable HTLCs](https://github.com/ACINQ/eclair/pull/3217)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Parallelize `ChannelMonitor` loading from async `KVStore`s](https://github.com/lightningdevkit/rust-lightning/pull/4147)
- [Default to padding blinded paths](https://github.com/lightningdevkit/rust-lightning/pull/4213)
- [Reconstruct ChannelManager forwarded HTLCs maps from Channels](https://github.com/lightningdevkit/rust-lightning/pull/4227)
- [Avoid force-closing 0-conf channels when funding is reorgd](https://github.com/lightningdevkit/rust-lightning/pull/4231)
- [Set and relay experimental accountable signal](https://github.com/lightningdevkit/rust-lightning/pull/4232)
- [Automatically archive resolved `ChannelMonitor`s in the BP](https://github.com/lightningdevkit/rust-lightning/pull/4288)
- [Fix double-forward, prefer legacy forward maps](https://github.com/lightningdevkit/rust-lightning/pull/4289)
- [Remove circular reference in `GossipVerifier`](https://github.com/lightningdevkit/rust-lightning/pull/4294)
- [Add a trivial helper to LSPS5s `WebhookNotification`](https://github.com/lightningdevkit/rust-lightning/pull/4295)
- [Remove spurious debug assertion added in 0.2](https://github.com/lightningdevkit/rust-lightning/pull/4312)
- [Refactor unified_qr.rs to use bitcoin-payment-instructions](https://github.com/lightningdevkit/ldk-node/pull/666)
- [Insert channel funding outputs into Wallet](https://github.com/lightningdevkit/ldk-node/pull/726)
- [Parallelize `read_payments`](https://github.com/lightningdevkit/ldk-node/pull/739)
- [Parallelize init further](https://github.com/lightningdevkit/ldk-node/pull/747)
- [Add structured logging context fields to LogRecord](https://github.com/lightningdevkit/ldk-node/pull/751)

### [lnd](https://github.com/lightningnetwork/lnd)
- [multi: add BuildOnion, SendOnion, and TrackOnion RPCs](https://github.com/lightningnetwork/lnd/pull/9489)
- [htlcswitch: add InitAttempt for idempotent external dispatch](https://github.com/lightningnetwork/lnd/pull/10049)
- [lnwire+tlv+route: enforce TLV length validation and add tests](https://github.com/lightningnetwork/lnd/pull/10249)
- [Aux Closer: Move coop-close aux finalization to chain watcher](https://github.com/lightningnetwork/lnd/pull/10289)
- [estimatefee: tx fee estimate for selected inputs](https://github.com/lightningnetwork/lnd/pull/10296)
- [graph: fix inefficient query for IsPublicNode](https://github.com/lightningnetwork/lnd/pull/10356)
- [[g175:3] graph/db: continue prepping `models` for V2 data](https://github.com/lightningnetwork/lnd/pull/10379)
- [Enhance Lsp Heuristic when probing a payment](https://github.com/lightningnetwork/lnd/pull/10396)
- [multi: add `CombinedNonce` functionality to Musig2 Signers](https://github.com/lightningnetwork/lnd/pull/10436)
- [Always add the payment address when probing an invoice](https://github.com/lightningnetwork/lnd/pull/10439)
- [channeldb: fix race condition in link node pruning](https://github.com/lightningnetwork/lnd/pull/10462)
- [lnwire: enforce non-zero timestamp in gossip messages](https://github.com/lightningnetwork/lnd/pull/10469)
- [discovery: add panic recovery for gossip message processing ](https://github.com/lightningnetwork/lnd/pull/10470)
- [rpcserver: use protocol max for fundMax, not maxChanSize](https://github.com/lightningnetwork/lnd/pull/10488)
