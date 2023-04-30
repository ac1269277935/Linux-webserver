# Linux-webserver

该项目基于牛客网Linux高并发服务器开发系列课程，并持续优化更新得来，目前可以支持webbench8k并发，仍在优化中

项目背景：开发一个基于Linux的轻量级、高性能、多线程的web服务器
主要工作：  
1.利用I/O复用技术与EPOll线程池实现多线程的Proactor高并发服务器
2.利用正则表达式与有限状态机解析HTTP请求报文，实现处理静态资源的需求
主要成果：经过Webbench压力测试，可以稳定实现8k的并发连接数据交换
![image](https://user-images.githubusercontent.com/62527710/235332443-c5462519-ae8a-4d3f-ad95-81e0e27ac3fd.png)
