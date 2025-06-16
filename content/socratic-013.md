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
- [LNBig routing income data](https://njump.me/nevent1qqsfjq45qu5d8tzjhz2kqtzsw49dn8tucyva2jat8trpxnlh4muqzjspzemhxue69uhhyetvv9ujumn0wd68ytnzv9hxgqgdwaehxw309ahx7uewd3hkcq3qngumlqmus6xkrmvvee4yc7swh9h4uk7vpq4ddt7a2jtvkc22y0asytq3hw)
- [Block Announces Bitcoin Business Stack, Makes Historic Lightning Payments Push at Bitcoin 2025](https://bitcoinmagazine.com/news/block-announces-bitcoin-business-stack-makes-historic-lightning-payments-push-at-bitcoin-2025)
- [Amboss Launches Rails, a Self-Custodial Bitcoin Yield Service](https://bitcoinmagazine.com/news/amboss-launches-rails-a-self-custodial-bitcoin-yield-service)
- [Steak ‘n Shake Now Accepting Bitcoin via Lightning Network Across U.S. Locations](https://bitcoinmagazine.com/news/steak-n-shake-now-accepting-bitcoin-via-lightning-network-across-u-s-locations)
- [Steak ‘n Shake Reveals Bitcoin Payment Success at Bitcoin 2025 Conference](https://bitcoinmagazine.com/news/steak-n-shake-reveals-bitcoin-payment-success-at-bitcoin-2025-conference)
- [1.5 Million Users to Access Bitcoin’s Lightning Network on Xverse thanks to Sati](https://bitcoinmagazine.com/press-releases/1-5-million-users-to-access-bitcoins-lightning-network-on-xverse-thanks-to-sati)
- [Ark Labs Launches Arkade, a New Native Operating System Using Bitcoin](https://bitcoinmagazine.com/news/ark-labs-launches-arkade-a-new-native-operating-system-using-bitcoin)
- [Spark Partners with Breez to Launch Bitcoin-Native SDK for Lightning Payments](https://bitcoinmagazine.com/news/spark-partners-with-breez-to-launch-bitcoin-native-sdk-for-lightning-payments)
- [Magic Eden Partners with Spark to Bring Fast, Cheap Bitcoin Settlements](https://bitcoinmagazine.com/news/magic-eden-partners-with-spark-to-bring-fast-cheap-bitcoin-settlements)
- [Save Our Wallets Launch](https://saveourwallets.org)
- [BRCA Included in market structure bill, the Clarity Act](https://x.com/TheBlueMatt/status/1931875497388245195)
- [Bitcoin Development Fund 5 year Report](https://hrf.org/latest/bitcoin-development-fund-5-year-report/)
- [Lightning Wallet Market Share in Japan](https://x.com/DiamondHandsLN/status/1922642890271916443)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Latency and Privacy in Lightning](https://delvingbitcoin.org/t/latency-and-privacy-in-lightning/1723)
- [Research Update: A Geometric Approach for Optimal Channel Rebalancing](https://delvingbitcoin.org/t/research-update-a-geometric-approach-for-optimal-channel-rebalancing/1768)

#### [Bitcoin Optech Podcast](https://bitcoinops.org/en/podcast/)
- N/A

#### Miscellaneous
- N/A

Releases
--------
- [LND v0.19.0-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.19.0-beta)
- [LND v0.19.1-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.19.1-beta)
- [LDK v0.1.4 - May 23, 2025 - "Careful Validation of Bogus States"](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.1.4)

bLIPs & BOLTs
-------------
- [Clarify Mandatory Field Length Requirements and Add Note on Low R Signatures in BOLT 11](https://github.com/lightning/bolts/pull/1243)
- [Path queries (feature 66/67)](https://github.com/lightning/bolts/pull/1259)
- [Add recommendations for receiver-side random delays](https://github.com/lightning/bolts/pull/1263)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Peer storage enable](https://github.com/ElementsProject/lightning/pull/8140)
- [gossipd: check for existing channel announcement before sigcheck](https://github.com/ElementsProject/lightning/pull/8322)

### [eclair](https://github.com/ACINQ/eclair/)
- [Attributable failures](https://github.com/ACINQ/eclair/pull/3065)
- [Refactor some closing helper functions](https://github.com/ACINQ/eclair/pull/3089)
- [Add low-level taproot helpers](https://github.com/ACINQ/eclair/pull/3086)
- [Stricter batching of commit_sig messages on the wire](https://github.com/ACINQ/eclair/pull/3083)
- [Cleaner handling of HTLC settlement during force-close](https://github.com/ACINQ/eclair/pull/3090)
- [Watch spent outputs before watching for confirmation](https://github.com/ACINQ/eclair/pull/3092)
- [Rework closing channel balance computation](https://github.com/ACINQ/eclair/pull/3096)
- [Parse offers and pay offers with currency](https://github.com/ACINQ/eclair/pull/3101)
- [Add attribution data to UpdateFulfillHtlc](https://github.com/ACINQ/eclair/pull/3100)
- [Remove non-final transactions from XxxCommitPublished](https://github.com/ACINQ/eclair/pull/3097)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Pass supported_protocols to LSPS0 (fix ListProtocols support)](https://github.com/lightningdevkit/rust-lightning/pull/3785)
- [Read ChannelManager even if we have no-peer post-update actions](https://github.com/lightningdevkit/rust-lightning/pull/3790)
- [Introduce interactive signing state flags for funded states.](https://github.com/lightningdevkit/rust-lightning/pull/3637)
- [Do not dip into the funder's reserve to cover the two anchors](https://github.com/lightningdevkit/rust-lightning/pull/3796)
- [LSPS2: Fail (or abandon) intercepted HTLCs if LSP channel open fails](https://github.com/lightningdevkit/rust-lightning/pull/3712)
- [Introduce Flow utilities and OffersMessageFlow implementation](https://github.com/lightningdevkit/rust-lightning/pull/3639)
- [LSPS2: Add error handling events for failed client requests](https://github.com/lightningdevkit/rust-lightning/pull/3804)
- [Allow setting a payer_note on pay_for_offer_from_human_readable_name](https://github.com/lightningdevkit/rust-lightning/pull/3808)
- [Channel Establishment for V3 Channels](https://github.com/lightningdevkit/rust-lightning/pull/3792)
- [Implement start_batch message batching](https://github.com/lightningdevkit/rust-lightning/pull/3793)
- [Separate auxiliary HTLC data from holder commitment transaction](https://github.com/lightningdevkit/rust-lightning/pull/3774)
- [Peer Storage Feature – Part 2](https://github.com/lightningdevkit/rust-lightning/pull/3623)
- [Fix possible dust HTLC sweep tx when feerate remains unchanged during a bump](https://github.com/lightningdevkit/rust-lightning/pull/3832)
- [Add missing pending FundingScope checks](https://github.com/lightningdevkit/rust-lightning/pull/3811)

### [lnd](https://github.com/lightningnetwork/lnd)
- [[graph-work-side-branch]: side branch for graph work](https://github.com/lightningnetwork/lnd/pull/9692)
- [lnwire: add lnwire.OpaqueAddr case in WriteElement for channel back-ups](https://github.com/lightningnetwork/lnd/pull/9856)
- [feat(lncli): Add --route_hints flag to sendpayment and queryroutes](https://github.com/lightningnetwork/lnd/pull/9721)
- [graph/db: init SQLStore caches and batch schedulers](https://github.com/lightningnetwork/lnd/pull/9853)
- [sqldb+graph/db: add node related tables and implement some node CRUD](https://github.com/lightningnetwork/lnd/pull/9866)
- [sqldb: re-usable TxOptions and NoOpReset](https://github.com/lightningnetwork/lnd/pull/9873)
- [sqldb+graph/db: add channel tables and implement some channel CRUD](https://github.com/lightningnetwork/lnd/pull/9869)
- [protofsm: add ConfMapper to allow conf attribute projection for new events](https://github.com/lightningnetwork/lnd/pull/9725)
- [protofsm: add option to allow conf resp to return full block](https://github.com/lightningnetwork/lnd/pull/9726)
- [accessman: remove restrictions on protected/temporary peers](https://github.com/lightningnetwork/lnd/pull/9876)
- [Add the option on path creator to specify the incoming channel on blinded path](https://github.com/lightningnetwork/lnd/pull/9127)
- [lnrpc: add HtlcIndex to ForwardingEvents](https://github.com/lightningnetwork/lnd/pull/9813)
- [multi: explicitly define InboundFees in ChannelUpdate and ChannelEdgePolicy](https://github.com/lightningnetwork/lnd/pull/9897)
- [graph/db: only fetch required info for graph cache population](https://github.com/lightningnetwork/lnd/pull/9923)
- [lnrpc: add incoming/outgoing channel ids filter to forwarding history request](https://github.com/lightningnetwork/lnd/pull/9356)

Security
--------
- [Full-Disclosure: CVE-2025-27586 "No Santa Claus under the Lightning Sun"](https://groups.google.com/g/bitcoindev/c/-UCeC6Ulvls)
