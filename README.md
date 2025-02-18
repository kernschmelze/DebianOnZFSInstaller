# DebianOnZFSInstaller
An interactive ZFS on Root installer for Debian

Usage:

1. Start Debian Live.
2. Switch to a console with, say, ctl-alt-F3
3. Get root (sudo su -)
4. Copy the perl script from USB stick, or download it into the /root directory
5. Name it there just 'debianonzfsinst' (without extension), make sure it is executable (chmod ...)
6. Call the script:   ./debianonzfsinst
7. Follow the dialogs
8. After it got installed, you have to reboot
9. The first boot it is usually necessary to 'zpool import -f <yourpool>'
10. Now do the postconfiguration... this part of the interactive installer is still WIP
