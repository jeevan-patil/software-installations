# software-installations

This document is to store guidelines to install most commonly used softwares on ubuntu operating system.

#### 1 Install latest nodejs

```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv 68576280
sudo apt-add-repository "deb https://deb.nodesource.com/node_8.x $(lsb_release -sc) main"
sudo apt-get update
sudo apt-get install nodejs
```

You can see node_8.x in the URL, replace it with the latest version available. To check if node is installed properly on the system, execute following command.

```
node -v
```
You should see output something like this

![alt text](https://github.com/jeevan-patil/software-installations/blob/master/pics/node.png)
