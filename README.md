# software-installations

This document is to store guidelines to install most commonly used softwares on ubuntu operating system.

#### 1 Installing Oracle JDK
```
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```

for Java 6, use ``` sudo apt-get install oracle-java6-installer ```
for Java 7, use ``` sudo apt-get install oracle-java7-installer ```

To check if it's installed properly, use java -version command. You should something like - 
![alt text](https://github.com/jeevan-patil/software-installations/blob/master/pics/java.png)

#### 2 Install latest nodejs

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

#### 3 Install Shutter - Screenshot tool

To install:
```
sudo add-apt-repository ppa:shutter/ppa
sudo apt-get update && sudo apt-get install shutter
```
To Uninstall:
```
sudo apt-get remove shutter
```
