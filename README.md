![screenshot](https://github.com/fastrgv/MiniPacman/blob/master/cpac.jpg)

# MiniPacman
MiniPac is a kid friendly ascii character version of Pacman that plays in a commandline terminal.

Here is the download link:

https://github.com/fastrgv/MiniPacman/releases/download/v1.0.2/pac9dec.tar.gz




# MiniPacman

## What's new:

Video:  https://github.com/fastrgv/MiniPacman/blob/master/pman25.mkv


**ver 1.0.2 -- 9dec17**

* The script hipri.bat for Windows was added to fix terminal-freezes by opening a high priority command window for console games.
* On Windows, Minipac now attempts to automatically set real-time priority, which should make the script hpri.bat unnecessary.
* Also added scripts gnupac.sh (linux) & osxpac.sh (OSX) to run at high priority using "nice", if necessary.



**ver 1.0.1 -- 6dec17**

* Added missing DLLs required under Windows;
* Added first optional command line parameter 0 ... 9 allows user to control speed of play, where 0 => slow, 5 => default, 9 => fast.
* Added second optional command line parameter 0 ... 9 allows user to control speed of Ghosts, where 0 => stopped, 2 => default, 9 => fast.
* Thus, a game with default settings has either two parameters "5 2", or no parameters.


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
* Unzip wherever;  

* Resize your terminal to at least 57 chars wide by 36 lines;

* You might want to enlarge the Font so that the window becomes physically larger.  

* type the executable name to begin.

OSX:		pacman_osx
Linux:	pacman_gnu
Windows:	pacman.exe

Each executable can now be given 2 optional integer command line parameters:
	* Game Speed 0..9;  0=slow, 5=default=medium, 9=fast;
	* Ghost Speed 0..9;  0=stopped, 2=default=easy, 9=fast

So on windows, the command "pacman.exe 5 2" gives default settings, same as no parameters.

NOTE:  Windows users can use the script "hipri.bat" to open a realtime, high-priority window in which to run pacman.  (It seems that some Windows hardware causes terminal freezes at normal priority.)  However, the latest version of pacman automatically attempts to set a high priority for itself in Windows.

For Linux/OSX users, you can use the "nice" command to be a bit less nice and give each terminal game the highest real time priority.  

For example, to run at high priority on OSX type:

"nice --adjustment=-20 pacman_osx".  

or simply use the scripts gnupac.sh or osxpac.sh:

osxpac.sh  (on OSX)

or

gnupac.sh  (on Linux)




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


