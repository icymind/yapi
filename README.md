# 新建数据库 volume

`sudo docker volume create mongo-data`

# 在数据库新建相关表

`sudo docker-compose -f init-db.yml up`

执行完毕后可以将相关 container 删除: `sudo docker-compose rm`

放心: 数据库 volume 不会删除

# 开始 yapi 服务

`sudo docker-compose up -d`
