FROM 192.168.230.147:8081/docker-virtual/docker-framework:latest

MAINTAINER guoyunzong gyzong1@163.com

ADD war/*.war /home/apache-tomcat-8.5.37/webapps/swampup.war

CMD /bin/bash -c cd /home; /home/apache-tomcat-8.5.37/bin/catalina.sh run
