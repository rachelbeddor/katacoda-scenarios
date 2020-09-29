Set up Docker Env

## Before you start
Please note that these steps follow a tutorial available on Apache Kylin's website - [Tutorial Link](http://kylin.apache.org/docs/gettingstarted/kylin-quickstart.html)

## Task

Pull the Apache Kylin image from the Docker Repository

`docker pull apachekylin/apache-kylin-standalone:3.1.0`{{execute}}

Next, start the container by executing the following command: 

`docker run -d \
-m 8G \
-p 7070:7070 \
-p 8088:8088 \
-p 50070:50070 \
-p 8032:8032 \
-p 8042:8042 \
-p 16010:16010 \
apachekylin/apache-kylin-standalone:3.1.0`{{execute}}

The container will start shortly. 




