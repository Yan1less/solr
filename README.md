# solr
服务于otakus系统的solr服务器
在solr是一个已经解压缩的war包，直接把它考到tomcat下就能运行
需要设置其solrhome的路径，在solr/WEB-INF/web.xml下搜索<env-entry-name>solr/home</env-entry-name>，改变其value
solrhome中data-config.xml指明了连接的数据库，schema.xml指明其域，solrconfig.xml中指明了需要读取data-config.xml配置文件
