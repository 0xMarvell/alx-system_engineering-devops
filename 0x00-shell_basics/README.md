# SHELL BASICS
### 0-current_working_directory
 - This script prints prints the absolute path name of the current working directory.
 Example:
 ```
 $ ./0-current_working_directory
 /root/alx-system_engineering-devops/0x00-shell_basics
 $
 ```

### 1-listit
 - This script displays the contents list of your current directory.
 Example:
 ```
 $ ./1-listit
 Applications    Documents   Dropbox Movies Pictures
 Desktop Downloads   Library Music Public
 $
 ```

 ### 2-bring_me_home
  - This script changes the working directory to the user’s home directory.
  Example:
  ```
  julien@ubuntu:/tmp$ source ./2-bring_me_home
  julien@ubuntu:~$ pwd
  /home/julien
  julien@ubuntu:~$ 
  ```

### 3-listfiles
 - This script displays current directory contents in a long format.
 Example:
 ```
 $ ./3-listfiles
 total 32
 -rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:19 0-current_working_directory
 -rwxr-xr-x@ 1 sylvain staff 19 Jan 25 00:23 1-listit
 -rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:29 2-bring_me_home
 -rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:39 3-listfiles
 $
 ```