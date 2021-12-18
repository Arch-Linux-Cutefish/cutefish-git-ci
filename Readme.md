# Cutefish AUR CI
## Project based on https://github.com/kopp/aurci2

This repository uses the github action
[`kopp/build-aur-packages`](https://github.com/kopp/build-aur-packages)
to build
[AUR packages](https://aur.archlinux.org/)
and provide the built packages as
[release](https://github.com/proxer05/cutefish-git-ci/releases/download/cutefish-git-ci).


## Use this Repository with `pacman`

You can use these packages by adding the following to your `/etc/pacman.conf`:

```
[cutefish-git]
SigLevel = Optional TrustAll
Server = https://github.com/Arch-Linux-Cutefish/cutefish-git-ci/releases/download/cutefish-git-ci
```

## Credits

Thanks https://github.com/kopp for https://github.com/kopp/build-aur-packages and  https://github.com/eyenpi for AUR package.
