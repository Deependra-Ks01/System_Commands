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

- list the file in long format
    ```bash
    ls -l
    ```