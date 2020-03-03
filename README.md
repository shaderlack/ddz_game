js斗地主游戏

服务器 : node.js

客户端:   cocos creator2.0

数据库 ：mysql
1.新建一个数据库名字ddz,导入帐号表,sql文件在ddz_server_node/sql下 
2.在服务器ddz_server_node增加配置db_config.js文件(这个配置没放到github因为里面记录了我的公网数据库信息) 
内容如下 
exports.dbconfig = { 
"host": "db的ip", 
"port": db端口, 
"user": "db账号", 
"password": "db的密码", 
"database": "db名称" 
}; 
3.保证测试机器上安装了node.js和nmp 
4.在命令行控制台cd到ddz_server_node目录下 
5.然后在控制台执行 nmp start 服务就启动了
![server](https://github.com/tinyshu/ddz_game/blob/master/image/1.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/2.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/3.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/4.png)



![server](https://github.com/tinyshu/ddz_game/blob/master/image/5.png)

​                        

​                            ![server](https://github.com/tinyshu/ddz_game/blob/master/image/6.png)

​					
