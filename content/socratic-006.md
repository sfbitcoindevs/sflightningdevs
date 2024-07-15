+++
title = "Socratic Seminar 6"
date = 2024-07-15
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/) and [Hivemind Ventures](https://hivemind.vc).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers April 13th to May 11th.


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)


News
----
- [Phoenix Android/iOS/Server now supports BOLT12](https://x.com/PhoenixWallet/status/1808547081214439494)


Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [bLIP: BOLT 11 Invoice Blinded Path Tagged Field](https://delvingbitcoin.org/t/blip-bolt-11-invoice-blinded-path-tagged-field/991)
- [Estimating Likelihood for Lightning Payments to be (in)feasible](https://delvingbitcoin.org/t/estimating-likelihood-for-lightning-payments-to-be-in-feasible/973)


Miscellaneous
-------------
- [Matt Morehouse on Fuzz Testing the Lightning Network](https://brink.dev/blog/2024/06/25/eng-call-fuzz-testing-lightning/)

Releases
--------
- [lnd v0.18.2-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.18.2-beta)


Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [ Part 2: connectd onionmessage improvements](https://github.com/ElementsProject/lightning/pull/7455)

### [eclair](https://github.com/ACINQ/eclair/)
- [Monitor onion messages](https://github.com/ACINQ/eclair/pull/2877)
- [Reject unspendable inputs in interactive-tx](https://github.com/ACINQ/eclair/pull/2870)
- [Activate route blinding and quiescence features](https://github.com/ACINQ/eclair/pull/2878)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Introduce MessageContext and use it to allow abandon failed payments](https://github.com/lightningdevkit/rust-lightning/pull/3085)
- [Interactive TX negotiation tracks shared outputs](https://github.com/lightningdevkit/rust-lightning/pull/2989)
- [Set max path length when paying BOLT 12 invoices.](https://github.com/lightningdevkit/rust-lightning/pull/3156)
- [Blinded paths with unannounced introduction nodes](https://github.com/lightningdevkit/rust-lightning/pull/3132)

### [lnd](https://github.com/lightningnetwork/lnd)
- [1/4 Route Blinding Receives: Groundwork](https://github.com/lightningnetwork/lnd/pull/8752)
- [routing: cancelable payment loop](https://github.com/lightningnetwork/lnd/pull/8734)
- [multi: hook up breach arb with new aux sweeper sub-system](https://github.com/lightningnetwork/lnd/pull/8861)
