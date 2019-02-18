---
layout: page
title: Tools
permalink: /tools/
---
Below is a list of open-source and/or command-line applications that I have used
and recommend for "power users" of Windows or MacOS, that is: savvy
non-programmers that may never have used a [command-line interface][CLI]
or may assume that "[git][]" and "[Linux][]" are misspelled.

If you are one of the top 4% of computer users that feel limited by
the shiny facade of a consumer-oriented human-machine interface
and, like [Mr. Anderson][Neo], feel that there must be
something more, then I invite you take the red pill and step beyond
the curtain of your graphical computer desktop. The journey will be
challenging and require study and practice, but once you have
experienced reality, you won't be satisfied by pretty illusions anymore.

## MacOS is Unix

I am fortunate to use a Apple Macintosh because its “MacOS” operating
system is a descendant of "Unix". Beneath the attractive facade of
macOS, iOS and watchOS lies "Unix Darwin", a Unix-derived operating
system like Linux and Android.

Unix-derived operating systems run all of the worlds top-500
super-computers, two-thirds of the internet’s billion web-servers and
all of the worlds 2.5 billion smart-phones and tablets. In contrast,
three-quarters of desktop users, mostly home consumers and office
employees, have been captured by Microsoft Windows. (Independent
professional users tend to choose Macs, which is obvious in any coffee
shop.)

This list of Unix-compatible tools will assume that you have access to
a Macintosh or another computer with a Unix-like operating system
because only a few of these tools have been ported to the proprietary
Windows environment. Open-source tools are generally written by
programmers for programmers to use and few of the worlds 20-million
programmers use Windows.

## Windows Isn’t
If you have only a Windows PC, you still have some options:

- Some very popular tools have versions that run under Windows.
- You can run some tools under "Windows Subsystem for Linux".
- You can run a Linux *virtual machine* inside Windows.

### Windows Subsystem for Linux

The *[Windows Subsystem for Linux][WSL]* is not Linux, but an adapter
between the *POSIX* [application programming interface][API] used by
Linux applications and the *Windows API*. In short, WSL presents a
Linux-shaped interface to Linux programs that it hosts, but the
application’s requests are serviced by Windows, not Linux. WSL can run
most command-line programs and even a few graphical programs (with
some work). See [Windows Subsystem for Linux Installation Guide for
Windows 10][WSL-Install-Guide] to try this route.

*Note:* I won’t be providing button-by-button explanations of how to
use Linux or the tools in the list. I’ll introduce them and point you
in the right direction but you are expected to learn about them for
yourself. I didn't say using Linux tools would be easy, just worthwhile.

### Linux Virtual Machine

There is a way to run “real” Linux on a Windows PC: a *virtual
machine*. This is another kind of adapter, but instead of adapting the
high-level application interface, it emulates the low-level computer
hardware. This allows you to install a complete operating system and
then run applications under it. For example, a virtual machine allows
me to run Windows applications under real Microsoft Windows 10 on my
Macintosh. You will use a virtual machine to run Linux under Windows
on your PC.

To host a Linux OS within your Windows PC you need two things:

- A virtualization application.
- A image of a virtual machine with Linux already installed.

There are two good choices for virtualization software:

- [VMware Workstation Player][VMware-Player] is free for personal use.
- [Oracle VirtualBox][Oracle-VirtualBox] is itself open-source software and free.

You can get a virtual image of a Linux machine from
[OSboxes.org][OSboxes]. I suggest that you choose “Ubuntu” for an
easier transition from Windows to Linux.

[CLI]: https://en.wikipedia.org/wiki/Command-line_interface
[git]: https://en.wikipedia.org/wiki/Git
[Linux]: https://en.wikipedia.org/wiki/Linux_kernel
[Neo]: https://en.wikipedia.org/wiki/Neo_(The_Matrix)
[WSL]: https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux
[API]: https://en.wikipedia.org/wiki/Application_programming_interface
[WSL-Install-Guide]: https://docs.microsoft.com/en-us/windows/wsl/install-win10
[VMware-Player]: https://www.vmware.com/products/workstation-player.html
[Oracle-VirtualBox]: https://www.virtualbox.org
[OSboxes]: https://www.osboxes.org/guide/

## Open-Source Tools

### Oracle VirtualBox
