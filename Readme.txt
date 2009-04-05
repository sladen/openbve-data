================
openBVE - Readme
================


---------------
Getting started
---------------

If you have problems starting openBVE, make sure that you have read the "Getting started" articles on the official homepage located at:

http://openbve.uuuq.com/en/use/index.html

These pages also include driving guides and an overview on the default keyboard assignment.


-----------------------------
OpenBve.exe vs. OpenBve64.exe
-----------------------------

First of all, users running on a 32-bit architecture should execute OpenBve.exe. For users running on a 64-bit machine, these are the differences:

OpenBve.exe executes as 32-bit. You have to use this file if the dependencies are only available in 32-bit. If the dependencies are 64-bit, you cannot use OpenBve.exe.

OpenBve64.exe on the other hand executes as 64-bit. You need 64-bit versions of the dependencies as well. Train plugins are not currently supported by OpenBve64.exe (not on operating systems other than Windows anyway).


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
http://openbve.uuuq.com/

Official discussion forum:
http://openbve.freeforums.net/

Please note that support is only offered for distributions that were downloaded from the official homepage, and only for the latest versions from either the stable or the development branches available there.


------------------------
Dedication to the public
------------------------

This program, along with all documentation provided, is dedicated to the public. I do not pose any restrictions on how this material can be used, and explicitly encourage redistribution and modification for any purpose.