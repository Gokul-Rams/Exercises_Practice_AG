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
