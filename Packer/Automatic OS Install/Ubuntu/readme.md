# Ubuntu.
Cloud-init is the New standard way to automate installs! debian's d-i preseed is now **Obsolete**

- 2021 [[SOLVED] Install extra packages with preseed](https://ubuntuforums.org/showthread.php?t=2467953)
  - relation: [Thread: Recommended way to mass deploy Ubuntu desktop](https://ubuntuforums.org/showthread.php?t=2467323)

# Server
https://ubuntu.com/server/docs/install/autoinstall

# Desktop
## recommended: [install Desktop on server](https://ubuntuforums.org/showthread.php?t=2467953&p=14064676#post14064676)
>On Server Edition, you can go full or minimal. Minimal would be core services:
>
>Package openssh-server is a default installation application... Add package ubuntu-desktop. I install from that ISO because of that one difference. From that ISO, I can deploy any flavor or variant. And if it is going to be visualized, I can use cloud init, to help it along.
>
>This is what I do with my own Support LiveCD, then install packages and configs from there. Do not think of "Server" as just being server, but as a Linux core system instance, with the potential and waiting to be "something".
>
>The only thing peculiar about it, in the transforming of Server ISO installs to Desktop, after the ubuntu-desktop package is installed... Is to tell it to use Network Manager, instead of NetPlan, as the networking managing service. So that users can manage nw connections graphically. But that is just one extra command after that package is installed.
