# Linux Philosphy and Concepts
## History of Linux
Linux is an open source computer operating system, initially developed on and for Intel x86-based personal computers. It has been subsequently ported to an astoundingly long list of other hardware platforms, from tiny embedded appliances to the world's largest supercomputers.

Linus Trovald, a student in Helsinki, Finland, started writing his own kernel in 1991. He used a penguin as his mascot after an incident at the zoo (don't know how true this is)

It was relicensed in 1992 using the General Public License (GPL) (*created by Richard Stallman*) by GNU (a project of the Free Software Foundation or FSF, which promotes freely available software). 

Today, Linux powers more than half of the servers on the Internet, the majority of smartphones (via the Android system, which is built on top of Linux), more than 90 percent of the public cloud workload, and all of the world’s most powerful supercomputers.

The freedoms surrounding GPL: 
- The freedom to use the software for any purpose
- The freedom to change the software to suit your needs
- The freedom to share the software with your friends and neighbors
- The freedom to share the changes you make

## Linux Philosophy
Even though Linux borrowed heavily from UNIX, it is not UNIX.

- Files are stored in a hierarchical file system with the top of the hierarchy being **root(/)**. 
- Linux makes its components available via files or objects that look like files
- Processes, networks sockets, and devices are accessible as files and can be manipulated using the same utilities used for regular files
- Linux is a fully multitasking (has simultaneous execution of multiple threads), multiuser OS 
- Linux has built-in networking and service processes (referred to as daemons in the UNIX world)

## Linux Terminology


# Linux distribution families 
- This categorization/grouping is based on their ancestry, package management system, and design philosphy
- Terms interacted with:
    - *Upstream* refers to where the software originally comes from — the source project or parent distribution that another distro or software package is based on.
    - *Downstream* refers to projects that take software from the upstream, modify or repackage it, and redistribute it.


    Fedora → RHEL → CentOS Stream

## Debian Family (Ubuntu, Linux Mint, etc.)
It is commonly used on both servers and desktop computers. Debian is a pure open source community project (not owned by any corporation) and has a strong focus on stability.

- **Package format:** .deb
- **Package manager:** APT (Advanced Package Tool)

1. Debian – The parent project; focuses on stability and freedom.
2. Ubuntu – Most popular Debian-based distro, maintained by Canonical.
3. Linux Mint (Debian Edition) – User-friendly, desktop-focused.
4. Kali Linux – Security-focused, used for penetration testing.
5. Raspberry Pi OS – Optimized for Raspberry Pi hardware.

## Red Hat Family (CentOS, Fedora)
- **Package format:** .rpm
- **Package manager:** YUM / DNF (Yellowdog Updater, Modified / Dandified YUM)
- **Distros:** 
1. AlmaLinux/Rocky Linux
2. Red Hat Enterprise Linux (RHEL)
3. CentOS Stream
4. Fedora - serves as an upstream testing platform for RHEL
5. Oracle Linux
6. CentOS a close clone of RHEL; in fact, CentOS has been part of Red Hat since 2014.

## SUSE Family (openSUSE)
openSUSE is available to end users at no cost. It includes the YaST (Yet Another Setup Tool) application for system administration purposes.

- **Package format**: .rpm
- **Package manager**: Zypper / YaST (Yet Another Setup Tool)
- **Distros:**
1. openSUSE Leap – Stable and enterprise-aligned.
2. openSUSE Tumbleweed – Rolling release, always up to date.
3. SUSE Linux Enterprise Server (SLES) – Enterprise version of SUSE.

## Arch Family
## Slackware Family
## Gentoo Family
## Independent/Unique Family

