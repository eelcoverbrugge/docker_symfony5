# docker_symfony5
Docker settings for a fresh symfony 5 install

Including containers:
- MySQL Database
- PHP-FPM
- NGINX

Instructions to fire up:
1. $ mkdir your_project_name
2. $ cd your_project_name
3. $ git clone git@github.com:eelcoverbrugge/docker_symfony5.git
4. $ symfony new src
5. $ cd docker
6. $ systemctl stop apache2
7. $ docker-compose up -d
8. $ cd ../src
9. $ git init
10. Create a new repository on Github
11. Follow further instructions on Github on how to push an existing repository from the command line
14. Go to http://localhost/

Source: https://dev.to/martinpham/symfony-5-development-with-docker-4hj8
