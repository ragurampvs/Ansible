                LXC - Linux Container

LXC is an operating-system-level virtualization method for running multiple isolated Linux systems on a control host using a single Linux kernel. 

The Linux kernel contains cgroups for resource isolation (CPU, memory, block I/O, network, etc, ), which does not require starting any virtual machines.

Cgroups also provides namespace isolation to completely isolate application view of the operating environment, including process trees, networks, userids and mounted filesystems.

LXC is open source software and licensed under GNU LGPLv2.1+ license.

Containers actually make use of kernel features called namespaces, cgroups, and chroots, to carve off a contained area.
