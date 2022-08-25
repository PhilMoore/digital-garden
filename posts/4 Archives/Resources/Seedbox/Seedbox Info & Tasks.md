# Seedbox Info & Tasks

## Sync Time
every day at 03:00 CET = 01:00 UTC

things:///show?id=yKrXdQpuAqwxJ92VLDrhz&filter=

## Apps
https://fadekun.lw981.usbx.me/rutorrent/ 
[Radarr - Login](https://fadekun.lw981.usbx.me/radarr/)
[Login - Sonarr](https://fadekun.lw981.usbx.me/sonarr/calendar)
[Jackett](https://fadekun.lw981.usbx.me/jackett/UI/Dashboard)
[Deluge: Web UI 1.3.15](https://fadekun.lw981.usbx.me/deluge/)

### Torrent Leech
[Login :: TorrentLeech.org](https://www.torrentleech.org/profile/pkun/#hitandruns)
Users with ratios below 0.85 experience wait times and slot restrictions, you can read all about these in the  [WIKI](http://wiki.torrentleech.org/) .
[user_guides    TorrentLeech.org Wiki](http://wiki.torrentleech.org/doku.php/user_guides)

### IPTorrents
Hit & Run - http://on.iptorrents.com/seeding_required.php


## CONNECT TO SEEDBOX VIA SSH
[How to connect to your… | UltraSeedbox Docs](https://docs.usbx.me/books/secure-shell-%28ssh%29/page/how-to-connect-to-your-seedbox-via-ssh)
ssh fadekun@apollo.usbx.me
DcYcPLiRcoRXQcY__R9


## CONNECT  TO SEEDBOX VIA FTP
IP: 46.232.211.110
Port: 21
Pass: DcYcPLiRcoRXQcY__R9

## Rclone Sync Command

### MANUAL SYNC TO DRIVE SSH COMMANDS
> it's better to use the rclone-upload.sh script rather than the systemd service

To run the command manually use: 
`/home/fadekun/scripts/rclone-upload.sh` - Paste this directly in an SSH terminal

`tail -f ~/scripts/rclone-upload.log`  - will show the logs in real-time


### *Edit MergerFS script*
nano $HOME/.config/systemd/user/mergerfs.service
nano $HOME/.config/systemd/user/rclone-vfs.service

nano $HOME/.config/systemd/user/rclone-vfs.service

cat ~/.config/systemd/user/rclone-uploader.service
cat ~/.config/systemd/user/rclone-vfs.service


### INSTALLING RCLONE
[Installation, Configur… | UltraSeedbox Docs](https://docs.usbx.me/books/rclone/page/installation-configuration-usage-of-rclone)

RCLONE LINLK:
[Google drive](https://rclone.org/drive/)

[Rclone VFS and MergerF… | UltraSeedbox Docs](https://docs.usbx.me/books/rclone/page/rclone-vfs-and-mergerfs-setup)


### OAUTH FOR GOOGLE DRIVE
[Configuring Oauth for Google Drive - Documentation -](https://kb.ultraseedbox.com/display/DOC/Configuring+Oauth+for+Google+Drive)

[Google Cloud Platform](https://console.developers.google.com/apis/credentials?highlightClient=313469352472-mfevu3oqgju94d8rvs9rtf4n9n5lfs40.apps.googleusercontent.com&project=instant-mobile-smtp-server)

CLIENT ID:
875693760964-5gi1lcrfni54jrot7c6q06dmnh23i2k4.apps.googleusercontent.com

SECRET ID
P9z0oSUZpMphZpYNZjkWWn3b



## AUTODL & DELUGE FOR SEED RACING
https://docs.usbx.me/books/deluge/page/setting-up-autodl-irssi-and-deluge-via-deluge-console

`/home32/fadekun/bin/deluge-console`

Absolute of script:
`/home32/fadekun/scripts/deluge-reannounce.sh`

Intersesting guide
[Special step-by-step Guide to Autodl-irssi (Exclusive)](https://www.rapidseedbox.com/kb/use-rutorrents-autodl-irssi-plugin)


TL AUTODL
[autodl.irssi    TorrentLeech.org Wiki](http://wiki.torrentleech.org/doku.php/autodl.irssi?s%5B%5D=irssi)
https://www.rapidseedbox.com/kb/use-rutorrents-autodl-irssi-plugin

[Seedbox Guide: How To Improve Your Torrent Tracker Ratio](https://seedboxgui.de/guides/improve-torrent-tracker-ratio/)


#### JACKETT SETUP
[Initial Setup and Conf… | UltraSeedbox Docs](https://docs.usbx.me/books/jackett/page/initial-setup-and-configuration)


####  DELUGE 
Autoremove on DELUGE
[Plugin Auto Remove Plus v0.6.1 - Deluge Forum](https://forum.deluge-torrent.org/viewtopic.php?t=47243)


### Ultra Seed Box Automation Setup Guide
[UltraSeedbox Recommend… | UltraSeedbox Docs](https://docs.usbx.me/books/automation---a-comprehensive-guide/page/ultraseedbox-recommended-full-automation-setup)


## Rclone De-Duplicating Files
https://rclone.org/commands/rclone_dedupe/
`rclone dedupe gdrive: --interactive`
^ Use the above for a proper run