# AWS [EC2] README
## Uploading latest code on aws [EC2]

* Open putty on your system
* Add the your host name on the terminal as shown in figure 1.


    ![figure 1](https://github.com/shahbazahmad-96/aws/blob/main/images/img1.png?raw=true)

* Browse your downloaded key through clicking `SSH`, then click on `Auth` and then `Credentials` option following steps 1, 2 and 3 as shown in figure 2.

    ![figure 2](https://github.com/shahbazahmad-96/aws/blob/main/images/img2.png?raw=true)

* When terminal is opne, type `ec2-user` in the terminal as shown in figure 3.

    ![figure 3](https://github.com/shahbazahmad-96/aws/blob/main/images/img3.png?raw=true)

* After login, type the `sudo su` and `ls` in the terminal as shown in figure 4. You'll see your web code folder there.

    ![figure 4](https://github.com/shahbazahmad-96/aws/blob/main/images/img4.png?raw=true)

* Now you can clone and update your code here.
* To clone your repo, you can use the following command.

    ```
    git clone https://your-repo-url
    ```

* To remove a specific file/folder

    ```
    rm -rf file-name/folder-name
    ```

* To copy a file/folder

    ```
    cp -r source-file/source-folder destination-folder
    ```

* To install your `new packages` in the project

    ```
    cd your-project-folder
    npm install
    ```

* To start your project session

    ```
    npm start
    ```

* To start database server

    ```
    cd backend
    node server.js
    ```



