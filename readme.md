Description
===========
Install nodejs files into the /opt directory.  Does not download files if the specified version is already installed.  Links will get updated even if the files were not downloaded.

Needs to be run as sudo.  This script will overwrite the following links in /usr/local directory.
* node
* nodejs
* npm
* npx

Usage
=====
    sudo bash install_node.sh [VERSION]

Options
=======
VERSION (optional) Download and install specific version of node.

Example
=======
    sudo bash install_node.sh 19.0.1
