# Getting started

## docker setting
```shell
$ docker pull mysql
$ docker images
$ docker image tag {target image id} inflearn-stock
$ docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=1234 --name inflearn-stock inflearn-stock 
```

## mysql create table
```shell
$ docker exec -it inflearn-stock bash
$ mysql -u root -p
$ create database stock;
$ use stock;
```
