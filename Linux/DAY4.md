# Linux Practical Questions for DevOps Beginners
## Topics Covered
- SSH (Secure Shell)
- SCP (Secure Copy)
- Apache Web Server
- Nginx Web Server
- `find` Command
- `awk` Command
- `sed` Command
- `grep` Command




## Questions

### 1. SSH Login Setup
Set up passwordless SSH login from Server A to Server B using SSH key authentication. Verify that you can run remote commands from Server A on Server B.

### 2. File Transfer with SCP
Transfer a file named `index.html` from `/var/www/html/` on Server A to Server B’s same location using `scp`. Ensure the file is accessible through a web browser from Server B.

### 3. Running Apache and Nginx Simultaneously
Configure Apache  and Nginx simultaneously. Place separate `index.html` files in their document roots and verify both servers are running without conflict.

### 4. Search with grep
Search for all lines containing the word “error” (case-insensitive) in the `/var/log/syslog` file. Save the output to a file called `errors.txt`.

### 5. Find Command Usage
Find all `.log` files in `/var/log/` that were modified in the last 7 days and copy them to a directory called `recent-logs/`.

### 6. Process Text with awk
Given a file `users.csv` with the format `username,uid, gid, home`, print only the usernames and home directories using `awk`.

### 7. Replace Text with sed
You have a configuration file `/etc/nginx/nginx.conf`. Replace all occurrences of the word `localhost` with `127.0.0.1` using `sed` and create a backup of the original file.

### 8. Combined Command Use
Find all `.conf` files in `/etc/` that contain the word `server` and replace the word with `host` using a combination of `find`, `grep`, and `sed`.

### 9. Compare Server Logs
You have two log files, `server1.log` and `server2.log`. Use the `comm` command to find lines unique to each file.

### 10. Bonus: Web Server Setup Task
Set up a simple HTML page under `/var/www/html` that says "Welcome to DevOps!" and ensure it is served correctly via Nginx on port 80. Use `grep` to check access logs for incoming requests.

---

Practice these regularly to strengthen your Linux fundamentals in a DevOps context.
