archtap
=======

ArchLinux Systemtap Build tool with auto Kernel compilation

* You want to use Archlinux with newest kernel version ever.
* You want to use SystemTap to do profiling on this kernel with full function.
* You want to minimized the effort on keeping it new and ready.

archtap is just a small script for this job.

What you should do to make it happen?

* You may mask linux linux-headers linux-docs in /etc/pacman.conf to avoid unnecessary update.
* refresh pacman database as you always do.
* run archtap if you want some fresh kernel.


What archtap does?

* It checks the if a newer kernel version has been available in you pacman database.
* It ask you y or n and build the new kernel with debuginfo.
* It then install it.

Painless archlinux & systemtap.
