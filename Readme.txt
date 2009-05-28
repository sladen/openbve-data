================
openBVE - Readme
================


---------------
Getting started
---------------

If you have problems starting openBVE, make sure that you have read the "Getting started" articles on the official homepage located at:

http://openbve.trainsimcentral.co.uk/use/index.html

These pages also include driving guides and an overview on the default keyboard assignment.


---------------------------------
OpenBve.exe vs. OpenBveAnyCpu.exe
---------------------------------

OpenBve.exe forcibly runs in 32-bit mode even on 64-bit (x64)processors. You should execute this file if you have a 32-bit (x86) processor, or if you have a 64-bit (x64) processor, but the dependencies (Tao, OpenAL, SDL) are only available in 32-bit form (which is currently the case for Windows users).

OpenBveAnyCpu.exe runs in the native mode the processor and operating system support, e.g. in 32-bit on an x86 processor, and in 64-bit on an x64 processor. You are required to have the matching depencendies (Tao, OpenAL, SDL) in order to execute this file.


----------------------
Command line arguments
----------------------

/route=FILE
Loads the specified route (CSV, RW) on startup. If /train is not also specified, the default train of the route will be used if one is found, otherwise the main menu opens with just the route selected.

/train=FOLDER
Loads the specified train folder (containing a train.dat) on startup. If /route is not also specified, the main menu will be opened with just the train selected.

/fhs
Uses the file system hierarchy standard on Unix (Linux/Mac). Please consult the "Using openBVE" pages on the official homepage page for more information.


-----
Links
-----

Official homepage:
http://openbve.trainsimcentral.co.uk/

Official discussion forum:
http://openbve.freeforums.net/

Please note that support is only offered for distributions that were downloaded from the official homepage, and only for the latest versions available there.


------------------------
Dedication to the public
------------------------

This program, along with all documentation provided, is dedicated to the public. I do not pose any restrictions on how this material can be used, and explicitly encourage redistribution and modification for any purpose.