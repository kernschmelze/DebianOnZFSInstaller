# DebianOnZFSInstaller
An interactive ZFS on Root installer for Debian

Usage:

1. Start Debian Live. Wait until the login screen appears
2. Switch to a console. The normal way to do so is ctrl-alt-F{1..6}
3. $ sudo su -
4. \# curl https://raw.githubusercontent.com/kernschmelze/DebianOnZFSInstaller/refs/heads/main/debianonzfsinst.pl -o debianonzfsinst.pl
5. \# perl debianonzfsinst.pl
8. Follow the dialogs
9. After it got installed, you have to reboot
10. The first boot it is usually necessary to 'zpool import -f <yourpool>'
11. Now do the postconfiguration... this part of the interactive installer is still TBD
