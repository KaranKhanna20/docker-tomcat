tomcat7
==================

docker image for tomcat7 (with OpenJDK JRE)
based off of stackbrew/debian:jessie

To deploy a specific .war file to ROOT, see the commented out section of the `Dockerfile`.

The following environment variables can be passed to the docker image:

`ADMIN_USER` (default: admin)

`ADMIN_PASS` (default: tomcat)

`MAX_UPLOAD_SIZE` (default: 52428800)

`CATALINA_OPTS` (default: "-Xms128m -Xmx1024m -XX:PermSize=128m -XX:MaxPermSize=256m")


Go to Web browser to see the sample.war content: http://localhost:8080/
