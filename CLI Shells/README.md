# Readme

## Preamble/Disambiguation

I'm only discussing Command-Line Interface (CLI) shells, not Graphical
User Interface (GUI) Shells. 

GUI shells are your familiar
[Windows](https://learn.microsoft.com/en-us/windows/win32/shell/shell-entry)
environments that Windows maintains as huge singular monorepos. When you
execute a Windows operating system, its
[kernel](https://en.wikipedia.org/wiki/Architecture_of_Windows_NT)
cannot be decoupled from your GUI (such as Windows 10 or Windows 11
GUI). Although there have been recent advances to have [Windows
container
images](https://learn.microsoft.com/en-us/virtualization/windowscontainers/manage-containers/container-base-images)
that you don't need to run GUI at all, but I'm pretty sure that a lot of
Windows-native programs are [not
supported](https://github.com/microsoft/Windows-Containers/issues/26#issuecomment-771247996). 

Linux or UNIX in general is a different situation. Your GUI shell is
optional. It depends on the
[distribution](https://en.wikipedia.org/wiki/Linux_distribution) you
use, but if you use [Arch Linux](https://archlinux.org/) by installing
it in either a VM program such as
[Virtualbox](https://www.virtualbox.org/) or
[VMware](https://www.vmware.com/), or real hardware (also called bare
metal installation) you will soon discover that your mouse will not
work. As the system boots up, starting from some point (unless there's
an error in [booting](https://en.wikipedia.org/wiki/Booting) which could
happen but rare these days) you will be greeted with a command-line
prompt with a blinking cursor. This is your CLI shell. 

MacOS is something I'm not familiar with, but as far as I understand, it
CAN have CLI-only environment. 


## What is a CLI Shell ( AKA UNIX Shell)?

Let's be clear, I'm NOT going to talk about "cmd.exe" in Windows, if not
just because cmd.exe in Windows is not as powerful as UNIX shells, or
that in practical use it is not as powerful as UNIX shells. Powershell
is better and a usable shell. Check out [Powershell
7.30](https://github.com/PowerShell/powershell/releases) or above if you
are on Windows. It's got inline completion hints!

Unix shells are the 
