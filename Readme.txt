================
openBVE - Readme
================


---------------
Getting started
---------------

If you have problems starting openBVE, make sure that you have read the "Getting started" articles on the official homepage located at:

http://openbve.trainsimcentral.co.uk/use/index.html

These pages also include driving guides and an overview on the default keyboard assignment.


----------------------------------
OpenBve.exe on 64-bit environments
----------------------------------

OpenBve.exe forcibly runs in 32-bit mode even on 64-bit (x64) processors. This means that you need to have 32-bit versions of the required external dependencies.

You can, however, download the source code and compile an any-cpu version of openBVE if you have 64-bit versions of the dependencies at hand.


----------------------
Command line arguments
----------------------

/route=FILE
Loads the specified route (CSV/RW) on startup. If /train is not also specified, the default train of the route will be used if one is found, otherwise the main menu opens with just the route selected.

/train=FOLDER
Loads the specified train folder (containing a train.dat) on startup. If /route is not also specified, the main menu will be opened with just the train selected.

/fhs
Uses the file system hierarchy standard on Unix (Linux/Mac). Please consult the "Using openBVE" pages on the official homepage page for more information.


-----
Links
-----

Official homepage:
http://openbve.trainsimcentral.co.uk/

Official discussion board:
http://openbve.freeforums.net/

Please note that support is only offered for distributions that were downloaded from the official homepage, and only for the latest versions available there.


------------------------
Dedication to the public
------------------------

This program is dedicated to the public. I do not pose any restrictions or requirements on how this material can be used, and explicitly encourage redistribution and modification for any purpose.