# releasenotes
Yeahreum Release Notes
Yeahreum Core version 0.12.3.3
==========================

Release is now available from:

  <https://www.yeahreum.org/downloads/#wallets>

This is a critical bugfix release.

Please report bugs using the issue tracker at github:

  <https://github.com/yeahreum/issues>


Upgrading and downgrading
=========================

How to Upgrade
--------------

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then run the
installer (on Windows) or just copy over /Applications/Yeahreum-Qt (on Mac) or
yeahreumd/yeahreum-qt (on Linux).

Downgrade warning
-----------------

### Downgrade to a version < 0.12.2.2

Because release 0.12.2.2 included the [per-UTXO fix](release-notes/yeahreum/release-notes-0.12.2.2.md#per-utxo-fix)
which changed the structure of the internal database, you will have to reindex
the database if you decide to use any pre-0.12.2.2 version.

Wallet forward or backward compatibility was not affected.

### Downgrade to 0.12.2.2/3, 0.12.3.1/2

Downgrading to these versions does not require any additional actions, should be
fully compatible.


Notable changes
===============

Fix crash bug with duplicate inputs within a transaction
--------------------------------------------------------

There was a critical bug discovered in Bitcoin Core's codebase recently which
can cause node receiving a block to crash https://github.com/bitcoin/bitcoin/pull/14247

0.12.3.3 Change log
===================

See detailed [set of changes](https://github.com/yeahreumpay/yeahreum/compare/v0.12.3.2...yeahreumpay:v0.12.3.3).

Credits
=======

Thanks to everyone who directly contributed to this release,
as well as everyone who submitted issues and reviewed pull requests.


Older releases
==============

Yeahreum was previously known as Darkcoin.

Darkcoin tree 0.8.x was a fork of Litecoin tree 0.8, original name was XCoin
which was first released on Jan/18/2014.

Darkcoin tree 0.9.x was the open source implementation of masternodes based on
the 0.8.x tree and was first released on Mar/13/2014.

Darkcoin tree 0.10.x used to be the closed source implementation of Darksend
which was released open source on Sep/25/2014.

Yeahreum Core tree 0.11.x was a fork of Bitcoin Core tree 0.9,
Darkcoin was rebranded to Yeahreum.

Yeahreum Core tree 0.12.0.x was a fork of Bitcoin Core tree 0.10.

Yeahreum Core tree 0.12.1.x was a fork of Bitcoin Core tree 0.12.

These release are considered obsolete. Old release notes can be found here:

- [v0.12.3.2] 
not available anymore released Jul/09/2018
- [v0.12.3.1] 
not available anymore released Jul/03/2018
- [v0.12.2.3] 
not available anymorereleased Jan/12/2018
- [v0.12.2.2] 
not available anymore released Dec/17/2017
- [v0.12.2] 
not available anymore released Nov/08/2017
- [v0.12.1] 
not available anymore released Feb/06/2017
- [v0.12.0] 
not available anymore released Jun/15/2015
- [v0.11.2] 
not available anymore released Mar/04/2015
- [v0.11.1] 
not available anymore released Feb/10/2015
- [v0.11.0] 
not available anymore released Jan/15/2015
- [v0.10.x] 
not available anymore released Sep/25/2014
- [v0.9.x] 
not available anymore released Mar/13/2014

