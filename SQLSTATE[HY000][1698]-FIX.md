```
DROP USER root@localhost;
CREATE USER root@localhost IDENTIFIED BY 'root_password';
GRANT ALL PRIVILEGES ON *.* TO 'root'@'localhost';
FLUSH PRIVILEGES;
```
