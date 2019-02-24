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
been captured by Microsoft Windows. (Given informed choice, professional
computer users tend to choose Macs, as is obvious in any coffee shop.)

This list of Unix-compatible tools will assume that you have access to
a Macintosh or another computer with a Unix-like operating system
because only a few of these tools have been ported to the proprietary
Windows environment. Open-source tools are generally written by
programmers for programmers and few of the worlds 20-million
programmers use Windows themselves.

## Windows Isn’t
However, if all you have is a Windows PC, you still have some options:

- Some very popular tools have versions that run under Windows.
- You can run some tools under _Windows Subsystem for Linux_.
- You can run a Linux _virtual machine_ inside Windows.

### Windows Subsystem for Linux

The _[Windows Subsystem for Linux][WSL]_ is not Linux, but an adapter
between the _POSIX_ [application programming interface][API] used by
Unix/Linux applications and the _Windows API_. In short, WSL fakes a
Linux-shaped interface for hosted Linux applications, but the
application’s requests are serviced by Windows. WSL can run most
command-line programs and even a few graphical programs. See [Windows
Subsystem for Linux Installation Guide][WSLG] to try this route.

_Note:_ I won’t be providing button-by-button explanations of how to
use Linux or the tools in the list. I’ll introduce them but you are
expected to learn about them for yourself. There is plenty of
information available. If you’re not motivated to learn, stop reading
this and go watch NetFlix. I didn't say learning about these tools
would be easy, just worthwhile.

### Linux Virtual Machine

There is a way to run “real” Linux on a Windows PC: a _virtual
machine_. This is another kind of adapter, but instead of adapting the
high-level application interface, it emulates the low-level computer
hardware. This allows you to install a complete operating system and
then run applications under it as if you had another PC. For example,
a virtual machine allows me to run real Microsoft Windows 10 on my
Macintosh. You will use a virtual machine to run real Linux on your
Windows PC.

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

Before MacOS, Windows or other operating systems with Graphical User
Interfaces for computers existed, there were text _terminals_. Early
[terminals](https://en.wikipedia.org/wiki/Computer_terminal) were
electric typewriters called
[teleprinters](https://en.wikipedia.org/wiki/Teleprinter) capable of
sending and receiving text messages over wires. These were adapted as
input-output devices for computers by replacing the teleprinter at one
end of the wire with the computer. In the 1960’s, Unix and other early
computer operating systems used this text-only human interface first
and it remained central to their architecture after graphical terminals
became available.

Today, you’ll find the original “Terminal” interface in MacOS in the
“Other” application folder. Under Ubuntu, type Control-Alt-T to open a
terminal. Note that Linux may have _only_ a terminal interface unless
a graphical user interface layer is installed and running. The GUI
isn’t a vital part of Linux.

When the terminal opens, it will present a _command line_ with a
_prompt_ like “$” or “>” and then wait for you to type something. This
is the point where 96% of computer users realize that they are not a
TV “hacker”, have no clue what to type, close the terminal and never
again attempt to peek behind the curtain. Lets explore a little
further - trust me, its safe and no “hacking” is required.

Type “help” and press enter/return. Read what appears. Don’t expect to
understand it all yet - just know that you can ask for “help” and get
some. (If you can’t see everything that appeared, enlarge the terminal
window or use the mouse wheel to scroll it.) For more help on some of
the commands in the list, type “help” and the command name, for
example: “help echo”. (BTW, if you want to be traditional at this
point, type “echo hello world” and press enter/return.)

Type “info” and press enter. A menu of available information will
appear. Type the letter “h” for help and read that. Type
“q” to quit when you’re done reading for now. That library of
information will be there when you need it.

Type “man man” and press enter. A user’s manual for the “man” program
will appear. Type “h” for help about this program and “q” to quit it.

Type “man ls” and read briefly about the “ls” command that lists
directory contents. Then type “ls /bin” for a listing of some
“binaries”, that is: programs. The list that appears is a handful of
the most basic programs in Unix/Linux. Type “man” and any of these
names to read about them, for example: “man ed”, “man cat”, “man
mkdir” and “man rmdir”. Type “ls /usr/bin” for a longer list of
programs to explore.

You have been typing commands, running programs and receiving
responses _through_ the terminal, but the program that you have been
commanding is the “shell”, specifically the “Bourne-Again Shell”
named “bash”. Type “info bash” to learn about typing commands to bash
and its other uses.

The point of this exploration is that there is a _lot_ of information
available to you just within the terminal (and much more available by
searching the internet). Please explore (carefully) and follow your
curiosity. Its like a safety-conscious workshop: pretty safe to walk
around if you remember that the tools are sharp and respect the places
that are locked or have warnings posted. Just don’t immediately try to
use “delete” “everything” and “override” and all will be well.

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
