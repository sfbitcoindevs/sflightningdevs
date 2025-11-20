+++
title = "Socratic Seminar 16"
date = 2025-11-20
+++

Housekeeping
------------

- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers October 16th to November 20th.

Privacy Tech That Accepts Lightning
----
- [Obscura VPN](https://obscura.net/)
- [Mullvad VPN](https://mullvad.net/en)
- [Kagi Search](https://kagi.com/)
- [Maple AI](https://trymaple.ai/)
- [Silent.link](https://silent.link/)

News
----
- [Square Launches Bitcoin Payment](https://x.com/CashApp/status/1990449886622306758)
- [Money Dev Kit Public Beta](https://x.com/nickslaney/status/1991151978953789614)
- [Lightning++ Happened!](https://btcpp.dev/conf/berlin25)
- [Amboss and Voltage Partner to Turn Bitcoin Payments Into a Source of Yield](https://bitcoinmagazine.com/business/amboss-and-voltage-partner)
- [Average Channel Size Spikes](https://x.com/Jestopher_BTC/status/1988884713528823970)
- [Lightning Network Capacity Spikes](https://amboss.space/stats?params=eyJtZXRyaWMiOiJjYXBhY2l0eSIsImNhdGVnb3J5IjoiYWxsVGltZU1ldHJpY3MifQ%3D%3D)

Delving Bitcoin
----
- [Private Key Handover](https://delvingbitcoin.org/t/private-key-handover/2098)
- [Gossip Observer: New project to monitor the Lightning P2P network](https://delvingbitcoin.org/t/gossip-observer-new-project-to-monitor-the-lightning-p2p-network/2105)

Releases
--------
- [CLN v25.09.1 Hot Wallet Guardian](https://github.com/ElementsProject/lightning/releases/tag/v25.09.1)
- [CLN v25.09.2 Hot Wallet Guardian](https://github.com/ElementsProject/lightning/releases/tag/v25.09.2)
- [Eclair v0.13.1](https://github.com/ACINQ/eclair/releases/tag/v0.13.1)
- [lnd v0.20.0-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.20.0-beta)
- [LDK 0.2 RC2 Natively Asynchronous Splicing"](https://github.com/lightningdevkit/rust-lightning/blob/v0.2.0-rc2/CHANGELOG.md)

bLIPs & BOLTs
-------------
- [Attribution data (feature 36/37)](https://github.com/lightning/bolts/pull/1044)
- [Lightning Specification Meeting 2025/10/20](https://github.com/lightning/bolts/issues/1293)
- [Lightning Specification Meeting 2025/11/17](https://github.com/lightning/bolts/issues/1296)

Noteworthy PRs
--------------
### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Fixing onion message support requirement for the first_node_id of bolt12 invoices](https://github.com/ElementsProject/lightning/pull/8682)
- [xpay phoenix detect](https://github.com/ElementsProject/lightning/pull/8537)
- [askrene: handle maxparts better.](https://github.com/ElementsProject/lightning/pull/8688)
- [Splice Spec Cleanup: Reestablish changes](https://github.com/ElementsProject/lightning/pull/8646)
- [Xpay bad nodes](https://github.com/ElementsProject/lightning/pull/8608)
- [Add Experimental no-MPP, Lsp-Trusts-Client LSPS2 Support](https://github.com/ElementsProject/lightning/pull/8569)
- [keysend: enforce BOLT11 description length limit](https://github.com/ElementsProject/lightning/pull/8535)
- [Add the ability to override an invoice amount to the htlc_accepted hook](https://github.com/ElementsProject/lightning/pull/8671)
- [Deprecate bech32 as default for `newaddr`](https://github.com/ElementsProject/lightning/pull/8656)
- [Enhance wallet backup and recovery with a mnemonic hsm_secret and standard taproot wallet derivations](https://github.com/ElementsProject/lightning/pull/8400)
- [Funding transaction withholding support](https://github.com/ElementsProject/lightning/pull/8546)
- [listnetworkevents: keep a log of all connect/disconnect/failed-connect and pings](https://github.com/ElementsProject/lightning/pull/8558)
- [xpay: wait, if final node gives us an indication we&#39;re behind on blockheight.](https://github.com/ElementsProject/lightning/pull/8645)
- [Big nodes, big loads and lots of (overdue) optimizations](https://github.com/ElementsProject/lightning/pull/8677)

### [eclair](https://github.com/ACINQ/eclair)
- [Allow high remote dust_limit_satoshis](https://github.com/ACINQ/eclair/pull/3215)
- [Use 73 bytes der-encoded signatures in weight estimation](https://github.com/ACINQ/eclair/pull/3210)
- [Allow aborting liquidity purchases after signing](https://github.com/ACINQ/eclair/pull/3206)
- [Eclair v0.13.1 release](https://github.com/ACINQ/eclair/pull/3196)
- [Remove support for non-anchor channels](https://github.com/ACINQ/eclair/pull/3173)
- [Stop sending `update_fee` for mobile wallets](https://github.com/ACINQ/eclair/pull/3186)
- [Allow aborting liquidity purchases after signing](https://github.com/ACINQ/eclair/pull/3206)
- [Allow high remote `dust_limit_satoshis`](https://github.com/ACINQ/eclair/pull/3215)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Put a 10_000vByte cap on `HolderHTLCOutput` 0FC package templates](https://github.com/lightningdevkit/rust-lightning/pull/4129)
- [Introduce ReceiveAuthKey verification for Blinded Payment Paths](https://github.com/lightningdevkit/rust-lightning/pull/4126)
- [Allow outgoing splice request while disconnected](https://github.com/lightningdevkit/rust-lightning/pull/4122)
- [Track funding tx channelmonitor](https://github.com/lightningdevkit/rust-lightning/pull/4109)
- [Delay FC for async payments](https://github.com/lightningdevkit/rust-lightning/pull/4140)
- [Add support for `Testnet4`](https://github.com/lightningdevkit/rust-lightning/pull/4148)
- [Note the mempool policy requirements of zero-fee commitment channels](https://github.com/lightningdevkit/rust-lightning/pull/4187)
- [Support async fetching of commitment point during channel reestablish](https://github.com/lightningdevkit/rust-lightning/pull/4197)
- [Allow counterparty tx_abort before handling initial commitment signed](https://github.com/lightningdevkit/rust-lightning/pull/4204)
- [Always forward gossip for all our channels to all our peers](https://github.com/lightningdevkit/rust-lightning/pull/4216)
- [Channel splicing support](https://github.com/lightningdevkit/ldk-node/pull/677)
- [Support client_trusts_lsp=true on ldk-node](https://github.com/lightningdevkit/ldk-node/pull/687)
- [Add support for configurable BIP39 mnemonic word counts](https://github.com/lightningdevkit/ldk-node/pull/699)

### [lnd](https://github.com/lightningnetwork/lnd)
- [multi: add upfront-shutdown-address to lnd.conf.](https://github.com/lightningnetwork/lnd/pull/9432)
- [[Part 2|*] Implement First Part for SQL Backend functions](https://github.com/lightningnetwork/lnd/pull/10287)
- [[Part 3|*] Implement Second Part for SQL Backend functions](https://github.com/lightningnetwork/lnd/pull/10291)
- [graph/db: freeze the SQL migration code](https://github.com/lightningnetwork/lnd/pull/10338)
- [Don't fail on invalid extra tlv data when decoding a payment](https://github.com/lightningnetwork/lnd/pull/10334)
- [lnwire: add missing Gossip 1.75 fields and message](https://github.com/lightningnetwork/lnd/pull/10232)
- [Basic structures for onion messages into LND](https://github.com/lightningnetwork/lnd/pull/9868)
- [rpcserver: resolve root cause of premature wallet rescanning](https://github.com/lightningnetwork/lnd/pull/10280)
- [discovery: fix potential infinite loop bug re context cancel error handling in gossip syncer](https://github.com/lightningnetwork/lnd/pull/10330)
