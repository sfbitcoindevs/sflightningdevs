+++
title = "Socratic Seminar 9"
date = 2025-01-30
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/) and [Hivemind Ventures](https://hivemind.vc).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers Dec 12th to January 28th.


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)

News
----
- [Amboss announces Magma AI](https://amboss.tech/blog/magma-ai)
- [Alby Labs releases ZapPlanner](https://zapplanner.albylabs.com/)
- [Closure of "DH Node" routing node by Diamond Hands](https://diamondhandsen.substack.com/p/closure-of-the-dh-node-routing-node)
- [Lightstack: Automagic Selfcustodial Cloud Lightning Stack](https://github.com/massmux/lightstack)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Disclosure: irrevocable fees -- stealing from LN using revoked commitment transactions](https://delvingbitcoin.org/t/disclosure-irrevocable-fees-stealing-from-ln-using-revoked-commitment-transactions/1314)
- [BROKEN: Multi-Party Eltoo with bounded settlement](https://delvingbitcoin.org/t/broken-multi-party-eltoo-with-bounded-settlement/1364)

#### Miscellaneous
- [A fast, scalable protocol for resolving Lightning payments](https://github.com/JohnLaw2/ln-opr/blob/main/opr_v1.1.pdf)

Releases
--------
- [Core Lightning v24.11.1](https://github.com/ElementsProject/lightning/releases/tag/v24.11.1)
- [LDK v0.1](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.1)
- [LND v0.18.4-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.18.4-beta)

bLIPs & BOLTs
-------------
- [Add bLIP 50: LSP Spec Transport Layer (LSPS0)](https://github.com/lightning/blips/pull/52)
- [Add bLIP 51: Channel Requests (LSPS1)](https://github.com/lightning/blips/pull/53)
- [Add bLIP 52: JIT Channel Negotiation (LSPS2)](https://github.com/lightning/blips/pull/54)
- [Include BIP 353 name info in invoice_requests](https://github.com/lightning/bolts/pull/1180)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- N/A

### [eclair](https://github.com/ACINQ/eclair/)
- [Peer storage](https://github.com/ACINQ/eclair/pull/2888)
- [Delay considering a channel closed when seeing an on-chain spend](https://github.com/ACINQ/eclair/pull/2936)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Support Trampoline flag in BOLT12 invoices](https://github.com/lightningdevkit/rust-lightning/pull/3446)
- [Tweak historical scoring model PDF and default penalties](https://github.com/lightningdevkit/rust-lightning/pull/3495)
- [Add lightning-liquidity crate to the workspace](https://github.com/lightningdevkit/rust-lightning/pull/3436)
- [Authenticate blinded payment paths](https://github.com/lightningdevkit/rust-lightning/pull/3435)
- [Set holder_commitment_point to Available on upgrade](https://github.com/lightningdevkit/rust-lightning/pull/3365)
- [Batch on-chain claims more aggressively per channel](https://github.com/lightningdevkit/rust-lightning/pull/3340)

### [lnd](https://github.com/lightningnetwork/lnd)
- N/A