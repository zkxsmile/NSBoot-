# NSBoot-v. 4.0.0
Diskless boot Windows/Linux - Free Analog CCBoot 

<h1>Games, Internet cafe, Schools</h1>
<h2>Viruses are no longer scary, no unauthorized changes</h1>

* Just restart your computer and the system state will return.
* If you have a lot of computers. There is no need to have hard disks on workstations with this technology
* Web based interface
* Linux based server
  - ZFS optimized storage 
  - Cached
  - Fast I/O perfomants
* Diskless boot from iscsi - Windows/Linux/Mac and other OS


This project is intended to be a free replacement for technology ccboot.
===
- Ubuntu : 
 apt install -y etherwake shellinabox qemu-utils lua-json lua-socket lua-posix nginx-extras zfsutils-linux
 


========================================

 TODO:
- [x] Base resty generic [LUA 5.3] 
- [x] nbd devices process detach from nginx [/usr/bin/nsbootd]
- [x] init stripc start/stop/status/reload [/etc/init.d/nsbootd]
- [ ] Web interface
- [ ] Installer system
- [x] vhd/qcow/qcow2/vmdk/vhdx parrent images
- [x] AutoRemove child images on boot system if not super mode
- [ ] Autoremove child images if disconnect iscsi more keep-alive connect
- [ ] GUI Installer system
- [ ] ShellInaboxd
