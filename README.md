pinsh
====

Easy to use pinentry wrapper written in /bin/sh. Basically, `pinsh` is an isolated copy of [kwalletcli-getpin](https://www.mirbsd.org/kwalletcli.htm "kwalletcli-getpin") with no KDE dependencies, insecure code removed, and converted from MirBSD's mksh to far, far more portable /bin/sh.


### Tested and Used on:


  - [OpenBSD 5.5 -stable](http://www.openbsd.org/ "OpenBSD 5.5 -stable")
  - [OpenBSD 5.6 -stable](http://www.openbsd.org/ "OpenBSD 5.6 -stable")
  - [OpenBSD 5.6 -current](http://www.openbsd.org/ "OpenBSD 5.6 -current")


### Changes Made to kwalletcli-gitpin


  - Converted to /bin/sh from MirBSD's mksh
  - Ripped out GUI message text UTF-8 conversion, removed: toutf8()
  - Ripped out unused function: tolat1()
  - Dont save password to var
  - Dont silently fall back to insecure method of getting password
  - Set better default GUI strings


