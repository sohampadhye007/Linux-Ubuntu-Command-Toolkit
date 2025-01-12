# Top 50 Ubuntu Commands with Examples


Welcome to the **Ubuntu Commands Guide** repository!  

Ubuntu is one of the most popular Linux distributions, known for its stability, security, and flexibility. Whether you're a software developer, system administrator, or an enthusiast exploring Linux for the first time, mastering Ubuntu commands is essential to making the most of this powerful operating system.  

### Ubuntu and Robotics  
Ubuntu is the preferred operating system for robotics development, offering seamless support for the Robot Operating System (ROS). Its rich ecosystem of libraries, tools, and software makes it indispensable for robot-related operations, automation, and control. From prototyping robotic systems to deploying them in real-world applications, Ubuntu provides the foundation needed for efficient and reliable development.  

### How This Guide Helps You  
This repository is designed for anyone starting their journey with Ubuntu. It covers:  
- **Essential commands**: Navigate the filesystem, manage files, and control processes.  
- **Advanced tools**: Automate tasks, configure the system, and analyze performance.  
- **Practical examples**: Each command is explained with examples and expected outputs, making it easier to understand and apply in real scenarios.  

Whether you're transitioning from another operating system or diving into robotics and automation, this guide will help you unlock the full potential of Ubuntu.  


## 1. `ls`
**Description:** Lists files and directories in the current directory.
- **Example Input:** `ls`
- **Expected Output:** 
  ```
  file1.txt  file2.txt  folder1  folder2
  ```

- **Example Input:** `ls -l`
- **Expected Output:**
  ```
  drwxr-xr-x 2 user user 4096 Jan 12 10:00 folder1
  -rw-r--r-- 1 user user  123 Jan 12 10:10 file1.txt
  ```

---

## 2. `cd`
**Description:** Changes the current directory.
- **Example Input:** `cd /home/user/Documents`
- **Expected Output:** Changes the working directory to `/home/user/Documents`.

- **Example Input:** `cd ..`
- **Expected Output:** Moves up one directory level.

---

## 3. `pwd`
**Description:** Prints the current working directory.
- **Example Input:** `pwd`
- **Expected Output:**
  ```
  /home/user/Documents
  ```

---

## 4. `touch`
**Description:** Creates an empty file.
- **Example Input:** `touch file.txt`
- **Expected Output:** Creates a file named `file.txt` in the current directory.

---

## 5. `mkdir`
**Description:** Creates a new directory.
- **Example Input:** `mkdir new_folder`
- **Expected Output:** Creates a folder named `new_folder`.

- **Example Input:** `mkdir -p folder/subfolder`
- **Expected Output:** Creates a folder and its subfolder in one command.

---

## 6. `rm`
**Description:** Deletes files or directories.
- **Example Input:** `rm file.txt`
- **Expected Output:** Deletes `file.txt`.

- **Example Input:** `rm -r folder`
- **Expected Output:** Recursively deletes `folder` and its contents.

---

## 7. `cp`
**Description:** Copies files or directories.
- **Example Input:** `cp source.txt destination.txt`
- **Expected Output:** Copies `source.txt` to `destination.txt`.

- **Example Input:** `cp -r source_folder/ destination_folder/`
- **Expected Output:** Copies `source_folder` to `destination_folder`.

---

## 8. `mv`
**Description:** Moves or renames files and directories.
- **Example Input:** `mv old_name.txt new_name.txt`
- **Expected Output:** Renames `old_name.txt` to `new_name.txt`.

- **Example Input:** `mv file.txt /path/to/destination/`
- **Expected Output:** Moves `file.txt` to `/path/to/destination/`.

---

## 9. `cat`
**Description:** Displays the content of a file.
- **Example Input:** `cat file.txt`
- **Expected Output:** Displays the content of `file.txt`.

---

## 10. `nano`
**Description:** Opens a file in the Nano text editor.
- **Example Input:** `nano file.txt`
- **Expected Output:** Opens `file.txt` in Nano for editing.

---

