+++
title = "Socratic Seminar 12"
date = 2025-05-15
+++

Housekeeping
------------

- This meetup is generously sponsored by [Spiral](https://spiral.xyz/)!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers April 25th to May 15th.

News
----
- [Revolut Integrates Lightspark for Lightning-Fast Bitcoin Payments in the UK and Europe](https://bitcoinmagazine.com/news/revolut-integrates-lightspark-for-lightning-fast-bitcoin-payments-in-the-uk-and-europe)
- [Coinbase: 15% of BTC transactions now move on Lightning rails](https://x.com/coinbase/status/1916961596775272652)
- [Amboss Liquidity Subscriptions](https://amboss.tech/blog/liquidity-subscriptions)
- [Geyserfund: Lightning is now 75% of contributions volume](https://x.com/steliosrammos/status/1921924760801357827)
- [Paying for Groceries with Bitcoin: SPAR, DFX, LNbits](https://news.lnbits.com/news/paying-for-groceries-with-bitcoin-inside-spars-lig)
- [57% of ticket sales for Adopting Bitcoin on Lightning](https://x.com/AdoptingBTC/status/1917380502547296389)
- [37% of Bitcoin transactions at CoinCorner on Lightning](https://x.com/CoinCorner/status/1917309714922098812)
- [Exploring Taproot Assets in Ark](https://blog.arklabs.xyz/taproot-assets-in-ark/)
- [BitGo Integrates Bitcoin Lightning Network](https://x.com/BitGo/status/1917285256367071321)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Mitigating Channel Depletion in the Lightning Network: A Survey of Potential Solutions](https://delvingbitcoin.org/t/mitigating-channel-depletion-in-the-lightning-network-a-survey-of-potential-solutions/1640)
- [Path Queries: Addressing Payment Reliability and Routing limitations](https://delvingbitcoin.org/t/path-queries-addressing-payment-reliability-and-routing-limitations/1672)

#### [Bitcoin Optech Podcast](https://bitcoinops.org/en/podcast/)
- N/A

#### Miscellaneous
- [Sovereign Tools: A comprehensive Bitcoin and Lightning Network wallet comparison tool](https://sovereigntools.com)
- [Misty Breez: A hybrid Lightning and Liquid network wallet built with the Nodeless Breez SDK](https://github.com/breez/misty-breez?tab=readme-ov-file)
- [Ultimate guide to LN routing and fee management.](https://stacker.news/items/972730)
- [Taproot Assets Extension for lnbits](https://github.com/echennells/taproot_assets)

Releases
--------
- [Core Lightning v25.02.2](https://github.com/ElementsProject/lightning/blob/v25.02.2/CHANGELOG.md)
- [LND v0.19.0-beta.rc4](https://github.com/lightningnetwork/lnd/blob/master/docs/release-notes/release-notes-0.19.0.md)
- [LNDg v1.10.0](https://github.com/cryptosharks131/lndg/releases/tag/v1.10.0)
- [Zeus v0.11.0-alpha4](https://github.com/ZeusLN/zeus/releases/tag/v0.11.0-alpha4)
- [Phoenix v2.6.0](https://github.com/ACINQ/phoenix/releases/tag/android-v2.6.0)

bLIPs & BOLTs
-------------
- [Require minimally-encoded features in BOLT 11 invoices](https://github.com/lightning/bolts/pull/1245)
- [Lightning Specification Meeting 2025/05/05](https://github.com/lightning/bolts/issues/1255)
- [BIP 321: URI Scheme (Replace BIP 21 with a new BIP containing information about more modern usage of it)](https://github.com/bitcoin/bips/pull/1555)
- [Does option_simple_close depend on CPFP carve out ?](https://github.com/lightning/bolts/issues/1253)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Add LSPS0 Client and Service Plugin](https://github.com/ElementsProject/lightning/pull/8227)
- [Handle closed channels better](https://github.com/ElementsProject/lightning/pull/8162)
- [lightningd: add short_channel_id option to listpeerchannels.](https://github.com/ElementsProject/lightning/pull/8237)
- [Splice: Interop Final (probably) with Eclair](https://github.com/ElementsProject/lightning/pull/8021)
- [bcli: don't try asking non-full nodes for blocks.](https://github.com/ElementsProject/lightning/pull/8268)
- [Workaround for LND to cause a force-close on our channel](https://github.com/ElementsProject/lightning/pull/8213)
- [Sendonion: add total amount](https://github.com/ElementsProject/lightning/pull/8015)
- [Signmessage](https://github.com/ElementsProject/lightning/pull/8226)

### [eclair](https://github.com/ACINQ/eclair/)
- [Simplify channel keys management](https://github.com/ACINQ/eclair/pull/3064)
- [Rework the TransactionWithInputInfo architecture](https://github.com/ACINQ/eclair/pull/3074)
- [Increase default revocation timeout](https://github.com/ACINQ/eclair/pull/3082)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [(2/3) Add Enum for HTLCHandlingFailed Reasons](https://github.com/lightningdevkit/rust-lightning/pull/3601)
- [(3/3) Add Failure Reason to HTLCHandlingFailed](https://github.com/lightningdevkit/rust-lightning/pull/3700)
- [Expand PaymentClaimable to include all inbound channel IDs for a payment](https://github.com/lightningdevkit/rust-lightning/pull/3655)
- [Log which hop in a path was the most limiting in capacity](https://github.com/lightningdevkit/rust-lightning/pull/3729)
- [Do not fail to load ChannelManager when we see claiming payments](https://github.com/lightningdevkit/rust-lightning/pull/3772)
- [Sweeper async change destination source fetching](https://github.com/lightningdevkit/rust-lightning/pull/3734)
- [Disallow dual-sync-async persistence without restarting](https://github.com/lightningdevkit/rust-lightning/pull/3737)

### [lnd](https://github.com/lightningnetwork/lnd)
- [sweep: return all inputs in PendingSweeps](https://github.com/lightningnetwork/lnd/pull/9772)
- [multi: downgrade to legacy coop close for taproot channels](https://github.com/lightningnetwork/lnd/pull/9669)
- [chain: add testnet4 support](https://github.com/lightningnetwork/lnd/pull/9620)
- [bimodal pathfinding probability improvements](https://github.com/lightningnetwork/lnd/pull/8330)

Security
--------
- N/A
