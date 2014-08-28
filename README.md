tomcat
======

Build:

docker build -t malderhout/centos7-tomcat7 .

Login:

docker run -i -t malderhout/centos7-tomcat7 /bin/bash

Run:

docker run -p 8080:8080 -d malderhout/centos7-tomcat7
