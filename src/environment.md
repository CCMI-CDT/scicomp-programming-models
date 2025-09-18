# Setting up your environment

A good development environment on your computer is crucial to effective working as a computational researcher.
In this section we discuss basic preliminaries to setup your machine for software development, code editing tools,
external services, and other useful resources to get you started.

## Configuring your computer

These days it does not really matter any more, whether you use Windows, Linux, or Mac OS for software development.
All three of them are fine and support almost anything you need. There is a small caveat with Windows on ARM architectures (
  e.g. recent Microsoft Surface devices ) Almost everything should work fine. But it is a relatively recent platform and
  there still maybe smaller support gaps.

### Windows setup

The best way to get started with development on Windows is to use [WSL - Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install).
This gives you a complete Ubuntu Linux environment under Windows, allowing any Linux software and development libraries to run natively
within Windows. It is fully Microsoft supported and the preferred way to do scientific software development under Windows.

To access WSL you can use the Windows Terminal app. For software development within WSL you can use [VS Code](https://code.visualstudio.com/) or a text based editor such as Neovim or Helix.

You should familiarize yourself with command line tools to install software under Ubuntu, the default Linux distribution in WSL. See also below for more
information on this.

### Linux setup

If you are already running Linux there is not much more you need to do apart from installing your preferred development tools. We are assuming that
people use Ubuntu and typically show commands for Ubuntu. But any Linux setup works fine.

### MacOS

If you are running Mac it is recommended to install [Homebrew](https://brew.sh/). This is a command line package manager that gives you access
to a vast ecosystem of software tools and libraries for almost anything.


### Coding tools

The most convenient graphical code editor is [VS Code](https://code.visualstudio.com). It supports a huge range of plugins with support
for almost any programming language. If you like working on the command line you might also consider [Neovim](https://neovim.io/) or
[Helix](https://helix-editor.com/). While these have faster editing speed than VS Code they are much harder to learn though. For Neovim
a preconfigured setup such as [LazyVim](https://www.lazyvim.org/) is recommendable.

Many of you will do significant work in Python. One of the most frequently used Python distributions is Anaconda.
Here, a personal recommendation is to install [Conda-Forge](https://conda-forge.org/download/). It is a minimalist version of Anaconda with
just the interpreter and the conda-forge repository preconfigured, which has the largest selection of packages.

### Working on the command line

Whatever system you have, you will do a lot of work on the command line. Very often, when using remote machines the command line is
the only way to interact with a computer. On Ubuntu and WSL your command line will typically by [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)). On Mac OS it will be [Zsh](https://en.wikipedia.org/wiki/Z_shell). Both are fairly similar for most day to day use.
A good tutorial to get started on these and similar so-called Unix like shells is available [here](https://cerfacs.fr/coop/unix-terminal).

### Version Management

Almost everybody uses [Git](https://git-scm.com/book/ms/v2/Getting-Started-About-Version-Control) for version management of code. You should
use `git` together with a [Github](https://github.com) account. Github also has a [simple tutorial](https://github.com/git-guides) for git.

  


