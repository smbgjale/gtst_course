## Advanced Linux Users

> To change password of user
- suso passwd username

> To change user id
- sudo usermod -u new_id username

> To delete user
- sudo userdel -r username

> To change users on terminal 
- su - username


## sudoers file

- sudoers file is a file Linux and Unix administrators use to allocate system rights to system users.
- the user you created doesn't have power to use **sudo** as the original one. And this is because it is not added in the sudoers file.

> To access this file use the command 
- sudo visudo

# Linux file permission
> every file on linux have their own 
- owner
- permissions

> there is 5 main parts on the listing
- permission
- owners
- date
- size
- filename

## ownership
> ownership is the owner of the file 
- and it have two kinds
> - user
> - Group

> to change the owner of file you can use the command 
 - chown user:group filename

 ## permission
> There are **3** types of permissions 
> - Read(r) ---- "4"
> - Write(w) ---- "2"
> - Execute(x) ----  "1"



**![alt text](/picturesForGtst/chmod.png)**


# package installation on linux

- on linux to install softwares you use package managers 
> - apt
> - pacman
> - pkg

> we will be using debian package manager on debian the package manager is called **"APT"** and also their is another one called **"dpkg"**

## Advanced package tool (apt)

- the old "apt" used to be called "apt-get"
> - sudo apt update
> - sudo apt search softwarename
> - sudo apt install softwarename 
> - sudo apt remove softwarename
> - sudo apt upgrade
> - apt purge softwarename

## package dependencies

> a software can be built based on another program called "modules"


## Dpkg / Debian package manager/ 
> syntax
> - sudo dpkg -i packagename
> - sudo dpkg -r packagename
> - sudo dpkg -p packagename
>
>
