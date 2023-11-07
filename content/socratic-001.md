+++
title = "Socratic Seminar 1"
date = 2023-11-07
+++

Housekeeping
------------

- This meetup is generously sponsored by [Digital Garage](https://dg717.com/), [Hivemind Ventures](https://hivemind.vc), and [CardCoins](https://cardcoins.co).
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers October 1st to November 3rd.


Presentation
------------
 - [Max Fang](https://twitter.com/MaxFangX) co-founder of [Lexe](https://lexe.app)


Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)

News
----

- [River publishes report detailing Lightning Network growth](https://river.com/learn/files/river-lightning-report-2023.pdf)
- [Blockstream officially launches Greenlight LaaS](https://blog.blockstream.com/greenlight-is-now-open-for-business/)
- [LightningTipBot lost 30% of channels in force-close incident](https://twitter.com/callebtc/status/1699073731577127264)
- [Mononaut writes a thread explaining cycling attacks](https://nitter.net/mononautical/status/1715736832950825224)
- [Doppler: a lightning domain-specific language](https://voltage.cloud/blog/bitcoin-development-platform/doppler-a-lightning-domain-specific-language/)

Miscellaneous
-------------

- [October 2023 Lightning spec meeting](https://github.com/lightning/bolts/issues/1115)
- [On solving pinning, replacement cycling and mempool issues for bitcoin second-layers](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-October/004158.html)
- [Removing channel reserve for mobile wallet users](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-October/004136.html)

Releases
--------

- [LDK 0.0.118](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.118)
- [lnd v0.17.0-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.17.0-beta)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
 - [Allow even unknown messages, by registration, and allow sending them](https://github.com/ElementsProject/lightning/pull/6689)
 - [addpsbtoutput: New onchain command for PSBT output and splice_out tests](https://github.com/ElementsProject/lightning/pull/6676)
 - [Fee hysteresis updates](https://github.com/ElementsProject/lightning/pull/6833)
 - [Fuzzing-Found BOLT11 crashes](https://github.com/ElementsProject/lightning/pull/6789)

 ### [eclair](https://github.com/ACINQ/eclair/)
 - [Ignore disabled edges for routing messages](https://github.com/ACINQ/eclair/pull/2750)
 - [Adapt max HTLC amount to balance](https://github.com/ACINQ/eclair/pull/2703)
 - [Poll bitcoind at startup instead of trying only once](https://github.com/ACINQ/eclair/pull/2739)
 - [Assume widely supported features](https://github.com/ACINQ/eclair/pull/2732)
 - [Splice with pending committed htlcs](https://github.com/ACINQ/eclair/pull/2720)
 - [Improve startup resource usage](https://github.com/ACINQ/eclair/pull/2733)
 - [Allow splicing on non dual-funded channels](https://github.com/ACINQ/eclair/pull/2727)

 ### [LDK](https://github.com/lightningdevkit/rust-lightning)
 - [Move the historical bucket tracker to 32 unequal sized buckets](https://github.com/lightningdevkit/rust-lightning/pull/2176)
 - [BOLT 12 Offers message flow](https://github.com/lightningdevkit/rust-lightning/pull/2039)
 - [Monitor updating persister](https://github.com/lightningdevkit/rust-lightning/pull/2359)
 - [Set a default max_total_routing_fee_msat of 1% + 50sats](https://github.com/lightningdevkit/rust-lightning/pull/2603)
 - [Try to overpay the recipient if we fail to find a path at all and limit overpay #2604](https://github.com/lightningdevkit/rust-lightning/pull/2604)
 - [Use correct to_remote script in counterparty commitments](https://github.com/lightningdevkit/rust-lightning/pull/2605)
 - [Allow retrieval of SpendableOutputDescriptors from relevant transactions](https://github.com/lightningdevkit/rust-lightning/pull/2609)
 - [More flexible fee rate estimates](https://github.com/lightningdevkit/rust-lightning/pull/2660)

 ### [lnd](https://github.com/lightningnetwork/lnd)
 - [multi: pong enforcement](https://github.com/lightningnetwork/lnd/pull/7828)
 - [invoices: refactor `InvoiceDB` to eliminate `ScanInvoices`](https://github.com/lightningnetwork/lnd/pull/8081)
 - [Add more information when a co-op close is failing.](https://github.com/lightningnetwork/lnd/pull/8090)
 - [input+sweep: make sure input with no fee rate is not added to cluster](https://github.com/lightningnetwork/lnd/pull/7824)
 - [sweeper: relax anchor sweeping when there's no deadline pressure](https://github.com/lightningnetwork/lnd/pull/7965)
 - [tlv: fuzz test encoding/decoding](https://github.com/lightningnetwork/lnd/pull/7889)
 - [funding: wait for coinbase maturity before sending channel_ready](https://github.com/lightningnetwork/lnd/pull/7925)
 - [peer: launch persistent peer pruning in background goroutine](https://github.com/lightningnetwork/lnd/pull/8041)
