Run below command to start the server

docker run -d --rm --name mysqldev -v .:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=mypw -p 3306:3306 mysql