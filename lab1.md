# Lab Report 1 - Remote Access and FileSystem
This lab report is meant to help with breaking down the process to complete three aspects of the lab which are as follows: **installation of VScode**, **remotely connecting to the server**, and **using some commands in the terminal**.

## Installing VScode
* Start by going to the [VScode official website](https://code.visualstudio.com/). Follow the instructions on the site to install.

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20%20vscode%20landing.png)

* When opened, VScode should look something similar to the image below.

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20vscode%20opened.png)

* You should make sure that Java is installed on the device by [following the instructions on Java's site](https://www.java.com/en/download/help/version_manual.html). If you do not have Java downloaded, you can [download it from the official site](https://www.java.com/en/download/). Follow the download instructions on the site.

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20java%20page.png)

## Remotely Connecting
* [Download git](https://git-scm.com/downloads) if you do not already have it from the developer's site. You can check if you have git by using the built in terminal on your computer. You can use the search option to look for your terminal on your device. You shell may not be in bash to start so type in `bash` to change the type to bash if it's set to something else. Then type in `git --version`. If you do not get a version back, then you do not have git installed.

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20mac%20terminal.png)

* Open VScode's terminal by using the Ctrl (Windows) or control (Apple) along with the backtick key (\`). Then, sign in using **cse15lwi23(your special letters)@ieng6.ucsd.edu and your AD password**. You will need to reset the password in order to sign into the new account. You can [follow the steps on the UCSD Educational Technology Services page](https://sdacs.ucsd.edu/~icc/index.php), starting with account lookup and then changing the password as instructed. Note: while inputting your password, it records your keystrokes but the bar will not move to show you how many characters you have already typed. Once you finish typing your password, you should hit the Enter (Windows) or return (Mac) key.

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20ssh%20login.png)

* If it asks you if you wish to connect to the server, you should select the yes option.

## Running Commands in Terminal
* The commands can be run in the VScode terminal while logged into the ieng account or logged out. While still logged into the ieng account, you can try out all the commands listed such as `cd`, `ls`, `pwd`, `mkdir`, and `cp`. More specific variations from the lab instructions include `cd ~`; `cd`; `ls -lat`; `ls -a`; `ls /home/linux/ieng6/cs15lwi23/cs15lwi23abc`, replacing abc with a different string of letters such as a group members’ username;
`cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`; `cat /home/linux/ieng6/cs15lwi23/public/hello.txt`.

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20not%20mac.png)

* To run the commands for your device and not the remote access account, you can hit Ctrl (Windows) or control (Mac) and D in order to sign out. From there you can run the same commands and see what comes up. 

![Image](https://raw.githubusercontent.com/aerin-c/cse15l-lab-report/main/lab1images/lab%201%20-%20mac.png)
