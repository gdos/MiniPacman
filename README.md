![screenshot](https://github.com/fastrgv/MiniPacman/blob/master/cpac.jpg)

# MiniPacman
MiniPac is a kid friendly ascii character version of Pacman that plays in a commandline terminal.

Here is the download link:

https://github.com/fastrgv/MiniPacman/releases/download/v1.0.0/pac3dec17.tar.gz




# MiniPacman

## What's new:

**ver 1.0.0 -- 3dec17**
* fixed arrow keys in Windows.
* original release.
* fair performance achieved by not clearing screens between redraws.
* simple Ada code that is easy to compile.


===========================================================================

### MiniPacman
MiniPac is a kid friendly ascii character version of Pacman that plays in a commandline terminal.  Pure minimalism with classic sounds and 9 predefined levels.  Runs on Windows, OSX & Linux.

Keyboard setup is important.  You should have a short key-delay and fast repeat setting.  

The arrow keys, or wasd-keys, or ijkl-keys control movement.  The (x),(q) keys quit;  (p) pauses game.

Includes executables and source code.

===============================================================
## Setup & Running:
Unzip wherever, make your terminal at least 60 chars wide by 40 lines, then simply type the executable name to begin.

OSX:		pacman_osx
Linux:	pacman_gnu
Windows:	pacman.exe

===============================================================

Usable keys:

* arrow-keys
* ijkl-keys
* wasd-keys
* (p)=pause
* (q)=quit


===========================================================================
## Compiler Scripts
There are three scripts, wcmp.bat for msWindows, lcmp.sh for Linux, and ocmp.sh for OS-X.

===============================================================
## Build Instructions:
Remember that prebuilt executables are already included.  If you want to rebuild...

Manually install GNAT GPL from libre.adacore.com/download/.  

Next, edit the scripts wcmp.bat or lcmp.sh or ocmp.sh so that the path to gnatmake is correct.

Then type "[lo]cmp.sh" or "wcmp.bat" to create new command-line executables for your system.



===============================================================
## Legal Mumbo Jumbo:

MiniPacman is covered by the GNU GPL v3 as indicated in the sources:

 Copyright (C) 2017  <fastrgv@gmail.com>

 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.

 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.

 You may read the full text of the GNU General Public License
 at <http://www.gnu.org/licenses/>.


----------------------------------------------
## Thanks to:
Mike Billars [michael@gmail.com] for his [gnu gpl] C-version of Pacman for the console, after which this Ada version was modelled.


----------------------------------------------
## Best Download Site for all my games:
https://github.com/fastrgv?tab=repositories


--------------------------------------------------
## Earlier Revision History:


