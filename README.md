offloading gem5
====
The benchmark supports computation offloading between client and server in dist-gem5


How to use dist-gem5
----
dist-gem5 has an [official website](https://publish.illinois.edu/icsl-pdgem5/getting-started-with-dist-gem5/). There are some tutorials and demo video to show how to use it. 

There are possibly some problems as follow when using dist-gem5.

#1. chroot#
If you want to use the command 'chroot', you have to install qemu. the installation command is as follow:
'apt-get install qemu qemu-user qemu-system qemu-user-static'
#2. An usual debug error#
If there is the error as follow in the output file testsys.terminal, you should update the file Makefile in the disk image following the URL https://www.mail-archive.com/gem5-users@gem5.org/msg14957.html However, there is a simple way that you can download the image in the latest version from http://www.gem5.org/dist/current/arm/, such as aarch-system-20180409.tar.xz.
How to install Java in Linux32 image
----

How to install Benchmark RAPID in Linux32 image
----

How to run RAPID with Linux32 image in dist-gem5
----
