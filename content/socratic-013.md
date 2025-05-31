+++
title = "Socratic Seminar 13"
date = 2025-06-19
+++

Housekeeping
------------

- This meetup is generously sponsored by [Spiral](https://spiral.xyz/)!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers May 16th to June 19th.

News
----
- [Block’s bitcoin checkout goes live in Vegas, a significant step in making it ‘everyday money’](https://www.cnbc.com/2025/05/27/block-bitcoin-checkout-vegas.html)
- [Block to roll out bitcoin payments on Square](https://block.xyz/inside/block-to-roll-out-bitcoin-payments-on-square)
- [Square Flies the Flag for the Lightning Network With 9.7% Yield on Bitcoin Holdings](https://www.coindesk.com/tech/2025/05/29/square-flies-the-flag-for-the-lightning-network-with-97-yield-on-bitcoin-holdings)
- [Block Announces Bitcoin Business Stack, Makes Historic Lightning Payments Push at Bitcoin 2025](https://bitcoinmagazine.com/news/block-announces-bitcoin-business-stack-makes-historic-lightning-payments-push-at-bitcoin-2025)
- [Amboss Launches Rails, a Self-Custodial Bitcoin Yield Service](https://bitcoinmagazine.com/news/amboss-launches-rails-a-self-custodial-bitcoin-yield-service)
- [Steak ‘n Shake Now Accepting Bitcoin via Lightning Network Across U.S. Locations](https://bitcoinmagazine.com/news/steak-n-shake-now-accepting-bitcoin-via-lightning-network-across-u-s-locations)
- [Steak ‘n Shake Reveals Bitcoin Payment Success at Bitcoin 2025 Conference](https://bitcoinmagazine.com/news/steak-n-shake-reveals-bitcoin-payment-success-at-bitcoin-2025-conference)
- [1.5 Million Users to Access Bitcoin’s Lightning Network on Xverse thanks to Sati](https://bitcoinmagazine.com/press-releases/1-5-million-users-to-access-bitcoins-lightning-network-on-xverse-thanks-to-sati)
- [Ark Labs Launches Arkade, a New Native Operating System Using Bitcoin](https://bitcoinmagazine.com/news/ark-labs-launches-arkade-a-new-native-operating-system-using-bitcoin)
- [Spark Partners with Breez to Launch Bitcoin-Native SDK for Lightning Payments](https://bitcoinmagazine.com/news/spark-partners-with-breez-to-launch-bitcoin-native-sdk-for-lightning-payments)
- [Magic Eden Partners with Spark to Bring Fast, Cheap Bitcoin Settlements](https://bitcoinmagazine.com/news/magic-eden-partners-with-spark-to-bring-fast-cheap-bitcoin-settlements)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Latency and Privacy in Lightning](https://delvingbitcoin.org/t/latency-and-privacy-in-lightning/1723)

#### [Bitcoin Optech Podcast](https://bitcoinops.org/en/podcast/)
- N/A

#### Miscellaneous
- N/A

Releases
--------
- N/A

bLIPs & BOLTs
-------------
- [Add recommendations for receiver-side random delays](https://github.com/lightning/bolts/pull/1263)
- [Success hold times](https://github.com/lightning/bolts/pull/1261)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Peer storage enable](https://github.com/ElementsProject/lightning/pull/8140)

### [eclair](https://github.com/ACINQ/eclair/)
- [Attributable failures](https://github.com/ACINQ/eclair/pull/3065)
- [Refactor some closing helper functions](https://github.com/ACINQ/eclair/pull/3089)
- [Add low-level taproot helpers](https://github.com/ACINQ/eclair/pull/3086)
- [Stricter batching of commit_sig messages on the wire](https://github.com/ACINQ/eclair/pull/3083)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Pass supported_protocols to LSPS0 (fix ListProtocols support)](https://github.com/lightningdevkit/rust-lightning/pull/3785)
- [Read ChannelManager even if we have no-peer post-update actions](https://github.com/lightningdevkit/rust-lightning/pull/3790)
- [Introduce interactive signing state flags for funded states.](https://github.com/lightningdevkit/rust-lightning/pull/3637)
- [Do not dip into the funder's reserve to cover the two anchors](https://github.com/lightningdevkit/rust-lightning/pull/3796)
- [LSPS2: Fail (or abandon) intercepted HTLCs if LSP channel open fails](https://github.com/lightningdevkit/rust-lightning/pull/3712)

### [lnd](https://github.com/lightningnetwork/lnd)
- [[graph-work-side-branch]: side branch for graph work](https://github.com/lightningnetwork/lnd/pull/9692)
- [lnwire: add lnwire.OpaqueAddr case in WriteElement for channel back-ups](https://github.com/lightningnetwork/lnd/pull/9856)
- [feat(lncli): Add --route_hints flag to sendpayment and queryroutes](https://github.com/lightningnetwork/lnd/pull/9721)
- [graph/db: init SQLStore caches and batch schedulers](https://github.com/lightningnetwork/lnd/pull/9853)
- [sqldb+graph/db: add node related tables and implement some node CRUD](https://github.com/lightningnetwork/lnd/pull/9866)
- [sqldb: re-usable TxOptions and NoOpReset](https://github.com/lightningnetwork/lnd/pull/9873)

Security
--------
- N/A
