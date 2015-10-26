Op-25 scanner/recorder built in a virtual machine (ubuntu 14.04) with vagrant.  In order to run install vagrant you need the following.  

#Requirements
##Vagrant 
[Vagrant download](https://www.vagrantup.com/downloads.html)
##VirtualBox 
[VirtualBox for Linux](https://www.virtualbox.org/wiki/Linux_Downloads)
[VirtualBox for Mac](http://download.virtualbox.org/virtualbox/5.0.4/VirtualBox-5.0.4-102546-OSX.dmg)
[VirtualBox for Windows](http://download.virtualbox.org/virtualbox/5.0.4/VirtualBox-5.0.4-102546-Win.exe)
##VirtualBox Extension Pack (for usb-antenna support)
[Extension Pack for all Platforms](http://download.virtualbox.org/virtualbox/5.0.4/Oracle_VM_VirtualBox_Extension_Pack-5.0.4-102546.vbox-extpack)

#Scanner Software 
```
git clone https://github.com/P25Scanners/vagrantScanner.git
cd vagrantScanner
vagrant up
```

#Current Progress
Compiled successfully with Vagrant (running Ubuntu 14.04 in a VirtualBox virtual machine) ....now we need to alter the config.json file in trunk-recorder (see the virtual machine)...



