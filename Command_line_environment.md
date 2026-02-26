- clear the screen
    ```bash
    clear    #or ctrl+l
    ```
- see the present working the directory
    ```bash
    pwd
    ```
- list the name the file or folders in the present directory
    ```bash
    ls
    ```
- What shell responding to our commands, we may want to list the processes that are currently running right now
    ```bash
    ps
    ```
- what OS we are using
    ```bash
    uname
    ```
- Come out of shell 
    ```bash
    exit        #or ctrl+D
    ```
- list the file in long format
    ```bash
    ls -l
    ```
- to see the manual pages for help
    ```bash
    man     #add argument with man e.g., man ls
    ```
- to move to home directory
    ```bash
    cd
    ```
- to move to same directory
    ```bash
    cd .
    ```
- to move to parent directory
    ```bash
    cd ..
    ```
- /bin      # Essential command binaries
- /boot     # Static files of the boot loader
- /dev      # Device files
- /etc      # Host specific system configuration
- /lib      # Essential shared libraries and kernel modules
- /media    # Mount points for removable devices
- /mnt      # Mount points
- /opt      # Add on application software packages
- /run      # Data relevant to running processes
- /sbin     # Essential system binaries
- /srv      # Data for services
- /usr      # Seceondary hierarchy
- /var      # Variable data

### /usr hierarchy
- /usr/bin      # User commands
- /usr/lib      # Libraries
- /usr/local    # Local hierarchy
- /usr/sbin     # Non-vital system binaries
- /usr/share    # Architecture dependent data
- /usr/include  # Header files included by C programs
- /usr/src      # Source code

### /var hierarchy   (for various log files)
- /var/cache    # Application cache data
- /var/lib      # Variable state information
- /var/local    # Variable data for /usr/local
- /var/lock     # Lock files
- /var/log      # Log files and directories
- /var/run      # Data relevant to running processes
- /var/temp     # Temporary files preserved between reboots

## Anatomy of a Linux Command

### Example:
```bash
user@machine:~$ ls -a
```

### Breakdown:

- **Command Prompt:** `user@machine:~$`
- **Username:** `user`
- **At Symbol:** `@`
- **Hostname:** `machine`
- **Colon:** `:`
- **Path:** `~`  
  > Indicates the directory where the command will be executed (here, Home directory)

- **Dollar Sign:** `$`  
  > Indicates a normal user. It signals that you can start typing a command.

- **Command:** `ls`
- **Option (Flag):** `-a`  
  > Lists all files, including hidden files (those starting with `.`)

