# Install notes for Ubuntu

Best instructions for dual booting I have found are [http://askubuntu.com/questions/688632/dual-boot-mac-el-captain-along-with-ubuntu-14-04/688692?stw=2#688692](http://askubuntu.com/questions/688632/dual-boot-mac-el-captain-along-with-ubuntu-14-04/688692?stw=2#688692).

Get the Ubuntu install disk from [Ubuntu](http://www.ubuntu.com/download/desktop/).

- Partition...

- 14.04 install
- with 3rd party
- LVM but DO NOT encrypt as it screws up NFS
- restart
- install updated ubuntu software
- restart
- virtualbox
- vagrant 64 bit from web
- log in to host/log out to create .ssh directory
- get keys
```
cd ~/.ssh
scp eevenson@host:~/.ssh/*id_rsa* .
```
- git-cola
- chrome 64 bit
- lastpass

- set up nfs
```
sudo apt-get update
sudo apt-get install nfs-kernel-server
sudo
```

- dropbox
- http://forum.bittorrent.com/topic/28106-linux-desktop-gui-unofficial-packages-for-bittorrent-sync/
- ReText
- https://help.ubuntu.com/community/SSH/OpenSSH/Configuring
- sublime text 3 + packages (eco and coffeescript)
