# scispark_zeppelin_web
Zeppelin with SciSpark skin
 
Download Zeppelin from its website
https://zeppelin.incubator.apache.org/download.html
Build to create WAR file

Copy the WAR file into local maven repo:
~/.m2/repository/org/apache/zeppelin/zeppelin-web/0.6.0-SNAPSHOT/

Git clone this repo and build
``` mvn clean package -DskipTests ```
