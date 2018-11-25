# xs-mysql
docker run -p 3306:3306 
--name xs-mysql 
-v /var/xs/mysql/conf:/etc/mysql/conf.d 
-v /var/xs/mysql/logs:/logs 
-v /var/xs/mysql/data:/var/lib/mysql 
-e MYSQL_ROOT_PASSWORD=R2poI8Q 
-d mysql:5.6
