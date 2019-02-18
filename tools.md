---
layout: page
title: Tools
permalink: /tools/
---
Below is a list of open-source and/or command-line applications that I have used
and recommend for "power users" of Windows or MacOS: savvy
non-programmers that may have never used a [command-line interface][CLI]
or that assume "[git][]" and "[Linux][]" are misspelled.

If you are one of the top 4% of computer users that feel limited by
the shiny facade of a consumer-oriented human-machine interface
and, like [Mr. Thomas A. Anderson][], feel that there must be
something more, then I invite you swallow the red pill and step beyond
the curtain of your graphical computer desktop. The journey will be
challenging and require study and practice, but once you have
experienced reality, you won't be satisfied by pretty illusions anymore.

## MacOS is Unix

I am fortunate to use a Apple Macintosh as my personal and work computer
because its operating system "macOS" is a descendant of "Unix". Beneath
the attractive facade of macOS (and iOS and watchOS) lies "Unix Darwin",
a Unix-derived operating system like Linux and Android.

Unix-derived operating systems run all of the worlds top-500
super-computers, two-thirds of the internet’s billion web-servers and
effectively all of the worlds 2.5 billion smart-phones and tablets. In
contrast, three-quarters of desktop computers, mostly home consumers
and office employees, are captured by Microsoft Windows. (Independent
professional computer user’s tend to choose Macs, as is obvious in any
coffee shop.)

This list of Unix-compatible tools will assume that you have access to
a Macintosh or other computer with a Unix-compatible operating system
because only a few of these tools have been ported to the proprietary
Windows environment. Open-source tools are generally written by programmers,
for programmers, and few of the worlds 20-million or so programmers
use Windows themselves. (They also write the proprietary software for the
world’s 1.5 billion Windows consumers, but that’s to pay for groceries.)

## Windows Isn’t
Still, if you have only a Windows PC, you have some options:

- Some very popular tools have versions that run under Windows.
- You can run many tools under "Windows Subsystem for Linux".
- You can run a Linux *virtual* computer inside Windows.

### Windows Subsystem for Linux

The “[Windows Subsystem for Linux][WSL]” is not Linux, but an adapter
between the “POSIX” [application programming interface][API] used by
Linux applications and the “Windows API”. In short, it presents a
Linux-shaped interface to host Linux programs, but it’s actually Windows
that services the application’s requests. WSL can run many
command-line programs and even a few graphical programs. See the Wikipedia
article for the limitations of WSL. See [Windows Subsystem for Linux
Installation Guide for Windows 10][WSL-Install-Guide].

### Linux Virtual Machine

There is a way to run “real” Linux on a Windows PC: a “virtual
machine“. This is another kind of adapter, but instead of adapting
between high-level application interfaces, it emulates the low-level
hardware of a computer so that you can install a real operating system
like Linux and then run applications under their native operating
system. (In my case, a virtual machine allows me to run Windows
applications under Microsoft Windows 10 on my Macintosh.)

To run a real Linux OS on your Windows PC you need two things:

- Some virtualization software.
- A virtual image of a Linux machine.

There are two good (and free!) choices for virtualization software:

- [VMware Workstation Player][VMware-Player] is free for personal use.
- [Oracle VirtualBox][Oracle-VirtualBox] is itself open-source software and free.

You can get a virtual image of a Linux machine from
[OSboxes.org][OSboxes]. As you’re coming from the Windows world, I
suggest that you select “Ubuntu” from the many flavors of Linux
available there for an easier transition.

[CLI]: https://en.wikipedia.org/wiki/Command-line_interface “CLI”
[git]: https://en.wikipedia.org/wiki/Git
[Linux]: https://en.wikipedia.org/wiki/Linux_kernel
[Mr. Thomas A. Anderson]: https://en.wikipedia.org/wiki/Neo_(The_Matrix) “Neo”
[WSL]: https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux “WSL”
[API]: https://en.wikipedia.org/wiki/Application_programming_interface “API”
[WSL-Install-Guide]: https://docs.microsoft.com/en-us/windows/wsl/install-win10
[VMware-Player]: https://www.vmware.com/products/workstation-player.html
[Oracle-VirtualBox]: https://www.virtualbox.org
[OSboxes]: https://www.osboxes.org/guide/