## 11. `vim`
**Description:** Opens a file in the Vim text editor.
- **Example Input:** `vim file.txt`
- **Expected Output:** Opens `file.txt` in Vim for editing.

---

## 12. `find`
**Description:** Searches for files and directories.
- **Example Input:** `find /home/user -name "file.txt"`
- **Expected Output:**
  ```
  /home/user/Documents/file.txt
  ```

---

## 13. `grep`
**Description:** Searches for text within files.
- **Example Input:** `grep "error" log.txt`
- **Expected Output:** Displays lines in `log.txt` containing "error".

---

## 14. `df`
**Description:** Displays disk space usage.
- **Example Input:** `df -h`
- **Expected Output:**
  ```
  Filesystem      Size  Used Avail Use% Mounted on
  /dev/sda1        50G   10G   40G  20% /
  ```

---

## 15. `du`
**Description:** Displays disk usage of files and directories.
- **Example Input:** `du -sh folder`
- **Expected Output:**
  ```
  1.2G    folder
  ```

---

## 16. `top`
**Description:** Displays real-time system resource usage.
- **Example Input:** `top`
- **Expected Output:** Interactive display of processes, memory, and CPU usage.

---

## 17. `htop`
**Description:** Interactive process viewer (requires installation).
- **Example Input:** `htop`
- **Expected Output:** Interactive display of processes with a better interface than `top`.

---

## 18. `ps`
**Description:** Displays currently running processes.
- **Example Input:** `ps aux`
- **Expected Output:**
  ```
  USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
  user      1234  0.0  0.1  123456  1234 ?        S    10:00   0:00 /usr/bin/python3
  ```

---

## 19. `kill`
**Description:** Terminates a process by its PID.
- **Example Input:** `kill 1234`
- **Expected Output:** Terminates the process with PID 1234.

---

## 20. `wget`
**Description:** Downloads files from the internet.
- **Example Input:** `wget https://example.com/file.zip`
- **Expected Output:** Downloads `file.zip` to the current directory.

---

## 21. `curl`
**Description:** Transfers data from or to a server.
- **Example Input:** `curl https://example.com`
- **Expected Output:** Displays the content of the webpage.

---

## 22. `chmod`
**Description:** Changes file permissions.
- **Example Input:** `chmod 755 script.sh`
- **Expected Output:** Changes permissions of `script.sh` to `755`.

---

## 23. `chown`
**Description:** Changes file owner and group.
- **Example Input:** `chown user:group file.txt`
- **Expected Output:** Changes the owner of `file.txt` to `user` and group to `group`.

---

## 24. `locate`
**Description:** Quickly finds a file by name.
- **Example Input:** `locate file.txt`
- **Expected Output:**
  ```
  /home/user/Documents/file.txt
  ```

---

## 25. `tar`
**Description:** Archives files into a `.tar` file.
- **Example Input:** `tar -cvf archive.tar folder`
- **Expected Output:** Creates `archive.tar` containing `folder`.

---

## 26. `zip`
**Description:** Compresses files into a `.zip` file.
- **Example Input:** `zip archive.zip file.txt`
- **Expected Output:** Creates `archive.zip` containing `file.txt`.

---

## 27. `unzip`
**Description:** Extracts files from a `.zip` archive.
- **Example Input:** `unzip archive.zip`
- **Expected Output:** Extracts files in `archive.zip` to the current directory.

---

## 28. `ssh`
**Description:** Connects to a remote server via SSH.
- **Example Input:** `ssh user@server.com`
- **Expected Output:** Opens a remote shell session with `server.com`.

---

## 29. `scp`
**Description:** Copies files between local and remote machines.
- **Example Input:** `scp file.txt user@server.com:/path/to/destination/`
- **Expected Output:** Copies `file.txt` to the specified path on the remote server.

---

## 30. `rsync`
**Description:** Synchronizes files and directories.
- **Example Input:** `rsync -av source/ destination/`
- **Expected Output:** Copies all files from `source/` to `destination/` while preserving permissions.

---

## 31. `history`
**Description:** Displays the command history.
- **Example Input:** `history`
- **Expected Output:**
  ```
  1  ls
  2  cd folder
  3  cat file.txt
  ```

