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
