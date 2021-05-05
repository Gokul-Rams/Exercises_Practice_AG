
# Docker

# Note:
  Script files is written for all questions to make the task given
  Make sure that Dockerfile is present in current dir while executing exercise 5 scripts

# Docker Questions:

1) Spin up a temporary container with image nginx:1.19.10 and execute inside it, such that the container should be destroyed, once you exit from the container

2) Spin up a container with image nginx:1.19.10 such that it should restart automatically if any fatal errors are encountered

3) Spin up a container with image nginx:1.19.10 such that port 80 of the container can be connected from port 8080 of the host

4) Spin up a container with image redis:6.2.2 and mount volume /mnt/redis-data of host to the /data of the container

5) Create a dockerfile with base image centos:7 , and build an image with any sample application file

6) Create a bridge network called test-app and spin up nginx and redis containers in that network

# Kubernetes

# Note:
  Execute the script file to achive the task.
  Each exercise expect exercise 6,7,11 contains both yaml files and script files
  exercise 6,7,11 contains only script files, which is sufficient to achive task given
  exercise 12 contains 2 yaml files and 2 script files , one script to add local DNS record and another to execute the exercise

# Kubernetes Questions:

1) Create a pod called web-server with nginx:1.19.10 image

2) Expose port 80 of the web-server pod to be reachable within cluster

3) Create a single pod with below images:

     i) nginx:1.19.10

    ii) redis:6.2.2

4) Expose port 80 and 6379 of the above created pod such that the application can be connected from the outside world using node's IP address

5) Create a deployment web-deploy with nginx:1.19.10 image of 2 replica

6) Change the image of web-deploy to nginx:1.20.0 and record the change

7) Scale web-deploy to 5 replica

8) Create a persistent volume redis-pv with below specs:

   i) hostpath /mnt/redis/data

   ii) storage size 2Gi

   iii) access mode - ReadWriteOnce

9) Create a persistent volume claim redis-pvc that claims redis-pv persistent volume

10) Create a pod redis which binds the redis-pvc to the path /data with image redis:6.2.2

11) Update the storage size of the redis persistent volume to 3Gi and record the change

12) Create an Ingress for web-deploy deployment with wildcard hostname

# ShellScripts

# febanaci
Prints the fibonacci series

# memory game
Game to test your memory game, digits will be given to memorize and asked again

# dirlogger
create a log file in plain text or html format about your current directory

# checksitesstatus
Check weather the sites with given address are active or down

# fileascendingsort_ex1
Sort the given entries in the file 
note: only sort numbers

# exercise Dated 14/04/2021

# Exercise file names are in format ex<exno>_*
  
1. create /data directory and and create file named sample.txt with content "this is sample file" under the /data
2. create soft/symbolic link file named /tmp/sample.txt for the file /data/sample.txt
3. create script to find the file sample.txt and copy the file to /tmp/found.txt
4. create loop to check the file loop.txt availability in /data directory, once the file loop.txt created under /data directory the script should exit with status code 1
5. Find the file which contain localhost under the /etc folder and redirect output to /tmp/find.out and redirect error to /tmp/find.err
6. set open file limit to 10000
7. create swapfile with size 512MB
8. Create user named tuser with home directroy name /home/testuser and group named testgroup
9. Update umask value to get 644 permission for files and only for the user "tuser"
10. install apache2/HTTPD and the service should listen port 8080, when i access the webserver port number 8080 i should get "Welcome to Home Page" message
11. Parse a json file and extract value of a field from it
12. Write a nested script .i.e; Write a shell script file, say parent_file.sh. Inside that script invoke another script namely child_script.sh and run it as a background process. Parent script should be running foreground and should exit only after the child_script completes its operation
13. Create a service file and run a process(say any script) using it

Note:
ex no 13 contains two scripts one for creating the service file and another is the script the service executes.
ex 10 This exercise changes the ports.config and index.heml files of apache httpd 
