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