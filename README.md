THCoin integration/staging tree
================================

http://www.litecoin.org

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers

What is THCoin?
----------------

THCoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 3 minute block targets
 - subsidy halves in 350k blocks (~2 years)
 - ~35 million total coins

The rest is the same as Bitcoin.
 - 100 coins per block
 - 720 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Litecoin client sofware, see http://www.litecoin.org.

License
-------

THCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Litecoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion (if they haven't already) on the
[mailing list](http://sourceforge.net/mailarchive/forum.php?forum_name=bitcoin-development).

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly to indicate new official, stable release versions of Litecoin.
