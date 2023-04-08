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
Download page link for linux/Unix [Click here](https://git-scm.com/download/linux)
  
## Installing on windows
<hl>
From windows terminal(Windows powershell)

```bash
winget install --id Git.Git -e --source winget
```

Windows exe file for normal installation. Download page link for windows [Click here](https://git-scm.com/download/win)

## Installation on mac

For reference [Click here](https://git-scm.com/download/mac)

# Setting your Git username for every repository on your computer
<hl>
Open Git Bash.
Set a Git username:

```
git config --global user.name "user name"
```
Enter your name in place of user name.

Confirm that you have set the Git username correctly:
```
git config --global user.name
```
>user name
Inplace of user name you will see your name

# Setting your email address for every repository on your computer
<hl>
Open Git Bash.
Set an email address in Git. You can use your GitHub-provided noreply email address or any email address.

```
git config --global user.email "email@example.com"
```
Confirm that you have set the email address correctly in Git:

```
git config --global user.email 
```
>email@example.com

