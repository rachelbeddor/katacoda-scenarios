This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

`echo 'Hello World'`{{execute}}

`docker pull apachekylin/apache-kylin-standalone:3.1.0`{{execute}}

`echo 'Hello World'`{{execute}}

`docker run -d \
-m 8G \
-p 7070:7070 \
-p 8088:8088 \
-p 50070:50070 \
-p 8032:8032 \
-p 8042:8042 \
-p 16010:16010 \
apachekylin/apache-kylin-standalone:3.1.0`{{execute}}

