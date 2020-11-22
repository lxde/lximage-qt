# LXImage-Qt

## Overview

LXImage-Qt is the Qt port of LXImage, a simple and fast image viewer.

In addition it features a tool to take screenshots.

It is maintained by the LXQt project but can be used independently from this
desktop environment.

## Installation

### Compiling source code

Runtime dependencies are qtx11extras and [libfm-qt](https://github.com/lxqt/libfm-qt)
(LXImage-Qt used to depend on [PCManFM-Qt](https://github.com/lxqt/pcmanfm-qt)
but the relevant code belongs to what was outsourced in libfm-qt).
Additional build dependencies are CMake and optionally Git to pull latest VCS
checkouts.

Code configuration is handled by CMake. CMake variable `CMAKE_INSTALL_PREFIX`
has to be set to `/usr` on most operating systems.

To build run `make`, to install `make install` which accepts variable `DESTDIR`
as usual.

### Binary packages

Official binary packages are available in Arch Linux, Debian (as of Debian stretch),
Fedora and openSUSE (Leap 42.1 and Tumbleweed). Just use the distributions'
package manager to search for string 'lximage'.


### Translation

Translations can be done in [LXQt-Weblate](https://translate.lxqt-project.org/projects/lxqt-desktop/lximage-qt/).

<a href="https://translate.lxqt-project.org/projects/lxqt-desktop/lximage-qt/">
<img src="https://translate.lxqt-project.org/widgets/lxqt-desktop/-/lximage-qt/multi-auto.svg" alt="Stato traduzione" />
</a>
