# LINUX FILE HIERARCHY
- Linux/UNIX have a special file system windows.
- File system  is a Directory structure that the OS uses.
- windows: system files appear under the **local disc C:**
- Linux: System files appear under the **root directory[/]**
>> you can check in terminal also in filemanager
## File Structure In Detail
## 1) / (root)
- Every single file and directory starts from the root directory 

- The only root user has the right has the right to write under this directory 
- /root is the root user's home directory. Which is not the same as/ 
## 2) bin - Binary Executables 
- Essential command binaries that need to be available in single-user mode ; for all users

i) e.g cat,ls,cp,pwd
## 3) /boot - Boot loader files 
     


     Kernel initrd,vmlinux,grub files are located under /boot 
     e.g - initrd.img -2.6,32-24-Generic,
         - vmlinuz -2.6,32-24-generic

## 4) /dev - Essential Device Files
       




       These include terminal devices,usb or any device attached to the system.
       E.g : /dev/tty1,/dev/usbmon0

 ## 5) /etc - tc cetera 





        It contain configiration files requied by all programs. This also contains startup and shutdown shell scripts used to start/stop indivisual programs. 
        Example: /etc/resolv.conf,/etc/logrotate.conf,
 ## 6) /home - Home directory


       Home directories for all users to store their personal files.
     E.g /home/anony,/home/efa
## 7) /lib - Liberaries      
       
       Liberaries essential for the binaries in /bin & /sbin
        => Liberary filenames are either Id* or lib*,so*.
        Example : Id-2.11.1.so,libncurses.so.5.7
## 8) /media => 
     Mount  points for removable media such as CD-ROMs
        => Temporary mount directory for removable devices .
        Examples :- /media/cdroom for CD-ROM;/media/floopy for floopy drives;
                  - /media/cdrecorder for CD writer 
## 9) /mnt =>

        - Temporarily mounted file.I mount directory where sysadmins can mount filesystems.
## 10) /opt :-
       Optional application software packages.Contains add-on applications from indisvidual venders.
       Add on applications should be installed under either /opt/ or /opt/sub-directory 
## 11) /sbin :~
       
       Essential system bineries.Just like /bin,/sbin also contains excutables.The linux commands located under this directory are used typically by system  adminstrator,for system adminstrator,for system maintenance purpose  
## 12) /tmp -Temporary Files
      
      DIRECTORY that contains temporary files created by system and users.
      Files under this directory are  deleted when system is rebooted.
## 13) /usr -User utilities




       - contains binaries,liberaries,documentation,and source-code for second level programs.
       - /usr/bin contains contains binary under files for user programs.If you can't find a user binaryunder /bin ,look under /usr/bin. For e.g : at,awk,cc,less,scp
       - /usr/sbin contains contains binary files  for system adminstrators. If you can't find a system binary under /sbin,look under /usr/sbin. FOR E.G:atd,cron,sshd,useradd,userdel
       - /usr/lib contains libraries for /usr/bin and /usr/sbin
       - /usr /src holds the linux kernel sources,header-files and documentation.



##  TEXT  EDITORS
- Programs that user for text processing 
- Linux command line text editors
  - VIM
  - Nano
  - Emacs
  - Neovim
  -  . . .
- Linux Graphical Text Editors         
    - Sublime
    - Vs code
    - Gedit
    - Pluma
    - . . .
    ## VIM
- Before vi the primary editor used editor used on Unix was the line editor 
  - User was able to see/edit only one line of the text at a time 
- Then vi editor improved and developed VIM.(VI iM proved)
- The vim editor is:
     - a very powerful
     - but at the same time it is cryptic 
     - It is hard to learn,specially for windows users 
- It have to modes   
      - a command mode -> where you can do commands 
      - Input mode -> where you can write 
 ### Opening vim
     Syntax
        vim your filename       
> vim is by default **command mode** when you open it.
> > To get on **_insert mode_** you have to type 'i'
> > To get back to **_command mode_** press 'esc'
>>> inside command mode you can
- > To save  :w + enter
- > To Quit :q + enter
- > To save & quit  :wq! + enter  
- > to force quite  :q!
- > For undo :u + enter
- > To execute commands  :%! your command
## NANO
      
      The Gnu nano text editor is a user-friendly,free and open-source text editor that usually comes pre-installed in modern linux systems.
### Starting nano 
        Syntax
             nano filename
## LINUX USER MANAGEMENT 
   - On linux,to create users you can use the following commands 
        - useradd -> simple
        - adduser -> Detailed
- Useradd command 
   - sudo useradd username 
- Adduser command 
    - sudo adduser user name                     
> - The user files are stored inside /etc/passwd
> - The user password are stored inside /etc/shadow
> - When you create a user it creates a group with that name.
## TO ACCESS ROOT ACCESS

       COMMAND
          -> sudo su 








       
