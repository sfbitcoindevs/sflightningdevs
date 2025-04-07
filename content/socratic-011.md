+++
title = "Socratic Seminar 11"
date = 2025-04-24
+++

Housekeeping
------------

- This meetup is generously sponsored by [Spiral](https://spiral.xyz/)!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers March 14th to April 24th.

Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)

News
----
- [Announcing Versioned Storage Service (VSS)](https://lightningdevkit.org/blog/announcing-vss)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Fee-Based Spam Prevention For Lightning](https://delvingbitcoin.org/t/fee-based-spam-prevention-for-lightning/1524)

#### [Bitcoin Optech Podcast](https://bitcoinops.org/en/podcast/)

#### Miscellaneous

Releases
--------
- [Eclair v0.12.0](https://github.com/ACINQ/eclair/releases/tag/v0.12.0)
- [LDK v0.1.2 - Apr 02, 2025 - "Foolishly Edgy Cases"](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.1.2)
- [CLN v25.02.1 - Onion Packet Filler Accreditation II](https://github.com/ElementsProject/lightning/releases/tag/v25.02.1)
- [CLN v24.11.2 The lightning-dev Mailing List III](https://github.com/ElementsProject/lightning/releases/tag/v24.11.2)
- [LNBits v1.0.0 - Alan Bits](https://github.com/lnbits/lnbits/releases/tag/v1.0.0)

bLIPs & BOLTs
-------------
- [Check for preimage before failing back missing HTLCs](https://github.com/lightning/bolts/pull/1233)
- [Make payment_secret mandatory and ASSUMED](https://github.com/lightning/bolts/pull/1242)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)

### [eclair](https://github.com/ACINQ/eclair/)
- [Add path finding for blinded routes](https://github.com/ACINQ/eclair/pull/3027)
- [Add support for using last_funding_locked tlv in channel_reestablish](https://github.com/ACINQ/eclair/pull/3007)
- [Offers without extra plugin](https://github.com/ACINQ/eclair/pull/2976)
- [Improve Bolt12 offer APIs](https://github.com/ACINQ/eclair/pull/3037)
- [Remove amount-based confirmation scaling](https://github.com/ACINQ/eclair/pull/3044)
- [Support p2tr bitcoin wallet](https://github.com/ACINQ/eclair/pull/3026)
- [Relay non-blinded failure from wallet nodes](https://github.com/ACINQ/eclair/pull/3050)
- [Use package relay for anchor force-close](https://github.com/ACINQ/eclair/pull/2963)
- [Optional payment_secret in trampoline outer payload](https://github.com/ACINQ/eclair/pull/3045)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Correct and update confirmation target constant definitions](https://github.com/lightningdevkit/rust-lightning/pull/3608)
- [Support scalar tweak to rotate holder funding key during splicing](https://github.com/lightningdevkit/rust-lightning/pull/3624)
- [allow functional tests to be used externally with a dynamic signer factory](https://github.com/lightningdevkit/rust-lightning/pull/3016)
- [Log cases where an onion failure cannot be attributed or interpreted](https://github.com/lightningdevkit/rust-lightning/pull/3629)
- [Add BOLT12 support to bLIP-51 / LSPS1](https://github.com/lightningdevkit/rust-lightning/pull/3649)
- [lightning-invoice: explicitly enforce a 7089 B max length on BOLT11 invoice deser](https://github.com/lightningdevkit/rust-lightning/pull/3665)
- [Handle receiving payments via Trampoline](https://github.com/ACINQ/eclair/pull/3045)
- [Attributable failures](https://github.com/lightningdevkit/rust-lightning/pull/2256)
- [Fix long route failure attribution](https://github.com/lightningdevkit/rust-lightning/pull/3709)
- [[RFC] Implement a way to do BOLT 12 Proof of Payment](https://github.com/lightningdevkit/rust-lightning/pull/3593)

### [lnd](https://github.com/lightningnetwork/lnd)
- [macaroons: ip range constraint](https://github.com/lightningnetwork/lnd/pull/9546)
- [multi+server.go: add initial permissions for some peers](https://github.com/lightningnetwork/lnd/pull/9458)
- [multi: integrate new RBF co-op flow into the server+peer](https://github.com/lightningnetwork/lnd/pull/9575)
- [chain: add testnet4 support](https://github.com/lightningnetwork/lnd/pull/9620)
- [multi: downgrade to legacy coop close for taproot channels](https://github.com/lightningnetwork/lnd/pull/9669)

Security
--------------
