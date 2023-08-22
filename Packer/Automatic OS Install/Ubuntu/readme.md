# Ubuntu.
# Server
https://ubuntu.com/server/docs/install/autoinstall


# Desktop
## recommended: [install Desktop on server](https://ubuntuforums.org/showthread.php?t=2467953&p=14064676#post14064676)
>On Server Edition, you can go full or minimal. Minimal would be core services:
>
>Package openssh-server is a default installation application... Add package ubuntu-desktop. I install from that ISO because of that one difference. From that ISO, I can deploy any flavor or variant. And if it is going to be visualized, I can use cloud init, to help it along.

## Ubiquity
sch: https://www.google.com/search?q=ubuntu+ubiquity+preseed

## wiki:
https://wiki.ubuntu.com/UbiquityAutomation
- https://wiki.ubuntu.com/DesktopCDOptions
- https://wiki.ubuntu.com/Ubiquity

## extra packages
sch: https://www.google.com/search?q=ubuntu+ubiquity+preseed+pkgsel

## openssh-server
discuss:
- https://askubuntu.com/questions/1317770/how-to-install-openssh-server-during-the-install-process
- https://askubuntu.com/questions/935565/install-openssh-server-package-from-preseed-file

## Solution!:
- 2021 [[SOLVED] Install extra packages with preseed](https://ubuntuforums.org/showthread.php?t=2467953)
  - relation: [Thread: Recommended way to mass deploy Ubuntu desktop](https://ubuntuforums.org/showthread.php?t=2467323)
- 2019 [[SOLVED] Preseed: cannot install openssh](https://ubuntuforums.org/archive/index.php/t-2411842.html)
