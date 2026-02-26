- To see current time stamp
    ```bash
    date
    ```
- To see the calander of current month
    ```bash
    cal     # to see calander of specific month cal Dec 2002
    ```
- To see the calander in different orientiation
    ```bash
    ncal
    ```
- To see the amount of memory free right now in the system
    ```bash
    free        # To make numbers human readable use cmd free -h
    ```
- To see what groups current user belongs to
    ```bash
    groups
    ```
### Typical output of ls -l
<p align="center">
  <img src="Assets/outputof_ls_-l.png" width="900" alt="Typical output of ls -l" />
</p>

### File type
- "-"      : Regular file
- "d"      : Directory
- "l"      : Symbolic link
- "c"      : Character file
- "b"      : Block file
- "s"      : Socket file
- "p"      : Named pipe

- inode is an entry in the filesystem table about the location in storage media and it'll be unique for every file. If multiple files have same inode then those are hard link

### Permission string 
- r     : read
- w     : write
- x     : execurable or if it's directory so it can be changing permission(entering dir)
<p align="center">
  <img src="Assets/permission_string.png" width="900" alt="Typical output of ls -l" />
</p>

- To create directory
    ```bash
    mkdir dir_name
    ```
- To remove the permission for file or directory
    ```bash
    chmod g-w level1        #we are removing the write permission of group of directory name level1. Use u: user, g: group, o: other
    ```
- To give the permission for file or directory
    ```bash
    chmod g+w level1        # We are giving the write permission to group of directory name level1. We use "+": to give, "-": to remove
    ```
- Use numerical for setting permissions
    ```bash
    chmod 700 level1
    ```
- To change the timestamp of last modified info about file or folder and file/folder dosen't exist it'll create it
    ```bash
    touch file1
    ```
- To copy a file to a new name
    ```bash
    cp file1 file2
    ```
- To move file
    ```bash
    mv      # To move to parent dir use "mv file2 .."; double dots used for parent directory; also can be use to change the name of file use cmd "mv file2 file2a"
    ```
- To remove the file
    ```bash
    rm      # Specify the name of the file after rm 
    ```
- To alias command
    ```bash
    alias rm="rm -i"
    ```
- To check the file listing in long listing formate with inode number (for hard link)
    ```bash
    ls -lia     # -l for long listing, -i for inode mumber and -a for . and .. file (all files)
    ```
- To check who am I (user using the system currently)
    ```bash
    whoami
    ```
- To read a file page by page
    ```bash
    less filename.log
    ```
- To check the type of file
    ```bash
    file        # Add filename aftet the command
    ```