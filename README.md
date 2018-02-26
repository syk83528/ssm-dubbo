# ssm-dubbo
基于dubbo通信的ssm模块化框架

##运行前提:
数据库sql文件在项目中,数据库名为e3mall,自己跑一下sql,生成表
zookeeper解压到自定义的一个文件夹下,然后根据我之前提及的教程启动.
zookeeper监控中心用我项目中的那个dubbo-admin.war,放到tomcat服务器中启动
注意! tomcat启动监控中心的话,注意端口号的区分,我监控中心用的8080,服务端8082,web端用8081

maven本地仓库我也放上去,如果需要的话就放到自己的本地,注意修改maven中setting.xml那个本地路径.如果不用的话就自己想idea中下载三方依赖


最后,解压那个e3-mall压缩包,那个就是整个项目.
