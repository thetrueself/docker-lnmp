# docker-lnmp
基于docker搭建的php开发环境

- 查看容器IP

```
 docker  inspect 9e87dd6022cd  | grep "IPAddress"
```

- mysql

```
docker-compose -f ./mysql.yml up -d
```

- redis

```
docker-compose -f ./redis.yml up -d
```
