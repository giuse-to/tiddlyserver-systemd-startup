# tiddlyserver-systemd-startup
This repo enables the tiddlyserver startup script on CentOS/RedHat like Linux OSes. 
The systemd service is called *tiddlyserver.service*. It provides the start, stop, restart and enable at boot time of the tiddly server, needed to use the tiddlywiki on linux systems.
The scripts are tested upon a CentOS 8 distro, the required node.js package is provided by rpm repos of the distro. 
## Requirements
- The tiddly server package must be downloaded from Arlen22 repo page: https://arlen22.github.io/tiddlyserver/  to the **/opt/** dir. Unzip it and create a symbolic link like that : **tiddlyserver --> TiddlyServer-x.y.z** so that you can reach the path: **/opt/tiddlyserver/server.js**.
- The nodejs rpm package must be installed (on CentOS/RedHat platforms: *yum install nodejs*).

## Usage

### Startup
*systemctl start tiddlyserver.service*

### Show status
*systemctl status tiddlyserver.service*

### Stop
*systemctl stop tiddlyserver.service*

### Startup at boot
*systemctl enable tiddlyserver.service*
