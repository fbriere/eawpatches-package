eawpatches-package
==================

eawpatches (also known as eawpats) provides a set of Gravis patch files
suitable for MIDI audio synthesis.  It is more complete than the freepats
package, but since many of these patches are of unknown origin, they cannot be
distributed by Debian.

This utility makes it possible to build your own personal Debian package of
eawpatches.

Requirements
============

  - fakeroot
  - wget or curl
  - unzip (optional)

Using eawpatches-package
========================

To use this package, run the `make-eawpatches-package` command.  This will
attempt to download eawpatches, and create a Debian package (.deb file) of
its contents.

The Debian package can be installed with the command `dpkg --install`.

Legal warning
-------------

Keep in mind that eawpatches contains proprietary files, most of which are
without any licence.  Download and use at your own risk.

Development
===========

This program and its source code can be downloaded from GitHub:

https://github.com/fbriere/eawpatches-package

Feedback
========

Bug reports and feature requests should be sent to the Issues section of this
program's GitHub repository.

You are also welcome to contact the author with any question or comment you
may have about this program.  Feedback is always appreciated.  :)

Author
=======

Frédéric Brière - fbriere@fbriere.net

