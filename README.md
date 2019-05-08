# mybatis-reverse-project
mybatis逆向工程
过程如下
   1.配置数据库文件。
     在/resource/db.properties中。包括数据库的类型、地址、用户名和密码。
   2.配置表的相关信息。
     在/resource/generatorConfig.xml中。如使用默认配置，则配置<table>标签即可，如需自定义，参考配置文件注释。
   3.在idea的Plugins中执行mybatis-generator:generate -e(此处配置在idea右侧-maven-Execute Maven Goal)。
