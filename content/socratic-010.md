+++
title = "Socratic Seminar 10"
date = 2025-03-13
+++

Housekeeping
------------

- This meetup is generously sponsored by [Presidio Bitcoin](https://presidiobitcoin.org)!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers January 29th to March 13th.

Chain Weather Report
--------------------

- [Mempool.space Lightning Dashboard](https://mempool.space/lightning)
- [Clark Moody Dashboard](https://bitcoin.clarkmoody.com/dashboard/)

Fun & Punchy Intro
------------------

- [Super Mario Sats game demo by D++](http://dplus.plus/pow?page=mario)
- Satoshi's 50th birthday party at Presidio Bitcoin 6:00 pm on April 5th

News
----
- [USDT Is Coming to Bitcoin and Lightning](https://tether.io/news/tether-brings-usdt-to-bitcoins-lightning-network-ushering-in-a-new-era-of-unstoppable-technology/)
- [Pathfinding With LDK](https://lightningdevkit.org/blog/ldk-pathfinding/)
- [Custodial Solutions Are Not Solutions](https://spiralbtc.substack.com/p/custodial-solutions-are-not-solutions)
- [How MuSig2 Is Powering Lightning Liquidity with Loop](https://lightning.engineering/posts/2025-02-13-loop-musig2)
- [PSA: You can now recover sats you might have lost in channels with LNBIG in 2018-2021](https://x.com/guggero/status/1888887824105046230)
- [Fedimint Lightning Gateway uses LDK Node to simplify deployment and liquidity management](https://lightningdevkit.org/blog/fedimint-lightning-gateway-uses-ldk-node-to-simplify-deployment-and-liquidity-management)
- [How we built our Sparknodes using LDK](https://lightningdevkit.org/blog/how-we-built-our-sparknodes-using-ldk)
- [Bitcoin Payments: From Digital Gold to Everyday Currency](https://breez.technology/report)
- [What’s Driving Bitcoin Adoption in 2025?](https://blog.river.com/bitcoin-adoption-2025)
- [LND's Deadline-Aware Budget Sweeper](https://morehouse.github.io/lightning/lnd-deadline-aware-budget-sweeper)

Presentation
------------
- [Vikash Singh on machine learning + Lightning](https://arxiv.org/abs/2410.01771)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Which Ephemeral Anchor Script Should Lightning Use?](https://delvingbitcoin.org/t/which-ephemeral-anchor-script-should-lightning-use/1412)
- [Zk-Gossip for Lightning Channel Announcements](https://delvingbitcoin.org/t/zk-gossip-for-lightning-channel-announcements/1407)
- [Zero-fee commitments for mobile wallets](https://delvingbitcoin.org/t/zero-fee-commitments-for-mobile-wallets/1453)
- [Highly Available Lightning Channels Revisited – ROUTE OR OUT](https://delvingbitcoin.org/t/highly-available-lightning-channels-revisited-route-or-out/1438)
- [Hybrid Jamming Mitigation: Results and Updates](https://delvingbitcoin.org/t/hybrid-jamming-mitigation-results-and-updates/1147/7)
- [An Exposition of Pathfinding Strategies Within Lightning Network Clients](https://delvingbitcoin.org/t/an-exposition-of-pathfinding-strategies-within-lightning-network-clients/1500)

#### [Bitcoin Optech Podcast](https://bitcoinops.org/en/podcast/)
- N/A

#### Miscellaneous
- N/A

Releases
--------
- [Core Lightning v25.02](https://github.com/ElementsProject/lightning/releases/tag/v25.02)
- [LDK v0.1.1](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.1.1)
- [LND v0.18.5-beta](https://github.com/lightningnetwork/lnd/blob/0-18-5-branch/docs/release-notes/release-notes-0.18.5.md)
- [Phoenix v2.5.0](https://github.com/ACINQ/phoenix/releases/tag/android-v2.5.0)
- [VLS v0.13](https://vls.tech/posts/v0.13/)

bLIPs & BOLTs
-------------
- [Option Simple Close](https://github.com/lightning/bolts/pull/1205)
- [Peer storage protocol spec merged](https://github.com/lightning/bolts/pull/1110)
- [Attributable failures (feature 36/37)](https://github.com/lightning/bolts/pull/1044)
- [Zero-fee commitments using v3 transactions (feature 40/41)](https://github.com/lightning/bolts/pull/1228)
- [Lightning Specification Meeting 2025/02/10](https://github.com/lightning/bolts/issues/1224)
- [Lightning Specification Meeting 2025/02/24](https://github.com/lightning/bolts/issues/1229)
- [Lightning Specification Meeting 2025/03/10](https://github.com/lightning/bolts/issues/1234)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [renepay: Support for BOLT12](https://github.com/ElementsProject/lightning/pull/7985)
- [Add support for BIP353 human readable names & more](https://github.com/ElementsProject/lightning/pull/7887)
- [xpay: don't MPP if we're told not to](https://github.com/ElementsProject/lightning/pull/8059)

### [eclair](https://github.com/ACINQ/eclair/)
- [Only Sync With Top Peers](https://github.com/ACINQ/eclair/pull/2983)
- [Send channel_announcement for splice transactions on public channels](https://github.com/ACINQ/eclair/pull/2968)
- [Add router support for batched splices](https://github.com/ACINQ/eclair/pull/2989)
- [Add liquidity griefing protection for liquidity ads](https://github.com/ACINQ/eclair/pull/2982)
- [Allow recipient to pay for blinded route fees](https://github.com/ACINQ/eclair/pull/2993)
- [Add scripts for taproot channels](https://github.com/ACINQ/eclair/pull/3016)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Fail Htlc Backwards Before Upstream Claims On-Chain](https://github.com/lightningdevkit/rust-lightning/pull/3556)
- [Implement Quiescence Protocol](https://github.com/lightningdevkit/rust-lightning/pull/3588)
- [Support receiving async payments](https://github.com/lightningdevkit/rust-lightning/pull/3440)
- [PeerStorage: Add feature and store peer storage in ChannelManager](https://github.com/lightningdevkit/rust-lightning/pull/3575)
- [Merge probabilistic scores from external source](https://github.com/lightningdevkit/rust-lightning/pull/3562)
- [Introduce RouteParametersConfig](https://github.com/lightningdevkit/rust-lightning/pull/3342)

### [lnd](https://github.com/lightningnetwork/lnd)
- [lnrpc+docs: deprecate warning SendToRoute, SendToRouteSync, SendPayment, and SendPaymentSync in Release 0.19](https://github.com/lightningnetwork/lnd/pull/9456)
- [Make BumpFee RPC user inputs more stricter](https://github.com/lightningnetwork/lnd/pull/9470)
- [Allow coop closing a channel with HTLCs on it via lncli](https://github.com/lightningnetwork/lnd/pull/9491)

Security
--------------
- [LND: Excessive Failback Exploit](https://morehouse.github.io/lightning/lnd-excessive-failback-exploit)
