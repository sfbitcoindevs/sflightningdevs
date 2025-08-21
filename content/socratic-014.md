+++
title = "Socratic Seminar 14"
date = 2025-08-21
+++

Housekeeping
------------

- This meetup is generously sponsored by [Spiral](https://spiral.xyz/)!
- Questions are encouraged, including basic ones!
- Socratic Seminars are held under the [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule): share the information you receive, but do not reveal the identity of who said it.
- For the privacy of other attendees, please refrain from taking photographs of other people without their permission.
- Socratic seminars are best when the moderator can let the conversation flow, so try to keep things concrete and focused.
- The reading list covers July 17th to August 21st.

News
----
- [Programming Lightning Workshop: Intro to Payment Channels](https://x.com/_austin_f/status/1950623228805927259)
- [Force Closures in LND](https://amboss.space/node/0391aeb8d6d54df19b56c3eec85ea5ab8aa04e6d5865af1b34fd26106ca75bf081?section=Closed+Channels)
- [US House Passes Bitcoin, Crypto Market Structure Bill The CLARITY Act](https://bitcoinmagazine.com/news/us-house-passes-bitcoin-crypto-market-structure-bill-the-clarity-act)
- [Tornado Cash Trial Concludes: Roman Storm Found Guilty on One of Three Counts](https://bitcoinmagazine.com/news/tornado-cash-trial-concludes-roman-storm-found-guilty-of-one-of-three-counts)
- [Samourai Wallet Developers Plead Guilty to Conspiring to Operate an Unlicensed Money Transmitting Business](https://bitcoinmagazine.com/news/samourai-wallet-developers-plead-guilty)
- [RGB v0.11.1 Launches, Allowing The Creation Of Digital Assets on Bitcoin Mainnet](https://bitcoinmagazine.com/news/rgb-v0-11-1-launches-allowing-the-creation-of-digital-assets-on-bitcoin-mainnet)
- [First RGB Bridge Brings USDT From Ethereum to Bitcoin via Lightning](https://bitcoinmagazine.com/news/first-rgb-bridge-brings-usdt-from-ethereum-to-bitcoin-via-lightning)
- [Square Begins Rollout of Bitcoin Payments for Sellers, Targets Full Availability by 2026](https://www.coindesk.com/tech/2025/07/23/square-begins-rollout-of-bitcoin-payments-for-sellers-targets-full-availability-by-2026)
- [Mullvad Lightning Payments](https://mullvad.net/en/blog/2025/8/5/lightning-payments)

Discussion
----------
#### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Proposal Bitcoin Deposits: A Zero UTXO Trust-Minimized Lightning Wallet](https://delvingbitcoin.org/t/proposal-bitcoin-deposits-a-zero-utxo-trust-minimized-lightning-wallet/1922)
- [RGB yellow paper: the formal specification of Bitcoin & Lightning smart contracts](https://delvingbitcoin.org/t/rgb-yellow-paper-the-formal-specification-of-bitcoin-lightning-smart-contracts/1885)

bLIPs & BOLTs
-------------
- [Add bLIP 55: Webhook Registration (LSPS5)](https://github.com/lightning/blips/pull/55)
- [Lightning Specification Meeting 2025/07/28](https://github.com/lightning/bolts/issues/1275)
- [Lightning Specification Meeting 2025/08/11](https://github.com/lightning/bolts/issues/1277)

Noteworthy PRs
--------------

### [Core Lightning](https://github.com/ElementsProject/lightning)
- [Askrene single path solver](https://github.com/ElementsProject/lightning/pull/8299)
- [Askrene: prune and cap](https://github.com/ElementsProject/lightning/pull/8332)
- [wss-proxy: replaced by a rust version](https://github.com/ElementsProject/lightning/pull/8080)
- [clnrest: add more request and response types](https://github.com/ElementsProject/lightning/pull/8383)
- [Askrene: fix constraints](https://github.com/ElementsProject/lightning/pull/8358)
- [Reckless uv installer](https://github.com/ElementsProject/lightning/pull/8430)
- [migration from poetry to uv](https://github.com/ElementsProject/lightning/pull/8249)
- [Assume option_channel_type](https://github.com/ElementsProject/lightning/pull/8389)
- [Allow routing by older scids when we splice](https://github.com/ElementsProject/lightning/pull/8387)
- [splice: Implement start_batch](https://github.com/ElementsProject/lightning/pull/8335)
- [cln-bip353: add plugin that fetches payment instructions from human readable addresses](https://github.com/ElementsProject/lightning/pull/8362)
- [Set custom tlvs to update_add_htlc via the htlc_accepted_hook](https://github.com/ElementsProject/lightning/pull/8433)
- [Xpay limit parts](https://github.com/ElementsProject/lightning/pull/8448)
- [xpay BIP353 support](https://github.com/ElementsProject/lightning/pull/8467)

### [eclair](https://github.com/ACINQ/eclair)
- [Add outgoing reputation](https://github.com/ACINQ/eclair/pull/3133)
- [Use CLTV expiry when computing reputation](https://github.com/ACINQ/eclair/pull/3134)
- [Improve taproot channels support and add tests](https://github.com/ACINQ/eclair/pull/3136)
- [Verify nonces on reconnection after we've pruned funding transactions](https://github.com/ACINQ/eclair/pull/3138)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Update fee and dust handling for zero fee channels](https://github.com/lightningdevkit/rust-lightning/pull/3884)
- [Introduce ReceiveAuthKey](https://github.com/lightningdevkit/rust-lightning/pull/3917)
- [Hold times for successful payments](https://github.com/lightningdevkit/rust-lightning/pull/3801)
- [add expiry_time to PendingOutboundPayment::StaticInvoiceReceived](https://github.com/lightningdevkit/rust-lightning/pull/3918)
- [Async background persistence](https://github.com/lightningdevkit/rust-lightning/pull/3905)
- [LSPS5 implementation](https://github.com/lightningdevkit/rust-lightning/pull/3662)
- [Enable Creation of Offers and Refunds Without Blinded Path](https://github.com/lightningdevkit/rust-lightning/pull/3246)
- [lightning-liquidity: Introduce MessageQueueNotifierGuard type](https://github.com/lightningdevkit/rust-lightning/pull/3981)
- [Splicing Tx negotiation during splicing](https://github.com/lightningdevkit/rust-lightning/pull/3736)
- [Introduce RenegotiatedFundingLocked monitor update variant](https://github.com/lightningdevkit/rust-lightning/pull/3894)
- [Let BackgroundProcessor drive HTLC forwarding](https://github.com/lightningdevkit/rust-lightning/pull/3891)
- [Ensure partial MPP claims continue to blocks channels on restart](https://github.com/lightningdevkit/rust-lightning/pull/3928)
- [Broadcast holder commitment for currently confirmed funding](https://github.com/lightningdevkit/rust-lightning/pull/3939)
- [Support splicing in ChannelContext::funding_tx_constructed](https://github.com/lightningdevkit/rust-lightning/pull/3982)
- [Detect and fail-back monitor-blocked un-forwarded HTLCs at close](https://github.com/lightningdevkit/rust-lightning/pull/3989)
- [Block RAA ChannelMonitorUpdates on PaymentClaimed events](https://github.com/lightningdevkit/rust-lightning/pull/3988)
- [Always emit bump events, even when fees are sufficient](https://github.com/lightningdevkit/rust-lightning/pull/4001)
- [Consider currently confirmed FundingScope when claiming commitments](https://github.com/lightningdevkit/rust-lightning/pull/3980)
- [Introduce FundingTransactionReadyForSignatures event](https://github.com/lightningdevkit/rust-lightning/pull/3889)
- [Detect commitment transaction confirmation in ChannelMonitor instead](https://github.com/lightningdevkit/rust-lightning/pull/4013)

### [lnd](https://github.com/lightningnetwork/lnd)
- [Add deletecanceledinvoice RPC call](https://github.com/lightningnetwork/lnd/pull/9625)
- [Increase the default outgoing bandwidth](https://github.com/lightningnetwork/lnd/pull/10096)
- [2 graph/db: batch-fetch node data](https://github.com/lightningnetwork/lnd/pull/10115)
- [3 graph/db: batch-fetch channel & policy data](https://github.com/lightningnetwork/lnd/pull/10116)
- [multi: make gossip filter sends non-blocking, only allow a single backlog catch up goroutine per peer](https://github.com/lightningnetwork/lnd/pull/10097)
- [4 sqldb+graph/db: add and use new pagination helper](https://github.com/lightningnetwork/lnd/pull/10118)
- [5 sqldb+graph/db: add and use new paginate & batch helper](https://github.com/lightningnetwork/lnd/pull/10121)
- [6 graph/db: use batch fetching to improve ForEachNode* performance](https://github.com/lightningnetwork/lnd/pull/10123)
- [contractcourt+sweep: make anchor inputs exclusive](https://github.com/lightningnetwork/lnd/pull/10117)
- [7 graph/db+autopilot: improve efficiency of autopilot methods that use the ForEachNode/ForEachChannel pattern](https://github.com/lightningnetwork/lnd/pull/10127)
- [8 graph/db: use batch loading for various graph SQL methods](https://github.com/lightningnetwork/lnd/pull/10129)
- [Add NoopAdd HTLCs](https://github.com/lightningnetwork/lnd/pull/9871)
- [graph/db+sqldb: different defaults for SQLite and Postgres query options](https://github.com/lightningnetwork/lnd/pull/10148)
- [graph/db: use batch validation to improve SQL migration performance](https://github.com/lightningnetwork/lnd/pull/10154)
- [Add missing invoice index for native sql](https://github.com/lightningnetwork/lnd/pull/10155)
- [lnd: use persisted node announcement settings across restarts](https://github.com/lightningnetwork/lnd/pull/8825)

Security
--------
- [Disclosure: LND gossip_timestamp_filter DoS](https://delvingbitcoin.org/t/disclosure-lnd-gossip-timestamp-filter-dos/1859)
