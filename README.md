# container_nginx

# running the container
bakr@bakr-virtual-machine:~/myproject$ docker run -d -p 8888:80 nginx
95312d3f5ea0aec07119b0dca749dff27196e229dc9203304c758ea19b2ff712

# check the container is running
bakr@bakr-virtual-machine:~/myproject$ docker ps
CONTAINER ID   IMAGE              COMMAND                  CREATED         STATUS         PORTS                                     NAMES
95312d3f5ea0   nginx              "/docker-entrypoint.…"   9 seconds ago   Up 7 seconds   0.0.0.0:8888->80/tcp, [::]:8888->80/tcp   priceless_ride
38e2989e655e   wordpress:latest   "docker-entrypoint.s…"   4 weeks ago     Up 22 hours    0.0.0.0:8000->80/tcp, [::]:8000->80/tcp   wordpress_wordpress_1
4de7058d9505   mysql              "docker-entrypoint.s…"   4 weeks ago     Up 22 hours    3306/tcp, 33060/tcp                       wordpress_mysql_db_1
bakr@bakr-virtual-machine:~/myproject$ ^C

