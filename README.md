# 基于Socket的网络聊天室

Created on 2020-4-20<br/>
Author:<1252665997@qq.com><br/>
Version 1.0<br/>

## 环境依赖
>JDK1.8

## 部署步骤
>1.将该项目导入IDEA（注意：该项目的编码格式为GBK）  
>2.先运行server包下的CatServer.java，启动服务器  
>3.然后运行login包下的CatLogin.java，启动客户端，支持多用户聊天

## 项目结构
+ N422chat  
   + bean           将传输所需的全部数据封装在以下的两个实体类中
     + ClientBean
     + PacketBean
   + client
     + MyChatroom   聊天界面<br/>
   + login
     + MyLogin      登录界面<br/>
     + MyRegister   注册界面<br/>
   + server
     + MyServer     服务器端程序<br/>
   + util
     + MyUtil       封装了对文件加载，获取当前时间的操作<br/>
+ Users.properties // 存放用户名和密码

## V1.0.0版本内容
>登录界面<br/>
![login](https://github.com/markablely/OnlineChatting/tree/master/picture/login.png)
>注册账号<br/>
![register](https://github.com/markablely/OnlineChatting/tree/master/picture/register.png)
>聊天<br/>
![chatting](https://github.com/markablely/OnlineChatting/tree/master/picture/chatting.png)
>传输文件<br/>
![transmit](https://github.com/markablely/OnlineChatting/tree/master/picture/transmit.png)
