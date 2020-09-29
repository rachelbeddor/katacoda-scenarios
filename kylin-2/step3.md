Figure out why 7070 (Kylin) Isn't Working

## Task 
Enter the container 

View your container by running 
`docker ps`{{execute}}

Find the name of your container and enter into the following command:

`docker exec -it <name_of_container> bash` 

Then, try to run `$KYLIN_HOME/bin/sample.sh`{{execute}} (should run automatically - test to see if run time supported)