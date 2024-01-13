+++
title = "Socratic Seminar 2"
date = 2024-01-16
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/), [Hivemind Ventures](https://hivemind.vc), and [CardCoins](https://cardcoins.co).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers November 4th to January 12th.


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)


News
----

- [Wallet of Satoshi stops serving US users](https://www.nobsbitcoin.com/wallet-of-satoshi-stops-serving-us-customers/)


Mailing list & Delving Bitcoin
------------------------------

- [LN-Symmetry project recap](https://delvingbitcoin.org/t/ln-symmetry-project-recap/359)
- [Liquidity griefing in multi-party transaction protocols](https://delvingbitcoin.org/t/liquidity-griefing-in-multi-party-transaction-protocols/264)
- [LN OM-mixer services](https://delvingbitcoin.org/t/ln-om-mixer-services/228)
- [LNHANCE BIPs and implementation](https://delvingbitcoin.org/t/lnhance-bips-and-implementation/376)
- [Liquidity Ads and griefing subtleties](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-December/004227.html)
- [The remote anchor of anchor channels is redundant](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-December/004246.html)
- [Scaling Lightning Safely With Feerate-Dependent Timelocks](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-December/004254.html)


Miscellaneous
-------------

- [December 2023](https://github.com/lightning/bolts/issues/1122) & [January 2024 Lightning spec meeting notes](https://github.com/lightning/bolts/issues/1127)
- [Optech overview of LN anchors and v3 transaction relay proposal](https://bitcoinops.org/en/newsletters/2024/01/10/)
- [Rethinking Lightning](https://stacker.news/items/379225)
- [Lightning, validia chain, and validity rollup comparison](https://lightco.in/2023/12/13/lightning-validia-rollups/)
- [Mercury Layer adds blinding](https://mercurylayer.com/)


Releases
--------
- [Core Lightning v23.11](https://github.com/ElementsProject/lightning/releases/tag/v23.11)
- [LDK v0.0.119](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.119)
- [LDK Node v0.2.0](https://github.com/lightningdevkit/ldk-node/releases/tag/v0.2.0)
- [LND v0.17.3-beta.rc1](https://github.com/lightningnetwork/lnd/blob/v0.17.3-beta.rc1/docs/release-notes/release-notes-0.17.3.md)
- [Fedimint v0.2.0 released](https://github.com/fedimint/fedimint/releases/tag/v0.2.0) including [private lightning payments](https://github.com/fedimint/fedimint/pull/3816)
- [Mutiny-node v0.5.0](https://github.com/MutinyWallet/mutiny-node/releases/tag/v0.5.0) adds multi-LSP support and fedimint
- [Phoenix v2.1.0 adds inbound liquidity requests](https://github.com/ACINQ/phoenix/releases/tag/android-v2.1.0)


Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Implement `is_some` for `cln_rpc::options::Value`](https://github.com/ElementsProject/lightning/pull/6894)
- [coin_mvt: use the `lightning_hrp` for *all* coin movement currency](https://github.com/ElementsProject/lightning/pull/6888)

### [eclair](https://github.com/ACINQ/eclair/)
- [Dip into remote initiator reserve only for splices](https://github.com/ACINQ/eclair/pull/2797)
- [Add a txOut field to our InteractiveTxBuilder.Input interface](https://github.com/ACINQ/eclair/pull/2791)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Direct connect for OnionMessage sending](https://github.com/lightningdevkit/rust-lightning/pull/2723)
- [Route blinding: support forwarding as the intro node](https://github.com/lightningdevkit/rust-lightning/pull/2540)
- [Support receiving to multi-hop blinded paths](https://github.com/lightningdevkit/rust-lightning/pull/2688)
- [Refactor commitment broadcast to always go through OnchainTxHandler](https://github.com/lightningdevkit/rust-lightning/pull/2703)
- [Provide inbound HTLC preimages to the EcdsaChannelSigner](https://github.com/lightningdevkit/rust-lightning/pull/2753)

### [lnd](https://github.com/lightningnetwork/lnd)
- [tlv: add new RecordT[T] utility type](https://github.com/lightningnetwork/lnd/pull/8121)
- [neutrino remove sweeptx](https://github.com/lightningnetwork/lnd/pull/7800)
- [multi: query chan update timestamps](https://github.com/lightningnetwork/lnd/pull/8030)
- [rpc: add gettx command to walletrpc](https://github.com/lightningnetwork/lnd/pull/7654)
- [routing: launch fetchFundingTx in goroutine so router can exit](https://github.com/lightningnetwork/lnd/pull/8151)
