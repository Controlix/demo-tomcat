# Issues

bitnami/tomcat 9 draait op java 11, spring-boor applicatie gebuild voor java 17 start niet op

tomcat 10 kan geen spring-boot 2 applicaties draaien

> docker run --rm -p 8080:8080 -e ALLOW_EMPTY_PASSWORD=yes -e TOMCAT_ALLOW_REMOTE_MANAGEMENT=yes --name tomcat bitnami/tomcat
> 
> docker cp target/demo-0.0.1-SNAPSHOT.war tomcat:/app

# Run with java 17 op tomcat 9

> docker run --rm -p 8080:8080 --name tomcat tomcat:9
> 
> docker cp target.demo.war tomcat:/usr/local/tomcat/webapps