+++
title = "Socratic Seminar 3"
date = 2024-04-16
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/), [Hivemind Ventures](https://hivemind.vc), and [CardCoins](https://cardcoins.co).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers January 13th to April 12th.


Presentation
------------
 - [Steve Lee](https://twitter.com/moneyball) - BOLT12 makes Bitcoin digital cash


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)


News
----

- [Coinbase selects Lightspark for Lightning](https://www.lightspark.com/news/coinbase-selects-lightspark)
- [Braiins releases beta Lightning payouts](https://twitter.com/BraiinsMining/status/1760319741560856983)


Delving Bitcoin
---------------

- [`sighash_outputdeltabounds`](https://delvingbitcoin.org/t/sighash-outputdeltabounds/504)
- [Payjoin-in-Potentiam: Externally fund an LSP channel open with one transaction](https://delvingbitcoin.org/t/payjoin-in-potentiam-externally-fund-an-lsp-channel-open-with-one-transaction/749)
- [Ecash and lightning via ZKCP](https://delvingbitcoin.org/t/ecash-and-lightning-via-zkcp/586)
- [Liquidity provider utxo management](https://delvingbitcoin.org/t/liquidity-provider-utxo-management/600)
- [DSL for experimenting with contracts](https://delvingbitcoin.org/t/dsl-for-experimenting-with-contracts/748)


Miscellaneous
-------------

- [Hedgehog: a protocol for improved layer two bitcoin payments](https://github.com/supertestnet/hedgehog)


Releases
--------

- [Core Lightning v24.02](https://github.com/ElementsProject/lightning/releases/tag/v24.02)
- [Eclair v0.10.0](https://github.com/ACINQ/eclair/blob/master/docs/release-notes/eclair-v0.10.0.md)
- [LDK v0.0.120](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.120)
- [LND v0.17.4-beta](https://github.com/lightningnetwork/lnd/blob/v0.17.4-beta/docs/release-notes/release-notes-0.17.4.md)
- [VLS v0.11.0](https://gitlab.com/lightning-signer/validating-lightning-signer/-/releases/v0.11.0)


Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Anchor-style channels become the default on Bitcoin](https://github.com/ElementsProject/lightning/pull/6785)
- [Removal of EOL deprecations for 23.05](https://github.com/ElementsProject/lightning/pull/7094)

### [eclair](https://github.com/ACINQ/eclair/)
- [Add configurable threshold on maximum anchor fee](https://github.com/ACINQ/eclair/pull/2816)
- [Abandon transactions whose ancestors have been double spent](https://github.com/ACINQ/eclair/pull/2818)
- [Allow plugins to set a dual funding contribution](https://github.com/ACINQ/eclair/pull/2829)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Interactive transaction construction](https://github.com/lightningdevkit/rust-lightning/pull/2419)
- [Include pending HTLC's in ChannelDetails](https://github.com/lightningdevkit/rust-lightning/pull/2442)
- [Serialize Trampoline payloads in outbound onions](https://github.com/lightningdevkit/rust-lightning/pull/2756)
- [Preliminary refactoring & structure for dual-funded channels](https://github.com/lightningdevkit/rust-lightning/pull/2770)
- [Route blinding: add min_final_cltv_delta to aggregated CLTV delta](https://github.com/lightningdevkit/rust-lightning/pull/2856)
- [Adds Into<PaymentHash> for PaymentPreimage](https://github.com/lightningdevkit/rust-lightning/pull/2916)
- [Support keysend to blinded paths](https://github.com/lightningdevkit/rust-lightning/pull/2935)

### [lnd](https://github.com/lightningnetwork/lnd)
- [Support utilizing Environment Variables in lnd.conf for rpcuser and rpcpass fields](https://github.com/lightningnetwork/lnd/pull/8310)
- [lnwire: add new closing_complete and closing_sig messages](https://github.com/lightningnetwork/lnd/pull/8338)
- [Unify coin selection, allow coin selection for PSBT with pre-defined inputs](https://github.com/lightningnetwork/lnd/pull/8378)
- [chainfee: introduce filterManager and use it for fee floor](https://github.com/lightningnetwork/lnd/pull/8418)
- [Upgrade new taproot TLVs to use tlv.OptionalRecordT](https://github.com/lightningnetwork/lnd/pull/8499)
