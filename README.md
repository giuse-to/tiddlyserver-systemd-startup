# tiddlyserver-systemd-startup
This repo enables the tiddlyserver startup script on CentOS/RedHat like Linux OSes. 
The systemd service is called *tiddlyserver.service*. It provides the start, stop, restart and enable at boot time of the tiddly server, needed to use the tiddlywiki on linux systems.
The scripts are tested upon a CentOS 8 distro, the required node.js package is provided by rpm repos of the distro. 
The tiddly server package, instead, have to be downloaded at Arlen22 repo page: https://arlen22.github.io/tiddlyserver/ .
