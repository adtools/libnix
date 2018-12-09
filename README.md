libnix: C link library for AmigaOS/m68k
===

**Short description:** Fork of [libnix](http://sourceforge.net/projects/libnix/) from [sourceforge.net](http://sourceforge.net).

## Overview

**libnix** is used in conjuction with [m68k-amigaos-toolchain](https://github.com/cahirwpz/m68k-amigaos-toolchain) project. It's standard C link library (similar to glibc or newlib, but quite incomplete) for gcc cross compiler targeting AmigaOS/m68k systems.

There are several initiatives trying to bring up an updated C link library for AmigaOS/m68k systems:

* [libnix-3.0](https://github.com/diegocr/libnix) by Diego Casorran
* [clib2](http://clib2.cvs.sourceforge.net/) by Olaf Barthel
* [arosc.library](http://repo.or.cz/w/AROS.git/tree/HEAD:/compiler/stdc) in [Amiga Research Operating System](http://aros.sf.net) source tree

For now I decided to use original sources by Jeff Shepher et al., perhaps I'll merge Diego Casorran's changes if I find them indispensable.
