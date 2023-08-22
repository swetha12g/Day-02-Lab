Installation of Linux Packages on new day 1 machine
sudo -i //to check sudo password
sudo apt update -y && upgrade -y 

Network Tool Commands
sudo apt install -y openssh-server //to install ssh server

ifconfig | grep inet // to know ip address of a machine

Git setup
sudo apt install git -y //to install git
git -h //to check wether it is installed or not
which git //to know where the package is installed 
git --version //to know which version of git or any other software is installed
git config --global user.name "name" //to give the username of git
git config --global user.email "email" // to give email 
git config --list //to know the details given on git


Git config settings
devops@devops:~/day-02-test$ git config -l
user.name=swetha12g
user.email=swetha12g@gmail.com
devops@devops:~/day-02-test$ git config --global
devops@devops:~/day-02-test$ git config --global --add url.https://github.com/.insteadof git://github.com/ 
devops@devops:~/day-02-test$ git config --global --add url.https://github.com/.insteadof git://github.com:
devops@devops:~/day-02-test$ git config --global --add url.https://<git-token>@github.com/.insteadof git://github.com/
devops@devops:~/day-02-test$ git config --global --add url.https://<git-token>@github.com/.insteadof git://github.com:
devops@devops:~/day-02-test$ git config -l
user.name=swetha12g
user.email=swetha12g@gmail.com
url.https://github.com/.insteadof=git://github.com/
url.https://github.com/.insteadof=git://github.com:
url.https://<git-token>@github.com/.insteadof=git://github.com/
url.https://<git-token>@github.com/.insteadof=git://github.com:

