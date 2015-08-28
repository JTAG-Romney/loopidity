### This is Loopidity *- A multitrack looping audio recorder for GNU/Linux designed for live handsfree use*
| build      | status |
| ---------- | ------ |
| linux      | [![Build Status](https://travis-ci.org/bill-auger/loopidity.svg?branch=linux)](https://travis-ci.org/bill-auger/loopidity) |
| windows    | [![Build Status](https://travis-ci.org/bill-auger/loopidity.svg?branch=mingw)](https://travis-ci.org/bill-auger/loopidity) |
| latest-dev | [![Build Status](https://travis-ci.org/bill-auger/loopidity.svg)](https://travis-ci.org/bill-auger/loopidity) |

#### build
* binaries coming soon - bake yer own for now
* build requires libsdl1.2 , libSDL_gfx , libSDL_ttf and libjack2 (also X11 on *nix) devel libs
* compiler must support c++11 features
* windows and code::blocks builds refer to [README-MINGW.md](https://github.com/bill-auger/loopidity/blob/master/README-MINGW.md)

build with gnu toolchain on a *nix
```bash
    $ cd build
    $ make
```
build with gnu toolchain on windows
```bash
    $ cd build
    $ MINGW=1 make
```
build with code::blocks
```bash
    $  cd build
    $  codeblocks loopidity.cbp
```