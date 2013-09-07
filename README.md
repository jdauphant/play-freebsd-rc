play-freebsd-rc
===============

Rc script for play framework 1.* and 2.* on freebsd

INSTALLATION
------------
* copy play in /usr/local/etc/rc.d

USAGE
-----
* create a synlink ln -s /usr/local/etc/rc.d/play /usr/local/etc/rc.d/play_applicationName
* add these lines to your rc.conf :
    play_ApplicationName_enable="YES"
    play_ApplicationName_path="/var/www/ApplicationName"
    play_ApplicationName_user="play" 
    play_ApplicationName_playpath="/usr/local/opt/play"
