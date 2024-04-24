## LINUX | UNIX FILE HIERRCHY
linux | unix have  a special file system that windows.
fil system is a directory structure that the os uses.
### SYSTEM FILES
* system files are files used by the system software {os}
windows; system files appear under the local disk c 
linux; system files appear under the directory [/]
### FILE STRUCTURE IN DETAIL 
1 / [root]
* every single file and directory starts from the root directory 
* the only root user has the right to wright under this directory 
* /root is the root users home directory, which is not the same us/
2 bin-binary exectables [run]
* essential command binaries that need to be avaliable in single -user mod; for all users
* eg, cat , scp, pwd 
3 /boot-boot londer files 
* kernel inltrd, vmlinux, grub file are locate under boot [use to turn on]
4 /dev -essential devices files 
* these include terminal device, usb or and device attached to the system 
* example; |dev|ttyl, /dev/ usbmoon1
5 /etc -et ceteral
contains configuration files required by all programs
this also contains startup and shutdown shell scripts used to start / stop
6 /home - home directory 
home directories for all user to store their personal files.
example; /home/eyohe
7 /lib - libraries essential for the binance in/bin $ sbin library file names are either id or lib 
8 /media  mount points for removable media sucj as CD-ROMS
temporary mount directory for removable devices
example |media cd , file
9 /mnt temporarily mounted file
temporary mount directory where sysadmins can mount file systems
10 /opt optional appl software packages 
contains add on applications from individual vendors add on application should be installed under essential 
11 /sbin - essential system binaries 
just like /bin, /sbin also contains binary exectables the linux commands located under this director 
12 /tmp - temporary files 
directory that contains temporary files created by system and users
file under this directory are deleted when system is rooted 
13 /usr - usr utilities
contains binaries, libraries, documentation and source 
code for second level programs 

programs that used for text processing 
### LINUX COMMAND LINE TEXT EDITOR'S 
VIM   NANO    EMACS    LINUX    VS CODE   NEOVIM   SUBLIME

#### VIM
before vi the primary editor used on unix was the ine editor 
user was able to see lediit 
SYNTAX to save and exit
:wq!  +  enter 
root id = 0
normal used id start with 1 - 999
#### create users you can use the f/f command 
      useradd - simplied
      adduser - detailed
the user files are stored inside /etc/passwd 
the user password are storied inside |etc|shadow
