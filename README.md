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
4. $ mv docker_symfony5 docker
5. $ symfony new src
6. $ cd docker
7. $ systemctl stop apache2
8. $ docker-compose up -d
9. $ cd ../src
10. $ composer install
11. $ git init
12. Create a new repository on Github.com
13. $ git remote add origin git@github.com:[your_repo_name]
14. $ git add .
15. $ git commit -m "Init"
16. $ git branch -M main
17. $ git push -u origin main
18. Go to http://localhost/

Source: https://dev.to/martinpham/symfony-5-development-with-docker-4hj8
