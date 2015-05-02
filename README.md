## Debmower!

Debmower puts together live Debian or Ubuntu images meant to be
booted from CDs, USB images or VMs.

Version 0.3 fixes many long-standing issues while Version 0.4,
due for end of May 2015, aims to resolve most of the remaining issues.

It's still in early alpha, if you plan to use it, please get in touch if
you need any assistance in setting it up.

In the mean-time, we suggest that you take look at the debian-live scripts,
it may be more suited your needs. debian-live is a modern, supported way of
building debian live images.

More documentation will be on its way.

Dependencies: debootstrap syslinux squashfs-tools genisoimage
              inotify-tools unionfs-fuse xorriso
              libisofs6 => 1.3.6, isolinux => 3:6.03+dfsg-5
Recommended: smb lxc bridge-utils memtest86+
