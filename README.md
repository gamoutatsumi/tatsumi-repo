# tatsumi-repo

[![build-pkgs](https://github.com/gamoutatsumi/tatsumi-repo/actions/workflows/build-pkgs.yml/badge.svg)](https://github.com/gamoutatsumi/tatsumi-repo/actions/workflows/build-pkgs.yml)
[![update-db](https://github.com/gamoutatsumi/tatsumi-repo/actions/workflows/update-db.yml/badge.svg)](https://github.com/gamoutatsumi/tatsumi-repo/actions/workflows/update-db.yml)

`/etc/pacman.conf`

```conf
[tatsumi-repo]
SigLevel = Never
Server = https://github.com/gamoutatsumi/tatsumi-repo/releases/download/x86_64
Server = https://hub.fastgit.org/gamoutatsumi/tatsumi-repo/releases/download/x86_64
```

```sh
sudo pacman -Syy
```
