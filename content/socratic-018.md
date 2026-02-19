+++
title = "Socratic Seminar 21"
date = 2026-02-19
+++

Housekeeping
------------

- This meetup is generously sponsored by Presidio Bitcoin!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers January 15th, 2026 to February 18th, 2026.

News
----

- [Amboss Unveils RailsX: The First Lightning-Native DEX for P2P Bitcoin and Stablecoin Trading](https://www.prnewswire.com/news-releases/amboss-unveils-railsx-the-first-lightning-native-dex-for-p2p-bitcoin-and-stablecoin-trading-302669827.html)
- [SDM Completes $1 Million Lightning Transaction in Pilot to Kraken, Powered by Voltage](https://www.prnewswire.com/news-releases/sdm-completes-1-million-lightning-transaction-in-pilot-to-kraken-powered-by-voltage-302679837.html)
- [Lightning Labs Releases AI Agent Tools for Native Bitcoin Lightning Payments](https://www.theblock.co/post/389584/lightning-labs-releases-ai-agent-tools-for-native-bitcoin-lightning-payments)
- [Magma Liquidity Market Volume on Track to Double Month-over-Month](https://x.com/Jestopher_BTC/status/2091247476095984031)
- [Amboss Rails Cluster Providing Over $1M/Month in Liquidity to Lightning Network](https://x.com/tonyioi/status/2089598480306901363)
- [Bitcoin's Lightning Network Exceeds $1 Billion in Monthly Volume](https://x.com/SDWouters/status/2024507942708351443)
- [Voltage Launches Voltage Credit: Programmatic Revolving Line of Credit on Bitcoin Payment Rails](https://x.com/voltage_cloud/status/2024493145451614683)
- [Lightning's Noise Protocol: An Approachable Deep Dive](https://programminglightning.com/noise-tutorial)

Releases
--------

- [Core Lightning v25.12.1](https://github.com/ElementsProject/lightning/releases/tag/v25.12.1)
- [LND v0.20.1-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.20.1-beta)
- [LDK v0.1.9](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.1.9)
- [LDK v0.2.1](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.2.1)
- [LDK v0.2.2](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.2.2)

bLIPs & BOLTs
-------------

- [Lightning Specification Meeting 2026/02/09](https://github.com/lightning/bolts/issues/1315)
- [Allow either node to send tx_init_rbf in v2 establishment](https://github.com/lightning/bolts/pull/1236)
- [Explicit commit_sig retransmission for interactive-tx](https://github.com/lightning/bolts/pull/1289)
- [BOLT 12: clarify that empty offer_chains must be rejected](https://github.com/lightning/bolts/pull/1306)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)

- [Askrene: scale with many layers](https://github.com/ElementsProject/lightning/pull/8760)
- [No more legacy onion support](https://github.com/ElementsProject/lightning/pull/8772)
- [common: tighten restrictions on periods, as per latest draft](https://github.com/ElementsProject/lightning/pull/8821)
- [askrene: add auto.include_fees layer](https://github.com/ElementsProject/lightning/pull/8824)
- [askrene: fixed a timeout corner case](https://github.com/ElementsProject/lightning/pull/8866)
- [More flake reductions](https://github.com/ElementsProject/lightning/pull/8868)
- [Gossmap: compaction support](https://github.com/ElementsProject/lightning/pull/8869)
- [Askrene parallel solving support](https://github.com/ElementsProject/lightning/pull/8723)
- [bcli: Refactor bcli plugin to synchronous execution](https://github.com/ElementsProject/lightning/pull/8820)
- [Fix peer connect crash](https://github.com/ElementsProject/lightning/pull/8889)
- [Make all peer messages constant message size](https://github.com/ElementsProject/lightning/pull/8893)
- [Gossmap compaction](https://github.com/ElementsProject/lightning/pull/8903)

### [eclair](https://github.com/ACINQ/eclair)

- [Add duration information to payment events](https://github.com/ACINQ/eclair/pull/3241)
- [Include the node_id of channel peers in payment events](https://github.com/ACINQ/eclair/pull/3243)
- [Add event for failed payment relay](https://github.com/ACINQ/eclair/pull/3244)
- [Improve channel and payment events](https://github.com/ACINQ/eclair/pull/3246)
- [Prioritize private channels when relaying payments](https://github.com/ACINQ/eclair/pull/3248)

### [LDK](https://github.com/lightningdevkit/rust-lightning)

- [Introduce Dummy Hop support for Blinded Payment Path](https://github.com/lightningdevkit/rust-lightning/pull/4152)
- [Rework ChannelManager::funding_transaction_signed](https://github.com/lightningdevkit/rust-lightning/pull/4257)
- [Mixed mode splicing](https://github.com/lightningdevkit/rust-lightning/pull/4261)
- [Add custom TLV in Bolt11 Payer API](https://github.com/lightningdevkit/rust-lightning/pull/4263)
- [Split splice initiation into two phases](https://github.com/lightningdevkit/rust-lightning/pull/4290)
- [Support generic HTLC interception](https://github.com/lightningdevkit/rust-lightning/pull/4300)
- [Prevent HTLC double-forwards, prune forwarded onions](https://github.com/lightningdevkit/rust-lightning/pull/4303)
- [net-tokio: add fn socks5_connect_outbound](https://github.com/lightningdevkit/rust-lightning/pull/4305)
- [Drop ChannelHandshakeLimits::max_funding_satoshis](https://github.com/lightningdevkit/rust-lightning/pull/4318)
- [Free holding cells immediately rather than in message sending](https://github.com/lightningdevkit/rust-lightning/pull/4320)
- [Add support for "phantom" BOLT 12 offers, up to the invoice_request step](https://github.com/lightningdevkit/rust-lightning/pull/4335)
- [Rework ChannelManager::funding_transaction_signed](https://github.com/lightningdevkit/rust-lightning/pull/4336)
- [Support HTLC interception by source channel](https://github.com/lightningdevkit/rust-lightning/pull/4338)
- [Set dont_forward on private channel updates and add tests](https://github.com/lightningdevkit/rust-lightning/pull/4340)
- [Fix race condition in async UtxoFuture resolution](https://github.com/lightningdevkit/rust-lightning/pull/4348)
- [BOLT 12: Validate bech32 padding per BIP-173](https://github.com/lightningdevkit/rust-lightning/pull/4349)
- [Add basic `CLAUDE.md` file](https://github.com/lightningdevkit/rust-lightning/pull/4352)
- [Refactor `BroadcasterInterface` to include `TransactionType`](https://github.com/lightningdevkit/rust-lightning/pull/4353)
- [Default to anchors and remove automatic channel acceptance](https://github.com/lightningdevkit/rust-lightning/pull/4354)
- [Support async signing of interactive-tx initial commitment signatures](https://github.com/lightningdevkit/rust-lightning/pull/4355)
- [Hold in-flight monitor updates until background event processing](https://github.com/lightningdevkit/rust-lightning/pull/4377)
- [Switch `SplicePrototype` feature flag to the prod feature bit](https://github.com/lightningdevkit/rust-lightning/pull/4387)
- [Drive splices to completion in chanmon_consistency](https://github.com/lightningdevkit/rust-lightning/pull/4411)
- [Free holding cell in remaining quiescence-exit code paths](https://github.com/lightningdevkit/rust-lightning/pull/4415)

### [lnd](https://github.com/lightningnetwork/lnd)

- [actor: add new package for structured concurrency based on the Actor model](https://github.com/lightningnetwork/lnd/pull/9820)
- [actor: add new abstraction over mailbox](https://github.com/lightningnetwork/lnd/pull/10142)
- [multi: update close logic to handle re-orgs of depth n-1, where n is num confs](https://github.com/lightningnetwork/lnd/pull/10331)
- [graph/db: continue graph store for V2 data](https://github.com/lightningnetwork/lnd/pull/10380)
- [graph/db: merge g175 types-prep side branch](https://github.com/lightningnetwork/lnd/pull/10414)
- [switchrpc: improve TrackOnion error handling](https://github.com/lightningnetwork/lnd/pull/10472)
- [switchrpc: add idempotent external HTLC dispatch via SendOnion](https://github.com/lightningnetwork/lnd/pull/10473)
- [rpcserver: add wallet_synced to GetInfoResponse](https://github.com/lightningnetwork/lnd/pull/10507)
- [routerrpc: FailureDetail enums for invoice/AMP validation failures](https://github.com/lightningnetwork/lnd/pull/10520)
- [build: add cc integration](https://github.com/lightningnetwork/lnd/pull/10525)
- [build: add PR severity classification workflow](https://github.com/lightningnetwork/lnd/pull/10526)
- [graphdb: fix backwards-compat for channel edge feature deserialization](https://github.com/lightningnetwork/lnd/pull/10529)
- [lncli unlock: wait until daemon can unlock](https://github.com/lightningnetwork/lnd/pull/10536)
- [discovery: fix gossiper shutdown deadlock](https://github.com/lightningnetwork/lnd/pull/10540)
- [graph/db: add v2 gossip support for channel policies](https://github.com/lightningnetwork/lnd/pull/10542)
- [.claude+.github: add issue dedupe workflow](https://github.com/lightningnetwork/lnd/pull/10559)
