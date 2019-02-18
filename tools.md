---
layout: page
title: Tools
permalink: /tools/
---

Below is a list of open-source and/or command-line applications that I
have found useful and recommend for computer "power users",
that is: savvy non-programmers that may never have used a
[command-line interface][CLI] or may assume that "[git][]" and
"[Linux][]" are misspelled.

If you are one of the top 4% of computer users that feel limited by
the shiny facade of a consumer-oriented human-machine interface and,
like [Mr. Anderson][Neo], feel that there must be something more, then
I invite you take the red pill and pass through the curtain of your
graphical computer desktop. The journey will be challenging and
require study and practice, but once you have experienced reality, you
won't be satisfied by pretty illusions anymore.

## MacOS is Unix

I am fortunate to use a Apple Macintosh because its “MacOS” operating
system is a descendant of "Unix“. Beneath the attractive facade of
macOS, iOS and watchOS lies "Unix Darwin", a Unix-derived operating
system like Linux and Android.

Unix-derived operating systems run every one of the worlds top-500
super-computers, two-thirds of the internet’s billion web-servers and
all of the worlds 2.5 billion smart-phones and tablets. In contrast,
three-quarters of desktop users, mostly home consumers that bought a
cheap PC or office employees using what their company provided, have
been captured by Microsoft Windows. (Given a choice, professional
computer users tend to choose Macs, as is obvious in any coffee shop.)

This list of Unix-compatible tools will assume that you have access to
a Macintosh or another computer with a Unix-like operating system
because only a few of these tools have been ported to the proprietary
Windows environment. Open-source tools are generally written by
programmers for programmers to use and few of the worlds 20-million
programmers use Windows themselves.

## Windows Isn’t
However, if all you have is a Windows PC, you still have some options:

- Some very popular tools have versions that run under Windows.
- You can run some tools under "Windows Subsystem for Linux".
- You can run a Linux *virtual machine* inside Windows.

### Windows Subsystem for Linux

The *[Windows Subsystem for Linux][WSL]* is not Linux, but an adapter
between the *POSIX* [application programming interface][API] used by
Unix/Linux applications and the *Windows API*. In short, WSL fakes a
Linux-shaped interface for Linux programs that it hosts, but the
application’s requests are serviced by Windows. WSL can run most
command-line programs and even a few graphical programs. See [Windows
Subsystem for Linux Installation Guide][WSLG] to try this route.

*Note:* I won’t be providing a button-by-button explanation of how to
use Linux or the tools in the list. I’ll introduce them but you are
expected to learn about them for yourself. If you’re not motivated to
learn, stop reading this and go watch NetFlix. I didn't say learning
about these tools would be easy, just worthwhile.

### Linux Virtual Machine

There is a way to run “real” Linux on a Windows PC: a *virtual
machine*. This is another kind of adapter, but instead of adapting the
high-level application interface, it emulates the low-level computer
hardware. This allows you to install a complete operating system and
then run applications under it. For example, a virtual machine allows
me to run real Microsoft Windows 10 on my Macintosh. You will use
a virtual machine to run real Linux on your Windows PC.

To host a Linux OS within your Windows PC you need two things:

- A virtualization application.
- A image of a virtual machine (with Linux already installed).

There are two good choices for virtualization software:

- [VMware Workstation Player][VM] is free for personal use.
- [Oracle VirtualBox][VB] is itself open-source software and free.

You can get a virtual image of a Linux machine from
[OSboxes.org][OSB]. I suggest that you choose “Ubuntu” for an
easier transition from Windows to Linux.

## The Terminal and the Shell

Terminal, bash, command-line editing.

## Application Packages

Package Managers: Mac homebrew, Ubuntu apt, python pip, ruby gem, emacs package.

## CLI Tools

## GUI Tools

[CLI]: https://en.wikipedia.org/wiki/Command-line_interface
[git]: https://en.wikipedia.org/wiki/Git
[Linux]: https://en.wikipedia.org/wiki/Linux_kernel
[Neo]: https://en.wikipedia.org/wiki/Neo_(The_Matrix)
[WSL]: https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux
[API]: https://en.wikipedia.org/wiki/Application_programming_interface
[WSLG]: https://docs.microsoft.com/en-us/windows/wsl/install-win10
[VM]: https://www.vmware.com/products/workstation-player.html
[VB]: https://www.virtualbox.org
[OSB]: https://www.osboxes.org/guide/
