master: [![Build Status](https://travis-ci.org/drazisil/comical.svg?branch=master)](https://travis-ci.org/drazisil/comical) dev: [![Build Status](https://travis-ci.org/drazisil/comical.svg?branch=dev)](https://travis-ci.org/drazisil/comical)

------------------------------------------------
Comical - The Comic Book Archive reader
------------------------------------------------

Finally - a cross-platform, open-source CBR and CBZ reader!  Read your favorite
scanned comic books and graphic novels with Comical's absurdly easy GUI and
in-your-face double page display!

Nifty Features:
* Single-Page or Double-Page display modes.
* Several zoom modes - Fit, Fit-to-Width, Fit-to-Height, Original, and Custom.
* Crisp image scaling with algorithms adapted from FreeImage 3.
* Autodetects double pages scanned together and displays it accordingly.
* Page rotation.
* Full-Screen mode.
* Left-to-Right or Right-to-Left browsing.
* Displays JPG, GIF, and PNG images.
* Supports RAR(.cbr) and ZIP(.cbz) comic book archives
* Supports all encrypted RAR archives as well as ZIP archives with pkzip 2.04g
encryption.

What you need to compile from source:
wxWidgets 2.6.0 or later
gcc 3.3 or later

Install:
===================
* patch -p1 -s < comical-wx2.8.patch (if using wxwidgets 2.8)
* ./configure && make

Acknowledgements:
================

Brought to you by: lightstruk, sfogel8108, skaughtie, tizzz

Copied from http://sourceforge.net/projects/comical/ by Drazisil

Cross-platform magic and GUI Widgets provided by:
wxWidgets (http://www.wxwindows.org)

Image resizing provided by:
FreeImage (http://freeimage.sourceforge.net/).

JPEG support provided by:
Independent JPEG Group (http://www.ijg.org/)

ZIP decompression provided by:
Copyright (C) 1998-2005 Gilles Vollant.

RAR decompression provided by RARLabs.  You cannot use the unrar source to
re-create the RAR compression algorithm, which is proprietary.  Distribution
of modified Unrar source in separate form or as part of other software is
permitted, provided that it is clearly stated in the documentation and source
comments that the code may not be used to develop a RAR compatible archiver.

Licence
=======================
Please see COPYING

In addition, as a special exception, the author gives permission to link the
code of his release of Comical with Rarlabs' "unrar" library (or with modified
versions of it that use the same license as the "unrar" library), and
distribute the linked executables. You must obey the GNU General Public License
in all respects for all of the code used other than "unrar". If you modify this
file, you may extend this exception to your version of the file, but you are
not obligated to do so. If you do not wish to do so, delete this exception
statement from your version.
