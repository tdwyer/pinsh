pish
====

Easy to use pinentry wrapper written in mksh. Basically, `pish` is an isolated copy of [kwalletcli-getpin](https://www.mirbsd.org/kwalletcli.htm "kwalletcli-getpin") with no KDE dependencies ,and some insecure code removed.


### Tested and Used on:


  - [OpenBSD 5.5 -stable](http://www.openbsd.org/ "OpenBSD 5.5 -stable")


### Changes Made to kwalletcli-gitpin


  - Converted to[OpenBSD 5.5 -stable](http://www.openbsd.org/ "OpenBSD") [ksh](http://www.openbsd.org/cgi-bin/man.cgi?query=ksh&sektion=0&manpath=OpenBSD+5.5&arch=amd64&format=html "ksh")
  - Ripped out GUI message text UTF-8 conversion, removed: toutf8()
  - Ripped out unused function: tolat1()
  - Dont save password to var
  - Dont silently fall back to insecure method of getting password


