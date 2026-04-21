Executing multiple commands
- Each command will be executed one after other
    ```bash
    command1 ; command2 ; command3 ;
    ```
- Command2 will be executed only if command1 succeeds
    ```bash
    command1 && command2
    ```
- Command2 will not be executed if command1 succeeds
    ```bash
    command1 || command2
    ```

- Using parenthesis for to run the commands in bash subshell
    ```bash
    (ls ; date ; wc -l /etc/profile; )
    ```

- To inspect the 
    ```bash
    echo $BASH_SUBSHELL
    ```
    ```bash
    (echo $BASH_SUBSHELL)
    ```
File pointers
- stdin
- stdout
- stderr

- to redirect the output of command to file (overide the file)
    ```bash
    command > file1
    ```

- to redirect the output of the keyborad intput to the file1
    ```bash
    cat > file1
    ```

- to append the redirect the ouput of command to  file
    ```bash
    command >> file1
    ```

- to redirect the error message to file of command
    ```bash
    command 2> file1
    ```

- to redirect the error and output of command to different files
    ```bash
    command > file1 2> file2
    ```

Currently. I'm studying for the end sem of the my IIIT Dharwad exams. And today is the exam of Blockchain Techonolgy. 
In the blockchain I've studied for the bitcoin, ethereum and other less popular blockchin. Done workshop of NFT and CBDC.




