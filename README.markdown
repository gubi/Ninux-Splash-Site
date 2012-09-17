# Ninux.org
[NINUX](http://wiki.ninux.org/) is an Italian Wireless Community Network

# Technology
This Splash-site is in HTML5 and CSS3, and uses jQuery 1.6.4

----
# Before Install
Create your own html contents and place them in `common/includes/`, then create the structure of the pages in the js array of `common/js/pages.js` file.

This repository contains 2 folders: compressed and uncompressed.
The files contained in the compressed folder have been minified and gzipped, if you want to use them you have to make sure they are server with the right content header (content-encoding: gzip). 

If you need (and you probably will) to change things use the files in the uncompressed folder, then report the changes to the compressed folder (minify and gzip).

# Install to NoDogSplash
1. If you have no SCP, install with `apt-get install scp` on your terminal or [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/).

2. CD into the unpacked folder on your system, then run this command on the terminal
    `scp -r {PATH_TO}/Ninux-Splash-Site/[CHOSEN-VERSION]* {USERNAME}@{DEVICE_IP}:/etc/nodogsplash/htdocs/`
    [CHOSEN-VERSION] is either compressed or uncompressed (the latter might need a bit more hacking to get it working). 

3. Reboot NoDogSplash with `/etc/nodogsplash restart`

Enjoy :)

# ToDo

1. PDA-tablet version

# Hack
You can save much loading time simply by compressing contents and scripts in one row... ;)

----
## License
    #  License
    #  
    #	This program is free software: you can redistribute it and/or modify
    #	it under the terms of the GNU General Public License as published by
    #	the Free Software Foundation, either version 3 of the License, or
    #	(at your option) any later version.
    #
    #	This program is distributed in the hope that it will be useful,
    #	but WITHOUT ANY WARRANTY; without even the implied warranty of
    #	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    #	GNU General Public License for more details.
    #
    #	You should have received a copy of the GNU General Public License
    #	along with this program.  If not, see <http://www.gnu.org/licenses/>.
    #
    #
    #	- - -
    #	Created by Alessandro Gubitosi
    #	on May 2012
    #    

This application is released under the Free GNU General Public License v3.0.
For more information about GNU License, see http://www.gnu.org/licenses/gpl.html