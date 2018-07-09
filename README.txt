OptiPNG version 0.7.7: Advanced PNG optimizer
=============================================

Copyright and licensing
-----------------------
  Copyright (C) 2001-2017 Cosmin Truta and the Contributing Authors.
  See the accompanying AUTHORS file.

  This program is distributed under the zlib license.
  See the accompanying LICENSE file.

  This program uses third-party software released under various
  open-source licenses.

Resources
---------
  Home page:
        http://optipng.sourceforge.net/

  Download:
        https://sourceforge.net/projects/optipng/files/

  Announcements:
        https://sourceforge.net/p/optipng/news/

  Support:
        https://sourceforge.net/projects/optipng/support
        ctruta (at) gmail (dot) com

Build instructions
------------------
  On Unix, or under a Bourne-compatible shell, run ./configure and make:
        cd optipng-0.7.7/
        ./configure
        make
        make test

  Alternatively, use a pre-configured makefile that matches your compiler;
        cd optipng-0.7.7/
        nmake -f build/visualc.mk

Installation instructions
-------------------------
  Build the program according to the instructions above.

  On Unix:
  - Make the "install" target:
        sudo make install
  - To uninstall, make the "uninstall" target:
        sudo make uninstall

  On Windows:
  - Copy optipng.exe to a directory found in PATH.
