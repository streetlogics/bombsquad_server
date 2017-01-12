To run this, simply cd into this directory and run ./bombsquad_server (on mac or linux) or launch_bombquad_server.bat (on windows)
You'll need to open UDP port 43210 so that the world can communicate with your server.
You can edit some server params in the bombsquad_server script, or for more fancy changes you can modify the game scripts in data/scripts.

platform-specific notes:

mac:
- The server should run on macOS 10.9 or newer

linux:
- The server binary was compiled on ubuntu 14.04 LTS. It depends on SDL2 and Python 2.7, so install either of those if need be.
  To do this you generally run something like "sudo apt-get install python2.7 libsdl2-2.0"

windows:
- You may need to run vc_redist.x86 to install support libraries if the app quits with complaints of missing DLLs

Please give me a holler at support@froemling.net if you run into any problems.

Enjoy!
-Eric
