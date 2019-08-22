# tomcat-8.5.43-src
tomcat-8.5.43-src 源碼
相关源码转pom博客：https://www.cnblogs.com/yangjiming/p/10953710.html

1)启动配置：
        Run Configurations:
            Main class: org.apache.catalina.startup.Bootstrap
            VM options: -XX:+UseSerialGC  -Dcatalina.home=C:/work/learn/source_place/source/apache/tomcat/tomcat-8.5.43-src  
                        -Dcatalina.base=C:/work/learn/source_place/source/apache/tomcat/tomcat-8.5.43-src  
                        -Djava.endorsed.dirs=C:/work/learn/source_place/source/apache/tomcat/tomcat-8.5.43-src/endorsed  
                        -Djava.io.tmpdir=C:/work/learn/source_place/source/apache/tomcat/tomcat-8.5.43-src/temp 
                        -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager 
                        -Djava.util.logging.config.file=C:/work/learn/source_place/source/apache/tomcat/tomcat-8.5.43-src/conf/logging.properties

