+++
title = "Socratic Seminar 7"
date = 2024-08-22
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/) and [Hivemind Ventures](https://hivemind.vc).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers July 17th to August 22nd.


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)


News
----
- [Taproot Assets on Lightning: The Global Financial Interoperability Layer](https://lightning.engineering/posts/2024-07-23-taproot-assets-LN/)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Bolt 12 Trusted Contacts](https://delvingbitcoin.org/t/bolt-12-trusted-contacts/1046)


Releases
--------
- [Core Lightning v24.08rc2](https://github.com/ElementsProject/lightning/blob/master/CHANGELOG.md#2408rc2---2024-08-15-to-be-added)
- [lnd v0.18.3](https://github.com/lightningnetwork/lnd/blob/master/docs/release-notes/release-notes-0.18.3.md)

bLIPs
--------
- [bLIP 4: Experimental Endorsement Signaling](https://github.com/lightning/blips/blob/master/blip-0004.md)
- [bLIP 25: Allow forwarding HTLCs with less value than the onion claims to pay](https://github.com/lightning/blips/blob/master/blip-0025.md)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Part 5: experimental range](https://github.com/ElementsProject/lightning/pull/7474)
- [Part 6: final catchup to latest BOLT spec](https://github.com/ElementsProject/lightning/pull/7476)

### [eclair](https://github.com/ACINQ/eclair/)
- [Add HTLC endorsement/confidence ](https://github.com/ACINQ/eclair/pull/2884)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Authenticate use of offer blinded paths](https://github.com/lightningdevkit/rust-lightning/pull/3139)

### [lnd](https://github.com/lightningnetwork/lnd)
- [MICRO: lnwallet: refactor channel to use new typed List #8952](https://github.com/lightningnetwork/lnd/pull/8952)
- [(2/4) Route Blinding Receives: Receive and send to a single blinded path in an invoice.](https://github.com/lightningnetwork/lnd/pull/8735)
- [routing: inbound fees support for BuildRoute](https://github.com/lightningnetwork/lnd/pull/8886)
