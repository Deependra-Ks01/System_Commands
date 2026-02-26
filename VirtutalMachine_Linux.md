- Create public-private key pair using ssh-keygen
    ```bash
    ssh-keygen      # it will create ed key
    ssh-keygen -t rsa       # With type rsa
    ```

    // it will ask for the address
         by default it will be 
         (/home/mymac/.ssh/id_rsa)

    // it will ask for passphrase

    ```bash
    cat ~/.ssh/id_rsa.pub # to see the public key
    ```

- copy the public key to the server
    ```bash
    cat ~/.ssh/id_rsa.pub | xsel -ib # Will copy the public key to the clipboard
    ```


- For IIT Madras
    Paste the public key to the system command couse site
    // after that we can login with IITM VM
    ```bash 
    ssh studentemmail_id
    ```