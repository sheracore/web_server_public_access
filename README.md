# web_server_public_access
### Command lines in your server(laptop)
#### We can user nginx or apache server
#### sudo apt install nginx
#### This command line show us our port and the listen ones
``` netstat -na (get all ports)```
``` netstat -na | grep LISTEN```
#### 0.0.0.0:80 (means with any ip you can get result on 80 port)
#### Config files is in ---> /etc/nginx and root path(default page) ---> /etc/nginx/sites-available (root /var/www/html) you can change it.
#### So go to you modem and go to its DMZ so add your ip adress that is nginx web server (port forwarding)
#### If it doesn't work you shout chage your nginx port in /etc/nginx/sites-available ---> listen
#### If your 80 port or any port banned by yout firewall you can get access to the special port by this command line
``` firewall-cmd --zone-public --add-port-8880/tcp ```
### Concept images

#### With some sites like dynamicdns and etc you can map your ip address to url link ( 178.252.130.42 ----> www.sheracore.com)
![GitHub Logo](/images/webserver_1.png)
From: ![jadi youtube](https://www.youtube.com/watch?v=vWvGNzjHH10)

![GitHub Logo](/images/webserver_2.png)
From: ![jadi youtube](https://www.youtube.com/watch?v=vWvGNzjHH10)

![GitHub Logo](/images/webserver_3.png)
From: ![jadi youtube](https://www.youtube.com/watch?v=vWvGNzjHH10)

#### With some sites like dynamicdns and etc you can map your ip address to url link ( 178.252.130.42 ----> www.sheracore.com)
![GitHub Logo](/images/webserver_4.png)
From: ![jadi youtube](https://www.youtube.com/watch?v=vWvGNzjHH10)

#### sudo apt install nginx
#### This command line show us our port and the listen ones
``` netstat -na (get all ports)```
``` netstat -na | grep LISTEN```
#### 0.0.0.0:80 (means with any ip you can get result on 80 port)
#### Config files is in ---> /etc/nginx and root path(default page) ---> /etc/nginx/sites-available (root /var/www/html) you can change it.
#### So go to you modem and go to its DMZ so add your ip adress that is nginx web server (port forwarding)
#### If it doesn't work you shout chage your nginx port in /etc/nginx/sites-available ---> listen
#### If your 80 port or any port banned by yout firewall you can get access to the special port by this command line
``` firewall-cmd --zone-public --add-port-8880/tcp ```

#### With some sites like dynamicdns and etc you can map your ip address to url link (i.e 178.252.130.42 : www.sheracore.com)
