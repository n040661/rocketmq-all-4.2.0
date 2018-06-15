1. 修改配置文件在distribution/conf目录下

2. NamesrvStartup.java 添加JVM启动参数：
-Drocketmq.home.dir=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution
-Duser.home=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution

3. BrokerStartup.java添加JVM启动参数：
-Drocketmq.home.dir=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution
-Duser.home=D:\Work\code\spring\Cloud\rocketmq-all-4.2.0\distribution
-Drocketmq.namesrv.addr=localhost:9876