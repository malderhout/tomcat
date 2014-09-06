Tomcat7 with OpenJDK7 on CentOS7
======

Build:

docker build -t malderhout/tomcat .

Login:

docker run -i -t malderhout/tomcat /bin/bash

Run:

docker run -p 8080:8080 -d malderhout/tomcat
