+++
title = "Socratic Seminar 4"
date = 2024-05-14
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/), [Hivemind Ventures](https://hivemind.vc), and [CardCoins](https://cardcoins.co).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers April 13th to May 11th.


Presentation
------------
 - [Ken Sedgwick](https://twitter.com/ksedgwic) - [VLS](https://vls.tech/) demo


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)


News
----

- [ACINQ announces that Phoenix will be removed from US app stores on May 3rd](https://twitter.com/PhoenixWallet/status/1783878658014249027)
- [Strike is exploring BOLT12 and LDK](https://github.com/LN-Zap/bolt12-playground)
- [Samourai wallet founders arrested](https://www.justice.gov/usao-sdny/pr/founders-and-ceo-cryptocurrency-mixing-service-arrested-and-charged-money-laundering)
- [Wasabi blocks US citizens and will shut down coordination services](https://blog.wasabiwallet.io/zksnacks-is-discontinuing-its-coinjoin-coordination-service-1st-of-june/)


Discussion
----------

#### Tweets & Blogs

- [Roasbeef makes a mainnet asset keysend payment w/ Taproot Asset channels](https://twitter.com/roasbeef/status/1786043468164337951)
- [1 week later, Roasbeef makes a mainnet multi-hop asset payment w/ Taproot Asset channels](https://twitter.com/roasbeef/status/1788624974728790471)

#### [Delving Bitcoin](https://delvingbitcoin.org/)

N/A


Miscellaneous
-------------

- [Two WIP Ark implementations are now public](https://github.com/ark-network)
 - [clArk is covenant-less and relies on pre-signed tx](https://github.com/ark-network/clArk)
 - [ark relies on covenants and is currently using Liquid](https://github.com/ark-network/ark)
 - [Ark vs clArk explainer](https://arkdev.info/docs/learn/clark)


Releases
--------

- [LDK v0.0.123](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.123)
- [LND v0.17.5-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.17.5-beta)
- [LND v0.18.0-beta Release Candidates](https://github.com/lightningnetwork/lnd/discussions/8709)


Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Fetch block from a peer if we don't have it](https://github.com/ElementsProject/lightning/pull/7240)

### [eclair](https://github.com/ACINQ/eclair/)
- [Implicit node id in offers with blinded paths](https://github.com/ACINQ/eclair/pull/2852)
- [Update Bitcoin Core to v26.1](https://github.com/ACINQ/eclair/pull/2851)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [ChannelManager documentation refresh](https://github.com/lightningdevkit/rust-lightning/pull/2704)
- [Add fuzzing coverage for BOLT11 invoice deserialization](https://github.com/lightningdevkit/rust-lightning/pull/3054)
- [Include excess counterparty commitment transaction fees in dust exposure](https://github.com/lightningdevkit/rust-lightning/pull/3045)
- LDK [#3017](https://github.com/lightningdevkit/rust-lightning/pull/3017) and [#3018](https://github.com/lightningdevkit/rust-lightning/pull/3018) update BOLT12 structs to support last-minute changes to the spec

### [lnd](https://github.com/lightningnetwork/lnd)
- LND [#8147](https://github.com/lightningnetwork/lnd/pull/8147), [#8422](https://github.com/lightningnetwork/lnd/pull/8422), [#8423](https://github.com/lightningnetwork/lnd/pull/8423), [#8148](https://github.com/lightningnetwork/lnd/pull/8148), [#8667](https://github.com/lightningnetwork/lnd/pull/8667), and [#8674](https://github.com/lightningnetwork/lnd/pull/8674) replace LND’s old sweeper with a new implementation
- [lnrpc: rejects positive inbound fees by default](https://github.com/lightningnetwork/lnd/pull/8627)
- [Blinded Route Error Handling](https://github.com/lightningnetwork/lnd/pull/8485)
