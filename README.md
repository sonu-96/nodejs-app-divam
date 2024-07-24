# nodejs-app-divam
```
Step-1:- cloning the git into my local machine this process i entered the user and password detail to access this because it's a private repository. In this i got a application code which is written in nodejs language. where the dependencies were installed regardings the application.
ERROR:- in this process i facing a problem when i go to the vs code and clone to the repository it's not start clone but when i go in my terminal and start clone it's started and i get the code.
step-2:- i went to the directory where the code was store in this i create a copy of .env.example file to .env and enter this file and change the nodejs port to 5555.
step-3:- after this i installed require dependencies for nodejs application mysql,nginx,npm and nodejs
   sudo apt install mysql-server
   sudo apt install nginx
   sudo apt install npm
   for nodejs version 18.*
        curl -s https://deb.nodesource.com/setup_18.x | sudo bash
        npm install 18.0.0
ERROR:- after setup of nodejs and npm they are not shown in my directory after some searches i found the location was not define in path so i add this in path variables.
   for search the path of npm =  whereis npm
   then add into the path using = export PATH=$PATH:/usr/share/npm ### after this command " source ~/.bashrc " run.

step-4:- after this i setup the mysql root user password and cofigure the path of nodejs application directory to nginx configuration.

step-5:- go to the directory where stored the nodejs code and run it.
   npm i
   npm run dev
step-4:- for auto start server i add a pm2 process.
    sudo npm install -g pm2
    sudo pm2 start npm --name "website domain name" -- start
    sudo pm2 save
   for checking logs
      sudo pm2 logs 0 
```
