1. 修改配置文件在distribution/conf目录下

2. NamesrvStartup.java 添加JVM启动参数：
-Drocketmq.home.dir=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution
-Duser.home=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution

3. BrokerStartup.java添加JVM启动参数：
-Drocketmq.home.dir=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution
-Duser.home=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution
-Drocketmq.namesrv.addr=localhost:9876


参考：
一致性：
https://blog.csdn.net/iie_libi/article/details/54236300
https://blog.csdn.net/zyw23zyw23/article/details/79070044

源码分析：https://yq.aliyun.com/articles/61141

视频：
http://blog.sina.com.cn/s/blog_693f08470102vibt.html