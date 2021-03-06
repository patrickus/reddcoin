Reddcoin Core version 2.0.1 is now available from:

  https://wallet.reddcoin.com/

This is a new minor version release of Reddcoin,
Previously, the original and sunsequent versions of Reddcoin were taken from a fork of Litecoin.
With the release of Reddcoin V2.0.0, is now based directly from a fork Bitcoin.
This allows for better source control and feature implementaion from upstream changes

Upgrading to this release is recommended.

Please report bugs using the issue tracker at github:

  https://github.com/reddcoin-project/reddcoin/issues

How to Upgrade
===============

If you are running an older version of Reddcoin, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then run the
installer (on Windows) or just copy over /Applications/Reddcoin-Qt (on Mac) or
reddcoind/reddcoin-qt (on Linux).

Start wallet

Notable changes
================

Core base code
------------------------------------

Reddcoin v2.0.0.0 was forked from Bitcoin v0.9.5

Staking and relay policy enhancements
------------------------------------

To implement BIP66, Reddcoin Core's block templates are now for version 4 blocks only.
When BIP66 concensus (Supermajority 6120/7200) is reached, only v4 blocks will be accepted by the network.
and any staking

OP_Return and data in the blockchain
------------------------------------
Reddcoin allows storing 80bytes of arbitary data in the blockchain

2.0.1 changelog
===============
fafc567 - John Nash, 2017-12-23 : Add additional dnsseed nodes
47abb78 - Henry Young, 2017-01-08 : Corrected two string literal Bitcoin references to Redecoin
f88a2e5 - Stoner19, 2017-01-05 : Update bitcoind.cpp
dbbfd6f - John Nash, 2016-11-30 : build: don't let libtool insert rpath into binaries
2ab6541 - John Nash, 2016-11-27 : build: fix newer boost build with c++11
81b7112 - John Nash, 2016-11-26 : add support for miniupnpc api version 14
e69213e - John Nash, 2016-11-25 : Clearer meaning to error messages High Fee warning and Not enough inputs
20bda36 - Erkan Yilmaz, 2016-08-18 : typo
87fa337 - John Nash, 2016-08-18 : #89 Improve layout of splash screen Update text layout and adjust background for readability
02572a6 - John Nash, 2016-08-16 : #87 Update Debian installation instructions Add details how to install URI support on Debian Add updated graphic icons
cc5cf5b - Sjolus, 2016-08-15 : Update rpcrawtransaction.cpp


Credits
--------

Thanks to everyone who contributed to coding, testing and feedback for this release, notably:

- @Deadpool
- @bmp02050
- @lionzeye
- @stoner19
- @henryyoung
- Erkan Yilmaz
- @Sjolus


As well as everyone that helped translating on [Transifex](https://www.transifex.com/reddcoin/reddcoin/).
- @Serkan34
- @Syar
- @ricklopez
- @hyoung
- @elcryptotrader
- @Maxamus
- @Erkan_Yilmaz
- @tecopos
- @xDeadp00lx
- @clickerz
- @Kasvain
- @collab
- @lionzeye
- @Ragnarice

