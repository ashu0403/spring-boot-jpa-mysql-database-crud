Docker command to run mysql : docker run -d --name mysql-container1  -e MYSQL_ROOT_PASSWORD=123456   -e MYSQL_DATABASE=testdb  -p 3306:3306  --restart unless-stopped  mysql:latest