---

## 32. `alias`
**Description:** Creates shortcuts for commands.
- **Example Input:** `alias ll='ls -la'`
- **Expected Output:** You can now use `ll` as a shortcut for `ls -la`.

---

## 33. `df`
**Description:** Displays disk space usage.
- **Example Input:** `df -h`
- **Expected Output:**
  ```
  Filesystem      Size  Used Avail Use% Mounted on
  /dev/sda1        50G   10G   40G  20% /
  ```

---

## 34. `free`
**Description:** Displays memory usage.
- **Example Input:** `free -h`
- **Expected Output:**
  ```
                total        used        free      shared  buff/cache   available
  Mem:           15G         4G         8G         1G         3G         10G
  Swap:           2G        512M        1.5G
  ```

---

## 35. `uptime`
**Description:** Displays system uptime.
- **Example Input:** `uptime`
- **Expected Output:**
  ```
  10:00:00 up 5 days,  2:34,  3 users,  load average: 0.00, 0.01, 0.05
  ```

---

## 36. `whoami`
**Description:** Displays the current username.
- **Example Input:** `whoami`
- **Expected Output:**
  ```
  user
  ```

---

## 37. `id`
**Description:** Displays user and group IDs.
- **Example Input:** `id`
- **Expected Output:**
  ```
  uid=1000(user) gid=1000(user) groups=1000(user),27(sudo)
  ```

---

## 38. `passwd`
**Description:** Changes the user password.
- **Example Input:** `passwd`
- **Expected Output:** Prompts to enter a new password.

---

## 39. `echo`
**Description:** Displays a string or variable value.
- **Example Input:** `echo Hello, World!`
- **Expected Output:**
  ```
  Hello, World!
  ```

---

## 40. `env`
**Description:** Displays environment variables.
- **Example Input:** `env`
- **Expected Output:** Displays a list of environment variables.

---

## 41. `export`
**Description:** Sets environment variables.
- **Example Input:** `export VAR=value`
- **Expected Output:** Sets the environment variable `VAR` to `value`.

---

## 42. `source`
**Description:** Executes a script in the current shell.
- **Example Input:** `source script.sh`
- **Expected Output:** Executes `script.sh` in the current shell.

---

## 43. `crontab`
**Description:** Schedules periodic tasks.
- **Example Input:** `crontab -e`
- **Expected Output:** Opens the crontab editor to schedule tasks.

---

## 44. `systemctl`
**Description:** Manages system services.
- **Example Input:** `systemctl status apache2`
- **Expected Output:** Displays the status of the `apache2` service.

---

## 45. `journalctl`
**Description:** Views system logs.
- **Example Input:** `journalctl -u apache2`
- **Expected Output:** Displays logs for the `apache2` service.

---

## 46. `dmesg`
**Description:** Displays kernel ring buffer messages.
- **Example Input:** `dmesg | grep error`
- **Expected Output:** Displays kernel errors.

---

## 47. `ifconfig`
**Description:** Displays or configures network interfaces.
- **Example Input:** `ifconfig`
- **Expected Output:** Displays network interface information.

---

## 48. `ip`
**Description:** Displays or manages IP addresses and routes.
- **Example Input:** `ip addr show`
- **Expected Output:**
  ```
  1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
      inet 127.0.0.1/8 scope host lo
      valid_lft forever preferred_lft forever
  ```

---

## 49. `ping`
**Description:** Tests network connectivity.
- **Example Input:** `ping google.com`
- **Expected Output:**
  ```
  PING google.com (142.250.72.14) 56(84) bytes of data.
  64 bytes from google.com: icmp_seq=1 ttl=118 time=14.8 ms
  ```

---

## 50. `traceroute`
**Description:** Displays the route packets take to a network host.
- **Example Input:** `traceroute google.com`
- **Expected Output:**
  ```
  traceroute to google.com (142.250.72.14), 30 hops max, 60 byte packets
   1  192.168.1.1 (192.168.1.1)  1.123 ms  1.098 ms  1.078 ms
   2  ...
  ```


