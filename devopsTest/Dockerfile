# use a node base image
FROM tomcat:latest

# set maintainer
MAINTAINER Tushar Heda <tusharheda08@gmail.com>

ADD devopsTest-0.0.1-SNAPSHOT.jar devopsTest-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "devopsTest-0.0.1-SNAPSHOT.jar"]

EXPOSE 8091

CMD ["catalina.sh", "run"]
