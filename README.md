
![preview](preview.png "screenshot")



### ssh-installer-termux
Easy setup of ssh server in Thermox (installer and automatic startup of ssh server and its prerequisites in Termux)

### What is ssh server? What is its use?
The use of ssh is that it provides you with the ability to connect to another device like a remote to your linux or termux terminal.
Today, there are few people who have worked with the Linux operating system and do not know this feature.

### What does this script do?

For those who are new to the Linux operating system, it is difficult to work with the Linux terminal and termux commands, and it may be difficult for them to install and run the ssh server.
That's why I developed this script to automate the setup of the ssh server.
I also included the guide to connect to the ssh server.

### Steps to install ssh server in termux
First, if you do not have the git package installed, send this command:

$ apt install git 

Now enter the following commands in order:

$ git clone https://github.com/eobardtawne/ssh-installer-termux-v1

$ cd ssh-installer-termux-v1

$ chmod +x ssh-install

$ bash ssh-install

$ cd && rm -fr ssh-installer-termux-v1

So easy to install successfully!
### Note: If there was a problem in downloading and installing, try again with vpn


