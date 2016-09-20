# generic-raspberry-nas

This is a set of scripts to setup a Raspberry Pi as a simple NAS+media server.

To install the NAS, simply run the following:
```bash
wget -Nnv https://raw.githubusercontent.com/vladonemo/generic-raspberry-nas/master/install.sh && bash install.sh
```

Features:
- plex used as a media streaming option
- samba shares for all content folders
- backup scripts for both full and incremental backups
- backing up Plex Media Server library (weekly incremental)
