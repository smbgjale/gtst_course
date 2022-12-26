# 🔚Finishing for Linux🔚

## script installation

> some hacking tools are developed by some peoples and those peoples make it open-source, and that means we can get those scripts( programs) from github.

> - git clone **"link"**

scripts are made with scripting languages like {python,bash,go,ruby,....}

## python installation

- pip install term

### if you need help on linux about commands
> use the command 
> - man(manual)
> > - This will give you the whole manual and instruction of a tool or command.
> - help
> > - This will give you a help option about the command if it have any
## linux processes & services

> as we interact with linux, we create numberd instances of running programs called "processes"
> - to get the processes
> > - ps [options ]

- ps -> for process running on my shell
- ps-A -> view all running processes
- ps-u username -> view users process
> To stop processes 
> - kill [options ] [pid ]
> - kill-19 PID --> to stop the process
> - kill-18 PID --> to resume the process we stopped
> - kill-9 PID --> to stop a process immediately


### to kill on htop
 
- after you opened htop search for the process that you want and then kill it using its PID


### Forground / Background

> to run programs in the **background** use the **"&"** operator or press **"^z"**

> - to get the backgound proccess back to the foreground 
> - press **"fg"**


## alias
> used to give a name to some bunch of commands.

## Tmux - Terminal multiplexer

- used to classify our terminal work

> - use the syntax down below after you create config file type
> > - nano .tmux.conf
> > > - then write the below code in the file 
> > - **![alt text](/picturesForGtst/conf%20code.png)**


### Then use the bellow commands to navigate through the **tmux**
> the below
**![alt text](/picturesForGtst/commands%20for%20tmux.png)**


### wget

> is a tool used to download files from webistes or servers

### find
> to find for any file/folder/music/videos 
