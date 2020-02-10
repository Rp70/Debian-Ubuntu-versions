# Debian & Ubuntu versions

You can find the Debian version on which your Ubuntu version is based in the file: `/etc/debian_version`

From 10.04 up to 20.04:
```
Ubuntu            Debian  
20.04  focal      bullseye/ sid
19.10  eoan       buster  / sid   - 10
19.04  disco      buster  / sid
18.10  cosmic     buster  / sid
18.04  bionic     buster  / sid
17.10  artful     stretch / sid   - 9
17.04  zesty      stretch / sid
16.10  yakkety    stretch / sid
16.04  xenial     stretch / sid
15.10  wily       jessie  / sid   - 8
15.04  vivid      jessie  / sid
14.10  utopic     jessie  / sid
14.04  trusty     jessie  / sid
13.10  saucy      wheezy  / sid   - 7
13.04  raring     wheezy  / sid
12.10  quantal    wheezy  / sid
12.04  precise    wheezy  / sid
11.10  oneiric    wheezy  / sid
11.04  natty      squeeze / sid   - 6
10.10  maverick   squeeze / sid
10.04  lucid      squeeze / sid
```
sid is the development distribution of Debian [(sid - testing - stable)](https://www.debian.org/doc/manuals/debian-faq/ch-ftparchives#s-testing)

You can find out the contents of the file without installing an entire system by view the sources for the [package `basefiles` on Launchpad](https://code.launchpad.net/ubuntu/+source/base-files).

This content was copied from https://askubuntu.com/a/445496. I'll keep this list updated once a new version release. All PRs are welcomed.
