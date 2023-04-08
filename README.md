# Git-config

## Installing on Linux
<hl>
Debian/Ubuntu
For the latest stable version for your release of Debian/Ubuntu

```
apt-get install git
```
For Ubuntu, this PPA provides the latest stable upstream Git version

```
add-apt-repository ppa:git-core/ppa
```
```
apt update
```
```
apt install git
```
Fedora
``` 
yum install git
```
(up to Fedora 21)
``` 
dnf install git
```
(Fedora 22 and later)

Gentoo
```
emerge --ask --verbose dev-vcs/git
```
Arch Linux
```
pacman -S git
```
openSUSE
```
zypper install git
```
Mageia
```
urpmi git
```
Nix/NixOS
```
nix-env -i git
```
FreeBSD
```
pkg install git
```
Solaris 9/10/11 (OpenCSW)
```
pkgutil -i git
```
Solaris 11 Express
```
pkg install developer/versioning/git
```
OpenBSD
```
pkg_add git
```
Alpine
```
apk add git
```

## Installing on windows
<hl>
From windows terminal(Windows powershell)

```bash
winget install --id Git.Git -e --source winget
```

Windows exe file for normal installation:
[Git 2.40.0.exe](https://objects.githubusercontent.com/github-production-release-asset-2e65be/23216272/d49d1e1a-bf36-4f68-beee-a4d791b6b56c?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230408%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230408T121336Z&X-Amz-Expires=300&X-Amz-Signature=cf7298c480fa6a0c1deb3fd15883e9560410a07a94e5a7d949c95849e3ff1f2a&X-Amz-SignedHeaders=host&actor_id=83121137&key_id=0&repo_id=23216272&response-content-disposition=attachment%3B%20filename%3DGit-2.40.0-64-bit.exe&response-content-type=application%2Foctet-stream)
