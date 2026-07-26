# **/** - root
    This is where all the other file systems are mounted .

# /usr 
    This dir contains user utilities 

# /sys & /proc
    This both dir are virtual file systems created at the startup of computer .
    It provides the info about current states of the computer components and processes
    that are currently running ...

# /bin & /sbin 
    This dir contains essential binary executables needed for basic computer operations,booting and recovery ...
# /dev 
    It contains files representing Hardware components ..

# /etc 
    System wide configuration files and scripts ..

# /boot
    This dir contatins files needed for computer to start the os including kernel and the    loader ...

# /home
    This is a user dir contains personal dir for each users and their files and their
    system settings and the personal configs ...

# /tmp & /var
    This both dir contains temporary and variable files and infos required for operations
    on the system ...


## Why do Linux Systems separate files into these directories instead of putting everything in one place ?

Because separating filesystems makes it easy to understand the kernel and makes it easier to debug and maintain the system ...
