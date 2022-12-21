 # FURTHER FOR LINUX 
  Linux File Hierarchy
   linux have special file system than window
   file system is a directory structure that the os uses 
  cont 
     for windows system file appears under the local disk C
     for linux system file appears under root directory (/)

                FILE STRUCTURE IN DETAIL
   1 root(/)
      *Every single file and dictory starts from the root directory
      *Only root user has the right to write under this directory 
      */root is the user home dirctory.Which is not the same as
   2 bin-Binary executables
      *Essemtial command binaries that need to be available in single-user mode;for all users 
      e.g cat,ls,cp,pwd
   3/boot-Boot loader files
      * krenel initrd,vmlinux.grubfiles are located under /boot 

   4 /dev - Essential Device files 
      * these include terminal device,usb or any device attached to the system    
   5 /etc-et cetera
      * these contains configuration files required by all programs 

   6 /home -Home dirctory
      *Home Dirctory for all users to store their personal files 
   7 /lib 
      * Libraries essential for the binaries in /bin & /sbin Library filenames are either id or lib   
   8 /media 
      * Mount points for removable media such as CD-ROMs Temporay mount directory for removable devices 
   9 /mnt - Temporsrily mounted file 
      * Temporary mount directory where sysadmins can mount files system
  10 /opt - Optinal application software packages 
      * contains add on applications from individual vendors add on application should be installed under either /opt/ or /opt/ sub-directory     
  11 /sbin - Essential system binaries
      *Just like /bin,/sbin also contains binary executables the linux command located under this directory are used typically by system administratory,for system maintenance purpose 
  12 /tmp - temporary files
      * Directory that contains temporary files created by system and users Files under this directory are DELETED when system is rebooted  
  13 /usr - user Utilities
      *contains binaries,libraries,documentaion and source-code for second level programs   
                     TEXT EDITORS
       1 Programs That user for text processing
       2 Linux command line text editors
              * VIM
              * Nano
              * Emacs
              * Neovim
                    .... 
       3 Linux Graphical Text editors 
              * Sublime 
              * Vscode 
              * Gedit 
              * pluma  
                     ....
                   VIM 
    * Before vi the primary editor used editor used on UNIX was the line editor   
            * user was able to see/edit only one line of the text at a time  
    *Then vi editor imroved and developed VIM .(VI im proved) 
    *The vim editor is :                          
           * a very powerful
           * but at the same time it is cryptic
           * it is hard to learn,specially for windows users 
    * it have to modes
       - a command mode -- where you can do commands - input mode - where you can write   
         Opening vim
           syntax your filename 
     vim is by default command mode when you open it 
       To get on insert mode you press 'esc'
           inside command mode you can use this commands like 
               * To save :w + enter
               * To Quit : q + enter
               * To save & quit : wq! + enter
               * To force quite :q!
               * For undo : u + enter
               * To excute commands : %! and your command
                  NANO
     The GNU nano text editor is user -friendly,free and open-source text editor that usually commes pre-installed in modern linux systems
                  LINUX USER MANAGEMENT
     * On linux to create users you can use the following commands 
                * useradd - simple 
                *adduser -Detailed
     * Useradd command 
            * sudo useradd username
     *Adduser command 
            * sudo adduser user name 
                       TO ACCESS ROOT USER 
       the command
           *sudo su
       in root access our id is "0"
                                                                                    
