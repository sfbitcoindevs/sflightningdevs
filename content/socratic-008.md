+++
title = "Socratic Seminar 8"
date = 2024-10-17
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/) and [Hivemind Ventures](https://hivemind.vc).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers August 23rd to October 14th.


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)

News
----
- [Strike adds BOLT12 support](https://strike.me/blog/bolt12-offers/)
- [Bisq adds Lightning support](https://github.com/bisq-network/bisq2/releases/tag/v2.1.0)
- [10101 is shutting down](https://10101.finance/blog/10101-is-shutting-down/)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Hybrid jamming mitigation: results and updates](https://delvingbitcoin.org/t/hybrid-jamming-mitigation-results-and-updates/1147)
- [SuperScalar: laddered timeout-tree structured Decker-Wattenhofer factories](https://delvingbitcoin.org/t/superscalar-laddered-timeout-tree-structured-decker-wattenhofer-factories/1143)
- [Privately sending payments while offline with BOLT12](https://delvingbitcoin.org/t/privately-sending-payments-while-offline-with-bolt12/1134)
- [Lightning cheques](https://delvingbitcoin.org/t/lightning-cheques/11620)
- [Expanding on BOLT12](https://delvingbitcoin.org/t/expanding-on-bolt12/1167)

#### Miscellaneous
- [Multi-party submarine swaps](https://conduition.io/scriptless/multi-party-submarine-swaps/)
- [Ark 0.3.0](https://arkdev.info/blog/ark-release-v0.3/)

Releases
--------
- [Core Lightning 24.08](https://github.com/ElementsProject/lightning/releases/tag/v24.08) & [Core Lightning 24.08.1](https://github.com/ElementsProject/lightning/releases/tag/v24.08.1)
 - [LDK 0.0.124](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.124)
 - [LND 0.18.3beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.18.3-beta) ([Release notes](https://github.com/lightningnetwork/lnd/blob/0-18-3-branch/docs/release-notes/release-notes-0.18.3.md))
 - [Phoenix mobile 2.4.0 & phoenixd 0.4.0](https://x.com/PhoenixWallet/status/1844377194489053555)
    - Increased BOLT12 invoice expiry to 24 hours
 - [Zeus 0.9.0](https://blog.zeusln.com/new-release-zeus-v0-9-0/)

bLIPs & BOLTs
-------------
- [BOLT12 spec merged: ready for tattoos](https://github.com/lightning/bolts/pull/798)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [hsmtool: provide nodeid from hsm secret](https://github.com/ElementsProject/lightning/pull/7644)
- [pay: Remember and update channel_hints across payments](https://github.com/ElementsProject/lightning/pull/7494)
- [Add getemergencyrecoverdata RPC Command to Fetch Data from emergency.recover File](https://github.com/ElementsProject/lightning/pull/7539)

### [eclair](https://github.com/ACINQ/eclair/)
- [Implement on-the-fly funding based on splicing and liquidity ads](https://github.com/ACINQ/eclair/pull/2861)
   - [bLIP 36: on-the-fly channel funding](https://github.com/lightning/blips/pull/36)
- [Add support for `funding_fee_credit`](https://github.com/ACINQ/eclair/pull/2875)
   - [bLIP 41: Channel funding fee credit](https://github.com/lightning/blips/blob/043b698471c4cc0f2d0e4cb6856f132690e377f9/blip-0041.md)
- [Wake up wallet nodes before relaying messages or payments](https://github.com/ACINQ/eclair/pull/2865)
- [Extensible liquidity ads](https://github.com/ACINQ/eclair/pull/2848)
- [Add `recommended_feerates` optional message](https://github.com/ACINQ/eclair/pull/2860)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Add the core functionality required to resolve Human Readable Names](https://github.com/lightningdevkit/rust-lightning/pull/3179)
   - [bLIP 32: Onion Message DNS Resolution](https://github.com/lightning/blips/blob/master/blip-0032.md)
- [Support paying static invoices](https://github.com/lightningdevkit/rust-lightning/pull/3140) per [BOLTs #1149](https://github.com/lightning/bolts/pull/1149)
- [Split up `ConfirmationTarget` even more](https://github.com/lightningdevkit/rust-lightning/pull/3268)
- [Introduce Reply Paths for BOLT12 Invoice in Offers Flow](https://github.com/lightningdevkit/rust-lightning/pull/3163)
- [Introduce Retry InvoiceRequest Flow](https://github.com/lightningdevkit/rust-lightning/pull/3010)

### [lnd](https://github.com/lightningnetwork/lnd)
- [[1/7] lnwire: add new Gossip 1.75 messages](https://github.com/lightningnetwork/lnd/pull/8044)
   - [Optech explainer: Updated channel announcements](https://bitcoinops.org/en/newsletters/2023/07/26/#updated-channel-announcements)
- [[custom channels 5/5]: merge custom channel staging branch into master](https://github.com/lightningnetwork/lnd/pull/8960)
- [discovery: implement banning for invalid channel anns](https://github.com/lightningnetwork/lnd/pull/9009)