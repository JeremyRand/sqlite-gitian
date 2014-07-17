sqlite-gitian
=============

Deterministic builds of SQLite using Gitian

__These have not been extensively tested.__  The Linux descriptor builds a working library on my machine (tested exactly once) that libcoind successfully uses.  The Windows descriptor builds something without obvious build errors (tested exactly once).  Other than that, __no testing has been conducted.__  Feedback invited!

__Do not use these descriptors for anything other than testing unless you are willing to accept the consequences.__

Instructions on using Gitian: https://github.com/bitcoin/bitcoin/blob/master/doc/gitian-building.md

Get the dependency like this:

    wget --no-check-certificate https://www.sqlite.org/2014/sqlite-autoconf-3080500.tar.gz

Want to help?  Build them and compare hashes against mine: https://github.com/JeremyRand/sqlite-gitian/issues/1
