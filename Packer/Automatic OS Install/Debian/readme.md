# chapter: Appendix B. Automating the installation using preseeding
https://www.debian.org/releases/stretch/amd64/apb.html.en

https://hands.com/d-i/

https://www.debian.org/releases/stretch/amd64/apbs04.html.en

# get preseed settings from Manual install
https://www.debian.org/releases/stretch/amd64/apbs03.html.en
>An alternative method is to do a manual installation and then, after rebooting, use the debconf-get-selections from the debconf-utils package to dump both the debconf database and the installer's cdebconf database to a single file:
>
>$ echo "#_preseed_V1" > file
>$ debconf-get-selections --installer >> file
>$ debconf-get-selections >> file
>However, a file generated in this manner will have some items that should not be preseeded

# install Additional Packages
[B.4.10. Package selection](https://www.debian.org/releases/stretch/amd64/apbs04.html.en#preseed-pkgsel)
>If you want to install some individual packages in addition to packages installed by tasks, you can use the parameter pkgsel/include. The value of this parameter can be a list of packages separated by either commas or spaces
