# use a node base image
FROM openjdk

# set maintainer
MAINTAINER Tushar Heda <tusharheda08@gmail.com>

ADD target/devopsTest-0.0.1-SNAPSHOT.jar devopsTest-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "/devopsTest-0.0.1-SNAPSHOT.jar"]

EXPOSE 8090