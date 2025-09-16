+++
title = "Socratic Seminar 15"
date = 2025-09-18
+++

Housekeeping
------------

- This meetup is generously sponsored by [Spiral](https://spiral.xyz/)!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- Welcome Bitcoin Design Week Attendees
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers August 22nd to September 18th.

Presentation
----
Steve Lee - Spark (Preview of Steve's presentation at lightning++ in Berlin)

News
----
- [SoFi Taps Bitcoin Lightning Network for Global Remittances With Lightspark](https://www.coindesk.com/business/2025/08/19/sofi-taps-bitcoin-lightning-network-for-global-remittances-with-lightspark)
- [LQWD's Lightning Network Strategy Shows Strong Initial Bitcoin Yield; Results Highlight Potential Yield at Scale on LQWD's BTC Treasury](https://lqwdtech.com/2025/lqwds-lightning-network-strategy-shows-strong-initial-bitcoin-yield-results-highlight-potential-yield-at-scale-on-lqwds-btc-treasury/)
- [Chipper Cash Now Processes Over 50% of Bitcoin Transactions Through Lightning — Powered by Voltage](https://www.voltage.cloud/blog/chipper-cash-now-processes-over-50-of-bitcoin-transactions-through-lightning-powered-by-voltage)
- [ZBD’s SDK Powers Bitcoin Earnings in Mobile Games, Driving 124% Revenue Growth](https://bitcoinmagazine.com/business/zbds-sdk-powers-bitcoin-earnings-in-mobile-games-driving-124-revenue-growth)
- [RocoMamas adopts Bitcoin Lightning payments at over 100 locations in South Africa](https://cryptobriefing.com/rocomamas-adopts-bitcoin-lightning-payments-south-africa/)

Discussion
----------
- [State of Lightning Privacy - Spiral's Elias Rohrer @ bitcoin++ privacy edition](https://www.youtube.com/watch?v=mvuWLob3CFU&t=817s)
- [MultiChannel and MultiPTLC: Towards A Global High-Availability CP Database For Bitcoin Payments](https://delvingbitcoin.org/t/multichannel-and-multiptlc-towards-a-global-high-availability-cp-database-for-bitcoin-payments/1983/1)
- [Lightning Is Misunderstood](https://bitcoinmagazine.com/print/lightning-is-misunderstood)
- [Lightning swaps *are* the connective tissue](https://insider.btcpp.dev/p/lightning-swaps-are-the-connective)

Released
--------
- [Core Lightning v25.09 Hot Wallet Guardian](https://github.com/ElementsProject/lightning/releases/tag/v25.09)
- [lnd v0.19.3-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.19.3-beta)
- [Eclair v0.13.0](https://github.com/ACINQ/eclair/blob/master/docs/release-notes/eclair-v0.13.0.md)

bLIPs & BOLTs
-------------
- [Lightning Specification Meeting 2025/08/25](https://github.com/lightning/bolts/issues/1283)
- [Lightning Specification Meeting 2025/09/08](https://github.com/lightning/bolts/issues/1286)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [offers: loosen payment_constraints on invoices' blinded paths.](https://github.com/ElementsProject/lightning/pull/8500)
- [common/bolt11: Fix BOLT11 hash calculation for unknown fallback address versions](https://github.com/ElementsProject/lightning/pull/8302)
- [plugins/bcli: use -rpcwait to simplify waiting for bitcoind to warm up](https://github.com/ElementsProject/lightning/pull/7967)
- [Added fixed SOURCE_DATE_EPOCH flag for reproducible ubuntu builds](https://github.com/ElementsProject/lightning/pull/8547)

### [eclair](https://github.com/ACINQ/eclair)
- [Adjust batch_size on commit_sig retransmission](https://github.com/ACINQ/eclair/pull/3147)
- [Split commit nonces from funding nonce in tx_complete](https://github.com/ACINQ/eclair/pull/3145)
- [Allow omitting previousTx for taproot splices](https://github.com/ACINQ/eclair/pull/3143)
- [Allow overriding max-closing-feerate with forceclose API](https://github.com/ACINQ/eclair/pull/3142)
- [Allow non-initiator RBF for dual funding](https://github.com/ACINQ/eclair/pull/3021)
- [Use balance estimates from past payments in path-finding](https://github.com/ACINQ/eclair/pull/2308)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Improve privacy for Blinded Message Paths using Dummy Hops](https://github.com/lightningdevkit/rust-lightning/pull/3726)
- [Update channel_reestablish for splicing](https://github.com/lightningdevkit/rust-lightning/pull/3886)
- [Custom Transactions Add TxBuilder::get_next_commitment_stats](https://github.com/lightningdevkit/rust-lightning/pull/3921)
- [Async FilesystemStore](https://github.com/lightningdevkit/rust-lightning/pull/3931)
- [Add splice-out support](https://github.com/lightningdevkit/rust-lightning/pull/3979)
- [Add LSPS5 DOS protections.](https://github.com/lightningdevkit/rust-lightning/pull/3993)
- [Validate funding contributions reserves in splice_init and splice_ack handling](https://github.com/lightningdevkit/rust-lightning/pull/4011)
- [Integrate Splicing with Quiescence](https://github.com/lightningdevkit/rust-lightning/pull/4019)
- [Support splice shared input signing](https://github.com/lightningdevkit/rust-lightning/pull/4024)
- [Emit DiscardFunding events for double spent splice transactions](https://github.com/lightningdevkit/rust-lightning/pull/4030)
- [Randomize order of inputs from OutputSweeper](https://github.com/lightningdevkit/rust-lightning/pull/4033)
- [Commit to client's node id in bLIP-52/LSPS2 promise](https://github.com/lightningdevkit/rust-lightning/pull/4040)
- [Create a single P2A anchor on commitment transactions in 0FC channels](https://github.com/lightningdevkit/rust-lightning/pull/4053)
- [Always-online node forward invoice request](https://github.com/lightningdevkit/rust-lightning/pull/4049)
- [Async send always-online counterparty side](https://github.com/lightningdevkit/rust-lightning/pull/4045)
- [Account for splices in claimable balances](https://github.com/lightningdevkit/rust-lightning/pull/4029)

### [lnd](https://github.com/lightningnetwork/lnd)
- [1/2 discovery+lnwire: add support for DNS host name in NodeAnnouncement msg](https://github.com/lightningnetwork/lnd/pull/9455)
- [Rate limit outgoing gossip bandwidth by peer](https://github.com/lightningnetwork/lnd/pull/10103)
- [graph/db+sqldb: Make the SQL migration retry-safe/idempotent](https://github.com/lightningnetwork/lnd/pull/10161)
- [graph/db: unwrap dns addresses from opaque ones during migration](https://github.com/lightningnetwork/lnd/pull/10162)
- [multi: switch on graph SQL migration](https://github.com/lightningnetwork/lnd/pull/10163)
- [build: make special label checks auto-pass instead of skip](https://github.com/lightningnetwork/lnd/pull/10187)
- [docs: add docs for EstimateRouteFee](https://github.com/lightningnetwork/lnd/pull/10149)
- [Add Support for P2TR Fallback Addresses in BOLT-11](https://github.com/lightningnetwork/lnd/pull/9975)
- [Expose confirmation count for pending 'channel open' transactions](https://github.com/lightningnetwork/lnd/pull/9677)

Security
--------
