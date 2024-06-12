# my-project
CREATE DATABASE vyshdata;
CREATE USER 'vysh'@'%' IDENTIFIED BY 'revyshq';
GRANT ALL PRIVILEGES ON vyshdata.* TO 'vysh'@'%';
FLUSH PRIVILEGES;
