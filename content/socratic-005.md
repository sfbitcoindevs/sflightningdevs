+++
title = "Socratic Seminar 5"
date = 2024-06-17
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
- [Introducing Ark Labs](https://blog.arklabs.to/introducing-ark-labs-a-new-venture-to-bring-seamless-and-scalable-payments-to-bitcoin-811388c0001b)


Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)

- [Stable Channels - peer-to-peer dollar balances on Lightning](https://delvingbitcoin.org/t/stable-channels-peer-to-peer-dollar-balances-on-lightning/875)
- [Upgrading Existing Lightning Channels](https://delvingbitcoin.org/t/upgrading-existing-lightning-channels/881)

Miscellaneous
-------------
- [Christian Decker - SIGHASH_NOINPUT: A History](https://x.com/bergealex4/status/1786933357575606594)
- [Securing Lightning Channels against Rational Miners](https://eprint.iacr.org/2024/826)
- [OCEAN now supports BOLT12 payouts](https://njump.me/nevent1qqs8sz359u7ysd8hw39v99hlxl5zs7mzsrrw5rwpsctm0ufart2g0ngpp4mhxue69uhkummn9ekx7mqppamhxue69uhkummnw3ezumt0d5q3gamnwvaz7tmwdaehgu3wdau8gu3wv3jhvq3qqtvl2em0llpnnllffhat8zltugwwz97x79gfmxfz4qk52n6zpk3qn2uecg)
	- [Documentation](https://ocean.xyz/docs/lightning)
- [Ark v2](https://brqgoo.medium.com/introducing-ark-v2-2e7ab378e87b)
- [Channel Balance Interpolation in the Lightning Network via Machine Learning](https://arxiv.org/abs/2405.12087)

Releases
--------
- [LND v0.18.0-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.18.0-beta)


Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [offers: Update to include sciddir_or_pubkey, for introduction point in blinded path.](https://github.com/ElementsProject/lightning/pull/7212)
- [BOLT catchup, including dual funding!](https://github.com/ElementsProject/lightning/pull/7086)
- [Ignore --ignore-fee-rates on mutual close, don't massively overpay with LDK nodes](https://github.com/ElementsProject/lightning/pull/7252)

### [eclair](https://github.com/ACINQ/eclair/)
- [Unwrap blinded routes that start at our node](https://github.com/ACINQ/eclair/pull/2858)
- [Add payCommitTxFees flag to LocalParams](https://github.com/ACINQ/eclair/pull/2845)
- [Add EncodedNodeId for mobile wallets](https://github.com/ACINQ/eclair/pull/2867)
- [Accept onion failure without a channel_update](https://github.com/ACINQ/eclair/pull/2854)
- [Use resolved paths in BlindedHop](https://github.com/ACINQ/eclair/pull/2859)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Trampoline Onion Deserialization](https://github.com/lightningdevkit/rust-lightning/pull/3006)
- [Allow responding asynchronously to OnionMessage](https://github.com/lightningdevkit/rust-lightning/pull/2996)
- [BOLT 12 static invoice encoding and building](https://github.com/lightningdevkit/rust-lightning/pull/3082)
- [Parse v2 gossip](https://github.com/lightningdevkit/rust-lightning/pull/3098)
- [Compact blinded path creation](https://github.com/lightningdevkit/rust-lightning/pull/3011)
	- [Optional compact blinded path creation](https://github.com/lightningdevkit/rust-lightning/pull/3080)
- [Allow for user-specified error message during force close channel](https://github.com/lightningdevkit/rust-lightning/pull/2889)
- [Asynchronous Bolt12Invoice payment](https://github.com/lightningdevkit/rust-lightning/pull/3078)
- [Force-close channels if their feerate gets stale without any update ](https://github.com/lightningdevkit/rust-lightning/pull/3037)

### [lnd](https://github.com/lightningnetwork/lnd)
- [Add more RPCs for scid aliases](https://github.com/lightningnetwork/lnd/pull/8509)
- [routing: cancelable payment loop](https://github.com/lightningnetwork/lnd/pull/8734)
- [rpc+htlcswitch: add HTLC transformation capabilities to the interceptor](https://github.com/lightningnetwork/lnd/issues/8619)
- [3/5: multi: add new AuxFundingController for custom external funding flows](https://github.com/lightningnetwork/lnd/pull/8622)

### [fedimint](https://github.com/fedimint/fedimint/pull/5391)
- [split: Support split partial invoice payments](https://github.com/fedimint/fedimint/pull/5391)

### BIPs/BOLTS/BLIPs
- [BIP431: Opt In Topologically Restricted Until Confirmation Transactions For More Robust Fee-bumping](https://github.com/bitcoin/bips/pull/1541)
- [Define blip-0032, DNSSEC proof querying over onion messages](https://github.com/lightning/blips/pull/32)

